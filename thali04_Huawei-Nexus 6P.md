#### Test 85202518082e18e_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-15 10:01:45.490   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 10:01:45.491   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:01:46.020  5338  5338 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 10:01:46.026  5338  5338 D AndroidRuntime: CheckJNI is OFF
09-15 10:01:46.052  5338  5338 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 10:01:46.082  5338  5338 I Radio-JNI: register_android_hardware_Radio DONE
09-15 10:01:46.097  5338  5338 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 10:01:46.105   927  3401 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 10:01:46.148   927  3401 I ActivityManager: Start proc 5347:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 10:01:46.152  5338  5338 D AndroidRuntime: Shutting down VM
09-15 10:01:46.233  5347  5347 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 10:01:46.266  5347  5347 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 10:01:46.289  5347  5347 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 9492-9511)
09-15 10:01:46.289  5347  5347 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 10:01:46.309  5347  5347 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4ae9cab}
09-15 10:01:46.309  5347  5347 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 10:01:46.310  5347  5347 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 10:01:46.315  5347  5347 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 10:01:46.316  5347  5347 E SysUtils: ApplicationContext is null in ApplicationStatus
09-15 10:01:46.349  5347  5347 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-15 10:01:46.363  5347  5347 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 10:01:46.363  5347  5347 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 10:01:46.363  5347  5347 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 10:01:46.363  5347  5347 I Adreno  : Build Date                       : 12/06/15
09-15 10:01:46.363  5347  5347 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 10:01:46.363  5347  5347 I Adreno  : Local Branch                     : mybranch17112971
09-15 10:01:46.363  5347  5347 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 10:01:46.363  5347  5347 I Adreno  : Remote Branch                    : NONE
09-15 10:01:46.363  5347  5347 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 10:01:46.416   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@367e643:true
,09-15 10:01:46.449   409   409 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[26153]" dev="sockfs" ino=26153 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 10:01:46.449   409   409 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[26153]" dev="sockfs" ino=26153 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 10:01:46.466  5347  5347 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 10:01:46.476  5347  5347 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 10:01:46.549   750   750 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32053]" dev="sockfs" ino=32053 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 10:01:46.549   750   750 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32053]" dev="sockfs" ino=32053 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 10:01:46.551  5347  5385 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 10:01:46.553  3037  3037 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[26165]" dev="sockfs" ino=26165 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 10:01:46.553  3037  3037 W Binder_4: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[26165]" dev="sockfs" ino=26165 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 10:01:46.563  5347  5372 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 10:01:46.589  5347  5385 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 10:01:46.675   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +487ms (total +556ms)
,09-15 10:01:46.689  5347  5347 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5347
,09-15 10:01:46.774  5347  5347 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 10:01:47.012  5347  5386 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -562038480
,09-15 10:01:47.045  5347  5386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 10:01:47.045  5347  5386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 10:01:47.045  5347  5386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 10:01:47.045  5347  5386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 10:01:47.045  5347  5386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-15 10:01:47.045  5347  5386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2673e0 added. We now have 1 listener(s)
,09-15 10:01:47.050  5347  5386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-15 10:01:47.052  5347  5386 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 10:01:47.053  5347  5386 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 10:01:47.054  5347  5386 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-15 10:01:47.059  5347  5386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ac953f added. We now have 1 listener(s)
09-15 10:01:47.060  5347  5386 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:01:47.065   927  2827 D WifiService: New client listening to asynchronous messages
,09-15 10:01:47.066  5347  5386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:01:47.066  5347  5386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 10:01:47.066  5347  5386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 10:01:47.066  5347  5386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-15 10:01:47.066  5347  5386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-15 10:01:47.070  5347  5386 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:01:47.070  5347  5386 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-15 10:01:47.084  5347  5386 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-15 10:01:47.085  5347  5386 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:01:47.085  5347  5386 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:01:47.085  5347  5386 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:01:47.085  5347  5386 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:01:47.085  5347  5386 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:01:47.085  5347  5386 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:01:47.085  5347  5386 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:01:47.085  5347  5386 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:01:47.085  5347  5386 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-15 10:01:47.085  5347  5386 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:01:47.085  5347  5386 I io.jxcore.node.LifeCycleMonitor: start: OK
09-15 10:01:47.088  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:01:47.091  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:01:47.113  5347  5347 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 10:01:47.558  5347  5356 I art     : Background sticky concurrent mark sweep GC freed 76935(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.258ms total 233.248ms
,09-15 10:01:48.149  5347  5394 W jxcore-log: Initializing JXcore engine
,09-15 10:01:48.149  5347  5394 W jxcore-log: JXcore engine is ready
,09-15 10:01:48.216  5394  5394 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11772 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-15 10:01:48.216  5394  5394 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[13642]" dev="sockfs" ino=13642 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-15 10:01:48.216  5394  5394 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 10:01:48.216  5394  5394 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31603]" dev="sockfs" ino=31603 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 10:01:48.230  5347  5394 W jxcore-log: Starting JXcore engine
,09-15 10:01:48.307  5347  5394 W jxcore-log: Platform android
09-15 10:01:48.307  5347  5394 W jxcore-log: 
,09-15 10:01:48.307  5347  5394 W jxcore-log: Process ARCH arm
09-15 10:01:48.307  5347  5394 W jxcore-log: 
,09-15 10:01:48.405  5347  5394 I jxcore-log: JXcore Cordova bridge is ready!
09-15 10:01:48.405  5347  5394 I jxcore-log: 
,09-15 10:01:48.406  5347  5394 W jxcore-log: JXcore engine is started
,09-15 10:01:48.414  5347  5386 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 10:01:48.421  5347  5347 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 10:01:58.247  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 10:01:58.247  5347  5394 I jxcore-log: 
,09-15 10:01:58.250  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 10:01:58.250  5347  5394 I jxcore-log: 
,09-15 10:01:58.255  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:01:58.255  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:01:58.255  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:01:58.255  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:01:58.255  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:01:58.255  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:01:58.255  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:01:58.255  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 10:01:58.257  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 10:01:58.259  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 10:01:58.259  5347  5394 I jxcore-log: 
,09-15 10:01:58.261  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 10:01:58.261  5347  5394 I jxcore-log: 
,09-15 10:01:58.513  5347  5394 I jxcore-log: Running unit tests
09-15 10:01:58.513  5347  5394 I jxcore-log: 
,09-15 10:01:58.513  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 10:01:58.513  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1be9460 added. We now have 2 listener(s)
09-15 10:01:58.514  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:01:58.514  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 10:01:58.514  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:01:58.514  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:01:58.515  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a9d19 added. We now have 2 listener(s)
09-15 10:01:58.515  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:01:58.515  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 10:01:58.517  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:01:58.520  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:01:58.520  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:01:58.520  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:01:58.520  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:01:58.520  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:01:58.520  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:01:58.520  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:01:58.520  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 10:01:58.521  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 10:01:58.521  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:01:58.522  5347  5394 D executeNativeTests: Running unit tests
,09-15 10:01:58.530  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:01:58.536  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:01:58.558  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 10:01:58.558  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af added. We now have 3 listener(s)
09-15 10:01:58.559  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 10:01:58.559  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 10:01:58.559  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:01:58.559  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:01:58.559  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc added. We now have 3 listener(s)
,09-15 10:01:58.559  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 10:01:58.560  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 10:01:58.561  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:01:58.563  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:01:58.563  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:01:58.563  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:01:58.563  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:01:58.563  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:01:58.563  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:01:58.563  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:01:58.563  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 10:01:58.564  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:01:58.564  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 10:01:58.565  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 10:01:58.565  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:01:58.565  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:01:58.566  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:01:58.566  5347  5394 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-15 10:01:58.566  5347  5394 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 10:01:58.566  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 10:01:58.566  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:01:58.566  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:01:58.566  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:01:58.567  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:01:58.567  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:01:58.567  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:01:58.567  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:01:58.568  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:01:58.568  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:01:58.568  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 10:01:58.568  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af removed from the list
09-15 10:01:58.568  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:01:58.568  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc removed from the list
,09-15 10:01:58.573  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:01:58.582  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:01:58.583  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:01:58.583  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:01:58.583  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:01:58.584  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:01:58.584  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:01:58.584  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:01:58.584  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:01:58.584  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:01:58.585  5347  5394 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-15 10:01:58.585  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:01:58.585  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:01:58.585  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:01:58.585  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:01:58.585  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:01:58.585  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:01:58.585  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:01:58.585  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:01:58.585  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:01:58.586  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:01:58.586  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:01:58.586  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:01:58.586  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:01:58.586  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:01:58.586  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 10:01:58.586  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:01:58.586  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:01:58.586  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:01:58.588  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 10:01:58.589  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-15 10:01:58.590  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:01:58.590  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:01:58.590  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:01:58.590  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:01:58.590  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:01:58.590  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:01:58.590  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:01:58.590  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:01:58.590  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:01:58.590  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:01:58.590  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:01:58.590  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:01:58.590  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:01:58.590  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:01:58.590  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:01:58.591  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:01:58.591  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:01:58.591  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:01:58.591  5347  5394 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 10:01:58.592  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:01:58.594  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:01:58.594  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:01:58.594  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:01:58.594  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:01:58.594  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:01:58.594  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:01:58.594  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:01:58.594  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:01:58.595  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:01:58.595  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:01:58.595  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 10:01:58.595  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 10:01:58.595  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 10:01:58.595  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:01:58.595  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:01:58.597  5347  5394 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 10:01:58.597  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 10:01:58.598  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:01:58.600  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:01:58.600  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 10:01:58.601  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 10:01:58.601  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 10:01:58.602  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-15 10:01:58.603  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-15 10:01:58.603  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 10:01:58.604  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 10:01:58.604  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 10:01:58.604  5347  5394 D BluetoothAdapter: STATE_ON
09-15 10:01:58.606  4257  4271 D BtGatt.GattService: registerClient() - UUID=0fb35448-fc71-4759-a557-613436162314
09-15 10:01:58.607  4257  4332 D BtGatt.GattService: onClientRegistered() - UUID=0fb35448-fc71-4759-a557-613436162314, clientIf=5
09-15 10:01:58.608  5347  5358 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 10:01:58.609  4257  4488 D BtGatt.GattService: start scan with filters
09-15 10:01:58.614  4257  4335 D BtGatt.ScanManager: handling starting scan
09-15 10:01:58.614  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 10:01:58.614  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 10:01:58.614  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 10:01:58.614  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 10:01:58.615  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 10:01:58.615  4257  4335 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:01:58.615  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 10:01:58.616  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 10:01:58.616  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 10:01:58.617  5347  5394 I io.jxcore.node.ConnectionHelper: start: OK
09-15 10:01:58.624  4257  4332 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 10:01:58.624  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:01:58.624  4257  4335 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 10:01:58.630  4257  4332 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 10:01:58.630  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:01:58.631  4257  4335 D BtGatt.ScanManager: Starting BLE batch scan
09-15 10:01:58.631  4257  4335 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 10:01:58.641  4257  4332 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 10:01:58.641  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:01:58.647  4257  4332 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 10:01:58.648  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:01:59.118  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 10:01:59.118  5347  5347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 10:01:59.118  5347  5347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:01:59.455   927  5071 D NetlinkSocketObserver: NeighborEvent{elapsedMs=342677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-15 10:02:00.492   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:01.493   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:02.493   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:03.494   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:03.621  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:02:03.621  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:03.622  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 10:02:03.622  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:03.622  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 10:02:03.622  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:02:03.622  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:02:03.622  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:02:03.622  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 10:02:03.623  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 10:02:03.623  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 10:02:03.624  5347  5394 D BluetoothAdapter: STATE_ON
09-15 10:02:03.626  4257  4271 D BtGatt.GattService: stopScan() - queue size =1
,09-15 10:02:03.629  4257  4488 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 10:02:03.631  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:02:03.632  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 10:02:03.632  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 10:02:03.632  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 10:02:03.632  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 10:02:03.635  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:02:03.635  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 10:02:03.636  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:02:03.636  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 10:02:03.637  4257  4257 D BtGatt.ScanManager: awakened up at time 346859
09-15 10:02:03.638  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:02:03.641  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:02:03.641  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:02:03.641  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:03.641  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:02:03.641  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:02:03.641  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:02:03.642  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:03.642  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:03.642  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:03.642  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:03.642  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:03.648  4257  4332 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 10:02:03.649  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:03.649  4257  4335 D BtGatt.ScanManager: stopping BLe Batch
,09-15 10:02:03.661  4257  4332 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 10:02:03.661  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:02:03.661  4257  4335 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 10:02:03.686  4257  4332 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-15 10:02:03.686  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:02:03.687  4257  4332 D BtGatt.GattService: current time is 346909338670
,09-15 10:02:03.688  4257  4332 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -95, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -89, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -78, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -87, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-15 10:02:03.692  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-15 10:02:03.694  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-15 10:02:03.695  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-15 10:02:03.695  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-15 10:02:03.695  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-15 10:02:03.696  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-15 10:02:04.142  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 10:02:04.496   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:05.496   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:02:08.654  5347  5394 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-15 10:02:08.660  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:02:08.670  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:02:08.670  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:08.670  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:08.670  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:08.670  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:02:08.670  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:08.670  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:02:08.670  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 10:02:08.674  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 10:02:08.675  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:02:08.675  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 10:02:08.675  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-15 10:02:08.675  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 10:02:08.676  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:02:08.676  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:02:08.680  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:08.683  5347  5394 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 10:02:08.683  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 10:02:08.686  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:08.691  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 10:02:08.693  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 10:02:08.693  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 10:02:08.699  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 10:02:08.699  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 10:02:08.699  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 10:02:08.700  5347  5394 D BluetoothAdapter: STATE_ON
09-15 10:02:08.704  4257  4488 D BtGatt.GattService: registerClient() - UUID=86e1a064-29ca-4c3b-8f5c-6cf78227a443
09-15 10:02:08.704  4257  4332 D BtGatt.GattService: onClientRegistered() - UUID=86e1a064-29ca-4c3b-8f5c-6cf78227a443, clientIf=5
,09-15 10:02:08.705  5347  5357 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 10:02:08.705  4257  4480 D BtGatt.GattService: start scan with filters
,09-15 10:02:08.710  4257  4335 D BtGatt.ScanManager: handling starting scan
09-15 10:02:08.711  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 10:02:08.711  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 10:02:08.711  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 10:02:08.712  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 10:02:08.716  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 10:02:08.716  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 10:02:08.716  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 10:02:08.718  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 10:02:08.721  4257  4332 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-15 10:02:08.721  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:08.721  4257  4335 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 10:02:08.724  5347  5394 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 10:02:08.729  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:02:08.729  5347  5394 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 10:02:08.729  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:08.729  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 10:02:08.729  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:08.730  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 10:02:08.730  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:02:08.730  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:02:08.730  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:02:08.730  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 10:02:08.730  4257  4332 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 10:02:08.730  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:08.730  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 10:02:08.730  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 10:02:08.730  4257  4335 D BtGatt.ScanManager: Starting BLE batch scan
09-15 10:02:08.730  4257  4335 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 10:02:08.733  5347  5394 D BluetoothAdapter: STATE_ON
,09-15 10:02:08.734  4257  4488 D BtGatt.GattService: stopScan() - queue size =1
09-15 10:02:08.735  4257  4480 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 10:02:08.736  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:02:08.736  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 10:02:08.736  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 10:02:08.736  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 10:02:08.736  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 10:02:08.741  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:02:08.741  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 10:02:08.741  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:02:08.741  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 10:02:08.742  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:02:08.744  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:08.744  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:02:08.744  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:08.744  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:02:08.744  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:02:08.744  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:08.744  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:02:08.744  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:08.744  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:08.744  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:08.744  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:08.744  4257  4332 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 10:02:08.744  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:08.745  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:08.745  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:08.746  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:08.746  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:08.746  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:02:08.747  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:08.747  5347  5394 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 10:02:08.749  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:02:08.752  4257  4332 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 10:02:08.752  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:02:08.755  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:02:08.755  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:08.755  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:08.755  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:08.755  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:02:08.755  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:08.755  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:02:08.755  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 10:02:08.757  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:08.757  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:02:08.757  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 10:02:08.759  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 10:02:08.759  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 10:02:08.759  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:02:08.759  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:02:08.761  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:08.762  5347  5394 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 10:02:08.762  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 10:02:08.763  4257  4332 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 10:02:08.763  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:02:08.763  4257  4335 D BtGatt.ScanManager: stopping BLe Batch
09-15 10:02:08.765  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:08.766  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 10:02:08.767  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 10:02:08.767  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 10:02:08.769  4257  4332 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 10:02:08.769  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:08.769  4257  4335 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 10:02:08.771  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 10:02:08.771  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 10:02:08.772  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 10:02:08.772  5347  5394 D BluetoothAdapter: STATE_ON
,09-15 10:02:08.775  4257  4488 D BtGatt.GattService: registerClient() - UUID=2c64284e-1269-4dcd-8f34-f0737b6b9838
09-15 10:02:08.775  4257  4332 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 10:02:08.775  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:08.775  4257  4332 D BtGatt.GattService: onClientRegistered() - UUID=2c64284e-1269-4dcd-8f34-f0737b6b9838, clientIf=5
,09-15 10:02:08.776  5347  5358 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 10:02:08.776  4257  4271 D BtGatt.GattService: start scan with filters
,09-15 10:02:08.778  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 10:02:08.778  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 10:02:08.778  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 10:02:08.778  4257  4335 D BtGatt.ScanManager: handling starting scan
09-15 10:02:08.778  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 10:02:08.780  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 10:02:08.780  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 10:02:08.780  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 10:02:08.781  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 10:02:08.783  5347  5394 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 10:02:08.784  4257  4332 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 10:02:08.784  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:08.784  4257  4335 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 10:02:08.789  4257  4332 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 10:02:08.789  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:08.789  4257  4335 D BtGatt.ScanManager: Starting BLE batch scan
,09-15 10:02:08.789  4257  4335 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 10:02:08.797  4257  4332 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 10:02:08.797  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:02:08.802  4257  4332 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 10:02:08.802  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:02:09.281  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-15 10:02:09.282  5347  5347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 10:02:09.282  5347  5347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:02:10.499   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:11.499   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:12.500   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:13.501   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:13.783  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:02:13.783  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:13.784  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-15 10:02:13.784  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:13.784  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 10:02:13.784  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:02:13.785  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:02:13.785  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:02:13.785  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 10:02:13.785  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 10:02:13.785  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 10:02:13.787  5347  5394 D BluetoothAdapter: STATE_ON
09-15 10:02:13.789  4257  4480 D BtGatt.GattService: stopScan() - queue size =1
,09-15 10:02:13.792  4257  4272 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 10:02:13.792  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:02:13.792  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 10:02:13.793  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 10:02:13.793  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-15 10:02:13.793  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 10:02:13.795  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:02:13.796  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 10:02:13.796  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:02:13.796  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 10:02:13.797  4257  4257 D BtGatt.ScanManager: awakened up at time 357019
09-15 10:02:13.797  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:02:13.800  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:02:13.801  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:02:13.801  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:02:13.805  4257  4332 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 10:02:13.805  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:13.805  4257  4335 D BtGatt.ScanManager: stopping BLe Batch
,09-15 10:02:13.812  4257  4332 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 10:02:13.812  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:13.812  4257  4335 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 10:02:13.829  4257  4332 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-15 10:02:13.829  4257  4332 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:02:13.829  4257  4332 D BtGatt.GattService: current time is 357051796417
09-15 10:02:13.829  4257  4332 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -78, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -76, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -79, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -87, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -97, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-15 10:02:13.830  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-15 10:02:13.830  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-15 10:02:13.830  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-15 10:02:13.830  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-15 10:02:13.830  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-15 10:02:13.830  4257  4332 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-15 10:02:14.302  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 10:02:14.302  5347  5347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 10:02:14.303  5347  5347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:02:14.502   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:15.503   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:02:18.801  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:02:18.802  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 10:02:18.802  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.802  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:02:18.802  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.802  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 10:02:18.803  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.803  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:02:18.803  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.803  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:18.803  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.805  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:18.805  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:18.808  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 10:02:18.808  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.808  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:02:18.808  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.810  5347  5394 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-15 10:02:18.812  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:18.812  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:18.812  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.812  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:02:18.812  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.812  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.813  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
,09-15 10:02:18.813  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.813  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.813  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:18.813  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:18.813  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.813  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.814  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:18.816  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:18.816  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.817  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.817  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:18.819  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 10:02:18.819  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:18.819  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:18.819  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.820  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:18.820  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.820  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:18.820  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.820  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.820  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.820  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:18.820  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.820  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.821  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:18.821  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.823  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:18.823  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.823  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.823  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.824  5347  5394 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-15 10:02:18.824  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:18.825  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 10:02:18.825  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.825  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:18.825  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.825  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.825  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.825  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.825  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:18.825  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:18.825  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.826  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.826  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:18.826  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.828  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 10:02:18.828  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.828  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.828  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.829  5347  5394 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-15 10:02:18.829  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:18.829  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:18.829  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.829  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:18.830  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:18.830  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.830  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.830  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.830  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.830  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:18.830  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.830  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.830  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:18.830  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.832  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:18.832  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.832  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.832  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.834  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 10:02:18.834  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:02:18.834  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-15 10:02:18.834  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 10:02:18.834  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:02:18.834  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:02:18.834  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 10:02:18.835  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:02:18.835  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:02:18.835  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:02:18.835  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:18.835  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.835  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:18.835  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.835  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.836  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.836  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.836  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.836  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:02:18.836  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.836  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.836  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.836  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.838  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:18.838  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.838  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.838  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.839  5347  5394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 10:02:18.840  5347  5394 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 10:02:18.840  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 10:02:18.845  5347  5394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 10:02:18.845  5347  5394 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-15 10:02:18.845  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 10:02:18.845  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 10:02:18.845  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 10:02:18.845  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 10:02:18.845  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 10:02:18.845  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 10:02:18.845  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 10:02:18.845  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-15 10:02:18.845  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 10:02:18.846  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 10:02:18.847  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 10:02:18.847  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 10:02:18.847  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 10:02:18.847  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 10:02:18.847  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 10:02:18.847  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 10:02:18.847  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-15 10:02:18.847  5347  5394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-15 10:02:18.848  5347  5394 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 10:02:18.848  5347  5394 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-15 10:02:18.848  5347  5394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 10:02:18.848  5347  5394 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 10:02:18.848  5347  5394 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-15 10:02:18.848  5347  5394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 10:02:18.848  5347  5394 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 10:02:18.848  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-15 10:02:18.852  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-15 10:02:18.853  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-15 10:02:18.853  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-15 10:02:18.854  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-15 10:02:18.854  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-15 10:02:18.854  5347  5394 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-15 10:02:18.854  5347  5394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 10:02:18.855  5347  5394 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-15 10:02:18.855  5347  5397 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-15 10:02:18.856  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:18.856  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:18.856  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.856  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:02:18.856  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.856  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.856  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-15 10:02:18.857  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.857  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.858  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.858  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:18.858  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.858  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:18.858  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.858  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.858  5347  5398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-15 10:02:18.860  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:18.860  5347  5397 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:02:18.860  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.861  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.861  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:18.862  5347  5394 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-15 10:02:18.862  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:18.859  4271  4271 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29477]" dev="sockfs" ino=29477 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 10:02:18.859  4271  4271 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29477]" dev="sockfs" ino=29477 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:02:18.863  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:18.863  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.863  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:02:18.863  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.863  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.863  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.863  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.863  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.863  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:18.863  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.863  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.863  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.863  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:18.865  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:18.865  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.865  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.865  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.866  5347  5394 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-15 10:02:18.866  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:18.867  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:18.867  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.867  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:02:18.867  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.867  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.867  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.867  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.867  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.867  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:18.867  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.867  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.868  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.868  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.869  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:18.869  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.869  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.869  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:18.870  5347  5394 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-15 10:02:18.870  5347  5394 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-15 10:02:18.870  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 10:02:18.870  5347  5394 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-15 10:02:18.870  5347  5394 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 10:02:18.870  5347  5394 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-15 10:02:18.871  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 10:02:18.871  5347  5394 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-15 10:02:18.871  5347  5394 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 10:02:18.871  5347  5394 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 10:02:18.871  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 10:02:18.871  5347  5394 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-15 10:02:18.871  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:18.871  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:18.871  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:18.871  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:18.871  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.872  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.872  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.872  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.872  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.872  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:18.872  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:18.872  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.872  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.872  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.873  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:18.873  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:18.873  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.874  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.875  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:18.875  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.875  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:18.875  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:18.875  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:18.875  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:18.875  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:02:18.875  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:18.875  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:23.335   927  5071 D NetlinkSocketObserver: NeighborEvent{elapsedMs=366557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 10:02:23.876  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:02:23.876  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:23.876  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:23.876  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.877  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.877  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
,09-15 10:02:23.877  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:23.877  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:23.878  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:23.878  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:02:23.878  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.878  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.878  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:23.879  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.879  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:23.879  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:23.879  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.879  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:23.879  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.879  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.883  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:23.883  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 10:02:23.883  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:02:23.884  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:23.891  5347  5394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-15 10:02:23.892  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:02:23.894  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 10:02:23.896  5347  5394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 10:02:23.897  5347  5394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 10:02:23.898  5347  5347 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-15 10:02:23.898  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-15 10:02:23.898  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:02:23.899  5347  5399 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:02:23.900  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:23.900  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 10:02:23.900  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 10:02:23.900  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 10:02:23.900  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.901  5347  5394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 10:02:23.901  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:23.901  5347  5347 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 10:02:23.901  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.901  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-15 10:02:23.901  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:02:23.901  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 10:02:23.901  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.902  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:23.899  4488  4488 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29482]" dev="sockfs" ino=29482 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 10:02:23.899  4488  4488 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29482]" dev="sockfs" ino=29482 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:02:23.904  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:02:23.904  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:23.904  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:02:23.905  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:23.905  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:02:23.905  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:02:23.905  5347  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 10:02:23.905  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:23.905  5347  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 10:02:23.905  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:23.905  5347  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-15 10:02:23.905  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:23.905  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.906  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.906  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:23.906  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.906  5347  5347 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 10:02:23.906  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:23.906  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:02:23.906  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.906  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.907  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.907  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.910  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 10:02:23.910  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:23.910  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.910  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:23.913  5347  5394 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-15 10:02:23.913  5347  5394 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 10:02:23.913  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 10:02:23.914  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:02:23.915  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-15 10:02:23.915  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:23.915  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:23.915  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:23.916  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:23.917  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:23.918  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.918  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:23.918  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.919  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:23.919  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:23.919  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.919  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:23.919  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.919  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.922  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:23.922  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:23.922  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.922  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:23.927  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:23.927  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:23.927  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 10:02:23.927  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:23.927  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.927  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:23.928  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:23.928  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.928  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:23.928  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:02:23.928  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.928  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.928  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.928  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:23.929  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:23.929  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 10:02:23.929  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.929  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:23.930  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:02:23.931  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:02:23.931  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:02:23.931  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:02:23.931  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:23.931  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.931  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49be6af not in the list
09-15 10:02:23.931  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.931  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
09-15 10:02:23.931  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:23.931  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:23.931  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.931  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:23.931  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:23.933  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:02:23.933  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:02:23.933  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:23.933  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104babc not in the list
,09-15 10:02:23.934  5347  5394 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-15 10:02:23.935  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 10:02:23.935  5347  5394 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-15 10:02:23.935  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 10:02:23.935  5347  5394 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-15 10:02:23.935  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 10:02:23.937  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 10:02:23.937  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-15 10:02:23.938  5347  5394 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-15 10:02:23.938  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-15 10:02:23.938  5347  5394 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-15 10:02:23.938  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 10:02:23.938  5347  5394 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-15 10:02:23.938  5347  5394 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-15 10:02:23.939  5347  5394 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-15 10:02:23.939  5347  5394 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-15 10:02:23.939  5347  5394 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-15 10:02:23.940  5347  5394 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-15 10:02:23.940  5347  5394 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-15 10:02:23.940  5347  5394 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-15 10:02:23.942  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 10:02:23.942  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b56773e added. We now have 3 listener(s)
09-15 10:02:23.942  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:02:23.944  5347  5394 D BluetoothAdapter: enable(): BT is already enabled..!
,09-15 10:02:23.945   927  3413 D WifiService: setWifiEnabled: true pid=5347, uid=10077
09-15 10:02:23.945   927  3413 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:02:23.993  4257  4450 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-15 10:02:23.993  5347  5397 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,09-15 10:02:23.995  4257  4466 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-15 10:02:24.406  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 10:02:25.504   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:26.505   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:27.506   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:28.507   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:28.950  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 10:02:28.951  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@419d99f added. We now have 4 listener(s)
09-15 10:02:28.951  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:02:28.964  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:02:28.964  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@419d99f removed from the list
09-15 10:02:28.964  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:02:28.964  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:28.965  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:28.967  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 10:02:28.968  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4a4aec added. We now have 4 listener(s)
09-15 10:02:28.969  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:02:28.973  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:02:28.973  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4a4aec removed from the list
09-15 10:02:28.974  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:02:28.974  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:28.975  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:28.976  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:02:28.976  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fdfeb5 added. We now have 4 listener(s)
,09-15 10:02:28.977  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:02:28.980   927  3283 D WifiService: setWifiEnabled: false pid=5347, uid=10077
,09-15 10:02:28.980   927  3283 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:02:28.986   927  2821 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-15 10:02:28.986   927  2821 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 10:02:28.986   927  2821 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 10:02:28.986   927  2821 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 10:02:28.990  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:02:28.992  4257  4328 D BluetoothAdapterState: Current state: ON, message: 23
,09-15 10:02:28.992  4257  4328 D BluetoothAdapterProperties: Setting state to 13
09-15 10:02:28.997  4257  4328 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 10:02:28.998  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:02:28.998  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:28.998  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:28.998  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:28.998  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:02:28.998  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:28.998  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:02:28.998  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:02:28.998  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:02:28.998  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:28.998  4257  4328 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 10:02:28.999  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:02:28.999  4257  4328 I BluetoothAdapterState: Entering PendingCommandState
09-15 10:02:28.999   927  2821 E native  : do suspend true
,09-15 10:02:29.001  4257  4332 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:02:29.001  4257  4328 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 10:02:29.002  4257  4257 D HeadsetService: Received stop request...Stopping profile...
,09-15 10:02:29.004   927   927 D BluetoothHeadset: Proxy object disconnected
,09-15 10:02:29.004   927   927 D BluetoothHeadset: Proxy object disconnected
09-15 10:02:29.004  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.004  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:29.004  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:29.004  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:29.004  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:29.004  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:29.004  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:29.004  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:02:29.004  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:02:29.004  3347  3678 D BluetoothHeadset: Proxy object disconnected
,09-15 10:02:29.005   927   927 D BluetoothHeadset: Proxy object disconnected
09-15 10:02:29.005  4257  4257 V BluetoothAdapterState: isTurningOff()=true
,09-15 10:02:29.005  4257  4257 V BluetoothAdapterState: isTurningOn()=false
,09-15 10:02:29.005  4257  4257 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:29.005  2971  2985 D BluetoothHeadset: Proxy object disconnected
09-15 10:02:29.005  4257  4257 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:29.005  2971  2971 D HeadsetProfile: Bluetooth service disconnected
09-15 10:02:29.006  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.006  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 10:02:29.010  4257  4257 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-15 10:02:29.010  4257  4257 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 10:02:29.010  4257  4450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:29.010  4257  4450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:29.010  4257  4450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:29.011  4257  4332 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 10:02:29.011  4257  4332 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 10:02:29.011  4257  4257 D A2dpService: Received stop request...Stopping profile...
09-15 10:02:29.011  4257  4483 D A2dpStateMachine: Exit Disconnected: -1
09-15 10:02:29.013  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:29.016  2971  2971 D BluetoothA2dp: Proxy object disconnected
09-15 10:02:29.017   927   927 D BluetoothA2dp: Proxy object disconnected
,09-15 10:02:29.017  4257  4257 D HidService: Received stop request...Stopping profile...
09-15 10:02:29.017  4257  4257 D HidService: Stopping Bluetooth HidService
09-15 10:02:29.017  2971  2971 D BluetoothInputDevice: Proxy object disconnected
09-15 10:02:29.017  2971  2971 D HidProfile: Bluetooth service disconnected
09-15 10:02:29.018  4257  4257 D HealthService: Received stop request...Stopping profile...
09-15 10:02:29.019  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.019  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:29.019  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:29.019  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:29.019  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:29.019  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:29.019  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:29.019  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:02:29.019  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 10:02:29.019  4257  4257 D PanService: Received stop request...Stopping profile...
09-15 10:02:29.020  2971  2971 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 10:02:29.020  2971  2971 D PanProfile: Bluetooth service disconnected
09-15 10:02:29.020  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.020  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:29.020  4257  4257 D BluetoothMapService: Received stop request...Stopping profile...
09-15 10:02:29.021  4257  4257 D BluetoothMapService: stop()
09-15 10:02:29.021  4257  4257 D BluetoothMapAppObserver: deinitObservers()
09-15 10:02:29.021  4257  4257 D BluetoothMapAppObserver: removeReceiver()
09-15 10:02:29.023  2971  2971 D BluetoothMap: Proxy object disconnected
09-15 10:02:29.023  2971  2971 D MapProfile: Bluetooth service disconnected
09-15 10:02:29.023  4257  4257 D SapService: Received stop request...Stopping profile...
09-15 10:02:29.023  4257  4257 V SapService: stop()
,09-15 10:02:29.024   927  5072 D DhcpClient: Clearing IP address
09-15 10:02:29.024   508   921 D CommandListener: Clearing all IP addresses on wlan0
09-15 10:02:29.025  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.025  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:29.025  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:29.025  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:29.025  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:29.025  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:29.025  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:29.025  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:02:29.025  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:02:29.025  4257  4257 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:29.025  4257  4257 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:29.025  4257  4257 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 10:02:29.025  4257  4257 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:29.025  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.025  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 10:02:29.028  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:29.028  4257  4332 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 10:02:29.028  4257  4257 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:29.028  4257  4257 V BluetoothAdapterState: isTurningOn()=false
,09-15 10:02:29.028  4257  4257 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:29.028  4257  4450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:29.028  4257  4257 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:29.028  4257  4450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:29.028  4257  4257 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 10:02:29.028  4257  4450 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 10:02:29.028  4257  4450 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 10:02:29.028  4257  4257 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 10:02:29.028  4257  4450 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 10:02:29.029  4257  4450 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 10:02:29.029  4257  4332 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 10:02:29.029  4257  4257 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:29.029  4257  4257 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:29.029  4257  4257 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:29.029  4257  4257 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:29.029  4257  4257 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 10:02:29.029  4257  4332 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 10:02:29.029  4257  4257 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 10:02:29.029   508   921 D CommandListener: Setting iface cfg
09-15 10:02:29.029  4257  4257 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:29.029  4257  4257 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:29.029  4257  4257 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:29.029  4257  4257 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:29.030  4257  4257 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 10:02:29.030  4257  4257 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 10:02:29.030  4257  4257 D BluetoothMapService: MAP Service closeService in
09-15 10:02:29.030  4257  4257 D BluetoothMapMasInstance0: MAP Service shutdown
,09-15 10:02:29.030  4257  4257 D ObexServerSockets0: shutdown(block = true)
09-15 10:02:29.031  4257  4490 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-15 10:02:29.031  4257  4257 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 10:02:29.031  4257  4257 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 10:02:29.031  4257  4491 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 10:02:29.032  4257  4466 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 10:02:29.032  4257  4257 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:29.032  4257  4257 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:29.032  4257  4257 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:29.032  4257  4257 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:29.032  4257  4257 D BluetoothMapService: cleanup()
09-15 10:02:29.033  4257  4257 D BluetoothMapService: MAP Service closeService in
09-15 10:02:29.033   927  5073 D DhcpClient: Receive thread stopped
09-15 10:02:29.033  4257  4257 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:29.033  4257  4257 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:29.033  4257  4257 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 10:02:29.033  4257  4257 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:29.034  4257  4328 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 10:02:29.034  4257  4328 D BluetoothAdapterProperties: Setting state to 15
09-15 10:02:29.034  4257  4328 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 10:02:29.034  4257  4328 I BluetoothAdapterState: Entering BleOnState
09-15 10:02:29.038  3436  5132 V NativeCrypto: Read error: ssl=0x7f9314e400: I/O error during system call, Connection timed out
09-15 10:02:29.040  3436  5132 V NativeCrypto: SSL shutdown failed: ssl=0x7f9314e400: I/O error during system call, Broken pipe
09-15 10:02:29.040   927  2833 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-15 10:02:29.041   927  2833 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-15 10:02:29.044   534   534 E Parcel  : Reading a NULL string not supported here.
09-15 10:02:29.045  2971  2985 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 10:02:29.046   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:29.046   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:29.046  2971  3606 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:29.047  2971  2984 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 10:02:29.047   927  2833 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-15 10:02:29.047  2971  2985 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-15 10:02:29.048   927   927 D RttService: SCAN_AVAILABLE : 1
,09-15 10:02:29.049   927  2903 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 10:02:29.049  4257  4257 I BtOppRfcommListener: stopping Accept Thread
09-15 10:02:29.049  4257  5004 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 10:02:29.050  4257  5004 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 10:02:29.051  3323  3473 W QCNEJ   : |CORE| network lost: 100
09-15 10:02:29.052  3323  3473 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-15 10:02:29.052  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.052  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:29.052  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:29.052  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:29.052  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:29.052  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:29.052  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:29.052  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:29.052  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:29.053  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.054  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:29.057  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.057  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:29.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:29.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:29.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:29.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:29.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:29.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:29.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:29.058  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.058  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:02:29.060  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:02:29.060  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:29.060  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:29.060  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:29.060  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:29.060  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:29.060  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:29.060  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:29.060  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:02:29.061  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.061  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:29.061   927   940 I ActivityManager: Start proc 5406:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-15 10:02:29.063   927  2821 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-15 10:02:29.064  3347  3383 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:29.065   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 10:02:29.065  2971  3606 D BluetoothMap: onBluetoothStateChange: up=false
09-15 10:02:29.065  2971  2984 D BluetoothPan: onBluetoothStateChange on: false
,09-15 10:02:29.067   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:29.067  4257  4328 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 10:02:29.067  4257  4328 D BluetoothAdapterProperties: Setting state to 16
09-15 10:02:29.067  4257  4328 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 10:02:29.068  4257  4328 D BluetoothAdapterProperties: onBleDisable
09-15 10:02:29.068  4257  4328 I BluetoothAdapterState: Entering PendingCommandState
09-15 10:02:29.068  4257  4329 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 10:02:29.070  4257  4450 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 10:02:29.070  4257  4450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:29.070  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:29.071  4257  4332 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:02:29.072  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:29.074  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:29.075  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:29.076  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:29.077  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:29.081   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 10:02:29.083   927  2821 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-15 10:02:29.084   927  2821 E native  : do suspend true
,09-15 10:02:29.108   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 10:02:29.109   508   921 D CommandListener: Clearing all IP addresses on wlan0
09-15 10:02:29.109   508   921 D TetherController: Setting IP forward enable = 0
09-15 10:02:29.110   927  2833 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-15 10:02:29.110   927  2833 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-15 10:02:29.113   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-15 10:02:29.115  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:29.117  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:29.118  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:29.118  4960  4960 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ae90bf6 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-15 10:02:29.124  4694  4707 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-15 10:02:29.125  4694  4707 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 10:02:29.125  4694  4707 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 10:02:29.125  4694  4707 E SarControlService: no key has been found,reset the power
09-15 10:02:29.125  4694  4732 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 10:02:29.125  4694  4732 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 10:02:29.126  4694  4732 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 10:02:29.126  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 10:02:29.126  4720  4720 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 10:02:29.127  4694  4732 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 10:02:29.127  4694  4732 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-15 10:02:29.127  4694  4732 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-15 10:02:29.130  4720  4734 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@222250c HexData = [00000000ea03000000000000ffffffff]
,09-15 10:02:29.130  4720  4734 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 10:02:29.131  4720  4734 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-15 10:02:29.131  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 10:02:29.131  4720  4720 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 10:02:29.132  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 10:02:29.133  4694  4705 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-15 10:02:29.135  5406  5406 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-15 10:02:29.137  4720  4734 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@222250c HexData = [00000000eb03000000000000ffffffff]
09-15 10:02:29.137  4720  4734 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 10:02:29.137  4720  4734 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-15 10:02:29.138  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 10:02:29.138  4694  4704 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 10:02:29.149  5406  5406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 10:02:29.154   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc1ee5a:true
,09-15 10:02:29.156  3436  3436 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:02:29.159   508   921 E Netd    : netlink response contains error (No such file or directory)
,09-15 10:02:29.161   508   921 D TetherController: Setting IP forward enable = 0
,09-15 10:02:29.170   927  3283 I ActivityManager: Start proc 5435:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-15 10:02:29.172   927  2821 D DhcpClient: doQuit
,09-15 10:02:29.172   927  2821 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 10:02:29.173  3431  3431 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-15 10:02:29.175   927  5072 D DhcpClient: onQuitting
,09-15 10:02:29.177  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:02:29.177  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:29.177  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:29.177  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:29.177  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:29.177  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:29.177  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:29.177  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:29.177  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:29.178  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.179  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:29.179  5406  5406 D LocalBluetoothProfileManager: Adding local MAP profile
09-15 10:02:29.181  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.183  5406  5406 D BluetoothMap: Create BluetoothMap proxy object
09-15 10:02:29.183  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:29.183  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:29.183  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:29.183  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:29.183  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:29.183  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:29.183  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:29.183  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:29.184  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.184  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:29.186  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:02:29.186  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:29.186  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:29.186  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:29.186  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:29.186  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:29.186  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:29.186  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:29.186  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:29.187  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:29.187  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:02:29.195  3431  3431 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 10:02:29.199  5406  5406 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-15 10:02:29.200  3431  3431 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-15 10:02:29.211  5435  5435 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-15 10:02:29.215  5406  5406 D DockEventReceiver: finishStartingService: stopping service
,09-15 10:02:29.223   927  2981 I ActivityManager: Killing 4632:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-15 10:02:29.224  3431  3431 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 10:02:29.235  3431  3431 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 10:02:29.241   927  2821 D wifi    : In wifi stop Hal
,09-15 10:02:29.241   927  2821 D wifi    : halHandle = 0x7f80969aa0, mVM = 0x7f9d00d140, mCls = 0x100aca
09-15 10:02:29.241  4104  4104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 10:02:29.241   927  3430 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 10:02:29.241   927  3430 D WifiHAL : Got a signal to exit!!!
09-15 10:02:29.241   927  3430 I WifiHAL : Exit wifi_event_loop
09-15 10:02:29.242   927  2821 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 10:02:29.242   927  2821 E WifiHAL : Event processing terminated
09-15 10:02:29.242   927  2821 D wifi    : In wifi cleaned up handler
09-15 10:02:29.242   927  2821 I WifiHAL : Internal cleanup completed
,09-15 10:02:29.244  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:29.246  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:29.246  3491  3861 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 10:02:29.247  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:29.263   927  3430 D wifi    : set interface wlan0 flags (DOWN)
,09-15 10:02:29.263   927  2821 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 10:02:29.275  4257  4332 I bt_hci  : shut_down
,09-15 10:02:29.279  4257  4338 D bt_hwcfg: hw_epilog_process
,09-15 10:02:29.279  4257  4338 I bt_vendor: low_power_mode_cb
,09-15 10:02:29.282  4257  4338 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 10:02:29.282  4257  4338 I bt_vendor: epilog_cb
09-15 10:02:29.282  4257  4338 I bt_hci  : epilog_finished_callback
09-15 10:02:29.283  4257  4332 I bt_hci_h4: hal_close
09-15 10:02:29.284  4257  4332 I bt_userial_vendor: device fd = 54 close
,09-15 10:02:29.389  4257  4329 D bt_stack_manager: event_shut_down_stack finished.
,09-15 10:02:29.389  4257  4328 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-15 10:02:29.391  4257  4328 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 10:02:29.391  4257  4257 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 10:02:29.391  4257  4257 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 10:02:29.391  4257  4257 D BtGatt.GattService: stop()
09-15 10:02:29.391  4257  4257 D BtGatt.AdvertiseManager: advertise clients cleared
09-15 10:02:29.393  4257  4257 V BluetoothAdapterState: isTurningOff()=false
09-15 10:02:29.393  4257  4257 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:29.393  4257  4257 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:29.393  4257  4257 V BluetoothAdapterState: isBleTurningOff()=true
09-15 10:02:29.393  4257  4328 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 10:02:29.393  4257  4328 D BluetoothAdapterProperties: Setting state to 10
09-15 10:02:29.393  4257  4328 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 10:02:29.394  4257  4328 I BluetoothAdapterState: Entering OffState
,09-15 10:02:29.394   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-15 10:02:29.401  4257  4257 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 10:02:29.401  4257  4257 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 10:02:29.401  4257  4257 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 10:02:29.402  4257  4329 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 10:02:29.414  4257  4329 D bt_stack_manager: event_clean_up_stack finished.
,09-15 10:02:29.422  5435  5435 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:02:29.422  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-15 10:02:29.423  5435  5435 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-15 10:02:29.423  5435  5435 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-15 10:02:29.423  5435  5435 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:02:29.423  5435  5435 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream,.java:290)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.k.d(PG:583)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:02:29.423  5435  5435 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
0,9-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:02:29.423  5435  5435 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:02:29.423  5435  5435 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:02:29.423  5435  5435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:02:29.438  4257  4257 I art     : System.exit called, status: 0
09-15 10:02:29.438  4257  4257 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-15 10:02:29.456  5406  5406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 10:02:29.459   927   937 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-15 10:02:29.460   927   937 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-15 10:02:29.460   927   937 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-15 10:02:29.460   927   937 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-15 10:02:29.460   927   937 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-15 10:02:29.460   927   937 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-15 10:02:29.460   927   937 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-15 10:02:29.460   927   937 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-15 10:02:29.460   927   937 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-15 10:02:29.460   927   937 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-15 10:02:29.460   927   937 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-15 10:02:29.460   927   937 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-15 10:02:29.466   927   944 D Tethering: InitialState.processMessage what=4
,09-15 10:02:29.488   927   937 I ActivityManager: Start proc 5469:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-15 10:02:29.489   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-15 10:02:29.489   927  3429 W ActivityManager: Spurious death for ProcessRecord{5170b88 5469:com.android.bluetooth/1002}, curProc for 4257: null
09-15 10:02:29.491  5406  5406 D DockEventReceiver: finishStartingService: stopping service
09-15 10:02:29.493   927  3405 I ActivityManager: Killing 5151:com.qualcomm.timeservice/1000 (adj 15): empty #17
09-15 10:02:29.507   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:29.569  5469  5469 D AdapterServiceConfig: Adding HeadsetService
,09-15 10:02:29.569  5469  5469 D AdapterServiceConfig: Adding A2dpService
09-15 10:02:29.569  5469  5469 D AdapterServiceConfig: Adding HidService
09-15 10:02:29.569  5469  5469 D AdapterServiceConfig: Adding HealthService
09-15 10:02:29.569  5469  5469 D AdapterServiceConfig: Adding PanService
09-15 10:02:29.569  5469  5469 D AdapterServiceConfig: Adding GattService
09-15 10:02:29.570  5469  5469 D AdapterServiceConfig: Adding BluetoothMapService
09-15 10:02:29.570  5469  5469 D AdapterServiceConfig: Adding SapService
,09-15 10:02:29.572   927  3413 I ActivityManager: Killing 4960:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-15 10:02:29.604  3436  3436 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:02:29.622  3765  3765 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-15 10:02:29.627  3765  5099 I iu.UploadsManager: num queued entries: 0
09-15 10:02:29.627  3765  5099 I iu.UploadsManager: num updated entries: 0
,09-15 10:02:29.629  3765  3765 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 10:02:29.631  3765  3765 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-15 10:02:29.632  3765  5099 I iu.SyncManager: NEXT; no task
,09-15 10:02:29.643   927  3424 I ActivityManager: Start proc 5483:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-15 10:02:29.675  5483  5483 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-15 10:02:29.685  5483  5483 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 10:02:29.691  5483  5483 D SprintDMHelper: simOperator: 
,09-15 10:02:29.691  5483  5483 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 10:02:29.703   927  3037 I ActivityManager: Start proc 5495:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-15 10:02:29.704   927  3037 I ActivityManager: Killing 5136:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-15 10:02:29.809  4104  5509 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 10:02:29.816   927  2981 I ActivityManager: Start proc 5510:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-15 10:02:29.818   927  2981 I ActivityManager: Killing 4342:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-15 10:02:29.841  5435  5458 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-15 10:02:29.875  5510  5510 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-15 10:02:29.909   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aada8ae:true
,09-15 10:02:30.060   927  3401 I ActivityManager: Killing 5209:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-15 10:02:30.101   927   938 I ActivityManager: Start proc 5524:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-15 10:02:30.131  5524  5524 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-15 10:02:30.139   927  3424 I ActivityManager: Killing 3259:android.process.acore/u0a2 (adj 15): empty #17
,09-15 10:02:30.509   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:02:34.001   927  3245 D WifiService: setWifiEnabled: true pid=5347, uid=10077
09-15 10:02:34.001   927  3245 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 10:02:34.013   508   921 D SoftapController: Softap fwReload - Ok
,09-15 10:02:34.018   508   921 D CommandListener: Setting iface cfg
,09-15 10:02:34.018   508   921 D CommandListener: Trying to bring down wlan0
,09-15 10:02:34.020   508   921 D CommandListener: Clearing all IP addresses on wlan0
,09-15 10:02:34.025   927  2821 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 10:02:34.594   927  2821 D wifi    : set interface wlan0 flags (UP)
09-15 10:02:34.597   927  2821 I WifiHAL : Initializing wifi
09-15 10:02:34.597   927  2821 I WifiHAL : Creating socket
,09-15 10:02:34.600   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 10:02:34.603   927  2821 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 10:02:34.603   927  2821 D wifi    : Did set static halHandle = 0x7f80969aa0
,09-15 10:02:34.603   927  2821 D wifi    : halHandle = 0x7f80969aa0, mVM = 0x7f9d00d140, mCls = 0x18ee
09-15 10:02:34.604   927  2821 D wifi    : array field set
09-15 10:02:34.604   927  2821 I WifiNative-HAL: interface[0] = wlan0
09-15 10:02:34.606   927  5542 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547618200224
09-15 10:02:34.606   927  5542 D wifi    : waitForHalEvents called, vm = 0x7f9d00d140, obj = 0x18ee, env = 0x7f8480a840
,09-15 10:02:34.679  5543  5543 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 10:02:34.699  5543  5543 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 10:02:34.707   927  2821 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 10:02:34.709  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:34.711  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:34.712  5543  5543 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 10:02:34.712  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:34.712  5543  5543 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 10:02:34.728   927  2821 D WifiConfigStore: Loading config and enabling all networks 
09-15 10:02:34.729  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:02:34.729  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:34.729  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:34.729  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:34.729  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:34.729  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:34.729  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:34.729  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:34.729  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:34.729  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:34.729  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:34.731  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:34.731  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:34.731  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:34.731  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:34.731  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:34.731  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:34.731  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:34.731  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:34.731  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:34.731  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:34.731  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:02:34.733  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:02:34.733  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:34.733  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:34.733  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:34.733  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:34.733  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:34.733  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:34.733  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:34.733  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:34.733  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:34.733  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:02:34.738   927  2821 D WifiConfigStore: loaded 0 passpoint configs
,09-15 10:02:34.738   927  2821 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 10:02:34.739   927  2821 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-15 10:02:34.739   927  2821 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-15 10:02:34.740   927  2821 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 10:02:34.740   927  2821 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 10:02:34.740   927  2821 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 10:02:34.741   927  2821 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-15 10:02:34.744   927  2821 D WifiNative-HAL: Setting external_sim to 1
09-15 10:02:34.744  4104  4104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 10:02:34.744   927  2821 D wifi    : setting dfs flag to true, 0x7f84ce92a0
09-15 10:02:34.745   927  2821 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 10:02:34.745   927  2821 D wifi    : setting scan oui 0x7f84ce92a0
09-15 10:02:34.745   927  2821 D WifiHAL : Sending mac address OUI
,09-15 10:02:34.762   927  2821 E native  : do suspend true
,09-15 10:02:34.768   927   927 D RttService: SCAN_AVAILABLE : 3
,09-15 10:02:34.769   927  2821 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 10:02:34.769   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 10:02:34.769   927  2903 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 10:02:34.770   508   921 D CommandListener: Setting iface cfg
,09-15 10:02:34.775   927  2820 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
09-15 10:02:34.775   927  2820 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 10:02:34.781   927  2820 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 10:02:34.786   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=378008 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,09-15 10:02:34.786   927  2820 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 10:02:37.870  5543  5543 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-15 10:02:37.921   927  2821 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-15 10:02:37.924   927  2821 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,09-15 10:02:37.924   927  2821 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 10:02:37.942   927  2821 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-15 10:02:37.987   927  2821 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-15 10:02:38.324  5543  5543 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-15 10:02:38.363  5543  5543 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-15 10:02:38.363  5543  5543 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-15 10:02:38.377   927  2821 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-15 10:02:38.378   927  2833 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-15 10:02:38.378   927  2821 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 10:02:38.399   927  2821 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 10:02:38.419   508   921 D CommandListener: Setting iface cfg
,09-15 10:02:38.424   927  2821 D WifiStateMachine: Start Dhcp Watchdog 2
,09-15 10:02:38.430   927  2821 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-15 10:02:38.441   927  5549 D DhcpClient: Receive thread started
,09-15 10:02:38.534   927  2821 E native  : do suspend false
,09-15 10:02:38.556   927  5548 D DhcpClient: Broadcasting DHCPDISCOVER
,09-15 10:02:38.571   927  5549 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172458, domain null
,09-15 10:02:38.572   927  5548 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172458 seconds
,09-15 10:02:38.574   927  5548 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-15 10:02:38.590   927  5549 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-15 10:02:38.591   927  5548 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-15 10:02:38.594   508   921 D CommandListener: Setting iface cfg
,09-15 10:02:38.599   927  2821 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-15 10:02:38.603   927  2821 E native  : do suspend true
09-15 10:02:38.604   927  5548 D DhcpClient: Scheduling renewal in 86399s
,09-15 10:02:38.630   927  2821 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-15 10:02:38.631   927  2821 D WifiConfigStore: No blacklist allowed without epno enabled
,09-15 10:02:38.632   927  2833 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-15 10:02:38.636   927  2833 D ConnectivityService: Adding iface wlan0 to network 101
,09-15 10:02:38.647   927  2821 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-15 10:02:38.685   927  2833 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-15 10:02:38.685   927  2833 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-15 10:02:38.690   927  2833 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-15 10:02:38.695   927  2833 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-15 10:02:38.697   927  2833 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-15 10:02:38.704   927  2833 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-15 10:02:38.709   927  2833 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-15 10:02:38.709   927  2833 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-15 10:02:38.709   927  2833 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-15 10:02:38.709   927  2833 D ConnectivityService:    accepting network in place of null
09-15 10:02:38.709   927  2821 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-15 10:02:38.710   927  2821 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 10:02:38.710   927  2833 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-15 10:02:38.726   927  5547 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381948, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 10:02:38.740   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 10:02:38.764   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 10:02:38.767   927  2833 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-15 10:02:38.768   927  2833 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 10:02:38.768  3323  3473 W QCNEJ   : |CORE| network available: 101
,09-15 10:02:38.769   927  2833 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-15 10:02:38.769  3323  3473 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-15 10:02:38.770  3323  3473 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-15 10:02:38.771  3323  3473 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-15 10:02:38.771   927   944 D Tethering: MasterInitialState.processMessage what=3
09-15 10:02:38.774  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:38.774  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:38.774  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:38.774  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:38.774  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:38.774  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:38.774  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:38.774  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:02:38.774  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:02:38.774  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:38.774  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:38.778  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:38.778  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:38.778  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:38.778  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:38.778  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:38.778  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:38.778  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:38.778  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:02:38.778  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:02:38.778  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:02:38.778  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:38.780  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:38.780  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:38.780  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:38.780  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:38.780  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:38.780  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:38.780  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:02:38.780  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:02:38.780  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:02:38.780  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:38.780  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 10:02:38.782  4694  4707 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-15 10:02:38.782  4694  4707 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 10:02:38.782  4694  4707 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-15 10:02:38.782  4694  4707 E SarControlService: no key has been found,reset the power
09-15 10:02:38.783  4694  4732 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 10:02:38.783  4694  4732 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 10:02:38.783  4694  4732 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 10:02:38.783  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 10:02:38.784  4720  4720 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 10:02:38.785  4694  4732 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 10:02:38.785  4694  4732 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 10:02:38.785  4694  4732 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 10:02:38.785  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 10:02:38.785  4720  4720 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-15 10:02:38.791  4720  4734 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@222250c HexData = [00000000ec03000000000000ffffffff]
,09-15 10:02:38.792  4720  4734 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 10:02:38.792  4720  4734 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-15 10:02:38.793  4720  4734 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@222250c HexData = [00000000ed03000000000000ffffffff]
09-15 10:02:38.793  4720  4734 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 10:02:38.793  4720  4734 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-15 10:02:38.796  3765  3765 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-15 10:02:38.797   927  5546 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-15 10:02:38.800  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 10:02:38.800  4694  4705 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-15 10:02:38.800  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 10:02:38.800  4694  4704 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 10:02:38.807  3765  5099 I iu.UploadsManager: num queued entries: 0
09-15 10:02:38.807  3765  5099 I iu.UploadsManager: num updated entries: 0
,09-15 10:02:38.809  3765  3765 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 10:02:38.810  3765  3765 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 10:02:38.812  5483  5483 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-15 10:02:38.816  5483  5483 D SprintDMHelper: simOperator: 
09-15 10:02:38.816  5483  5483 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 10:02:38.829  3765  5099 I iu.SyncManager: NEXT; no task
,09-15 10:02:38.859   927  5546 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 15 Sep 2016 14:02:38 GMT], X-Android-Received-Millis=[1473948158858], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473948158828]}
,09-15 10:02:38.859   927  2833 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-15 10:02:38.860   927  2833 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-15 10:02:38.860   927  2833 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-15 10:02:38.861   927  2833 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-15 10:02:38.921  4104  5563 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-15 10:02:39.011   927  3401 D WifiService: setWifiEnabled: false pid=5347, uid=10077
,09-15 10:02:39.011   927  3401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:02:39.018   927  2821 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-15 10:02:39.018   927  2821 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 10:02:39.019   927  2821 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 10:02:39.019   927  2821 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 10:02:39.042   927  2821 E native  : do suspend true
,09-15 10:02:39.056   927  5548 D DhcpClient: Clearing IP address
,09-15 10:02:39.056   508   921 D CommandListener: Clearing all IP addresses on wlan0
,09-15 10:02:39.062   508   921 D CommandListener: Setting iface cfg
,09-15 10:02:39.065  3436  5569 V NativeCrypto: Read error: ssl=0x7f9314e080: I/O error during system call, Connection timed out
,09-15 10:02:39.070  3436  5569 V NativeCrypto: SSL shutdown failed: ssl=0x7f9314e080: I/O error during system call, Broken pipe
,09-15 10:02:39.085   927  5549 D DhcpClient: Receive thread stopped
,09-15 10:02:39.085   927  3424 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,09-15 10:02:39.086   927  5546 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,09-15 10:02:39.086   927  2833 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-15 10:02:39.086   927  2833 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-15 10:02:39.086   927  5546 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-15 10:02:39.091   534   534 E Parcel  : Reading a NULL string not supported here.
,09-15 10:02:39.091   927   927 D RttService: SCAN_AVAILABLE : 1
09-15 10:02:39.092   927  2903 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-15 10:02:39.097   927  2821 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-15 10:02:39.099   927  2833 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-15 10:02:39.100   927  5546 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-15 10:02:39.101  3323  3473 W QCNEJ   : |CORE| network lost: 101
09-15 10:02:39.102   927  2821 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 10:02:39.102   927  2821 E native  : do suspend true
,09-15 10:02:39.103  3323  3473 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-15 10:02:39.124   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 10:02:39.146   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 10:02:39.146   508   921 D CommandListener: Clearing all IP addresses on wlan0
,09-15 10:02:39.146   927  2833 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-15 10:02:39.146   927  2833 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 10:02:39.148   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-15 10:02:39.150   927  2821 D DhcpClient: doQuit
09-15 10:02:39.150   927  2821 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 10:02:39.151  5543  5543 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 10:02:39.151  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:02:39.151   927  5548 D DhcpClient: onQuitting
09-15 10:02:39.151  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:39.151  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:39.151  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:39.151  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:02:39.151  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:39.151  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:39.151  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:39.151  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:39.151  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:39.151  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:39.153  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:39.153  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:39.153  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:39.153  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:39.153  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:39.153  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:39.153  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:39.153  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:39.153  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:39.153  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:39.153  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:39.155  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:39.155  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:39.155  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:39.155  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:39.155  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:39.155  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:39.155  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:39.155  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:39.155  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:39.155  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for m,ultiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:39.155  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:39.156  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:39.157  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:39.157  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:39.157  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:39.157  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:39.157  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:39.157  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:39.157  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:39.157  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:39.157  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:39.157  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:39.157  4694  4707 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 10:02:39.157  4694  4707 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 10:02:39.157  4694  4707 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,09-15 10:02:39.157  4694  4707 E SarControlService: no key has been found,reset the power
09-15 10:02:39.157  4694  4732 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 10:02:39.157  4694  4732 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 10:02:39.158  4694  4732 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 10:02:39.158  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:39.158  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 10:02:39.158  4720  4720 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 10:02:39.159  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:39.162  4694  4732 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 10:02:39.165  4694  4732 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 10:02:39.165  4694  4732 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 10:02:39.166  4720  4734 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@222250c HexData = [00000000ee03000000000000ffffffff]
09-15 10:02:39.166  4720  4734 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 10:02:39.166  4720  4734 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-15 10:02:39.167  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-15 10:02:39.167  4720  4720 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 10:02:39.167  5543  5543 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-15 10:02:39.172  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 10:02:39.172  4694  4704 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-15 10:02:39.173  5543  5543 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-15 10:02:39.175  4720  4734 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@222250c HexData = [00000000ef03000000000000ffffffff]
09-15 10:02:39.175  4720  4734 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 10:02:39.175  4720  4734 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-15 10:02:39.176  4720  4720 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-15 10:02:39.176  4694  4705 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-15 10:02:39.177  3765  3765 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-15 10:02:39.181  3765  5099 I iu.UploadsManager: num queued entries: 0
09-15 10:02:39.181  3765  5099 I iu.UploadsManager: num updated entries: 0
09-15 10:02:39.182  3765  5099 I iu.SyncManager: NEXT; no task
09-15 10:02:39.184  3765  3765 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 10:02:39.186  3765  3765 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 10:02:39.187  5483  5483 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 10:02:39.191  5483  5483 D SprintDMHelper: simOperator: 
09-15 10:02:39.191  5483  5483 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 10:02:39.203  4104  5579 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 10:02:39.215  5543  5543 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 10:02:39.223   508   921 E Netd    : netlink response contains error (No such file or directory)
,09-15 10:02:39.224   927  2833 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-15 10:02:39.225  5543  5543 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 10:02:39.229  4104  4104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 10:02:39.229   927  2821 D wifi    : In wifi stop Hal
09-15 10:02:39.229   927  2821 D wifi    : halHandle = 0x7f80969aa0, mVM = 0x7f9d00d140, mCls = 0x18ee
09-15 10:02:39.230   927  5542 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 10:02:39.230   927  5542 D WifiHAL : Got a signal to exit!!!
09-15 10:02:39.230   927  5542 I WifiHAL : Exit wifi_event_loop
09-15 10:02:39.230   927  2821 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 10:02:39.230   927  2821 E WifiHAL : Event processing terminated
09-15 10:02:39.230   927  2821 D wifi    : In wifi cleaned up handler
09-15 10:02:39.230   927  2821 I WifiHAL : Internal cleanup completed
,09-15 10:02:39.232  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:39.232  3491  3861 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 10:02:39.233  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:39.234  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:39.253   927  5542 D wifi    : set interface wlan0 flags (DOWN)
,09-15 10:02:39.253   927  2821 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 10:02:39.459   927   944 D Tethering: InitialState.processMessage what=4
,09-15 10:02:39.465   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 10:02:39.768   927  2833 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-15 10:02:41.959   927   927 E WifiNative-wlan0: set PNO failure
,09-15 10:02:44.055   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93a987a:true
,09-15 10:02:44.056  5469  5469 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 10:02:44.061  5469  5469 I bt_bluedroid: init
,09-15 10:02:44.061  5469  5584 I BluetoothAdapterState: Entering OffState
,09-15 10:02:44.064  5469  5585 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-15 10:02:44.065  5469  5585 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 10:02:44.065  5469  5585 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 10:02:44.065  5469  5585 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 10:02:44.066  5469  5469 I bt_bluedroid: get_profile_interface socket
,09-15 10:02:44.069  5469  5469 I bt_bluedroid: get_profile_interface sdp
09-15 10:02:44.069  5469  5588 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 10:02:44.071  5469  5588 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 10:02:44.076  5469  5479 I bt_bluedroid: config_hci_snoop_log
,09-15 10:02:44.079   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 10:02:44.085  5469  5584 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 10:02:44.086  5469  5584 D BluetoothAdapterProperties: Setting state to 14
,09-15 10:02:44.086  5469  5584 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-15 10:02:44.088  5469  5584 D BluetoothBondStateMachine: make
,09-15 10:02:44.091  5469  5589 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 10:02:44.095  5469  5584 I BluetoothAdapterState: Entering PendingCommandState
,09-15 10:02:44.096  5469  5469 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 10:02:44.100  5469  5469 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
,09-15 10:02:44.101  5469  5469 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 10:02:44.102  5469  5469 D BtGatt.GattService: Received start request. Starting profile...
09-15 10:02:44.102  5469  5469 D BtGatt.GattService: start()
09-15 10:02:44.102  5469  5469 I bt_bluedroid: get_profile_interface gatt
,09-15 10:02:44.104  5469  5469 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:02:44.104  5469  5469 D BtGatt.AdvertiseManager: advertise manager created
,09-15 10:02:44.111  5469  5469 V BluetoothAdapterState: isTurningOff()=false
,09-15 10:02:44.111  5469  5469 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:44.111  5469  5469 V BluetoothAdapterState: isBleTurningOn()=true
09-15 10:02:44.111  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 10:02:44.112  5469  5584 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 10:02:44.114  5469  5584 I bt_bluedroid: bt_bluedroid
,09-15 10:02:44.114  5469  5585 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 10:02:44.115  5469  5585 I bt_hci  : start_up
,09-15 10:02:44.121  5469  5585 I bt_vendor: alloc value 0xf3fb8871
09-15 10:02:44.121  5469  5585 I bt_vendor: init
,09-15 10:02:44.121  5469  5585 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-15 10:02:44.121  5469  5585 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 10:02:44.229  5593  5593 W irq/448-msm_hs_: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 10:02:44.231  5469  5585 D bt_hci  : start_up starting async portion
09-15 10:02:44.232  5469  5592 I bt_hci  : event_finish_startup
,09-15 10:02:44.232  5469  5592 I bt_hci_h4: hal_open
09-15 10:02:44.232  5469  5592 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-15 10:02:44.233  5469  5592 I bt_userial_vendor: device fd = 54 open
,09-15 10:02:44.248  5469  5592 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 10:02:44.250  5469  5592 D bt_hwcfg: Chipset BCM4358A3
,09-15 10:02:44.250  5469  5592 D bt_hwcfg: Target name = [BCM4358A3]
09-15 10:02:44.250  5469  5592 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 10:02:44.652  5469  5592 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 10:02:44.653  5469  5592 D bt_hwcfg: Settlement delay -- 100 ms
09-15 10:02:44.653  5469  5592 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 10:02:44.786  5469  5592 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 10:02:44.786  5469  5592 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-15 10:02:44.788  5469  5592 I bt_hwcfg: vendor lib fwcfg completed
,09-15 10:02:44.788  5469  5592 I bt_vendor: firmware callback
09-15 10:02:44.788  5469  5592 I bt_hci  : firmware_config_callback
,09-15 10:02:44.797  5469  5595 I bt_btu  : btu_task pending for preload complete event
,09-15 10:02:44.797  5469  5595 I bt_btu_task: Bluetooth chip preload is complete
09-15 10:02:44.797  5469  5595 I bt_btu  : btu_task received preload complete event
,09-15 10:02:44.806  5469  5595 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 10:02:44.806  5469  5595 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 10:02:44.806  5469  5595 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 10:02:44.806  5469  5595 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-15 10:02:44.806  5469  5595 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 10:02:44.806  5469  5595 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 10:02:44.807  5469  5595 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 10:02:44.807  5469  5595 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 10:02:44.807  5469  5595 I         : BTE_InitTraceLevels -- TRC_GAP
,09-15 10:02:44.807  5469  5595 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 10:02:44.807  5469  5595 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 10:02:44.807  5469  5595 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 10:02:44.807  5469  5595 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 10:02:44.807  5469  5595 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-15 10:02:44.808  5469  5595 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 10:02:44.889  5469  5595 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f36549
,09-15 10:02:44.890  5469  5595 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f36549 
,09-15 10:02:44.902  5469  5588 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 10:02:44.904  5469  5588 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 10:02:44.904  5469  5588 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 10:02:44.908  5469  5588 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 10:02:44.911  5469  5588 D BluetoothAdapterProperties: Scan Mode:20
,09-15 10:02:44.912  5469  5588 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 10:02:44.912  5469  5588 D bt_hci  : do_postload posting postload work item
09-15 10:02:44.912  5469  5592 I bt_hci  : event_postload
09-15 10:02:44.913  5469  5592 I bt_vendor: sco_config_cb
09-15 10:02:44.913  5469  5592 I bt_hci  : sco_config_callback postload finished.
,09-15 10:02:44.918  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:44.919  5469  5588 D bt_bte_conf: Device ID record 1 : primary
,09-15 10:02:44.919  5469  5588 D bt_bte_conf:   vendorId            = 000f
09-15 10:02:44.919  5469  5588 D bt_bte_conf:   vendorIdSource      = 0001
09-15 10:02:44.919  5469  5588 D bt_bte_conf:   product             = 1200
09-15 10:02:44.919  5469  5588 D bt_bte_conf:   version             = 1436
09-15 10:02:44.919  5469  5588 D bt_bte_conf:   clientExecutableURL = 
09-15 10:02:44.919  5469  5588 D bt_bte_conf:   serviceDescription  = 
09-15 10:02:44.919  5469  5588 D bt_bte_conf:   documentationURL    = 
09-15 10:02:44.919  5469  5588 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 10:02:44.920  5469  5585 D bt_stack_manager: event_start_up_stack finished
09-15 10:02:44.921  5469  5584 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 10:02:44.921  5469  5592 I bt_vendor: low_power_mode_cb
09-15 10:02:44.921  5469  5584 D BluetoothAdapterProperties: Setting state to 15
09-15 10:02:44.921  5469  5584 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 10:02:44.922  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:44.923  5469  5584 I BluetoothAdapterState: Entering BleOnState
09-15 10:02:44.924  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:44.926  5469  5584 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 10:02:44.926  5469  5584 D BluetoothAdapterProperties: Setting state to 11
09-15 10:02:44.926  5469  5584 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 10:02:44.932  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:44.933  5469  5469 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:02:44.934  5469  5469 D HeadsetService: Received start request. Starting profile...
09-15 10:02:44.934  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:44.936  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:44.937  5469  5469 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 10:02:44.937  5469  5469 D HeadsetStateMachine: make
,09-15 10:02:44.948  5469  5584 I BluetoothAdapterState: Entering PendingCommandState
,09-15 10:02:44.949  5469  5469 D HeadsetStateMachine: max_hf_connections = 1
,09-15 10:02:44.949  5469  5469 I bt_bluedroid: get_profile_interface handsfree
09-15 10:02:44.949  5469  5588 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 10:02:44.949  5469  5588 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
,09-15 10:02:44.952  5469  5469 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:02:44.953  5469  5469 D A2dpService: Received start request. Starting profile...
,09-15 10:02:44.954  5469  5469 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-15 10:02:44.954  5469  5469 I bt_bluedroid: get_profile_interface avrcp
,09-15 10:02:44.959  5469  5469 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 10:02:44.960  5469  5469 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 10:02:44.960  5469  5469 D A2dpStateMachine: make
09-15 10:02:44.961  5469  5469 I bt_bluedroid: get_profile_interface a2dp
09-15 10:02:44.961  5469  5588 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 10:02:44.963  5469  5603 D A2dpStateMachine: Enter Disconnected: -2
09-15 10:02:44.963  5469  5469 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 10:02:44.964  5469  5469 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:02:44.965  5406  5406 D BluetoothInputDevice: Proxy object connected
09-15 10:02:44.966  5469  5469 D HidService: Received start request. Starting profile...
09-15 10:02:44.966  5469  5469 I bt_bluedroid: get_profile_interface hidhost
09-15 10:02:44.966  5469  5469 D HidService: setHidService(): set to: null
09-15 10:02:44.966  5469  5588 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f1756d
,09-15 10:02:44.966  5406  5406 D HidProfile: Bluetooth service connected
09-15 10:02:44.966  5469  5588 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 10:02:44.966  5469  5469 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 10:02:44.967  5469  5469 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:02:44.968  5469  5469 D HealthService: Received start request. Starting profile...
,09-15 10:02:44.969  5469  5469 I bt_bluedroid: get_profile_interface health
09-15 10:02:44.970  5469  5469 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-15 10:02:44.971  5469  5469 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:02:44.972  3436  3436 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:02:44.972  5406  5406 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 10:02:44.973  5406  5406 D PanProfile: Bluetooth service connected
,09-15 10:02:44.973  5469  5469 D PanService: Received start request. Starting profile...
09-15 10:02:44.973  5469  5469 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 10:02:44.974  5469  5469 I bt_bluedroid: get_profile_interface pan
,09-15 10:02:44.975  5469  5588 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 10:02:44.977  5469  5469 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
,09-15 10:02:44.979  5469  5469 D BluetoothMapService: Received start request. Starting profile...
,09-15 10:02:44.979  5469  5469 D BluetoothMapService: start()
09-15 10:02:44.981  5469  5469 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-15 10:02:44.982  5469  5469 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 10:02:44.982  5469  5469 D BluetoothMapAppObserver: createReceiver()
09-15 10:02:44.983  5469  5469 D BluetoothMapAppObserver: initObservers()
09-15 10:02:44.984  5469  5469 D BluetoothMapAppObserver: getEnabledAccountItems()
09-15 10:02:44.989  5469  5469 V SapService: SapBinder()
09-15 10:02:44.989  5469  5469 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:02:44.990  5406  5406 D BluetoothMap: Proxy object connected
09-15 10:02:44.990  5406  5406 D MapProfile: Bluetooth service connected
,09-15 10:02:44.990  5406  5406 D BluetoothMap: getConnectedDevices()
09-15 10:02:44.991  5469  5469 D SapService: Received start request. Starting profile...
09-15 10:02:44.991  5469  5469 V SapService: start()
09-15 10:02:44.992  5406  5406 D BluetoothMap: Bluetooth is Not enabled
09-15 10:02:44.992  5469  5469 V BluetoothAdapterState: isTurningOff()=false
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isTurningOn()=true
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:44.993  5469  5601 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isTurningOff()=false
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isTurningOn()=true
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isTurningOff()=false
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isTurningOn()=true
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isTurningOff()=false
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isTurningOn()=true
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:44.993  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:44.994  5469  5469 V BluetoothAdapterState: isTurningOff()=false
09-15 10:02:44.994  5469  5469 V BluetoothAdapterState: isTurningOn()=true
09-15 10:02:44.994  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:44.994  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 10:02:44.994  5469  5469 V BluetoothAdapterState: isTurningOff()=false
09-15 10:02:44.994  5469  5469 V BluetoothAdapterState: isTurningOn()=true
09-15 10:02:44.994  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:44.994  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:44.995  5469  5469 V BluetoothAdapterState: isTurningOff()=false
09-15 10:02:44.995  5469  5469 V BluetoothAdapterState: isTurningOn()=true
09-15 10:02:44.995  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:44.995  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:44.995  5469  5584 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 10:02:44.995  5469  5584 D BluetoothAdapterProperties: ScanMode =  20
09-15 10:02:44.995  5469  5584 D BluetoothAdapterProperties: State =  11
09-15 10:02:44.996  5469  5584 D BluetoothAdapterProperties: Setting state to 12
09-15 10:02:44.996  5469  5584 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 10:02:44.996  5469  5584 I BluetoothAdapterState: Entering OnState
09-15 10:02:44.996  2971  2984 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 10:02:44.999   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 10:02:44.999  5406  5421 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 10:02:45.000  5469  5588 D BluetoothAdapterProperties: Scan Mode:21
09-15 10:02:45.000  5469  5588 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 10:02:45.000   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:02:45.001  2971  2985 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:02:45.001  5406  5423 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 10:02:45.002  2971  3606 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 10:02:45.003  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:45.003  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:45.003  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:45.003  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:45.003  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:02:45.003  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:45.003  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:45.003  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:45.003  2971  2971 D BluetoothInputDevice: Proxy object connected
09-15 10:02:45.003  2971  2984 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 10:02:45.003  2971  2971 D HidProfile: Bluetooth service connected
,09-15 10:02:45.005  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:45.005  3347  3372 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:02:45.006   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 10:02:45.006  2971  2971 D BluetoothA2dp: Proxy object connected
09-15 10:02:45.007   927   927 D BluetoothA2dp: Proxy object connected
09-15 10:02:45.007  2971  2985 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 10:02:45.008  5469  5469 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 10:02:45.009  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:45.009  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:45.009  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:45.009  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:45.009  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:02:45.009  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:45.009  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:45.009  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:45.009  5469  5469 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-15 10:02:45.010  2971  2971 D BluetoothMap: Proxy object connected
09-15 10:02:45.010  5406  5421 D BluetoothPan: onBluetoothStateChange on: true
09-15 10:02:45.010  2971  2971 D MapProfile: Bluetooth service connected
09-15 10:02:45.010  2971  2971 D BluetoothMap: getConnectedDevices()
09-15 10:02:45.011  2971  2984 D BluetoothPan: onBluetoothStateChange on: true
09-15 10:02:45.012  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:45.013  2971  2971 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 10:02:45.013  2971  2971 D PanProfile: Bluetooth service connected
,09-15 10:02:45.013  5406  5423 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 10:02:45.014  5469  5469 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:02:45.015   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:02:45.015  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:45.015  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:45.015  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:45.015  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:45.015  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:02:45.015  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:45.015  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:45.015  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:45.016   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 10:02:45.017  5469  5469 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:02:45.019  5406  5406 D LocalBluetoothProfileManager: Adding local A2DP profile
09-15 10:02:45.019  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:45.019  5469  5469 D ObexServerSockets: Succeed to create listening sockets 
09-15 10:02:45.019  5469  5469 D ObexServerSockets0: startAccept()
09-15 10:02:45.020  5469  5469 D ObexServerSockets0: prepareForNewConnect()
09-15 10:02:45.021  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:45.022  5469  5469 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-15 10:02:45.022  5469  5469 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 10:02:45.022  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:45.024  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:45.024  5469  5469 D BluetoothMapService: onReceive
09-15 10:02:45.024  5469  5469 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-15 10:02:45.024  5406  5406 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-15 10:02:45.025  5469  5469 D BluetoothMapService: STATE_ON
09-15 10:02:45.027  5469  5612 D ObexServerSockets0: Accepting socket connection...
09-15 10:02:45.027  5469  5611 D ObexServerSockets0: Accepting socket connection...
,09-15 10:02:45.029  5469  5613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:02:45.030  5469  5613 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-15 10:02:45.030  5469  5613 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 10:02:45.033  5406  5406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 10:02:45.036  5406  5406 D BluetoothA2dp: Proxy object connected
,09-15 10:02:45.040  3436  3436 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:02:45.044  5406  5406 D DockEventReceiver: finishStartingService: stopping service
,09-15 10:02:45.046  2971  2971 D BluetoothPbap: Proxy object connected
,09-15 10:02:45.046  2971  2971 D PbapServerProfile: Bluetooth service connected
,09-15 10:02:45.046  5406  5406 D BluetoothPbap: Proxy object connected
09-15 10:02:45.047  5406  5406 D PbapServerProfile: Bluetooth service connected
,09-15 10:02:45.050  5469  5469 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 10:02:45.050  5469  5469 D ObexServerSockets0: prepareForNewConnect()
,09-15 10:02:45.053  5469  5617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:02:45.064  5469  5621 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:02:45.065  5469  5621 I BtOppRfcommListener: Accept thread started.
,09-15 10:02:45.100   927   927 D BluetoothHeadset: Proxy object connected
,09-15 10:02:45.101   927   944 D BluetoothHeadset: Proxy object connected
09-15 10:02:45.101   927   927 D BluetoothHeadset: Proxy object connected
09-15 10:02:45.101  2971  3606 D BluetoothHeadset: Proxy object connected
09-15 10:02:45.101  3347  3383 D BluetoothHeadset: Proxy object connected
,09-15 10:02:45.101  2971  2971 D HeadsetProfile: Bluetooth service connected
09-15 10:02:45.101   927   927 D BluetoothHeadset: Proxy object connected
09-15 10:02:45.101  2971  2985 D BluetoothHeadset: Proxy object connected
,09-15 10:02:45.103  2971  2971 D HeadsetProfile: Bluetooth service connected
,09-15 10:02:45.106  3347  3678 D BluetoothHeadset: Proxy object connected
,09-15 10:02:45.115   927   944 D BluetoothHeadset: Proxy object connected
,09-15 10:02:45.132  5406  5421 D BluetoothHeadset: Proxy object connected
,09-15 10:02:45.135  5406  5406 D HeadsetProfile: Bluetooth service connected
,09-15 10:02:45.510   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:46.511   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:46.716   927  2833 D ConnectivityService: handlePromptUnvalidated 101
,09-15 10:02:47.512   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:48.513   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:49.032  5469  5584 D BluetoothAdapterState: Current state: ON, message: 23
,09-15 10:02:49.032  5469  5584 D BluetoothAdapterProperties: Setting state to 13
,09-15 10:02:49.032  5469  5584 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 10:02:49.033  5469  5584 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 10:02:49.035  5469  5584 I BluetoothAdapterState: Entering PendingCommandState
09-15 10:02:49.039  5469  5469 D BluetoothMapService: onReceive
,09-15 10:02:49.039  5469  5469 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 10:02:49.040  5469  5469 D BluetoothMapService: STATE_TURNING_OFF
09-15 10:02:49.040  5469  5469 D BluetoothMapService: MAP Service closeService in
,09-15 10:02:49.040  5469  5469 D BluetoothMapMasInstance0: MAP Service shutdown
,09-15 10:02:49.041  5469  5469 D ObexServerSockets0: shutdown(block = true)
,09-15 10:02:49.042  5469  5611 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-15 10:02:49.043  5469  5469 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-15 10:02:49.044  5469  5469 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 10:02:49.044  5469  5597 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-15 10:02:49.045  5469  5612 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-15 10:02:49.047  5469  5469 I BtOppRfcommListener: stopping Accept Thread
09-15 10:02:49.047  5469  5588 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:02:49.048  5469  5584 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-15 10:02:49.048  5469  5621 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 10:02:49.048  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:49.049  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:49.049  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:49.049  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:49.049  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:49.049  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:49.049  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:49.049  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:49.049  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:49.049  5469  5621 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 10:02:49.050  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:49.050  5406  5406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 10:02:49.051  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:49.053  5469  5469 D HeadsetService: Received stop request...Stopping profile...
09-15 10:02:49.057  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:49.057  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:49.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:49.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:49.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:49.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:49.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:49.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:49.057  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:49.058  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:49.058  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:49.060   927   927 D BluetoothHeadset: Proxy object disconnected
09-15 10:02:49.060   927   927 D BluetoothHeadset: Proxy object disconnected
09-15 10:02:49.061  3347  3372 D BluetoothHeadset: Proxy object disconnected
09-15 10:02:49.061   927   927 D BluetoothHeadset: Proxy object disconnected
09-15 10:02:49.062  2971,  2984 D BluetoothHeadset: Proxy object disconnected
09-15 10:02:49.063  5406  5423 D BluetoothHeadset: Proxy object disconnected
09-15 10:02:49.066  5469  5469 D A2dpService: Received stop request...Stopping profile...
09-15 10:02:49.066  5469  5603 D A2dpStateMachine: Exit Disconnected: -1
09-15 10:02:49.066  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:49.066  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:02:49.066  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:02:49.066  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:02:49.066  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:02:49.066  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:02:49.066  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:02:49.066  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:02:49.066  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:02:49.067  5406  5406 D DockEventReceiver: finishStartingService: stopping service
09-15 10:02:49.067  5347  5347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:02:49.067  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:02:49.068  5406  5406 D HeadsetProfile: Bluetooth service disconnected
,09-15 10:02:49.068   927   927 D BluetoothA2dp: Proxy object disconnected
09-15 10:02:49.069  5406  5406 D BluetoothA2dp: Proxy object disconnected
09-15 10:02:49.069  5469  5469 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:49.069  5469  5469 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:49.069  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:49.069  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:49.069  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:49.070  5469  5469 D HidService: Received stop request...Stopping profile...
,09-15 10:02:49.071  5469  5469 D HidService: Stopping Bluetooth HidService
09-15 10:02:49.072  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:49.072  2971  2971 D HeadsetProfile: Bluetooth service disconnected
09-15 10:02:49.073  5406  5406 D BluetoothInputDevice: Proxy object disconnected
09-15 10:02:49.073  5406  5406 D HidProfile: Bluetooth service disconnected
,09-15 10:02:49.073  2971  2971 D BluetoothA2dp: Proxy object disconnected
09-15 10:02:49.073  2971  2971 D BluetoothInputDevice: Proxy object disconnected
09-15 10:02:49.073  2971  2971 D HidProfile: Bluetooth service disconnected
09-15 10:02:49.073  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:49.076  3436  3436 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 10:02:49.077  5469  5469 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 10:02:49.077  5469  5469 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 10:02:49.077  5469  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:49.077  5469  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:49.077  5469  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:49.078  5469  5469 D HealthService: Received stop request...Stopping profile...
,09-15 10:02:49.078  5469  5588 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 10:02:49.078  5469  5588 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-15 10:02:49.079  5469  5469 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:49.080  5469  5469 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:49.080  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:49.080  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:49.081  5469  5469 D PanService: Received stop request...Stopping profile...
09-15 10:02:49.083  2971  2971 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-15 10:02:49.083  2971  2971 D PanProfile: Bluetooth service disconnected
09-15 10:02:49.083  5406  5406 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 10:02:49.083  5406  5406 D PanProfile: Bluetooth service disconnected
09-15 10:02:49.084  5469  5588 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 10:02:49.084  5469  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:49.084  5469  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:49.084  5469  5595 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 10:02:49.085  5469  5595 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 10:02:49.085  5469  5595 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 10:02:49.085  5469  5595 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-15 10:02:49.085  5469  5469 D BluetoothMapService: Received stop request...Stopping profile...
09-15 10:02:49.085  5469  5469 D BluetoothMapService: stop()
09-15 10:02:49.085  5469  5469 D BluetoothMapAppObserver: deinitObservers()
09-15 10:02:49.085  5469  5469 D BluetoothMapAppObserver: removeReceiver()
09-15 10:02:49.087  2971  2971 D BluetoothMap: Proxy object disconnected
09-15 10:02:49.087  2971  2971 D MapProfile: Bluetooth service disconnected
09-15 10:02:49.087  5406  5406 D BluetoothMap: Proxy object disconnected
09-15 10:02:49.087  5406  5406 D MapProfile: Bluetooth service disconnected
09-15 10:02:49.088  5469  5469 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:49.088  5469  5469 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:49.088  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:49.088  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:49.088  5469  5469 D SapService: Received stop request...Stopping profile...
,09-15 10:02:49.088  5469  5469 V SapService: stop()
,09-15 10:02:49.090  5469  5469 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-15 10:02:49.090  5469  5469 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 10:02:49.090  5469  5588 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 10:02:49.092  2971  2971 D BluetoothPbap: Proxy object disconnected
09-15 10:02:49.092  5406  5406 D BluetoothPbap: Proxy object disconnected
09-15 10:02:49.092  2971  2971 D PbapServerProfile: Bluetooth service disconnected
09-15 10:02:49.092  5406  5406 D PbapServerProfile: Bluetooth service disconnected
09-15 10:02:49.092  5469  5469 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:49.092  5469  5469 V BluetoothAdapterState: isTurningOn()=false
,09-15 10:02:49.092  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:49.092  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:49.093  5469  5469 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 10:02:49.093  5469  5588 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-15 10:02:49.094  5469  5469 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 10:02:49.094  5469  5469 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:49.094  5469  5469 V BluetoothAdapterState: isTurningOn()=false
,09-15 10:02:49.094  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:49.094  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:49.095  5469  5469 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 10:02:49.095  5469  5469 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 10:02:49.095  5469  5469 D BluetoothMapService: MAP Service closeService in
09-15 10:02:49.095  5469  5469 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:49.095  5469  5469 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:49.095  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 10:02:49.096  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:49.096  5469  5469 D BluetoothMapService: cleanup()
09-15 10:02:49.096  5469  5469 D BluetoothMapService: MAP Service closeService in
09-15 10:02:49.096  5469  5469 V BluetoothAdapterState: isTurningOff()=true
09-15 10:02:49.096  5469  5469 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:49.096  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:49.096  5469  5469 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:49.096  5469  5584 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 10:02:49.096  5469  5584 D BluetoothAdapterProperties: Setting state to 15
09-15 10:02:49.096  5469  5584 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 10:02:49.097  5469  5584 I BluetoothAdapterState: Entering BleOnState
,09-15 10:02:49.097  2971  2985 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 10:02:49.098   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:49.099  5406  5421 D BluetoothMap: onBluetoothStateChange: up=false
09-15 10:02:49.102   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:49.102  2971  2984 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:49.103  5406  5423 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-15 10:02:49.103  2971  3606 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 10:02:49.104  2971  2985 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 10:02:49.105  3347  3383 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:49.105   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 10:02:49.106  5406  5421 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 10:02:49.107  2971  2984 D BluetoothMap: onBluetoothStateChange: up=false
09-15 10:02:49.107  5406  5423 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:02:49.107  5406  5421 D BluetoothPan: onBluetoothStateChange on: false
09-15 10:02:49.108  2971  3606 D BluetoothPan: onBluetoothStateChange on: false
09-15 10:02:49.108  5406  5423 D BluetoothPbap: onBluetoothStateChange: up=false
,09-15 10:02:49.109   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 10:02:49.109  5469  5584 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 10:02:49.109  5469  5584 D BluetoothAdapterProperties: Setting state to 16
09-15 10:02:49.109  5469  5584 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 10:02:49.109  5469  5584 D BluetoothAdapterProperties: onBleDisable
09-15 10:02:49.110  5469  5584 I BluetoothAdapterState: Entering PendingCommandState
09-15 10:02:49.110  5469  5585 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 10:02:49.111  5469  5595 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 10:02:49.111  5469  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:02:49.112  5469  5588 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:02:49.112  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:49.112  5406  5406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 10:02:49.113  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:49.116  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:02:49.117  3436  3436 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:02:49.118  5406  5406 D DockEventReceiver: finishStartingService: stopping service
09-15 10:02:49.118  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:49.119  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:49.124  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:49.325  5469  5588 I bt_hci  : shut_down
,09-15 10:02:49.331  5469  5592 D bt_hwcfg: hw_epilog_process
09-15 10:02:49.331  5469  5592 I bt_vendor: low_power_mode_cb
,09-15 10:02:49.333  5469  5592 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 10:02:49.334  5469  5592 I bt_vendor: epilog_cb
09-15 10:02:49.334  5469  5592 I bt_hci  : epilog_finished_callback
,09-15 10:02:49.337  5469  5588 I bt_hci_h4: hal_close
,09-15 10:02:49.338  5469  5588 I bt_userial_vendor: device fd = 54 close
,09-15 10:02:49.448  5469  5585 D bt_stack_manager: event_shut_down_stack finished.
,09-15 10:02:49.449  5469  5584 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 10:02:49.452  5469  5584 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-15 10:02:49.452  5469  5469 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 10:02:49.453  5469  5469 D BtGatt.GattService: Received stop request...Stopping profile...
,09-15 10:02:49.453  5469  5469 D BtGatt.GattService: stop()
09-15 10:02:49.453  5469  5469 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 10:02:49.456  5469  5469 V BluetoothAdapterState: isTurningOff()=false
,09-15 10:02:49.456  5469  5469 V BluetoothAdapterState: isTurningOn()=false
,09-15 10:02:49.456  5469  5469 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:02:49.456  5469  5469 V BluetoothAdapterState: isBleTurningOff()=true
09-15 10:02:49.456  5469  5584 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 10:02:49.457  5469  5584 D BluetoothAdapterProperties: Setting state to 10
,09-15 10:02:49.457  5469  5584 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 10:02:49.458  5469  5584 I BluetoothAdapterState: Entering OffState
09-15 10:02:49.459   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-15 10:02:49.470  5469  5469 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 10:02:49.471  5469  5469 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 10:02:49.471  5469  5469 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 10:02:49.472  5469  5585 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 10:02:49.478  5469  5469 I art     : System.exit called, status: 0
,09-15 10:02:49.478  5469  5469 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 10:02:49.503   927   937 I ActivityManager: Process com.android.bluetooth (pid 5469) has died
,09-15 10:02:49.514   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:02:50.514   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:02:54.030  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:02:54.030  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:54.035  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:02:54.035  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fdfeb5 removed from the list
,09-15 10:02:54.035  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:02:54.035  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:02:54.036  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:02:54.039  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:02:54.040  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@acc70bb added. We now have 4 listener(s)
09-15 10:02:54.040  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:02:54.042  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:02:54.042  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@acc70bb removed from the list
,09-15 10:02:54.042  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:02:54.042  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:02:54.043  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:02:54.045  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 10:02:54.045  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f0729d8 added. We now have 4 listener(s)
09-15 10:02:54.045  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:02:59.054  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:02:59.088   927   944 I ActivityManager: Start proc 5629:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 10:02:59.179  5629  5629 D AdapterServiceConfig: Adding HeadsetService
,09-15 10:02:59.179  5629  5629 D AdapterServiceConfig: Adding A2dpService
09-15 10:02:59.179  5629  5629 D AdapterServiceConfig: Adding HidService
09-15 10:02:59.179  5629  5629 D AdapterServiceConfig: Adding HealthService
09-15 10:02:59.179  5629  5629 D AdapterServiceConfig: Adding PanService
,09-15 10:02:59.179  5629  5629 D AdapterServiceConfig: Adding GattService
09-15 10:02:59.180  5629  5629 D AdapterServiceConfig: Adding BluetoothMapService
09-15 10:02:59.180  5629  5629 D AdapterServiceConfig: Adding SapService
,09-15 10:02:59.189   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6fa4f3a:true
,09-15 10:02:59.190  5629  5629 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 10:02:59.192  5629  5629 I bt_bluedroid: init
,09-15 10:02:59.192  5629  5641 I BluetoothAdapterState: Entering OffState
,09-15 10:02:59.194  5629  5642 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-15 10:02:59.194  5629  5642 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 10:02:59.194  5629  5642 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 10:02:59.194  5629  5642 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-15 10:02:59.194  5629  5629 I bt_bluedroid: get_profile_interface socket
,09-15 10:02:59.196  5629  5645 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 10:02:59.197  5629  5629 I bt_bluedroid: get_profile_interface sdp
09-15 10:02:59.197  5629  5645 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 10:02:59.203  5629  5639 I bt_bluedroid: config_hci_snoop_log
,09-15 10:02:59.205   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 10:02:59.209  5629  5641 D BluetoothAdapterState: Current state: OFF, message: 0
09-15 10:02:59.209  5629  5641 D BluetoothAdapterProperties: Setting state to 14
09-15 10:02:59.209  5629  5641 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 10:02:59.210  5629  5641 D BluetoothBondStateMachine: make
,09-15 10:02:59.212  5629  5646 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 10:02:59.215  5629  5641 I BluetoothAdapterState: Entering PendingCommandState
,09-15 10:02:59.216  5629  5629 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 10:02:59.218  5629  5629 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:02:59.219  5629  5629 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 10:02:59.219  5629  5629 D BtGatt.GattService: Received start request. Starting profile...
09-15 10:02:59.219  5629  5629 D BtGatt.GattService: start()
09-15 10:02:59.220  5629  5629 I bt_bluedroid: get_profile_interface gatt
09-15 10:02:59.220  5629  5629 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:02:59.221  5629  5629 D BtGatt.AdvertiseManager: advertise manager created
,09-15 10:02:59.226  5629  5629 V BluetoothAdapterState: isTurningOff()=false
,09-15 10:02:59.226  5629  5629 V BluetoothAdapterState: isTurningOn()=false
09-15 10:02:59.226  5629  5629 V BluetoothAdapterState: isBleTurningOn()=true
09-15 10:02:59.226  5629  5629 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:02:59.226  5629  5641 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 10:02:59.229  5629  5641 I bt_bluedroid: bt_bluedroid
09-15 10:02:59.229  5629  5642 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 10:02:59.229  5629  5642 I bt_hci  : start_up
,09-15 10:02:59.234  5629  5642 I bt_vendor: alloc value 0xf400f871
,09-15 10:02:59.234  5629  5642 I bt_vendor: init
09-15 10:02:59.234  5629  5642 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 10:02:59.234  5629  5642 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 10:02:59.343  5629  5642 D bt_hci  : start_up starting async portion
,09-15 10:02:59.344  5629  5649 I bt_hci  : event_finish_startup
09-15 10:02:59.344  5629  5649 I bt_hci_h4: hal_open
09-15 10:02:59.344  5629  5649 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 10:02:59.343  5650  5650 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 10:02:59.346  5629  5649 I bt_userial_vendor: device fd = 54 open
,09-15 10:02:59.360  5629  5649 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 10:02:59.363  5629  5649 D bt_hwcfg: Chipset BCM4358A3
,09-15 10:02:59.363  5629  5649 D bt_hwcfg: Target name = [BCM4358A3]
09-15 10:02:59.363  5629  5649 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 10:02:59.868  5629  5649 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 10:02:59.869  5629  5649 D bt_hwcfg: Settlement delay -- 100 ms
09-15 10:02:59.869  5629  5649 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 10:03:00.002  5629  5649 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-15 10:03:00.003  5629  5649 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 10:03:00.005  5629  5649 I bt_hwcfg: vendor lib fwcfg completed
,09-15 10:03:00.005  5629  5649 I bt_vendor: firmware callback
09-15 10:03:00.005  5629  5649 I bt_hci  : firmware_config_callback
09-15 10:03:00.014  5629  5652 I bt_btu  : btu_task pending for preload complete event
,09-15 10:03:00.015  5629  5652 I bt_btu_task: Bluetooth chip preload is complete
09-15 10:03:00.015  5629  5652 I bt_btu  : btu_task received preload complete event
,09-15 10:03:00.022  5629  5652 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 10:03:00.023  5629  5652 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 10:03:00.023  5629  5652 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 10:03:00.023  5629  5652 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 10:03:00.023  5629  5652 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-15 10:03:00.023  5629  5652 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 10:03:00.023  5629  5652 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 10:03:00.023  5629  5652 I         : BTE_InitTraceLevels -- TRC_BTM
,09-15 10:03:00.023  5629  5652 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 10:03:00.024  5629  5652 I         : BTE_InitTraceLevels -- TRC_PAN
,09-15 10:03:00.024  5629  5652 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 10:03:00.024  5629  5652 I         : BTE_InitTraceLevels -- TRC_GATT
,09-15 10:03:00.024  5629  5652 I         : BTE_InitTraceLevels -- TRC_SMP
,09-15 10:03:00.024  5629  5652 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 10:03:00.024  5629  5652 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 10:03:00.125  5629  5652 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f8d549
09-15 10:03:00.125  5629  5652 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f8d549 
,09-15 10:03:00.146  5629  5645 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 10:03:00.148  5629  5645 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 10:03:00.149  5629  5645 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 10:03:00.152  5629  5645 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 10:03:00.155  5629  5645 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:03:00.157  5629  5645 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 10:03:00.157  5629  5645 D bt_hci  : do_postload posting postload work item
09-15 10:03:00.157  5629  5649 I bt_hci  : event_postload
09-15 10:03:00.157  5629  5649 I bt_vendor: sco_config_cb
09-15 10:03:00.158  5629  5649 I bt_hci  : sco_config_callback postload finished.
,09-15 10:03:00.159  5629  5645 D bt_bte_conf: Device ID record 1 : primary
09-15 10:03:00.160  5629  5645 D bt_bte_conf:   vendorId            = 000f
,09-15 10:03:00.160  5629  5645 D bt_bte_conf:   vendorIdSource      = 0001
09-15 10:03:00.160  5629  5645 D bt_bte_conf:   product             = 1200
09-15 10:03:00.160  5629  5645 D bt_bte_conf:   version             = 1436
09-15 10:03:00.160  5629  5645 D bt_bte_conf:   clientExecutableURL = 
09-15 10:03:00.160  5629  5645 D bt_bte_conf:   serviceDescription  = 
09-15 10:03:00.160  5629  5645 D bt_bte_conf:   documentationURL    = 
09-15 10:03:00.160  5629  5645 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 10:03:00.162  5629  5642 D bt_stack_manager: event_start_up_stack finished
09-15 10:03:00.162  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:00.163  5629  5641 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 10:03:00.164  5629  5641 D BluetoothAdapterProperties: Setting state to 15
09-15 10:03:00.164  5629  5641 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 10:03:00.165  5629  5641 I BluetoothAdapterState: Entering BleOnState
,09-15 10:03:00.167  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:03:00.169  5629  5649 I bt_vendor: low_power_mode_cb
09-15 10:03:00.171  5629  5641 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-15 10:03:00.171  5629  5641 D BluetoothAdapterProperties: Setting state to 11
09-15 10:03:00.171  5629  5641 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 10:03:00.175  5629  5629 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:03:00.177  5629  5629 D HeadsetService: Received start request. Starting profile...
,09-15 10:03:00.180  5629  5629 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 10:03:00.180  5629  5629 D HeadsetStateMachine: make
,09-15 10:03:00.187  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:03:00.190  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:03:00.196  5629  5629 D HeadsetStateMachine: max_hf_connections = 1
,09-15 10:03:00.196  5629  5629 I bt_bluedroid: get_profile_interface handsfree
09-15 10:03:00.196  5629  5645 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 10:03:00.197  5629  5645 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-15 10:03:00.199  5629  5629 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:03:00.200  5629  5629 D A2dpService: Received start request. Starting profile...
09-15 10:03:00.200  5629  5629 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 10:03:00.201  5629  5629 I bt_bluedroid: get_profile_interface avrcp
09-15 10:03:00.201  5629  5641 I BluetoothAdapterState: Entering PendingCommandState
,09-15 10:03:00.207  5629  5629 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-15 10:03:00.207  5629  5629 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 10:03:00.207  5629  5629 D A2dpStateMachine: make
09-15 10:03:00.208  5629  5629 I bt_bluedroid: get_profile_interface a2dp
,09-15 10:03:00.209  5629  5645 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 10:03:00.212  5629  5660 D A2dpStateMachine: Enter Disconnected: -2
,09-15 10:03:00.213  5629  5629 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 10:03:00.214  5629  5629 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
,09-15 10:03:00.214  5629  5629 D HidService: Received start request. Starting profile...
09-15 10:03:00.215  5629  5629 I bt_bluedroid: get_profile_interface hidhost
,09-15 10:03:00.215  5629  5629 D HidService: setHidService(): set to: null
09-15 10:03:00.215  5629  5645 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f6e56d
09-15 10:03:00.215  5629  5645 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 10:03:00.215  5629  5629 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 10:03:00.216  5629  5629 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:03:00.216  5629  5629 D HealthService: Received start request. Starting profile...
,09-15 10:03:00.218  5629  5629 I bt_bluedroid: get_profile_interface health
,09-15 10:03:00.219  5629  5629 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-15 10:03:00.220  5629  5629 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
09-15 10:03:00.221  5629  5629 D PanService: Received start request. Starting profile...
,09-15 10:03:00.221  5629  5629 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 10:03:00.221  5629  5629 I bt_bluedroid: get_profile_interface pan
,09-15 10:03:00.222  5629  5645 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 10:03:00.225  5629  5629 V BluetoothAdapterState: isTurningOff()=false
,09-15 10:03:00.225  5629  5629 V BluetoothAdapterState: isTurningOn()=true
09-15 10:03:00.225  5629  5629 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:03:00.225  5629  5629 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:03:00.226  5629  5657 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 10:03:00.227  3436  3436 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 10:03:00.227  5629  5629 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
,09-15 10:03:00.228  5629  5629 D BluetoothMapService: Received start request. Starting profile...
09-15 10:03:00.228  5629  5629 D BluetoothMapService: start()
,09-15 10:03:00.230  5629  5629 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 10:03:00.231  5629  5629 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-15 10:03:00.231  5629  5629 D BluetoothMapAppObserver: createReceiver()
,09-15 10:03:00.233  5629  5629 D BluetoothMapAppObserver: initObservers()
09-15 10:03:00.233  5629  5629 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 10:03:00.240  5629  5629 V SapService: SapBinder()
09-15 10:03:00.240  5629  5629 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
,09-15 10:03:00.241  5629  5629 D SapService: Received start request. Starting profile...
09-15 10:03:00.241  5629  5629 V SapService: start()
,09-15 10:03:00.242  5629  5629 V BluetoothAdapterState: isTurningOff()=false
09-15 10:03:00.242  5629  5629 V BluetoothAdapterState: isTurningOn()=true
09-15 10:03:00.242  5629  5629 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:03:00.242  5629  5629 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:03:00.242  5629  5629 V BluetoothAdapterState: isTurningOff()=false
09-15 10:03:00.242  5629  5629 V BluetoothAdapterState: isTurningOn()=true
09-15 10:03:00.242  5629  5629 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:03:00.242  5629  5629 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:03:00.242  5629  5629 V BluetoothAdapterState: isTurningOff()=false
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isTurningOn()=true
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isTurningOff()=false
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isTurningOn()=true
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isTurningOff()=false
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isTurningOn()=true
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:03:00.243  5629  5629 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:03:00.244  5629  5629 V BluetoothAdapterState: isTurningOff()=false
09-15 10:03:00.244  5629  5629 V BluetoothAdapterState: isTurningOn()=true
,09-15 10:03:00.244  5629  5629 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:03:00.244  5629  5629 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:03:00.244  5629  5641 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 10:03:00.244  5629  5641 D BluetoothAdapterProperties: ScanMode =  20
09-15 10:03:00.244  5629  5641 D BluetoothAdapterProperties: State =  11
,09-15 10:03:00.245  5629  5641 D BluetoothAdapterProperties: Setting state to 12
09-15 10:03:00.245  5629  5641 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 10:03:00.245  5629  5641 I BluetoothAdapterState: Entering OnState
09-15 10:03:00.245  2971  2985 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 10:03:00.247  5629  5645 D BluetoothAdapterProperties: Scan Mode:21
09-15 10:03:00.247  5629  5645 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 10:03:00.247   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 10:03:00.248  5406  5423 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 10:03:00.251   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:03:00.251  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:03:00.251  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:00.251  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:00.251  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:03:00.251  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:00.251  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:00.251  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:00.251  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:00.251  2971  2984 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 10:03:00.252  5406  5423 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 10:03:00.253  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:03:00.253  2971  3606 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 10:03:00.255  2971  2985 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 10:03:00.255  2971  2971 D BluetoothInputDevice: Proxy object connected
09-15 10:03:00.255  2971  2971 D HidProfile: Bluetooth service connected
09-15 10:03:00.257  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:03:00.257  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:00.257  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:00.257  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:03:00.257  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:00.257  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:00.257  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:00.257  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:03:00.257  3347  3678 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:03:00.257   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 10:03:00.257  2971  2971 D BluetoothA2dp: Proxy object connected
09-15 10:03:00.258   927   927 D BluetoothA2dp: Proxy object connected
09-15 10:03:00.258  5406  5423 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 10:03:00.259  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:03:00.260  2971  3606 D BluetoothMap: onBluetoothStateChange: up=true
09-15 10:03:00.260  5629  5629 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 10:03:00.260  5629  5629 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 10:03:00.260  5406  5406 D BluetoothMap: Proxy object connected
09-15 10:03:00.261  5406  5406 D MapProfile: Bluetooth service connected
09-15 10:03:00.261  5406  5406 D BluetoothMap: getConnectedDevices()
09-15 10:03:00.262  2971  2971 D BluetoothMap: Proxy object connected
09-15 10:03:00.262  5406  5421 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:03:00.262  5629  5629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:03:00.262  2971  2971 D MapProfile: Bluetooth service connected
09-15 10:03:00.262  2971  2971 D BluetoothMap: getConnectedDevices()
09-15 10:03:00.263  5406  5423 D BluetoothPan: onBluetoothStateChange on: true
09-15 10:03:00.263  5629  5629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:03:00.264  2971  2984 D BluetoothPan: onBluetoothStateChange on: true
09-15 10:03:00.265  5629  5629 D ObexServerSockets: Succeed to create listening sockets 
09-15 10:03:00.265  5629  5629 D ObexServerSockets0: startAccept()
09-15 10:03:00.265  5629  5629 D ObexServerSockets0: prepareForNewConnect()
09-15 10:03:00.265  5406  5668 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 10:03:00.266  5629  5629 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 10:03:00.266  5629  5629 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-15 10:03:00.267   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:03:00.267  5629  5669 D ObexServerSockets0: Accepting socket connection...
09-15 10:03:00.267  5629  5670 D ObexServerSockets0: Accepting socket connection...
09-15 10:03:00.268   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 10:03:00.270  5629  5629 D BluetoothMapService: onReceive
09-15 10:03:00.270  5629  5629 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 10:03:00.270  2971  2971 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 10:03:00.270  2971  2971 D PanProfile: Bluetooth service connected
09-15 10:03:00.270  5629  5629 D BluetoothMapService: STATE_ON
09-15 10:03:00.271  5406  5406 D BluetoothInputDevice: Proxy object connected
09-15 10:03:00.271  5406  5406 D HidProfile: Bluetooth service connected
09-15 10:03:00.271  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:00.273  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:00.273  5406  5406 D BluetoothA2dp: Proxy object connected
,09-15 10:03:00.274  5629  5671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:03:00.277  5629  5671 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 10:03:00.278  5629  5671 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 10:03:00.280  5406  5406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 10:03:00.283  5406  5406 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 10:03:00.283  5406  5406 D PanProfile: Bluetooth service connected
,09-15 10:03:00.287  3436  3436 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:03:00.289  5406  5406 D DockEventReceiver: finishStartingService: stopping service
,09-15 10:03:00.293  5406  5406 D BluetoothPbap: Proxy object connected
,09-15 10:03:00.293  5406  5406 D PbapServerProfile: Bluetooth service connected
,09-15 10:03:00.297  2971  2971 D BluetoothPbap: Proxy object connected
09-15 10:03:00.297  2971  2971 D PbapServerProfile: Bluetooth service connected
,09-15 10:03:00.298  5629  5629 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 10:03:00.298  5629  5629 D ObexServerSockets0: prepareForNewConnect()
,09-15 10:03:00.299  5629  5675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:03:00.313  5629  5679 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:03:00.315  5629  5679 I BtOppRfcommListener: Accept thread started.
,09-15 10:03:00.350   927   927 D BluetoothHeadset: Proxy object connected
09-15 10:03:00.350   927   927 D BluetoothHeadset: Proxy object connected
09-15 10:03:00.350  3347  3372 D BluetoothHeadset: Proxy object connected
,09-15 10:03:00.350   927   927 D BluetoothHeadset: Proxy object connected
09-15 10:03:00.351  2971  2985 D BluetoothHeadset: Proxy object connected
09-15 10:03:00.351  2971  2971 D HeadsetProfile: Bluetooth service connected
09-15 10:03:00.351   927   944 D BluetoothHeadset: Proxy object connected
09-15 10:03:00.351  5406  5423 D BluetoothHeadset: Proxy object connected
09-15 10:03:00.352  2971  2984 D BluetoothHeadset: Proxy object connected
09-15 10:03:00.352  2971  2971 D HeadsetProfile: Bluetooth service connected
09-15 10:03:00.353  5406  5406 D HeadsetProfile: Bluetooth service connected
,09-15 10:03:00.357  3347  3383 D BluetoothHeadset: Proxy object connected
,09-15 10:03:00.363  5406  5421 D BluetoothHeadset: Proxy object connected
,09-15 10:03:00.363  5406  5406 D HeadsetProfile: Bluetooth service connected
,09-15 10:03:00.367   927   944 D BluetoothHeadset: Proxy object connected
,09-15 10:03:04.069  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:03:04.069  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:04.069  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:04.069  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:03:04.069  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:04.069  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:04.069  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:04.069  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:04.075  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:03:04.075  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:04.076  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f0729d8 removed from the list
09-15 10:03:04.076  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:03:04.076  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:04.076  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:03:04.080  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 10:03:04.080  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9dcd131 added. We now have 4 listener(s)
09-15 10:03:04.080  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 10:03:04.083   927  3405 D WifiService: setWifiEnabled: false pid=5347, uid=10077
09-15 10:03:04.083   927  3405 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:03:09.094  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:03:09.095   927  3424 D WifiService: setWifiEnabled: true pid=5347, uid=10077
09-15 10:03:09.095   927  3424 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:03:09.105   508   921 D SoftapController: Softap fwReload - Ok
,09-15 10:03:09.110   508   921 D CommandListener: Setting iface cfg
,09-15 10:03:09.110   508   921 D CommandListener: Trying to bring down wlan0
09-15 10:03:09.112   508   921 D CommandListener: Clearing all IP addresses on wlan0
,09-15 10:03:09.117   927  2821 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 10:03:09.794   927  2821 D wifi    : set interface wlan0 flags (UP)
,09-15 10:03:09.800   927  2821 I WifiHAL : Initializing wifi
09-15 10:03:09.800   927  2821 I WifiHAL : Creating socket
09-15 10:03:09.803   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 10:03:09.807   927  2821 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 10:03:09.807   927  2821 D wifi    : Did set static halHandle = 0x7f80969aa0
09-15 10:03:09.808   927  2821 D wifi    : halHandle = 0x7f80969aa0, mVM = 0x7f9d00d140, mCls = 0x14d6
,09-15 10:03:09.809   927  2821 D wifi    : array field set
09-15 10:03:09.809   927  2821 I WifiNative-HAL: interface[0] = wlan0
09-15 10:03:09.812   927  5684 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547618200224
09-15 10:03:09.812   927  5684 D wifi    : waitForHalEvents called, vm = 0x7f9d00d140, obj = 0x14d6, env = 0x7f8231fcc0
,09-15 10:03:09.869  5685  5685 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 10:03:09.890  5685  5685 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 10:03:09.901  5685  5685 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 10:03:09.901  5685  5685 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 10:03:09.913   927  2821 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 10:03:09.928  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:03:09.928  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:09.928  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:09.928  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:03:09.928  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:09.928  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:09.928  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:09.928  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:09.930   927  2821 D WifiConfigStore: Loading config and enabling all networks 
09-15 10:03:09.931  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:03:09.934  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:03:09.934  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:09.934  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:09.934  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:03:09.934  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:09.934  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:09.934  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:09.934  5347  5347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:09.936  5347  5347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:03:09.938  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:09.939  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:09.940   927  2821 D WifiConfigStore: loaded 0 passpoint configs
09-15 10:03:09.940   927  2821 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 10:03:09.941   927  2821 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 10:03:09.943   927  2821 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-15 10:03:09.944   927  2821 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 10:03:09.944   927  2821 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 10:03:09.944   927  2821 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-15 10:03:09.944   927  2821 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 10:03:09.950   927  2821 D WifiNative-HAL: Setting external_sim to 1
,09-15 10:03:09.950  4104  4104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 10:03:09.950   927  2821 D wifi    : setting dfs flag to true, 0x7f847f6780
09-15 10:03:09.951   927  2821 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 10:03:09.951   927  2821 D wifi    : setting scan oui 0x7f847f6780
09-15 10:03:09.951   927  2821 D WifiHAL : Sending mac address OUI
,09-15 10:03:09.968   927  2821 E native  : do suspend true
,09-15 10:03:09.975   927  2821 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 10:03:09.975   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 10:03:09.976   927   927 D RttService: SCAN_AVAILABLE : 3
,09-15 10:03:09.976   927  2903 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 10:03:09.977   508   921 D CommandListener: Setting iface cfg
,09-15 10:03:09.981   927  2820 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
09-15 10:03:09.981   927  2820 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 10:03:09.987   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=413209 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,09-15 10:03:09.988   927  2820 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 10:03:09.989   927  2820 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 10:03:10.515   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:03:11.516   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:03:12.517   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:03:13.518   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:03:14.114  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:03:14.114  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:14.114  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:14.114  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:03:14.114  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:14.114  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:14.114  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:14.114  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:14.121  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:03:14.122  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:14.122  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9dcd131 removed from the list
,09-15 10:03:14.122  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:03:14.122  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:03:14.122  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:03:14.133  5347  5688 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-15 10:03:14.133  5347  5688 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 10:03:14.519   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:03:15.520   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:03:17.165  5347  5688 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-15 10:03:17.166  5347  5689 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-15 10:03:17.167  5347  5689 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-15 10:03:17.167  5347  5688 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-15 10:03:17.167  5347  5689 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:03:17.167  5347  5688 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:03:17.169  5347  5688 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 10:03:17.169  5347  5689 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:03:17.170  5347  5692 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: IncomingSocketThread/Sender)
,09-15 10:03:17.171  5347  5689 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-15 10:03:17.172  5347  5688 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-15 10:03:17.175  5347  5691 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Sender)
,09-15 10:03:17.176  5347  5693 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver)
,09-15 10:03:17.178  5347  5694 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: OutgoingSocketThread/Receiver)
09-15 10:03:17.179  5347  5693 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver)
09-15 10:03:17.179  5347  5693 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-15 10:03:17.180  5347  5693 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-15 10:03:17.180  5347  5694 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: OutgoingSocketThread/Receiver)
09-15 10:03:17.180  5347  5694 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-15 10:03:17.180  5347  5694 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-15 10:03:20.140  5347  5394 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-15 10:03:20.142  5347  5394 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-15 10:03:20.148  5347  5394 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@78718d9 Bundle[{}]
09-15 10:03:20.149  5347  5394 I io.jxcore.node.LifeCycleMonitor: start: OK
09-15 10:03:20.150  5347  5394 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-15 10:03:20.151  5347  5394 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-15 10:03:20.153  5347  5394 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 10:03:20.153  5347  5394 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-15 10:03:20.155  5347  5394 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-15 10:03:20.161  5347  5394 I System.out: Running OutgoingSocketThread
,09-15 10:03:20.163  5347  5695 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-15 10:03:20.164  5347  5695 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 10:03:23.175  5347  5695 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-15 10:03:23.175  5347  5696 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-15 10:03:23.175  5347  5695 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-15 10:03:23.175  5347  5696 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-15 10:03:23.176  5347  5696 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:03:23.176  5347  5695 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:03:23.177  5347  5696 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 10:03:23.178  5347  5696 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-15 10:03:23.178  5347  5695 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:03:23.181  5347  5699 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Sender)
,09-15 10:03:23.185  5347  5698 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender)
,09-15 10:03:23.186  5347  5695 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-15 10:03:23.189  5347  5700 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
,09-15 10:03:23.190  5347  5700 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
,09-15 10:03:23.190  5347  5700 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-15 10:03:23.191  5347  5700 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-15 10:03:23.191  5347  5701 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: OutgoingSocketThread/Receiver)
,09-15 10:03:23.193  5347  5701 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: OutgoingSocketThread/Receiver)
09-15 10:03:23.193  5347  5701 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-15 10:03:23.193  5347  5701 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-15 10:03:26.174  5347  5394 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-15 10:03:26.175  5347  5394 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-15 10:03:26.176  5347  5394 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
09-15 10:03:26.181  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 10:03:26.181  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a83016 added. We now have 3 listener(s)
,09-15 10:03:26.186  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 10:03:26.186  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 10:03:26.186  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:03:26.186  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:03:26.186  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8475d97 added. We now have 4 listener(s)
,09-15 10:03:26.187  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 10:03:26.188  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:03:26.192  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:03:26.196  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:03:26.196  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:26.196  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:26.196  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:03:26.196  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:26.196  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:26.196  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:26.196  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:26.199  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:03:26.199  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 10:03:26.200  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:03:26.200  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:03:26.200  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:03:26.200  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:03:26.201  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:26.201  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:03:26.201  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 10:03:26.201  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a83016 removed from the list
09-15 10:03:26.201  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:03:26.201  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8475d97 removed from the list
09-15 10:03:26.203  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:26.205  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:26.206  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:03:26.206  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:26.207  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:26.207  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:26.208  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:03:26.208  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 10:03:26.209  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:26.209  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8475d97 not in the list
09-15 10:03:26.209  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:26.209  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:26.210  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:03:26.211  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:03:26.211  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:03:26.211  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8475d97 not in the list
09-15 10:03:26.211  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:03:26.211  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:26.211  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:26.211  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a83016 not in the list
09-15 10:03:26.212  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 10:03:26.212  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efc4f6d added. We now have 3 listener(s)
,09-15 10:03:26.213  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 10:03:26.213  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 10:03:26.213  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:03:26.214  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:03:26.214  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cef37a2 added. We now have 4 listener(s)
09-15 10:03:26.214  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 10:03:26.215  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:03:26.217  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:03:26.221  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:03:26.221  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:26.221  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:26.221  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:03:26.221  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:26.221  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:26.221  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:26.221  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:26.223  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:03:26.224  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:03:26.224  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 10:03:26.224  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 10:03:26.224  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 10:03:26.224  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:03:26.224  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:03:26.225  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:03:26.228  5347  5394 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 10:03:26.228  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 10:03:26.228  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:03:26.232  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 10:03:26.232  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 10:03:26.233  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 10:03:26.235  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 10:03:26.235  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 10:03:26.235  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 10:03:26.236  5347  5394 D BluetoothAdapter: STATE_ON
,09-15 10:03:26.239  5629  5640 D BtGatt.GattService: registerClient() - UUID=a5333f27-3cbf-4356-bf3f-9cd848f626cd
09-15 10:03:26.240  5629  5645 D BtGatt.GattService: onClientRegistered() - UUID=a5333f27-3cbf-4356-bf3f-9cd848f626cd, clientIf=5
,09-15 10:03:26.241  5347  5357 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 10:03:26.242  5629  5658 D BtGatt.GattService: start scan with filters
,09-15 10:03:26.246  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 10:03:26.246  5629  5648 D BtGatt.ScanManager: handling starting scan
09-15 10:03:26.248  5629  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b48e352
,09-15 10:03:26.246  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 10:03:26.256  5629  5645 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 10:03:26.259  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:03:26.259  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 10:03:26.259  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 10:03:26.259  5629  5648 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 10:03:26.262  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 10:03:26.263  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 10:03:26.263  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 10:03:26.264  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 10:03:26.266  5629  5645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 10:03:26.266  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:03:26.266  5347  5394 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 10:03:26.266  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 10:03:26.266  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 10:03:26.266  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:26.266  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 10:03:26.266  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:03:26.266  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:03:26.266  5629  5648 D BtGatt.ScanManager: Starting BLE batch scan
09-15 10:03:26.266  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:03:26.267  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 10:03:26.267  5629  5648 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 10:03:26.267  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 10:03:26.267  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 10:03:26.268  5347  5394 D BluetoothAdapter: STATE_ON
,09-15 10:03:26.268  5629  5639 D BtGatt.GattService: stopScan() - queue size =1
09-15 10:03:26.269  5629  5640 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 10:03:26.269  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:03:26.269  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 10:03:26.269  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 10:03:26.270  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 10:03:26.270  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 10:03:26.271  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:03:26.275  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 10:03:26.275  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:03:26.275  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 10:03:26.276  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:03:26.277  5629  5645 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 10:03:26.277  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:03:26.277  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:03:26.277  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:03:26.277  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:03:26.282  5629  5645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 10:03:26.282  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:03:26.290  5629  5645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 10:03:26.290  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:03:26.291  5629  5648 D BtGatt.ScanManager: stopping BLe Batch
,09-15 10:03:26.295  5629  5645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 10:03:26.295  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:03:26.295  5629  5648 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 10:03:26.300  5629  5645 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 10:03:26.301  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:03:26.778  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-15 10:03:26.779  5347  5347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:03:26.779  5347  5347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:03:29.277  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:03:29.278  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:03:29.278  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:03:29.278  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:03:29.279  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:29.279  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 10:03:29.279  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 10:03:29.279  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efc4f6d removed from the list
09-15 10:03:29.279  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:29.279  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cef37a2 removed from the list
09-15 10:03:29.280  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:03:29.280  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:29.282  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:29.282  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:03:29.285  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 10:03:29.285  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:03:29.285  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:29.285  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cef37a2 not in the list
09-15 10:03:29.285  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:29.286  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:03:29.288  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 10:03:29.289  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:03:29.289  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:29.289  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cef37a2 not in the list
09-15 10:03:29.289  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:03:29.289  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:29.290  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:29.290  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efc4f6d not in the list
,09-15 10:03:29.292  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 10:03:29.292  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d32688f added. We now have 3 listener(s)
,09-15 10:03:29.298  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 10:03:29.298  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 10:03:29.298  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:03:29.298  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:03:29.298  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ec471c added. We now have 4 listener(s)
09-15 10:03:29.298  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 10:03:29.300  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:03:29.305  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:03:29.310  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:03:29.310  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:29.310  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:29.310  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:03:29.310  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:29.310  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:29.310  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:29.310  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:29.314  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:03:29.314  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 10:03:29.315  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 10:03:29.316  5347  5394 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-15 10:03:29.316  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-15 10:03:29.317  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:29.317  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 10:03:29.317  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 10:03:29.317  5347  5394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-15 10:03:29.317  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:03:29.325  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-15 10:03:29.326  5347  5394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 10:03:29.326  5347  5394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 10:03:29.326  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 10:03:29.326  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-15 10:03:29.326  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:03:29.326  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:03:29.326  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:03:29.326  5347  5347 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 10:03:29.327  5347  5702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:03:29.329  5667  5667 W Binder_6: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[28521]" dev="sockfs" ino=28521 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:03:29.331  5347  5394 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 10:03:29.332  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 10:03:29.332  5347  5702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-15 10:03:29.329  5667  5667 W Binder_6: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28521]" dev="sockfs" ino=28521 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:03:29.337  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 10:03:29.338  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 10:03:29.338  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 10:03:29.340  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-15 10:03:29.340  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:03:29.341  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-15 10:03:29.342  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:03:29.342  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:03:29.342  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-15 10:03:29.343  5347  5394 D BluetoothAdapter: STATE_ON
,09-15 10:03:29.348  5629  5639 D BtGatt.GattService: registerClient() - UUID=3e7c0bc5-4c37-4f26-b668-54aa81d92dbd
09-15 10:03:29.349  5629  5645 D BtGatt.GattService: onClientRegistered() - UUID=3e7c0bc5-4c37-4f26-b668-54aa81d92dbd, clientIf=5
,09-15 10:03:29.349  5347  5357 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-15 10:03:29.351  5629  5647 D BtGatt.AdvertiseManager: message : 0
,09-15 10:03:29.354  5629  5647 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 10:03:29.365  5629  5645 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 10:03:29.372  5629  5645 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 10:03:29.373  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 10:03:29.373  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 10:03:29.375  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 10:03:29.376  5347  5347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 10:03:29.376  5347  5347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 10:03:29.376  5347  5347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 10:03:29.376  5347  5347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 10:03:29.376  5347  5347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 10:03:29.377  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-15 10:03:29.378  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-15 10:03:29.380  5347  5347 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-15 10:03:29.380  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:03:29.881  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-15 10:03:29.881  5347  5347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 10:03:29.882  5347  5347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:03:32.380  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:03:32.380  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-15 10:03:32.380  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 10:03:32.381  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-15 10:03:32.381  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 10:03:32.381  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-15 10:03:32.382  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 10:03:32.382  5347  5702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 10:03:32.382  5347  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 10:03:32.382  5347  5394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-15 10:03:32.382  5347  5702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 10:03:32.382  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:03:32.382  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:03:32.382  5347  5347 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 10:03:32.383  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-15 10:03:32.383  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 10:03:32.385  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 10:03:32.387  5347  5394 D BluetoothAdapter: STATE_ON
09-15 10:03:32.388  5347  5394 D BluetoothLeScanner: could not find callback wrapper
09-15 10:03:32.388  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:03:32.388  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-15 10:03:32.390  5629  5647 D BtGatt.AdvertiseManager: message : 1
09-15 10:03:32.392  5629  5647 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 10:03:32.406  5629  5645 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-15 10:03:32.407  5629  5645 D BtGatt.GattService: Client app is not null!
,09-15 10:03:32.409  5629  5665 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 10:03:32.410  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 10:03:32.410  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 10:03:32.411  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 10:03:32.411  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-15 10:03:32.411  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-15 10:03:32.414  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:03:32.414  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:03:32.415  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 10:03:32.416  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:03:32.418  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:03:32.418  5347  5347 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 10:03:32.418  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:32.418  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:03:32.418  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 10:03:32.418  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:03:32.419  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d32688f removed from the list
09-15 10:03:32.419  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:32.419  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:03:32.419  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ec471c removed from the list
09-15 10:03:32.419  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:03:32.419  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:03:32.419  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:32.421  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:32.421  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:32.423  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:03:32.423  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:03:32.423  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:32.423  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ec471c not in the list
,09-15 10:03:32.424  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:32.424  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:32.426  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:03:32.426  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:03:32.426  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:32.426  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ec471c not in the list
,09-15 10:03:32.426  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:03:32.426  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:32.426  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:32.427  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d32688f not in the list
09-15 10:03:32.428  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 10:03:32.428  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19368a1 added. We now have 3 listener(s)
,09-15 10:03:32.430  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:03:32.430  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 10:03:32.430  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 10:03:32.431  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:03:32.431  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32acac6 added. We now have 4 listener(s)
09-15 10:03:32.431  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 10:03:32.432  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:03:32.436  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:03:32.440  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:03:32.440  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:32.440  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:32.440  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:03:32.440  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:32.440  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:32.440  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:32.440  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:32.444  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:03:32.444  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:03:32.444  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 10:03:32.444  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 10:03:32.444  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 10:03:32.445  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:03:32.445  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:03:32.446  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:03:32.449  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:03:32.450  5347  5394 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 10:03:32.451  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 10:03:32.456  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 10:03:32.457  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 10:03:32.457  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 10:03:32.461  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 10:03:32.461  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 10:03:32.461  5347  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 10:03:32.462  5347  5394 D BluetoothAdapter: STATE_ON
,09-15 10:03:32.466  5629  5665 D BtGatt.GattService: registerClient() - UUID=f76607d2-c366-425b-a886-73df9fffb302
09-15 10:03:32.466  5629  5645 D BtGatt.GattService: onClientRegistered() - UUID=f76607d2-c366-425b-a886-73df9fffb302, clientIf=5
09-15 10:03:32.466  5347  5358 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 10:03:32.467  5629  5667 D BtGatt.GattService: start scan with filters
,09-15 10:03:32.470  5629  5648 D BtGatt.ScanManager: handling starting scan
,09-15 10:03:32.470  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 10:03:32.470  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 10:03:32.471  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 10:03:32.471  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 10:03:32.477  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 10:03:32.477  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 10:03:32.477  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 10:03:32.478  5629  5645 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 10:03:32.478  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:03:32.478  5629  5648 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 10:03:32.479  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 10:03:32.484  5629  5645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 10:03:32.485  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:03:32.485  5629  5648 D BtGatt.ScanManager: Starting BLE batch scan
09-15 10:03:32.485  5629  5648 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 10:03:32.497  5629  5645 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 10:03:32.497  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:03:32.502  5629  5645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-15 10:03:32.502  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:03:32.919  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 10:03:32.978  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 10:03:32.979  5347  5347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 10:03:32.979  5347  5347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:03:35.489  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:03:35.490  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 10:03:35.490  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 10:03:35.490  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:35.490  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-15 10:03:35.491  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:03:35.491  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:03:35.491  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:03:35.491  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 10:03:35.491  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 10:03:35.492  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 10:03:35.494  5347  5394 D BluetoothAdapter: STATE_ON
09-15 10:03:35.496  5629  5639 D BtGatt.GattService: stopScan() - queue size =1
,09-15 10:03:35.499  5629  5666 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 10:03:35.503  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:03:35.504  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 10:03:35.504  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 10:03:35.505  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-15 10:03:35.505  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 10:03:35.506  5629  5629 D BtGatt.ScanManager: awakened up at time 438728
09-15 10:03:35.508  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:03:35.508  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 10:03:35.509  5347  5394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:03:35.509  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 10:03:35.512  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 10:03:35.513  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:03:35.513  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:03:35.514  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:35.514  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:03:35.514  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 10:03:35.514  5347  5347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:03:35.514  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19368a1 removed from the list
09-15 10:03:35.514  5347  5347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:03:35.514  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 10:03:35.514  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32acac6 removed from the list
09-15 10:03:35.514  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:03:35.514  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:35.515  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:03:35.515  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:35.516  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:03:35.516  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:03:35.516  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:35.516  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32acac6 not in the list
09-15 10:03:35.516  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:35.516  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:35.517  5629  5645 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 10:03:35.517  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:03:35.517  5629  5648 D BtGatt.ScanManager: stopping BLe Batch
09-15 10:03:35.518  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:03:35.518  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:03:35.518  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:35.518  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32acac6 not in the list
09-15 10:03:35.518  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:03:35.518  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:35.518  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:35.518  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19368a1 not in the list
09-15 10:03:35.519  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 10:03:35.519  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a9823 added. We now have 3 listener(s)
,09-15 10:03:35.521  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:03:35.521  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 10:03:35.521  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:03:35.521  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:03:35.522  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfa120 added. We now have 4 listener(s)
09-15 10:03:35.522  5347  5394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 10:03:35.522  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:03:35.525  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:03:35.528  5629  5645 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 10:03:35.528  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:03:35.528  5629  5648 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 10:03:35.530  5347  5394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:03:35.530  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:03:35.530  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:03:35.530  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:03:35.530  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:03:35.530  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:03:35.530  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:03:35.530  5347  5394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:03:35.532  5347  5394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:03:35.532  5347  5394 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:03:35.532  5347  5394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:03:35.532  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:03:35.532  5347  5394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:03:35.533  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:03:35.533  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:35.533  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:03:35.533  5347  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 10:03:35.533  5347  5394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a9823 removed from the list
09-15 10:03:35.533  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:35.533  5347  5394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfa120 removed from the list
,09-15 10:03:35.535  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:35.537  5347  5394 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:03:35.537  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:35.538  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:35.538  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:35.540  5347  5347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:03:35.540  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:03:35.540  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:03:35.540  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:35.540  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfa120 not in the list
,09-15 10:03:35.541  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:35.541  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:35.542  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:03:35.542  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 10:03:35.542  5347  5394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:03:35.542  5347  5394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfa120 not in the list
09-15 10:03:35.542  5347  5394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:03:35.542  5347  5394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:03:35.542  5347  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:03:35.543  5347  5394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a9823 not in the list
,09-15 10:03:35.543  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-15 10:03:35.544  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 10:03:35.544  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-15 10:03:35.544  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 10:03:35.544  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 10:03:35.544  5347  5394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 10:03:35.547  5629  5645 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-15 10:03:35.547  5629  5645 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:03:35.547  5629  5645 D BtGatt.GattService: current time is 438769510670
09-15 10:03:35.547  5629  5645 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -88, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -78, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -80, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -87, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-15 10:03:35.548  5629  5645 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-15 10:03:35.549  5629  5645 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-15 10:03:35.549  5629  5645 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-15 10:03:35.549  5629  5645 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-15 10:03:35.549  5629  5645 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-15 10:03:36.014  5347  5347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 10:03:37.555  5347  5703 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,09-15 10:03:39.554  5347  5394 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 187
,09-15 10:03:39.554  5347  5394 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 187, name: My test thread name)
,09-15 10:03:39.558  5347  5704 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name)
,09-15 10:03:39.558  5347  5704 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 188, thread name: My test thread name)
09-15 10:03:39.560  5347  5704 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-15 10:03:39.563  5347  5394 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 10:03:39.569  5347  5705 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name)
,09-15 10:03:39.570  5347  5705 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 192, thread name: My test thread name): Test exception.
,09-15 10:03:39.570  5347  5705 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-15 10:03:39.579  5347  5394 I jxcore-log: Total number of executed tests:  82
09-15 10:03:39.579  5347  5394 I jxcore-log: 
,09-15 10:03:39.580  5347  5394 I jxcore-log: Number of passed tests:  82
09-15 10:03:39.580  5347  5394 I jxcore-log: 
09-15 10:03:39.580  5347  5394 I jxcore-log: Number of failed tests:  0
09-15 10:03:39.580  5347  5394 I jxcore-log: 
09-15 10:03:39.580  5347  5394 I jxcore-log: Number of ignored tests:  0
09-15 10:03:39.580  5347  5394 I jxcore-log: 
,09-15 10:03:39.580  5347  5394 I jxcore-log: Total duration:  101016
09-15 10:03:39.580  5347  5394 I jxcore-log: 
,09-15 10:03:39.588  5347  5394 I jxcore-log: Unit Test app is loaded
09-15 10:03:39.588  5347  5394 I jxcore-log: 
,09-15 10:03:39.603  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.603  5347  5394 I jxcore-log: 
,09-15 10:03:39.610  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.610  5347  5394 I jxcore-log: 
,09-15 10:03:39.611  5347  5347 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-15 10:03:39.612  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.612  5347  5394 I jxcore-log: 
,09-15 10:03:39.613  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.613  5347  5394 I jxcore-log: 
,09-15 10:03:39.616  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 10:03:39.616  5347  5394 I jxcore-log: 
,09-15 10:03:39.618  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 10:03:39.618  5347  5394 I jxcore-log: 
,09-15 10:03:39.621  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.621  5347  5394 I jxcore-log: 
,09-15 10:03:39.623  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.623  5347  5394 I jxcore-log: 
09-15 10:03:39.624  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 10:03:39.624  5347  5394 I jxcore-log: 
,09-15 10:03:39.625  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 10:03:39.625  5347  5394 I jxcore-log: 
,09-15 10:03:39.626  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 10:03:39.626  5347  5394 I jxcore-log: 
09-15 10:03:39.628  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.628  5347  5394 I jxcore-log: 
,09-15 10:03:39.629  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.629  5347  5394 I jxcore-log: 
,09-15 10:03:39.630  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.630  5347  5394 I jxcore-log: 
09-15 10:03:39.631  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.631  5347  5394 I jxcore-log: 
,09-15 10:03:39.632  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.632  5347  5394 I jxcore-log: 
,09-15 10:03:39.633  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.633  5347  5394 I jxcore-log: 
,09-15 10:03:39.634  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.634  5347  5394 I jxcore-log: 
,09-15 10:03:39.635  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.635  5347  5394 I jxcore-log: 
,09-15 10:03:39.636  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.636  5347  5394 I jxcore-log: 
,09-15 10:03:39.637  5347  5703 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
09-15 10:03:39.637  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.637  5347  5394 I jxcore-log: 
,09-15 10:03:39.638  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.638  5347  5394 I jxcore-log: 
,09-15 10:03:39.639  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.639  5347  5394 I jxcore-log: 
09-15 10:03:39.640  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.640  5347  5394 I jxcore-log: 
09-15 10:03:39.640  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.640  5347  5394 I jxcore-log: 
09-15 10:03:39.641  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.641  5347  5394 I jxcore-log: 
,09-15 10:03:39.642  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:03:39.642  5347  5394 I jxcore-log: 
,09-15 10:03:39.643  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.643  5347  5394 I jxcore-log: 
09-15 10:03:39.643  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.643  5347  5394 I jxcore-log: 
09-15 10:03:39.644  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.644  5347  5394 I jxcore-log: 
09-15 10:03:39.644  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.644  5347  5394 I jxcore-log: 
,09-15 10:03:39.645  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.645  5347  5394 I jxcore-log: 
,09-15 10:03:39.646  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.646  5347  5394 I jxcore-log: 
,09-15 10:03:39.647  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.647  5347  5394 I jxcore-log: 
,09-15 10:03:39.648  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.648  5347  5394 I jxcore-log: 
,09-15 10:03:39.649  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.649  5347  5394 I jxcore-log: 
09-15 10:03:39.649  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.649  5347  5394 I jxcore-log: 
09-15 10:03:39.650  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.650  5347  5394 I jxcore-log: 
09-15 10:03:39.650  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.650  5347  5394 I jxcore-log: 
09-15 10:03:39.651  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:03:39.651  5347  5394 I jxcore-log: 
,09-15 10:03:39.652  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.652  5347  5394 I jxcore-log: 
,09-15 10:03:39.652  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.652  5347  5394 I jxcore-log: 
09-15 10:03:39.653  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.653  5347  5394 I jxcore-log: 
,09-15 10:03:39.654  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.654  5347  5394 I jxcore-log: 
,09-15 10:03:39.655  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.655  5347  5394 I jxcore-log: 
,09-15 10:03:39.656  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 10:03:39.656  5347  5394 I jxcore-log: 
09-15 10:03:39.656  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.656  5347  5394 I jxcore-log: 
09-15 10:03:39.657  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 10:03:39.657  5347  5394 I jxcore-log: 
09-15 10:03:39.658  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.658  5347  5394 I jxcore-log: 
,09-15 10:03:39.659  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 10:03:39.659  5347  5394 I jxcore-log: 
,09-15 10:03:39.660  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 10:03:39.660  5347  5394 I jxcore-log: 
,09-15 10:03:39.660  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:03:39.660  5347  5394 I jxcore-log: 
,09-15 10:03:39.661  5347  5394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 10:03:39.661  5347  5394 I jxcore-log: 
,09-15 10:03:39.667  5347  5394 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-15 10:03:39.667  5347  5394 I jxcore-log:   bluetooth: 'on',
09-15 10:03:39.667  5347  5394 I jxcore-log:   wifi: 'on',
09-15 10:03:39.667  5347  5394 I jxcore-log:   cellular: 'doNotCare',
09-15 10:03:39.667  5347  5394 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-15 10:03:39.667  5347  5394 I jxcore-log: 
,09-15 10:03:39.674  5347  5394 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-15 10:03:39.674  5347  5394 I jxcore-log:   bluetooth: 'on',
09-15 10:03:39.674  5347  5394 I jxcore-log:   wifi: 'on',
09-15 10:03:39.674  5347  5394 I jxcore-log:   cellular: 'doNotCare' }
09-15 10:03:39.674  5347  5394 I jxcore-log: 
,09-15 10:03:39.675  5347  5394 I jxcore-log: My device name is: Huawei-Nexus 6P
09-15 10:03:39.675  5347  5394 I jxcore-log: 
,09-15 10:03:39.676  5347  5394 I jxcore-log: WARN testUtils: myNameCallback not set!
09-15 10:03:39.676  5347  5394 I jxcore-log: 
,09-15 10:03:39.676  5347  5394 I jxcore-log: Running for WIFI network type
09-15 10:03:39.676  5347  5394 I jxcore-log: 
,09-15 10:03:40.520   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 10:03:40.520   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:03:41.429  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-15 10:03:41.429  5347  5394 I jxcore-log: 
,09-15 10:03:41.734  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-15 10:03:41.734  5347  5394 I jxcore-log: 
,09-15 10:03:41.760  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-15 10:03:41.760  5347  5394 I jxcore-log: 
,09-15 10:03:42.896  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-15 10:03:42.896  5347  5394 I jxcore-log: 
,09-15 10:03:42.900  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-15 10:03:42.900  5347  5394 I jxcore-log: 
,09-15 10:03:42.904  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-15 10:03:42.904  5347  5394 I jxcore-log: 
,09-15 10:03:42.948  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-15 10:03:42.948  5347  5394 I jxcore-log: 
,09-15 10:03:42.960  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-15 10:03:42.960  5347  5394 I jxcore-log: 
,09-15 10:03:42.963  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-15 10:03:42.963  5347  5394 I jxcore-log: 
,09-15 10:03:43.604  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-15 10:03:43.604  5347  5394 I jxcore-log: 
,09-15 10:03:43.830  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-15 10:03:43.830  5347  5394 I jxcore-log: 
,09-15 10:03:43.838  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-15 10:03:43.838  5347  5394 I jxcore-log: 
,09-15 10:03:43.843  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-15 10:03:43.843  5347  5394 I jxcore-log: 
,09-15 10:03:43.855  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-15 10:03:43.855  5347  5394 I jxcore-log: 
,09-15 10:03:43.879  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-15 10:03:43.879  5347  5394 I jxcore-log: 
,09-15 10:03:43.908  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-15 10:03:43.908  5347  5394 I jxcore-log: 
,09-15 10:03:43.913  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-15 10:03:43.913  5347  5394 I jxcore-log: 
,09-15 10:03:43.919  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-15 10:03:43.919  5347  5394 I jxcore-log: 
,09-15 10:03:43.931  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-15 10:03:43.931  5347  5394 I jxcore-log: 
,09-15 10:03:43.935  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-15 10:03:43.935  5347  5394 I jxcore-log: 
,09-15 10:03:43.939  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-15 10:03:43.939  5347  5394 I jxcore-log: 
,09-15 10:03:43.949  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-15 10:03:43.949  5347  5394 I jxcore-log: 
,09-15 10:03:43.967  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-15 10:03:43.967  5347  5394 I jxcore-log: 
,09-15 10:03:43.975  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-15 10:03:43.975  5347  5394 I jxcore-log: 
,09-15 10:03:43.985  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-15 10:03:43.985  5347  5394 I jxcore-log: 
,09-15 10:03:43.992  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-15 10:03:43.992  5347  5394 I jxcore-log: 
,09-15 10:03:44.002  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-15 10:03:44.002  5347  5394 I jxcore-log: 
,09-15 10:03:44.010  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-15 10:03:44.010  5347  5394 I jxcore-log: 
,09-15 10:03:44.014  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-15 10:03:44.014  5347  5394 I jxcore-log: 
,09-15 10:03:44.032  5347  5394 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-15 10:03:44.032  5347  5394 I jxcore-log: 
,09-15 10:03:44.038  5347  5394 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-15 10:03:44.039  5347  5394 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-15 10:03:44.039  5347  5394 I jxcore-log: 
,09-15 10:03:44.040  5347  5394 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-15 10:03:44.040  5347  5394 I jxcore-log: 
,09-15 10:03:44.040  5347  5394 I jxcore-log: ThaliTape :: Started ThaliTape
09-15 10:03:44.040  5347  5394 I jxcore-log: 
,09-15 10:03:44.043  5347  5394 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-15 10:03:44.043  5347  5394 I jxcore-log: 
,09-15 10:03:44.071  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:03:44.071  5347  5394 I jxcore-log: 
,09-15 10:03:44.071  5347  5394 I jxcore-log: websocket error
09-15 10:03:44.071  5347  5394 I jxcore-log: 
,09-15 10:03:44.072  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:03:44.072  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:03:44.072  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:03:44.072  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:44.072  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:03:44.072  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:44.072  5347  5394 I jxcore-log: 
,09-15 10:03:44.072  5347  5394 I jxcore-log: WARN testUtils: logCallback not set!
09-15 10:03:44.072  5347  5394 I jxcore-log: 
,09-15 10:03:44.964  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:03:44.964  5347  5394 I jxcore-log: 
,09-15 10:03:44.965  5347  5394 I jxcore-log: websocket error
09-15 10:03:44.965  5347  5394 I jxcore-log: 
09-15 10:03:44.965  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:03:44.965  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:03:44.965  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:03:44.965  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:44.965  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:03:44.965  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:44.965  5347  5394 I jxcore-log: 
,09-15 10:03:47.537  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:03:47.537  5347  5394 I jxcore-log: 
09-15 10:03:47.538  5347  5394 I jxcore-log: websocket error
09-15 10:03:47.538  5347  5394 I jxcore-log: 
09-15 10:03:47.538  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:03:47.538  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:03:47.538  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:03:47.538  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:47.538  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:03:47.538  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:47.538  5347  5394 I jxcore-log: 
,09-15 10:03:52.569  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:03:52.569  5347  5394 I jxcore-log: 
,09-15 10:03:52.570  5347  5394 I jxcore-log: websocket error
09-15 10:03:52.570  5347  5394 I jxcore-log: 
09-15 10:03:52.570  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:03:52.570  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:03:52.570  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:03:52.570  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:52.570  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:03:52.570  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:52.570  5347  5394 I jxcore-log: 
,09-15 10:03:57.601  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:03:57.601  5347  5394 I jxcore-log: 
,09-15 10:03:57.601  5347  5394 I jxcore-log: websocket error
09-15 10:03:57.601  5347  5394 I jxcore-log: 
09-15 10:03:57.601  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:03:57.601  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:03:57.601  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:03:57.601  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:57.601  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:03:57.601  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:03:57.601  5347  5394 I jxcore-log: 
,09-15 10:04:00.522   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:01.523   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:02.525   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:02.636  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:02.636  5347  5394 I jxcore-log: 
,09-15 10:04:02.636  5347  5394 I jxcore-log: websocket error
09-15 10:04:02.636  5347  5394 I jxcore-log: 
09-15 10:04:02.637  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:02.637  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:02.637  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:02.637  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:02.637  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:02.637  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:02.637  5347  5394 I jxcore-log: 
,09-15 10:04:03.526   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:04.528   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:05.528   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:04:07.664  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:07.664  5347  5394 I jxcore-log: 
,09-15 10:04:07.665  5347  5394 I jxcore-log: websocket error
09-15 10:04:07.665  5347  5394 I jxcore-log: 
09-15 10:04:07.665  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:07.665  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:07.665  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:07.665  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:07.665  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:07.665  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:07.665  5347  5394 I jxcore-log: 
,09-15 10:04:10.529   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:11.531   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:12.532   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:12.692  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:12.692  5347  5394 I jxcore-log: 
09-15 10:04:12.692  5347  5394 I jxcore-log: websocket error
09-15 10:04:12.692  5347  5394 I jxcore-log: 
09-15 10:04:12.692  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:12.692  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:12.692  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:12.692  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:12.692  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:12.692  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:12.692  5347  5394 I jxcore-log: 
,09-15 10:04:13.533   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:14.535   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:15.535   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:04:17.721  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:17.721  5347  5394 I jxcore-log: 
,09-15 10:04:17.721  5347  5394 I jxcore-log: websocket error
09-15 10:04:17.721  5347  5394 I jxcore-log: 
,09-15 10:04:17.722  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:17.722  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:17.722  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:17.722  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:17.722  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:17.722  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:17.722  5347  5394 I jxcore-log: 
,09-15 10:04:22.752  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:22.752  5347  5394 I jxcore-log: 
,09-15 10:04:22.752  5347  5394 I jxcore-log: websocket error
09-15 10:04:22.752  5347  5394 I jxcore-log: 
09-15 10:04:22.753  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:22.753  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:22.753  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:22.753  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:22.753  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:22.753  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:22.753  5347  5394 I jxcore-log: 
,09-15 10:04:25.537   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:26.538   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:27.540   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:27.814  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:27.814  5347  5394 I jxcore-log: 
09-15 10:04:27.815  5347  5394 I jxcore-log: websocket error
09-15 10:04:27.815  5347  5394 I jxcore-log: 
09-15 10:04:27.815  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:27.815  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:27.815  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:27.815  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:27.815  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:27.815  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:27.815  5347  5394 I jxcore-log: 
,09-15 10:04:28.541   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:29.542   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:30.543   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:04:32.845  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:32.845  5347  5394 I jxcore-log: 
,09-15 10:04:32.845  5347  5394 I jxcore-log: websocket error
09-15 10:04:32.845  5347  5394 I jxcore-log: 
09-15 10:04:32.846  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:32.846  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:32.846  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:32.846  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:32.846  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:32.846  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:32.846  5347  5394 I jxcore-log: 
,09-15 10:04:37.871  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:37.871  5347  5394 I jxcore-log: 
09-15 10:04:37.871  5347  5394 I jxcore-log: websocket error
09-15 10:04:37.871  5347  5394 I jxcore-log: 
,09-15 10:04:37.872  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:37.872  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:37.872  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:37.872  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:37.872  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:37.872  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:37.872  5347  5394 I jxcore-log: 
,09-15 10:04:42.896  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:42.896  5347  5394 I jxcore-log: 
,09-15 10:04:42.897  5347  5394 I jxcore-log: websocket error
09-15 10:04:42.897  5347  5394 I jxcore-log: 
09-15 10:04:42.897  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:42.897  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:42.897  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:42.897  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:42.897  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:42.897  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:42.897  5347  5394 I jxcore-log: 
,09-15 10:04:45.545   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:46.547   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:47.548   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:47.924  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:47.924  5347  5394 I jxcore-log: 
,09-15 10:04:47.925  5347  5394 I jxcore-log: websocket error
09-15 10:04:47.925  5347  5394 I jxcore-log: 
,09-15 10:04:47.926  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:47.926  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:47.926  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:47.926  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:47.926  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:47.926  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:47.926  5347  5394 I jxcore-log: 
,09-15 10:04:48.550   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:49.551   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:04:50.552   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:04:52.949  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:52.949  5347  5394 I jxcore-log: 
09-15 10:04:52.949  5347  5394 I jxcore-log: websocket error
09-15 10:04:52.949  5347  5394 I jxcore-log: 
09-15 10:04:52.949  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:52.949  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:52.949  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:52.949  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:52.949  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:52.949  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:52.949  5347  5394 I jxcore-log: 
,09-15 10:04:57.975  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:04:57.975  5347  5394 I jxcore-log: 
09-15 10:04:57.975  5347  5394 I jxcore-log: websocket error
09-15 10:04:57.975  5347  5394 I jxcore-log: 
09-15 10:04:57.975  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:04:57.975  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:04:57.975  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:04:57.975  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:57.975  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:04:57.975  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:04:57.975  5347  5394 I jxcore-log: 
,09-15 10:05:03.000  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:03.000  5347  5394 I jxcore-log: 
,09-15 10:05:03.001  5347  5394 I jxcore-log: websocket error
09-15 10:05:03.001  5347  5394 I jxcore-log: 
09-15 10:05:03.001  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:03.001  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:03.001  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:03.001  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:03.001  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:03.001  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:03.001  5347  5394 I jxcore-log: 
,09-15 10:05:08.026  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:08.026  5347  5394 I jxcore-log: 
,09-15 10:05:08.027  5347  5394 I jxcore-log: websocket error
09-15 10:05:08.027  5347  5394 I jxcore-log: 
09-15 10:05:08.027  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:08.027  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:08.027  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:08.027  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:08.027  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:08.027  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:08.027  5347  5394 I jxcore-log: 
,09-15 10:05:10.553   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:05:11.555   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:05:12.556   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:05:13.051  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:13.051  5347  5394 I jxcore-log: 
,09-15 10:05:13.052  5347  5394 I jxcore-log: websocket error
09-15 10:05:13.052  5347  5394 I jxcore-log: 
09-15 10:05:13.052  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:13.052  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:13.052  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:13.052  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:13.052  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:13.052  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:13.052  5347  5394 I jxcore-log: 
,09-15 10:05:13.557   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:05:14.558   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:05:15.559   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:05:18.076  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:18.076  5347  5394 I jxcore-log: 
,09-15 10:05:18.076  5347  5394 I jxcore-log: websocket error
09-15 10:05:18.076  5347  5394 I jxcore-log: 
09-15 10:05:18.077  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:18.077  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:18.077  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:18.077  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:18.077  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:18.077  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:18.077  5347  5394 I jxcore-log: 
,09-15 10:05:23.103  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:23.103  5347  5394 I jxcore-log: 
,09-15 10:05:23.104  5347  5394 I jxcore-log: websocket error
09-15 10:05:23.104  5347  5394 I jxcore-log: 
09-15 10:05:23.106  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:23.106  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:23.106  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:23.106  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:23.106  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:23.106  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:23.106  5347  5394 I jxcore-log: 
,09-15 10:05:28.129  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:28.129  5347  5394 I jxcore-log: 
,09-15 10:05:28.130  5347  5394 I jxcore-log: websocket error
09-15 10:05:28.130  5347  5394 I jxcore-log: 
09-15 10:05:28.130  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:28.130  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:28.130  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:28.130  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:28.130  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:28.130  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:28.130  5347  5394 I jxcore-log: 
,09-15 10:05:33.160  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:33.160  5347  5394 I jxcore-log: 
09-15 10:05:33.160  5347  5394 I jxcore-log: websocket error
09-15 10:05:33.160  5347  5394 I jxcore-log: 
09-15 10:05:33.160  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:33.160  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:33.160  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:33.160  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:33.160  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:33.160  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:33.160  5347  5394 I jxcore-log: 
,09-15 10:05:38.184  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:38.184  5347  5394 I jxcore-log: 
,09-15 10:05:38.184  5347  5394 I jxcore-log: websocket error
09-15 10:05:38.184  5347  5394 I jxcore-log: 
,09-15 10:05:38.185  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:38.185  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:38.185  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:38.185  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:38.185  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:38.185  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:38.185  5347  5394 I jxcore-log: 
,09-15 10:05:40.559   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 10:05:40.560   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:05:43.210  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:43.210  5347  5394 I jxcore-log: 
,09-15 10:05:43.210  5347  5394 I jxcore-log: websocket error
09-15 10:05:43.210  5347  5394 I jxcore-log: 
09-15 10:05:43.210  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:43.210  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:43.210  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:43.210  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:43.210  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:43.210  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:43.210  5347  5394 I jxcore-log: 
,09-15 10:05:48.240  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:48.240  5347  5394 I jxcore-log: 
,09-15 10:05:48.240  5347  5394 I jxcore-log: websocket error
09-15 10:05:48.240  5347  5394 I jxcore-log: 
09-15 10:05:48.240  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:48.240  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:48.240  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:48.240  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:48.240  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:48.240  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:48.240  5347  5394 I jxcore-log: 
,09-15 10:05:53.263  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:53.263  5347  5394 I jxcore-log: 
09-15 10:05:53.264  5347  5394 I jxcore-log: websocket error
09-15 10:05:53.264  5347  5394 I jxcore-log: 
09-15 10:05:53.264  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:53.264  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:53.264  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:53.264  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:53.264  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:53.264  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:53.264  5347  5394 I jxcore-log: 
,09-15 10:05:58.288  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:05:58.288  5347  5394 I jxcore-log: 
,09-15 10:05:58.288  5347  5394 I jxcore-log: websocket error
09-15 10:05:58.288  5347  5394 I jxcore-log: 
09-15 10:05:58.289  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:05:58.289  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:05:58.289  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:05:58.289  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:58.289  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:05:58.289  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:05:58.289  5347  5394 I jxcore-log: 
,09-15 10:06:03.312  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:03.312  5347  5394 I jxcore-log: 
,09-15 10:06:03.312  5347  5394 I jxcore-log: websocket error
09-15 10:06:03.312  5347  5394 I jxcore-log: 
09-15 10:06:03.313  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:03.313  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:03.313  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:03.313  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:03.313  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:03.313  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:03.313  5347  5394 I jxcore-log: 
,09-15 10:06:05.655   536  1156 E QC-QMI  : qmi_client [536] 9: failed to locate client data
,09-15 10:06:05.658   520   520 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
09-15 10:06:05.658   520   520 E QC-QMI  : QMUX qmux_client_id=9 not found in qmux client list, unable to remove
,09-15 10:06:05.662   536   536 I Atfwd_Daemon: Stop the daemon....
,09-15 10:06:05.696  5708  5708 W ATFWD-daemon: type=1400 audit(0.0:120): avc: denied { read write } for name="diag" dev="tmpfs" ino=11712 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-15 10:06:05.698  5708  5708 I libmdmdetect: ESOC framework not supported
09-15 10:06:05.699  5708  5708 I libmdmdetect: Found internal modem: modem
,09-15 10:06:05.699  5708  5708 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-15 10:06:05.704  5708  5708 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-15 10:06:05.704  5708  5708 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
09-15 10:06:05.704  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:06.706  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:07.708  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:08.336  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:08.336  5347  5394 I jxcore-log: 
09-15 10:06:08.337  5347  5394 I jxcore-log: websocket error
09-15 10:06:08.337  5347  5394 I jxcore-log: 
09-15 10:06:08.337  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:08.337  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:08.337  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:08.337  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:08.337  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:08.337  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:08.337  5347  5394 I jxcore-log: 
,09-15 10:06:08.709  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:09.710  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:10.712  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:06:13.391  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:13.391  5347  5394 I jxcore-log: 
09-15 10:06:13.392  5347  5394 I jxcore-log: websocket error
09-15 10:06:13.392  5347  5394 I jxcore-log: 
09-15 10:06:13.392  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:13.392  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:13.392  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:13.392  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:13.392  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:13.392  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:13.392  5347  5394 I jxcore-log: 
,09-15 10:06:15.713  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:16.714  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:17.716  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:18.416  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:18.416  5347  5394 I jxcore-log: 
09-15 10:06:18.417  5347  5394 I jxcore-log: websocket error
09-15 10:06:18.417  5347  5394 I jxcore-log: 
09-15 10:06:18.417  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:18.417  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:18.417  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:18.417  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:18.417  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:18.417  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:18.417  5347  5394 I jxcore-log: 
,09-15 10:06:18.717  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:19.719  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:20.720  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:06:23.439  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:23.439  5347  5394 I jxcore-log: 
09-15 10:06:23.439  5347  5394 I jxcore-log: websocket error
09-15 10:06:23.439  5347  5394 I jxcore-log: 
09-15 10:06:23.440  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:23.440  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:23.440  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:23.440  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:23.440  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:23.440  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:23.440  5347  5394 I jxcore-log: 
,09-15 10:06:28.462  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:28.462  5347  5394 I jxcore-log: 
09-15 10:06:28.463  5347  5394 I jxcore-log: websocket error
09-15 10:06:28.463  5347  5394 I jxcore-log: 
,09-15 10:06:28.463  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:28.463  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:28.463  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:28.463  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:28.463  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:28.463  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:28.463  5347  5394 I jxcore-log: 
,09-15 10:06:30.722  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:31.723  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:32.725  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:33.486  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:33.486  5347  5394 I jxcore-log: 
09-15 10:06:33.487  5347  5394 I jxcore-log: websocket error
09-15 10:06:33.487  5347  5394 I jxcore-log: 
,09-15 10:06:33.487  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:33.487  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:33.487  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:33.487  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:33.487  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:33.487  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:33.487  5347  5394 I jxcore-log: 
,09-15 10:06:33.726  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:34.729  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:35.730  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:06:38.518  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:38.518  5347  5394 I jxcore-log: 
,09-15 10:06:38.519  5347  5394 I jxcore-log: websocket error
09-15 10:06:38.519  5347  5394 I jxcore-log: 
09-15 10:06:38.519  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:38.519  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:38.519  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:38.519  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:38.519  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:38.519  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:38.519  5347  5394 I jxcore-log: 
,09-15 10:06:43.544  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:43.544  5347  5394 I jxcore-log: 
09-15 10:06:43.545  5347  5394 I jxcore-log: websocket error
09-15 10:06:43.545  5347  5394 I jxcore-log: 
,09-15 10:06:43.545  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:43.545  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:43.545  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:43.545  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:43.545  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:43.545  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:43.545  5347  5394 I jxcore-log: 
,09-15 10:06:48.568  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:48.568  5347  5394 I jxcore-log: 
09-15 10:06:48.568  5347  5394 I jxcore-log: websocket error
09-15 10:06:48.568  5347  5394 I jxcore-log: 
09-15 10:06:48.569  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:48.569  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:48.569  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:48.569  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:48.569  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:48.569  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:48.569  5347  5394 I jxcore-log: 
,09-15 10:06:50.731  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:51.733  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:52.735  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:53.594  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:53.594  5347  5394 I jxcore-log: 
09-15 10:06:53.594  5347  5394 I jxcore-log: websocket error
09-15 10:06:53.594  5347  5394 I jxcore-log: 
09-15 10:06:53.595  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:53.595  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:53.595  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:53.595  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:53.595  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:53.595  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:53.595  5347  5394 I jxcore-log: 
,09-15 10:06:53.736  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:54.738  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:06:55.739  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:06:58.620  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:06:58.620  5347  5394 I jxcore-log: 
09-15 10:06:58.621  5347  5394 I jxcore-log: websocket error
09-15 10:06:58.621  5347  5394 I jxcore-log: 
,09-15 10:06:58.621  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:06:58.621  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:06:58.621  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:06:58.621  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:58.621  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:06:58.621  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:06:58.621  5347  5394 I jxcore-log: 
,09-15 10:07:03.645  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:03.645  5347  5394 I jxcore-log: 
09-15 10:07:03.645  5347  5394 I jxcore-log: websocket error
09-15 10:07:03.645  5347  5394 I jxcore-log: 
09-15 10:07:03.646  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:03.646  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:03.646  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:03.646  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:03.646  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:03.646  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:03.646  5347  5394 I jxcore-log: 
,09-15 10:07:08.671  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:08.671  5347  5394 I jxcore-log: 
,09-15 10:07:08.671  5347  5394 I jxcore-log: websocket error
09-15 10:07:08.671  5347  5394 I jxcore-log: 
09-15 10:07:08.672  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:08.672  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:08.672  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:08.672  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:08.672  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:08.672  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:08.672  5347  5394 I jxcore-log: 
,09-15 10:07:13.696  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:13.696  5347  5394 I jxcore-log: 
09-15 10:07:13.697  5347  5394 I jxcore-log: websocket error
09-15 10:07:13.697  5347  5394 I jxcore-log: 
09-15 10:07:13.697  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:13.697  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:13.697  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:13.697  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:13.697  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:13.697  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:13.697  5347  5394 I jxcore-log: 
,09-15 10:07:15.740  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:16.742  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:17.743  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:18.721  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:18.721  5347  5394 I jxcore-log: 
09-15 10:07:18.722  5347  5394 I jxcore-log: websocket error
09-15 10:07:18.722  5347  5394 I jxcore-log: 
09-15 10:07:18.722  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:18.722  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:18.722  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:18.722  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:18.722  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:18.722  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:18.722  5347  5394 I jxcore-log: 
,09-15 10:07:18.744  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:19.746  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:20.747  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:07:23.746  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:23.746  5347  5394 I jxcore-log: 
,09-15 10:07:23.747  5347  5394 I jxcore-log: websocket error
09-15 10:07:23.747  5347  5394 I jxcore-log: 
09-15 10:07:23.747  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:23.747  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:23.747  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:23.747  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:23.747  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:23.747  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:23.747  5347  5394 I jxcore-log: 
,09-15 10:07:28.770  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:28.770  5347  5394 I jxcore-log: 
,09-15 10:07:28.771  5347  5394 I jxcore-log: websocket error
09-15 10:07:28.771  5347  5394 I jxcore-log: 
09-15 10:07:28.771  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:28.771  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:28.771  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:28.771  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:28.771  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:28.771  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:28.771  5347  5394 I jxcore-log: 
,09-15 10:07:33.795  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:33.795  5347  5394 I jxcore-log: 
,09-15 10:07:33.796  5347  5394 I jxcore-log: websocket error
09-15 10:07:33.796  5347  5394 I jxcore-log: 
09-15 10:07:33.796  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:33.796  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:33.796  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:33.796  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:33.796  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:33.796  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:33.796  5347  5394 I jxcore-log: 
,09-15 10:07:38.820  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:38.820  5347  5394 I jxcore-log: 
09-15 10:07:38.821  5347  5394 I jxcore-log: websocket error
09-15 10:07:38.821  5347  5394 I jxcore-log: 
,09-15 10:07:38.821  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:38.821  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:38.821  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:38.821  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:38.821  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:38.821  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:38.821  5347  5394 I jxcore-log: 
,09-15 10:07:43.846  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:43.846  5347  5394 I jxcore-log: 
,09-15 10:07:43.846  5347  5394 I jxcore-log: websocket error
09-15 10:07:43.846  5347  5394 I jxcore-log: 
09-15 10:07:43.846  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:43.846  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:43.846  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:43.846  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:43.846  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:43.846  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:43.846  5347  5394 I jxcore-log: 
,09-15 10:07:45.748  5708  5708 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 10:07:45.748  5708  5708 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:07:48.872  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:48.872  5347  5394 I jxcore-log: 
,09-15 10:07:48.873  5347  5394 I jxcore-log: websocket error
09-15 10:07:48.873  5347  5394 I jxcore-log: 
09-15 10:07:48.873  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:48.873  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:48.873  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:48.873  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:48.873  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:48.873  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:48.873  5347  5394 I jxcore-log: 
,09-15 10:07:50.749  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:51.751  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:52.752  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:53.754  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:53.898  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:53.898  5347  5394 I jxcore-log: 
09-15 10:07:53.898  5347  5394 I jxcore-log: websocket error
09-15 10:07:53.898  5347  5394 I jxcore-log: 
09-15 10:07:53.899  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:53.899  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:53.899  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:53.899  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:53.899  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:53.899  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:53.899  5347  5394 I jxcore-log: 
,09-15 10:07:54.755  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:07:55.756  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:07:58.922  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:07:58.922  5347  5394 I jxcore-log: 
,09-15 10:07:58.922  5347  5394 I jxcore-log: websocket error
09-15 10:07:58.922  5347  5394 I jxcore-log: 
09-15 10:07:58.923  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:07:58.923  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:07:58.923  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:07:58.923  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:58.923  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:07:58.923  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:07:58.923  5347  5394 I jxcore-log: 
,09-15 10:08:00.759  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:01.760  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:02.761  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:03.763  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:03.946  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:03.946  5347  5394 I jxcore-log: 
,09-15 10:08:03.946  5347  5394 I jxcore-log: websocket error
09-15 10:08:03.946  5347  5394 I jxcore-log: 
09-15 10:08:03.947  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:03.947  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:03.947  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:03.947  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:03.947  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:03.947  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:03.947  5347  5394 I jxcore-log: 
,09-15 10:08:04.764  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:05.765  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:08:08.985  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:08.985  5347  5394 I jxcore-log: 
09-15 10:08:08.985  5347  5394 I jxcore-log: websocket error
09-15 10:08:08.985  5347  5394 I jxcore-log: 
,09-15 10:08:08.985  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:08.985  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:08.985  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:08.985  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:08.985  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:08.985  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:08.985  5347  5394 I jxcore-log: 
,09-15 10:08:14.014  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:14.014  5347  5394 I jxcore-log: 
,09-15 10:08:14.014  5347  5394 I jxcore-log: websocket error
09-15 10:08:14.014  5347  5394 I jxcore-log: 
,09-15 10:08:14.014  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:14.014  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:14.014  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:14.014  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:14.014  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:14.014  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:14.014  5347  5394 I jxcore-log: 
,09-15 10:08:15.766  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:16.767  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:17.768  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:18.770  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:19.037  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:19.037  5347  5394 I jxcore-log: 
,09-15 10:08:19.037  5347  5394 I jxcore-log: websocket error
09-15 10:08:19.037  5347  5394 I jxcore-log: 
,09-15 10:08:19.038  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:19.038  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:19.038  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:19.038  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:19.038  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:19.038  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:19.038  5347  5394 I jxcore-log: 
,09-15 10:08:19.771  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:20.772  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:08:24.060  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:24.060  5347  5394 I jxcore-log: 
,09-15 10:08:24.061  5347  5394 I jxcore-log: websocket error
09-15 10:08:24.061  5347  5394 I jxcore-log: 
,09-15 10:08:24.062  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:24.062  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:24.062  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:24.062  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:24.062  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:24.062  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:24.062  5347  5394 I jxcore-log: 
,09-15 10:08:29.085  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:29.085  5347  5394 I jxcore-log: 
,09-15 10:08:29.086  5347  5394 I jxcore-log: websocket error
09-15 10:08:29.086  5347  5394 I jxcore-log: 
09-15 10:08:29.086  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:29.086  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:29.086  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:29.086  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:29.086  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:29.086  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:29.086  5347  5394 I jxcore-log: 
,09-15 10:08:34.111  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:34.111  5347  5394 I jxcore-log: 
,09-15 10:08:34.112  5347  5394 I jxcore-log: websocket error
09-15 10:08:34.112  5347  5394 I jxcore-log: 
,09-15 10:08:34.112  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:34.112  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:34.112  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:34.112  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:34.112  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:34.112  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:34.112  5347  5394 I jxcore-log: 
,09-15 10:08:35.773  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:36.774  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:37.775  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:38.776  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:39.135  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:39.135  5347  5394 I jxcore-log: 
,09-15 10:08:39.135  5347  5394 I jxcore-log: websocket error
09-15 10:08:39.135  5347  5394 I jxcore-log: 
09-15 10:08:39.135  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:39.135  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:39.135  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:39.135  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:39.135  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:39.135  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:39.135  5347  5394 I jxcore-log: 
,09-15 10:08:39.778  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:08:40.778  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:08:44.159  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:44.159  5347  5394 I jxcore-log: 
,09-15 10:08:44.159  5347  5394 I jxcore-log: websocket error
09-15 10:08:44.159  5347  5394 I jxcore-log: 
09-15 10:08:44.160  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:44.160  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:44.160  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:44.160  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:44.160  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:44.160  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:44.160  5347  5394 I jxcore-log: 
,09-15 10:08:49.186  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:49.186  5347  5394 I jxcore-log: 
,09-15 10:08:49.186  5347  5394 I jxcore-log: websocket error
09-15 10:08:49.186  5347  5394 I jxcore-log: 
09-15 10:08:49.186  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:49.186  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:49.186  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:49.186  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:49.186  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:49.186  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:49.186  5347  5394 I jxcore-log: 
,09-15 10:08:54.225  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:54.225  5347  5394 I jxcore-log: 
,09-15 10:08:54.225  5347  5394 I jxcore-log: websocket error
09-15 10:08:54.225  5347  5394 I jxcore-log: 
09-15 10:08:54.225  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:54.225  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:54.225  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:54.225  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:54.225  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:54.225  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:54.225  5347  5394 I jxcore-log: 
,09-15 10:08:59.246  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:08:59.246  5347  5394 I jxcore-log: 
09-15 10:08:59.247  5347  5394 I jxcore-log: websocket error
09-15 10:08:59.247  5347  5394 I jxcore-log: 
,09-15 10:08:59.247  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:08:59.247  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:08:59.247  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:08:59.247  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:59.247  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:08:59.247  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:08:59.247  5347  5394 I jxcore-log: 
,09-15 10:09:00.780  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:01.781  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:02.782  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:03.783  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:04.270  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:04.270  5347  5394 I jxcore-log: 
,09-15 10:09:04.271  5347  5394 I jxcore-log: websocket error
09-15 10:09:04.271  5347  5394 I jxcore-log: 
09-15 10:09:04.271  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:04.271  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:04.271  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:04.271  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:04.271  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:04.271  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:04.271  5347  5394 I jxcore-log: 
,09-15 10:09:04.786  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:05.786  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:09:09.297  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:09.297  5347  5394 I jxcore-log: 
,09-15 10:09:09.297  5347  5394 I jxcore-log: websocket error
09-15 10:09:09.297  5347  5394 I jxcore-log: 
09-15 10:09:09.298  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:09.298  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:09.298  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:09.298  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:09.298  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:09.298  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:09.298  5347  5394 I jxcore-log: 
,09-15 10:09:14.321  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:14.321  5347  5394 I jxcore-log: 
09-15 10:09:14.322  5347  5394 I jxcore-log: websocket error
09-15 10:09:14.322  5347  5394 I jxcore-log: 
,09-15 10:09:14.322  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:14.322  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:14.322  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:14.322  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:14.322  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:14.322  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:14.322  5347  5394 I jxcore-log: 
,09-15 10:09:19.349  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:19.349  5347  5394 I jxcore-log: 
09-15 10:09:19.349  5347  5394 I jxcore-log: websocket error
09-15 10:09:19.349  5347  5394 I jxcore-log: 
,09-15 10:09:19.349  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:19.349  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:19.349  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:19.349  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:19.349  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:19.349  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:19.349  5347  5394 I jxcore-log: 
,09-15 10:09:24.374  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:24.374  5347  5394 I jxcore-log: 
09-15 10:09:24.374  5347  5394 I jxcore-log: websocket error
09-15 10:09:24.374  5347  5394 I jxcore-log: 
,09-15 10:09:24.375  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:24.375  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:24.375  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:24.375  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:24.375  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:24.375  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:24.375  5347  5394 I jxcore-log: 
,09-15 10:09:29.398  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:29.398  5347  5394 I jxcore-log: 
09-15 10:09:29.398  5347  5394 I jxcore-log: websocket error
09-15 10:09:29.398  5347  5394 I jxcore-log: 
09-15 10:09:29.398  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:29.398  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:29.398  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:29.398  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:29.398  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:29.398  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:29.398  5347  5394 I jxcore-log: 
,09-15 10:09:30.787  5708  5708 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 10:09:30.788  5708  5708 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:09:34.427  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:34.427  5347  5394 I jxcore-log: 
09-15 10:09:34.427  5347  5394 I jxcore-log: websocket error
09-15 10:09:34.427  5347  5394 I jxcore-log: 
09-15 10:09:34.428  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:34.428  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:34.428  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:34.428  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:34.428  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:34.428  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:34.428  5347  5394 I jxcore-log: 
,09-15 10:09:39.452  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:39.452  5347  5394 I jxcore-log: 
09-15 10:09:39.453  5347  5394 I jxcore-log: websocket error
09-15 10:09:39.453  5347  5394 I jxcore-log: 
,09-15 10:09:39.453  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:39.453  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:39.453  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:39.453  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:39.453  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:39.453  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:39.453  5347  5394 I jxcore-log: 
,09-15 10:09:40.789  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:41.790  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:42.792  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:43.794  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:44.478  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:44.478  5347  5394 I jxcore-log: 
,09-15 10:09:44.479  5347  5394 I jxcore-log: websocket error
09-15 10:09:44.479  5347  5394 I jxcore-log: 
09-15 10:09:44.479  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:44.479  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:44.479  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:44.479  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:44.479  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:44.479  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:44.479  5347  5394 I jxcore-log: 
,09-15 10:09:44.795  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:45.795  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:09:49.503  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:49.503  5347  5394 I jxcore-log: 
,09-15 10:09:49.504  5347  5394 I jxcore-log: websocket error
09-15 10:09:49.504  5347  5394 I jxcore-log: 
09-15 10:09:49.504  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:49.504  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:49.504  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:49.504  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:49.504  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:49.504  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:49.504  5347  5394 I jxcore-log: 
,09-15 10:09:50.797  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:51.798  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:52.799  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:53.801  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:54.528  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:54.528  5347  5394 I jxcore-log: 
09-15 10:09:54.528  5347  5394 I jxcore-log: websocket error
09-15 10:09:54.528  5347  5394 I jxcore-log: 
09-15 10:09:54.529  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:54.529  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:54.529  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:54.529  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:54.529  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:54.529  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:54.529  5347  5394 I jxcore-log: 
,09-15 10:09:54.802  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:09:55.803  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:09:59.555  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:09:59.555  5347  5394 I jxcore-log: 
09-15 10:09:59.555  5347  5394 I jxcore-log: websocket error
09-15 10:09:59.555  5347  5394 I jxcore-log: 
,09-15 10:09:59.555  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:09:59.555  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:09:59.555  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:09:59.555  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:59.555  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:09:59.555  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:09:59.555  5347  5394 I jxcore-log: 
,09-15 10:10:04.581  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:04.581  5347  5394 I jxcore-log: 
,09-15 10:10:04.582  5347  5394 I jxcore-log: websocket error
09-15 10:10:04.582  5347  5394 I jxcore-log: 
09-15 10:10:04.582  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:04.582  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:04.582  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:04.582  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:04.582  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:04.582  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:04.582  5347  5394 I jxcore-log: 
,09-15 10:10:05.804  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:06.806  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:07.808  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:08.809  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:09.603  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:09.603  5347  5394 I jxcore-log: 
09-15 10:10:09.603  5347  5394 I jxcore-log: websocket error
09-15 10:10:09.603  5347  5394 I jxcore-log: 
09-15 10:10:09.604  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:09.604  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:09.604  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:09.604  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:09.604  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:09.604  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:09.604  5347  5394 I jxcore-log: 
,09-15 10:10:09.810  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:10.811  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:10:14.628  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:14.628  5347  5394 I jxcore-log: 
09-15 10:10:14.629  5347  5394 I jxcore-log: websocket error
09-15 10:10:14.629  5347  5394 I jxcore-log: 
09-15 10:10:14.629  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:14.629  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:14.629  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:14.629  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:14.629  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:14.629  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:14.629  5347  5394 I jxcore-log: 
,09-15 10:10:19.652  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:19.652  5347  5394 I jxcore-log: 
,09-15 10:10:19.652  5347  5394 I jxcore-log: websocket error
09-15 10:10:19.652  5347  5394 I jxcore-log: 
09-15 10:10:19.652  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:19.652  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:19.652  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:19.652  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:19.652  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:19.652  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:19.652  5347  5394 I jxcore-log: 
,09-15 10:10:24.676  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:24.676  5347  5394 I jxcore-log: 
,09-15 10:10:24.677  5347  5394 I jxcore-log: websocket error
09-15 10:10:24.677  5347  5394 I jxcore-log: 
09-15 10:10:24.677  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:24.677  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:24.677  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:24.677  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:24.677  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:24.677  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:24.677  5347  5394 I jxcore-log: 
,09-15 10:10:25.813  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:26.814  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:27.816  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:28.817  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:29.702  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:29.702  5347  5394 I jxcore-log: 
,09-15 10:10:29.702  5347  5394 I jxcore-log: websocket error
09-15 10:10:29.702  5347  5394 I jxcore-log: 
,09-15 10:10:29.702  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:29.702  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:29.702  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:29.702  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:29.702  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:29.702  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:29.702  5347  5394 I jxcore-log: 
,09-15 10:10:29.819  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:30.819  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:10:34.725  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:34.725  5347  5394 I jxcore-log: 
,09-15 10:10:34.726  5347  5394 I jxcore-log: websocket error
09-15 10:10:34.726  5347  5394 I jxcore-log: 
09-15 10:10:34.726  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:34.726  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:34.726  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:34.726  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:34.726  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:34.726  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:34.726  5347  5394 I jxcore-log: 
,09-15 10:10:39.754  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:39.754  5347  5394 I jxcore-log: 
09-15 10:10:39.755  5347  5394 I jxcore-log: websocket error
09-15 10:10:39.755  5347  5394 I jxcore-log: 
09-15 10:10:39.755  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:39.755  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:39.755  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:39.755  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:39.755  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:39.755  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:39.755  5347  5394 I jxcore-log: 
,09-15 10:10:44.778  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:44.778  5347  5394 I jxcore-log: 
,09-15 10:10:44.778  5347  5394 I jxcore-log: websocket error
09-15 10:10:44.778  5347  5394 I jxcore-log: 
09-15 10:10:44.779  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:44.779  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:44.779  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:44.779  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:44.779  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:44.779  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:44.779  5347  5394 I jxcore-log: 
,09-15 10:10:49.803  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:49.803  5347  5394 I jxcore-log: 
09-15 10:10:49.803  5347  5394 I jxcore-log: websocket error
09-15 10:10:49.803  5347  5394 I jxcore-log: 
09-15 10:10:49.804  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:49.804  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:49.804  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:49.804  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:49.804  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:49.804  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:49.804  5347  5394 I jxcore-log: 
,09-15 10:10:50.821  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:51.823  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:52.824  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:53.826  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:54.826  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:54.826  5347  5394 I jxcore-log: 
,09-15 10:10:54.826  5347  5394 I jxcore-log: websocket error
09-15 10:10:54.826  5347  5394 I jxcore-log: 
09-15 10:10:54.827  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:54.827  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:54.827  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:54.827  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:54.827  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:54.827  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:54.827  5347  5394 I jxcore-log: 
09-15 10:10:54.827  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:10:55.828  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:10:59.850  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:10:59.850  5347  5394 I jxcore-log: 
,09-15 10:10:59.851  5347  5394 I jxcore-log: websocket error
09-15 10:10:59.851  5347  5394 I jxcore-log: 
09-15 10:10:59.851  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:10:59.851  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:10:59.851  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:10:59.851  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:59.851  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:10:59.851  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:10:59.851  5347  5394 I jxcore-log: 
,09-15 10:11:04.875  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:04.875  5347  5394 I jxcore-log: 
,09-15 10:11:04.876  5347  5394 I jxcore-log: websocket error
09-15 10:11:04.876  5347  5394 I jxcore-log: 
09-15 10:11:04.876  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:04.876  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:04.876  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:04.876  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:04.876  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:04.876  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:04.876  5347  5394 I jxcore-log: 
,09-15 10:11:09.898  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:09.898  5347  5394 I jxcore-log: 
09-15 10:11:09.899  5347  5394 I jxcore-log: websocket error
09-15 10:11:09.899  5347  5394 I jxcore-log: 
09-15 10:11:09.899  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:09.899  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:09.899  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:09.899  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:09.899  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:09.899  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:09.899  5347  5394 I jxcore-log: 
,09-15 10:11:14.922  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:14.922  5347  5394 I jxcore-log: 
09-15 10:11:14.923  5347  5394 I jxcore-log: websocket error
09-15 10:11:14.923  5347  5394 I jxcore-log: 
09-15 10:11:14.923  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:14.923  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:14.923  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:14.923  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:14.923  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:14.923  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:14.923  5347  5394 I jxcore-log: 
,09-15 10:11:19.947  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:19.947  5347  5394 I jxcore-log: 
,09-15 10:11:19.947  5347  5394 I jxcore-log: websocket error
09-15 10:11:19.947  5347  5394 I jxcore-log: 
09-15 10:11:19.947  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:19.947  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:19.947  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:19.947  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:19.947  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:19.947  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:19.947  5347  5394 I jxcore-log: 
,09-15 10:11:20.828  5708  5708 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 10:11:20.829  5708  5708 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:11:24.972  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:24.972  5347  5394 I jxcore-log: 
,09-15 10:11:24.972  5347  5394 I jxcore-log: websocket error
09-15 10:11:24.972  5347  5394 I jxcore-log: 
09-15 10:11:24.973  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:24.973  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:24.973  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:24.973  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:24.973  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:24.973  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:24.973  5347  5394 I jxcore-log: 
,09-15 10:11:29.997  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:29.997  5347  5394 I jxcore-log: 
,09-15 10:11:29.997  5347  5394 I jxcore-log: websocket error
09-15 10:11:29.997  5347  5394 I jxcore-log: 
,09-15 10:11:29.998  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:29.998  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:29.998  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:29.998  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:29.998  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:29.998  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:29.998  5347  5394 I jxcore-log: 
,09-15 10:11:35.021  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:35.021  5347  5394 I jxcore-log: 
09-15 10:11:35.021  5347  5394 I jxcore-log: websocket error
09-15 10:11:35.021  5347  5394 I jxcore-log: 
09-15 10:11:35.022  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:35.022  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:35.022  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:35.022  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:35.022  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:35.022  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:35.022  5347  5394 I jxcore-log: 
,09-15 10:11:35.830  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:36.831  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:37.832  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:38.833  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:39.834  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:40.045  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:40.045  5347  5394 I jxcore-log: 
,09-15 10:11:40.045  5347  5394 I jxcore-log: websocket error
09-15 10:11:40.045  5347  5394 I jxcore-log: 
09-15 10:11:40.046  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:40.046  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:40.046  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:40.046  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:40.046  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:40.046  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:40.046  5347  5394 I jxcore-log: 
,09-15 10:11:40.835  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:11:45.068  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:45.068  5347  5394 I jxcore-log: 
09-15 10:11:45.068  5347  5394 I jxcore-log: websocket error
09-15 10:11:45.068  5347  5394 I jxcore-log: 
,09-15 10:11:45.069  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:45.069  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:45.069  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:45.069  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:45.069  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:45.069  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:45.069  5347  5394 I jxcore-log: 
,09-15 10:11:45.836  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:46.837  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:47.838  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:48.840  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:49.841  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:11:50.092  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:50.092  5347  5394 I jxcore-log: 
09-15 10:11:50.092  5347  5394 I jxcore-log: websocket error
09-15 10:11:50.092  5347  5394 I jxcore-log: 
09-15 10:11:50.093  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:50.093  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:50.093  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:50.093  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:50.093  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:50.093  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:50.093  5347  5394 I jxcore-log: 
,09-15 10:11:50.841  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:11:55.123  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:11:55.123  5347  5394 I jxcore-log: 
,09-15 10:11:55.124  5347  5394 I jxcore-log: websocket error
09-15 10:11:55.124  5347  5394 I jxcore-log: 
,09-15 10:11:55.124  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:11:55.124  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:11:55.124  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:11:55.124  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:55.124  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:11:55.124  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:11:55.124  5347  5394 I jxcore-log: 
,09-15 10:12:00.149  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:00.149  5347  5394 I jxcore-log: 
09-15 10:12:00.150  5347  5394 I jxcore-log: websocket error
09-15 10:12:00.150  5347  5394 I jxcore-log: 
,09-15 10:12:00.150  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:00.150  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:00.150  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:00.150  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:00.150  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:00.150  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:00.150  5347  5394 I jxcore-log: 
,09-15 10:12:00.843  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:01.844  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:02.845  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:03.846  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:04.848  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:05.172  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:05.172  5347  5394 I jxcore-log: 
09-15 10:12:05.172  5347  5394 I jxcore-log: websocket error
09-15 10:12:05.172  5347  5394 I jxcore-log: 
09-15 10:12:05.172  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:05.172  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:05.172  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:05.172  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:05.172  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:05.172  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:05.172  5347  5394 I jxcore-log: 
,09-15 10:12:05.849  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:12:10.197  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:10.197  5347  5394 I jxcore-log: 
,09-15 10:12:10.198  5347  5394 I jxcore-log: websocket error
09-15 10:12:10.198  5347  5394 I jxcore-log: 
,09-15 10:12:10.198  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:10.198  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:10.198  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:10.198  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:10.198  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:10.198  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:10.198  5347  5394 I jxcore-log: 
,09-15 10:12:15.224  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:15.224  5347  5394 I jxcore-log: 
09-15 10:12:15.224  5347  5394 I jxcore-log: websocket error
09-15 10:12:15.224  5347  5394 I jxcore-log: 
09-15 10:12:15.225  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:15.225  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:15.225  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:15.225  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:15.225  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:15.225  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:15.225  5347  5394 I jxcore-log: 
,09-15 10:12:20.248  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:20.248  5347  5394 I jxcore-log: 
,09-15 10:12:20.249  5347  5394 I jxcore-log: websocket error
09-15 10:12:20.249  5347  5394 I jxcore-log: 
09-15 10:12:20.249  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:20.249  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:20.249  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:20.249  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:20.249  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:20.249  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:20.249  5347  5394 I jxcore-log: 
,09-15 10:12:20.850  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:21.851  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:22.852  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:23.853  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:24.855  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:25.270  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:25.270  5347  5394 I jxcore-log: 
,09-15 10:12:25.271  5347  5394 I jxcore-log: websocket error
09-15 10:12:25.271  5347  5394 I jxcore-log: 
09-15 10:12:25.271  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:25.271  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:25.271  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:25.271  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:25.271  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:25.271  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:25.271  5347  5394 I jxcore-log: 
,09-15 10:12:25.856  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:12:30.295  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:30.295  5347  5394 I jxcore-log: 
,09-15 10:12:30.296  5347  5394 I jxcore-log: websocket error
09-15 10:12:30.296  5347  5394 I jxcore-log: 
09-15 10:12:30.296  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:30.296  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:30.296  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:30.296  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:30.296  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:30.296  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:30.296  5347  5394 I jxcore-log: 
,09-15 10:12:35.319  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:35.319  5347  5394 I jxcore-log: 
,09-15 10:12:35.319  5347  5394 I jxcore-log: websocket error
09-15 10:12:35.319  5347  5394 I jxcore-log: 
09-15 10:12:35.320  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:35.320  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:35.320  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:35.320  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:35.320  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:35.320  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:35.320  5347  5394 I jxcore-log: 
,09-15 10:12:40.343  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:40.343  5347  5394 I jxcore-log: 
,09-15 10:12:40.344  5347  5394 I jxcore-log: websocket error
09-15 10:12:40.344  5347  5394 I jxcore-log: 
09-15 10:12:40.346  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:40.346  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:40.346  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:40.346  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:40.346  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:40.346  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:40.346  5347  5394 I jxcore-log: 
,09-15 10:12:45.368  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:45.368  5347  5394 I jxcore-log: 
09-15 10:12:45.368  5347  5394 I jxcore-log: websocket error
09-15 10:12:45.368  5347  5394 I jxcore-log: 
09-15 10:12:45.369  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:45.369  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:45.369  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:45.369  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:45.369  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:45.369  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:45.369  5347  5394 I jxcore-log: 
,09-15 10:12:45.857  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:46.858  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:47.859  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:48.861  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:49.862  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:12:50.403  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:50.403  5347  5394 I jxcore-log: 
,09-15 10:12:50.404  5347  5394 I jxcore-log: websocket error
09-15 10:12:50.404  5347  5394 I jxcore-log: 
09-15 10:12:50.404  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:50.404  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:50.404  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:50.404  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:50.404  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:50.404  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:50.404  5347  5394 I jxcore-log: 
,09-15 10:12:50.863  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:12:55.426  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:12:55.426  5347  5394 I jxcore-log: 
,09-15 10:12:55.426  5347  5394 I jxcore-log: websocket error
09-15 10:12:55.426  5347  5394 I jxcore-log: 
09-15 10:12:55.426  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:12:55.426  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:12:55.426  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:12:55.426  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:55.426  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:12:55.426  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:12:55.426  5347  5394 I jxcore-log: 
,09-15 10:13:00.450  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:00.450  5347  5394 I jxcore-log: 
,09-15 10:13:00.451  5347  5394 I jxcore-log: websocket error
09-15 10:13:00.451  5347  5394 I jxcore-log: 
09-15 10:13:00.451  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:00.451  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:00.451  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:00.451  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:00.451  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:00.451  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:00.451  5347  5394 I jxcore-log: 
,09-15 10:13:05.475  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:05.475  5347  5394 I jxcore-log: 
,09-15 10:13:05.476  5347  5394 I jxcore-log: websocket error
09-15 10:13:05.476  5347  5394 I jxcore-log: 
09-15 10:13:05.476  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:05.476  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:05.476  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:05.476  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:05.476  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:05.476  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:05.476  5347  5394 I jxcore-log: 
,09-15 10:13:10.498  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:10.498  5347  5394 I jxcore-log: 
,09-15 10:13:10.499  5347  5394 I jxcore-log: websocket error
09-15 10:13:10.499  5347  5394 I jxcore-log: 
09-15 10:13:10.499  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:10.499  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:10.499  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:10.499  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:10.499  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:10.499  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:10.499  5347  5394 I jxcore-log: 
,09-15 10:13:15.522  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:15.522  5347  5394 I jxcore-log: 
,09-15 10:13:15.522  5347  5394 I jxcore-log: websocket error
09-15 10:13:15.522  5347  5394 I jxcore-log: 
09-15 10:13:15.523  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:15.523  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:15.523  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:15.523  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:15.523  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:15.523  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:15.523  5347  5394 I jxcore-log: 
,09-15 10:13:15.864  5708  5708 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 10:13:15.864  5708  5708 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:13:20.546  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:20.546  5347  5394 I jxcore-log: 
,09-15 10:13:20.547  5347  5394 I jxcore-log: websocket error
09-15 10:13:20.547  5347  5394 I jxcore-log: 
09-15 10:13:20.547  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:20.547  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:20.547  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:20.547  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:20.547  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:20.547  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:20.547  5347  5394 I jxcore-log: 
,09-15 10:13:25.572  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:25.572  5347  5394 I jxcore-log: 
09-15 10:13:25.572  5347  5394 I jxcore-log: websocket error
09-15 10:13:25.572  5347  5394 I jxcore-log: 
09-15 10:13:25.573  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:25.573  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:25.573  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:25.573  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:25.573  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:25.573  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:25.573  5347  5394 I jxcore-log: 
,09-15 10:13:30.597  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:30.597  5347  5394 I jxcore-log: 
,09-15 10:13:30.598  5347  5394 I jxcore-log: websocket error
09-15 10:13:30.598  5347  5394 I jxcore-log: 
09-15 10:13:30.598  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:30.598  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:30.598  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:30.598  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:30.598  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:30.598  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:30.598  5347  5394 I jxcore-log: 
,09-15 10:13:35.621  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:35.621  5347  5394 I jxcore-log: 
,09-15 10:13:35.621  5347  5394 I jxcore-log: websocket error
09-15 10:13:35.621  5347  5394 I jxcore-log: 
09-15 10:13:35.622  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:35.622  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:35.622  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:35.622  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:35.622  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:35.622  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:35.622  5347  5394 I jxcore-log: 
,09-15 10:13:35.865  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:36.866  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:37.868  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:38.869  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:39.871  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:40.645  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:40.645  5347  5394 I jxcore-log: 
,09-15 10:13:40.645  5347  5394 I jxcore-log: websocket error
09-15 10:13:40.645  5347  5394 I jxcore-log: 
,09-15 10:13:40.646  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:40.646  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:40.646  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:40.646  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:40.646  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:40.646  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:40.646  5347  5394 I jxcore-log: 
,09-15 10:13:40.871  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:13:45.668  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:45.668  5347  5394 I jxcore-log: 
,09-15 10:13:45.669  5347  5394 I jxcore-log: websocket error
09-15 10:13:45.669  5347  5394 I jxcore-log: 
,09-15 10:13:45.669  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:45.669  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:45.669  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:45.669  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:45.669  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:45.669  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:45.669  5347  5394 I jxcore-log: 
,09-15 10:13:45.873  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:46.874  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:47.876  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:48.877  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:49.879  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:13:50.691  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:50.691  5347  5394 I jxcore-log: 
,09-15 10:13:50.692  5347  5394 I jxcore-log: websocket error
09-15 10:13:50.692  5347  5394 I jxcore-log: 
09-15 10:13:50.692  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:50.692  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:50.692  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:50.692  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:50.692  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:50.692  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:50.692  5347  5394 I jxcore-log: 
,09-15 10:13:50.879  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:13:55.715  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:13:55.715  5347  5394 I jxcore-log: 
,09-15 10:13:55.715  5347  5394 I jxcore-log: websocket error
09-15 10:13:55.715  5347  5394 I jxcore-log: 
09-15 10:13:55.716  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:13:55.716  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:13:55.716  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:13:55.716  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:55.716  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:13:55.716  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:13:55.716  5347  5394 I jxcore-log: 
,09-15 10:14:00.743  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:00.743  5347  5394 I jxcore-log: 
09-15 10:14:00.743  5347  5394 I jxcore-log: websocket error
09-15 10:14:00.743  5347  5394 I jxcore-log: 
09-15 10:14:00.744  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:00.744  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:00.744  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:00.744  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:00.744  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:00.744  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:00.744  5347  5394 I jxcore-log: 
,09-15 10:14:00.880  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:01.881  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:02.882  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:03.884  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:04.885  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:05.813  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:05.813  5347  5394 I jxcore-log: 
09-15 10:14:05.813  5347  5394 I jxcore-log: websocket error
09-15 10:14:05.813  5347  5394 I jxcore-log: 
09-15 10:14:05.813  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:05.813  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:05.813  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:05.813  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:05.813  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:05.813  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:05.813  5347  5394 I jxcore-log: 
,09-15 10:14:05.885  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:14:10.838  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:10.838  5347  5394 I jxcore-log: 
,09-15 10:14:10.838  5347  5394 I jxcore-log: websocket error
09-15 10:14:10.838  5347  5394 I jxcore-log: 
09-15 10:14:10.838  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:10.838  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:10.838  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:10.838  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:10.838  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:10.838  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:10.838  5347  5394 I jxcore-log: 
,09-15 10:14:15.863  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:15.863  5347  5394 I jxcore-log: 
09-15 10:14:15.863  5347  5394 I jxcore-log: websocket error
09-15 10:14:15.863  5347  5394 I jxcore-log: 
09-15 10:14:15.864  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:15.864  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:15.864  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:15.864  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:15.864  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:15.864  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:15.864  5347  5394 I jxcore-log: 
,09-15 10:14:20.886  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:20.890  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:20.890  5347  5394 I jxcore-log: 
09-15 10:14:20.890  5347  5394 I jxcore-log: websocket error
09-15 10:14:20.890  5347  5394 I jxcore-log: 
09-15 10:14:20.891  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:20.891  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:20.891  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:20.891  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:20.891  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:20.891  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:20.891  5347  5394 I jxcore-log: 
,09-15 10:14:21.887  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:22.888  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:23.890  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:24.891  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:25.892  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:14:25.913  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:25.913  5347  5394 I jxcore-log: 
,09-15 10:14:25.914  5347  5394 I jxcore-log: websocket error
09-15 10:14:25.914  5347  5394 I jxcore-log: 
09-15 10:14:25.914  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:25.914  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:25.914  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:25.914  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:25.914  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:25.914  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:25.914  5347  5394 I jxcore-log: 
,09-15 10:14:30.936  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:30.936  5347  5394 I jxcore-log: 
,09-15 10:14:30.937  5347  5394 I jxcore-log: websocket error
09-15 10:14:30.937  5347  5394 I jxcore-log: 
09-15 10:14:30.937  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:30.937  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:30.937  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:30.937  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:30.937  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:30.937  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:30.937  5347  5394 I jxcore-log: 
,09-15 10:14:35.960  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:35.960  5347  5394 I jxcore-log: 
,09-15 10:14:35.960  5347  5394 I jxcore-log: websocket error
09-15 10:14:35.960  5347  5394 I jxcore-log: 
09-15 10:14:35.961  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:35.961  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:35.961  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:35.961  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:35.961  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:35.961  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:35.961  5347  5394 I jxcore-log: 
,09-15 10:14:40.986  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:40.986  5347  5394 I jxcore-log: 
,09-15 10:14:40.987  5347  5394 I jxcore-log: websocket error
09-15 10:14:40.987  5347  5394 I jxcore-log: 
09-15 10:14:40.987  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:40.987  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:40.987  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:40.987  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:40.987  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:40.987  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:40.987  5347  5394 I jxcore-log: 
,09-15 10:14:45.893  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:46.012  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:46.012  5347  5394 I jxcore-log: 
,09-15 10:14:46.012  5347  5394 I jxcore-log: websocket error
09-15 10:14:46.012  5347  5394 I jxcore-log: 
,09-15 10:14:46.012  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:46.012  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:46.012  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:46.012  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:46.012  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:46.012  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:46.012  5347  5394 I jxcore-log: 
,09-15 10:14:46.895  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:47.896  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:48.898  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:49.899  5708  5708 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:14:50.900  5708  5708 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:14:51.035  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:51.035  5347  5394 I jxcore-log: 
09-15 10:14:51.036  5347  5394 I jxcore-log: websocket error
09-15 10:14:51.036  5347  5394 I jxcore-log: 
09-15 10:14:51.036  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:51.036  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:51.036  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:51.036  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:51.036  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:51.036  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:51.036  5347  5394 I jxcore-log: 
,09-15 10:14:56.058  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:14:56.058  5347  5394 I jxcore-log: 
09-15 10:14:56.058  5347  5394 I jxcore-log: websocket error
09-15 10:14:56.058  5347  5394 I jxcore-log: 
09-15 10:14:56.058  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:14:56.058  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:14:56.058  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:14:56.058  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:56.058  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:14:56.058  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:14:56.058  5347  5394 I jxcore-log: 
,09-15 10:15:01.083  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:01.083  5347  5394 I jxcore-log: 
,09-15 10:15:01.083  5347  5394 I jxcore-log: websocket error
09-15 10:15:01.083  5347  5394 I jxcore-log: 
09-15 10:15:01.083  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:01.083  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:01.083  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:01.083  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:01.083  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:01.083  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:01.083  5347  5394 I jxcore-log: 
,09-15 10:15:06.106  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:06.106  5347  5394 I jxcore-log: 
,09-15 10:15:06.106  5347  5394 I jxcore-log: websocket error
09-15 10:15:06.106  5347  5394 I jxcore-log: 
09-15 10:15:06.106  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:06.106  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:06.106  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:06.106  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:06.106  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:06.106  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:06.106  5347  5394 I jxcore-log: 
,09-15 10:15:11.140  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:11.140  5347  5394 I jxcore-log: 
,09-15 10:15:11.140  5347  5394 I jxcore-log: websocket error
09-15 10:15:11.140  5347  5394 I jxcore-log: 
,09-15 10:15:11.140  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:11.140  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:11.140  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:11.140  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:11.140  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:11.140  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:11.140  5347  5394 I jxcore-log: 
,09-15 10:15:15.900  5708  5708 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 10:15:15.901  5708  5708 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:15:16.164  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:16.164  5347  5394 I jxcore-log: 
,09-15 10:15:16.165  5347  5394 I jxcore-log: websocket error
09-15 10:15:16.165  5347  5394 I jxcore-log: 
,09-15 10:15:16.165  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:16.165  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:16.165  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:16.165  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:16.165  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:16.165  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:16.165  5347  5394 I jxcore-log: 
,09-15 10:15:21.187  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:21.187  5347  5394 I jxcore-log: 
,09-15 10:15:21.188  5347  5394 I jxcore-log: websocket error
09-15 10:15:21.188  5347  5394 I jxcore-log: 
09-15 10:15:21.188  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:21.188  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:21.188  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:21.188  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:21.188  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:21.188  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:21.188  5347  5394 I jxcore-log: 
,09-15 10:15:26.212  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:26.212  5347  5394 I jxcore-log: 
,09-15 10:15:26.212  5347  5394 I jxcore-log: websocket error
09-15 10:15:26.212  5347  5394 I jxcore-log: 
,09-15 10:15:26.212  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:26.212  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:26.212  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:26.212  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:26.212  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:26.212  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:26.212  5347  5394 I jxcore-log: 
,09-15 10:15:31.238  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:31.238  5347  5394 I jxcore-log: 
,09-15 10:15:31.239  5347  5394 I jxcore-log: websocket error
09-15 10:15:31.239  5347  5394 I jxcore-log: 
09-15 10:15:31.239  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:31.239  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:31.239  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:31.239  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:31.239  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:31.239  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:31.239  5347  5394 I jxcore-log: 
,09-15 10:15:36.263  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:36.263  5347  5394 I jxcore-log: 
,09-15 10:15:36.263  5347  5394 I jxcore-log: websocket error
09-15 10:15:36.263  5347  5394 I jxcore-log: 
09-15 10:15:36.264  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:36.264  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:36.264  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:36.264  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:36.264  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:36.264  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:36.264  5347  5394 I jxcore-log: 
,09-15 10:15:40.911  5708  5710 E QC-QMI  : qmi_client [5708] 1d: failed to locate client data
,09-15 10:15:40.914   520   520 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-15 10:15:40.915   520   520 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-15 10:15:40.921  5708  5708 I Atfwd_Daemon: Stop the daemon....
,09-15 10:15:40.967  5722  5722 I libmdmdetect: ESOC framework not supported
,09-15 10:15:40.966  5722  5722 W ATFWD-daemon: type=1400 audit(0.0:121): avc: denied { read write } for name="diag" dev="tmpfs" ino=11712 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-15 10:15:40.968  5722  5722 I libmdmdetect: Found internal modem: modem
,09-15 10:15:40.969  5722  5722 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-15 10:15:40.977  5722  5722 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-15 10:15:40.978  5722  5722 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-15 10:15:40.979  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:41.286  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:41.286  5347  5394 I jxcore-log: 
,09-15 10:15:41.286  5347  5394 I jxcore-log: websocket error
09-15 10:15:41.286  5347  5394 I jxcore-log: 
09-15 10:15:41.287  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:41.287  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:41.287  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:41.287  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:41.287  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:41.287  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:41.287  5347  5394 I jxcore-log: 
,09-15 10:15:41.982  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:42.983  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:43.985  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:44.986  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:45.987  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:15:46.311  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:46.311  5347  5394 I jxcore-log: 
09-15 10:15:46.312  5347  5394 I jxcore-log: websocket error
09-15 10:15:46.312  5347  5394 I jxcore-log: 
09-15 10:15:46.312  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:46.312  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:46.312  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:46.312  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:46.312  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:46.312  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:46.312  5347  5394 I jxcore-log: 
,09-15 10:15:50.989  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:51.335  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:51.335  5347  5394 I jxcore-log: 
,09-15 10:15:51.335  5347  5394 I jxcore-log: websocket error
09-15 10:15:51.335  5347  5394 I jxcore-log: 
09-15 10:15:51.336  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:51.336  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:51.336  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:51.336  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:51.336  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:51.336  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:51.336  5347  5394 I jxcore-log: 
,09-15 10:15:51.990  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:52.991  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:53.992  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:54.993  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:15:55.994  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:15:56.358  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:15:56.358  5347  5394 I jxcore-log: 
,09-15 10:15:56.359  5347  5394 I jxcore-log: websocket error
09-15 10:15:56.359  5347  5394 I jxcore-log: 
09-15 10:15:56.359  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:15:56.359  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:15:56.359  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:15:56.359  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:56.359  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:15:56.359  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:15:56.359  5347  5394 I jxcore-log: 
,09-15 10:16:01.382  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:01.382  5347  5394 I jxcore-log: 
09-15 10:16:01.382  5347  5394 I jxcore-log: websocket error
09-15 10:16:01.382  5347  5394 I jxcore-log: 
09-15 10:16:01.382  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:01.382  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:01.382  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:01.382  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:01.382  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:01.382  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:01.382  5347  5394 I jxcore-log: 
,09-15 10:16:05.995  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:06.407  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:06.407  5347  5394 I jxcore-log: 
,09-15 10:16:06.407  5347  5394 I jxcore-log: websocket error
09-15 10:16:06.407  5347  5394 I jxcore-log: 
09-15 10:16:06.408  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:06.408  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:06.408  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:06.408  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:06.408  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:06.408  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:06.408  5347  5394 I jxcore-log: 
,09-15 10:16:06.997  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:07.999  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:09.000  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:10.001  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:11.002  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:16:11.432  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:11.432  5347  5394 I jxcore-log: 
,09-15 10:16:11.432  5347  5394 I jxcore-log: websocket error
09-15 10:16:11.432  5347  5394 I jxcore-log: 
,09-15 10:16:11.433  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:11.433  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:11.433  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:11.433  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:11.433  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:11.433  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:11.433  5347  5394 I jxcore-log: 
,09-15 10:16:16.455  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:16.455  5347  5394 I jxcore-log: 
09-15 10:16:16.455  5347  5394 I jxcore-log: websocket error
09-15 10:16:16.455  5347  5394 I jxcore-log: 
09-15 10:16:16.455  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:16.455  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:16.455  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:16.455  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:16.455  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:16.455  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:16.455  5347  5394 I jxcore-log: 
,09-15 10:16:21.478  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:21.478  5347  5394 I jxcore-log: 
,09-15 10:16:21.479  5347  5394 I jxcore-log: websocket error
09-15 10:16:21.479  5347  5394 I jxcore-log: 
09-15 10:16:21.479  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:21.479  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:21.479  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:21.479  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:21.479  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:21.479  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:21.479  5347  5394 I jxcore-log: 
,09-15 10:16:26.003  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:26.502  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:26.502  5347  5394 I jxcore-log: 
09-15 10:16:26.503  5347  5394 I jxcore-log: websocket error
09-15 10:16:26.503  5347  5394 I jxcore-log: 
,09-15 10:16:26.503  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:26.503  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:26.503  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:26.503  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:26.503  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:26.503  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:26.503  5347  5394 I jxcore-log: 
,09-15 10:16:27.006  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:28.007  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:29.009  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:30.010  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:31.011  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:16:31.527  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:31.527  5347  5394 I jxcore-log: 
,09-15 10:16:31.527  5347  5394 I jxcore-log: websocket error
09-15 10:16:31.527  5347  5394 I jxcore-log: 
,09-15 10:16:31.528  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:31.528  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:31.528  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:31.528  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:31.528  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:31.528  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:31.528  5347  5394 I jxcore-log: 
,09-15 10:16:35.472   927   939 I UsageStatsService: User[0] Flushing usage stats to disk
,09-15 10:16:36.551  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:36.551  5347  5394 I jxcore-log: 
09-15 10:16:36.551  5347  5394 I jxcore-log: websocket error
09-15 10:16:36.551  5347  5394 I jxcore-log: 
09-15 10:16:36.552  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:36.552  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:36.552  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:36.552  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:36.552  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:36.552  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:36.552  5347  5394 I jxcore-log: 
,09-15 10:16:41.574  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:41.574  5347  5394 I jxcore-log: 
,09-15 10:16:41.575  5347  5394 I jxcore-log: websocket error
09-15 10:16:41.575  5347  5394 I jxcore-log: 
09-15 10:16:41.575  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:41.575  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:41.575  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:41.575  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:41.575  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:41.575  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:41.575  5347  5394 I jxcore-log: 
,09-15 10:16:46.598  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:46.598  5347  5394 I jxcore-log: 
,09-15 10:16:46.599  5347  5394 I jxcore-log: websocket error
09-15 10:16:46.599  5347  5394 I jxcore-log: 
09-15 10:16:46.599  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:46.599  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:46.599  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:46.599  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:46.599  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:46.599  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:46.599  5347  5394 I jxcore-log: 
,09-15 10:16:51.012  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:51.622  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:51.622  5347  5394 I jxcore-log: 
,09-15 10:16:51.622  5347  5394 I jxcore-log: websocket error
09-15 10:16:51.622  5347  5394 I jxcore-log: 
09-15 10:16:51.623  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:51.623  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:51.623  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:51.623  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:51.623  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:51.623  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:51.623  5347  5394 I jxcore-log: 
,09-15 10:16:52.013  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:53.015  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:54.016  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:55.018  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:16:56.019  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:16:56.645  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:16:56.645  5347  5394 I jxcore-log: 
09-15 10:16:56.645  5347  5394 I jxcore-log: websocket error
09-15 10:16:56.645  5347  5394 I jxcore-log: 
09-15 10:16:56.646  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:16:56.646  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:16:56.646  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:16:56.646  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:56.646  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:16:56.646  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:16:56.646  5347  5394 I jxcore-log: 
,09-15 10:17:01.670  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:01.670  5347  5394 I jxcore-log: 
09-15 10:17:01.670  5347  5394 I jxcore-log: websocket error
09-15 10:17:01.670  5347  5394 I jxcore-log: 
09-15 10:17:01.671  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:01.671  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:01.671  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:01.671  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:01.671  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:01.671  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:01.671  5347  5394 I jxcore-log: 
,09-15 10:17:06.697  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:06.697  5347  5394 I jxcore-log: 
09-15 10:17:06.698  5347  5394 I jxcore-log: websocket error
09-15 10:17:06.698  5347  5394 I jxcore-log: 
09-15 10:17:06.698  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:06.698  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:06.698  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:06.698  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:06.698  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:06.698  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:06.698  5347  5394 I jxcore-log: 
,09-15 10:17:11.720  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:11.720  5347  5394 I jxcore-log: 
,09-15 10:17:11.720  5347  5394 I jxcore-log: websocket error
09-15 10:17:11.720  5347  5394 I jxcore-log: 
,09-15 10:17:11.721  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:11.721  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:11.721  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:11.721  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:11.721  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:11.721  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:11.721  5347  5394 I jxcore-log: 
,09-15 10:17:16.749  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:16.749  5347  5394 I jxcore-log: 
09-15 10:17:16.749  5347  5394 I jxcore-log: websocket error
09-15 10:17:16.749  5347  5394 I jxcore-log: 
,09-15 10:17:16.750  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:16.750  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:16.750  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:16.750  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:16.750  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:16.750  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:16.750  5347  5394 I jxcore-log: 
,09-15 10:17:21.019  5722  5722 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 10:17:21.019  5722  5722 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:17:21.772  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:21.772  5347  5394 I jxcore-log: 
,09-15 10:17:21.772  5347  5394 I jxcore-log: websocket error
09-15 10:17:21.772  5347  5394 I jxcore-log: 
,09-15 10:17:21.773  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:21.773  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:21.773  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:21.773  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:21.773  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:21.773  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:21.773  5347  5394 I jxcore-log: 
,09-15 10:17:26.020  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:26.797  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:26.797  5347  5394 I jxcore-log: 
09-15 10:17:26.798  5347  5394 I jxcore-log: websocket error
09-15 10:17:26.798  5347  5394 I jxcore-log: 
09-15 10:17:26.798  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:26.798  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:26.798  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:26.798  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:26.798  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:26.798  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:26.798  5347  5394 I jxcore-log: 
,09-15 10:17:27.022  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:28.023  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:29.024  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:30.025  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:31.026  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:17:31.831  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:31.831  5347  5394 I jxcore-log: 
,09-15 10:17:31.832  5347  5394 I jxcore-log: websocket error
09-15 10:17:31.832  5347  5394 I jxcore-log: 
,09-15 10:17:31.832  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:31.832  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:31.832  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:31.832  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:31.832  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:31.832  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:31.832  5347  5394 I jxcore-log: 
,09-15 10:17:36.027  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:36.872  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:36.872  5347  5394 I jxcore-log: 
,09-15 10:17:36.872  5347  5394 I jxcore-log: websocket error
09-15 10:17:36.872  5347  5394 I jxcore-log: 
09-15 10:17:36.873  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:36.873  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:36.873  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:36.873  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:36.873  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:36.873  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:36.873  5347  5394 I jxcore-log: 
,09-15 10:17:37.028  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:38.029  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:39.030  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:40.032  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:41.033  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:17:41.894  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:41.894  5347  5394 I jxcore-log: 
,09-15 10:17:41.895  5347  5394 I jxcore-log: websocket error
09-15 10:17:41.895  5347  5394 I jxcore-log: 
09-15 10:17:41.895  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:41.895  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:41.895  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:41.895  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:41.895  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:41.895  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:41.895  5347  5394 I jxcore-log: 
,09-15 10:17:46.919  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:46.919  5347  5394 I jxcore-log: 
09-15 10:17:46.920  5347  5394 I jxcore-log: websocket error
09-15 10:17:46.920  5347  5394 I jxcore-log: 
09-15 10:17:46.920  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:46.920  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:46.920  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:46.920  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:46.920  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:46.920  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:46.920  5347  5394 I jxcore-log: 
,09-15 10:17:51.034  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:51.945  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:51.945  5347  5394 I jxcore-log: 
,09-15 10:17:51.945  5347  5394 I jxcore-log: websocket error
09-15 10:17:51.945  5347  5394 I jxcore-log: 
09-15 10:17:51.945  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:51.945  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:51.945  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:51.945  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:51.945  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:51.945  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:51.945  5347  5394 I jxcore-log: 
,09-15 10:17:52.035  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:53.036  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:54.038  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:55.039  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:17:56.040  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:17:56.968  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:17:56.968  5347  5394 I jxcore-log: 
,09-15 10:17:56.968  5347  5394 I jxcore-log: websocket error
09-15 10:17:56.968  5347  5394 I jxcore-log: 
,09-15 10:17:56.968  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:17:56.968  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:17:56.968  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:17:56.968  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:56.968  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:17:56.968  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:17:56.968  5347  5394 I jxcore-log: 
,09-15 10:18:01.994  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:01.994  5347  5394 I jxcore-log: 
09-15 10:18:01.995  5347  5394 I jxcore-log: websocket error
09-15 10:18:01.995  5347  5394 I jxcore-log: 
09-15 10:18:01.995  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:01.995  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:01.995  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:01.995  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:01.995  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:01.995  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:01.995  5347  5394 I jxcore-log: 
,09-15 10:18:07.019  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:07.019  5347  5394 I jxcore-log: 
,09-15 10:18:07.019  5347  5394 I jxcore-log: websocket error
09-15 10:18:07.019  5347  5394 I jxcore-log: 
09-15 10:18:07.019  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:07.019  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:07.019  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:07.019  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:07.019  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:07.019  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:07.019  5347  5394 I jxcore-log: 
,09-15 10:18:11.041  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:12.042  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:12.043  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:12.043  5347  5394 I jxcore-log: 
,09-15 10:18:12.043  5347  5394 I jxcore-log: websocket error
09-15 10:18:12.043  5347  5394 I jxcore-log: 
,09-15 10:18:12.045  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:12.045  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:12.045  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:12.045  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:12.045  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:12.045  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:12.045  5347  5394 I jxcore-log: 
,09-15 10:18:13.044  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:14.045  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:15.047  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:16.048  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:18:17.068  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:17.068  5347  5394 I jxcore-log: 
09-15 10:18:17.068  5347  5394 I jxcore-log: websocket error
09-15 10:18:17.068  5347  5394 I jxcore-log: 
09-15 10:18:17.069  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:17.069  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:17.069  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:17.069  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:17.069  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:17.069  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:17.069  5347  5394 I jxcore-log: 
,09-15 10:18:22.090  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:22.090  5347  5394 I jxcore-log: 
09-15 10:18:22.091  5347  5394 I jxcore-log: websocket error
09-15 10:18:22.091  5347  5394 I jxcore-log: 
,09-15 10:18:22.091  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:22.091  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:22.091  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:22.091  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:22.091  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:22.091  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:22.091  5347  5394 I jxcore-log: 
,09-15 10:18:27.114  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:27.114  5347  5394 I jxcore-log: 
09-15 10:18:27.115  5347  5394 I jxcore-log: websocket error
09-15 10:18:27.115  5347  5394 I jxcore-log: 
09-15 10:18:27.115  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:27.115  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:27.115  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:27.115  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:27.115  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:27.115  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:27.115  5347  5394 I jxcore-log: 
,09-15 10:18:32.140  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:32.140  5347  5394 I jxcore-log: 
09-15 10:18:32.140  5347  5394 I jxcore-log: websocket error
09-15 10:18:32.140  5347  5394 I jxcore-log: 
09-15 10:18:32.140  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:32.140  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:32.140  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:32.140  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:32.140  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:32.140  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:32.140  5347  5394 I jxcore-log: 
,09-15 10:18:36.049  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:37.051  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:37.163  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:37.163  5347  5394 I jxcore-log: 
,09-15 10:18:37.164  5347  5394 I jxcore-log: websocket error
09-15 10:18:37.164  5347  5394 I jxcore-log: 
,09-15 10:18:37.164  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:37.164  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:37.164  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:37.164  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:37.164  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:37.164  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:37.164  5347  5394 I jxcore-log: 
,09-15 10:18:38.052  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:39.054  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:40.055  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:18:41.056  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:18:42.188  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:42.188  5347  5394 I jxcore-log: 
09-15 10:18:42.188  5347  5394 I jxcore-log: websocket error
09-15 10:18:42.188  5347  5394 I jxcore-log: 
09-15 10:18:42.188  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:42.188  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:42.188  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:42.188  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:42.188  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:42.188  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:42.188  5347  5394 I jxcore-log: 
,09-15 10:18:47.212  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:47.212  5347  5394 I jxcore-log: 
,09-15 10:18:47.212  5347  5394 I jxcore-log: websocket error
09-15 10:18:47.212  5347  5394 I jxcore-log: 
09-15 10:18:47.212  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:47.212  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:47.212  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:47.212  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:47.212  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:47.212  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:47.212  5347  5394 I jxcore-log: 
,09-15 10:18:52.253  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:52.253  5347  5394 I jxcore-log: 
09-15 10:18:52.253  5347  5394 I jxcore-log: websocket error
09-15 10:18:52.253  5347  5394 I jxcore-log: 
09-15 10:18:52.253  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:52.253  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:52.253  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:52.253  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:52.253  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:52.253  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:52.253  5347  5394 I jxcore-log: 
,09-15 10:18:57.281  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:18:57.281  5347  5394 I jxcore-log: 
09-15 10:18:57.281  5347  5394 I jxcore-log: websocket error
09-15 10:18:57.281  5347  5394 I jxcore-log: 
09-15 10:18:57.282  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:18:57.282  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:18:57.282  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:18:57.282  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:57.282  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:18:57.282  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:18:57.282  5347  5394 I jxcore-log: 
,09-15 10:19:02.308  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:02.308  5347  5394 I jxcore-log: 
,09-15 10:19:02.308  5347  5394 I jxcore-log: websocket error
09-15 10:19:02.308  5347  5394 I jxcore-log: 
09-15 10:19:02.308  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:02.308  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:02.308  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:02.308  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:02.308  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:02.308  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:02.308  5347  5394 I jxcore-log: 
,09-15 10:19:06.057  5722  5722 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 10:19:06.057  5722  5722 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:19:07.331  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:07.331  5347  5394 I jxcore-log: 
09-15 10:19:07.332  5347  5394 I jxcore-log: websocket error
09-15 10:19:07.332  5347  5394 I jxcore-log: 
,09-15 10:19:07.332  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:07.332  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:07.332  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:07.332  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:07.332  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:07.332  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:07.332  5347  5394 I jxcore-log: 
,09-15 10:19:12.356  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:12.356  5347  5394 I jxcore-log: 
,09-15 10:19:12.357  5347  5394 I jxcore-log: websocket error
09-15 10:19:12.357  5347  5394 I jxcore-log: 
09-15 10:19:12.357  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:12.357  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:12.357  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:12.357  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:12.357  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:12.357  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:12.357  5347  5394 I jxcore-log: 
,09-15 10:19:16.058  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:17.059  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:17.383  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:17.383  5347  5394 I jxcore-log: 
,09-15 10:19:17.384  5347  5394 I jxcore-log: websocket error
09-15 10:19:17.384  5347  5394 I jxcore-log: 
,09-15 10:19:17.384  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:17.384  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:17.384  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:17.384  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:17.384  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:17.384  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:17.384  5347  5394 I jxcore-log: 
,09-15 10:19:18.061  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:19.062  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:20.063  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:21.064  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:19:22.407  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:22.407  5347  5394 I jxcore-log: 
09-15 10:19:22.408  5347  5394 I jxcore-log: websocket error
09-15 10:19:22.408  5347  5394 I jxcore-log: 
09-15 10:19:22.408  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:22.408  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:22.408  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:22.408  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:22.408  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:22.408  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:22.408  5347  5394 I jxcore-log: 
,09-15 10:19:26.065  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:27.066  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:27.433  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:27.433  5347  5394 I jxcore-log: 
,09-15 10:19:27.433  5347  5394 I jxcore-log: websocket error
09-15 10:19:27.433  5347  5394 I jxcore-log: 
09-15 10:19:27.433  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:27.433  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:27.433  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:27.433  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:27.433  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:27.433  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:27.433  5347  5394 I jxcore-log: 
,09-15 10:19:28.067  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:29.069  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:30.070  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:31.071  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:19:32.460  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:32.460  5347  5394 I jxcore-log: 
09-15 10:19:32.460  5347  5394 I jxcore-log: websocket error
09-15 10:19:32.460  5347  5394 I jxcore-log: 
,09-15 10:19:32.460  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:32.460  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:32.460  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:32.460  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:32.460  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:32.460  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:32.460  5347  5394 I jxcore-log: 
,09-15 10:19:37.484  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:37.484  5347  5394 I jxcore-log: 
,09-15 10:19:37.484  5347  5394 I jxcore-log: websocket error
09-15 10:19:37.484  5347  5394 I jxcore-log: 
09-15 10:19:37.485  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:37.485  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:37.485  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:37.485  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:37.485  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:37.485  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:37.485  5347  5394 I jxcore-log: 
,09-15 10:19:41.072  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:42.074  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:42.512  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:42.512  5347  5394 I jxcore-log: 
,09-15 10:19:42.513  5347  5394 I jxcore-log: websocket error
09-15 10:19:42.513  5347  5394 I jxcore-log: 
,09-15 10:19:42.513  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:42.513  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:42.513  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:42.513  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:42.513  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:42.513  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:42.513  5347  5394 I jxcore-log: 
,09-15 10:19:43.076  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:44.077  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:45.079  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:19:46.079  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:19:47.537  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:47.537  5347  5394 I jxcore-log: 
,09-15 10:19:47.538  5347  5394 I jxcore-log: websocket error
09-15 10:19:47.538  5347  5394 I jxcore-log: 
09-15 10:19:47.538  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:47.538  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:47.538  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:47.538  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:47.538  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:47.538  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:47.538  5347  5394 I jxcore-log: 
,09-15 10:19:52.562  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:52.562  5347  5394 I jxcore-log: 
,09-15 10:19:52.562  5347  5394 I jxcore-log: websocket error
09-15 10:19:52.562  5347  5394 I jxcore-log: 
,09-15 10:19:52.563  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:52.563  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:52.563  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:52.563  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:52.563  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:52.563  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:52.563  5347  5394 I jxcore-log: 
,09-15 10:19:57.587  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:19:57.587  5347  5394 I jxcore-log: 
09-15 10:19:57.588  5347  5394 I jxcore-log: websocket error
09-15 10:19:57.588  5347  5394 I jxcore-log: 
09-15 10:19:57.588  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:19:57.588  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:19:57.588  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:19:57.588  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:57.588  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:19:57.588  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:19:57.588  5347  5394 I jxcore-log: 
,09-15 10:20:01.080  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:02.082  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:02.613  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:02.613  5347  5394 I jxcore-log: 
,09-15 10:20:02.613  5347  5394 I jxcore-log: websocket error
09-15 10:20:02.613  5347  5394 I jxcore-log: 
09-15 10:20:02.614  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:02.614  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:02.614  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:02.614  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:02.614  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:02.614  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:02.614  5347  5394 I jxcore-log: 
,09-15 10:20:03.083  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:04.085  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:05.086  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:06.086  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:20:07.638  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:07.638  5347  5394 I jxcore-log: 
,09-15 10:20:07.639  5347  5394 I jxcore-log: websocket error
09-15 10:20:07.639  5347  5394 I jxcore-log: 
09-15 10:20:07.639  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:07.639  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:07.639  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:07.639  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:07.639  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:07.639  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:07.639  5347  5394 I jxcore-log: 
,09-15 10:20:12.662  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:12.662  5347  5394 I jxcore-log: 
,09-15 10:20:12.662  5347  5394 I jxcore-log: websocket error
09-15 10:20:12.662  5347  5394 I jxcore-log: 
09-15 10:20:12.663  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:12.663  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:12.663  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:12.663  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:12.663  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:12.663  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:12.663  5347  5394 I jxcore-log: 
,09-15 10:20:17.692  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:17.692  5347  5394 I jxcore-log: 
09-15 10:20:17.692  5347  5394 I jxcore-log: websocket error
09-15 10:20:17.692  5347  5394 I jxcore-log: 
09-15 10:20:17.692  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:17.692  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:17.692  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:17.692  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:17.692  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:17.692  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:17.692  5347  5394 I jxcore-log: 
,09-15 10:20:22.714  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:22.714  5347  5394 I jxcore-log: 
,09-15 10:20:22.714  5347  5394 I jxcore-log: websocket error
09-15 10:20:22.714  5347  5394 I jxcore-log: 
09-15 10:20:22.715  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:22.715  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:22.715  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:22.715  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:22.715  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:22.715  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:22.715  5347  5394 I jxcore-log: 
,09-15 10:20:26.087  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:27.089  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:27.739  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:27.739  5347  5394 I jxcore-log: 
,09-15 10:20:27.739  5347  5394 I jxcore-log: websocket error
09-15 10:20:27.739  5347  5394 I jxcore-log: 
,09-15 10:20:27.740  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:27.740  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:27.740  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:27.740  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:27.740  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:27.740  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:27.740  5347  5394 I jxcore-log: 
,09-15 10:20:28.090  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:29.091  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:30.092  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:20:31.093  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:20:32.763  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:32.763  5347  5394 I jxcore-log: 
,09-15 10:20:32.763  5347  5394 I jxcore-log: websocket error
09-15 10:20:32.763  5347  5394 I jxcore-log: 
,09-15 10:20:32.764  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:32.764  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:32.764  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:32.764  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:32.764  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:32.764  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:32.764  5347  5394 I jxcore-log: 
,09-15 10:20:37.788  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:37.788  5347  5394 I jxcore-log: 
09-15 10:20:37.788  5347  5394 I jxcore-log: websocket error
09-15 10:20:37.788  5347  5394 I jxcore-log: 
,09-15 10:20:37.788  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:37.788  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:37.788  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:37.788  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:37.788  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:37.788  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:37.788  5347  5394 I jxcore-log: 
,09-15 10:20:42.811  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:42.811  5347  5394 I jxcore-log: 
09-15 10:20:42.812  5347  5394 I jxcore-log: websocket error
09-15 10:20:42.812  5347  5394 I jxcore-log: 
,09-15 10:20:42.812  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:42.812  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:42.812  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:42.812  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:42.812  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:42.812  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:42.812  5347  5394 I jxcore-log: 
,09-15 10:20:47.837  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:47.837  5347  5394 I jxcore-log: 
,09-15 10:20:47.838  5347  5394 I jxcore-log: websocket error
09-15 10:20:47.838  5347  5394 I jxcore-log: 
09-15 10:20:47.838  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:47.838  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:47.838  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:47.838  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:47.838  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:47.838  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:47.838  5347  5394 I jxcore-log: 
,09-15 10:20:52.861  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:52.861  5347  5394 I jxcore-log: 
,09-15 10:20:52.862  5347  5394 I jxcore-log: websocket error
09-15 10:20:52.862  5347  5394 I jxcore-log: 
09-15 10:20:52.862  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:52.862  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:52.862  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:52.862  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:52.862  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:52.862  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:52.862  5347  5394 I jxcore-log: 
,09-15 10:20:56.094  5722  5722 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 10:20:56.094  5722  5722 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:20:57.885  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:20:57.885  5347  5394 I jxcore-log: 
09-15 10:20:57.886  5347  5394 I jxcore-log: websocket error
09-15 10:20:57.886  5347  5394 I jxcore-log: 
,09-15 10:20:57.886  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:20:57.886  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:20:57.886  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:20:57.886  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:57.886  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:20:57.886  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:20:57.886  5347  5394 I jxcore-log: 
,09-15 10:21:02.912  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:02.912  5347  5394 I jxcore-log: 
,09-15 10:21:02.913  5347  5394 I jxcore-log: websocket error
09-15 10:21:02.913  5347  5394 I jxcore-log: 
09-15 10:21:02.913  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:02.913  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:02.913  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:02.913  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:02.913  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:02.913  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:02.913  5347  5394 I jxcore-log: 
,09-15 10:21:07.936  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:07.936  5347  5394 I jxcore-log: 
,09-15 10:21:07.936  5347  5394 I jxcore-log: websocket error
09-15 10:21:07.936  5347  5394 I jxcore-log: 
09-15 10:21:07.937  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:07.937  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:07.937  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:07.937  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:07.937  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:07.937  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:07.937  5347  5394 I jxcore-log: 
,09-15 10:21:11.095  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:12.096  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:12.960  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:12.960  5347  5394 I jxcore-log: 
,09-15 10:21:12.961  5347  5394 I jxcore-log: websocket error
09-15 10:21:12.961  5347  5394 I jxcore-log: 
09-15 10:21:12.961  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:12.961  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:12.961  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:12.961  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:12.961  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:12.961  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:12.961  5347  5394 I jxcore-log: 
,09-15 10:21:13.098  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:14.099  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:15.100  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:16.101  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:21:17.985  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:17.985  5347  5394 I jxcore-log: 
,09-15 10:21:17.985  5347  5394 I jxcore-log: websocket error
09-15 10:21:17.985  5347  5394 I jxcore-log: 
09-15 10:21:17.986  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:17.986  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:17.986  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:17.986  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:17.986  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:17.986  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:17.986  5347  5394 I jxcore-log: 
,09-15 10:21:21.103  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:22.104  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:23.010  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:23.010  5347  5394 I jxcore-log: 
,09-15 10:21:23.010  5347  5394 I jxcore-log: websocket error
09-15 10:21:23.010  5347  5394 I jxcore-log: 
09-15 10:21:23.010  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:23.010  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:23.010  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:23.010  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:23.010  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:23.010  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:23.010  5347  5394 I jxcore-log: 
,09-15 10:21:23.105  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:24.107  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:25.108  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:26.108  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:21:28.036  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:28.036  5347  5394 I jxcore-log: 
09-15 10:21:28.036  5347  5394 I jxcore-log: websocket error
09-15 10:21:28.036  5347  5394 I jxcore-log: 
,09-15 10:21:28.037  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:28.037  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:28.037  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:28.037  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:28.037  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:28.037  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:28.037  5347  5394 I jxcore-log: 
,09-15 10:21:33.061  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:33.061  5347  5394 I jxcore-log: 
,09-15 10:21:33.062  5347  5394 I jxcore-log: websocket error
09-15 10:21:33.062  5347  5394 I jxcore-log: 
09-15 10:21:33.062  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:33.062  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:33.062  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:33.062  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:33.062  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:33.062  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:33.062  5347  5394 I jxcore-log: 
,09-15 10:21:36.110  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:37.111  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:38.083  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:38.083  5347  5394 I jxcore-log: 
09-15 10:21:38.084  5347  5394 I jxcore-log: websocket error
09-15 10:21:38.084  5347  5394 I jxcore-log: 
,09-15 10:21:38.084  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:38.084  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:38.084  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:38.084  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:38.084  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:38.084  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:38.084  5347  5394 I jxcore-log: 
,09-15 10:21:38.111  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:39.113  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:40.115  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:41.116  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:21:43.108  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:43.108  5347  5394 I jxcore-log: 
09-15 10:21:43.108  5347  5394 I jxcore-log: websocket error
09-15 10:21:43.108  5347  5394 I jxcore-log: 
,09-15 10:21:43.109  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:43.109  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:43.109  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:43.109  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:43.109  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:43.109  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:43.109  5347  5394 I jxcore-log: 
,09-15 10:21:48.131  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:48.131  5347  5394 I jxcore-log: 
09-15 10:21:48.132  5347  5394 I jxcore-log: websocket error
09-15 10:21:48.132  5347  5394 I jxcore-log: 
,09-15 10:21:48.132  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:48.132  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:48.132  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:48.132  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:48.132  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:48.132  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:48.132  5347  5394 I jxcore-log: 
,09-15 10:21:53.155  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:53.155  5347  5394 I jxcore-log: 
,09-15 10:21:53.156  5347  5394 I jxcore-log: websocket error
09-15 10:21:53.156  5347  5394 I jxcore-log: 
,09-15 10:21:53.156  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:53.156  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:53.156  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:53.156  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:53.156  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:53.156  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:53.156  5347  5394 I jxcore-log: 
,09-15 10:21:56.117  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:57.118  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:58.119  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:21:58.182  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:21:58.182  5347  5394 I jxcore-log: 
,09-15 10:21:58.183  5347  5394 I jxcore-log: websocket error
09-15 10:21:58.183  5347  5394 I jxcore-log: 
09-15 10:21:58.183  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:21:58.183  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:21:58.183  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:21:58.183  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:58.183  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:21:58.183  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:21:58.183  5347  5394 I jxcore-log: 
,09-15 10:21:59.121  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:22:00.122  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:22:01.122  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:22:03.206  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:03.206  5347  5394 I jxcore-log: 
,09-15 10:22:03.206  5347  5394 I jxcore-log: websocket error
09-15 10:22:03.206  5347  5394 I jxcore-log: 
,09-15 10:22:03.206  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:03.206  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:03.206  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:03.206  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:03.206  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:03.206  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:03.206  5347  5394 I jxcore-log: 
,09-15 10:22:08.233  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:08.233  5347  5394 I jxcore-log: 
09-15 10:22:08.233  5347  5394 I jxcore-log: websocket error
09-15 10:22:08.233  5347  5394 I jxcore-log: 
,09-15 10:22:08.234  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:08.234  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:08.234  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:08.234  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:08.234  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:08.234  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:08.234  5347  5394 I jxcore-log: 
,09-15 10:22:13.258  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:13.258  5347  5394 I jxcore-log: 
,09-15 10:22:13.258  5347  5394 I jxcore-log: websocket error
09-15 10:22:13.258  5347  5394 I jxcore-log: 
09-15 10:22:13.259  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:13.259  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:13.259  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:13.259  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:13.259  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:13.259  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:13.259  5347  5394 I jxcore-log: 
,09-15 10:22:18.283  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:18.283  5347  5394 I jxcore-log: 
,09-15 10:22:18.283  5347  5394 I jxcore-log: websocket error
09-15 10:22:18.283  5347  5394 I jxcore-log: 
09-15 10:22:18.283  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:18.283  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:18.283  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:18.283  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:18.283  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:18.283  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:18.283  5347  5394 I jxcore-log: 
,09-15 10:22:21.123  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:22:22.125  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:22:23.126  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:22:23.309  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:23.309  5347  5394 I jxcore-log: 
,09-15 10:22:23.310  5347  5394 I jxcore-log: websocket error
09-15 10:22:23.310  5347  5394 I jxcore-log: 
,09-15 10:22:23.310  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:23.310  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:23.310  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:23.310  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:23.310  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:23.310  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:23.310  5347  5394 I jxcore-log: 
,09-15 10:22:24.127  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:22:25.129  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:22:26.129  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:22:28.337  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:28.337  5347  5394 I jxcore-log: 
09-15 10:22:28.337  5347  5394 I jxcore-log: websocket error
09-15 10:22:28.337  5347  5394 I jxcore-log: 
09-15 10:22:28.338  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:28.338  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:28.338  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:28.338  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:28.338  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:28.338  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:28.338  5347  5394 I jxcore-log: 
,09-15 10:22:33.362  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:33.362  5347  5394 I jxcore-log: 
09-15 10:22:33.362  5347  5394 I jxcore-log: websocket error
09-15 10:22:33.362  5347  5394 I jxcore-log: 
09-15 10:22:33.363  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:33.363  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:33.363  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:33.363  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:33.363  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:33.363  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:33.363  5347  5394 I jxcore-log: 
,09-15 10:22:38.388  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:38.388  5347  5394 I jxcore-log: 
09-15 10:22:38.388  5347  5394 I jxcore-log: websocket error
09-15 10:22:38.388  5347  5394 I jxcore-log: 
,09-15 10:22:38.388  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:38.388  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:38.388  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:38.388  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:38.388  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:38.388  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:38.388  5347  5394 I jxcore-log: 
,09-15 10:22:43.414  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:43.414  5347  5394 I jxcore-log: 
,09-15 10:22:43.414  5347  5394 I jxcore-log: websocket error
09-15 10:22:43.414  5347  5394 I jxcore-log: 
09-15 10:22:43.415  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:43.415  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:43.415  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:43.415  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:43.415  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:43.415  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:43.415  5347  5394 I jxcore-log: 
,09-15 10:22:48.439  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:48.439  5347  5394 I jxcore-log: 
,09-15 10:22:48.440  5347  5394 I jxcore-log: websocket error
09-15 10:22:48.440  5347  5394 I jxcore-log: 
09-15 10:22:48.440  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:48.440  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:48.440  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:48.440  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:48.440  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:48.440  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:48.440  5347  5394 I jxcore-log: 
,09-15 10:22:51.130  5722  5722 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 10:22:51.130  5722  5722 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:22:53.463  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:53.463  5347  5394 I jxcore-log: 
09-15 10:22:53.464  5347  5394 I jxcore-log: websocket error
09-15 10:22:53.464  5347  5394 I jxcore-log: 
09-15 10:22:53.464  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:53.464  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:53.464  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:53.464  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:53.464  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:53.464  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:53.464  5347  5394 I jxcore-log: 
,09-15 10:22:58.489  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:22:58.489  5347  5394 I jxcore-log: 
09-15 10:22:58.489  5347  5394 I jxcore-log: websocket error
09-15 10:22:58.489  5347  5394 I jxcore-log: 
09-15 10:22:58.489  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:22:58.489  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:22:58.489  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:22:58.489  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:58.489  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:22:58.489  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:22:58.489  5347  5394 I jxcore-log: 
,09-15 10:23:03.516  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:03.516  5347  5394 I jxcore-log: 
,09-15 10:23:03.516  5347  5394 I jxcore-log: websocket error
09-15 10:23:03.516  5347  5394 I jxcore-log: 
,09-15 10:23:03.516  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:03.516  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:03.516  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:03.516  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:03.516  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:03.516  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:03.516  5347  5394 I jxcore-log: 
,09-15 10:23:08.538  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:08.538  5347  5394 I jxcore-log: 
,09-15 10:23:08.538  5347  5394 I jxcore-log: websocket error
09-15 10:23:08.538  5347  5394 I jxcore-log: 
09-15 10:23:08.539  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:08.539  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:08.539  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:08.539  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:08.539  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:08.539  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:08.539  5347  5394 I jxcore-log: 
,09-15 10:23:11.131  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:12.133  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:13.134  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:13.562  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:13.562  5347  5394 I jxcore-log: 
,09-15 10:23:13.563  5347  5394 I jxcore-log: websocket error
09-15 10:23:13.563  5347  5394 I jxcore-log: 
,09-15 10:23:13.563  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:13.563  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:13.563  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:13.563  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:13.563  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:13.563  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:13.563  5347  5394 I jxcore-log: 
,09-15 10:23:14.136  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:15.137  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:16.138  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:23:18.587  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:18.587  5347  5394 I jxcore-log: 
09-15 10:23:18.588  5347  5394 I jxcore-log: websocket error
09-15 10:23:18.588  5347  5394 I jxcore-log: 
09-15 10:23:18.588  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:18.588  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:18.588  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:18.588  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:18.588  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:18.588  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:18.588  5347  5394 I jxcore-log: 
,09-15 10:23:21.140  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:22.141  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:23.142  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:23.613  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:23.613  5347  5394 I jxcore-log: 
09-15 10:23:23.613  5347  5394 I jxcore-log: websocket error
09-15 10:23:23.613  5347  5394 I jxcore-log: 
09-15 10:23:23.613  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:23.613  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:23.613  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:23.613  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:23.613  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:23.613  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:23.613  5347  5394 I jxcore-log: 
,09-15 10:23:24.144  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:25.146  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:26.147  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:23:28.636  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:28.636  5347  5394 I jxcore-log: 
,09-15 10:23:28.636  5347  5394 I jxcore-log: websocket error
09-15 10:23:28.636  5347  5394 I jxcore-log: 
09-15 10:23:28.637  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:28.637  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:28.637  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:28.637  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:28.637  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:28.637  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:28.637  5347  5394 I jxcore-log: 
,09-15 10:23:33.662  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:33.662  5347  5394 I jxcore-log: 
09-15 10:23:33.662  5347  5394 I jxcore-log: websocket error
09-15 10:23:33.662  5347  5394 I jxcore-log: 
09-15 10:23:33.662  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:33.662  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:33.662  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:33.662  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:33.662  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:33.662  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:33.662  5347  5394 I jxcore-log: 
,09-15 10:23:36.148  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:37.149  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:38.150  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:38.693  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:38.693  5347  5394 I jxcore-log: 
09-15 10:23:38.693  5347  5394 I jxcore-log: websocket error
09-15 10:23:38.693  5347  5394 I jxcore-log: 
09-15 10:23:38.693  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:38.693  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:38.693  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:38.693  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:38.693  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:38.693  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:38.693  5347  5394 I jxcore-log: 
,09-15 10:23:39.151  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:40.153  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:41.154  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:23:43.715  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:43.715  5347  5394 I jxcore-log: 
,09-15 10:23:43.715  5347  5394 I jxcore-log: websocket error
09-15 10:23:43.715  5347  5394 I jxcore-log: 
09-15 10:23:43.716  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:43.716  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:43.716  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:43.716  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:43.716  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:43.716  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:43.716  5347  5394 I jxcore-log: 
,09-15 10:23:48.739  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:48.739  5347  5394 I jxcore-log: 
09-15 10:23:48.740  5347  5394 I jxcore-log: websocket error
09-15 10:23:48.740  5347  5394 I jxcore-log: 
09-15 10:23:48.740  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:48.740  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:48.740  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:48.740  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:48.740  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:48.740  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:48.740  5347  5394 I jxcore-log: 
,09-15 10:23:53.764  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:53.764  5347  5394 I jxcore-log: 
,09-15 10:23:53.764  5347  5394 I jxcore-log: websocket error
09-15 10:23:53.764  5347  5394 I jxcore-log: 
09-15 10:23:53.765  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:53.765  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:53.765  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:53.765  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:53.765  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:53.765  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:53.765  5347  5394 I jxcore-log: 
,09-15 10:23:56.161  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:57.162  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:58.163  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:23:58.789  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:23:58.789  5347  5394 I jxcore-log: 
09-15 10:23:58.789  5347  5394 I jxcore-log: websocket error
09-15 10:23:58.789  5347  5394 I jxcore-log: 
09-15 10:23:58.789  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:23:58.789  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:23:58.789  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:23:58.789  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:58.789  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:23:58.789  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:23:58.789  5347  5394 I jxcore-log: 
,09-15 10:23:59.165  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:24:00.166  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:24:01.166  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 10:24:03.814  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:03.814  5347  5394 I jxcore-log: 
09-15 10:24:03.814  5347  5394 I jxcore-log: websocket error
09-15 10:24:03.814  5347  5394 I jxcore-log: 
09-15 10:24:03.815  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:03.815  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:03.815  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:03.815  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:03.815  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:03.815  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:03.815  5347  5394 I jxcore-log: 
,09-15 10:24:08.841  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:08.841  5347  5394 I jxcore-log: 
,09-15 10:24:08.841  5347  5394 I jxcore-log: websocket error
09-15 10:24:08.841  5347  5394 I jxcore-log: 
,09-15 10:24:08.842  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:08.842  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:08.842  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:08.842  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:08.842  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:08.842  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:08.842  5347  5394 I jxcore-log: 
,09-15 10:24:13.866  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:13.866  5347  5394 I jxcore-log: 
09-15 10:24:13.867  5347  5394 I jxcore-log: websocket error
09-15 10:24:13.867  5347  5394 I jxcore-log: 
09-15 10:24:13.867  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:13.867  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:13.867  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:13.867  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:13.867  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:13.867  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:13.867  5347  5394 I jxcore-log: 
,09-15 10:24:18.891  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:18.891  5347  5394 I jxcore-log: 
09-15 10:24:18.892  5347  5394 I jxcore-log: websocket error
09-15 10:24:18.892  5347  5394 I jxcore-log: 
09-15 10:24:18.892  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:18.892  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:18.892  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:18.892  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:18.892  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:18.892  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:18.892  5347  5394 I jxcore-log: 
,09-15 10:24:21.168  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:24:22.169  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:24:23.170  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:24:23.917  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:23.917  5347  5394 I jxcore-log: 
,09-15 10:24:23.918  5347  5394 I jxcore-log: websocket error
09-15 10:24:23.918  5347  5394 I jxcore-log: 
,09-15 10:24:23.918  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:23.918  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:23.918  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:23.918  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:23.918  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:23.918  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:23.918  5347  5394 I jxcore-log: 
,09-15 10:24:24.171  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:24:25.173  5722  5722 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:24:26.174  5722  5722 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 10:24:28.999  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:28.999  5347  5394 I jxcore-log: 
,09-15 10:24:28.999  5347  5394 I jxcore-log: websocket error
09-15 10:24:28.999  5347  5394 I jxcore-log: 
,09-15 10:24:28.999  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:28.999  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:28.999  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:28.999  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:28.999  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:28.999  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:28.999  5347  5394 I jxcore-log: 
,09-15 10:24:34.037  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:34.037  5347  5394 I jxcore-log: 
,09-15 10:24:34.038  5347  5394 I jxcore-log: websocket error
09-15 10:24:34.038  5347  5394 I jxcore-log: 
09-15 10:24:34.038  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:34.038  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:34.038  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:34.038  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:34.038  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:34.038  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:34.038  5347  5394 I jxcore-log: 
,09-15 10:24:39.088  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:39.088  5347  5394 I jxcore-log: 
09-15 10:24:39.088  5347  5394 I jxcore-log: websocket error
09-15 10:24:39.088  5347  5394 I jxcore-log: 
09-15 10:24:39.089  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:39.089  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:39.089  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:39.089  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:39.089  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:39.089  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:39.089  5347  5394 I jxcore-log: 
,09-15 10:24:44.139  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:44.139  5347  5394 I jxcore-log: 
09-15 10:24:44.139  5347  5394 I jxcore-log: websocket error
09-15 10:24:44.139  5347  5394 I jxcore-log: 
09-15 10:24:44.139  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:44.139  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:44.139  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:44.139  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:44.139  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:44.139  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:44.139  5347  5394 I jxcore-log: 
,09-15 10:24:49.166  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:49.166  5347  5394 I jxcore-log: 
09-15 10:24:49.167  5347  5394 I jxcore-log: websocket error
09-15 10:24:49.167  5347  5394 I jxcore-log: 
09-15 10:24:49.167  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:49.167  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:49.167  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:49.167  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:49.167  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:49.167  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:49.167  5347  5394 I jxcore-log: 
,09-15 10:24:51.175  5722  5722 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 10:24:51.175  5722  5722 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:24:54.190  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:54.190  5347  5394 I jxcore-log: 
,09-15 10:24:54.191  5347  5394 I jxcore-log: websocket error
09-15 10:24:54.191  5347  5394 I jxcore-log: 
09-15 10:24:54.191  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:54.191  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:54.191  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:54.191  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:54.191  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:54.191  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:54.191  5347  5394 I jxcore-log: 
,09-15 10:24:59.219  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:24:59.219  5347  5394 I jxcore-log: 
09-15 10:24:59.219  5347  5394 I jxcore-log: websocket error
09-15 10:24:59.219  5347  5394 I jxcore-log: 
09-15 10:24:59.220  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:24:59.220  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:24:59.220  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:24:59.220  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:59.220  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:24:59.220  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:24:59.220  5347  5394 I jxcore-log: 
,09-15 10:25:04.248  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:25:04.248  5347  5394 I jxcore-log: 
,09-15 10:25:04.248  5347  5394 I jxcore-log: websocket error
09-15 10:25:04.248  5347  5394 I jxcore-log: 
09-15 10:25:04.249  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:25:04.249  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:25:04.249  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:25:04.249  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:25:04.249  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:25:04.249  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:25:04.249  5347  5394 I jxcore-log: 
,09-15 10:25:09.273  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:25:09.273  5347  5394 I jxcore-log: 
09-15 10:25:09.273  5347  5394 I jxcore-log: websocket error
09-15 10:25:09.273  5347  5394 I jxcore-log: 
09-15 10:25:09.273  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:25:09.273  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:25:09.273  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:25:09.273  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:25:09.273  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:25:09.273  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:25:09.273  5347  5394 I jxcore-log: 
,09-15 10:25:14.298  5347  5394 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 10:25:14.298  5347  5394 I jxcore-log: 
,09-15 10:25:14.298  5347  5394 I jxcore-log: websocket error
09-15 10:25:14.298  5347  5394 I jxcore-log: 
09-15 10:25:14.298  5347  5394 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 10:25:14.298  5347  5394 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 10:25:14.298  5347  5394 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 10:25:14.298  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:25:14.298  5347  5394 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 10:25:14.298  5347  5394 I jxcore-log: emit@events.js:82:1
09-15 10:25:14.298  5347  5394 I jxcore-log: 
,09-15 10:25:16.186  5722  5724 E QC-QMI  : qmi_client [5722] 1e: failed to locate client data
,09-15 10:25:16.190   520   520 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-15 10:25:16.191   520   520 E QC-QMI  : QMUX qmux_client_id=1e not found in qmux client list, unable to remove
09-15 10:25:16.194  5722  5722 I Atfwd_Daemon: Stop the daemon....
,09-15 10:25:16.236  5731  5731 I libmdmdetect: ESOC framework not supported
,09-15 10:25:16.236  5731  5731 I libmdmdetect: Found internal modem: modem
09-15 10:25:16.233  5731  5731 W ATFWD-daemon: type=1400 audit(0.0:122): avc: denied { read write } for name="diag" dev="tmpfs" ino=11712 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
09-15 10:25:16.237  5731  5731 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-15 10:25:16.243  5731  5731 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
09-15 10:25:16.243  5731  5731 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-15 10:25:16.244  5731  5731 I ServiceManager: Waiting for service AtCmdFwd...
,TIME-OUT KILL (timeout was 1400000ms),09-15 10:25:16.943  5735  5735 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 10:25:16.948  5735  5735 D AndroidRuntime: CheckJNI is OFF
09-15 10:25:16.972  5735  5735 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 10:25:17.002  5735  5735 I Radio-JNI: register_android_hardware_Radio DONE
09-15 10:25:17.018  5735  5735 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-15 10:25:17.028   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-15 10:25:17.029   927   940 I ActivityManager: Killing 5347:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
09-15 10:25:17.135   927  3283 D GraphicsStats: Buffer count: 2
09-15 10:25:17.136   927  3401 I WindowState: WIN DEATH: Window{8bee633 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-15 10:25:17.136   927  2827 D WifiService: Client connection lost with reason: 4
09-15 10:25:17.160   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-15 10:25:17.162   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-15 10:25:17.162   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-15 10:25:17.162   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-15 10:25:17.162   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:25:17.162   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:25:17.162   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 10:25:17.162   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 10:25:17.163   927   940 I ActivityManager:   Force finishing activity ActivityRecord{283cbc u0 com.test.thalitest/.MainActivity t2}
09-15 10:25:17.164   927   950 I art     : Starting a blocking GC Explicit
09-15 10:25:17.169   927  3245 W ActivityManager: Spurious death for ProcessRecord{a18f36f 0:com.test.thalitest/u0a77}, curProc for 5347: null
09-15 10:25:17.239   927   950 I art     : Explicit concurrent mark sweep GC freed 33288(2009KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 1.264ms total 74.539ms
09-15 10:25:17.246  5731  5731 I ServiceManager: Waiting for service AtCmdFwd...
09-15 10:25:17.257   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-15 10:25:17.261  5735  5735 I art     : System.exit called, status: 0
09-15 10:25:17.261  5735  5735 I AndroidRuntime: VM exiting with result code 0.
09-15 10:25:17.276   927   950 I ActivityManager: Start proc 5749:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-15 10:25:17.276   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-15 10:25:17.281   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-15 10:25:17.285  5629  5629 D BluetoothMapAppObserver: onReceive
09-15 10:25:17.285  5629  5629 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-15 10:25:17.291  3491  3806 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-15 10:25:17.298  3246  3246 I Keyboard.Facilitator: resetDictionaries() : en_US
09-15 10:25:17.306   927  2810 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-15 10:25:17.308   927   940 I ActivityManager: Start proc 5761:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-15 10:25:17.313  3246  5759 I Keyboard.Facilitator.DecoderInitializer: run()
09-15 10:25:17.329  3246  5759 I Decoder : createOrResetDecoder
09-15 10:25:17.334  3347  3347 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-15 10:25:17.366    27    27 W kworker/2:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-15 10:25:17.369    27    27 W kworker/2:1: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-15 10:25:17.377   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-15 10:25:17.380  3373  3555 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-15 10:25:17.376    27    27 W kworker/2:1: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-15 10:25:17.394   927   937 I ActivityManager: Start proc 5778:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-15 10:25:17.395  3373  3555 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-15 10:25:17.395  3373  3555 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3373
09-15 10:25:17.395  3373  3555 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:25:17.395  3373  3555 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 10:25:17.397  3436  3436 I ConfigService: onCreate
09-15 10:25:17.401   927  3405 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-15 10:25:17.401   927  5785 E DropBoxManagerService: Can't write: system_app_crash
09-15 10:25:17.401   927  5785 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 10:25:17.401   927  5785 E DropBoxManagerService: 	... 5 more
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-15 10:25:17.401  3436  5783 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-15 10:25:17.402  3436  5783 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-15 10:25:17.404  3436  5783 W SQLiteOpenHelper: Opened config.db in read-only mode
09-15 10:25:17.415  3373  3555 I Process : Sending signal. PID: 3373 SIG: 9
09-15 10:25:17.431  3246  5759 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-15 10:25:17.443  5761  5761 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
09-15 10:25:17.471   384   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
