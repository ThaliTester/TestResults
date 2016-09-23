#### Test 850469114943827_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 03:12:43.145   537   537 I ServiceManager: Waiting for service AtCmdFwd...
09-23 03:12:44.147   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-23 03:12:44.836  5505  5505 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 03:12:44.841  5505  5505 D AndroidRuntime: CheckJNI is OFF
09-23 03:12:44.869  5505  5505 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 03:12:44.900  5505  5505 I Radio-JNI: register_android_hardware_Radio DONE
09-23 03:12:44.915  5505  5505 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 03:12:44.918   929  3499 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 03:12:44.955   929  3499 I ActivityManager: Start proc 5514:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 03:12:44.960  5505  5505 D AndroidRuntime: Shutting down VM
,09-23 03:12:45.303   929  3503 I WindowManager: Screenshot max retries 4 of Token{4d0c92c ActivityRecord{44e68df u0 com.test.thalitest/.MainActivity t2}} appWin=Window{a4111c4 u0 Starting com.test.thalitest} drawState=2
,09-23 03:12:45.366  5514  5514 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 03:12:45.400  5514  5514 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 03:12:45.472  5514  5514 I LibraryLoader: Time to load native libraries: 68 ms (timestamps 1368-1436)
,09-23 03:12:45.473  5514  5514 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 03:12:45.508  5514  5514 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {51915ac}
09-23 03:12:45.508  5514  5514 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 03:12:45.509  5514  5514 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-23 03:12:45.516  5514  5514 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-23 03:12:45.518  5514  5514 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 03:12:45.570  5514  5514 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 03:12:45.588  5514  5514 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 03:12:45.588  5514  5514 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 03:12:45.588  5514  5514 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 03:12:45.588  5514  5514 I Adreno  : Build Date                       : 12/06/15
09-23 03:12:45.588  5514  5514 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 03:12:45.588  5514  5514 I Adreno  : Local Branch                     : mybranch17112971
09-23 03:12:45.588  5514  5514 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 03:12:45.588  5514  5514 I Adreno  : Remote Branch                    : NONE
09-23 03:12:45.588  5514  5514 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 03:12:45.648   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44947cf:true
,09-23 03:12:45.677  2941  2941 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[23326]" dev="sockfs" ino=23326 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 03:12:45.677  2941  2941 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[23326]" dev="sockfs" ino=23326 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 03:12:45.692  5514  5514 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 03:12:45.701  5514  5514 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 03:12:45.734  2941  2941 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32455]" dev="sockfs" ino=32455 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 03:12:45.734  2941  2941 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32455]" dev="sockfs" ino=32455 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 03:12:45.737  5514  5551 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 03:12:45.737  3499  3499 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14944]" dev="sockfs" ino=14944 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 03:12:45.737  3499  3499 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14944]" dev="sockfs" ino=14944 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 03:12:45.744  5514  5538 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 03:12:45.778  5514  5551 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 03:12:45.864   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +557ms (total +931ms)
,09-23 03:12:45.888  5514  5514 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5514
,09-23 03:12:45.994  5514  5514 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 03:12:46.167  5514  5554 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -583268048
,09-23 03:12:46.171  5514  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 03:12:46.171  5514  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 03:12:46.171  5514  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 03:12:46.171  5514  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 03:12:46.171  5514  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-23 03:12:46.171  5514  5554 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df8fced added. We now have 1 listener(s)
,09-23 03:12:46.173  5514  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-23 03:12:46.174  5514  5554 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 03:12:46.174  5514  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 03:12:46.174  5514  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-23 03:12:46.178  5514  5554 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1860770 added. We now have 1 listener(s)
09-23 03:12:46.178  5514  5554 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 03:12:46.184   929  2967 D WifiService: New client listening to asynchronous messages
,09-23 03:12:46.184  5514  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 03:12:46.185  5514  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 03:12:46.185  5514  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 03:12:46.185  5514  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 03:12:46.185  5514  5554 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 03:12:46.187  5514  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 03:12:46.187  5514  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 03:12:46.190  5514  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 03:12:46.190  5514  5554 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 03:12:46.190  5514  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 03:12:46.190  5514  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 03:12:46.190  5514  5554 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 03:12:46.190  5514  5554 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 03:12:46.190  5514  5554 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 03:12:46.190  5514  5554 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 03:12:46.190  5514  5554 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 03:12:46.190  5514  5554 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 03:12:46.190  5514  5554 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 03:12:46.191  5514  5554 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 03:12:46.194  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 03:12:46.196  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 03:12:46.322  5514  5514 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 03:12:46.465  5514  5560 W jxcore-log: Initializing JXcore engine
,09-23 03:12:46.465  5514  5560 W jxcore-log: JXcore engine is ready
,09-23 03:12:46.487  5560  5560 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12855 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-23 03:12:46.487  5560  5560 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13228]" dev="sockfs" ino=13228 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-23 03:12:46.487  5560  5560 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 03:12:46.487  5560  5560 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32423]" dev="sockfs" ino=32423 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 03:12:46.496  5514  5560 W jxcore-log: Starting JXcore engine
,09-23 03:12:46.548  5514  5560 W jxcore-log: Platform android
09-23 03:12:46.548  5514  5560 W jxcore-log: 
,09-23 03:12:46.548  5514  5560 W jxcore-log: Process ARCH arm
09-23 03:12:46.548  5514  5560 W jxcore-log: 
,09-23 03:12:46.651  5514  5560 I jxcore-log: JXcore Cordova bridge is ready!
09-23 03:12:46.651  5514  5560 I jxcore-log: 
09-23 03:12:46.651  5514  5560 W jxcore-log: JXcore engine is started
,09-23 03:12:46.653  5514  5554 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 03:12:46.656  5514  5514 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 03:12:53.144  5514  5560 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 03:12:53.144  5514  5560 I jxcore-log: 
,09-23 03:12:53.146  5514  5560 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 03:12:53.146  5514  5560 I jxcore-log: 
,09-23 03:12:53.150  5514  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 03:12:53.150  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 03:12:53.150  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 03:12:53.150  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 03:12:53.150  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 03:12:53.150  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 03:12:53.150  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 03:12:53.150  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 03:12:53.152  5514  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 03:12:53.154  5514  5560 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 03:12:53.154  5514  5560 I jxcore-log: 
,09-23 03:12:53.155  5514  5560 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 03:12:53.155  5514  5560 I jxcore-log: 
,09-23 03:12:53.496  5514  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 03:12:53.496  5514  5560 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea2b23c added. We now have 2 listener(s)
09-23 03:12:53.497  5514  5560 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 03:12:53.497  5514  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 03:12:53.497  5514  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 03:12:53.497  5514  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 03:12:53.497  5514  5560 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc5bc5 added. We now have 2 listener(s)
,09-23 03:12:53.497  5514  5560 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 03:12:53.498  5514  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 03:12:53.499  5514  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 03:12:53.501  5514  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 03:12:53.501  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 03:12:53.501  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 03:12:53.501  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 03:12:53.501  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 03:12:53.501  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 03:12:53.501  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 03:12:53.501  5514  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 03:12:53.502  5514  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 03:12:53.503  5514  5560 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 03:12:53.503  5514  5560 D ExecuteNativeTests: Running unit tests
,09-23 03:12:53.504  5514  5560 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 03:12:53.504   929  3472 D WifiService: setWifiEnabled: true pid=5514, uid=10077
09-23 03:12:53.504   929  3472 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 03:12:53.508  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 03:12:53.513  5514  5514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 03:12:58.728   929  5211 D NetlinkSocketObserver: NeighborEvent{elapsedMs=184691, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 03:13:03.508  5514  5560 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 03:13:03.535  5514  5560 I jxcore-log: *Native tests were executed*
09-23 03:13:03.535  5514  5560 I jxcore-log: 
,09-23 03:13:03.535  5514  5560 I jxcore-log: Total number of executed tests:  1
09-23 03:13:03.535  5514  5560 I jxcore-log: 
,09-23 03:13:03.536  5514  5560 I jxcore-log: Number of passed tests:  1
09-23 03:13:03.536  5514  5560 I jxcore-log: 
09-23 03:13:03.536  5514  5560 I jxcore-log: Number of failed tests:  0
09-23 03:13:03.536  5514  5560 I jxcore-log: 
09-23 03:13:03.536  5514  5560 I jxcore-log: Number of ignored tests:  0
09-23 03:13:03.536  5514  5560 I jxcore-log: 
09-23 03:13:03.536  5514  5560 I jxcore-log: Total duration:  3
09-23 03:13:03.536  5514  5560 I jxcore-log: 
,09-23 03:13:03.537  5514  5560 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 03:13:03.537  5514  5560 I jxcore-log: 
09-23 03:13:03.539  5514  5560 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 03:13:03.539  5514  5560 I jxcore-log: 
09-23 03:13:03.541  5514  5560 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 03:13:03.541  5514  5560 I jxcore-log: 
,09-23 03:13:03.564  5514  5514 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-23 03:13:04.048  5562  5562 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 03:13:04.052  5562  5562 D AndroidRuntime: CheckJNI is OFF
,09-23 03:13:04.080  5562  5562 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 03:13:04.111  5562  5562 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 03:13:04.126  5562  5562 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 03:13:04.138   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-23 03:13:04.139   929   942 I ActivityManager: Killing 5514:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-23 03:13:04.148   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 03:13:04.211   929  2967 D WifiService: Client connection lost with reason: 4
,09-23 03:13:04.211   929   940 D GraphicsStats: Buffer count: 2
,09-23 03:13:04.211   929  3128 I WindowState: WIN DEATH: Window{3a1cea u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-23 03:13:04.258   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-23 03:13:04.258   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-23 03:13:04.259   929   952 I art     : Starting a blocking GC Explicit
,09-23 03:13:04.259   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-23 03:13:04.259   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-23 03:13:04.259   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:13:04.259   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:13:04.259   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 03:13:04.259   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 03:13:04.260   929   942 I ActivityManager:   Force finishing activity ActivityRecord{44e68df u0 com.test.thalitest/.MainActivity t2}
,09-23 03:13:04.268   929   939 W ActivityManager: Spurious death for ProcessRecord{80750c1 0:com.test.thalitest/u0a77}, curProc for 5514: null
,09-23 03:13:04.269   929   947 W WindowManager: Attempted to add application window with unknown token Token{4d0c92c ActivityRecord{44e68df u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-23 03:13:04.269   929   947 W WindowManager: Token{4d0c92c ActivityRecord{44e68df u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{4d0c92c ActivityRecord{44e68df u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-23 03:13:04.269   929   947 W WindowManager: view not successfully added to wm, removing view
09-23 03:13:04.269   929   947 W WindowManager: Exception when adding starting window
09-23 03:13:04.269   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{1924fa7 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-23 03:13:04.269   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-23 03:13:04.269   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-23 03:13:04.269   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-23 03:13:04.269   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-23 03:13:04.269   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-23 03:13:04.269   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:13:04.269   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:13:04.269   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 03:13:04.269   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 03:13:04.343   929   952 I art     : Explicit concurrent mark sweep GC freed 55282(4MB) AllocSpace objects, 20(456KB) LOS objects, 33% free, 28MB/43MB, paused 1.611ms total 83.376ms
,09-23 03:13:04.363   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-23 03:13:04.367  5562  5562 I art     : System.exit called, status: 0
09-23 03:13:04.367  5562  5562 I AndroidRuntime: VM exiting with result code 0.
,09-23 03:13:04.371   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-23 03:13:04.376   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-23 03:13:04.380  4374  4374 D BluetoothMapAppObserver: onReceive
09-23 03:13:04.380  4374  4374 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-23 03:13:04.394   929  2939 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-23 03:13:04.395  3394  3394 I Keyboard.Facilitator: resetDictionaries() : en_US
09-23 03:13:04.396  3584  3928 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-23 03:13:04.423  3394  5574 I Keyboard.Facilitator.DecoderInitializer: run()
,09-23 03:13:04.432  3380  5575 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-23 03:13:04.433  3394  5574 I Decoder : createOrResetDecoder
,09-23 03:13:04.443  3481  3481 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-23 03:13:04.462  3564  3564 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-23 03:13:04.462  3564  3564 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-23 03:13:04.481   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-23 03:13:04.477    28    28 W kworker/2:1: type=1400 audit(0.0:110): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 03:13:04.487    28    28 W kworker/2:1: type=1400 audit(0.0:111): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 03:13:04.504  3875  5580 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-23 03:13:04.505  3875  5580 D AccountUtils: Clearing selected account for com.test.thalitest
,09-23 03:13:04.504    28    28 W kworker/2:1: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 03:13:04.512   929  3386 I ActivityManager: Start proc 5582:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-23 03:13:04.513  3512  3634 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-23 03:13:04.513  3512  3634 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3512
09-23 03:13:04.513  3512  3634 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:13:04.513  3512  3634 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 03:13:04.516   929  5590 E DropBoxManagerService: Can't write: system_app_crash
09-23 03:13:04.516   929  5590 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 03:13:04.516   929  5590 E DropBoxManagerService: 	... 5 more
,09-23 03:13:04.517  3564  3564 I ConfigService: onCreate
,09-23 03:13:04.518   929   939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-23 03:13:04.522  3564  5591 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 03:13:04.522  3564  5591 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 03:13:04.522  3564  5591 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-23 03:13:04.524  3512  3634 I Process : Sending signal. PID: 3512 SIG: 9
09-23 03:13:04.524  3564  5591 W SQLiteOpenHelper: Opened config.db in read-only mode
09-23 03:13:04.543  3394  5574 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-23 03:13:04.559  3875  5580 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-23 03:13:04.576  3380  3407 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj8A0FB2967) - 
,09-23 03:13:04.587  3875  5580 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:13:04.587  3875  5580 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 03:13:04.587  3875  5580 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:13:04.587  3875  5580 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 03:13:04.588  3875  5580 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-23 03:13:04.639   929  2938 W InputDispatcher: channel '404a3f5 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-23 03:13:04.639   929  2938 E InputDispatcher: channel '404a3f5 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-23 03:13:04.639   929  5573 D GraphicsStats: Buffer count: 1
09-23 03:13:04.639   929  3472 I WindowState: WIN DEATH: Window{404a3f5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-23 03:13:04.639   929  3472 W InputDispatcher: Attempted to unregister already unregistered input channel '404a3f5 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-23 03:13:04.650  3380  3407 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-23 03:13:04.650  3380  3407 E AndroidRuntime: Process: android.process.acore, PID: 3380
09-23 03:13:04.650  3380  3407 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:13:04.650  3380  3407 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 03:13:04.660   929  3503 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3512) has died
,09-23 03:13:04.661   929  3503 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-23 03:13:04.664  3380  3407 I Process : Sending signal. PID: 3380 SIG: 9
,09-23 03:13:04.695  3875  5602 I GMPM-SVC: App measurement is starting up
,09-23 03:13:04.700  3875  5602 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-23 03:13:04.701  3875  5602 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-23 03:13:04.900   383   472 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
