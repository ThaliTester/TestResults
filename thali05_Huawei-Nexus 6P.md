#### Test 83268893ec4b63c_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-21 10:50:26.906   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 10:50:27.908   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
09-21 10:50:28.326  5532  5532 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 10:50:28.332  5532  5532 D AndroidRuntime: CheckJNI is OFF
09-21 10:50:28.358  5532  5532 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 10:50:28.391  5532  5532 I Radio-JNI: register_android_hardware_Radio DONE
09-21 10:50:28.405  5532  5532 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-21 10:50:28.409   928  3616 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-21 10:50:28.450   928  3616 I ActivityManager: Start proc 5541:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-21 10:50:28.472  5532  5532 D AndroidRuntime: Shutting down VM
,09-21 10:50:28.796   928   938 I WindowManager: Screenshot max retries 4 of Token{f1e19bd ActivityRecord{48d4d14 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{fbd2aac u0 Starting com.test.thalitest} drawState=2
,09-21 10:50:28.867  5541  5541 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-21 10:50:28.904  5541  5541 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-21 10:50:28.980  5541  5541 I LibraryLoader: Time to load native libraries: 67 ms (timestamps 345-412)
,09-21 10:50:28.980  5541  5541 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-21 10:50:29.022  5541  5541 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6e0ec35}
,09-21 10:50:29.023  5541  5541 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 10:50:29.023  5541  5541 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-21 10:50:29.027  5541  5541 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-21 10:50:29.028  5541  5541 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-21 10:50:29.066  5541  5541 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-21 10:50:29.075  5541  5541 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-21 10:50:29.076  5541  5541 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 10:50:29.076  5541  5541 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-21 10:50:29.076  5541  5541 I Adreno  : Build Date                       : 12/06/15
09-21 10:50:29.076  5541  5541 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-21 10:50:29.076  5541  5541 I Adreno  : Local Branch                     : mybranch17112971
09-21 10:50:29.076  5541  5541 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-21 10:50:29.076  5541  5541 I Adreno  : Remote Branch                    : NONE
09-21 10:50:29.076  5541  5541 I Adreno  : Reconstruct Branch               : NOTHING
,09-21 10:50:29.111   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7282344:true
,09-21 10:50:29.151  3016  3016 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22243]" dev="sockfs" ino=22243 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 10:50:29.151  3016  3016 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22243]" dev="sockfs" ino=22243 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 10:50:29.162  5541  5541 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 10:50:29.170  5541  5541 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-21 10:50:29.197  3016  3016 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31603]" dev="sockfs" ino=31603 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 10:50:29.197  3016  3016 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31603]" dev="sockfs" ino=31603 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 10:50:29.198  5541  5578 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-21 10:50:29.201  3463  3463 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22255]" dev="sockfs" ino=22255 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 10:50:29.201  3463  3463 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[22255]" dev="sockfs" ino=22255 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 10:50:29.206  5541  5565 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-21 10:50:29.240  5541  5578 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 10:50:29.327   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +527ms (total +902ms)
,09-21 10:50:29.358  5541  5541 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5541
,09-21 10:50:29.470  5541  5541 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 10:50:29.759  5541  5581 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -562820816
,09-21 10:50:29.796  5541  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 10:50:29.796  5541  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 10:50:29.796  5541  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 10:50:29.796  5541  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 10:50:29.796  5541  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-21 10:50:29.797  5541  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4265e2 added. We now have 1 listener(s)
,09-21 10:50:29.806  5541  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-21 10:50:29.809  5541  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:50:29.811  5541  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:50:29.812  5541  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-21 10:50:29.820  5541  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a4fe2e added. We now have 1 listener(s)
09-21 10:50:29.820  5541  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:50:29.830   928  3044 D WifiService: New client listening to asynchronous messages
09-21 10:50:29.831  5541  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 10:50:29.831  5541  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 10:50:29.832  5541  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 10:50:29.832  5541  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 10:50:29.832  5541  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-21 10:50:29.836  5541  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 10:50:29.836  5541  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-21 10:50:29.848  5541  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-21 10:50:29.848  5541  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:50:29.848  5541  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:29.848  5541  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:29.848  5541  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:29.848  5541  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:29.848  5541  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:29.848  5541  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:50:29.848  5541  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 10:50:29.848  5541  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 10:50:29.848  5541  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:50:29.850  5541  5581 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 10:50:30.225  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:30.233  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:30.237  5541  5541 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 10:50:30.496  5541  5587 W jxcore-log: Initializing JXcore engine
09-21 10:50:30.497  5541  5587 W jxcore-log: JXcore engine is ready
,09-21 10:50:30.521  5587  5587 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11873 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-21 10:50:30.521  5587  5587 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15486]" dev="sockfs" ino=15486 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-21 10:50:30.521  5587  5587 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 10:50:30.521  5587  5587 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32930]" dev="sockfs" ino=32930 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-21 10:50:30.530  5541  5587 W jxcore-log: Starting JXcore engine
,09-21 10:50:30.532  5541  5550 I art     : Background sticky concurrent mark sweep GC freed 81912(8MB) AllocSpace objects, 19(2MB) LOS objects, 24% free, 24MB/32MB, paused 1.384ms total 106.924ms
,09-21 10:50:30.583  5541  5587 W jxcore-log: Platform android
09-21 10:50:30.583  5541  5587 W jxcore-log: 
09-21 10:50:30.583  5541  5587 W jxcore-log: Process ARCH arm
09-21 10:50:30.583  5541  5587 W jxcore-log: 
,09-21 10:50:30.679  5541  5587 I jxcore-log: JXcore Cordova bridge is ready!
09-21 10:50:30.679  5541  5587 I jxcore-log: 
,09-21 10:50:30.679  5541  5587 W jxcore-log: JXcore engine is started
,09-21 10:50:30.691  5541  5581 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 10:50:30.698  5541  5541 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 10:50:37.262  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-21 10:50:37.262  5541  5587 I jxcore-log: 
,09-21 10:50:37.264  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-21 10:50:37.264  5541  5587 I jxcore-log: 
,09-21 10:50:37.268  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:50:37.268  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.268  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.268  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.268  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:37.268  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.268  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:50:37.268  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 10:50:37.269  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 10:50:37.271  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-21 10:50:37.271  5541  5587 I jxcore-log: 
,09-21 10:50:37.272  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-21 10:50:37.272  5541  5587 I jxcore-log: 
,09-21 10:50:37.611  5541  5587 D executeNativeTests: Running unit tests
,09-21 10:50:37.652  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 10:50:37.652  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 added. We now have 2 listener(s)
,09-21 10:50:37.653  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:50:37.653  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-21 10:50:37.653  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:50:37.653  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 10:50:37.653  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 added. We now have 2 listener(s)
09-21 10:50:37.653  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 10:50:37.654  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 10:50:37.656  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 10:50:37.661  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:50:37.661  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.661  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.661  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.661  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:37.661  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.661  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:50:37.661  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 10:50:37.665  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.666  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:50:37.669  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 10:50:37.669  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 10:50:37.669  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 10:50:37.670  5541  5587 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-21 10:50:37.670  5541  5587 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-21 10:50:37.670  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 10:50:37.670  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-21 10:50:37.670  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 10:50:37.670  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.671  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.671  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.671  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.671  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.671  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:50:37.671  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:50:37.671  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 removed from the list
09-21 10:50:37.671  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.671  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 removed from the list
09-21 10:50:37.672  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:37.683  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:37.684  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.684  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.685  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.685  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.685  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.685  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.685  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.685  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.686  5541  5587 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-21 10:50:37.687  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.687  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-21 10:50:37.687  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.687  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.687  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.687  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.687  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.687  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-21 10:50:37.687  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.687  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.687  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.687  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.687  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 10:50:37.687  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.688  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.688  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.688  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.688  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
,09-21 10:50:37.690  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-21 10:50:37.690  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-21 10:50:37.690  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 10:50:37.690  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-21 10:50:37.690  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-21 10:50:37.692  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-21 10:50:37.693  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 10:50:37.693  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 10:50:37.693  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 10:50:37.693  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.693  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.693  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.693  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 10:50:37.693  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.693  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.693  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.693  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.693  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.693  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.693  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.693  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.693  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.693  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.694  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.694  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.694  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.694  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.694  5541  5587 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 10:50:37.695  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:50:37.697  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:50:37.697  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.697  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.697  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.697  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:37.697  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.697  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:50:37.697  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 10:50:37.698  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.698  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:50:37.698  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:50:37.698  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 10:50:37.698  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 10:50:37.698  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:50:37.698  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 10:50:37.700  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 10:50:37.701  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 10:50:37.703  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 10:50:37.703  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.705  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 10:50:37.705  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 10:50:37.708  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.708  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-21 10:50:37.713  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-21 10:50:37.714  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 10:50:37.715  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 10:50:37.715  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 10:50:37.716  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:50:37.720  4475  4701 D BtGatt.GattService: registerClient() - UUID=d6270bfc-5644-4918-a20c-1cb64c47143e
09-21 10:50:37.721  4475  4538 D BtGatt.GattService: onClientRegistered() - UUID=d6270bfc-5644-4918-a20c-1cb64c47143e, clientIf=5
09-21 10:50:37.722  5541  5552 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 10:50:37.723  4475  4489 D BtGatt.GattService: start scan with filters
09-21 10:50:37.727  4475  4541 D BtGatt.ScanManager: handling starting scan
09-21 10:50:37.727  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 10:50:37.727  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 10:50:37.727  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 10:50:37.727  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 10:50:37.728  4475  4541 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
09-21 10:50:37.728  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 10:50:37.729  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 10:50:37.729  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 10:50:37.729  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 10:50:37.731  5541  5587 I io.jxcore.node.ConnectionHelper: start: OK
09-21 10:50:37.732  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.732  5541  5587 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 10:50:37.732  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.732  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 10:50:37.732  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 10:50:37.732  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 10:50:37.732  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 10:50:37.732  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 10:50:37.732  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 10:50:37.732  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 10:50:37.733  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 10:50:37.733  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 10:50:37.733  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:50:37.733  4475  4491 D BtGatt.GattService: stopScan() - queue size =1
09-21 10:50:37.733  4475  4701 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 10:50:37.734  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 10:50:37.734  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 10:50:37.734  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 10:50:37.734  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 10:50:37.734  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 10:50:37.734  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:50:37.734  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 10:50:37.734  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 10:50:37.735  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 10:50:37.735  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:50:37.735  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.735  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.735  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:50:37.735  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.735  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.735  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.735  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.735  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.735  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:50:37.736  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:50:37.736  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:50:37.737  5541  5587 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 10:50:37.737  4475  4538 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 10:50:37.737  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.737  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:50:37.738  4475  4541 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-21 10:50:37.742  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:50:37.742  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.742  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.742  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.742  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:37.742  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.742  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:50:37.742  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 10:50:37.743  4475  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 10:50:37.743  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.744  4475  4541 D BtGatt.ScanManager: Starting BLE batch scan
09-21 10:50:37.744  4475  4541 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 10:50:37.744  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.745  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:50:37.745  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:50:37.745  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 10:50:37.745  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 10:50:37.745  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:50:37.745  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 10:50:37.747  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 10:50:37.747  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 10:50:37.748  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.750  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 10:50:37.750  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 10:50:37.750  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 10:50:37.753  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.754  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 10:50:37.754  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 10:50:37.754  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 10:50:37.755  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:50:37.756  4475  4538 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 10:50:37.756  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.756  4475  4682 D BtGatt.GattService: registerClient() - UUID=21708e7f-5863-4609-b2d3-7a86813b1362
09-21 10:50:37.757  4475  4538 D BtGatt.GattService: onClientRegistered() - UUID=21708e7f-5863-4609-b2d3-7a86813b1362, clientIf=5
09-21 10:50:37.757  5541  5552 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 10:50:37.757  4475  4491 D BtGatt.GattService: start scan with filters
09-21 10:50:37.761  4475  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 10:50:37.761  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.763  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 10:50:37.763  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 10:50:37.763  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 10:50:37.763  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 10:50:37.765  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 10:50:37.765  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 10:50:37.765  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 10:50:37.765  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 10:50:37.766  5541  5587 I io.jxcore.node.ConnectionHelper: start: OK
09-21 10:50:37.768  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.768  5541  5587 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 10:50:37.768  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.768  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 10:50:37.768  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.768  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 10:50:37.768  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 10:50:37.768  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 10:50:37.768  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 10:50:37.768  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 10:50:37.768  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 10:50:37.768  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 10:50:37.768  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:50:37.769  4475  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 10:50:37.769  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.769  4475  4701 D BtGatt.GattService: stopScan() - queue size =0
09-21 10:50:37.769  4475  4541 D BtGatt.ScanManager: stopping BLe Batch
09-21 10:50:37.769  4475  4682 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 10:50:37.769  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 10:50:37.769  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 10:50:37.769  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 10:50:37.769  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 10:50:37.769  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 10:50:37.771  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:50:37.771  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 10:50:37.771  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 10:50:37.771  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-21 10:50:37.771  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:50:37.772  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.772  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.772  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:50:37.772  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.772  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.772  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.772  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:50:37.772  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.772  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.772  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:50:37.772  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:50:37.772  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.773  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.773  4475  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 10:50:37.773  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.773  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.773  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.773  4475  4541 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 10:50:37.773  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.773  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.774  5541  5587 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 10:50:37.775  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:50:37.777  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:50:37.777  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.777  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.777  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.777  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:37.777  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.777  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:50:37.777  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 10:50:37.779  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.779  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:50:37.779  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:50:37.779  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 10:50:37.779  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 10:50:37.779  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:50:37.779  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 10:50:37.780  4475  4538 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 10:50:37.780  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.781  4475  4541 D BtGatt.ScanManager: handling starting scan
09-21 10:50:37.781  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.782  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 10:50:37.782  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 10:50:37.784  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.786  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 10:50:37.786  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 10:50:37.786  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 10:50:37.789  4475  4538 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 10:50:37.789  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.790  4475  4541 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-21 10:50:37.790  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 10:50:37.790  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 10:50:37.790  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 10:50:37.791  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:50:37.793  4475  4489 D BtGatt.GattService: registerClient() - UUID=4a83e8ca-c03d-4732-870c-9d190e2c6cca
09-21 10:50:37.794  4475  4538 D BtGatt.GattService: onClientRegistered() - UUID=4a83e8ca-c03d-4732-870c-9d190e2c6cca, clientIf=5
09-21 10:50:37.794  5541  5552 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 10:50:37.795  4475  4682 D BtGatt.GattService: start scan with filters
09-21 10:50:37.795  4475  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 10:50:37.795  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.795  4475  4541 D BtGatt.ScanManager: Starting BLE batch scan
09-21 10:50:37.795  4475  4541 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 10:50:37.797  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 10:50:37.797  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 10:50:37.798  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 10:50:37.798  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 10:50:37.800  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 10:50:37.800  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 10:50:37.800  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 10:50:37.801  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 10:50:37.804  4475  4538 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 10:50:37.805  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.806  5541  5587 I io.jxcore.node.ConnectionHelper: start: OK
09-21 10:50:37.806  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.806  5541  5587 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 10:50:37.806  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.806  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 10:50:37.806  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.806  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 10:50:37.806  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 10:50:37.806  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 10:50:37.806  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 10:50:37.806  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 10:50:37.806  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 10:50:37.806  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 10:50:37.807  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:50:37.808  4475  4489 D BtGatt.GattService: stopScan() - queue size =1
09-21 10:50:37.808  4475  4682 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 10:50:37.809  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 10:50:37.809  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 10:50:37.809  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 10:50:37.809  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 10:50:37.809  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 10:50:37.809  4475  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 10:50:37.810  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.810  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:50:37.810  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 10:50:37.810  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 10:50:37.810  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 10:50:37.810  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:50:37.811  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:50:37.812  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:50:37.812  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.812  5541  5587 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 10:50:37.812  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:50:37.812  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.812  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.812  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.812  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 10:50:37.812  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:50:37.812  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.812  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.812  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.812  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.812  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.813  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.813  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.814  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.814  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.814  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.814  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.814  5541  5587 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-21 10:50:37.815  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.815  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.815  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.815  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.815  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.815  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.815  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.815  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.815  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.815  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.816  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.815  4475  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 10:50:37.816  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.816  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.816  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.816  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.816  4475  4541 D BtGatt.ScanManager: stopping BLe Batch
09-21 10:50:37.817  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.817  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.817  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.817  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.817  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-21 10:50:37.818  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.818  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.818  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.818  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.818  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.818  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.818  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.818  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.818  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.818  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.818  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.818  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.818  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.819  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.819  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.819  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.819  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.820  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.820  5541  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-21 10:50:37.820  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.820  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.820  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.820  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.820  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.820  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.821  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.821  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.821  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.821  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.821  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.821  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.821  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.821  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.822  4475  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 10:50:37.822  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.822  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.822  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.823  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.823  4475  4541 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 10:50:37.823  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.823  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-21 10:50:37.823  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.823  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.823  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.823  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.823  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.824  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.824  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.824  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.824  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.824  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.824  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.824  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.824  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.824  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.825  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.825  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.825  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.825  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.826  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 10:50:37.826  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 10:50:37.826  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 10:50:37.826  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 10:50:37.826  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 10:50:37.826  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 10:50:37.826  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.826  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.826  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.827  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.827  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.827  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.827  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.827  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.827  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.827  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.827  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.827  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.827  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.827  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.828  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.828  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.828  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.828  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.829  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 10:50:37.829  4475  4538 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 10:50:37.829  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.829  5541  5587 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-21 10:50:37.829  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-21 10:50:37.831  4475  4541 D BtGatt.ScanManager: handling starting scan
09-21 10:50:37.831  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 10:50:37.831  5541  5587 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-21 10:50:37.831  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-21 10:50:37.831  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 10:50:37.831  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-21 10:50:37.831  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-21 10:50:37.831  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-21 10:50:37.832  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-21 10:50:37.833  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 10:50:37.833  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 10:50:37.833  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 10:50:37.833  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-21 10:50:37.833  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-21 10:50:37.833  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 10:50:37.833  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 10:50:37.833  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 10:50:37.833  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-21 10:50:37.833  5541  5587 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-21 10:50:37.833  5541  5587 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-21 10:50:37.833  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 10:50:37.834  5541  5587 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-21 10:50:37.834  5541  5587 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-21 10:50:37.834  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 10:50:37.834  5541  5587 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-21 10:50:37.834  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-21 10:50:37.837  4475  4538 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 10:50:37.837  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.837  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-21 10:50:37.837  4475  4541 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-21 10:50:37.838  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-21 10:50:37.838  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-21 10:50:37.839  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-21 10:50:37.839  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-21 10:50:37.839  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-21 10:50:37.839  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 10:50:37.839  5541  5587 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-21 10:50:37.839  5541  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-21 10:50:37.840  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.840  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.840  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.840  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.840  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.840  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.840  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-21 10:50:37.841  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.841  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.841  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.841  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.841  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.841  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.841  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.841  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.841  5541  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-21 10:50:37.842  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.842  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.842  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.842  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.842  5541  5588 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 10:50:37.843  5541  5587 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-21 10:50:37.843  4475  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 10:50:37.844  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.844  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.844  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.844  4475  4541 D BtGatt.ScanManager: Starting BLE batch scan
09-21 10:50:37.844  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.844  4475  4541 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 10:50:37.844  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.844  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.844  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.844  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.844  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.844  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.844  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.844  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.844  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.844  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.845  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.845  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.846  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.846  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.846  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.846  5541  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-21 10:50:37.846  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.847  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.847  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-21 10:50:37.847  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.847  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.847  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.847  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.847  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.847  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.847  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.847  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.847  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.847  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.847  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.844  4703  4703 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31633]" dev="sockfs" ino=31633 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 10:50:37.848  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.844  4703  4703 W Binder_5: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31633]" dev="sockfs" ino=31633 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 10:50:37.848  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.848  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.848  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.849  5541  5587 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-21 10:50:37.849  5541  5587 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-21 10:50:37.849  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-21 10:50:37.849  5541  5587 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-21 10:50:37.849  5541  5587 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-21 10:50:37.849  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-21 10:50:37.849  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-21 10:50:37.849  5541  5587 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-21 10:50:37.850  5541  5587 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-21 10:50:37.850  5541  5587 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-21 10:50:37.850  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-21 10:50:37.850  5541  5587 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-21 10:50:37.850  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.850  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.850  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.850  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.850  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.850  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.850  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.850  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.850  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.850  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.850  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.851  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.851  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.851  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.853  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.853  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.853  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.853  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.854  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.854  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.854  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.854  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.854  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.854  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.854  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.854  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.854  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.854  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.855  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.855  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.855  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.855  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.855  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.855  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.855  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.855  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.855  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.855  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.855  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.856  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.856  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.856  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.856  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.856  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.856  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.856  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.856  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.857  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.857  4475  4538 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 10:50:37.857  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.857  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.857  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.857  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.858  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-21 10:50:37.858  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:50:37.859  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-21 10:50:37.859  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-21 10:50:37.859  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-21 10:50:37.859  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-21 10:50:37.859  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 10:50:37.859  5541  5541 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-21 10:50:37.860  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.860  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-21 10:50:37.860  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-21 10:50:37.860  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-21 10:50:37.860  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.860  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-21 10:50:37.860  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.860  5541  5541 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-21 10:50:37.860  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.860  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 10:50:37.860  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 10:50:37.860  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 10:50:37.860  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.860  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.861  5541  5590 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 10:50:37.861  4682  4682 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32241]" dev="sockfs" ino=32241 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 10:50:37.861  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:50:37.861  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.861  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:50:37.861  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.861  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:50:37.861  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.862  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:50:37.862  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.861  4682  4682 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32241]" dev="sockfs" ino=32241 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 10:50:37.862  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.862  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.862  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.862  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.862  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.862  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.862  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.862  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.862  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.862  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.862  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.863  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.863  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.863  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.863  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.863  5541  5590 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-21 10:50:37.864  5541  5587 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-21 10:50:37.864  5541  5590 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-21 10:50:37.864  5541  5590 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-21 10:50:37.864  5541  5587 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-21 10:50:37.864  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 10:50:37.864  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 10:50:37.864  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.864  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.864  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.864  5541  5541 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-21 10:50:37.864  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.864  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.864  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.865  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.865  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.865  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.865  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.865  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.865  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.865  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.865  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.866  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.867  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.867  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.867  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.867  4475  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 10:50:37.867  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.871  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.871  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.871  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.871  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.871  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.871  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.871  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.871  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.871  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.871  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.872  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.872  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.872  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.872  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.872  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.873  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.873  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.873  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.873  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:50:37.873  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:50:37.873  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:50:37.873  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:50:37.873  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.873  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.874  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9748183 not in the list
09-21 10:50:37.874  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.874  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.874  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:50:37.874  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.874  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.874  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:50:37.874  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:50:37.875  4475  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 10:50:37.875  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:50:37.875  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.875  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:50:37.875  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:50:37.875  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4633f00 not in the list
09-21 10:50:37.875  4475  4541 D BtGatt.ScanManager: stopping BLe Batch
09-21 10:50:37.876  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-21 10:50:37.876  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-21 10:50:37.876  5541  5587 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-21 10:50:37.876  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-21 10:50:37.876  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-21 10:50:37.876  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-21 10:50:37.877  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-21 10:50:37.877  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-21 10:50:37.878  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-21 10:50:37.878  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-21 10:50:37.878  5541  5587 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-21 10:50:37.878  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-21 10:50:37.878  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-21 10:50:37.878  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-21 10:50:37.879  5541  5587 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-21 10:50:37.879  5541  5587 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-21 10:50:37.879  5541  5587 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-21 10:50:37.879  5541  5587 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-21 10:50:37.879  5541  5587 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-21 10:50:37.879  4475  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 10:50:37.879  5541  5587 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-21 10:50:37.879  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.879  4475  4541 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 10:50:37.880  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:50:37.880  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f11d9e2 added. We now have 2 listener(s)
09-21 10:50:37.880  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:50:37.884  5541  5587 D BluetoothAdapter: enable(): BT is already enabled..!
09-21 10:50:37.884  4475  4538 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 10:50:37.884  4475  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:50:37.884   928   938 D WifiService: setWifiEnabled: true pid=5541, uid=10077
09-21 10:50:37.884   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-21 10:50:37.885  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:50:37.885  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c8d173 added. We now have 3 listener(s)
09-21 10:50:37.885  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:50:37.889  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:50:37.889  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4446830 added. We now have 4 listener(s)
09-21 10:50:37.889  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:50:37.890  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:50:37.890  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dff2ca9 added. We now have 5 listener(s)
09-21 10:50:37.890  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:50:37.891   928   939 D WifiService: setWifiEnabled: false pid=5541, uid=10077
09-21 10:50:37.891   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 10:50:37.894   928  3032 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-21 10:50:37.894   928  3032 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-21 10:50:37.894   928  3032 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-21 10:50:37.894   928  3032 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-21 10:50:37.895  4475  4534 D BluetoothAdapterState: Current state: ON, message: 23
09-21 10:50:37.895  4475  4534 D BluetoothAdapterProperties: Setting state to 13
09-21 10:50:37.895  4475  4534 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-21 10:50:37.896  4475  4534 D BluetoothAdapterProperties: onBluetoothDisable()
09-21 10:50:37.896  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:50:37.897  4475  4534 I BluetoothAdapterState: Entering PendingCommandState
09-21 10:50:37.897  4475  4475 D BluetoothMapService: onReceive
09-21 10:50:37.897  4475  4475 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-21 10:50:37.897  4475  4475 D BluetoothMapService: STATE_TURNING_OFF
09-21 10:50:37.898  4475  4475 D BluetoothMapService: MAP Service closeService in
09-21 10:50:37.898  4475  4475 D BluetoothMapMasInstance0: MAP Service shutdown
09-21 10:50:37.898  4475  4475 D ObexServerSockets0: shutdown(block = true)
09-21 10:50:37.898  4475  4475 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 10:50:37.898  4475  4704 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-21 10:50:37.899  4475  4475 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 10:50:37.899  4475  4705 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-21 10:50:37.901  4475  4679 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-21 10:50:37.901  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.902  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:50:37.902  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.902  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.902  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.902  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:37.902  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.902  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:50:37.902  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 10:50:37.902  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.902  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.903  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:50:37.903   928  5287 D DhcpClient: Clearing IP address
09-21 10:50:37.903   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-21 10:50:37.904  4475  4475 I BtOppRfcommListener: stopping Accept Thread
09-21 10:50:37.905  4475  5210 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-21 10:50:37.905  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.905  4475  5210 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-21 10:50:37.907  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.909  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.909  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:37.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:37.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:50:37.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 10:50:37.910   507   921 D CommandListener: Setting iface cfg
09-21 10:50:37.912  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.912  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 10:50:37.914  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.914   928   941 I ActivityManager: Start proc 5593:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-21 10:50:37.916  4475  4538 D BluetoothAdapterProperties: Scan Mode:20
09-21 10:50:37.916  3694  5350 V NativeCrypto: Read error: ssl=0x7f71eac380: I/O error during system call, Connection timed out
09-21 10:50:37.916  4475  4534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-21 10:50:37.918  3694  5350 V NativeCrypto: SSL shutdown failed: ssl=0x7f71eac380: I/O error during system call, Broken pipe
09-21 10:50:37.919  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.919  4475  4475 D HeadsetService: Received stop request...Stopping profile...
09-21 10:50:37.922   928  3047 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-21 10:50:37.922   928  3047 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-21 10:50:37.925  3189  3204 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:37.926   928   928 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:37.926  4475  4475 D A2dpService: Received stop request...Stopping profile...
09-21 10:50:37.926  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.926   928   928 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:37.926  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:37.926  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.926  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.926  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.926  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:37.926  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:37.926  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 10:50:37.926  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 10:50:37.926  3585  3600 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:37.926  4475  4696 D A2dpStateMachine: Exit Disconnected: -1
09-21 10:50:37.926   928   928 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:37.927   928  3047 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-21 10:50:37.927  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.927  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:50:37.927   928   928 D BluetoothA2dp: Proxy object disconnected
09-21 10:50:37.928  4475  4475 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:37.928  4475  4475 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:37.928  4475  4475 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 10:50:37.928  4475  4475 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:37.929  4475  4475 D HidService: Received stop request...Stopping profile...
09-21 10:50:37.929  4475  4475 D HidService: Stopping Bluetooth HidService
09-21 10:50:37.929  3553  3681 W QCNEJ   : |CORE| network lost: 100
09-21 10:50:37.929  3553  3681 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-21 10:50:37.930  3189  3189 D HeadsetProfile: Bluetooth service disconnected
,09-21 10:50:37.930   928   928 D RttService: SCAN_AVAILABLE : 1
09-21 10:50:37.931  3189  3189 D BluetoothA2dp: Proxy object disconnected
09-21 10:50:37.931   928  3147 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-21 10:50:37.931   536   536 E Parcel  : Reading a NULL string not supported here.
09-21 10:50:37.932  3189  3189 D BluetoothInputDevice: Proxy object disconnected
09-21 10:50:37.932  3189  3189 D HidProfile: Bluetooth service disconnected
09-21 10:50:37.932  4475  4475 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-21 10:50:37.932  4475  4475 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-21 10:50:37.932  4475  4475 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:37.932  4475  4475 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:37.932  4475  4475 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:37.932  4475  4475 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:37.933  4475  4538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-21 10:50:37.933  4475  4659 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:37.933  4475  4659 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:37.933  4475  4659 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:37.933  4475  4538 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-21 10:50:37.938   928  5288 D DhcpClient: Receive thread stopped
,09-21 10:50:37.941  4475  4659 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:37.941  4475  4659 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:37.941  4475  4475 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:37.941  4475  4475 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:37.941  4475  4475 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:37.941  4475  4475 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:37.941  4475  4538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-21 10:50:37.941  4475  4659 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 10:50:37.941  4475  4659 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 10:50:37.941  4475  4659 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 10:50:37.941  4475  4659 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 10:50:37.941  4475  4475 D HealthService: Received stop request...Stopping profile...
,09-21 10:50:37.943  4475  4475 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-21 10:50:37.943  4475  4475 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-21 10:50:37.944   928  3032 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-21 10:50:37.944  4475  4475 D PanService: Received stop request...Stopping profile...
09-21 10:50:37.944  4475  4538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-21 10:50:37.946  4475  4475 D BluetoothMapService: Received stop request...Stopping profile...
09-21 10:50:37.946  4475  4475 D BluetoothMapService: stop()
09-21 10:50:37.947  4475  4475 D BluetoothMapAppObserver: deinitObservers()
09-21 10:50:37.947  4475  4475 D BluetoothMapAppObserver: removeReceiver()
09-21 10:50:37.948  4475  4475 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:37.948  4475  4475 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:37.948  4475  4475 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:37.948  4475  4475 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:37.948  4475  4475 D SapService: Received stop request...Stopping profile...
09-21 10:50:37.948  4475  4475 V SapService: stop()
,09-21 10:50:37.949  4475  4475 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-21 10:50:37.949  4475  4538 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-21 10:50:37.949  4475  4475 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-21 10:50:37.950  4475  4475 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:37.950  4475  4475 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:37.950  4475  4475 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 10:50:37.950  4475  4475 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:37.950  4475  4475 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-21 10:50:37.950  4475  4475 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-21 10:50:37.951  4475  4475 D BluetoothMapService: MAP Service closeService in
09-21 10:50:37.951  4475  4475 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:37.951  4475  4475 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:37.951  4475  4475 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:37.951  4475  4475 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 10:50:37.951  4475  4475 D BluetoothMapService: cleanup()
,09-21 10:50:37.951  4475  4475 D BluetoothMapService: MAP Service closeService in
09-21 10:50:37.951  4475  4475 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:37.951  4475  4475 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:37.952  4475  4475 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:37.952  4475  4475 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:37.952  4475  4534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-21 10:50:37.952  4475  4534 D BluetoothAdapterProperties: Setting state to 15
09-21 10:50:37.952  4475  4534 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-21 10:50:37.952   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-21 10:50:37.952  4475  4534 I BluetoothAdapterState: Entering BleOnState
09-21 10:50:37.953  3189  3203 D BluetoothMap: onBluetoothStateChange: up=false
09-21 10:50:37.953   928  3032 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-21 10:50:37.954   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 10:50:37.954  3189  3715 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-21 10:50:37.957   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 10:50:37.957   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 10:50:37.958  3189  3204 D BluetoothPbap: onBluetoothStateChange: up=false
09-21 10:50:37.959  3189  3203 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 10:50:37.959  3585  4016 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 10:50:37.959  3189  3715 D BluetoothPan: onBluetoothStateChange on: false
09-21 10:50:37.960   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 10:50:37.960  3189  3204 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 10:50:37.961  4475  4534 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-21 10:50:37.961  4475  4534 D BluetoothAdapterProperties: Setting state to 16
09-21 10:50:37.961  4475  4534 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-21 10:50:37.962  4475  4534 D BluetoothAdapterProperties: onBleDisable
09-21 10:50:37.962  4475  4534 I BluetoothAdapterState: Entering PendingCommandState
09-21 10:50:37.962  4475  4535 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-21 10:50:37.963  4475  4659 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-21 10:50:37.963  4475  4659 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-21 10:50:37.963  5541  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-21 10:50:37.964  4475  4538 D BluetoothAdapterProperties: Scan Mode:20
09-21 10:50:37.965  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.965  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:37.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:37.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:37.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:37.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:37.966  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.966  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 10:50:37.968  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.968  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:37.968  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.968  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.968  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:37.968  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:37.968  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:37.968  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:37.968  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:37.969  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:37.971  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:37.972   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-21 10:50:37.972   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-21 10:50:37.973   507   921 D TetherController: Setting IP forward enable = 0
09-21 10:50:37.975   928  3047 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-21 10:50:37.975   928  3047 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-21 10:50:37.977  5593  5593 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-21 10:50:37.978   928  3032 D DhcpClient: doQuit
09-21 10:50:37.978   928   945 D Tethering: MasterInitialState.processMessage what=3
09-21 10:50:37.978   928  3032 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 10:50:37.979  3619  3619 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-21 10:50:37.979  5181  5181 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1455c71 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-21 10:50:37.979   928  5287 D DhcpClient: onQuitting
09-21 10:50:37.979  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:37.983  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.984  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:37.984  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.984  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.984  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:37.984  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:37.984  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:37.984  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:37.984  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:37.985  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 10:50:37.986  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:50:37.989  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.990  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:37.990  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:37.990  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:37.990  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:37.990  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:37.990  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:37.990  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:37.990  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:37.990  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:37.990  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:50:37.992  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:37.994  4867  4890 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-21 10:50:37.994  4867  4890 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-21 10:50:37.994  4867  4890 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-21 10:50:37.995  4867  4890 E SarControlService: no key has been found,reset the power
,09-21 10:50:37.995  4867  4905 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-21 10:50:37.995  4867  4905 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-21 10:50:37.995  4867  4905 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-21 10:50:37.995  4896  4896 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-21 10:50:37.995  4896  4896 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-21 10:50:37.996  4867  4905 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-21 10:50:37.996  4867  4905 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-21 10:50:37.996  4867  4905 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-21 10:50:37.998  4896  4896 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-21 10:50:37.998  4896  4896 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-21 10:50:38.001  4896  4913 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cb0ab1f HexData = [00000000ea03000000000000ffffffff]
,09-21 10:50:38.001  4896  4913 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-21 10:50:38.001  4896  4913 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-21 10:50:38.002  4896  4896 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-21 10:50:38.002  4867  4877 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-21 10:50:38.008  4896  4913 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cb0ab1f HexData = [00000000eb03000000000000ffffffff]
09-21 10:50:38.008  4896  4913 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-21 10:50:38.008  4896  4913 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-21 10:50:38.009  4896  4896 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-21 10:50:38.009  4867  4879 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-21 10:50:38.014  5593  5593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-21 10:50:38.019   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@773636c:true
,09-21 10:50:38.021  3694  3694 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 10:50:38.021  3619  3619 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-21 10:50:38.026  3619  3619 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-21 10:50:38.034   928  3616 I ActivityManager: Start proc 5621:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-21 10:50:38.046  5593  5593 D LocalBluetoothProfileManager: Adding local MAP profile
,09-21 10:50:38.049  5593  5593 D BluetoothMap: Create BluetoothMap proxy object
,09-21 10:50:38.060  3619  3619 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-21 10:50:38.066  5593  5593 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-21 10:50:38.070  5621  5621 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-21 10:50:38.072  3619  3619 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-21 10:50:38.081  5593  5593 D DockEventReceiver: finishStartingService: stopping service
,09-21 10:50:38.086   928  3494 I ActivityManager: Killing 4847:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-21 10:50:38.170  4475  4538 I bt_hci  : shut_down
,09-21 10:50:38.174  4475  4542 D bt_hwcfg: hw_epilog_process
09-21 10:50:38.175  4475  4542 I bt_vendor: low_power_mode_cb
,09-21 10:50:38.175   928  3032 D wifi    : In wifi stop Hal
,09-21 10:50:38.175  4357  4357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 10:50:38.175   928  3032 D wifi    : halHandle = 0x7f708c43a0, mVM = 0x7f8cf4d140, mCls = 0x100a72
09-21 10:50:38.175   928  3614 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-21 10:50:38.175   928  3614 D WifiHAL : Got a signal to exit!!!
,09-21 10:50:38.175   928  3614 I WifiHAL : Exit wifi_event_loop
09-21 10:50:38.176   928  3032 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-21 10:50:38.176   928  3032 E WifiHAL : Event processing terminated
09-21 10:50:38.177   928  3032 D wifi    : In wifi cleaned up handler
09-21 10:50:38.177   928  3032 I WifiHAL : Internal cleanup completed
09-21 10:50:38.177  4475  4542 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-21 10:50:38.177  4475  4542 I bt_vendor: epilog_cb
09-21 10:50:38.177  4475  4542 I bt_hci  : epilog_finished_callback
,09-21 10:50:38.178  3717  4102 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 10:50:38.178  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:38.180  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:38.180  4475  4538 I bt_hci_h4: hal_close
09-21 10:50:38.180  4475  4538 I bt_userial_vendor: device fd = 54 close
,09-21 10:50:38.201   928  3614 D wifi    : set interface wlan0 flags (DOWN)
09-21 10:50:38.201   928  3032 D WifiNative-HAL: HAL event thread stopped successfully
,09-21 10:50:38.252  5621  5621 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at java.io.File.exists(File.java:361)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 10:50:38.252  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 10:50:38.253  5621  5621 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 10:50:38.253  5621  5621 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 10:50:38.253  5621  5621 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.e.b(PG:170)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 10:50:38.253  5621  5621 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.k.d(PG:583)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.e.b(PG:170)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 10:50:38.253  5621  5621 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.File.exists(File.java:361)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 10:50:38.253  5621  5621 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.File.exists(File.java:361)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 10:50:38.253  5621  5621 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 10:50:38.253  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 10:50:38.258  5593  5593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 10:50:38.263  3694  3694 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 10:50:38.263  5593  5593 D DockEventReceiver: finishStartingService: stopping service
09-21 10:50:38.265   928  4043 I ActivityManager: Killing 5181:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-21 10:50:38.314  4002  4002 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-21 10:50:38.316  4002  4002 D SystemUpdateService: onCreate
09-21 10:50:38.319  4475  4535 D bt_stack_manager: event_shut_down_stack finished.
09-21 10:50:38.320  4002  4002 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-21 10:50:38.320  4475  4534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-21 10:50:38.321  4475  4534 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-21 10:50:38.322  4475  4475 D BtGatt.DebugUtils: handleDebugAction() action=null
09-21 10:50:38.323  4475  4475 D BtGatt.GattService: Received stop request...Stopping profile...
09-21 10:50:38.323  4475  4475 D BtGatt.GattService: stop()
09-21 10:50:38.323  4475  4475 D BtGatt.AdvertiseManager: advertise clients cleared
09-21 10:50:38.326  4475  4475 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:38.326  4475  4475 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:38.326  4475  4475 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:38.326  4475  4475 V BluetoothAdapterState: isBleTurningOff()=true
09-21 10:50:38.326  4475  4534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-21 10:50:38.326  4475  4534 D BluetoothAdapterProperties: Setting state to 10
09-21 10:50:38.326  4475  4534 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-21 10:50:38.327  4475  4534 I BluetoothAdapterState: Entering OffState
09-21 10:50:38.327   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-21 10:50:38.332  4475  4475 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-21 10:50:38.332  4475  4475 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-21 10:50:38.333  4475  4475 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-21 10:50:38.334  4475  4535 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-21 10:50:38.336  4002  4002 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-21 10:50:38.345  4475  4475 I art     : System.exit called, status: 0
,09-21 10:50:38.345  4475  4475 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-21 10:50:38.351  4002  5322 I iu.UploadsManager: num queued entries: 0
,09-21 10:50:38.352  4002  5322 I iu.UploadsManager: num updated entries: 0
09-21 10:50:38.353  4002  5322 I iu.SyncManager: NEXT; no task
,09-21 10:50:38.354  4002  4002 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-21 10:50:38.356  4002  4002 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-21 10:50:38.358  5325  5325 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-21 10:50:38.362  5325  5325 D SprintDMHelper: simOperator: 
09-21 10:50:38.362  5325  5325 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-21 10:50:38.362  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 10:50:38.372  4357  5655 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-21 10:50:38.378  4002  5652 I SystemUpdateService: active receiver: enabled
,09-21 10:50:38.391   928  4043 I ActivityManager: Start proc 5657:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-21 10:50:38.402   928   939 I ActivityManager: Process com.android.bluetooth (pid 4475) has died
,09-21 10:50:38.404  4002  5652 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-21 10:50:38.404   928   945 D Tethering: InitialState.processMessage what=4
,09-21 10:50:38.407   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-21 10:50:38.422  5657  5657 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-21 10:50:38.423  4002  5652 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,09-21 10:50:38.423  4002  5652 I SystemUpdateService: now status is 0 (complete)
09-21 10:50:38.423  4002  5652 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-21 10:50:38.423  4002  5652 I SystemUpdateService: file has been verified
09-21 10:50:38.424  4002  5652 I SystemUpdateService: OTA package size = 21989297
,09-21 10:50:38.447  4002  5652 I SystemUpdateService: showing system update notification
,09-21 10:50:38.480  4002  4002 D SystemUpdateService: onDestroy
,09-21 10:50:38.481   928  3494 I ActivityManager: Killing 4549:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-21 10:50:38.604  5621  5640 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-21 10:50:38.616   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7f95159:true
,09-21 10:50:39.061   507   921 E Netd    : netlink response contains error (No such file or directory)
,09-21 10:50:39.062   928  3047 E NetdConnector: NDC Command {53 network destroy 100} took too long (1085ms)
,09-21 10:50:39.063   928  3047 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-21 10:50:39.064   928  3022 E NetdConnector: NDC Command {54 bandwidth setglobalalert 2097152} took too long (1081ms)
,09-21 10:50:39.065   928  3021 E NetdConnector: NDC Command {55 bandwidth gettetherstats} took too long (656ms)
09-21 10:50:39.065   507   921 D TetherController: Setting IP forward enable = 0
,09-21 10:50:40.904   928  3494 D WifiService: setWifiEnabled: true pid=5541, uid=10077
09-21 10:50:40.904   928  3494 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 10:50:40.912   507   921 D SoftapController: Softap fwReload - Ok
,09-21 10:50:40.916   507   921 D CommandListener: Setting iface cfg
,09-21 10:50:40.917   507   921 D CommandListener: Trying to bring down wlan0
,09-21 10:50:40.918   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-21 10:50:40.924   928  3032 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 10:50:41.518   928  3032 D wifi    : set interface wlan0 flags (UP)
09-21 10:50:41.521   928  3032 I WifiHAL : Initializing wifi
,09-21 10:50:41.521   928  3032 I WifiHAL : Creating socket
09-21 10:50:41.527   928  3032 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-21 10:50:41.527   928  3032 D wifi    : Did set static halHandle = 0x7f708c43a0
,09-21 10:50:41.528   928  3032 D wifi    : halHandle = 0x7f708c43a0, mVM = 0x7f8cf4d140, mCls = 0x101862
09-21 10:50:41.529   928  3032 D wifi    : array field set
09-21 10:50:41.529   928  3032 I WifiNative-HAL: interface[0] = wlan0
09-21 10:50:41.531   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-21 10:50:41.537   928  5678 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547349087136
,09-21 10:50:41.538   928  5678 D wifi    : waitForHalEvents called, vm = 0x7f8cf4d140, obj = 0x101862, env = 0x7f711ed880
,09-21 10:50:41.614  5679  5679 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-21 10:50:41.633   928  3032 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-21 10:50:41.639  5679  5679 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 10:50:41.642  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:41.646  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:41.673  5679  5679 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 10:50:41.673  5679  5679 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-21 10:50:41.689  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 10:50:41.689  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:41.689  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:41.689  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:41.689  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:41.689  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:41.689  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:41.689  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:41.689  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:41.689  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:41.689  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 10:50:41.690  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 10:50:41.690  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:41.690  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:41.690  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:41.690  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:41.690  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:41.690  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:41.690  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:41.690  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:41.691  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:41.691  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:50:41.691   928  3032 D WifiConfigStore: Loading config and enabling all networks 
,09-21 10:50:41.702   928  3032 D WifiConfigStore: loaded 0 passpoint configs
,09-21 10:50:41.702   928  3032 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-21 10:50:41.702   928  3032 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-21 10:50:41.703   928  3032 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-21 10:50:41.704   928  3032 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-21 10:50:41.705   928  3032 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-21 10:50:41.705   928  3032 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-21 10:50:41.705   928  3032 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-21 10:50:41.708  4357  4357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-21 10:50:41.708   928  3032 D WifiNative-HAL: Setting external_sim to 1
09-21 10:50:41.709   928  3032 D wifi    : setting dfs flag to true, 0x7f6e3a73c0
09-21 10:50:41.709   928  3032 D WifiStateMachine: Setting OUI to DA-A1-19
09-21 10:50:41.709   928  3032 D wifi    : setting scan oui 0x7f6e3a73c0
09-21 10:50:41.710   928  3032 D WifiHAL : Sending mac address OUI
,09-21 10:50:41.713   928  3032 E native  : do suspend false
,09-21 10:50:41.720   928  3032 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-21 10:50:41.720   928   928 D RttService: SCAN_AVAILABLE : 3
09-21 10:50:41.720   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-21 10:50:41.721   928  3147 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-21 10:50:41.722   507   921 D CommandListener: Setting iface cfg
,09-21 10:50:41.725   928  3023 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-21 10:50:41.726   928  3023 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-21 10:50:41.735   928  3023 D WifiNative-HAL: p2pGetDeviceAddress
,09-21 10:50:41.740   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=183172 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
09-21 10:50:41.740   928  3023 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-21 10:50:43.910   928  4043 D WifiService: setWifiEnabled: false pid=5541, uid=10077
,09-21 10:50:43.910   928  4043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 10:50:43.919   928   928 D RttService: SCAN_AVAILABLE : 1
,09-21 10:50:43.920   928  3147 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-21 10:50:43.931   928  3032 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-21 10:50:43.932   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-21 10:50:43.938   928  3032 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 10:50:43.940  5679  5679 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-21 10:50:43.946  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:43.946  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:43.946  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:43.946  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:43.946  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:43.946  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:43.946  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:43.946  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:43.946  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:43.946  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:43.947  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:50:43.949  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:43.949  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:43.949  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:43.949  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:43.949  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:43.949  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:43.949  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:43.949  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:43.949  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:43.949  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:43.949  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 10:50:43.955  5679  5679 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-21 10:50:43.959  5679  5679 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-21 10:50:43.962  5679  5679 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-21 10:50:44.077   928  3032 D wifi    : In wifi stop Hal
,09-21 10:50:44.077   928  3032 D wifi    : halHandle = 0x7f708c43a0, mVM = 0x7f8cf4d140, mCls = 0x101862
,09-21 10:50:44.077  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:44.077   928  5678 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-21 10:50:44.078   928  5678 D WifiHAL : Got a signal to exit!!!
09-21 10:50:44.078   928  5678 I WifiHAL : Exit wifi_event_loop
,09-21 10:50:44.079   928  3032 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-21 10:50:44.079   928  3032 E WifiHAL : Event processing terminated
09-21 10:50:44.080   928  3032 D wifi    : In wifi cleaned up handler
09-21 10:50:44.080  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:44.081   928  3032 I WifiHAL : Internal cleanup completed
,09-21 10:50:44.082  4357  4357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-21 10:50:44.084  3717  4102 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-21 10:50:44.115   928  5678 D wifi    : set interface wlan0 flags (DOWN)
,09-21 10:50:44.115   928  3032 D WifiNative-HAL: HAL event thread stopped successfully
,09-21 10:50:44.322   928   945 D Tethering: InitialState.processMessage what=4
,09-21 10:50:44.331   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-21 10:50:46.950   928   945 I ActivityManager: Start proc 5683:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-21 10:50:47.044  5683  5683 D AdapterServiceConfig: Adding HeadsetService
09-21 10:50:47.044  5683  5683 D AdapterServiceConfig: Adding A2dpService
09-21 10:50:47.044  5683  5683 D AdapterServiceConfig: Adding HidService
09-21 10:50:47.044  5683  5683 D AdapterServiceConfig: Adding HealthService
,09-21 10:50:47.045  5683  5683 D AdapterServiceConfig: Adding PanService
,09-21 10:50:47.045  5683  5683 D AdapterServiceConfig: Adding GattService
09-21 10:50:47.045  5683  5683 D AdapterServiceConfig: Adding BluetoothMapService
09-21 10:50:47.045  5683  5683 D AdapterServiceConfig: Adding SapService
,09-21 10:50:47.060   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4fa64ef:true
,09-21 10:50:47.060  5683  5683 D BluetoothAdapterState: make() - Creating AdapterState
,09-21 10:50:47.063  5683  5683 I bt_bluedroid: init
,09-21 10:50:47.063  5683  5695 I BluetoothAdapterState: Entering OffState
,09-21 10:50:47.065  5683  5696 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-21 10:50:47.066  5683  5696 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-21 10:50:47.066  5683  5696 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-21 10:50:47.066  5683  5696 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-21 10:50:47.066  5683  5683 I bt_bluedroid: get_profile_interface socket
,09-21 10:50:47.068  5683  5683 I bt_bluedroid: get_profile_interface sdp
,09-21 10:50:47.068  5683  5699 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-21 10:50:47.069  5683  5699 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 10:50:47.073  5683  5694 I bt_bluedroid: config_hci_snoop_log
09-21 10:50:47.074   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-21 10:50:47.077  5683  5695 D BluetoothAdapterState: Current state: OFF, message: 0
,09-21 10:50:47.078  5683  5695 D BluetoothAdapterProperties: Setting state to 14
09-21 10:50:47.078  5683  5695 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-21 10:50:47.079  5683  5695 D BluetoothBondStateMachine: make
09-21 10:50:47.080  5683  5700 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-21 10:50:47.083  5683  5695 I BluetoothAdapterState: Entering PendingCommandState
,09-21 10:50:47.084  5683  5683 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-21 10:50:47.086  5683  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:47.087  5683  5683 D BtGatt.DebugUtils: handleDebugAction() action=null
09-21 10:50:47.087  5683  5683 D BtGatt.GattService: Received start request. Starting profile...
09-21 10:50:47.087  5683  5683 D BtGatt.GattService: start()
09-21 10:50:47.087  5683  5683 I bt_bluedroid: get_profile_interface gatt
,09-21 10:50:47.088  5683  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
09-21 10:50:47.088  5683  5683 D BtGatt.AdvertiseManager: advertise manager created
,09-21 10:50:47.093  5683  5683 V BluetoothAdapterState: isTurningOff()=false
,09-21 10:50:47.094  5683  5683 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:47.094  5683  5683 V BluetoothAdapterState: isBleTurningOn()=true
09-21 10:50:47.094  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:47.094  5683  5695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-21 10:50:47.095  5683  5695 I bt_bluedroid: bt_bluedroid
09-21 10:50:47.095  5683  5696 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-21 10:50:47.096  5683  5696 I bt_hci  : start_up
,09-21 10:50:47.101  5683  5696 I bt_vendor: alloc value 0xf3fe3871
09-21 10:50:47.101  5683  5696 I bt_vendor: init
09-21 10:50:47.101  5683  5696 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-21 10:50:47.101  5683  5696 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-21 10:50:47.208  5683  5696 D bt_hci  : start_up starting async portion
09-21 10:50:47.209  5683  5703 I bt_hci  : event_finish_startup
,09-21 10:50:47.209  5683  5703 I bt_hci_h4: hal_open
09-21 10:50:47.209  5683  5703 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-21 10:50:47.212  5683  5703 I bt_userial_vendor: device fd = 54 open
,09-21 10:50:47.207  5704  5704 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 10:50:47.227  5683  5703 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 10:50:47.230  5683  5703 D bt_hwcfg: Chipset BCM4358A3
,09-21 10:50:47.230  5683  5703 D bt_hwcfg: Target name = [BCM4358A3]
09-21 10:50:47.231  5683  5703 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-21 10:50:47.619  5683  5703 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-21 10:50:47.619  5683  5703 D bt_hwcfg: Settlement delay -- 100 ms
09-21 10:50:47.620  5683  5703 I bt_hwcfg: Setting fw settlement delay to 100 
,09-21 10:50:47.754  5683  5703 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 10:50:47.755  5683  5703 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-21 10:50:47.757  5683  5703 I bt_hwcfg: vendor lib fwcfg completed
,09-21 10:50:47.757  5683  5703 I bt_vendor: firmware callback
09-21 10:50:47.757  5683  5703 I bt_hci  : firmware_config_callback
,09-21 10:50:47.766  5683  5707 I bt_btu  : btu_task pending for preload complete event
,09-21 10:50:47.766  5683  5707 I bt_btu_task: Bluetooth chip preload is complete
,09-21 10:50:47.766  5683  5707 I bt_btu  : btu_task received preload complete event
09-21 10:50:47.772  5683  5707 I         : BTE_InitTraceLevels -- TRC_HCI
09-21 10:50:47.772  5683  5707 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-21 10:50:47.772  5683  5707 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-21 10:50:47.772  5683  5707 I         : BTE_InitTraceLevels -- TRC_AVDT
09-21 10:50:47.772  5683  5707 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-21 10:50:47.772  5683  5707 I         : BTE_InitTraceLevels -- TRC_A2D
09-21 10:50:47.772  5683  5707 I         : BTE_InitTraceLevels -- TRC_BNEP
09-21 10:50:47.772  5683  5707 I         : BTE_InitTraceLevels -- TRC_BTM
,09-21 10:50:47.773  5683  5707 I         : BTE_InitTraceLevels -- TRC_GAP
09-21 10:50:47.773  5683  5707 I         : BTE_InitTraceLevels -- TRC_PAN
09-21 10:50:47.773  5683  5707 I         : BTE_InitTraceLevels -- TRC_SDP
09-21 10:50:47.773  5683  5707 I         : BTE_InitTraceLevels -- TRC_GATT
,09-21 10:50:47.773  5683  5707 I         : BTE_InitTraceLevels -- TRC_SMP
09-21 10:50:47.773  5683  5707 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-21 10:50:47.773  5683  5707 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-21 10:50:47.856  5683  5707 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f61549
,09-21 10:50:47.856  5683  5707 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f61549 
,09-21 10:50:47.877  5683  5699 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-21 10:50:47.879  5683  5699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-21 10:50:47.880  5683  5699 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-21 10:50:47.882  5683  5699 D BluetoothAdapterProperties: Name is: Nexus 6P
09-21 10:50:47.884  5683  5699 D BluetoothAdapterProperties: Scan Mode:20
09-21 10:50:47.884  5683  5699 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 10:50:47.884  5683  5699 D bt_hci  : do_postload posting postload work item
09-21 10:50:47.885  5683  5703 I bt_hci  : event_postload
09-21 10:50:47.885  5683  5703 I bt_vendor: sco_config_cb
09-21 10:50:47.885  5683  5703 I bt_hci  : sco_config_callback postload finished.
,09-21 10:50:47.889  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:47.891  5683  5699 D bt_bte_conf: Device ID record 1 : primary
09-21 10:50:47.891  5683  5699 D bt_bte_conf:   vendorId            = 000f
09-21 10:50:47.891  5683  5699 D bt_bte_conf:   vendorIdSource      = 0001
09-21 10:50:47.891  5683  5699 D bt_bte_conf:   product             = 1200
09-21 10:50:47.891  5683  5699 D bt_bte_conf:   version             = 1436
09-21 10:50:47.891  5683  5699 D bt_bte_conf:   clientExecutableURL = 
09-21 10:50:47.891  5683  5699 D bt_bte_conf:   serviceDescription  = 
09-21 10:50:47.891  5683  5699 D bt_bte_conf:   documentationURL    = 
09-21 10:50:47.892  5683  5699 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-21 10:50:47.892  5683  5696 D bt_stack_manager: event_start_up_stack finished
,09-21 10:50:47.893  5683  5695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-21 10:50:47.893  5683  5703 I bt_vendor: low_power_mode_cb
09-21 10:50:47.894  5683  5695 D BluetoothAdapterProperties: Setting state to 15
09-21 10:50:47.894  5683  5695 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-21 10:50:47.895  5683  5695 I BluetoothAdapterState: Entering BleOnState
09-21 10:50:47.896  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:47.900  5683  5695 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-21 10:50:47.900  5683  5695 D BluetoothAdapterProperties: Setting state to 11
09-21 10:50:47.900  5683  5695 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-21 10:50:47.907  5683  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:47.909  5683  5683 D HeadsetService: Received start request. Starting profile...
09-21 10:50:47.909   538   538 I ServiceManager: Waiting for service AtCmdFwd...
09-21 10:50:47.911  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:47.912  5683  5683 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-21 10:50:47.912  5683  5683 D HeadsetStateMachine: make
,09-21 10:50:47.916  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:47.924  5683  5695 I BluetoothAdapterState: Entering PendingCommandState
,09-21 10:50:47.925  5683  5683 D HeadsetStateMachine: max_hf_connections = 1
,09-21 10:50:47.925  5683  5683 I bt_bluedroid: get_profile_interface handsfree
09-21 10:50:47.925  5683  5699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-21 10:50:47.925  5683  5699 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-21 10:50:47.928  5683  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:47.929  5683  5683 D A2dpService: Received start request. Starting profile...
09-21 10:50:47.929  5683  5683 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-21 10:50:47.930  5683  5683 I bt_bluedroid: get_profile_interface avrcp
,09-21 10:50:47.935  5683  5683 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-21 10:50:47.936  5683  5683 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-21 10:50:47.936  5683  5683 D A2dpStateMachine: make
09-21 10:50:47.937  5683  5683 I bt_bluedroid: get_profile_interface a2dp
,09-21 10:50:47.937  5683  5699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-21 10:50:47.939  5683  5715 D A2dpStateMachine: Enter Disconnected: -2
,09-21 10:50:47.940  5683  5683 I BluetoothHidServiceJni: classInitNative: succeeds
09-21 10:50:47.941  5683  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:47.942  3694  3694 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 10:50:47.943  5593  5593 D BluetoothInputDevice: Proxy object connected
09-21 10:50:47.943  5683  5683 D HidService: Received start request. Starting profile...
09-21 10:50:47.944  5683  5683 I bt_bluedroid: get_profile_interface hidhost
09-21 10:50:47.944  5683  5683 D HidService: setHidService(): set to: null
09-21 10:50:47.944  5683  5699 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f4256d
09-21 10:50:47.944  5683  5699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-21 10:50:47.944  5683  5683 I BluetoothHealthServiceJni: classInitNative: succeeds
09-21 10:50:47.945  5683  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
09-21 10:50:47.946  5593  5593 D HidProfile: Bluetooth service connected
,09-21 10:50:47.946  5683  5683 D HealthService: Received start request. Starting profile...
09-21 10:50:47.948  5683  5683 I bt_bluedroid: get_profile_interface health
09-21 10:50:47.948  5683  5683 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-21 10:50:47.949  5683  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:47.951  5683  5683 D PanService: Received start request. Starting profile...
,09-21 10:50:47.951  5683  5683 D BluetoothPanServiceJni: initializeNative(L110): pan
09-21 10:50:47.951  5683  5683 I bt_bluedroid: get_profile_interface pan
09-21 10:50:47.951  5683  5699 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-21 10:50:47.954  5683  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
09-21 10:50:47.957  5683  5683 D BluetoothMapService: Received start request. Starting profile...
09-21 10:50:47.957  5683  5683 D BluetoothMapService: start()
09-21 10:50:47.961  5593  5593 D BluetoothPan: BluetoothPAN Proxy object connected
09-21 10:50:47.961  5683  5683 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-21 10:50:47.962  5593  5593 D PanProfile: Bluetooth service connected
,09-21 10:50:47.962  5593  5593 D BluetoothMap: Proxy object connected
09-21 10:50:47.962  5593  5593 D MapProfile: Bluetooth service connected
09-21 10:50:47.962  5593  5593 D BluetoothMap: getConnectedDevices()
,09-21 10:50:47.962  5683  5683 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-21 10:50:47.963  5683  5683 D BluetoothMapAppObserver: createReceiver()
09-21 10:50:47.963  5593  5593 D BluetoothMap: Bluetooth is Not enabled
09-21 10:50:47.964  5683  5683 D BluetoothMapAppObserver: initObservers()
09-21 10:50:47.964  5683  5683 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-21 10:50:47.970  5683  5683 V SapService: SapBinder()
,09-21 10:50:47.970  5683  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
09-21 10:50:47.971  5683  5683 D SapService: Received start request. Starting profile...
09-21 10:50:47.971  5683  5683 V SapService: start()
09-21 10:50:47.972  5683  5683 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:47.972  5683  5683 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:47.973  5683  5713 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:47.973  5683  5683 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isTurningOn()=true
,09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:47.974  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:47.975  5683  5683 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:47.975  5683  5683 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:47.975  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:47.975  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:47.975  5683  5695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-21 10:50:47.975  5683  5695 D BluetoothAdapterProperties: ScanMode =  20
09-21 10:50:47.975  5683  5695 D BluetoothAdapterProperties: State =  11
09-21 10:50:47.976  5683  5699 D BluetoothAdapterProperties: Scan Mode:21
09-21 10:50:47.976  5683  5695 D BluetoothAdapterProperties: Setting state to 12
09-21 10:50:47.977  5683  5699 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 10:50:47.977  5683  5695 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-21 10:50:47.979  5683  5695 I BluetoothAdapterState: Entering OnState
,09-21 10:50:47.980  3189  3715 D BluetoothMap: onBluetoothStateChange: up=true
,09-21 10:50:47.981  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:47.981  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:47.981  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:47.981  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:47.981  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:47.981  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:47.981  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:47.981  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:47.982   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 10:50:47.982  3189  3189 D BluetoothMap: Proxy object connected
09-21 10:50:47.982  3189  3189 D MapProfile: Bluetooth service connected
09-21 10:50:47.982  3189  3189 D BluetoothMap: getConnectedDevices()
,09-21 10:50:47.982  3189  3715 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-21 10:50:47.983  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:50:47.984   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 10:50:47.984  3189  3189 D BluetoothInputDevice: Proxy object connected
,09-21 10:50:47.984  3189  3189 D HidProfile: Bluetooth service connected
09-21 10:50:47.985   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 10:50:47.985  3189  3203 D BluetoothPbap: onBluetoothStateChange: up=true
09-21 10:50:47.986   928   928 D BluetoothA2dp: Proxy object connected
,09-21 10:50:47.987  5593  5605 D BluetoothPbap: onBluetoothStateChange: up=true
,09-21 10:50:47.989  3189  3204 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 10:50:47.989  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:47.989  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:47.989  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:47.989  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:47.989  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:47.989  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:47.989  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:47.989  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 10:50:47.989  3585  4016 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 10:50:47.989  5683  5683 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-21 10:50:47.990  3189  3715 D BluetoothPan: onBluetoothStateChange on: true
09-21 10:50:47.990  5683  5683 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-21 10:50:47.991  5683  5683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 10:50:47.992  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:50:47.992  5593  5606 D BluetoothMap: onBluetoothStateChange: up=true
,09-21 10:50:47.992  3189  3189 D BluetoothPan: BluetoothPAN Proxy object connected
09-21 10:50:47.992  3189  3189 D PanProfile: Bluetooth service connected
09-21 10:50:47.992   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 10:50:47.993  3189  3204 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 10:50:47.993  5683  5683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 10:50:47.994  3189  3189 D BluetoothA2dp: Proxy object connected
09-21 10:50:47.994  5593  5605 D BluetoothPan: onBluetoothStateChange on: true
09-21 10:50:47.995  5593  5606 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-21 10:50:47.995  5683  5683 D ObexServerSockets: Succeed to create listening sockets 
09-21 10:50:47.995  5683  5683 D ObexServerSockets0: startAccept()
,09-21 10:50:47.995  5683  5683 D ObexServerSockets0: prepareForNewConnect()
09-21 10:50:47.996   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-21 10:50:47.997  5683  5683 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-21 10:50:47.997  5683  5683 D BluetoothSdpJni: SDP Create record success - handle: 0
09-21 10:50:47.998  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:47.999  5593  5593 D LocalBluetoothProfileManager: Adding local A2DP profile
09-21 10:50:48.000  5683  5724 D ObexServerSockets0: Accepting socket connection...
09-21 10:50:48.000  5683  5683 D BluetoothMapService: onReceive
,09-21 10:50:48.000  5683  5683 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-21 10:50:48.000  5683  5683 D BluetoothMapService: STATE_ON
09-21 10:50:48.000  5683  5725 D ObexServerSockets0: Accepting socket connection...
09-21 10:50:48.000  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:48.002  5683  5726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 10:50:48.004  5593  5593 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-21 10:50:48.005  5683  5726 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-21 10:50:48.005  5683  5726 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-21 10:50:48.011  5593  5593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-21 10:50:48.013  5593  5593 D BluetoothA2dp: Proxy object connected
,09-21 10:50:48.016  3694  3694 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 10:50:48.017  5593  5593 D DockEventReceiver: finishStartingService: stopping service
,09-21 10:50:48.023  5593  5593 D BluetoothPbap: Proxy object connected
,09-21 10:50:48.023  5593  5593 D PbapServerProfile: Bluetooth service connected
,09-21 10:50:48.027  5683  5683 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-21 10:50:48.027  5683  5683 D ObexServerSockets0: prepareForNewConnect()
,09-21 10:50:48.028  3189  3189 D BluetoothPbap: Proxy object connected
09-21 10:50:48.028  3189  3189 D PbapServerProfile: Bluetooth service connected
,09-21 10:50:48.030  5683  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 10:50:48.042  5683  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 10:50:48.043  5683  5734 I BtOppRfcommListener: Accept thread started.
,09-21 10:50:48.084  3189  3204 D BluetoothHeadset: Proxy object connected
,09-21 10:50:48.084  3189  3189 D HeadsetProfile: Bluetooth service connected
09-21 10:50:48.084   928   928 D BluetoothHeadset: Proxy object connected
09-21 10:50:48.084   928   928 D BluetoothHeadset: Proxy object connected
09-21 10:50:48.084  3585  3598 D BluetoothHeadset: Proxy object connected
09-21 10:50:48.085   928   928 D BluetoothHeadset: Proxy object connected
09-21 10:50:48.085   928   945 D BluetoothHeadset: Proxy object connected
,09-21 10:50:48.089  3189  3715 D BluetoothHeadset: Proxy object connected
,09-21 10:50:48.089  3189  3189 D HeadsetProfile: Bluetooth service connected
,09-21 10:50:48.091  3585  3600 D BluetoothHeadset: Proxy object connected
,09-21 10:50:48.092   928   945 D BluetoothHeadset: Proxy object connected
,09-21 10:50:48.109  5593  5605 D BluetoothHeadset: Proxy object connected
,09-21 10:50:48.110  5593  5593 D HeadsetProfile: Bluetooth service connected
,09-21 10:50:48.910   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 10:50:49.911   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 10:50:49.929  5683  5695 D BluetoothAdapterState: Current state: ON, message: 23
,09-21 10:50:49.929  5683  5695 D BluetoothAdapterProperties: Setting state to 13
,09-21 10:50:49.929  5683  5695 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-21 10:50:49.931  5683  5695 D BluetoothAdapterProperties: onBluetoothDisable()
,09-21 10:50:49.932  5683  5695 I BluetoothAdapterState: Entering PendingCommandState
,09-21 10:50:49.940  5683  5683 D BluetoothMapService: onReceive
09-21 10:50:49.940  5683  5683 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-21 10:50:49.941  5683  5683 D BluetoothMapService: STATE_TURNING_OFF
09-21 10:50:49.942  5683  5683 D BluetoothMapService: MAP Service closeService in
09-21 10:50:49.942  5683  5683 D BluetoothMapMasInstance0: MAP Service shutdown
,09-21 10:50:49.942  5683  5683 D ObexServerSockets0: shutdown(block = true)
,09-21 10:50:49.945  5683  5724 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-21 10:50:49.944  5683  5683 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 10:50:49.946  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:49.947  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:49.947  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:49.947  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:49.947  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:49.947  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:49.947  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:49.947  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:49.947  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:49.947  5683  5725 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-21 10:50:49.948  5683  5683 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 10:50:49.948  5683  5709 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-21 10:50:49.949  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:49.949  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:50:49.949  5683  5699 D BluetoothAdapterProperties: Scan Mode:20
09-21 10:50:49.949  5683  5695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-21 10:50:49.950  5683  5683 I BtOppRfcommListener: stopping Accept Thread
09-21 10:50:49.950  5683  5734 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-21 10:50:49.951  5683  5734 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-21 10:50:49.956  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:49.956  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:49.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:49.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:49.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:49.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 10:50:49.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:49.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:49.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:49.957  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 10:50:49.957  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 10:50:49.961  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:49.964  5683  5683 D HeadsetService: Received stop request...Stopping profile...
09-21 10:50:49.964  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:49.967  3189  3204 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:49.967  3189  3189 D HeadsetProfile: Bluetooth service disconnected
09-21 10:50:49.967   928   928 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:49.968  5683  5683 D A2dpService: Received stop request...Stopping profile...
09-21 10:50:49.968   928   928 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:49.968  5683  5715 D A2dpStateMachine: Exit Disconnected: -1
09-21 10:50:49.968  3585  4016 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:49.968   928   928 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:49.969  5593  5606 D BluetoothHeadset: Proxy object disconnected
09-21 10:50:49.970   928   928 D BluetoothA2dp: Proxy object disconnected
09-21 10:50:49.970  3189  3189 D BluetoothA2dp: Proxy object disconnected
09-21 10:50:49.971  5683  5683 D HidService: Received stop request...Stopping profile...
09-21 10:50:49.971  5683  5683 D HidService: Stopping Bluetooth HidService
09-21 10:50:49.972  3189  3189 D BluetoothInputDevice: Proxy object disconnected
,09-21 10:50:49.972  3189  3189 D HidProfile: Bluetooth service disconnected
09-21 10:50:49.972  5593  5593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 10:50:49.976  5593  5593 D HeadsetProfile: Bluetooth service disconnected
,09-21 10:50:49.976  5683  5683 D HealthService: Received stop request...Stopping profile...
09-21 10:50:49.976  5593  5593 D BluetoothA2dp: Proxy object disconnected
,09-21 10:50:49.977  5593  5593 D BluetoothInputDevice: Proxy object disconnected
09-21 10:50:49.977  5593  5593 D HidProfile: Bluetooth service disconnected
09-21 10:50:49.980  5683  5683 V BluetoothAdapterState: isTurningOff()=true
,09-21 10:50:49.980  5683  5683 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:49.980  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:49.980  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 10:50:49.981  5683  5683 D PanService: Received stop request...Stopping profile...
09-21 10:50:49.982  3189  3189 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-21 10:50:49.982  3189  3189 D PanProfile: Bluetooth service disconnected
09-21 10:50:49.983  5683  5683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-21 10:50:49.983  5683  5683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-21 10:50:49.984  5683  5699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-21 10:50:49.984  5683  5707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:49.984  5683  5707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:49.984  5683  5707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:49.984  5683  5699 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-21 10:50:49.985  5683  5683 D BluetoothMapService: Received stop request...Stopping profile...
09-21 10:50:49.985  5683  5683 D BluetoothMapService: stop()
09-21 10:50:49.985  5683  5683 D BluetoothMapAppObserver: deinitObservers()
09-21 10:50:49.985  5683  5683 D BluetoothMapAppObserver: removeReceiver()
09-21 10:50:49.988  5683  5683 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:49.988  3189  3189 D BluetoothMap: Proxy object disconnected
09-21 10:50:49.988  5683  5683 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:49.988  3189  3189 D MapProfile: Bluetooth service disconnected
09-21 10:50:49.988  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:49.988  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 10:50:49.989  5683  5707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:49.989  5683  5707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:49.990  5683  5707 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 10:50:49.990  5683  5699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-21 10:50:49.990  5683  5707 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 10:50:49.990  5683  5707 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 10:50:49.990  5683  5707 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 10:50:49.990  5593  5593 D DockEventReceiver: finishStartingService: stopping service
,09-21 10:50:49.991  5683  5683 D SapService: Received stop request...Stopping profile...
09-21 10:50:49.991  5683  5683 V SapService: stop()
,09-21 10:50:49.991  5593  5593 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-21 10:50:49.991  5593  5593 D PanProfile: Bluetooth service disconnected
09-21 10:50:49.991  5593  5593 D BluetoothMap: Proxy object disconnected
09-21 10:50:49.991  5593  5593 D MapProfile: Bluetooth service disconnected
09-21 10:50:49.993  5683  5683 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:49.993  5683  5683 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:49.993  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:49.994  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:49.994  5683  5683 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-21 10:50:49.994  5683  5683 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-21 10:50:49.994  5683  5683 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:49.994  5683  5699 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-21 10:50:49.994  5683  5683 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:49.994  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:49.994  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 10:50:49.996  5683  5683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-21 10:50:49.996  5683  5699 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-21 10:50:49.996  5683  5683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-21 10:50:49.997  5683  5683 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:49.997  5683  5683 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:49.997  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:49.997  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:49.997  5683  5683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-21 10:50:49.997  5683  5683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-21 10:50:49.998  3694  3694 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 10:50:49.998  5683  5683 D BluetoothMapService: MAP Service closeService in
09-21 10:50:49.999  5683  5683 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:49.999  5683  5683 V BluetoothAdapterState: isTurningOn()=false
,09-21 10:50:49.999  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:49.999  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:49.999  5683  5683 D BluetoothMapService: cleanup()
09-21 10:50:49.999  5683  5683 D BluetoothMapService: MAP Service closeService in
09-21 10:50:50.000  5683  5683 V BluetoothAdapterState: isTurningOff()=true
09-21 10:50:50.000  5683  5683 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:50.000  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:50.000  5683  5683 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 10:50:50.000  5683  5695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-21 10:50:50.000  5683  5695 D BluetoothAdapterProperties: Setting state to 15
09-21 10:50:50.000  5683  5695 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-21 10:50:50.001  5683  5695 I BluetoothAdapterState: Entering BleOnState
09-21 10:50:50.001  3189  3715 D BluetoothMap: onBluetoothStateChange: up=false
09-21 10:50:50.002   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-21 10:50:50.002  5593  5606 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-21 10:50:50.002  3189  3203 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-21 10:50:50.003   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 10:50:50.003   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 10:50:50.003  3189  3204 D BluetoothPbap: onBluetoothStateChange: up=false
09-21 10:50:50.004  5593  5605 D BluetoothPbap: onBluetoothStateChange: up=false
09-21 10:50:50.005  3189  3715 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-21 10:50:50.005  3585  3598 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-21 10:50:50.005  5593  5606 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-21 10:50:50.007  3189  3203 D BluetoothPan: onBluetoothStateChange on: false
,09-21 10:50:50.009  5593  5605 D BluetoothMap: onBluetoothStateChange: up=false
09-21 10:50:50.009   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 10:50:50.009  3189  3204 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 10:50:50.010  5593  5606 D BluetoothPan: onBluetoothStateChange on: false
09-21 10:50:50.010  5593  5605 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-21 10:50:50.011  5683  5695 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-21 10:50:50.011  5683  5695 D BluetoothAdapterProperties: Setting state to 16
09-21 10:50:50.011  5683  5695 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-21 10:50:50.012  5683  5695 D BluetoothAdapterProperties: onBleDisable
09-21 10:50:50.013  5683  5695 I BluetoothAdapterState: Entering PendingCommandState
,09-21 10:50:50.014  5683  5696 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-21 10:50:50.016  5683  5707 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-21 10:50:50.016  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:50.016  5683  5707 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 10:50:50.017  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:50.018  5593  5593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 10:50:50.019  5683  5699 D BluetoothAdapterProperties: Scan Mode:20
09-21 10:50:50.019  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:50.021  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:50.023  5593  5593 D DockEventReceiver: finishStartingService: stopping service
,09-21 10:50:50.025  3694  3694 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 10:50:50.227  5683  5699 I bt_hci  : shut_down
,09-21 10:50:50.232  5683  5703 D bt_hwcfg: hw_epilog_process
,09-21 10:50:50.232  5683  5703 I bt_vendor: low_power_mode_cb
,09-21 10:50:50.234  5683  5703 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-21 10:50:50.234  5683  5703 I bt_vendor: epilog_cb
09-21 10:50:50.234  5683  5703 I bt_hci  : epilog_finished_callback
,09-21 10:50:50.237  5683  5699 I bt_hci_h4: hal_close
,09-21 10:50:50.237  5683  5699 I bt_userial_vendor: device fd = 54 close
,09-21 10:50:50.355  5683  5696 D bt_stack_manager: event_shut_down_stack finished.
,09-21 10:50:50.356  5683  5695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-21 10:50:50.359  5683  5695 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-21 10:50:50.359  5683  5683 D BtGatt.DebugUtils: handleDebugAction() action=null
09-21 10:50:50.359  5683  5683 D BtGatt.GattService: Received stop request...Stopping profile...
,09-21 10:50:50.359  5683  5683 D BtGatt.GattService: stop()
09-21 10:50:50.360  5683  5683 D BtGatt.AdvertiseManager: advertise clients cleared
,09-21 10:50:50.362  5683  5683 V BluetoothAdapterState: isTurningOff()=false
,09-21 10:50:50.362  5683  5683 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:50.362  5683  5683 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:50.362  5683  5683 V BluetoothAdapterState: isBleTurningOff()=true
09-21 10:50:50.362  5683  5695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-21 10:50:50.363  5683  5695 D BluetoothAdapterProperties: Setting state to 10
09-21 10:50:50.363  5683  5695 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-21 10:50:50.363  5683  5695 I BluetoothAdapterState: Entering OffState
,09-21 10:50:50.364   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-21 10:50:50.373  5683  5683 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-21 10:50:50.374  5683  5683 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-21 10:50:50.374  5683  5683 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-21 10:50:50.376  5683  5696 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-21 10:50:50.382  5683  5683 I art     : System.exit called, status: 0
,09-21 10:50:50.382  5683  5683 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-21 10:50:50.407   928  3496 I ActivityManager: Process com.android.bluetooth (pid 5683) has died
,09-21 10:50:50.912   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 10:50:51.913   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 10:50:52.914   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-21 10:50:52.926  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,09-21 10:50:52.927  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 10:50:55.933  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:50:55.934  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@75511cf added. We now have 6 listener(s)
,09-21 10:50:55.934  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 10:50:55.938  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:50:55.938  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fbfd75c added. We now have 7 listener(s)
09-21 10:50:55.938  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 10:50:55.940  5541  5587 I System.out: IsBluetoothEnabled
,09-21 10:50:55.949  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:55.973   928   945 I ActivityManager: Start proc 5742:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-21 10:50:56.047  5742  5742 D AdapterServiceConfig: Adding HeadsetService
,09-21 10:50:56.047  5742  5742 D AdapterServiceConfig: Adding A2dpService
09-21 10:50:56.047  5742  5742 D AdapterServiceConfig: Adding HidService
09-21 10:50:56.048  5742  5742 D AdapterServiceConfig: Adding HealthService
,09-21 10:50:56.048  5742  5742 D AdapterServiceConfig: Adding PanService
,09-21 10:50:56.048  5742  5742 D AdapterServiceConfig: Adding GattService
09-21 10:50:56.048  5742  5742 D AdapterServiceConfig: Adding BluetoothMapService
09-21 10:50:56.048  5742  5742 D AdapterServiceConfig: Adding SapService
,09-21 10:50:56.059   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c804bc:true
,09-21 10:50:56.059  5742  5742 D BluetoothAdapterState: make() - Creating AdapterState
,09-21 10:50:56.062  5742  5742 I bt_bluedroid: init
,09-21 10:50:56.062  5742  5754 I BluetoothAdapterState: Entering OffState
,09-21 10:50:56.064  5742  5755 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-21 10:50:56.065  5742  5755 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-21 10:50:56.065  5742  5755 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-21 10:50:56.065  5742  5755 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-21 10:50:56.065  5742  5742 I bt_bluedroid: get_profile_interface socket
,09-21 10:50:56.067  5742  5742 I bt_bluedroid: get_profile_interface sdp
,09-21 10:50:56.067  5742  5758 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-21 10:50:56.069  5742  5758 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 10:50:56.073  5742  5753 I bt_bluedroid: config_hci_snoop_log
09-21 10:50:56.074   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-21 10:50:56.078  5742  5754 D BluetoothAdapterState: Current state: OFF, message: 0
09-21 10:50:56.078  5742  5754 D BluetoothAdapterProperties: Setting state to 14
09-21 10:50:56.078  5742  5754 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-21 10:50:56.080  5742  5754 D BluetoothBondStateMachine: make
,09-21 10:50:56.082  5742  5759 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-21 10:50:56.085  5742  5754 I BluetoothAdapterState: Entering PendingCommandState
,09-21 10:50:56.086  5742  5742 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-21 10:50:56.088  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:56.089  5742  5742 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-21 10:50:56.089  5742  5742 D BtGatt.GattService: Received start request. Starting profile...
09-21 10:50:56.089  5742  5742 D BtGatt.GattService: start()
09-21 10:50:56.090  5742  5742 I bt_bluedroid: get_profile_interface gatt
09-21 10:50:56.091  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
09-21 10:50:56.091  5742  5742 D BtGatt.AdvertiseManager: advertise manager created
,09-21 10:50:56.096  5742  5742 V BluetoothAdapterState: isTurningOff()=false
,09-21 10:50:56.096  5742  5742 V BluetoothAdapterState: isTurningOn()=false
09-21 10:50:56.096  5742  5742 V BluetoothAdapterState: isBleTurningOn()=true
09-21 10:50:56.096  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:56.096  5742  5754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-21 10:50:56.097  5742  5754 I bt_bluedroid: bt_bluedroid
,09-21 10:50:56.097  5742  5755 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-21 10:50:56.098  5742  5755 I bt_hci  : start_up
,09-21 10:50:56.103  5742  5755 I bt_vendor: alloc value 0xf3fe3871
09-21 10:50:56.103  5742  5755 I bt_vendor: init
,09-21 10:50:56.103  5742  5755 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-21 10:50:56.103  5742  5755 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-21 10:50:56.215  5742  5755 D bt_hci  : start_up starting async portion
,09-21 10:50:56.215  5742  5762 I bt_hci  : event_finish_startup
,09-21 10:50:56.215  5742  5762 I bt_hci_h4: hal_open
,09-21 10:50:56.215  5742  5762 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-21 10:50:56.214  5763  5763 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 10:50:56.219  5742  5762 I bt_userial_vendor: device fd = 54 open
,09-21 10:50:56.232  5742  5762 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 10:50:56.235  5742  5762 D bt_hwcfg: Chipset BCM4358A3
09-21 10:50:56.235  5742  5762 D bt_hwcfg: Target name = [BCM4358A3]
,09-21 10:50:56.235  5742  5762 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-21 10:50:56.638  5742  5762 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-21 10:50:56.638  5742  5762 D bt_hwcfg: Settlement delay -- 100 ms
09-21 10:50:56.639  5742  5762 I bt_hwcfg: Setting fw settlement delay to 100 
,09-21 10:50:56.773  5742  5762 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 10:50:56.773  5742  5762 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-21 10:50:56.775  5742  5762 I bt_hwcfg: vendor lib fwcfg completed
,09-21 10:50:56.775  5742  5762 I bt_vendor: firmware callback
,09-21 10:50:56.775  5742  5762 I bt_hci  : firmware_config_callback
,09-21 10:50:56.783  5742  5765 I bt_btu  : btu_task pending for preload complete event
09-21 10:50:56.783  5742  5765 I bt_btu_task: Bluetooth chip preload is complete
09-21 10:50:56.783  5742  5765 I bt_btu  : btu_task received preload complete event
,09-21 10:50:56.790  5742  5765 I         : BTE_InitTraceLevels -- TRC_HCI
,09-21 10:50:56.791  5742  5765 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-21 10:50:56.791  5742  5765 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-21 10:50:56.791  5742  5765 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-21 10:50:56.792  5742  5765 I         : BTE_InitTraceLevels -- TRC_AVRC
09-21 10:50:56.792  5742  5765 I         : BTE_InitTraceLevels -- TRC_A2D
09-21 10:50:56.792  5742  5765 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-21 10:50:56.793  5742  5765 I         : BTE_InitTraceLevels -- TRC_BTM
09-21 10:50:56.793  5742  5765 I         : BTE_InitTraceLevels -- TRC_GAP
09-21 10:50:56.793  5742  5765 I         : BTE_InitTraceLevels -- TRC_PAN
09-21 10:50:56.793  5742  5765 I         : BTE_InitTraceLevels -- TRC_SDP
,09-21 10:50:56.793  5742  5765 I         : BTE_InitTraceLevels -- TRC_GATT
09-21 10:50:56.793  5742  5765 I         : BTE_InitTraceLevels -- TRC_SMP
09-21 10:50:56.793  5742  5765 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-21 10:50:56.793  5742  5765 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-21 10:50:56.879  5742  5765 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f61549
,09-21 10:50:56.880  5742  5765 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f61549 
,09-21 10:50:56.900  5742  5758 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-21 10:50:56.900  5742  5758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-21 10:50:56.901  5742  5758 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-21 10:50:56.903  5742  5758 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 10:50:56.906  5742  5758 D BluetoothAdapterProperties: Scan Mode:20
,09-21 10:50:56.907  5742  5758 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-21 10:50:56.907  5742  5758 D bt_hci  : do_postload posting postload work item
09-21 10:50:56.907  5742  5762 I bt_hci  : event_postload
09-21 10:50:56.907  5742  5762 I bt_vendor: sco_config_cb
09-21 10:50:56.907  5742  5762 I bt_hci  : sco_config_callback postload finished.
09-21 10:50:56.910  5742  5758 D bt_bte_conf: Device ID record 1 : primary
09-21 10:50:56.910  5742  5758 D bt_bte_conf:   vendorId            = 000f
09-21 10:50:56.910  5742  5758 D bt_bte_conf:   vendorIdSource      = 0001
09-21 10:50:56.910  5742  5758 D bt_bte_conf:   product             = 1200
09-21 10:50:56.910  5742  5758 D bt_bte_conf:   version             = 1436
09-21 10:50:56.910  5742  5758 D bt_bte_conf:   clientExecutableURL = 
,09-21 10:50:56.910  5742  5758 D bt_bte_conf:   serviceDescription  = 
09-21 10:50:56.910  5742  5758 D bt_bte_conf:   documentationURL    = 
09-21 10:50:56.910  5742  5758 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-21 10:50:56.910  5742  5755 D bt_stack_manager: event_start_up_stack finished
09-21 10:50:56.911  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:56.912  5742  5754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-21 10:50:56.912  5742  5754 D BluetoothAdapterProperties: Setting state to 15
09-21 10:50:56.912  5742  5754 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-21 10:50:56.913  5742  5754 I BluetoothAdapterState: Entering BleOnState
09-21 10:50:56.916  5742  5762 I bt_vendor: low_power_mode_cb
,09-21 10:50:56.919  5742  5754 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-21 10:50:56.919  5742  5754 D BluetoothAdapterProperties: Setting state to 11
09-21 10:50:56.919  5742  5754 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-21 10:50:56.923  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:56.924  5742  5742 D HeadsetService: Received start request. Starting profile...
09-21 10:50:56.927  5742  5742 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-21 10:50:56.928  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:56.929  5742  5742 D HeadsetStateMachine: make
,09-21 10:50:56.935  5742  5754 I BluetoothAdapterState: Entering PendingCommandState
,09-21 10:50:56.939  5742  5742 D HeadsetStateMachine: max_hf_connections = 1
09-21 10:50:56.939  5742  5742 I bt_bluedroid: get_profile_interface handsfree
09-21 10:50:56.939  5742  5758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-21 10:50:56.940  5742  5758 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-21 10:50:56.943  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:56.943  5742  5742 D A2dpService: Received start request. Starting profile...
09-21 10:50:56.944  5742  5742 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-21 10:50:56.944  5742  5742 I bt_bluedroid: get_profile_interface avrcp
,09-21 10:50:56.949  5742  5742 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-21 10:50:56.949  5742  5742 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-21 10:50:56.949  5742  5742 D A2dpStateMachine: make
09-21 10:50:56.950  5742  5742 I bt_bluedroid: get_profile_interface a2dp
09-21 10:50:56.951  5742  5758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-21 10:50:56.952  5742  5773 D A2dpStateMachine: Enter Disconnected: -2
09-21 10:50:56.952  5742  5742 I BluetoothHidServiceJni: classInitNative: succeeds
09-21 10:50:56.953  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:56.953  5742  5742 D HidService: Received start request. Starting profile...
09-21 10:50:56.954  5742  5742 I bt_bluedroid: get_profile_interface hidhost
09-21 10:50:56.954  5742  5742 D HidService: setHidService(): set to: null
09-21 10:50:56.954  5742  5758 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f4256d
09-21 10:50:56.954  5742  5758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-21 10:50:56.955  5742  5742 I BluetoothHealthServiceJni: classInitNative: succeeds
09-21 10:50:56.956  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
09-21 10:50:56.957  5742  5742 D HealthService: Received start request. Starting profile...
09-21 10:50:56.957  3694  3694 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 10:50:56.958  5742  5742 I bt_bluedroid: get_profile_interface health
09-21 10:50:56.959  5742  5742 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-21 10:50:56.960  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:56.960  5742  5742 D PanService: Received start request. Starting profile...
09-21 10:50:56.960  5742  5742 D BluetoothPanServiceJni: initializeNative(L110): pan
09-21 10:50:56.961  5742  5742 I bt_bluedroid: get_profile_interface pan
09-21 10:50:56.961  5742  5758 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-21 10:50:56.963  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:56.964  5742  5742 D BluetoothMapService: Received start request. Starting profile...
09-21 10:50:56.964  5742  5742 D BluetoothMapService: start()
,09-21 10:50:56.966  5742  5742 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-21 10:50:56.967  5742  5742 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-21 10:50:56.967  5742  5742 D BluetoothMapAppObserver: createReceiver()
,09-21 10:50:56.969  5742  5742 D BluetoothMapAppObserver: initObservers()
09-21 10:50:56.969  5742  5742 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-21 10:50:56.976  5742  5742 V SapService: SapBinder()
,09-21 10:50:56.976  5742  5742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:50:56.977  5742  5742 D SapService: Received start request. Starting profile...
09-21 10:50:56.977  5742  5742 V SapService: start()
,09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isTurningOff()=false
,09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:56.980  5742  5771 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:56.980  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isTurningOff()=false
09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isTurningOn()=true
,09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:56.981  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:56.982  5742  5742 V BluetoothAdapterState: isTurningOff()=false
,09-21 10:50:56.982  5742  5742 V BluetoothAdapterState: isTurningOn()=true
09-21 10:50:56.982  5742  5742 V BluetoothAdapterState: isBleTurningOn()=false
09-21 10:50:56.982  5742  5742 V BluetoothAdapterState: isBleTurningOff()=false
09-21 10:50:56.983  5742  5754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-21 10:50:56.983  5742  5754 D BluetoothAdapterProperties: ScanMode =  20
09-21 10:50:56.983  5742  5754 D BluetoothAdapterProperties: State =  11
,09-21 10:50:56.984  5742  5758 D BluetoothAdapterProperties: Scan Mode:21
09-21 10:50:56.984  5742  5754 D BluetoothAdapterProperties: Setting state to 12
09-21 10:50:56.984  5742  5754 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-21 10:50:56.984  5742  5758 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 10:50:56.984  3189  3715 D BluetoothMap: onBluetoothStateChange: up=true
09-21 10:50:56.986  5742  5754 I BluetoothAdapterState: Entering OnState
09-21 10:50:56.986   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 10:50:56.987  5593  5605 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 10:50:56.987  3189  3189 D BluetoothMap: Proxy object connected
09-21 10:50:56.988  3189  3189 D MapProfile: Bluetooth service connected
09-21 10:50:56.988  3189  3189 D BluetoothMap: getConnectedDevices()
09-21 10:50:56.988  3189  3204 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-21 10:50:56.990   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-21 10:50:56.991   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 10:50:56.991  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:56.991  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:56.991  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:56.991  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:56.991  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:56.991  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:56.991  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:56.991  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:56.991  3189  3715 D BluetoothPbap: onBluetoothStateChange: up=true
09-21 10:50:56.991  3189  3189 D BluetoothInputDevice: Proxy object connected
09-21 10:50:56.992  3189  3189 D HidProfile: Bluetooth service connected
09-21 10:50:56.992   928   928 D BluetoothA2dp: Proxy object connected
09-21 10:50:56.994  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:50:56.994  5593  5606 D BluetoothPbap: onBluetoothStateChange: up=true
,09-21 10:50:56.995  5742  5742 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-21 10:50:56.995  5742  5742 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-21 10:50:56.997  5742  5742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 10:50:56.997  3189  3204 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-21 10:50:56.998  3585  3600 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-21 10:50:56.999  5593  5605 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 10:50:57.000  5742  5742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 10:50:57.000  3189  3203 D BluetoothPan: onBluetoothStateChange on: true
09-21 10:50:57.001  5742  5742 D ObexServerSockets: Succeed to create listening sockets 
09-21 10:50:57.001  5742  5742 D ObexServerSockets0: startAccept()
09-21 10:50:57.001  5742  5742 D ObexServerSockets0: prepareForNewConnect()
,09-21 10:50:57.002  5593  5606 D BluetoothMap: onBluetoothStateChange: up=true
,09-21 10:50:57.002  5593  5593 D BluetoothA2dp: Proxy object connected
09-21 10:50:57.003  5742  5742 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-21 10:50:57.004  5742  5742 D BluetoothSdpJni: SDP Create record success - handle: 0
09-21 10:50:57.004  5742  5780 D ObexServerSockets0: Accepting socket connection...
09-21 10:50:57.004  5742  5781 D ObexServerSockets0: Accepting socket connection...
09-21 10:50:57.005   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 10:50:57.005  3189  3204 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 10:50:57.005  3189  3189 D BluetoothPan: BluetoothPAN Proxy object connected
09-21 10:50:57.005  3189  3189 D PanProfile: Bluetooth service connected
,09-21 10:50:57.006  3189  3189 D BluetoothA2dp: Proxy object connected
09-21 10:50:57.006  5593  5779 D BluetoothPan: onBluetoothStateChange on: true
09-21 10:50:57.008  5593  5606 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-21 10:50:57.010  5593  5593 D BluetoothMap: Proxy object connected
09-21 10:50:57.010  5593  5593 D MapProfile: Bluetooth service connected
09-21 10:50:57.010  5593  5593 D BluetoothMap: getConnectedDevices()
09-21 10:50:57.011  5742  5742 D BluetoothMapService: onReceive
09-21 10:50:57.011  5742  5742 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-21 10:50:57.012  5742  5742 D BluetoothMapService: STATE_ON
09-21 10:50:57.012   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-21 10:50:57.012  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:57.013  5593  5593 D BluetoothPan: BluetoothPAN Proxy object connected
09-21 10:50:57.013  5593  5593 D PanProfile: Bluetooth service connected
09-21 10:50:57.013  5593  5593 D BluetoothInputDevice: Proxy object connected
09-21 10:50:57.013  5593  5593 D HidProfile: Bluetooth service connected
09-21 10:50:57.014  5742  5782 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 10:50:57.015  5742  5782 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-21 10:50:57.015  5742  5782 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-21 10:50:57.018  5593  5593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-21 10:50:57.023  5593  5593 D DockEventReceiver: finishStartingService: stopping service
,09-21 10:50:57.024  3694  3694 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 10:50:57.031  5593  5593 D BluetoothPbap: Proxy object connected
,09-21 10:50:57.031  5593  5593 D PbapServerProfile: Bluetooth service connected
,09-21 10:50:57.037  5742  5742 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-21 10:50:57.037  5742  5742 D ObexServerSockets0: prepareForNewConnect()
09-21 10:50:57.037  3189  3189 D BluetoothPbap: Proxy object connected
,09-21 10:50:57.037  3189  3189 D PbapServerProfile: Bluetooth service connected
09-21 10:50:57.038  5742  5787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 10:50:57.056  5742  5791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 10:50:57.057  5742  5791 I BtOppRfcommListener: Accept thread started.
,09-21 10:50:57.088  3189  3204 D BluetoothHeadset: Proxy object connected
,09-21 10:50:57.088  3189  3189 D HeadsetProfile: Bluetooth service connected
09-21 10:50:57.088   928   928 D BluetoothHeadset: Proxy object connected
09-21 10:50:57.088   928   928 D BluetoothHeadset: Proxy object connected
09-21 10:50:57.089  3585  4016 D BluetoothHeadset: Proxy object connected
09-21 10:50:57.089   928   928 D BluetoothHeadset: Proxy object connected
09-21 10:50:57.089  5593  5779 D BluetoothHeadset: Proxy object connected
09-21 10:50:57.091  5593  5593 D HeadsetProfile: Bluetooth service connected
,09-21 10:50:57.091   928   945 D BluetoothHeadset: Proxy object connected
,09-21 10:50:57.099  3189  3203 D BluetoothHeadset: Proxy object connected
,09-21 10:50:57.099  3189  3189 D HeadsetProfile: Bluetooth service connected
09-21 10:50:57.099  3585  3598 D BluetoothHeadset: Proxy object connected
,09-21 10:50:57.105   928   945 D BluetoothHeadset: Proxy object connected
,09-21 10:50:57.966  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:57.966  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:57.966  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:57.966  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 10:50:57.966  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:57.966  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:57.966  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:57.966  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 10:50:57.972  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 10:50:57.976  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 10:50:57.976  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@574ea65 added. We now have 8 listener(s)
,09-21 10:50:57.976  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 10:50:57.983   928   938 D WifiService: setWifiEnabled: false pid=5541, uid=10077
09-21 10:50:57.983   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 10:50:57.992  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:50:57.993   928   939 D WifiService: setWifiEnabled: true pid=5541, uid=10077
09-21 10:50:57.993   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 10:50:57.999   507   921 D SoftapController: Softap fwReload - Ok
,09-21 10:50:58.005   507   921 D CommandListener: Setting iface cfg
,09-21 10:50:58.005   507   921 D CommandListener: Trying to bring down wlan0
,09-21 10:50:58.007   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-21 10:50:58.012   928  3032 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 10:50:58.623   928  3032 D wifi    : set interface wlan0 flags (UP)
,09-21 10:50:58.628   928  3032 I WifiHAL : Initializing wifi
09-21 10:50:58.628   928  3032 I WifiHAL : Creating socket
09-21 10:50:58.633   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-21 10:50:58.634   928  3032 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-21 10:50:58.634   928  3032 D wifi    : Did set static halHandle = 0x7f708c43a0
,09-21 10:50:58.634   928  3032 D wifi    : halHandle = 0x7f708c43a0, mVM = 0x7f8cf4d140, mCls = 0x10190a
09-21 10:50:58.635   928  3032 D wifi    : array field set
09-21 10:50:58.635   928  3032 I WifiNative-HAL: interface[0] = wlan0
09-21 10:50:58.637   928  5796 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547349087136
,09-21 10:50:58.637   928  5796 D wifi    : waitForHalEvents called, vm = 0x7f8cf4d140, obj = 0x10190a, env = 0x7f711edac0
,09-21 10:50:58.695  5797  5797 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-21 10:50:58.715  5797  5797 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 10:50:58.725  5797  5797 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 10:50:58.726  5797  5797 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-21 10:50:58.738   928  3032 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-21 10:50:58.751   928  3032 D WifiConfigStore: Loading config and enabling all networks 
,09-21 10:50:58.755  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:58.755  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:58.755  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:58.755  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:58.755  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:58.755  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:58.755  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:58.755  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 10:50:58.757  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 10:50:58.758  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:50:58.762   928  3032 D WifiConfigStore: loaded 0 passpoint configs
,09-21 10:50:58.762   928  3032 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-21 10:50:58.763   928  3032 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-21 10:50:58.763   928  3032 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-21 10:50:58.764   928  3032 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-21 10:50:58.765   928  3032 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-21 10:50:58.765   928  3032 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-21 10:50:58.765   928  3032 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-21 10:50:58.768   928  3032 D WifiNative-HAL: Setting external_sim to 1
,09-21 10:50:58.768  4357  4357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 10:50:58.768   928  3032 D wifi    : setting dfs flag to true, 0x7f6e3a0e80
,09-21 10:50:58.769   928  3032 D WifiStateMachine: Setting OUI to DA-A1-19
09-21 10:50:58.769   928  3032 D wifi    : setting scan oui 0x7f6e3a0e80
09-21 10:50:58.769   928  3032 D WifiHAL : Sending mac address OUI
,09-21 10:50:58.773   928  3032 E native  : do suspend false
,09-21 10:50:58.779   928   928 D RttService: SCAN_AVAILABLE : 3
09-21 10:50:58.779   928  3032 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-21 10:50:58.779   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-21 10:50:58.780   928  3147 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-21 10:50:58.781   507   921 D CommandListener: Setting iface cfg
,09-21 10:50:58.784   928  3023 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-21 10:50:58.784   928  3023 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-21 10:50:58.793   928  3023 D WifiNative-HAL: p2pGetDeviceAddress
,09-21 10:50:58.797   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=200229 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
09-21 10:50:58.797   928  3023 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-21 10:50:59.005  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 10:50:59.005  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:50:59.005  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:50:59.005  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:50:59.005  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:50:59.005  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:50:59.005  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:50:59.005  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 10:50:59.010  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 10:50:59.019  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-21 10:50:59.021  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-21 10:50:59.027  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6c055b3 Bundle[{}]
,09-21 10:50:59.027  5541  5587 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 10:50:59.028  5541  5587 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-21 10:50:59.028  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-21 10:50:59.029  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-21 10:50:59.030  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-21 10:50:59.031  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-21 10:50:59.036  5541  5587 I System.out: Running OutgoingSocketThread
,09-21 10:50:59.038  5541  5799 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 152)
,09-21 10:50:59.039  5541  5799 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38710
09-21 10:50:59.039  5541  5799 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-21 10:51:00.039  5541  5587 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 153)
,09-21 10:51:00.039  5541  5587 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 153)
,09-21 10:51:00.047  5541  5587 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-21 10:51:00.048  5541  5587 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-21 10:51:00.049  5541  5587 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 159)
,09-21 10:51:00.054  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 10:51:00.055  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150c33a added. We now have 2 listener(s)
,09-21 10:51:00.059  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 10:51:00.059  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:51:00.059  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 10:51:00.060  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 10:51:00.060  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bafbeb added. We now have 9 listener(s)
09-21 10:51:00.060  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:51:00.061  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 10:51:00.067  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 10:51:00.074  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:51:00.074  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:51:00.074  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:51:00.074  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:51:00.074  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:51:00.074  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:51:00.074  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:51:00.074  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 10:51:00.077  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:51:00.077  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:51:00.077  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 10:51:00.078  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cec7e1 added. We now have 3 listener(s)
,09-21 10:51:00.079  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:51:00.080  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:51:00.080  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-21 10:51:00.080  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:51:00.080  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:51:00.080  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf7d906 added. We now have 10 listener(s)
09-21 10:51:00.080  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:51:00.080  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:51:00.080  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:51:00.080  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:51:00.081  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 10:51:00.081  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.081  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:51:00.081  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:51:00.081  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.081  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@150c33a removed from the list
09-21 10:51:00.081  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.081  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bafbeb removed from the list
09-21 10:51:00.081  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:51:00.081  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 10:51:00.082  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.082  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.083  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.083  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:51:00.083  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.084  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bafbeb not in the list
09-21 10:51:00.084  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.084  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 10:51:00.085  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:51:00.085  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.085  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.085  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf7d906 removed from the list
09-21 10:51:00.085  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:51:00.085  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 10:51:00.085  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.085  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.085  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cec7e1 removed from the list
09-21 10:51:00.086  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 10:51:00.086  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b6bc7 added. We now have 2 listener(s)
09-21 10:51:00.088  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:51:00.088  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:51:00.088  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:51:00.088  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 10:51:00.088  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fddb5f4 added. We now have 9 listener(s)
09-21 10:51:00.088  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:51:00.089  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 10:51:00.092  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:51:00.095  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:51:00.095  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:51:00.095  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:51:00.095  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:51:00.095  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:51:00.095  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:51:00.095  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:51:00.095  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 10:51:00.096  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:51:00.097  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 10:51:00.097  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 10:51:00.097  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a87f92 added. We now have 3 listener(s)
09-21 10:51:00.098  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:51:00.098  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:51:00.099  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-21 10:51:00.099  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:51:00.099  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:51:00.099  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@888fd63 added. We now have 10 listener(s)
09-21 10:51:00.099  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:51:00.100  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:51:00.100  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 10:51:00.100  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 10:51:00.100  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:51:00.100  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 10:51:00.100  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:51:00.103  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 10:51:00.103  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 10:51:00.107  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 10:51:00.108  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-21 10:51:00.108  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 10:51:00.111  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 10:51:00.111  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-21 10:51:00.111  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 10:51:00.112  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:51:00.114  5742  5770 D BtGatt.GattService: registerClient() - UUID=e7dc75aa-bb4b-4476-aa38-6e7ac23dc1fc
09-21 10:51:00.115  5742  5758 D BtGatt.GattService: onClientRegistered() - UUID=e7dc75aa-bb4b-4476-aa38-6e7ac23dc1fc, clientIf=5
09-21 10:51:00.116  5541  5551 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-21 10:51:00.117  5742  5778 D BtGatt.GattService: start scan with filters
,09-21 10:51:00.120  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-21 10:51:00.120  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 10:51:00.120  5742  5761 D BtGatt.ScanManager: handling starting scan
09-21 10:51:00.120  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 10:51:00.120  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 10:51:00.122  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 10:51:00.122  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 10:51:00.122  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 10:51:00.123  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 10:51:00.124  5742  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba02f04
,09-21 10:51:00.126  5541  5587 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 10:51:00.126  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 10:51:00.126  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 10:51:00.126  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.126  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 10:51:00.126  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-21 10:51:00.126  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 10:51:00.126  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-21 10:51:00.126  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-21 10:51:00.127  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 10:51:00.127  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 10:51:00.127  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:51:00.128  5742  5778 D BtGatt.GattService: stopScan() - queue size =1
09-21 10:51:00.129  5742  5753 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 10:51:00.129  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 10:51:00.129  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 10:51:00.129  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 10:51:00.129  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 10:51:00.129  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-21 10:51:00.130  5742  5758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 10:51:00.130  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.131  5742  5761 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-21 10:51:00.131  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:51:00.131  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 10:51:00.131  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 10:51:00.131  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-21 10:51:00.132  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 10:51:00.133  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:51:00.133  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:51:00.133  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:51:00.134  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:51:00.135  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:51:00.135  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-21 10:51:00.135  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 10:51:00.135  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.135  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:51:00.135  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.135  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b6bc7 removed from the list
09-21 10:51:00.135  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.135  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fddb5f4 removed from the list
09-21 10:51:00.135  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,09-21 10:51:00.135  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.136  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.136  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.136  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.137  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:51:00.137  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 10:51:00.137  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.137  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.137  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fddb5f4 not in the list
,09-21 10:51:00.137  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.137  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.137  5742  5761 D BtGatt.ScanManager: Starting BLE batch scan
09-21 10:51:00.137  5742  5761 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 10:51:00.138  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:51:00.138  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.138  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.138  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@888fd63 removed from the list
09-21 10:51:00.138  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:51:00.138  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.138  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.138  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.139  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a87f92 removed from the list
09-21 10:51:00.139  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 10:51:00.139  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7840cbf added. We now have 2 listener(s)
09-21 10:51:00.141  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:51:00.141  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:51:00.141  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:51:00.141  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:51:00.141  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d5cf8c added. We now have 9 listener(s)
09-21 10:51:00.142  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 10:51:00.142  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 10:51:00.145  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 10:51:00.147  5742  5758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-21 10:51:00.147  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 10:51:00.149  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:51:00.149  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:51:00.149  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:51:00.149  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:51:00.149  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:51:00.149  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:51:00.149  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:51:00.149  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 10:51:00.151  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-21 10:51:00.151  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:51:00.151  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.151  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:51:00.151  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 10:51:00.151  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a006eea added. We now have 3 listener(s)
,09-21 10:51:00.153  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:51:00.153  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:51:00.153  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:51:00.153  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:51:00.153  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f6b5db added. We now have 10 listener(s)
09-21 10:51:00.153  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 10:51:00.153  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:51:00.153  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:51:00.154  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:51:00.154  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 10:51:00.154  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 10:51:00.154  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:51:00.154  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 10:51:00.155  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:51:00.158  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 10:51:00.158  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.158  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 10:51:00.158  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 10:51:00.158  5742  5761 D BtGatt.ScanManager: stopping BLe Batch
,09-21 10:51:00.161  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 10:51:00.162  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-21 10:51:00.162  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 10:51:00.163  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 10:51:00.163  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.163  5742  5761 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-21 10:51:00.164  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-21 10:51:00.164  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 10:51:00.165  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-21 10:51:00.165  5541  5587 D BluetoothAdapter: STATE_ON
,09-21 10:51:00.167  5742  5778 D BtGatt.GattService: registerClient() - UUID=f7d9710a-858b-4322-9e16-1a3aea310352
,09-21 10:51:00.167  5742  5758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 10:51:00.167  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.168  5742  5758 D BtGatt.GattService: onClientRegistered() - UUID=f7d9710a-858b-4322-9e16-1a3aea310352, clientIf=5
,09-21 10:51:00.169  5541  5633 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 10:51:00.169  5742  5770 D BtGatt.GattService: start scan with filters
,09-21 10:51:00.171  5742  5761 D BtGatt.ScanManager: handling starting scan
09-21 10:51:00.171  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 10:51:00.171  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-21 10:51:00.171  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 10:51:00.171  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 10:51:00.173  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 10:51:00.174  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 10:51:00.174  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 10:51:00.175  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 10:51:00.175  5742  5758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 10:51:00.175  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.176  5742  5761 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 10:51:00.178  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-21 10:51:00.178  5541  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-21 10:51:00.178  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:51:00.178  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:51:00.178  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:51:00.178  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:51:00.178  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.178  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 10:51:00.178  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.179  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7840cbf removed from the list
09-21 10:51:00.179  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-21 10:51:00.179  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d5cf8c removed from the list
09-21 10:51:00.179  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:51:00.179  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 10:51:00.180  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-21 10:51:00.180  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 10:51:00.180  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-21 10:51:00.180  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.180  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.180  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:51:00.180  5742  5761 D BtGatt.ScanManager: Starting BLE batch scan
09-21 10:51:00.180  5742  5761 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 10:51:00.181  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.181  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:51:00.181  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.182  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d5cf8c not in the list
09-21 10:51:00.182  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 10:51:00.182  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-21 10:51:00.182  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 10:51:00.182  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 10:51:00.182  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 10:51:00.182  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:51:00.183  5742  5752 D BtGatt.GattService: stopScan() - queue size =1
09-21 10:51:00.183  5742  5753 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 10:51:00.183  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 10:51:00.183  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 10:51:00.183  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 10:51:00.183  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 10:51:00.183  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 10:51:00.185  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:51:00.185  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-21 10:51:00.185  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 10:51:00.185  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 10:51:00.186  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 10:51:00.187  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-21 10:51:00.187  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.187  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.187  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f6b5db removed from the list
09-21 10:51:00.187  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:51:00.187  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:51:00.187  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.187  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:51:00.187  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 10:51:00.187  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.187  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:51:00.187  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a006eea removed from the list
09-21 10:51:00.188  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 10:51:00.188  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e20d4b7 added. We now have 2 listener(s)
09-21 10:51:00.189  5742  5758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 10:51:00.189  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.189  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 10:51:00.189  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:51:00.189  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:51:00.189  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:51:00.189  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1548424 added. We now have 9 listener(s)
09-21 10:51:00.189  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:51:00.190  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 10:51:00.192  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 10:51:00.193  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 10:51:00.193  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 10:51:00.196  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:51:00.196  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:51:00.196  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:51:00.196  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:51:00.196  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:51:00.196  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:51:00.196  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:51:00.196  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 10:51:00.198  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:51:00.198  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 10:51:00.198  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 10:51:00.198  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcbf142 added. We now have 3 listener(s)
09-21 10:51:00.198  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 10:51:00.198  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.199  5742  5761 D BtGatt.ScanManager: stopping BLe Batch
09-21 10:51:00.199  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:51:00.199  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:51:00.199  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:51:00.200  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 10:51:00.200  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:51:00.200  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e640553 added. We now have 10 listener(s)
09-21 10:51:00.200  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:51:00.200  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:51:00.200  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 10:51:00.200  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 10:51:00.200  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 10:51:00.200  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 10:51:00.200  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 10:51:00.203  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 10:51:00.203  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 10:51:00.204  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 10:51:00.204  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.204  5742  5761 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-21 10:51:00.206  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 10:51:00.207  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 10:51:00.207  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 10:51:00.209  5742  5758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-21 10:51:00.209  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 10:51:00.211  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-21 10:51:00.211  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 10:51:00.211  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 10:51:00.211  5541  5587 D BluetoothAdapter: STATE_ON
,09-21 10:51:00.213  5742  5753 D BtGatt.GattService: registerClient() - UUID=5ffd8cec-c1f0-4ced-97b8-29b678d9ed52
,09-21 10:51:00.213  5742  5758 D BtGatt.GattService: onClientRegistered() - UUID=5ffd8cec-c1f0-4ced-97b8-29b678d9ed52, clientIf=5
09-21 10:51:00.214  5541  5551 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 10:51:00.214  5742  5783 D BtGatt.GattService: start scan with filters
,09-21 10:51:00.216  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-21 10:51:00.216  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 10:51:00.216  5742  5761 D BtGatt.ScanManager: handling starting scan
09-21 10:51:00.216  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 10:51:00.216  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 10:51:00.218  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 10:51:00.218  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 10:51:00.218  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 10:51:00.219  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 10:51:00.221  5742  5758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 10:51:00.221  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.221  5742  5761 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-21 10:51:00.223  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:51:00.223  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:51:00.223  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:51:00.224  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:51:00.224  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.224  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 10:51:00.224  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.224  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e20d4b7 removed from the list
09-21 10:51:00.224  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.224  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1548424 removed from the list
09-21 10:51:00.224  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:51:00.224  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:51:00.224  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.224  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-21 10:51:00.224  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.224  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:51:00.226  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.226  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 10:51:00.226  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:51:00.226  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-21 10:51:00.226  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.226  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1548424 not in the list
09-21 10:51:00.226  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 10:51:00.226  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 10:51:00.226  5742  5761 D BtGatt.ScanManager: Starting BLE batch scan
09-21 10:51:00.226  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 10:51:00.226  5742  5761 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 10:51:00.226  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 10:51:00.226  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 10:51:00.227  5541  5587 D BluetoothAdapter: STATE_ON
09-21 10:51:00.227  5742  5753 D BtGatt.GattService: stopScan() - queue size =1
,09-21 10:51:00.234  5742  5770 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 10:51:00.234  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 10:51:00.234  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-21 10:51:00.234  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 10:51:00.234  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 10:51:00.234  5742  5758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 10:51:00.234  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 10:51:00.234  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 10:51:00.235  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:51:00.235  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 10:51:00.235  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 10:51:00.235  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 10:51:00.236  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 10:51:00.236  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-21 10:51:00.236  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.236  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.237  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e640553 removed from the list
09-21 10:51:00.237  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:51:00.237  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:51:00.237  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.237  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 10:51:00.237  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.237  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.237  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 10:51:00.237  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcbf142 removed from the list
09-21 10:51:00.237  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 10:51:00.237  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39fa3af added. We now have 2 listener(s)
09-21 10:51:00.238  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:51:00.239  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:51:00.239  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:51:00.239  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 10:51:00.239  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.239  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:51:00.239  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73233bc added. We now have 9 listener(s)
09-21 10:51:00.239  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 10:51:00.239  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 10:51:00.241  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 10:51:00.244  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 10:51:00.244  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 10:51:00.244  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 10:51:00.244  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 10:51:00.244  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 10:51:00.244  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 10:51:00.244  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 10:51:00.244  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 10:51:00.245  5742  5758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 10:51:00.245  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 10:51:00.245  5742  5761 D BtGatt.ScanManager: stopping BLe Batch
09-21 10:51:00.246  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 10:51:00.246  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 10:51:00.246  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 10:51:00.246  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8a669a added. We now have 3 listener(s)
09-21 10:51:00.247  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:51:00.247  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 10:51:00.248  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 10:51:00.248  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 10:51:00.248  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 10:51:00.248  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4ccbcb added. We now have 10 listener(s)
09-21 10:51:00.248  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 10:51:00.248  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 10:51:00.248  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 10:51:00.248  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 10:51:00.249  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 10:51:00.249  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 10:51:00.249  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.249  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 10:51:00.249  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.249  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39fa3af removed from the list
09-21 10:51:00.249  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.249  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73233bc removed from the list
09-21 10:51:00.249  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
09-21 10:51:00.249  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.250  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.250  5742  5758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 10:51:00.250  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.250  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 10:51:00.250  5742  5761 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 10:51:00.251  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.251  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:51:00.251  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.251  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73233bc not in the list
09-21 10:51:00.251  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.251  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 10:51:00.252  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 10:51:00.253  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 10:51:00.253  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 10:51:00.253  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4ccbcb removed from the list
09-21 10:51:00.253  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 10:51:00.253  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 10:51:00.253  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 10:51:00.253  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 10:51:00.253  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8a669a removed from the list
,09-21 10:51:00.254  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-21 10:51:00.254  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-21 10:51:00.254  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-21 10:51:00.254  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 10:51:00.254  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-21 10:51:00.254  5742  5758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 10:51:00.255  5742  5758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 10:51:00.255  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-21 10:51:00.260  5541  5800 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name)
,09-21 10:51:00.260  5541  5800 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: My test thread name)
09-21 10:51:00.260  5541  5800 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-21 10:51:00.261  5541  5801 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name)
09-21 10:51:00.261  5541  5801 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name)
,09-21 10:51:00.261  5541  5801 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-21 10:51:00.263  5541  5587 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-21 10:51:00.263  5541  5587 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-21 10:51:00.263  5541  5587 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-21 10:51:00.263  5541  5587 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-21 10:51:00.263  5541  5587 D com.test.thalitest.ThaliTestRunner: Total duration: 22612 ms
09-21 10:51:00.264  5541  5587 I jxcore-log: *Native tests were executed*
09-21 10:51:00.264  5541  5587 I jxcore-log: 
,09-21 10:51:00.265  5541  5587 I jxcore-log: Total number of executed tests:  80
09-21 10:51:00.265  5541  5587 I jxcore-log: 
,09-21 10:51:00.265  5541  5587 I jxcore-log: Number of passed tests:  80
09-21 10:51:00.265  5541  5587 I jxcore-log: 
09-21 10:51:00.265  5541  5587 I jxcore-log: Number of failed tests:  0
09-21 10:51:00.265  5541  5587 I jxcore-log: 
09-21 10:51:00.265  5541  5587 I jxcore-log: Number of ignored tests:  0
09-21 10:51:00.265  5541  5587 I jxcore-log: 
09-21 10:51:00.266  5541  5587 I jxcore-log: Total duration:  22612
09-21 10:51:00.266  5541  5587 I jxcore-log: 
09-21 10:51:00.266  5541  5587 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-21 10:51:00.266  5541  5587 I jxcore-log: 
09-21 10:51:00.268  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 10:51:00.268  5541  5587 I jxcore-log: 
09-21 10:51:00.271  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 10:51:00.271  5541  5587 I jxcore-log: 
09-21 10:51:00.272  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 10:51:00.272  5541  5587 I jxcore-log: 
09-21 10:51:00.273  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 10:51:00.273  5541  5587 I jxcore-log: 
09-21 10:51:00.274  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 10:51:00.274  5541  5587 I jxcore-log: 
,09-21 10:51:00.275  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 10:51:00.275  5541  5587 I jxcore-log: 
09-21 10:51:00.276  5541  5541 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-21 10:51:00.278  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 10:51:00.278  5541  5587 I jxcore-log: 
09-21 10:51:00.280  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.280  5541  5587 I jxcore-log: 
09-21 10:51:00.281  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.281  5541  5587 I jxcore-log: 
09-21 10:51:00.281  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.281  5541  5587 I jxcore-log: 
09-21 10:51:00.282  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.282  5541  5587 I jxcore-log: 
09-21 10:51:00.283  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 10:51:00.283  5541  5587 I jxcore-log: 
09-21 10:51:00.285  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.285  5541  5587 I jxcore-log: 
09-21 10:51:00.285  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.285  5541  5587 I jxcore-log: 
09-21 10:51:00.286  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.286  5541  5587 I jxcore-log: 
09-21 10:51:00.287  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.287  5541  5587 I jxcore-log: 
09-21 10:51:00.287  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.287  5541  5587 I jxcore-log: 
09-21 10:51:00.288  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.288  5541  5587 I jxcore-log: 
09-21 10:51:00.289  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.289  5541  5587 I jxcore-log: 
,09-21 10:51:00.289  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.289  5541  5587 I jxcore-log: 
09-21 10:51:00.290  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.290  5541  5587 I jxcore-log: 
09-21 10:51:00.290  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 10:51:00.290  5541  5587 I jxcore-log: 
,09-21 10:51:00.291  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.291  5541  5587 I jxcore-log: 
09-21 10:51:00.292  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.292  5541  5587 I jxcore-log: 
09-21 10:51:00.292  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.292  5541  5587 I jxcore-log: 
09-21 10:51:00.293  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.293  5541  5587 I jxcore-log: 
09-21 10:51:00.294  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.294  5541  5587 I jxcore-log: 
09-21 10:51:00.295  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.295  5541  5587 I jxcore-log: 
09-21 10:51:00.295  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 10:51:00.295  5541  5587 I jxcore-log: 
,09-21 10:51:00.634  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 10:51:00.639  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 10:51:00.639  5541  5587 I jxcore-log: 
,09-21 10:51:00.688  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 10:51:00.692  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 10:51:00.692  5541  5587 I jxcore-log: 
,09-21 10:51:00.738  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 10:51:00.741  5541  5587 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 10:51:00.741  5541  5587 I jxcore-log: 
,09-21 10:51:00.774  5802  5802 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-21 10:51:00.780  5802  5802 D AndroidRuntime: CheckJNI is OFF
,09-21 10:51:00.809  5802  5802 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-21 10:51:00.842  5802  5802 I Radio-JNI: register_android_hardware_Radio DONE
,09-21 10:51:00.860  5802  5802 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-21 10:51:00.870   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-21 10:51:00.871   928   941 I ActivityManager: Killing 5541:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-21 10:51:00.947   928  3463 D GraphicsStats: Buffer count: 2
,09-21 10:51:00.947   928  3232 I WindowState: WIN DEATH: Window{1f792e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-21 10:51:00.947   928  3044 D WifiService: Client connection lost with reason: 4
,09-21 10:51:01.005   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-21 10:51:01.005   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-21 10:51:01.006   928   951 I art     : Starting a blocking GC Explicit
09-21 10:51:01.006   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-21 10:51:01.006   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-21 10:51:01.006   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:51:01.006   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:51:01.006   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 10:51:01.006   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-21 10:51:01.008   928   941 I ActivityManager:   Force finishing activity ActivityRecord{48d4d14 u0 com.test.thalitest/.MainActivity t2}
,09-21 10:51:01.018   928  3586 W ActivityManager: Spurious death for ProcessRecord{b29529 0:com.test.thalitest/u0a77}, curProc for 5541: null
,09-21 10:51:01.022   928   946 W WindowManager: Attempted to add application window with unknown token Token{f1e19bd ActivityRecord{48d4d14 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-21 10:51:01.023   928   946 W WindowManager: Token{f1e19bd ActivityRecord{48d4d14 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{f1e19bd ActivityRecord{48d4d14 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-21 10:51:01.023   928   946 W WindowManager: view not successfully added to wm, removing view
09-21 10:51:01.023   928   946 W WindowManager: Exception when adding starting window
09-21 10:51:01.023   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{d0397c8 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-21 10:51:01.023   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-21 10:51:01.023   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-21 10:51:01.023   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-21 10:51:01.023   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-21 10:51:01.023   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-21 10:51:01.023   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:51:01.023   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:51:01.023   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 10:51:01.023   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-21 10:51:01.083   928   951 I art     : Explicit concurrent mark sweep GC freed 24610(1564KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.490ms total 77.108ms
,09-21 10:51:01.104   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-21 10:51:01.106  5802  5802 I art     : System.exit called, status: 0
09-21 10:51:01.107  5802  5802 I AndroidRuntime: VM exiting with result code 0.
,09-21 10:51:01.111   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-21 10:51:01.120   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-21 10:51:01.125  5742  5742 D BluetoothMapAppObserver: onReceive
,09-21 10:51:01.125  5742  5742 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-21 10:51:01.132  3500  3500 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-21 10:51:01.134  3717  4058 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-21 10:51:01.134   928  3014 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-21 10:51:01.155  3500  5813 I Keyboard.Facilitator.DecoderInitializer: run()
,09-21 10:51:01.177  3500  5813 I Decoder : createOrResetDecoder
,09-21 10:51:01.185  3585  3585 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-21 10:51:01.183  3467  5815 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-21 10:51:01.193  3694  3694 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-21 10:51:01.193  3694  3694 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-21 10:51:01.205   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-21 10:51:01.220  3694  3694 I ConfigService: onCreate
,09-21 10:51:01.237  5374  5374 W kworker/1:3: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 10:51:01.237  5374  5374 W kworker/1:3: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 10:51:01.247  5374  5374 W kworker/1:3: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 10:51:01.255  3500  5813 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-21 10:51:01.257  4002  5819 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-21 10:51:01.257  4002  5819 D AccountUtils: Clearing selected account for com.test.thalitest
09-21 10:51:01.258  3467  3507 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj76A083976) - 
,09-21 10:51:01.286  4002  5819 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-21 10:51:01.314  3467  5815 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-21 10:51:01.315  3467  5815 I Process : Sending signal. PID: 3467 SIG: 9
,09-21 10:51:01.322  4002  5819 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:51:01.322  4002  5819 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-21 10:51:01.323  4002  5819 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 10:51:01.324  4002  5819 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-21 10:51:01.347  3500  5813 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-21 10:51:01.350  3500  5813 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-21 10:51:01.350  3500  5813 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-21 10:51:01.361  3500  5813 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-21 10:51:01.361  3500  5813 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-21 10:51:01.362  3500  5813 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-21 10:51:01.362  3500  5813 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-21 10:51:01.363  3500  5813 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-21 10:51:01.363  3500  5813 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-21 10:51:01.363  3500  5813 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-21 10:51:01.363  3500  5813 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-21 10:51:01.363  3500  5813 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-21 10:51:01.363  3500  5813 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-21 10:51:01.370  4002  4002 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-21 10:51:01.370  4002  4002 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-21 10:51:01.384  4002  4002 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-21 10:51:01.385  4002  4002 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-21 10:51:01.399   380   380 E lowmemorykiller: Error writing /proc/3467/oom_score_adj; errno=22
09-21 10:51:01.400   380   380 E lowmemorykiller: Error writing /proc/3467/oom_score_adj; errno=22
,09-21 10:51:01.405  4785  5829 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-21 10:51:01.419   928  3494 I ActivityManager: Start proc 5833:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,09-21 10:51:01.446  4785  5829 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-21 10:51:01.471  4002  5828 W BaseAppContext: Using Auth Proxy for data requests.
,09-21 10:51:01.485   928  4043 I ActivityManager: Start proc 5838:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-21 10:51:01.492  4002  4002 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-21 10:51:01.496  4002  5828 W BaseAppContext: Using Auth Proxy for data requests.
,09-21 10:51:01.506  4002  5841 I GMPM-SVC: App measurement is starting up
,09-21 10:51:01.517  4002  5841 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-21 10:51:01.518  4002  5841 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-21 10:51:01.534   928   939 I ActivityManager: Process android.process.acore (pid 3467) has died
,09-21 10:51:01.535   928   939 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-21 10:51:01.635   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
