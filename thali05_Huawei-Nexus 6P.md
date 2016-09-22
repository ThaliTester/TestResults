#### Test 86147834a13d096_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-22 06:57:39.470   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-22 06:57:41.579  5396  5396 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 06:57:41.585  5396  5396 D AndroidRuntime: CheckJNI is OFF
09-22 06:57:41.616  5396  5396 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 06:57:41.651  5396  5396 I Radio-JNI: register_android_hardware_Radio DONE
09-22 06:57:41.666  5396  5396 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-22 06:57:41.669   929  3392 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-22 06:57:41.715   929  3392 I ActivityManager: Start proc 5405:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-22 06:57:41.729  5396  5396 D AndroidRuntime: Shutting down VM
,09-22 06:57:42.055   929  3547 I WindowManager: Screenshot max retries 4 of Token{d28d52c ActivityRecord{e0f24df u0 com.test.thalitest/.MainActivity t2}} appWin=Window{3b2d0d7 u0 Starting com.test.thalitest} drawState=2
,09-22 06:57:42.121  5405  5405 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-22 06:57:42.159  5405  5405 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-22 06:57:42.180  5405  5405 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 7098-7116)
,09-22 06:57:42.181  5405  5405 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-22 06:57:42.199  5405  5405 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6b8248b}
,09-22 06:57:42.200  5405  5405 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-22 06:57:42.200  5405  5405 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-22 06:57:42.205  5405  5405 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-22 06:57:42.206  5405  5405 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-22 06:57:42.240  5405  5405 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-22 06:57:42.260  5405  5405 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-22 06:57:42.261  5405  5405 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 06:57:42.261  5405  5405 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-22 06:57:42.261  5405  5405 I Adreno  : Build Date                       : 12/06/15
09-22 06:57:42.261  5405  5405 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-22 06:57:42.261  5405  5405 I Adreno  : Local Branch                     : mybranch17112971
09-22 06:57:42.261  5405  5405 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-22 06:57:42.261  5405  5405 I Adreno  : Remote Branch                    : NONE
09-22 06:57:42.261  5405  5405 I Adreno  : Reconstruct Branch               : NOTHING
,09-22 06:57:42.301   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@add3a:true
,09-22 06:57:42.325  3972  3972 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[16071]" dev="sockfs" ino=16071 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 06:57:42.325  3972  3972 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[16071]" dev="sockfs" ino=16071 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 06:57:42.339  5405  5405 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-22 06:57:42.347  5405  5405 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-22 06:57:42.368  3972  3972 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31785]" dev="sockfs" ino=31785 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 06:57:42.368  3972  3972 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31785]" dev="sockfs" ino=31785 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 06:57:42.371  5405  5442 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-22 06:57:42.371  3127  3127 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15075]" dev="sockfs" ino=15075 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 06:57:42.371  3127  3127 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15075]" dev="sockfs" ino=15075 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 06:57:42.376  5405  5429 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-22 06:57:42.396  5405  5442 I OpenGLRenderer: Initialized EGL, version 1.4
,09-22 06:57:42.474   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +417ms (total +782ms)
,09-22 06:57:42.518  5405  5405 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5405
,09-22 06:57:42.601  5405  5405 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-22 06:57:42.722  5405  5444 D jxcore_app_log: JniHelper::setJavaVM(0xf517c000), pthread_self() = -579864272
,09-22 06:57:42.725  5405  5444 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 06:57:42.725  5405  5444 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 06:57:42.725  5405  5444 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 06:57:42.725  5405  5444 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 06:57:42.725  5405  5444 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-22 06:57:42.725  5405  5444 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf5da40 added. We now have 1 listener(s)
09-22 06:57:42.728  5405  5444 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-22 06:57:42.728  5405  5444 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:57:42.729  5405  5444 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:57:42.729  5405  5444 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-22 06:57:42.731  5405  5444 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95e771f added. We now have 1 listener(s)
,09-22 06:57:42.731  5405  5444 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 06:57:42.736   929  2944 D WifiService: New client listening to asynchronous messages
,09-22 06:57:42.736  5405  5444 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 06:57:42.736  5405  5444 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-22 06:57:42.736  5405  5444 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-22 06:57:42.736  5405  5444 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 06:57:42.736  5405  5444 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-22 06:57:42.738  5405  5444 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:57:42.738  5405  5444 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-22 06:57:42.742  5405  5444 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-22 06:57:42.743  5405  5444 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:57:42.743  5405  5444 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:57:42.743  5405  5444 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:57:42.743  5405  5444 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:57:42.743  5405  5444 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:57:42.743  5405  5444 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:57:42.743  5405  5444 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:57:42.743  5405  5444 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:57:42.743  5405  5444 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 06:57:42.743  5405  5444 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:57:42.743  5405  5444 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-22 06:57:42.747  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:57:42.753  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:57:42.765  5405  5405 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 06:57:43.076  5405  5452 W jxcore-log: Initializing JXcore engine
09-22 06:57:43.076  5405  5452 W jxcore-log: JXcore engine is ready
,09-22 06:57:43.098  5452  5452 W Thread-58: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11836 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-22 06:57:43.098  5452  5452 W Thread-58: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16392]" dev="sockfs" ino=16392 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-22 06:57:43.098  5452  5452 W Thread-58: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-22 06:57:43.098  5452  5452 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31104]" dev="sockfs" ino=31104 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-22 06:57:43.105  5405  5414 I art     : Background sticky concurrent mark sweep GC freed 86310(8MB) AllocSpace objects, 18(1892KB) LOS objects, 26% free, 24MB/32MB, paused 2.799ms total 113.781ms
,09-22 06:57:43.108  5405  5452 W jxcore-log: Starting JXcore engine
,09-22 06:57:43.166  5405  5452 W jxcore-log: Platform android
09-22 06:57:43.166  5405  5452 W jxcore-log: 
,09-22 06:57:43.166  5405  5452 W jxcore-log: Process ARCH arm
09-22 06:57:43.166  5405  5452 W jxcore-log: 
,09-22 06:57:43.268  5405  5452 I jxcore-log: JXcore Cordova bridge is ready!
09-22 06:57:43.268  5405  5452 I jxcore-log: 
,09-22 06:57:43.268  5405  5452 W jxcore-log: JXcore engine is started
,09-22 06:57:43.278  5405  5444 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 06:57:43.283  5405  5405 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 06:57:46.822   929  2943 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 06:57:52.862  5405  5452 I jxcore-log: 2016-09-22 10:57:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-22 06:57:52.862  5405  5452 I jxcore-log: 
,09-22 06:57:52.864  5405  5452 I jxcore-log: 2016-09-22 10:57:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-22 06:57:52.864  5405  5452 I jxcore-log: 
,09-22 06:57:52.869  5405  5452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:57:52.869  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:57:52.869  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:57:52.869  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:57:52.869  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:57:52.869  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:57:52.869  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:57:52.869  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 06:57:52.870  5405  5452 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 06:57:52.872  5405  5452 I jxcore-log: 2016-09-22 10:57:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-22 06:57:52.872  5405  5452 I jxcore-log: 
,09-22 06:57:52.874  5405  5452 I jxcore-log: 2016-09-22 10:57:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-22 06:57:52.874  5405  5452 I jxcore-log: 
,09-22 06:57:53.126  5405  5452 I jxcore-log: Running unit tests
09-22 06:57:53.126  5405  5452 I jxcore-log: 
,09-22 06:57:53.126  5405  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 06:57:53.126  5405  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6180067 added. We now have 2 listener(s)
09-22 06:57:53.127  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 06:57:53.127  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:57:53.127  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 06:57:53.127  5405  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:57:53.127  5405  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f01be14 added. We now have 2 listener(s)
09-22 06:57:53.127  5405  5452 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:57:53.128  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 06:57:53.130  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:57:53.133  5405  5452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:57:53.133  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:57:53.133  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:57:53.133  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:57:53.133  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:57:53.133  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:57:53.133  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:57:53.133  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 06:57:53.134  5405  5452 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 06:57:53.135  5405  5452 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:57:53.135  5405  5452 D executeNativeTests: Running unit tests
,09-22 06:57:53.142  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:57:53.148  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:57:53.171  5405  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 06:57:53.171  5405  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1960e62 added. We now have 3 listener(s)
09-22 06:57:53.172  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:57:53.172  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 06:57:53.172  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 06:57:53.172  5405  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 06:57:53.172  5405  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 added. We now have 3 listener(s)
09-22 06:57:53.172  5405  5452 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 06:57:53.172  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 06:57:53.174  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:57:53.176  5405  5452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:57:53.176  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:57:53.176  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:57:53.176  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:57:53.176  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:57:53.176  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:57:53.176  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:57:53.176  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:57:53.177  5405  5452 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 06:57:53.177  5405  5452 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 06:57:53.178  5405  5452 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-22 06:57:53.178  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-22 06:57:53.178  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-22 06:57:53.178  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 06:57:53.179  5405  5452 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-22 06:57:53.179  5405  5452 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 06:57:53.179  5405  5452 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 06:57:53.179  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 06:57:53.179  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 06:57:53.179  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 06:57:53.180  5405  5452 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 06:57:53.180  5405  5452 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:57:53.180  5405  5452 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:57:53.180  5405  5452 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 06:57:53.180  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:57:53.181  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:57:53.181  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 06:57:53.181  5405  5452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1960e62 removed from the list
09-22 06:57:53.181  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:57:53.181  5405  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 removed from the list
09-22 06:57:53.182  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:57:53.186  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:57:53.187  5405  5452 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 06:57:53.187  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:57:53.187  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:57:53.187  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:57:53.188  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:57:53.188  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:57:53.188  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:57:53.188  5405  5452 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 not in the list
09-22 06:57:53.189  5405  5452 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-22 06:57:53.189  5405  5452 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 06:57:53.189  5405  5452 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:57:53.189  5405  5452 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:57:53.189  5405  5452 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:57:53.189  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:57:53.189  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:57:53.189  5405  5452 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1960e62 not in the list
09-22 06:57:53.189  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:57:53.189  5405  5452 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 not in the list
09-22 06:57:53.189  5405  5452 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:57:53.189  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 06:57:53.189  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:57:53.189  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:57:53.189  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:57:53.190  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:57:53.190  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:57:53.190  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:57:53.190  5405  5452 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 not in the list
09-22 06:57:53.192  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 06:57:53.192  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 06:57:53.192  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 06:57:53.192  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 06:57:53.192  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-22 06:57:53.192  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 06:57:53.193  5405  5452 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 06:57:53.193  5405  5452 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 06:57:53.194  5405  5452 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 06:57:53.194  5405  5452 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 06:57:53.194  5405  5452 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:57:53.194  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:57:53.194  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:57:53.194  5405  5452 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1960e62 not in the list
09-22 06:57:53.194  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:57:53.194  5405  5452 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 not in the list
09-22 06:57:53.194  5405  5452 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:57:53.194  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 06:57:53.194  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:57:53.194  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:57:53.194  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:57:53.195  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:57:53.195  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 06:57:53.195  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:57:53.195  5405  5452 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 not in the list
09-22 06:57:53.195  5405  5452 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 06:57:53.196  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:57:53.198  5405  5452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:57:53.198  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:57:53.198  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:57:53.198  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:57:53.198  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:57:53.198  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:57:53.198  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:57:53.198  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:57:53.199  5405  5452 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 06:57:53.199  5405  5452 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:57:53.199  5405  5452 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:57:53.199  5405  5452 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 06:57:53.199  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 06:57:53.199  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:57:53.199  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 06:57:53.201  5405  5452 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 06:57:53.201  5405  5452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 06:57:53.203  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:57:53.205  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:57:53.206  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 06:57:53.207  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 06:57:53.207  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 06:57:53.208  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-22 06:57:53.209  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-22 06:57:53.209  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 06:57:53.209  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 06:57:53.210  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 06:57:53.210  5405  5452 D BluetoothAdapter: STATE_ON
09-22 06:57:53.212  4366  4583 D BtGatt.GattService: registerClient() - UUID=cfe6f444-bc31-4235-86ab-53746c58d159
09-22 06:57:53.213  4366  4428 D BtGatt.GattService: onClientRegistered() - UUID=cfe6f444-bc31-4235-86ab-53746c58d159, clientIf=5
09-22 06:57:53.215  5405  5415 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 06:57:53.216  4366  4380 D BtGatt.GattService: start scan with filters
09-22 06:57:53.220  4366  4433 D BtGatt.ScanManager: handling starting scan
09-22 06:57:53.220  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 06:57:53.220  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 06:57:53.220  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 06:57:53.220  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 06:57:53.221  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:57:53.222  4366  4433 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@de62ab2
09-22 06:57:53.222  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 06:57:53.222  5405  5405 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:57:53.222  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 06:57:53.223  5405  5452 I io.jxcore.node.ConnectionHelper: start: OK
09-22 06:57:53.229  4366  4428 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 06:57:53.229  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:57:53.230  4366  4433 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 06:57:53.236  4366  4428 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 06:57:53.237  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:57:53.237  4366  4433 D BtGatt.ScanManager: Starting BLE batch scan
09-22 06:57:53.237  4366  4433 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 06:57:53.249  4366  4428 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 06:57:53.249  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:57:53.255  4366  4428 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 06:57:53.255  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:57:53.725  5405  5405 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-22 06:57:53.725  5405  5405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:57:53.726  5405  5405 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 06:57:56.460   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-22 06:57:56.465   929  2945 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-22 06:57:58.228  5405  5452 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 06:57:58.228  5405  5452 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-22 06:57:58.228  5405  5452 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 06:57:58.228  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:57:58.228  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 06:57:58.228  5405  5452 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 06:57:58.228  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 06:57:58.229  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 06:57:58.229  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 06:57:58.229  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 06:57:58.229  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 06:57:58.230  5405  5452 D BluetoothAdapter: STATE_ON
09-22 06:57:58.231  4366  4583 D BtGatt.GattService: stopScan() - queue size =1
09-22 06:57:58.233  4366  4380 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 06:57:58.234  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 06:57:58.234  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-22 06:57:58.234  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-22 06:57:58.235  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 06:57:58.235  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 06:57:58.238  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 06:57:58.239  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 06:57:58.239  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 06:57:58.240  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:57:58.240  4366  4366 D BtGatt.ScanManager: awakened up at time 213176
09-22 06:57:58.241  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:57:58.245  5405  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:57:58.245  5405  5452 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:57:58.245  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:57:58.245  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 06:57:58.245  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:57:58.245  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 06:57:58.245  5405  5452 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1960e62 not in the list
09-22 06:57:58.245  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 06:57:58.246  5405  5452 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 not in the list
09-22 06:57:58.246  5405  5452 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:57:58.246  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:57:58.248  4366  4428 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 06:57:58.248  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:57:58.249  4366  4433 D BtGatt.ScanManager: stopping BLe Batch
09-22 06:57:58.249  5405  5405 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 06:57:58.249  5405  5405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 06:57:58.256  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 06:57:58.258  5405  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 06:57:58.258  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 06:57:58.258  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:57:58.258  4366  4428 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 06:57:58.258  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:57:58.259  4366  4433 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 06:57:58.259  5405  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 06:57:58.267  5405  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:57:58.267  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:57:58.267  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 06:57:58.272  5405  5405 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 06:57:58.272  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:57:58.273  5405  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 06:57:58.278  5405  5405 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 06:57:58.280  4366  4428 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-22 06:57:58.281  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:57:58.281  4366  4428 D BtGatt.GattService: current time is 213217121693
09-22 06:57:58.281  4366  4428 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -75, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -78, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -76, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -76, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-22 06:57:58.283  4366  4428 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 06:57:58.285  4366  4428 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-22 06:57:58.285  4366  4428 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-22 06:57:58.286  4366  4428 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 06:57:58.286  4366  4428 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-22 06:57:58.286  4366  4428 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-22 06:57:58.779  5405  5405 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 06:57:59.499   929  2945 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-22 06:57:59.503   929  2945 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-22 06:58:03.248  5405  5452 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-22 06:58:03.254  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:58:03.264  5405  5452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:58:03.264  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:58:03.264  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:58:03.264  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:58:03.264  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:58:03.264  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:58:03.264  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:58:03.264  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 06:58:03.270  5405  5452 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 06:58:03.270  5405  5452 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:58:03.271  5405  5452 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 06:58:03.272  5405  5452 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-22 06:58:03.272  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-22 06:58:03.272  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:58:03.272  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 06:58:03.275  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:58:03.277  5405  5452 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 06:58:03.278  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:58:03.281  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 06:58:03.282  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 06:58:03.282  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 06:58:03.282  5405  5452 D BluetoothAdapter: STATE_ON
09-22 06:58:03.285  4366  4380 D BtGatt.GattService: registerClient() - UUID=bb1ccaa7-220a-449e-ae1f-816f5a1e8a50
09-22 06:58:03.285  4366  4428 D BtGatt.GattService: onClientRegistered() - UUID=bb1ccaa7-220a-449e-ae1f-816f5a1e8a50, clientIf=5
,09-22 06:58:03.286  5405  5415 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 06:58:03.286  4366  4583 D BtGatt.GattService: start scan with filters
09-22 06:58:03.289  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 06:58:03.289  4366  4433 D BtGatt.ScanManager: handling starting scan
09-22 06:58:03.290  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 06:58:03.290  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 06:58:03.290  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 06:58:03.293  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:58:03.293  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-22 06:58:03.293  5405  5405 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:58:03.296  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 06:58:03.297  4366  4428 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 06:58:03.297  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:58:03.297  4366  4433 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 06:58:03.299  5405  5452 I io.jxcore.node.ConnectionHelper: start: OK
,09-22 06:58:03.302  5405  5452 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 06:58:03.302  5405  5452 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 06:58:03.302  5405  5452 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 06:58:03.302  5405  5452 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 06:58:03.302  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 06:58:03.302  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 06:58:03.303  5405  5452 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 06:58:03.303  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 06:58:03.303  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 06:58:03.303  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-22 06:58:03.303  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 06:58:03.303  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 06:58:03.303  4366  4428 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 06:58:03.303  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:58:03.303  4366  4433 D BtGatt.ScanManager: Starting BLE batch scan
,09-22 06:58:03.304  4366  4433 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 06:58:03.304  5405  5452 D BluetoothAdapter: STATE_ON
09-22 06:58:03.304  4366  4380 D BtGatt.GattService: stopScan() - queue size =1
09-22 06:58:03.305  4366  4583 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 06:58:03.306  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 06:58:03.306  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 06:58:03.306  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 06:58:03.306  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 06:58:03.306  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 06:58:03.307  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:58:03.307  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-22 06:58:03.307  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 06:58:03.308  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:58:03.308  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:58:03.309  5405  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 06:58:03.309  5405  5452 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 06:58:03.309  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:58:03.309  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 06:58:03.310  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 06:58:03.310  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 06:58:03.310  5405  5452 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1960e62 not in the list
09-22 06:58:03.310  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:58:03.310  5405  5452 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 not in the list
09-22 06:58:03.310  5405  5452 D io.jxcore.node.ConnectivityMonitor: stop
09-22 06:58:03.310  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 06:58:03.313  5405  5405 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 06:58:03.313  5405  5405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 06:58:03.316  4366  4428 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 06:58:03.316  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:58:03.316  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 06:58:03.317  5405  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 06:58:03.318  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 06:58:03.318  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 06:58:03.318  5405  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 06:58:03.320  5405  5452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 06:58:03.320  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 06:58:03.321  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 06:58:03.322  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 06:58:03.322  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 06:58:03.323  4366  4428 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 06:58:03.323  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:58:03.323  5405  5452 D BluetoothAdapter: STATE_ON
09-22 06:58:03.323  5405  5452 D BluetoothLeScanner: could not find callback wrapper
09-22 06:58:03.323  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 06:58:03.323  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 06:58:03.323  5405  5452 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7122bf3 not in the list
09-22 06:58:03.324  5405  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 06:58:03.324  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:58:03.324  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 06:58:03.326  5405  5405 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 06:58:03.326  5405  5405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 06:58:03.327  5405  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 06:58:03.327  5405  5452 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-22 06:58:03.329  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:58:03.329  5405  5405 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 06:58:03.330  4366  4428 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 06:58:03.330  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:58:03.330  4366  4433 D BtGatt.ScanManager: stopping BLe Batch
,09-22 06:58:03.334  5405  5452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:58:03.334  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:58:03.334  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:58:03.334  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:58:03.334  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:58:03.334  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:58:03.334  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:58:03.334  5405  5452 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 06:58:03.335  5405  5452 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 06:58:03.336  4366  4428 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 06:58:03.336  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:58:03.336  5405  5452 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 06:58:03.336  4366  4433 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 06:58:03.336  5405  5452 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 06:58:03.336  5405  5452 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 06:58:03.336  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 06:58:03.336  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 06:58:03.336  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 06:58:03.339  5405  5452 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 06:58:03.341  4366  4428 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-22 06:58:03.341  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:58:03.341  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:58:03.343  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 06:58:03.343  5405  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 06:58:03.344  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-22 06:58:03.344  5405  5452 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 06:58:03.345  5405  5452 D BluetoothAdapter: STATE_ON
09-22 06:58:03.347  4366  4591 D BtGatt.GattService: registerClient() - UUID=6aff695d-ea5d-45ce-a85a-084f0973f4a5
09-22 06:58:03.347  4366  4428 D BtGatt.GattService: onClientRegistered() - UUID=6aff695d-ea5d-45ce-a85a-084f0973f4a5, clientIf=5
,09-22 06:58:03.348  5405  5416 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 06:58:03.348  4366  4380 D BtGatt.GattService: start scan with filters
,09-22 06:58:03.350  4366  4433 D BtGatt.ScanManager: handling starting scan
09-22 06:58:03.350  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 06:58:03.350  5405  5452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 06:58:03.350  5405  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 06:58:03.350  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 06:58:03.352  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 06:58:03.352  5405  5452 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 06:58:03.352  5405  5405 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 06:58:03.353  5405  5452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 06:58:03.356  4366  4428 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 06:58:03.356  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:58:03.356  4366  4433 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 06:58:03.357  5405  5452 I io.jxcore.node.ConnectionHelper: start: OK
,09-22 06:58:03.360  4366  4428 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 06:58:03.360  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 06:58:03.360  4366  4433 D BtGatt.ScanManager: Starting BLE batch scan
09-22 06:58:03.360  4366  4433 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 06:58:03.368  4366  4428 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 06:58:03.368  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:58:03.372  4366  4428 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-22 06:58:03.372  4366  4428 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 06:58:03.854  5405  5405 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-22 06:58:03.854  5405  5405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 06:58:03.854  5405  5405 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 06:58:04.471   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-22 06:58:04.471   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0

```
