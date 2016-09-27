#### Test 85046911c0a96fd_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-27 07:06:39.667  5570  5615 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
09-27 07:06:39.716  3738  3738 I ConfigFetchService: fetch service done; releasing wakelock
09-27 07:06:39.717  3738  3738 I ConfigFetchService: stopping self
09-27 07:06:39.734  5570  5615 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
09-27 07:06:39.744  3738  4954 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
09-27 07:06:39.812  3738  4954 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
09-27 07:06:39.837  5570  5615 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-27 07:06:40.695   535   535 I ServiceManager: Waiting for service AtCmdFwd...
--------- beginning of system
09-27 07:06:40.999   927  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 07:06:41.696   535   535 I ServiceManager: Waiting for service AtCmdFwd...
09-27 07:06:41.838  5628  5628 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-27 07:06:41.844  5628  5628 D AndroidRuntime: CheckJNI is OFF
09-27 07:06:41.873  5628  5628 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-27 07:06:41.905  5628  5628 I Radio-JNI: register_android_hardware_Radio DONE
09-27 07:06:41.920  5628  5628 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-27 07:06:41.924   927  3693 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-27 07:06:41.967   927  3693 I ActivityManager: Start proc 5637:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-27 07:06:41.990  5628  5628 D AndroidRuntime: Shutting down VM
,09-27 07:06:42.313   927  3839 I WindowManager: Screenshot max retries 4 of Token{4b72667 ActivityRecord{b695a26 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{80787fe u0 Starting com.test.thalitest} drawState=2
,09-27 07:06:42.378  5637  5637 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-27 07:06:42.414  5637  5637 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-27 07:06:42.482  5637  5637 I LibraryLoader: Time to load native libraries: 64 ms (timestamps 1299-1363)
09-27 07:06:42.482  5637  5637 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-27 07:06:42.513  5637  5637 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {aba9873}
,09-27 07:06:42.513  5637  5637 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-27 07:06:42.514  5637  5637 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-27 07:06:42.519  5637  5637 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-27 07:06:42.521  5637  5637 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-27 07:06:42.569  5637  5637 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-27 07:06:42.588  5637  5637 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-27 07:06:42.589  5637  5637 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-27 07:06:42.589  5637  5637 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-27 07:06:42.589  5637  5637 I Adreno  : Build Date                       : 12/06/15
09-27 07:06:42.589  5637  5637 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-27 07:06:42.589  5637  5637 I Adreno  : Local Branch                     : mybranch17112971
09-27 07:06:42.589  5637  5637 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-27 07:06:42.589  5637  5637 I Adreno  : Remote Branch                    : NONE
09-27 07:06:42.589  5637  5637 I Adreno  : Reconstruct Branch               : NOTHING
,09-27 07:06:42.612   927  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 07:06:42.639   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a55f2d:true
,09-27 07:06:42.662   403   403 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15051]" dev="sockfs" ino=15051 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 07:06:42.662   403   403 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[15051]" dev="sockfs" ino=15051 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 07:06:42.676  5637  5637 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-27 07:06:42.684  5637  5637 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-27 07:06:42.696   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:06:42.702   741   741 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33895]" dev="sockfs" ino=33895 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 07:06:42.708  5637  5674 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-27 07:06:42.702   741   741 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33895]" dev="sockfs" ino=33895 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 07:06:42.705  3693  3693 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[16760]" dev="sockfs" ino=16760 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 07:06:42.705  3693  3693 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[16760]" dev="sockfs" ino=16760 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 07:06:42.713  5637  5661 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-27 07:06:42.744  5637  5674 I OpenGLRenderer: Initialized EGL, version 1.4
,09-27 07:06:42.817   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +501ms (total +877ms)
,09-27 07:06:42.843  5637  5637 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5637
,09-27 07:06:42.914  5637  5637 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-27 07:06:43.037  5637  5677 D jxcore_app_log: JniHelper::setJavaVM(0xf50bc000), pthread_self() = -581957328
,09-27 07:06:43.041  5637  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-27 07:06:43.041  5637  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-27 07:06:43.041  5637  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-27 07:06:43.041  5637  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-27 07:06:43.041  5637  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-27 07:06:43.041  5637  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cc5d08 added. We now have 1 listener(s)
,09-27 07:06:43.043  5637  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-27 07:06:43.044  5637  5677 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 07:06:43.044  5637  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 07:06:43.044  5637  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-27 07:06:43.046  5637  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bbce87 added. We now have 1 listener(s)
09-27 07:06:43.047  5637  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 07:06:43.054   927  2981 D WifiService: New client listening to asynchronous messages
,09-27 07:06:43.055  5637  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 07:06:43.055  5637  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-27 07:06:43.055  5637  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-27 07:06:43.055  5637  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-27 07:06:43.055  5637  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-27 07:06:43.058  5637  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 07:06:43.058  5637  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-27 07:06:43.062  5637  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-27 07:06:43.062  5637  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 07:06:43.062  5637  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:06:43.062  5637  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:06:43.062  5637  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:06:43.062  5637  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:06:43.062  5637  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 07:06:43.062  5637  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 07:06:43.062  5637  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 07:06:43.063  5637  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-27 07:06:43.063  5637  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 07:06:43.063  5637  5677 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-27 07:06:43.066  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:06:43.072  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:06:43.082  5637  5637 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-27 07:06:43.390  5637  5683 W jxcore-log: Initializing JXcore engine
09-27 07:06:43.391  5637  5683 W jxcore-log: JXcore engine is ready
,09-27 07:06:43.412  5683  5683 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12555 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-27 07:06:43.412  5683  5683 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16417]" dev="sockfs" ino=16417 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-27 07:06:43.412  5683  5683 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-27 07:06:43.412  5683  5683 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32177]" dev="sockfs" ino=32177 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-27 07:06:43.423  5637  5683 W jxcore-log: Starting JXcore engine
,09-27 07:06:43.478  5637  5683 W jxcore-log: Platform android
09-27 07:06:43.478  5637  5683 W jxcore-log: 
09-27 07:06:43.478  5637  5683 W jxcore-log: Process ARCH arm
09-27 07:06:43.478  5637  5683 W jxcore-log: 
,09-27 07:06:43.579  5637  5683 I jxcore-log: JXcore Cordova bridge is ready!
09-27 07:06:43.579  5637  5683 I jxcore-log: 
,09-27 07:06:43.579  5637  5683 W jxcore-log: JXcore engine is started
,09-27 07:06:43.588  5637  5677 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-27 07:06:43.591  5637  5637 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-27 07:06:43.697   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:06:44.698   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:06:44.726  3589  3589 I ConfigService: onDestroy
,09-27 07:06:45.699   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 07:06:50.463  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-27 07:06:50.463  5637  5683 I jxcore-log: 
,09-27 07:06:50.465  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-27 07:06:50.465  5637  5683 I jxcore-log: 
,09-27 07:06:50.470  5637  5683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 07:06:50.470  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:06:50.470  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:06:50.470  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:06:50.470  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:06:50.470  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 07:06:50.470  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 07:06:50.470  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 07:06:50.472  5637  5683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 07:06:50.474  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-27 07:06:50.474  5637  5683 I jxcore-log: 
,09-27 07:06:50.475  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-27 07:06:50.475  5637  5683 I jxcore-log: 
,09-27 07:06:50.700   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:06:50.709  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 07:06:50.710  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0aa46e added. We now have 2 listener(s)
09-27 07:06:50.710  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 07:06:50.710  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 07:06:50.710  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 07:06:50.711  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 07:06:50.711  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b5b70f added. We now have 2 listener(s)
,09-27 07:06:50.711  5637  5683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 07:06:50.711  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 07:06:50.713  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 07:06:50.716  5637  5683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 07:06:50.716  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:06:50.716  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:06:50.716  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:06:50.716  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:06:50.716  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 07:06:50.716  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 07:06:50.716  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 07:06:50.717  5637  5683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 07:06:50.717  5637  5683 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 07:06:50.718  5637  5683 D ExecuteNativeTests: Running unit tests
09-27 07:06:50.718  5637  5683 D BluetoothAdapter: enable(): BT is already enabled..!
,09-27 07:06:50.719   927  3693 D WifiService: setWifiEnabled: true pid=5637, uid=10077
09-27 07:06:50.719   927  3693 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 07:06:50.726  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:06:50.731  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:06:51.701   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:06:52.703   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:06:53.103   927  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 07:06:53.300  4809  4880 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-27 07:06:53.301  4809  4809 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,09-27 07:06:53.704   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:06:54.706   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:06:55.707   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 07:06:56.130   927  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 07:07:00.011   927   927 I ActivityManager: Killing 5072:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,09-27 07:07:00.209   927  5396 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-27 07:07:00.725  5637  5683 I com.test.thalitest.ThaliTestRunner: Running UT
,09-27 07:07:00.787  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 07:07:00.788  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be126c9 added. We now have 3 listener(s)
,09-27 07:07:00.788  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 07:07:00.789  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 07:07:00.789  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 07:07:00.789  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 07:07:00.789  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@124f1ce added. We now have 3 listener(s)
,09-27 07:07:00.789  5637  5683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 07:07:00.789  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 07:07:00.792  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 07:07:00.795  5637  5683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 07:07:00.795  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:00.795  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:00.795  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:00.795  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:00.795  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 07:07:00.795  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 07:07:00.795  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 07:07:00.796  5637  5683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 07:07:00.796  5637  5683 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 07:07:00.800  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
09-27 07:07:00.800  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-27 07:07:00.800  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 07:07:00.800  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 07:07:00.800  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 07:07:00.801  5637  5683 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-27 07:07:00.801  5637  5683 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-27 07:07:00.801  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 07:07:00.801  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 07:07:00.801  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 07:07:00.801  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 07:07:00.802  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
09-27 07:07:00.802  5637  5683 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-27 07:07:00.803  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:00.803  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-27 07:07:00.805  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
09-27 07:07:00.805  5637  5683 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-27 07:07:00.816  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:00.816  5637  5683 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 07:07:00.817  5637  5683 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-27 07:07:00.817  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-27 07:07:00.817  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-27 07:07:00.817  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 07:07:00.817  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 07:07:00.818  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 07:07:00.818  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 07:07:00.819  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 07:07:00.819  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 07:07:00.819  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 07:07:00.819  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 07:07:00.819  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 07:07:00.819  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 07:07:00.819  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-27 07:07:00.821  5637  5683 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 07:07:00.821  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 07:07:00.823  5637  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 07:07:00.825  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 07:07:00.826  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 07:07:00.822  4613  4613 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31433]" dev="sockfs" ino=31433 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:00.826  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 07:07:00.826  5637  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 07:07:00.822  4613  4613 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31433]" dev="sockfs" ino=31433 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:00.827  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 07:07:00.827  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 07:07:00.827  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-27 07:07:00.828  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:00.828  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-27 07:07:00.828  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 07:07:00.828  5637  5683 D BluetoothAdapter: STATE_ON
,09-27 07:07:00.831  4600  4859 D BtGatt.GattService: registerClient() - UUID=eee82495-d608-4956-bcd6-b70efa7af645
,09-27 07:07:00.832  4600  4688 D BtGatt.GattService: onClientRegistered() - UUID=eee82495-d608-4956-bcd6-b70efa7af645, clientIf=5
,09-27 07:07:00.832  5637  5648 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 07:07:00.836  4600  4690 D BtGatt.AdvertiseManager: message : 0
,09-27 07:07:00.839  4600  4690 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 07:07:00.857  4600  4688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 07:07:00.864  4600  4688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 07:07:00.866  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-27 07:07:00.866  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 07:07:00.867  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 07:07:00.867  5637  5683 I io.jxcore.node.ConnectionHelper: start: OK
09-27 07:07:00.868  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-27 07:07:00.868  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-27 07:07:00.868  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 07:07:00.868  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 07:07:00.868  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 07:07:00.869  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 07:07:00.872  5637  5637 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 07:07:00.872  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 07:07:01.370  5637  5683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 07:07:01.371  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-27 07:07:01.371  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 07:07:01.371  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 07:07:01.371  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-27 07:07:01.372  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-27 07:07:01.372  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 07:07:01.373  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-27 07:07:01.373  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 07:07:01.373  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 07:07:01.373  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-27 07:07:01.373  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 07:07:01.373  5637  5637 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-27 07:07:01.373  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-27 07:07:01.374  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 07:07:01.374  5637  5637 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 07:07:01.374  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 07:07:01.374  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-27 07:07:01.374  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 07:07:01.375  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 07:07:01.375  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 07:07:01.375  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-27 07:07:01.376  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-27 07:07:01.376  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 07:07:01.376  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-27 07:07:01.377  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 07:07:01.377  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 07:07:01.377  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-27 07:07:01.377  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 07:07:01.378  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 07:07:01.378  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 07:07:01.378  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-27 07:07:01.378  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 07:07:01.378  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 07:07:01.379  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 07:07:01.379  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-27 07:07:01.380  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-27 07:07:01.380  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 07:07:01.380  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 07:07:01.381  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 07:07:01.382  5637  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 07:07:01.382  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 07:07:01.382  5637  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 07:07:01.382  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-27 07:07:01.382  5637  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 07:07:01.383  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 07:07:01.383  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 07:07:01.383  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 07:07:01.383  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 07:07:01.383  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 07:07:01.385  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-27 07:07:01.389  5637  5683 D BluetoothAdapter: STATE_ON
,09-27 07:07:01.391  5637  5683 D BluetoothLeScanner: could not find callback wrapper
09-27 07:07:01.391  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 07:07:01.391  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 07:07:01.393  4600  4690 D BtGatt.AdvertiseManager: message : 1
09-27 07:07:01.393  4600  4690 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 07:07:01.401  4600  4688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 07:07:01.402  4600  4688 D BtGatt.GattService: Client app is not null!
,09-27 07:07:01.403  4600  4832 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 07:07:01.403  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 07:07:01.404  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 07:07:01.404  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 07:07:01.404  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 07:07:01.404  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 07:07:01.405  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:01.406  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 07:07:01.406  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 07:07:01.407  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 07:07:01.409  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 07:07:01.409  5637  5637 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 07:07:01.409  5637  5637 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 07:07:01.409  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 07:07:01.409  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 07:07:01.409  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:01.410  5637  5683 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 07:07:01.410  5637  5683 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 07:07:01.410  5637  5683 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-27 07:07:01.411  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-27 07:07:01.411  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 07:07:01.411  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 07:07:01.411  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 07:07:01.411  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 07:07:01.413  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 07:07:01.413  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 07:07:01.413  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 07:07:01.413  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 07:07:01.413  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 07:07:01.413  5637  5683 I org.thalip,roject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 07:07:01.413  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 07:07:01.413  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 07:07:01.414  5637  5688 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:01.412  4859  4859 W Binder_5: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31442]" dev="sockfs" ino=31442 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:01.412  4859  4859 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31442]" dev="sockfs" ino=31442 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:01.417  5637  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 07:07:01.419  5637  5683 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 07:07:01.419  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 07:07:01.424  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 07:07:01.424  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 07:07:01.424  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 07:07:01.426  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 07:07:01.427  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 07:07:01.427  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-27 07:07:01.427  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:01.427  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:01.427  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 07:07:01.428  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:01.430  4600  4613 D BtGatt.GattService: registerClient() - UUID=88123b27-bdcd-4476-9803-dc7233bfcaef
09-27 07:07:01.430  4600  4688 D BtGatt.GattService: onClientRegistered() - UUID=88123b27-bdcd-4476-9803-dc7233bfcaef, clientIf=5
09-27 07:07:01.431  5637  5647 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-27 07:07:01.432  4600  4690 D BtGatt.AdvertiseManager: message : 0
09-27 07:07:01.434  4600  4690 D BtGatt.AdvertiseManager: starting multi advertising
09-27 07:07:01.456  4600  4688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 07:07:01.461  4600  4688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-27 07:07:01.461  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 07:07:01.461  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 07:07:01.463  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 07:07:01.464  5637  5683 I io.jxcore.node.ConnectionHelper: start: OK
09-27 07:07:01.464  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 07:07:01.464  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 07:07:01.464  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 07:07:01.464  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 07:07:01.464  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 07:07:01.464  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 07:07:01.466  5637  5637 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 07:07:01.466  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 07:07:01.967  5637  5637 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 07:07:01.967  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
09-27 07:07:01.968  5637  5683 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 07:07:01.968  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 07:07:01.968  5637  5683 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 07:07:01.968  5637  5637 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 07:07:01.968  5637  5683 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-27 07:07:01.969  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-27 07:07:01.970  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-27 07:07:01.970  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-27 07:07:01.970  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-27 07:07:01.970  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-27 07:07:01.970  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-27 07:07:01.970  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-27 07:07:01.970  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-27 07:07:01.970  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-27 07:07:01.970  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,09-27 07:07:01.974  4600  4690 D BtGatt.AdvertiseManager: message : 1
09-27 07:07:01.975  4600  4690 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 07:07:01.989  4600  4688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 07:07:01.989  4600  4688 D BtGatt.GattService: Client app is not null!
,09-27 07:07:01.991  4600  4613 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 07:07:01.991  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 07:07:01.991  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 07:07:01.992  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 07:07:01.992  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-27 07:07:01.992  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 07:07:01.992  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,09-27 07:07:01.992  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:01.993  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:01.993  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 07:07:01.994  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:01.999  4600  4613 D BtGatt.GattService: registerClient() - UUID=ac09058d-96c4-4d38-9d1c-71bc8524412c
09-27 07:07:02.001  4600  4688 D BtGatt.GattService: onClientRegistered() - UUID=ac09058d-96c4-4d38-9d1c-71bc8524412c, clientIf=5
09-27 07:07:02.002  5637  5648 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-27 07:07:02.003  4600  4690 D BtGatt.AdvertiseManager: message : 0
,09-27 07:07:02.008  4600  4690 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 07:07:02.021  4600  4688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 07:07:02.029  4600  4688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 07:07:02.029  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-27 07:07:02.029  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 07:07:02.029  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 07:07:02.029  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 07:07:02.029  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 07:07:02.029  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 07:07:02.029  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-27 07:07:02.030  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 07:07:02.030  5637  5683 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 07:07:02.031  5637  5683 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 07:07:02.031  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-27 07:07:02.031  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 07:07:02.031  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 07:07:02.031  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-27 07:07:02.031  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 07:07:02.032  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 07:07:02.032  5637  5688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 07:07:02.032  5637  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 07:07:02.032  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 07:07:02.032  5637  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 07:07:02.032  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 07:07:02.032  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 07:07:02.032  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-27 07:07:02.032  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 07:07:02.032  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 07:07:02.032  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 07:07:02.033  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:02.033  5637  5683 D BluetoothLeScanner: could not find callback wrapper
09-27 07:07:02.033  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 07:07:02.033  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 07:07:02.034  4600  4690 D BtGatt.AdvertiseManager: message : 1
,09-27 07:07:02.035  4600  4690 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 07:07:02.042  4600  4688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-27 07:07:02.042  4600  4688 D BtGatt.GattService: Client app is not null!
,09-27 07:07:02.043  4600  4614 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 07:07:02.044  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 07:07:02.044  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-27 07:07:02.044  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 07:07:02.044  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 07:07:02.044  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 07:07:02.046  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:02.046  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 07:07:02.046  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 07:07:02.047  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 07:07:02.048  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 07:07:02.048  5637  5637 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 07:07:02.048  5637  5637 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 07:07:02.048  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 07:07:02.049  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
09-27 07:07:02.050  5637  5683 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-27 07:07:02.051  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-27 07:07:02.048  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 07:07:02.052  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:02.052  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-27 07:07:02.053  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,09-27 07:07:02.053  5637  5683 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-27 07:07:02.054  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-27 07:07:02.054  5637  5683 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-27 07:07:02.055  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-27 07:07:02.055  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 07:07:02.055  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 07:07:02.056  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 07:07:02.056  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 07:07:02.056  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 07:07:02.056  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 07:07:02.056  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 07:07:02.056  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 07:07:02.056  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 07:07:02.056  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 07:07:02.056  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 07:07:02.056  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 07:07:02.057  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-27 07:07:02.058  5637  5683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 07:07:02.058  5637  5683 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 07:07:02.058  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-27 07:07:02.061  5637  5683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-27 07:07:02.062  5637  5683 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 07:07:02.062  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 07:07:02.063  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 07:07:02.064  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-27 07:07:02.064  5637  5683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-27 07:07:02.064  5637  5683 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 07:07:02.064  5637  5683 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-27 07:07:02.064  5637  5683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 07:07:02.064  5637  5683 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 07:07:02.064  5637  5683 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-27 07:07:02.064  5637  5683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 07:07:02.065  5637  5683 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 07:07:02.065  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-27 07:07:02.069  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-27 07:07:02.070  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-27 07:07:02.070  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-27 07:07:02.071  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-27 07:07:02.071  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-27 07:07:02.071  5637  5683 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-27 07:07:02.071  5637  5683 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 07:07:02.071  5637  5683 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-27 07:07:02.072  5637  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
09-27 07:07:02.073  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-27 07:07:02.073  5637  5683 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-27 07:07:02.073  5637  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-27 07:07:02.073  5637  5692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:02.074  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-27 07:07:02.074  5637  5683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-27 07:07:02.072  4613  4613 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32258]" dev="sockfs" ino=32258 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:02.072  4613  4613 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32258]" dev="sockfs" ino=32258 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:02.075  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-27 07:07:02.075  5637  5683 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-27 07:07:02.076  5637  5683 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-27 07:07:02.076  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 07:07:02.076  5637  5683 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-27 07:07:02.076  5637  5683 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 07:07:02.076  5637  5683 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-27 07:07:02.076  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 07:07:02.076  5637  5683 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-27 07:07:02.076  5637  5683 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 07:07:02.076  5637  5683 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 07:07:02.076  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-27 07:07:02.076  5637  5683 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-27 07:07:02.077  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-27 07:07:02.077  5637  5683 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 07:07:02.077  5637  5683 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 07:07:02.077  5637  5683 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-27 07:07:02.077  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,09-27 07:07:02.078  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 07:07:02.078  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 07:07:02.078  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 07:07:02.078  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 07:07:02.079  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 07:07:02.080  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 07:07:02.080  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 07:07:02.080  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 07:07:02.080  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 07:07:02.080  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 07:07:02.080  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 07:07:02.080  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 07:07:02.081  5637  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:02.078  4829  4829 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33924]" dev="sockfs" ino=33924 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:02.078  4829  4829 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33924]" dev="sockfs" ino=33924 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 07:07:02.084  5637  5683 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 07:07:02.084  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 07:07:02.085  5637  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 07:07:02.087  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 07:07:02.087  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 07:07:02.087  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 07:07:02.089  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-27 07:07:02.089  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 07:07:02.089  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-27 07:07:02.089  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:02.089  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:02.089  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-27 07:07:02.090  5637  5683 D BluetoothAdapter: STATE_ON
,09-27 07:07:02.092  4600  4859 D BtGatt.GattService: registerClient() - UUID=17abe011-aa89-463f-b76b-806e36a8a9b5
,09-27 07:07:02.092  4600  4688 D BtGatt.GattService: onClientRegistered() - UUID=17abe011-aa89-463f-b76b-806e36a8a9b5, clientIf=5
,09-27 07:07:02.093  5637  5647 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-27 07:07:02.093  4600  4690 D BtGatt.AdvertiseManager: message : 0
,09-27 07:07:02.095  4600  4690 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 07:07:02.103  4600  4688 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 07:07:02.108  4600  4688 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 07:07:02.108  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 07:07:02.108  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-27 07:07:02.109  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 07:07:02.110  5637  5683 I io.jxcore.node.ConnectionHelper: start: OK
09-27 07:07:02.110  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 07:07:02.111  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 07:07:02.111  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-27 07:07:02.111  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-27 07:07:02.111  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 07:07:02.111  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 07:07:02.113  5637  5637 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 07:07:02.113  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 07:07:02.611  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 07:07:02.611  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 07:07:02.612  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 07:07:02.612  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 07:07:02.613  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 07:07:02.613  5637  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 07:07:02.613  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 07:07:02.613  5637  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 07:07:02.613  5637  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-27 07:07:02.613  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 07:07:02.613   927  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
09-27 07:07:02.613  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-27 07:07:02.617  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be126c9 removed from the list
09-27 07:07:02.617  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 07:07:02.616  5637  5637 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-27 07:07:02.617  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-27 07:07:02.617  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 07:07:02.617  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 07:07:02.617  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 07:07:02.618  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 07:07:02.618  5637  5637 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 07:07:02.619  5637  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
,09-27 07:07:02.619  5637  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
09-27 07:07:02.619  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:02.620  5637  5683 D BluetoothLeScanner: could not find callback wrapper
09-27 07:07:02.620  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 07:07:02.620  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 07:07:02.620  5637  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
09-27 07:07:02.622  4600  4690 D BtGatt.AdvertiseManager: message : 1
09-27 07:07:02.623  5637  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
09-27 07:07:02.623  4600  4819 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-27 07:07:02.623  4600  4690 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 07:07:02.635  4600  4688 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-27 07:07:02.635  4600  4688 D BtGatt.GattService: Client app is not null!
,09-27 07:07:02.637  4600  4613 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 07:07:02.637  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 07:07:02.638  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-27 07:07:02.638  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-27 07:07:02.638  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-27 07:07:02.638  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 07:07:02.642  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:02.642  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-27 07:07:02.642  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 07:07:02.643  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 07:07:02.645  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 07:07:02.645  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@124f1ce removed from the list
09-27 07:07:02.645  5637  5683 D io.jxcore.node.ConnectivityMonitor: stop
09-27 07:07:02.645  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 07:07:02.645  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 07:07:02.645  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:02.648  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,09-27 07:07:02.650  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-27 07:07:02.650  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 07:07:02.651  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 07:07:02.652  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 07:07:02.652  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 07:07:02.652  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-27 07:07:02.652  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 07:07:02.652  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 07:07:02.653  5637  5695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:02.654  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,09-27 07:07:02.652  4859  4859 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[28560]" dev="sockfs" ino=28560 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 07:07:02.652  4859  4859 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28560]" dev="sockfs" ino=28560 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 07:07:02.654  5637  5683 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-27 07:07:02.655  5637  5683 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 07:07:02.655  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 07:07:02.655  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 07:07:02.655  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 07:07:02.657  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
09-27 07:07:02.657  5637  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-27 07:07:02.666  5637  5683 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
09-27 07:07:02.668  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 07:07:02.668  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 07:07:02.668  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-27 07:07:02.668  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-27 07:07:02.669  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 07:07:02.669  5637  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 07:07:02.670  5637  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 07:07:02.670  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 07:07:02.670  5637  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 07:07:02.670  5637  5683 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be126c9 not in the list
09-27 07:07:02.670  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 07:07:02.670  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 07:07:02.670  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 07:07:02.670  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 07:07:02.670  5637  5637 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 07:07:02.670  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-27 07:07:02.670  5637  5683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 07:07:02.670  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 07:07:02.671  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:02.672  5637  5683 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@124f1ce not in the list
09-27 07:07:02.672  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 07:07:02.672  5637  5683 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 07:07:02.672  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 07:07:02.672  5637  5683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 07:07:02.672  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 07:07:02.672  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:02.673  5637  5683 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
09-27 07:07:02.674  5637  5683 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-27 07:07:02.674  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-27 07:07:02.674  5637  5683 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-27 07:07:02.674  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 07:07:02.674  5637  5683 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-27 07:07:02.674  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 07:07:02.674  5637  5683 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
09-27 07:07:02.675  5637  5683 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,09-27 07:07:02.676  5637  5683 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
09-27 07:07:02.677  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-27 07:07:02.677  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-27 07:07:02.678  5637  5683 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
09-27 07:07:02.678  5637  5683 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-27 07:07:02.678  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 07:07:02.678  5637  5683 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-27 07:07:02.678  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 07:07:02.678  5637  5683 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-27 07:07:02.678  5637  5683 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-27 07:07:02.679  5637  5683 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-27 07:07:02.679  5637  5683 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-27 07:07:02.679  5637  5683 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-27 07:07:02.680  5637  5683 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
09-27 07:07:02.680  5637  5683 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-27 07:07:02.680  5637  5683 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-27 07:07:02.680  5637  5683 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-27 07:07:02.681  5637  5683 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-27 07:07:02.681  5637  5683 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
09-27 07:07:02.682  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 07:07:02.682  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5976a7e added. We now have 3 listener(s)
09-27 07:07:02.684  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 07:07:02.684  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 07:07:02.684  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 07:07:02.684  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 07:07:02.684  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5eebdf added. We now have 3 listener(s)
09-27 07:07:02.684  5637  5683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 07:07:02.685  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 07:07:02.689  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 07:07:02.693  5637  5683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 07:07:02.693  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:02.693  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:02.693  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:02.693  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:02.693  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 07:07:02.693  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 07:07:02.693  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 07:07:02.694  5637  5683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 07:07:02.695  5637  5683 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 07:07:02.696  5637  5683 D BluetoothAdapter: enable(): BT is already enabled..!
09-27 07:07:02.697   927  3858 D WifiService: setWifiEnabled: true pid=5637, uid=10077
09-27 07:07:02.697   927  3858 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 07:07:02.697  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:02.698  5637  5683 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,09-27 07:07:02.700  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:02.701  5637  5683 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
09-27 07:07:02.702  5637  5683 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-27 07:07:02.704   927  3424 D WifiService: setWifiEnabled: false pid=5637, uid=10077
09-27 07:07:02.704   927  3424 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 07:07:02.707   927  2980 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-27 07:07:02.707   927  2980 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-27 07:07:02.707   927  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 07:07:02.707   927  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 07:07:02.715   927  5397 D DhcpClient: Clearing IP address
,09-27 07:07:02.715   506   921 D CommandListener: Clearing all IP addresses on wlan0
,09-27 07:07:02.718   506   921 D CommandListener: Setting iface cfg
,09-27 07:07:02.719   927  5398 D DhcpClient: Receive thread stopped
,09-27 07:07:02.727  3589  5451 V NativeCrypto: Read error: ssl=0x7f7fb2d000: I/O error during system call, Connection timed out
09-27 07:07:02.729   927  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-27 07:07:02.729  3589  5451 V NativeCrypto: SSL shutdown failed: ssl=0x7f7fb2d000: I/O error during system call, Broken pipe
09-27 07:07:02.729   927  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-27 07:07:02.734   927   927 D RttService: SCAN_AVAILABLE : 1
09-27 07:07:02.735   533   533 E Parcel  : Reading a NULL string not supported here.
09-27 07:07:02.735   927  3088 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-27 07:07:02.737   927  2982 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-27 07:07:02.740  3767  3916 W QCNEJ   : |CORE| network lost: 100
,09-27 07:07:02.740  3767  3916 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-27 07:07:02.740   927  2980 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-27 07:07:02.745   927  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 07:07:02.769   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 07:07:02.790   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 07:07:02.790   506   921 D CommandListener: Clearing all IP addresses on wlan0
09-27 07:07:02.791   927  2982 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-27 07:07:02.791   927  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-27 07:07:02.791   506   921 D TetherController: Setting IP forward enable = 0
09-27 07:07:02.794   927  2980 D DhcpClient: doQuit
,09-27 07:07:02.794   927  2980 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-27 07:07:02.794   927  5397 D DhcpClient: onQuitting
09-27 07:07:02.796   927   944 D Tethering: MasterInitialState.processMessage what=3
09-27 07:07:02.796  3457  3457 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-27 07:07:02.798  5278  5278 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@82edc8f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-27 07:07:02.802  5060  5084 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-27 07:07:02.802  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:02.802  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:02.802  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:02.802  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 07:07:02.802  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:02.802  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:02.802  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:02.802  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:02.802  5060  5084 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 07:07:02.802  5060  5084 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-27 07:07:02.802  5060  5084 E SarControlService: no key has been found,reset the power
09-27 07:07:02.803  5060  5096 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 07:07:02.803  5060  5096 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 07:07:02.803  3738  3738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 07:07:02.804  5060  5096 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 07:07:02.804  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:02.805  5085  5085 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 07:07:02.806  5085  5085 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 07:07:02.809  5060  5096 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 07:07:02.809  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:02.809  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:02.809  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:02.809  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 07:07:02.809  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:02.809  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:02.809  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:02.809  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:02.809  5060  5096 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-27 07:07:02.809  5060  5096 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 07:07:02.812  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:02.815  5085  5099 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@39bc1ad HexData = [00000000ea03000000000000ffffffff]
09-27 07:07:02.815  5085  5099 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 07:07:02.815  5085  5099 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-27 07:07:02.810  5085  5085 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 07:07:02.816  5085  5085 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 07:07:02.816  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:02.816  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:02.816  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:02.816  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 07:07:02.816  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:02.816  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:02.816  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:02.816  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:02.817  3738  3738 D SystemUpdateService: onCreate
09-27 07:07:02.817  5085  5085 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 07:07:02.819  5060  5070 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 07:07:02.819  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:02.820  5085  5099 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@39bc1ad HexData = [00000000eb03000000000000ffffffff]
09-27 07:07:02.820  5085  5099 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 07:07:02.820  5085  5099 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-27 07:07:02.820  3457  3457 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-27 07:07:02.820  5085  5085 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-27 07:07:02.821  5060  5071 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 07:07:02.822  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:02.824  3738  3738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-27 07:07:02.825  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:02.826  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:02.827  3457  3457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-27 07:07:02.835  3738  3738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-27 07:07:02.839  3738  5710 I SystemUpdateService: active receiver: enabled
,09-27 07:07:02.843  3738  3738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 07:07:02.844  3738  3738 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 07:07:02.846  5423  5423 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 07:07:02.852  5423  5423 D SprintDMHelper: simOperator: 
09-27 07:07:02.852  5423  5423 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 07:07:02.858   506   921 E Netd    : netlink response contains error (No such file or directory)
,09-27 07:07:02.859   506   921 D TetherController: Setting IP forward enable = 0
,09-27 07:07:02.863  3738  5421 I iu.UploadsManager: num queued entries: 0
,09-27 07:07:02.865  5034  5717 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-27 07:07:02.867  3738  5421 I iu.UploadsManager: num updated entries: 0
09-27 07:07:02.868  3738  5421 I iu.SyncManager: NEXT; no task
,09-27 07:07:02.868  3738  5710 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 07:07:02.870  3738  5710 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-27 07:07:02.870  3738  5710 I SystemUpdateService: now status is 0 (complete)
09-27 07:07:02.870  3738  5710 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 07:07:02.870  3738  5710 I SystemUpdateService: file has been verified
09-27 07:07:02.871  3738  5710 I SystemUpdateService: OTA package size = 21989297
,09-27 07:07:02.876  3457  3457 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-27 07:07:02.876   927  3693 I ActivityManager: Start proc 5720:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-27 07:07:02.877  3738  5710 I SystemUpdateService: showing system update notification
,09-27 07:07:02.891  3738  3738 D SystemUpdateService: onDestroy
,09-27 07:07:02.892  3457  3457 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 07:07:02.921  5720  5720 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-27 07:07:02.929   927  3424 I ActivityManager: Killing 4999:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-27 07:07:02.994   927  2980 D wifi    : In wifi stop Hal
,09-27 07:07:02.994   927  2980 D wifi    : halHandle = 0x7f6e00d680, mVM = 0x7f8a68d140, mCls = 0x100a02
,09-27 07:07:02.995   927  3456 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 07:07:02.995   927  3456 D WifiHAL : Got a signal to exit!!!
09-27 07:07:02.995   927  3456 I WifiHAL : Exit wifi_event_loop
09-27 07:07:02.996   927  2980 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-27 07:07:02.996   927  2980 E WifiHAL : Event processing terminated
09-27 07:07:02.997   927  2980 D wifi    : In wifi cleaned up handler
09-27 07:07:02.997   927  2980 I WifiHAL : Internal cleanup completed
09-27 07:07:02.998  5034  5034 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 07:07:03.002  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:03.004  4090  4237 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 07:07:03.005  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:03.006  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:03.023   927  3456 D wifi    : set interface wlan0 flags (DOWN)
,09-27 07:07:03.023   927  2980 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 07:07:03.172  5637  5637 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 07:07:03.211  5637  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:03.216   927   938 D WifiService: setWifiEnabled: true pid=5637, uid=10077
09-27 07:07:03.216   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 07:07:03.230   506   921 D SoftapController: Softap fwReload - Ok
,09-27 07:07:03.232   927   944 D Tethering: InitialState.processMessage what=4
09-27 07:07:03.237   506   921 D CommandListener: Setting iface cfg
,09-27 07:07:03.237   506   921 D CommandListener: Trying to bring down wlan0
,09-27 07:07:03.239   506   921 D CommandListener: Clearing all IP addresses on wlan0
09-27 07:07:03.241   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 07:07:03.245   927  2980 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 07:07:03.721   927  3858 D WifiService: setWifiEnabled: true pid=5637, uid=10077
,09-27 07:07:03.724   927  3858 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 07:07:03.855   927  2980 D wifi    : set interface wlan0 flags (UP)
,09-27 07:07:03.855   927  2980 I WifiHAL : Initializing wifi
,09-27 07:07:03.856   927  2980 I WifiHAL : Creating socket
,09-27 07:07:03.859   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-27 07:07:03.865   927  2980 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-27 07:07:03.865   927  2980 D wifi    : Did set static halHandle = 0x7f6e00d680
09-27 07:07:03.865   927  2980 D wifi    : halHandle = 0x7f6e00d680, mVM = 0x7f8a68d140, mCls = 0x101926
09-27 07:07:03.866   927  2980 D wifi    : array field set
,09-27 07:07:03.866   927  2980 I WifiNative-HAL: interface[0] = wlan0
09-27 07:07:03.868   927  5735 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547306395264
09-27 07:07:03.868   927  5735 D wifi    : waitForHalEvents called, vm = 0x7f8a68d140, obj = 0x101926, env = 0x7f73363480
,09-27 07:07:03.961  5736  5736 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 07:07:03.969   927  2980 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-27 07:07:03.978  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:03.982  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:03.983  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:03.985  5736  5736 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 07:07:03.994  5736  5736 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-27 07:07:03.994  5736  5736 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 07:07:04.010   927  2980 D WifiConfigStore: Loading config and enabling all networks 
,09-27 07:07:04.014  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:04.014  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:04.014  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:04.014  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:04.014  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:04.014  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:04.014  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:04.014  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:04.017  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:04.020  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:04.020  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:04.020  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:04.020  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:04.020  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:04.020  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:04.020  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:04.020  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:04.022  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:04.023   927  2980 D WifiConfigStore: loaded 0 passpoint configs
09-27 07:07:04.024   927  2980 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 07:07:04.024   927  2980 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-27 07:07:04.025  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:04.025  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:04.025  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:04.025  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:04.025  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:04.025  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:04.025  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:04.025  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:04.025   927  2980 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-27 07:07:04.026  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:04.026   927  2980 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 07:07:04.027   927  2980 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 07:07:04.027   927  2980 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 07:07:04.027   927  2980 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 07:07:04.031   927  2980 D WifiNative-HAL: Setting external_sim to 1
,09-27 07:07:04.031  5034  5034 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 07:07:04.031   927  2980 D wifi    : setting dfs flag to true, 0x7f7507f960
09-27 07:07:04.032   927  2980 D WifiStateMachine: Setting OUI to DA-A1-19
09-27 07:07:04.032   927  2980 D wifi    : setting scan oui 0x7f7507f960
09-27 07:07:04.032   927  2980 D WifiHAL : Sending mac address OUI
,09-27 07:07:04.036   927  2980 E native  : do suspend false
,09-27 07:07:04.043   927  2980 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-27 07:07:04.043   927   927 D RttService: SCAN_AVAILABLE : 3
09-27 07:07:04.043   927  3088 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-27 07:07:04.043   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-27 07:07:04.044   506   921 D CommandListener: Setting iface cfg
,09-27 07:07:04.047   927  2963 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-27 07:07:04.047   927  2963 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 07:07:04.056   927  2963 D WifiNative-HAL: p2pGetDeviceAddress
,09-27 07:07:04.061   927  2963 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-27 07:07:04.061   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=142942 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-27 07:07:04.230  5637  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:04.241  4600  4684 D BluetoothAdapterState: Current state: ON, message: 23
,09-27 07:07:04.241  4600  4684 D BluetoothAdapterProperties: Setting state to 13
,09-27 07:07:04.242  4600  4684 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-27 07:07:04.243  4600  4684 D BluetoothAdapterProperties: onBluetoothDisable()
09-27 07:07:04.244  4600  4684 I BluetoothAdapterState: Entering PendingCommandState
,09-27 07:07:04.246  4600  4600 D BluetoothMapService: onReceive
,09-27 07:07:04.246  4600  4600 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 07:07:04.246  4600  4600 D BluetoothMapService: STATE_TURNING_OFF
,09-27 07:07:04.246  4600  4600 D BluetoothMapService: MAP Service closeService in
09-27 07:07:04.247  4600  4600 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 07:07:04.247  4600  4600 D ObexServerSockets0: shutdown(block = true)
,09-27 07:07:04.247  4600  4600 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 07:07:04.248  4600  4600 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 07:07:04.248  4600  4861 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-27 07:07:04.249  4600  4860 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-27 07:07:04.249  4600  4819 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-27 07:07:04.252  4600  4600 I BtOppRfcommListener: stopping Accept Thread
,09-27 07:07:04.253  4600  5335 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-27 07:07:04.253  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:04.253  4600  5335 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-27 07:07:04.253  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:04.253  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:04.253  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:04.253  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:04.253  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 07:07:04.253  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:04.253  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:04.253  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:04.255  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:04.255  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:04.259  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:04.259  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:04.259  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:04.259  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:04.259  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:04.259  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 07:07:04.259  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:04.259  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:04.259  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:04.261  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:04.262  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:04.265  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:04.265  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:04.265  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:04.265  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:04.265  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:04.265  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 07:07:04.265  5637  5637 V io.,jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:04.265  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:04.265  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:04.266  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:04.266  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:04.271   927   940 I ActivityManager: Start proc 5740:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-27 07:07:04.272  4600  4688 D BluetoothAdapterProperties: Scan Mode:20
09-27 07:07:04.272  4600  4684 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 07:07:04.275  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:04.277  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:04.279  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:04.281  4600  4600 D HeadsetService: Received stop request...Stopping profile...
09-27 07:07:04.283   927   927 D BluetoothHeadset: Proxy object disconnected
09-27 07:07:04.283   927   927 D BluetoothHeadset: Proxy object disconnected
09-27 07:07:04.284   927   927 D BluetoothHeadset: Proxy object disconnected
09-27 07:07:04.284  3124  3951 D BluetoothHeadset: Proxy object disconnected
,09-27 07:07:04.284  3124  3124 D HeadsetProfile: Bluetooth service disconnected
09-27 07:07:04.285  3814  3843 D BluetoothHeadset: Proxy object disconnected
,09-27 07:07:04.286  4600  4600 D A2dpService: Received stop request...Stopping profile...
,09-27 07:07:04.287  4600  4841 D A2dpStateMachine: Exit Disconnected: -1
,09-27 07:07:04.288   927   927 D BluetoothA2dp: Proxy object disconnected
09-27 07:07:04.290  4600  4600 D HidService: Received stop request...Stopping profile...
09-27 07:07:04.290  3124  3124 D BluetoothA2dp: Proxy object disconnected
09-27 07:07:04.291  4600  4600 D HidService: Stopping Bluetooth HidService
09-27 07:07:04.292  3124  3124 D BluetoothInputDevice: Proxy object disconnected
09-27 07:07:04.292  3124  3124 D HidProfile: Bluetooth service disconnected
09-27 07:07:04.295  4600  4600 D HealthService: Received stop request...Stopping profile...
,09-27 07:07:04.297  4600  4600 D PanService: Received stop request...Stopping profile...
,09-27 07:07:04.298  3124  3124 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 07:07:04.298  3124  3124 D PanProfile: Bluetooth service disconnected
,09-27 07:07:04.300  4600  4600 V BluetoothAdapterState: isTurningOff()=true
,09-27 07:07:04.300  4600  4600 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:04.300  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:04.300  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:04.301  4600  4600 D BluetoothMapService: Received stop request...Stopping profile...
09-27 07:07:04.301  4600  4600 D BluetoothMapService: stop()
,09-27 07:07:04.302  4600  4600 D BluetoothMapAppObserver: deinitObservers()
09-27 07:07:04.302  4600  4600 D BluetoothMapAppObserver: removeReceiver()
09-27 07:07:04.303  3124  3124 D BluetoothMap: Proxy object disconnected
09-27 07:07:04.303  3124  3124 D MapProfile: Bluetooth service disconnected
,09-27 07:07:04.306  4600  4600 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-27 07:07:04.306  4600  4600 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 07:07:04.306  4600  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:04.306  4600  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:04.306  4600  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:04.306  4600  4688 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-27 07:07:04.306  4600  4688 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-27 07:07:04.307  4600  4600 D SapService: Received stop request...Stopping profile...
09-27 07:07:04.307  4600  4600 V SapService: stop()
09-27 07:07:04.308  4600  4600 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:04.308  4600  4600 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:04.308  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:04.308  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 07:07:04.310  4600  4688 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-27 07:07:04.310  4600  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:04.310  4600  4600 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:04.310  4600  4600 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:04.310  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:04.310  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:04.310  4600  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:04.311  4600  4807 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 07:07:04.311  4600  4807 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 07:07:04.311  4600  4807 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 07:07:04.311  4600  4600 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 07:07:04.311  4600  4807 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 07:07:04.311  4600  4600 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 07:07:04.311  4600  4688 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 07:07:04.311  4600  4600 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:04.311  4600  4600 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:04.311  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:04.311  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:04.311  4600  4600 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-27 07:07:04.312  4600  4688 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-27 07:07:04.312  4600  4600 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 07:07:04.312  4600  4600 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:04.312  4600  4600 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:04.312  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:04.312  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:04.312  4600  4600 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 07:07:04.313  4600  4600 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-27 07:07:04.314  4600  4600 D BluetoothMapService: MAP Service closeService in
09-27 07:07:04.314  4600  4600 V BluetoothAdapterState: isTurningOff()=true
,09-27 07:07:04.315  4600  4600 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:04.315  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:04.315  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:04.315  4600  4600 D BluetoothMapService: cleanup()
09-27 07:07:04.315  4600  4600 D BluetoothMapService: MAP Service closeService in
09-27 07:07:04.315  4600  4600 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:04.315  4600  4600 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:04.315  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:04.315  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:04.316  4600  4684 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 07:07:04.316  4600  4684 D BluetoothAdapterProperties: Setting state to 15
09-27 07:07:04.316  4600  4684 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 07:07:04.316  4600  4684 I BluetoothAdapterState: Entering BleOnState
09-27 07:07:04.316  3124  3136 D BluetoothPan: onBluetoothStateChange on: false
,09-27 07:07:04.317  3124  3135 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 07:07:04.318  3124  3951 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 07:07:04.319   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 07:07:04.319   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 07:07:04.319  3124  3978 D BluetoothMap: onBluetoothStateChange: up=false
09-27 07:07:04.320  3814  3836 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 07:07:04.320  3124  3136 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 07:07:04.321   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 07:07:04.321  3124  3135 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 07:07:04.321   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 07:07:04.322  4600  4684 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 07:07:04.322  4600  4684 D BluetoothAdapterProperties: Setting state to 16
09-27 07:07:04.322  4600  4684 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 07:07:04.322  4600  4684 D BluetoothAdapterProperties: onBleDisable
09-27 07:07:04.323  4600  4684 I BluetoothAdapterState: Entering PendingCommandState
09-27 07:07:04.323  4600  4685 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 07:07:04.324  4600  4688 D BluetoothAdapterProperties: Scan Mode:20
09-27 07:07:04.324  4600  4807 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 07:07:04.324  4600  4807 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:04.324  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:04.327  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:04.328  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:04.330  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:04.331  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:04.331  5740  5740 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-27 07:07:04.332  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:04.347  5740  5740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 07:07:04.351   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bb80b96:true
,09-27 07:07:04.353  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 07:07:04.366   927   937 I ActivityManager: Start proc 5752:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-27 07:07:04.374  5740  5740 D LocalBluetoothProfileManager: Adding local MAP profile
,09-27 07:07:04.377  5740  5740 D BluetoothMap: Create BluetoothMap proxy object
,09-27 07:07:04.392  5740  5740 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-27 07:07:04.400  5752  5752 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-27 07:07:04.405  5740  5740 D DockEventReceiver: finishStartingService: stopping service
,09-27 07:07:04.413   927  3858 I ActivityManager: Killing 5278:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-27 07:07:04.531  4600  4688 I bt_hci  : shut_down
,09-27 07:07:04.535  4600  4692 D bt_hwcfg: hw_epilog_process
,09-27 07:07:04.535  4600  4692 I bt_vendor: low_power_mode_cb
,09-27 07:07:04.537  4600  4692 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-27 07:07:04.538  4600  4692 I bt_vendor: epilog_cb
09-27 07:07:04.538  4600  4692 I bt_hci  : epilog_finished_callback
,09-27 07:07:04.540  4600  4688 I bt_hci_h4: hal_close
,09-27 07:07:04.541  4600  4688 I bt_userial_vendor: device fd = 54 close
,09-27 07:07:04.597  5752  5752 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-27 07:07:04.597  5752  5752 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 07:07:04.597  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 07:07:04.598  5752  5752 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 07:07:04.598  5752  5752 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 07:07:04.598  5752  5752 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.k.d(PG:583)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 07:07:04.598  5752  5752 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 07:07:04.598  5752  5752 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 07:07:04.598  5752  5752 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 07:07:04.598  5752  5752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 07:07:04.611  5740  5740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 07:07:04.618  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 07:07:04.631  5740  5740 D DockEventReceiver: finishStartingService: stopping service
09-27 07:07:04.635   927   937 I ActivityManager: Killing 4698:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-27 07:07:04.671  4600  4685 D bt_stack_manager: event_shut_down_stack finished.
09-27 07:07:04.671  4600  4684 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-27 07:07:04.673  4600  4684 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-27 07:07:04.673  4600  4600 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 07:07:04.674  4600  4600 D BtGatt.GattService: Received stop request...Stopping profile...
,09-27 07:07:04.674  4600  4600 D BtGatt.GattService: stop()
09-27 07:07:04.674  4600  4600 D BtGatt.AdvertiseManager: advertise clients cleared
09-27 07:07:04.675  4600  4600 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:04.675  4600  4600 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:04.675  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:04.675  4600  4600 V BluetoothAdapterState: isBleTurningOff()=true
09-27 07:07:04.676  4600  4684 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-27 07:07:04.676  4600  4684 D BluetoothAdapterProperties: Setting state to 10
09-27 07:07:04.676  4600  4684 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 07:07:04.677  4600  4684 I BluetoothAdapterState: Entering OffState
09-27 07:07:04.677   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-27 07:07:04.690  4600  4600 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-27 07:07:04.690  4600  4600 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 07:07:04.690  4600  4600 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 07:07:04.691  4600  4685 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-27 07:07:04.699  4600  4600 I art     : System.exit called, status: 0
09-27 07:07:04.700  4600  4600 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 07:07:04.730   927  3877 I ActivityManager: Process com.android.bluetooth (pid 4600) has died
,09-27 07:07:04.739  5637  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:04.751   927   944 I ActivityManager: Start proc 5784:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 07:07:04.809  5784  5784 D AdapterServiceConfig: Adding HeadsetService
,09-27 07:07:04.809  5784  5784 D AdapterServiceConfig: Adding A2dpService
09-27 07:07:04.809  5784  5784 D AdapterServiceConfig: Adding HidService
09-27 07:07:04.809  5784  5784 D AdapterServiceConfig: Adding HealthService
09-27 07:07:04.809  5784  5784 D AdapterServiceConfig: Adding PanService
09-27 07:07:04.810  5784  5784 D AdapterServiceConfig: Adding GattService
09-27 07:07:04.810  5784  5784 D AdapterServiceConfig: Adding BluetoothMapService
,09-27 07:07:04.810  5784  5784 D AdapterServiceConfig: Adding SapService
,09-27 07:07:04.817   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40006cc:true
,09-27 07:07:04.817  5784  5784 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 07:07:04.819  5784  5784 I bt_bluedroid: init
,09-27 07:07:04.819  5784  5796 I BluetoothAdapterState: Entering OffState
,09-27 07:07:04.821  5784  5797 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-27 07:07:04.821  5784  5797 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 07:07:04.821  5784  5797 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 07:07:04.822  5784  5797 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 07:07:04.822  5784  5784 I bt_bluedroid: get_profile_interface socket
,09-27 07:07:04.823  5784  5784 I bt_bluedroid: get_profile_interface sdp
,09-27 07:07:04.823  5784  5800 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-27 07:07:04.824  5784  5800 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 07:07:04.826  5784  5795 I bt_bluedroid: config_hci_snoop_log
,09-27 07:07:04.826   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-27 07:07:04.829  5784  5796 D BluetoothAdapterState: Current state: OFF, message: 0
,09-27 07:07:04.829  5784  5796 D BluetoothAdapterProperties: Setting state to 14
09-27 07:07:04.829  5784  5796 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-27 07:07:04.831  5784  5796 D BluetoothBondStateMachine: make
,09-27 07:07:04.832  5784  5801 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 07:07:04.834  5784  5796 I BluetoothAdapterState: Entering PendingCommandState
,09-27 07:07:04.835  5784  5784 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 07:07:04.836  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
,09-27 07:07:04.837  5784  5784 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 07:07:04.837  5784  5784 D BtGatt.GattService: Received start request. Starting profile...
09-27 07:07:04.837  5784  5784 D BtGatt.GattService: start()
09-27 07:07:04.837  5784  5784 I bt_bluedroid: get_profile_interface gatt
,09-27 07:07:04.838  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:04.838  5784  5784 D BtGatt.AdvertiseManager: advertise manager created
,09-27 07:07:04.842  5784  5784 V BluetoothAdapterState: isTurningOff()=false
,09-27 07:07:04.842  5784  5784 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:04.842  5784  5784 V BluetoothAdapterState: isBleTurningOn()=true
09-27 07:07:04.842  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 07:07:04.842  5784  5796 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 07:07:04.843  5784  5796 I bt_bluedroid: bt_bluedroid
09-27 07:07:04.844  5784  5797 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-27 07:07:04.844  5784  5797 I bt_hci  : start_up
,09-27 07:07:04.848  5784  5797 I bt_vendor: alloc value 0xf3d95871
,09-27 07:07:04.848  5784  5797 I bt_vendor: init
09-27 07:07:04.848  5784  5797 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 07:07:04.849  5784  5797 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 07:07:04.852  5752  5772 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-27 07:07:04.863   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af8f9cd:true
,09-27 07:07:04.957  5784  5797 D bt_hci  : start_up starting async portion
09-27 07:07:04.957  5784  5804 I bt_hci  : event_finish_startup
,09-27 07:07:04.957  5784  5804 I bt_hci_h4: hal_open
09-27 07:07:04.957  5784  5804 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-27 07:07:04.952  5807  5807 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-27 07:07:04.959  5784  5804 I bt_userial_vendor: device fd = 54 open
,09-27 07:07:04.971  5784  5804 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 07:07:04.973  5784  5804 D bt_hwcfg: Chipset BCM4358A3
,09-27 07:07:04.973  5784  5804 D bt_hwcfg: Target name = [BCM4358A3]
09-27 07:07:04.974  5784  5804 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 07:07:05.248  5784  5796 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-27 07:07:05.373  5784  5804 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-27 07:07:05.374  5784  5804 D bt_hwcfg: Settlement delay -- 100 ms
09-27 07:07:05.374  5784  5804 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 07:07:05.498  5784  5804 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-27 07:07:05.498  5784  5804 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-27 07:07:05.500  5784  5804 I bt_hwcfg: vendor lib fwcfg completed
09-27 07:07:05.500  5784  5804 I bt_vendor: firmware callback
09-27 07:07:05.500  5784  5804 I bt_hci  : firmware_config_callback
,09-27 07:07:05.510  5784  5809 I bt_btu  : btu_task pending for preload complete event
,09-27 07:07:05.510  5784  5809 I bt_btu_task: Bluetooth chip preload is complete
,09-27 07:07:05.510  5784  5809 I bt_btu  : btu_task received preload complete event
,09-27 07:07:05.516  5784  5809 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 07:07:05.516  5784  5809 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-27 07:07:05.516  5784  5809 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-27 07:07:05.517  5784  5809 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-27 07:07:05.517  5784  5809 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-27 07:07:05.517  5784  5809 I         : BTE_InitTraceLevels -- TRC_A2D
09-27 07:07:05.517  5784  5809 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-27 07:07:05.517  5784  5809 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 07:07:05.517  5784  5809 I         : BTE_InitTraceLevels -- TRC_GAP
09-27 07:07:05.517  5784  5809 I         : BTE_InitTraceLevels -- TRC_PAN
09-27 07:07:05.517  5784  5809 I         : BTE_InitTraceLevels -- TRC_SDP
,09-27 07:07:05.518  5784  5809 I         : BTE_InitTraceLevels -- TRC_GATT
,09-27 07:07:05.518  5784  5809 I         : BTE_InitTraceLevels -- TRC_SMP
,09-27 07:07:05.518  5784  5809 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 07:07:05.518  5784  5809 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 07:07:05.603  5784  5809 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d13549
09-27 07:07:05.604  5784  5809 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d13549 
,09-27 07:07:05.623  5784  5800 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 07:07:05.624  5784  5800 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 07:07:05.625  5784  5800 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 07:07:05.627  5784  5800 D BluetoothAdapterProperties: Name is: Nexus 6P
09-27 07:07:05.630  5784  5800 D BluetoothAdapterProperties: Scan Mode:20
09-27 07:07:05.630  5784  5800 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 07:07:05.630  5784  5800 D bt_hci  : do_postload posting postload work item
09-27 07:07:05.630  5784  5804 I bt_hci  : event_postload
09-27 07:07:05.630  5784  5804 I bt_vendor: sco_config_cb
,09-27 07:07:05.630  5784  5804 I bt_hci  : sco_config_callback postload finished.
09-27 07:07:05.633  5784  5800 D bt_bte_conf: Device ID record 1 : primary
,09-27 07:07:05.633  5784  5800 D bt_bte_conf:   vendorId            = 000f
09-27 07:07:05.633  5784  5800 D bt_bte_conf:   vendorIdSource      = 0001
09-27 07:07:05.633  5784  5800 D bt_bte_conf:   product             = 1200
09-27 07:07:05.633  5784  5800 D bt_bte_conf:   version             = 1436
09-27 07:07:05.633  5784  5800 D bt_bte_conf:   clientExecutableURL = 
09-27 07:07:05.633  5784  5800 D bt_bte_conf:   serviceDescription  = 
09-27 07:07:05.633  5784  5800 D bt_bte_conf:   documentationURL    = 
09-27 07:07:05.634  5784  5800 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-27 07:07:05.634  5784  5797 D bt_stack_manager: event_start_up_stack finished
09-27 07:07:05.636  5784  5796 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 07:07:05.636  5784  5796 D BluetoothAdapterProperties: Setting state to 15
09-27 07:07:05.636  5784  5796 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 07:07:05.636  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.638  5784  5796 I BluetoothAdapterState: Entering BleOnState
09-27 07:07:05.641  5784  5804 I bt_vendor: low_power_mode_cb
09-27 07:07:05.642  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.645  5784  5796 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-27 07:07:05.645  5784  5796 D BluetoothAdapterProperties: Setting state to 11
09-27 07:07:05.645  5784  5796 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 07:07:05.650  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:05.653  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:05.655  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:05.655  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:05.656  5784  5784 D HeadsetService: Received start request. Starting profile...
,09-27 07:07:05.660  5784  5784 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 07:07:05.660  5784  5784 D HeadsetStateMachine: make
09-27 07:07:05.660  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:05.672  5784  5784 D HeadsetStateMachine: max_hf_connections = 1
,09-27 07:07:05.672  5784  5796 I BluetoothAdapterState: Entering PendingCommandState
09-27 07:07:05.672  5784  5784 I bt_bluedroid: get_profile_interface handsfree
09-27 07:07:05.672  5784  5800 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 07:07:05.672  5784  5800 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-27 07:07:05.675  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
,09-27 07:07:05.676  5784  5784 D A2dpService: Received start request. Starting profile...
,09-27 07:07:05.676  5784  5784 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 07:07:05.677  5784  5784 I bt_bluedroid: get_profile_interface avrcp
,09-27 07:07:05.682  5784  5784 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 07:07:05.682  5784  5784 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 07:07:05.683  5784  5784 D A2dpStateMachine: make
09-27 07:07:05.683  5784  5784 I bt_bluedroid: get_profile_interface a2dp
,09-27 07:07:05.685  5784  5800 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-27 07:07:05.686  5784  5817 D A2dpStateMachine: Enter Disconnected: -2
,09-27 07:07:05.687  5784  5784 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 07:07:05.688  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:05.689  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 07:07:05.689  5740  5740 D BluetoothInputDevice: Proxy object connected
09-27 07:07:05.690  5784  5784 D HidService: Received start request. Starting profile...
09-27 07:07:05.690  5784  5784 I bt_bluedroid: get_profile_interface hidhost
09-27 07:07:05.690  5784  5784 D HidService: setHidService(): set to: null
09-27 07:07:05.690  5784  5800 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cf456d
09-27 07:07:05.691  5784  5800 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 07:07:05.692  5784  5784 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 07:07:05.693  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:05.693  5784  5784 D HealthService: Received start request. Starting profile...
,09-27 07:07:05.694  5740  5740 D HidProfile: Bluetooth service connected
09-27 07:07:05.694  5784  5784 I bt_bluedroid: get_profile_interface health
09-27 07:07:05.695  5784  5784 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-27 07:07:05.696  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:05.697  5740  5740 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 07:07:05.697  5784  5784 D PanService: Received start request. Starting profile...
09-27 07:07:05.697  5784  5784 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 07:07:05.697  5784  5784 I bt_bluedroid: get_profile_interface pan
09-27 07:07:05.698  5740  5740 D PanProfile: Bluetooth service connected
,09-27 07:07:05.698  5784  5800 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-27 07:07:05.700  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
,09-27 07:07:05.701  5740  5740 D BluetoothMap: Proxy object connected
,09-27 07:07:05.702  5784  5784 D BluetoothMapService: Received start request. Starting profile...
09-27 07:07:05.702  5784  5784 D BluetoothMapService: start()
09-27 07:07:05.702  5740  5740 D MapProfile: Bluetooth service connected
09-27 07:07:05.703  5740  5740 D BluetoothMap: getConnectedDevices()
09-27 07:07:05.703  5740  5740 D BluetoothMap: Bluetooth is Not enabled
,09-27 07:07:05.704  5784  5784 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-27 07:07:05.706  5784  5784 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-27 07:07:05.706  5784  5784 D BluetoothMapAppObserver: createReceiver()
09-27 07:07:05.707  5784  5784 D BluetoothMapAppObserver: initObservers()
09-27 07:07:05.707  5784  5784 D BluetoothMapAppObserver: getEnabledAccountItems()
09-27 07:07:05.707   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:07:05.713  5784  5784 V SapService: SapBinder()
,09-27 07:07:05.713  5784  5784 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
,09-27 07:07:05.714  5784  5784 D SapService: Received start request. Starting profile...
09-27 07:07:05.714  5784  5784 V SapService: start()
,09-27 07:07:05.716  5784  5784 V BluetoothAdapterState: isTurningOff()=false
,09-27 07:07:05.716  5784  5784 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:05.716  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.716  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.716  5784  5784 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:05.716  5784  5784 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:05.716  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.716  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.716  5784  5815 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:05.717  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.718  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.718  5784  5784 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:05.718  5784  5784 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:05.718  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.718  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.718  5784  5784 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:05.718  5784  5784 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:05.718  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.719  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 07:07:05.719  5784  5796 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-27 07:07:05.719  5784  5796 D BluetoothAdapterProperties: ScanMode =  20
09-27 07:07:05.719  5784  5796 D BluetoothAdapterProperties: State =  11
09-27 07:07:05.720  5784  5800 D BluetoothAdapterProperties: Scan Mode:21
09-27 07:07:05.721  5784  5800 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-27 07:07:05.721  5784  5796 D BluetoothAdapterProperties: Setting state to 12
09-27 07:07:05.721  5784  5796 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 07:07:05.722  5784  5796 I BluetoothAdapterState: Entering OnState
09-27 07:07:05.722  3124  3978 D BluetoothPan: onBluetoothStateChange on: true
09-27 07:07:05.724  3124  3124 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 07:07:05.724  3124  3124 D PanProfile: Bluetooth service connected
09-27 07:07:05.724  3124  3135 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 07:07:05.724  5637  5637 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-27 07:07:05.726  3124  3124 D BluetoothInputDevice: Proxy object connected
,09-27 07:07:05.726  3124  3135 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 07:07:05.726  3124  3124 D HidProfile: Bluetooth service connected
09-27 07:07:05.727  5637  5637 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-27 07:07:05.727   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:05.727   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:05.728  5740  5750 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-27 07:07:05.728  3124  3136 D BluetoothMap: onBluetoothStateChange: up=true
,09-27 07:07:05.730  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:05.730  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:05.730  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:05.730  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:05.730  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:05.730  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:05.730  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:05.730  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:05.731  3124  3124 D BluetoothMap: Proxy object connected
09-27 07:07:05.731  3124  3124 D MapProfile: Bluetooth service connected
09-27 07:07:05.731  3124  3124 D BluetoothMap: getConnectedDevices()
09-27 07:07:05.732  5740  5751 D BluetoothMap: onBluetoothStateChange: up=true
09-27 07:07:05.732  3814  3836 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:05.732  5784  5784 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 07:07:05.733  3124  3978 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 07:07:05.733  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:05.733  5784  5784 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-27 07:07:05.734  5784  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:05.735   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 07:07:05.736  5740  5750 D BluetoothPan: onBluetoothStateChange on: true
09-27 07:07:05.736  5784  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:05.736  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:05.736  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:05.736  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:05.736  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:05.736  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:05.736  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:05.736  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:05.736  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:05.737  5740  5751 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 07:07:05.737  5784  5784 D ObexServerSockets: Succeed to create listening sockets 
09-27 07:07:05.737  5784  5784 D ObexServerSockets0: startAccept()
,09-27 07:07:05.737  5784  5784 D ObexServerSockets0: prepareForNewConnect()
09-27 07:07:05.738  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:05.739  3124  3135 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:05.740   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:05.740  5784  5784 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 07:07:05.740  5784  5784 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 07:07:05.740  5784  5822 D ObexServerSockets0: Accepting socket connection...
09-27 07:07:05.741  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:05.741  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:05.741  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:05.741  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:05.741  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:05.741  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:05.741  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:05.741  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:05.742   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,09-27 07:07:05.744  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:05.746  5784  5823 D ObexServerSockets0: Accepting socket connection...
09-27 07:07:05.746   927   927 D BluetoothA2dp: Proxy object connected
09-27 07:07:05.746  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.747  3124  3124 D BluetoothA2dp: Proxy object connected
,09-27 07:07:05.747  5784  5784 D BluetoothMapService: onReceive
,09-27 07:07:05.747  5784  5784 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 07:07:05.747  5784  5784 D BluetoothMapService: STATE_ON
09-27 07:07:05.748  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.749  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.750  5740  5740 D LocalBluetoothProfileManager: Adding local A2DP profile
09-27 07:07:05.750  5784  5825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 07:07:05.751  5637  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.752  5784  5825 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 07:07:05.752  5784  5825 D BluetoothSdpJni: SDP Create record success - handle: 1
09-27 07:07:05.753  5637  5683 D io.jxcore.node.ConnectivityMonitor: stop
09-27 07:07:05.753  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 07:07:05.755  5637  5683 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
09-27 07:07:05.756  5637  5683 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
09-27 07:07:05.758  5740  5740 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-27 07:07:05.758  5637  5683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:05.759  5784  5796 D BluetoothAdapterState: Current state: ON, message: 23
09-27 07:07:05.759  5784  5796 D BluetoothAdapterProperties: Setting state to 13
09-27 07:07:05.759  5784  5796 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-27 07:07:05.759  5784  5796 D BluetoothAdapterProperties: onBluetoothDisable()
09-27 07:07:05.760  5784  5796 I BluetoothAdapterState: Entering PendingCommandState
09-27 07:07:05.761  5784  5784 D BluetoothMapService: onReceive
09-27 07:07:05.761  5784  5800 D BluetoothAdapterProperties: Scan Mode:20
,09-27 07:07:05.761  5784  5784 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 07:07:05.761  5784  5784 D BluetoothMapService: STATE_TURNING_OFF
09-27 07:07:05.761  5784  5796 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 07:07:05.762  5784  5784 D BluetoothMapService: MAP Service closeService in
09-27 07:07:05.762  5784  5784 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 07:07:05.762  5784  5784 D ObexServerSockets0: shutdown(block = true)
09-27 07:07:05.762  5784  5784 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 07:07:05.762  5784  5822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-27 07:07:05.762  5784  5784 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 07:07:05.762  5784  5811 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-27 07:07:05.763  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:05.763  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:05.763  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:05.763  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:05.763  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:05.763  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 07:07:05.763  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:05.763  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:05.763  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:05.763  5740  5740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 07:07:05.763  5784  5823 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-27 07:07:05.764  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:05.764  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:05.765  5784  5784 D HeadsetService: Received stop request...Stopping profile...
09-27 07:07:05.765  5740  5740 D BluetoothA2dp: Proxy object connected
09-27 07:07:05.766  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:05.766  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:05.766  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:05.766  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:05.766  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:05.766  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 07:07:05.766  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:05.766  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:05.766  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:05.767  5637  5637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:05.767  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:05.769  5784  5784 D A2dpService: Received stop request...Stopping profile...
09-27 07:07:05.769  5784  5817 D A2dpStateMachine: Exit Disconnected: -1
09-27 07:07:05.770  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.771   927   927 D BluetoothA2dp: Proxy object disconnected
,09-27 07:07:05.771  5740  5740 D DockEventReceiver: finishStartingService: stopping service
09-27 07:07:05.771  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.772  5740  5740 D BluetoothA2dp: Proxy object disconnected
09-27 07:07:05.772  5784  5784 D HidService: Received stop request...Stopping profile...
09-27 07:07:05.772  5784  5784 D HidService: Stopping Bluetooth HidService
09-27 07:07:05.773  5740  5740 D BluetoothInputDevice: Proxy object disconnected
09-27 07:07:05.773  5740  5740 D HidProfile: Bluetooth service disconnected
,09-27 07:07:05.775  5784  5784 D HealthService: Received stop request...Stopping profile...
09-27 07:07:05.776  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 07:07:05.776  5784  5784 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:05.776  5784  5784 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:05.776  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.776  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.778  5784  5784 D PanService: Received stop request...Stopping profile...
,09-27 07:07:05.778  3124  3124 D BluetoothA2dp: Proxy object disconnected
,09-27 07:07:05.779  3124  3124 D BluetoothInputDevice: Proxy object disconnected
09-27 07:07:05.779  3124  3124 D HidProfile: Bluetooth service disconnected
09-27 07:07:05.779  5740  5740 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 07:07:05.780  5740  5740 D PanProfile: Bluetooth service disconnected
09-27 07:07:05.781  5784  5784 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-27 07:07:05.781  5784  5784 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 07:07:05.781  5784  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:05.781  5784  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:05.781  5784  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:05.781  5784  5800 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-27 07:07:05.782  5784  5800 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,09-27 07:07:05.782  5784  5784 D BluetoothMapService: Received stop request...Stopping profile...
09-27 07:07:05.782  5784  5784 D BluetoothMapService: stop()
,09-27 07:07:05.783  5784  5784 D BluetoothMapAppObserver: deinitObservers()
09-27 07:07:05.783  5784  5784 D BluetoothMapAppObserver: removeReceiver()
09-27 07:07:05.784  5784  5784 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:05.784  5784  5784 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:05.784  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.784  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.784  5784  5784 D SapService: Received stop request...Stopping profile...
09-27 07:07:05.784  5784  5784 V SapService: stop()
09-27 07:07:05.786  5740  5740 D BluetoothMap: Proxy object disconnected
09-27 07:07:05.786  5740  5740 D MapProfile: Bluetooth service disconnected
,09-27 07:07:05.786  5784  5800 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-27 07:07:05.786  5784  5784 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:05.786  5784  5784 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:05.786  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.786  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.786  5784  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:05.786  5784  5784 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 07:07:05.786  5784  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:05.786  5784  5784 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 07:07:05.787  5784  5809 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-27 07:07:05.787  5784  5809 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 07:07:05.787  5784  5809 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 07:07:05.787  5784  5800 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 07:07:05.787  5784  5809 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 07:07:05.791  3124  3124 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 07:07:05.791  3124  3124 D PanProfile: Bluetooth service disconnected
09-27 07:07:05.791  3124  3124 D BluetoothMap: Proxy object disconnected
09-27 07:07:05.791  3124  3124 D MapProfile: Bluetooth service disconnected
,09-27 07:07:05.795  5740  5740 D BluetoothPbap: Proxy object connected
09-27 07:07:05.795  3124  3124 D BluetoothPbap: Proxy object connected
09-27 07:07:05.795  3124  3124 D PbapServerProfile: Bluetooth service connected
,09-27 07:07:05.796  5784  5784 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:05.796  5740  5740 D PbapServerProfile: Bluetooth service connected
09-27 07:07:05.796  5784  5784 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:05.796  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.796  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.796  5784  5784 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 07:07:05.796  5784  5800 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-27 07:07:05.796  5784  5784 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-27 07:07:05.797  5784  5784 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:05.797  5784  5784 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:05.797  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.797  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 07:07:05.803  5784  5784 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 07:07:05.803  5784  5784 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-27 07:07:05.805  5784  5784 D BluetoothMapService: MAP Service closeService in
09-27 07:07:05.805  5784  5784 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:05.805  5784  5784 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:05.806  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.806  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.806  5784  5784 D BluetoothMapService: cleanup()
09-27 07:07:05.806  5784  5784 D BluetoothMapService: MAP Service closeService in
,09-27 07:07:05.806  5784  5784 V BluetoothAdapterState: isTurningOff()=true
09-27 07:07:05.806  5784  5784 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:05.806  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:05.806  5784  5784 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:05.807  5784  5796 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 07:07:05.807  5784  5796 D BluetoothAdapterProperties: Setting state to 15
09-27 07:07:05.807  5784  5796 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-27 07:07:05.807  5740  5740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 07:07:05.808  3124  3978 D BluetoothPan: onBluetoothStateChange on: false
09-27 07:07:05.808  5784  5796 I BluetoothAdapterState: Entering BleOnState
09-27 07:07:05.809  3124  3136 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 07:07:05.810  3124  3951 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 07:07:05.811   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 07:07:05.811   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 07:07:05.811  5740  5750 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-27 07:07:05.812  3124  3135 D BluetoothMap: onBluetoothStateChange: up=false
,09-27 07:07:05.812  5740  5751 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 07:07:05.812  5740  5750 D BluetoothMap: onBluetoothStateChange: up=false
09-27 07:07:05.813  3814  4043 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 07:07:05.813  3124  3978 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 07:07:05.814   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 07:07:05.814  5740  5751 D BluetoothPan: onBluetoothStateChange on: false
,09-27 07:07:05.814  5740  5750 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 07:07:05.815  5740  5751 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 07:07:05.815  3124  3136 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 07:07:05.816   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 07:07:05.816  5784  5796 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 07:07:05.816  5784  5796 D BluetoothAdapterProperties: Setting state to 16
09-27 07:07:05.816  5784  5796 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 07:07:05.817  5784  5796 D BluetoothAdapterProperties: onBleDisable
09-27 07:07:05.817  5784  5796 I BluetoothAdapterState: Entering PendingCommandState
,09-27 07:07:05.817  5784  5797 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-27 07:07:05.820  5784  5809 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 07:07:05.820  5784  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 07:07:05.821  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.822  5784  5800 D BluetoothAdapterProperties: Scan Mode:20
09-27 07:07:05.823  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.825  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.826  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:05.827  5740  5740 D DockEventReceiver: finishStartingService: stopping service
,09-27 07:07:05.830  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 07:07:05.835  5740  5740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 07:07:05.840  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 07:07:05.841  5740  5740 D DockEventReceiver: finishStartingService: stopping service
,09-27 07:07:06.021  5784  5800 I bt_hci  : shut_down
,09-27 07:07:06.021  5784  5804 D bt_hwcfg: hw_epilog_process
09-27 07:07:06.022  5784  5804 I bt_vendor: low_power_mode_cb
,09-27 07:07:06.024  5784  5804 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-27 07:07:06.024  5784  5804 I bt_vendor: epilog_cb
09-27 07:07:06.024  5784  5804 I bt_hci  : epilog_finished_callback
09-27 07:07:06.025  5784  5800 I bt_hci_h4: hal_close
09-27 07:07:06.025  5784  5800 I bt_userial_vendor: device fd = 54 close
,09-27 07:07:06.151  5784  5797 D bt_stack_manager: event_shut_down_stack finished.
,09-27 07:07:06.152  5784  5796 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-27 07:07:06.155  5784  5796 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-27 07:07:06.155  5784  5784 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 07:07:06.156  5784  5784 D BtGatt.GattService: Received stop request...Stopping profile...
09-27 07:07:06.156  5784  5784 D BtGatt.GattService: stop()
09-27 07:07:06.157  5784  5784 D BtGatt.AdvertiseManager: advertise clients cleared
,09-27 07:07:06.160  5784  5784 V BluetoothAdapterState: isTurningOff()=false
,09-27 07:07:06.160  5784  5784 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:06.160  5784  5784 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:06.160  5784  5784 V BluetoothAdapterState: isBleTurningOff()=true
09-27 07:07:06.160  5784  5796 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-27 07:07:06.161  5784  5796 D BluetoothAdapterProperties: Setting state to 10
09-27 07:07:06.161  5784  5796 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 07:07:06.162  5784  5796 I BluetoothAdapterState: Entering OffState
,09-27 07:07:06.164   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-27 07:07:06.175  5784  5784 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-27 07:07:06.176  5784  5784 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 07:07:06.176  5784  5784 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 07:07:06.179  5784  5797 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-27 07:07:06.186  5784  5784 I art     : System.exit called, status: 0
,09-27 07:07:06.186  5784  5784 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 07:07:06.219   927  3839 I ActivityManager: Process com.android.bluetooth (pid 5784) has died
,09-27 07:07:06.259  5637  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 07:07:06.260  5637  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:06.260  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:06.260  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:06.260  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:06.260  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 07:07:06.260  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:06.260  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:06.260  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:06.260  5637  5696 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 07:07:06.260  5637  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:06.262  5637  5683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:06.292   927   944 I ActivityManager: Start proc 5836:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 07:07:06.353  5836  5836 D AdapterServiceConfig: Adding HeadsetService
,09-27 07:07:06.354  5836  5836 D AdapterServiceConfig: Adding A2dpService
09-27 07:07:06.354  5836  5836 D AdapterServiceConfig: Adding HidService
09-27 07:07:06.354  5836  5836 D AdapterServiceConfig: Adding HealthService
,09-27 07:07:06.354  5836  5836 D AdapterServiceConfig: Adding PanService
09-27 07:07:06.355  5836  5836 D AdapterServiceConfig: Adding GattService
,09-27 07:07:06.355  5836  5836 D AdapterServiceConfig: Adding BluetoothMapService
09-27 07:07:06.355  5836  5836 D AdapterServiceConfig: Adding SapService
,09-27 07:07:06.364   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9201424:true
,09-27 07:07:06.364  5836  5836 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 07:07:06.366  5836  5836 I bt_bluedroid: init
,09-27 07:07:06.367  5836  5848 I BluetoothAdapterState: Entering OffState
,09-27 07:07:06.369  5836  5849 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-27 07:07:06.369  5836  5849 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 07:07:06.369  5836  5849 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 07:07:06.369  5836  5849 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 07:07:06.369  5836  5836 I bt_bluedroid: get_profile_interface socket
,09-27 07:07:06.371  5836  5836 I bt_bluedroid: get_profile_interface sdp
,09-27 07:07:06.371  5836  5852 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 07:07:06.372  5836  5852 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 07:07:06.374  5836  5847 I bt_bluedroid: config_hci_snoop_log
,09-27 07:07:06.374   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-27 07:07:06.378  5836  5848 D BluetoothAdapterState: Current state: OFF, message: 0
,09-27 07:07:06.379  5836  5848 D BluetoothAdapterProperties: Setting state to 14
09-27 07:07:06.379  5836  5848 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-27 07:07:06.380  5836  5848 D BluetoothBondStateMachine: make
,09-27 07:07:06.381  5836  5853 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 07:07:06.384  5836  5848 I BluetoothAdapterState: Entering PendingCommandState
,09-27 07:07:06.385  5836  5836 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 07:07:06.387  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:06.387  5836  5836 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 07:07:06.388  5836  5836 D BtGatt.GattService: Received start request. Starting profile...
09-27 07:07:06.388  5836  5836 D BtGatt.GattService: start()
09-27 07:07:06.388  5836  5836 I bt_bluedroid: get_profile_interface gatt
,09-27 07:07:06.389  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
,09-27 07:07:06.389  5836  5836 D BtGatt.AdvertiseManager: advertise manager created
,09-27 07:07:06.393  5836  5836 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:06.393  5836  5836 V BluetoothAdapterState: isTurningOn()=false
09-27 07:07:06.393  5836  5836 V BluetoothAdapterState: isBleTurningOn()=true
09-27 07:07:06.393  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 07:07:06.394  5836  5848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 07:07:06.395  5836  5848 I bt_bluedroid: bt_bluedroid
,09-27 07:07:06.395  5836  5849 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-27 07:07:06.395  5836  5849 I bt_hci  : start_up
,09-27 07:07:06.400  5836  5849 I bt_vendor: alloc value 0xf3d95871
,09-27 07:07:06.400  5836  5849 I bt_vendor: init
09-27 07:07:06.400  5836  5849 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 07:07:06.400  5836  5849 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 07:07:06.512  5836  5849 D bt_hci  : start_up starting async portion
09-27 07:07:06.512  5836  5856 I bt_hci  : event_finish_startup
09-27 07:07:06.512  5836  5856 I bt_hci_h4: hal_open
09-27 07:07:06.513  5836  5856 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-27 07:07:06.508  5857  5857 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 07:07:06.515  5836  5856 I bt_userial_vendor: device fd = 54 open
,09-27 07:07:06.530  5836  5856 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 07:07:06.533  5836  5856 D bt_hwcfg: Chipset BCM4358A3
,09-27 07:07:06.533  5836  5856 D bt_hwcfg: Target name = [BCM4358A3]
09-27 07:07:06.533  5836  5856 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 07:07:06.708   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:07:06.769  5836  5848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-27 07:07:06.939  5836  5856 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 07:07:06.940  5836  5856 D bt_hwcfg: Settlement delay -- 100 ms
09-27 07:07:06.940  5836  5856 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 07:07:07.064  5836  5856 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 07:07:07.064  5836  5856 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-27 07:07:07.066  5836  5856 I bt_hwcfg: vendor lib fwcfg completed
09-27 07:07:07.066  5836  5856 I bt_vendor: firmware callback
,09-27 07:07:07.066  5836  5856 I bt_hci  : firmware_config_callback
,09-27 07:07:07.073  5836  5859 I bt_btu  : btu_task pending for preload complete event
,09-27 07:07:07.074  5836  5859 I bt_btu_task: Bluetooth chip preload is complete
09-27 07:07:07.074  5836  5859 I bt_btu  : btu_task received preload complete event
,09-27 07:07:07.081  5836  5859 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 07:07:07.081  5836  5859 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-27 07:07:07.081  5836  5859 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-27 07:07:07.081  5836  5859 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 07:07:07.081  5836  5859 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 07:07:07.081  5836  5859 I         : BTE_InitTraceLevels -- TRC_A2D
09-27 07:07:07.082  5836  5859 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-27 07:07:07.082  5836  5859 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 07:07:07.082  5836  5859 I         : BTE_InitTraceLevels -- TRC_GAP
09-27 07:07:07.082  5836  5859 I         : BTE_InitTraceLevels -- TRC_PAN
09-27 07:07:07.082  5836  5859 I         : BTE_InitTraceLevels -- TRC_SDP
,09-27 07:07:07.082  5836  5859 I         : BTE_InitTraceLevels -- TRC_GATT
09-27 07:07:07.082  5836  5859 I         : BTE_InitTraceLevels -- TRC_SMP
09-27 07:07:07.082  5836  5859 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 07:07:07.083  5836  5859 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 07:07:07.169  5836  5859 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d13549
,09-27 07:07:07.169  5836  5859 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d13549 
,09-27 07:07:07.186  5836  5852 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 07:07:07.188  5836  5852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 07:07:07.188  5836  5852 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 07:07:07.190  5836  5852 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 07:07:07.193  5836  5852 D BluetoothAdapterProperties: Scan Mode:20
,09-27 07:07:07.193  5836  5852 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-27 07:07:07.194  5836  5852 D bt_hci  : do_postload posting postload work item
09-27 07:07:07.194  5836  5856 I bt_hci  : event_postload
09-27 07:07:07.194  5836  5856 I bt_vendor: sco_config_cb
09-27 07:07:07.194  5836  5856 I bt_hci  : sco_config_callback postload finished.
09-27 07:07:07.196  5836  5852 D bt_bte_conf: Device ID record 1 : primary
09-27 07:07:07.196  5836  5852 D bt_bte_conf:   vendorId            = 000f
09-27 07:07:07.196  5836  5852 D bt_bte_conf:   vendorIdSource      = 0001
,09-27 07:07:07.196  5836  5852 D bt_bte_conf:   product             = 1200
09-27 07:07:07.196  5836  5852 D bt_bte_conf:   version             = 1436
09-27 07:07:07.196  5836  5852 D bt_bte_conf:   clientExecutableURL = 
09-27 07:07:07.196  5836  5852 D bt_bte_conf:   serviceDescription  = 
09-27 07:07:07.196  5836  5852 D bt_bte_conf:   documentationURL    = 
09-27 07:07:07.196  5836  5852 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-27 07:07:07.197  5836  5849 D bt_stack_manager: event_start_up_stack finished
09-27 07:07:07.198  5836  5848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 07:07:07.198  5836  5848 D BluetoothAdapterProperties: Setting state to 15
09-27 07:07:07.198  5836  5848 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 07:07:07.199  5836  5848 I BluetoothAdapterState: Entering BleOnState
09-27 07:07:07.202  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:07.203  5836  5848 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-27 07:07:07.203  5836  5848 D BluetoothAdapterProperties: Setting state to 11
09-27 07:07:07.204  5836  5848 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-27 07:07:07.204  5836  5856 I bt_vendor: low_power_mode_cb
09-27 07:07:07.205  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:07.212  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:07.214  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:07.215  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
,09-27 07:07:07.216   927   927 D BluetoothHeadset: Proxy object connected
,09-27 07:07:07.216   927   927 D BluetoothHeadset: Proxy object connected
09-27 07:07:07.217   927   927 D BluetoothHeadset: Proxy object connected
09-27 07:07:07.217  3124  3978 D BluetoothHeadset: Proxy object connected
09-27 07:07:07.218  3814  3836 D BluetoothHeadset: Proxy object connected
09-27 07:07:07.218  5836  5836 D HeadsetService: Received start request. Starting profile...
09-27 07:07:07.219  3124  3124 D HeadsetProfile: Bluetooth service connected
09-27 07:07:07.220  5836  5836 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-27 07:07:07.221  5836  5836 D HeadsetStateMachine: make
,09-27 07:07:07.226  5736  5736 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 07:07:07.227  5736  5736 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-27 07:07:07.228  5836  5848 I BluetoothAdapterState: Entering PendingCommandState
09-27 07:07:07.229  5736  5736 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-27 07:07:07.230  5736  5736 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-27 07:07:07.232  5836  5836 D HeadsetStateMachine: max_hf_connections = 1
09-27 07:07:07.232  5836  5836 I bt_bluedroid: get_profile_interface handsfree
09-27 07:07:07.235  5836  5852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 07:07:07.235  5836  5852 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-27 07:07:07.236  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:07.237  5836  5836 D A2dpService: Received start request. Starting profile...
09-27 07:07:07.238  5836  5836 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 07:07:07.238  5836  5836 I bt_bluedroid: get_profile_interface avrcp
,09-27 07:07:07.245  5836  5836 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 07:07:07.245  5836  5836 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 07:07:07.245  5836  5836 D A2dpStateMachine: make
,09-27 07:07:07.246  5836  5836 I bt_bluedroid: get_profile_interface a2dp
,09-27 07:07:07.249  5836  5852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-27 07:07:07.250  5836  5868 D A2dpStateMachine: Enter Disconnected: -2
09-27 07:07:07.251  5836  5836 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 07:07:07.252  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:07.253  5836  5836 D HidService: Received start request. Starting profile...
,09-27 07:07:07.253  5836  5836 I bt_bluedroid: get_profile_interface hidhost
09-27 07:07:07.253  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 07:07:07.254  5836  5836 D HidService: setHidService(): set to: null
,09-27 07:07:07.254  5836  5852 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cf456d
09-27 07:07:07.255  5836  5852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 07:07:07.255  5836  5836 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 07:07:07.256  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:07.257  5836  5836 D HealthService: Received start request. Starting profile...
,09-27 07:07:07.258  5836  5836 I bt_bluedroid: get_profile_interface health
09-27 07:07:07.259  5836  5836 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-27 07:07:07.259  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:07.260  5836  5836 D PanService: Received start request. Starting profile...
09-27 07:07:07.260  5836  5836 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 07:07:07.260  5836  5836 I bt_bluedroid: get_profile_interface pan
09-27 07:07:07.260  5836  5852 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-27 07:07:07.262  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
09-27 07:07:07.262  5836  5836 D BluetoothMapService: Received start request. Starting profile...
09-27 07:07:07.263  5836  5836 D BluetoothMapService: start()
09-27 07:07:07.265  5836  5836 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-27 07:07:07.266  5836  5836 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-27 07:07:07.266  5836  5836 D BluetoothMapAppObserver: createReceiver()
09-27 07:07:07.267  5836  5836 D BluetoothMapAppObserver: initObservers()
09-27 07:07:07.267  5836  5836 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-27 07:07:07.270  5836  5848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-27 07:07:07.271   927  2980 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-27 07:07:07.271   927  2980 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-27 07:07:07.272   927  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 07:07:07.273  5836  5836 V SapService: SapBinder()
09-27 07:07:07.273  5836  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
,09-27 07:07:07.273  5836  5836 D SapService: Received start request. Starting profile...
09-27 07:07:07.274  5836  5836 V SapService: start()
,09-27 07:07:07.278  5836  5836 V BluetoothAdapterState: isTurningOff()=false
,09-27 07:07:07.278  5836  5836 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:07.278  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:07.278  5836  5866 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 07:07:07.278  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:07.278  5836  5836 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:07.278  5836  5836 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:07.278  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:07.278  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:07.279  5836  5836 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:07.279  5836  5836 V BluetoothAdapterState: isTurningOn()=true
,09-27 07:07:07.279  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 07:07:07.279  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:07.279  5836  5836 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:07.279  5836  5836 V BluetoothAdapterState: isTurningOn()=true
,09-27 07:07:07.279  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:07.279  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 07:07:07.280  5836  5836 V BluetoothAdapterState: isTurningOff()=false
,09-27 07:07:07.280  5836  5836 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:07.280  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:07.280  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:07.280  5836  5836 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:07.280  5836  5836 V BluetoothAdapterState: isTurningOn()=true
,09-27 07:07:07.280   927  2980 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
09-27 07:07:07.280  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
09-27 07:07:07.280  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:07.282  5836  5836 V BluetoothAdapterState: isTurningOff()=false
09-27 07:07:07.282  5836  5836 V BluetoothAdapterState: isTurningOn()=true
09-27 07:07:07.282  5836  5836 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 07:07:07.282  5836  5836 V BluetoothAdapterState: isBleTurningOff()=false
09-27 07:07:07.282  5836  5848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-27 07:07:07.283  5836  5848 D BluetoothAdapterProperties: ScanMode =  20
09-27 07:07:07.283  5836  5848 D BluetoothAdapterProperties: State =  11
09-27 07:07:07.284  5836  5852 D BluetoothAdapterProperties: Scan Mode:21
09-27 07:07:07.284  5836  5852 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 07:07:07.284  5836  5848 D BluetoothAdapterProperties: Setting state to 12
09-27 07:07:07.284  5836  5848 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-27 07:07:07.284  5836  5848 I BluetoothAdapterState: Entering OnState
09-27 07:07:07.284  3124  3951 D BluetoothPan: onBluetoothStateChange on: true
,09-27 07:07:07.286  3124  3135 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-27 07:07:07.287  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:07.287  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:07.287  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:07.287  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:07.287  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:07.287  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:07.287  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:07.287  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 07:07:07.288  3124  3136 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 07:07:07.290  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:07.292   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:07.292   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:07.292  5740  5750 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 07:07:07.293  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:07.293  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:07.293  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:07.293  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:07.293  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:07.293  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:07.293  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:07.293  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:07.294  3124  3978 D BluetoothMap: onBluetoothStateChange: up=true
09-27 07:07:07.295  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:07.295  5740  5751 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:07.296  5740  5750 D BluetoothMap: onBluetoothStateChange: up=true
09-27 07:07:07.296  3124  3124 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 07:07:07.296  3124  3124 D PanProfile: Bluetooth service connected
09-27 07:07:07.297  3124  3124 D BluetoothInputDevice: Proxy object connected
09-27 07:07:07.297  3124  3124 D HidProfile: Bluetooth service connected
09-27 07:07:07.297  5740  5740 D BluetoothInputDevice: Proxy object connected
09-27 07:07:07.297  5740  5740 D HidProfile: Bluetooth service connected
,09-27 07:07:07.298  5836  5836 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 07:07:07.298  5836  5836 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-27 07:07:07.299  3814  4001 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:07.299  3124  3136 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 07:07:07.299  5836  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:07.302   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 07:07:07.302  5836  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:07.302  5740  5751 D BluetoothPan: onBluetoothStateChange on: true
09-27 07:07:07.303  5836  5836 D ObexServerSockets: Succeed to create listening sockets 
,09-27 07:07:07.303  5836  5836 D ObexServerSockets0: startAccept()
09-27 07:07:07.303  5836  5836 D ObexServerSockets0: prepareForNewConnect()
09-27 07:07:07.304  5740  5750 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 07:07:07.305  5836  5836 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 07:07:07.305  5836  5836 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 07:07:07.306  5836  5874 D ObexServerSockets0: Accepting socket connection...
09-27 07:07:07.306  5740  5873 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-27 07:07:07.306  5836  5875 D ObexServerSockets0: Accepting socket connection...
09-27 07:07:07.307  3124  3124 D BluetoothMap: Proxy object connected
09-27 07:07:07.307  3124  3124 D MapProfile: Bluetooth service connected
09-27 07:07:07.307  3124  3124 D BluetoothMap: getConnectedDevices()
09-27 07:07:07.307   927   927 D BluetoothA2dp: Proxy object connected
,09-27 07:07:07.307  5740  5740 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 07:07:07.307  5740  5740 D PanProfile: Bluetooth service connected
09-27 07:07:07.307  5740  5740 D BluetoothMap: Proxy object connected
09-27 07:07:07.307  5740  5740 D MapProfile: Bluetooth service connected
09-27 07:07:07.307  5740  5740 D BluetoothMap: getConnectedDevices()
09-27 07:07:07.308  3124  3136 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:07.309   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 07:07:07.311  5836  5836 D BluetoothMapService: onReceive
,09-27 07:07:07.311  5836  5836 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 07:07:07.311   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 07:07:07.311  5836  5836 D BluetoothMapService: STATE_ON
09-27 07:07:07.311   927   927 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-27 07:07:07.313  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:07.314  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:07.315  5740  5740 D BluetoothA2dp: Proxy object connected
09-27 07:07:07.316  3124  3124 D BluetoothA2dp: Proxy object connected
09-27 07:07:07.318  5836  5878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:07.319  5836  5878 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 07:07:07.319  5836  5878 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-27 07:07:07.323   927  2980 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 07:07:07.324  5740  5740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 07:07:07.325  5736  5736 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
09-27 07:07:07.328  5740  5740 D DockEventReceiver: finishStartingService: stopping service
,09-27 07:07:07.330  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 07:07:07.339  5836  5836 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 07:07:07.339  5836  5836 D ObexServerSockets0: prepareForNewConnect()
,09-27 07:07:07.339  5740  5740 D BluetoothPbap: Proxy object connected
09-27 07:07:07.339  5740  5740 D PbapServerProfile: Bluetooth service connected
09-27 07:07:07.339  3124  3124 D BluetoothPbap: Proxy object connected
09-27 07:07:07.340  3124  3124 D PbapServerProfile: Bluetooth service connected
,09-27 07:07:07.346  5836  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 07:07:07.358  5836  5886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 07:07:07.360  5836  5886 I BtOppRfcommListener: Accept thread started.
,09-27 07:07:07.396  5740  5750 D BluetoothHeadset: Proxy object connected
,09-27 07:07:07.397  5740  5740 D HeadsetProfile: Bluetooth service connected
,09-27 07:07:07.709   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:07:07.747  5736  5736 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 07:07:07.777  5637  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:07.777  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:07.777  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:07.777  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:07.777  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:07.777  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:07.777  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:07.777  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:07.779  5736  5736 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-27 07:07:07.780  5736  5736 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-27 07:07:07.782  5637  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:07.789   927  2980 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-27 07:07:07.789   927  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 07:07:07.789   927  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-27 07:07:07.790  5637  5683 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,09-27 07:07:07.792   927  3839 D WifiService: setWifiEnabled: false pid=5637, uid=10077
09-27 07:07:07.792   927  3839 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-27 07:07:07.796  5637  5683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:07.808   927  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 07:07:07.819   506   921 D CommandListener: Setting iface cfg
,09-27 07:07:07.825   927  2980 D WifiStateMachine: Start Dhcp Watchdog 2
,09-27 07:07:07.831   927  5891 D DhcpClient: Receive thread started
,09-27 07:07:07.836   927  2980 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{1}, ntable=[]
,09-27 07:07:07.836   927  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 07:07:07.836   927  2982 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-27 07:07:07.836   927  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 07:07:07.836   927  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 07:07:07.846   506   921 D CommandListener: Clearing all IP addresses on wlan0
,09-27 07:07:07.853   927  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
09-27 07:07:07.853   927  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,09-27 07:07:07.859   927   927 D RttService: SCAN_AVAILABLE : 1
,09-27 07:07:07.859   927  3088 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-27 07:07:07.862   927  2982 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-27 07:07:07.862   927  5891 D DhcpClient: Receive thread stopped
09-27 07:07:07.864   927  2980 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-27 07:07:07.867   927  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 07:07:07.869   506   921 D CommandListener: Clearing all IP addresses on wlan0
09-27 07:07:07.871   927  2980 D DhcpClient: doQuit
09-27 07:07:07.872   927  2980 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-27 07:07:07.872   927  5890 D DhcpClient: onQuitting
09-27 07:07:07.873  5736  5736 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-27 07:07:07.881  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:07.881  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:07.881  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:07.881  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 07:07:07.881  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:07.881  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:07.881  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:07.881  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:07.885  5736  5736 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-27 07:07:07.885  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:07.889  5736  5736 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-27 07:07:07.890  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:07.890  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:07.890  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:07.890  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 07:07:07.890  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:07.890  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:07.890  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:07.890  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:07.893  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:07.944  5736  5736 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-27 07:07:07.956  5736  5736 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 07:07:08.060  5034  5034 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 07:07:08.065   927  2980 D wifi    : In wifi stop Hal
09-27 07:07:08.066   927  2980 D wifi    : halHandle = 0x7f6e00d680, mVM = 0x7f8a68d140, mCls = 0x101926
09-27 07:07:08.066   927  5735 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-27 07:07:08.066   927  5735 D WifiHAL : Got a signal to exit!!!
09-27 07:07:08.066   927  5735 I WifiHAL : Exit wifi_event_loop
09-27 07:07:08.068   927  2980 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-27 07:07:08.069   927  2980 E WifiHAL : Event processing terminated
09-27 07:07:08.069   927  2980 D wifi    : In wifi cleaned up handler
09-27 07:07:08.070   927  2980 I WifiHAL : Internal cleanup completed
09-27 07:07:08.072  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:08.074  4090  4237 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 07:07:08.079  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:08.089   927  5735 D wifi    : set interface wlan0 flags (DOWN)
,09-27 07:07:08.089   927  2980 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 07:07:08.293   927   944 D Tethering: InitialState.processMessage what=4
,09-27 07:07:08.299   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 07:07:08.304  5637  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:08.304  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:08.304  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:08.304  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 07:07:08.304  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:08.304  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:08.304  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:08.304  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:08.310  5637  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:08.312   927  3424 D WifiService: setWifiEnabled: true pid=5637, uid=10077
09-27 07:07:08.312   927  3424 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-27 07:07:08.313  5637  5683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:08.315   506   921 D SoftapController: Softap fwReload - Ok
,09-27 07:07:08.318   506   921 D CommandListener: Setting iface cfg
,09-27 07:07:08.318   506   921 D CommandListener: Trying to bring down wlan0
,09-27 07:07:08.319   506   921 D CommandListener: Clearing all IP addresses on wlan0
,09-27 07:07:08.322   927  2980 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 07:07:08.710   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:07:08.817   927  3424 D WifiService: setWifiEnabled: true pid=5637, uid=10077
,09-27 07:07:08.817   927  3424 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 07:07:08.929   927  2980 D wifi    : set interface wlan0 flags (UP)
,09-27 07:07:08.930   927  2980 I WifiHAL : Initializing wifi
,09-27 07:07:08.931   927  2980 I WifiHAL : Creating socket
,09-27 07:07:08.936   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-27 07:07:08.939   927  2980 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-27 07:07:08.940   927  2980 D wifi    : Did set static halHandle = 0x7f6e00d680
,09-27 07:07:08.940   927  2980 D wifi    : halHandle = 0x7f6e00d680, mVM = 0x7f8a68d140, mCls = 0x12fa
,09-27 07:07:08.940   927  2980 D wifi    : array field set
,09-27 07:07:08.940   927  2980 I WifiNative-HAL: interface[0] = wlan0
,09-27 07:07:08.943   927  5894 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547306395264
,09-27 07:07:08.943   927  5894 D wifi    : waitForHalEvents called, vm = 0x7f8a68d140, obj = 0x12fa, env = 0x7f7fb68780
,09-27 07:07:09.003  5895  5895 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 07:07:09.023  5895  5895 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 07:07:09.032  5895  5895 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 07:07:09.032  5895  5895 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 07:07:09.043   927  2980 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-27 07:07:09.049  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:09.053  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:09.059   927  2980 D WifiConfigStore: Loading config and enabling all networks 
09-27 07:07:09.062  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:09.062  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:09.062  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:09.062  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:09.062  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:09.062  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:09.062  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:09.062  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:09.064  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 07:07:09.068  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:09.068  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:09.068  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:09.068  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:09.068  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:09.068  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:09.068  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:09.068  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:09.071  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:09.071   927  2980 D WifiConfigStore: loaded 0 passpoint configs
09-27 07:07:09.072   927  2980 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-27 07:07:09.072   927  2980 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-27 07:07:09.073   927  2980 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-27 07:07:09.075   927  2980 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 07:07:09.075   927  2980 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 07:07:09.075   927  2980 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 07:07:09.075   927  2980 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 07:07:09.090   927  2980 D WifiNative-HAL: Setting external_sim to 1
,09-27 07:07:09.090  5034  5034 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 07:07:09.090   927  2980 D wifi    : setting dfs flag to true, 0x7f7507fd80
09-27 07:07:09.090   927  2980 D WifiStateMachine: Setting OUI to DA-A1-19
,09-27 07:07:09.091   927  2980 D wifi    : setting scan oui 0x7f7507fd80
09-27 07:07:09.091   927  2980 D WifiHAL : Sending mac address OUI
,09-27 07:07:09.094   927  2980 E native  : do suspend false
,09-27 07:07:09.101   927  2980 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-27 07:07:09.101   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 07:07:09.101   927   927 D RttService: SCAN_AVAILABLE : 3
09-27 07:07:09.102   927  3088 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 07:07:09.102   506   921 D CommandListener: Setting iface cfg
,09-27 07:07:09.105   927  2963 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '141 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 141 Failed to set address (No such device)'
,09-27 07:07:09.105   927  2963 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 07:07:09.109   927  2963 D WifiNative-HAL: p2pGetDeviceAddress
09-27 07:07:09.109   927  2963 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-27 07:07:09.114   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=147995 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=9 mControllerEnergyUsed=34 }
,09-27 07:07:09.323  5637  5696 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:09.323  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:09.323  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:09.323  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:09.323  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:09.323  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:09.323  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:09.323  5637  5696 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:09.325  5637  5696 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:09.326  5637  5683 D BluetoothAdapter: enable(): BT is already enabled..!
,09-27 07:07:09.327   927   938 D WifiService: setWifiEnabled: true pid=5637, uid=10077
09-27 07:07:09.327   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-27 07:07:09.327  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 07:07:09.327  5637  5683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 07:07:09.327  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 07:07:09.327  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 07:07:09.327  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5976a7e removed from the list
09-27 07:07:09.327  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 07:07:09.327  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5eebdf removed from the list
09-27 07:07:09.328  5637  5683 D io.jxcore.node.ConnectivityMonitor: stop
09-27 07:07:09.328  5637  5683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 07:07:09.328  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 07:07:09.329  5637  5683 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
09-27 07:07:09.330  5637  5683 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
09-27 07:07:09.332  5637  5897 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-27 07:07:09.332  5637  5897 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 07:07:09.714   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 07:07:09.859  5637  5899 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-27 07:07:09.859  5637  5897 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-27 07:07:09.860  5637  5899 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 07:07:09.860  5637  5897 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-27 07:07:09.861  5637  5897 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 07:07:09.861  5637  5899 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 07:07:09.863  5637  5899 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 07:07:09.863  5637  5897 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 07:07:09.866  5637  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: IncomingSocketThread/Sender)
,09-27 07:07:09.868  5637  5897 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 07:07:09.868  5637  5903 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Receiver)
09-27 07:07:09.868  5637  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: OutgoingSocketThread/Sender)
,09-27 07:07:09.870  5637  5899 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-27 07:07:09.870  5637  5903 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: OutgoingSocketThread/Receiver)
09-27 07:07:09.870  5637  5903 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-27 07:07:09.870  5637  5903 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-27 07:07:09.871  5637  5904 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: IncomingSocketThread/Receiver)
,09-27 07:07:09.873  5637  5904 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: IncomingSocketThread/Receiver)
09-27 07:07:09.873  5637  5904 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-27 07:07:09.873  5637  5904 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-27 07:07:10.338  5637  5683 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-27 07:07:10.340  5637  5683 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
09-27 07:07:10.341  5637  5683 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,09-27 07:07:10.346  5637  5683 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
09-27 07:07:10.347  5637  5683 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-27 07:07:10.350  5637  5683 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
09-27 07:07:10.350  5637  5683 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-27 07:07:10.351  5637  5683 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-27 07:07:10.357  5637  5683 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-27 07:07:10.358  5637  5683 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c4446e1 Bundle[{}]
09-27 07:07:10.359  5637  5683 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-27 07:07:10.359  5637  5683 I io.jxcore.node.LifeCycleMonitor: start: OK
09-27 07:07:10.359  5637  5683 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-27 07:07:10.360  5637  5683 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
09-27 07:07:10.360  5637  5683 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-27 07:07:10.361  5637  5683 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
09-27 07:07:10.361  5637  5683 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-27 07:07:10.361  5637  5683 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
09-27 07:07:10.361  5637  5683 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-27 07:07:10.362  5637  5683 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
09-27 07:07:10.363  5637  5683 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-27 07:07:10.365  5637  5683 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,09-27 07:07:10.367  5637  5683 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-27 07:07:10.369  5637  5683 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
09-27 07:07:10.370  5637  5683 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
09-27 07:07:10.371  5637  5683 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
09-27 07:07:10.371  5637  5683 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,09-27 07:07:10.374  5637  5683 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-27 07:07:10.378  5637  5905 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-27 07:07:10.378  5637  5905 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 07:07:10.383  5637  5905 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-27 07:07:10.383  5637  5905 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 07:07:10.384  5637  5905 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 07:07:10.384  5637  5905 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 07:07:10.385  5637  5907 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-27 07:07:10.385  5637  5907 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 07:07:10.385  5637  5908 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 175, name: OutgoingSocketThread/Sender)
,09-27 07:07:10.385  5637  5907 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 07:07:10.386  5637  5905 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 07:07:10.387  5637  5907 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 07:07:10.387  5637  5909 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: OutgoingSocketThread/Receiver)
,09-27 07:07:10.388  5637  5907 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-27 07:07:10.389  5637  5910 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: IncomingSocketThread/Sender)
,09-27 07:07:10.389  5637  5909 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 176, thread name: OutgoingSocketThread/Receiver)
,09-27 07:07:10.389  5637  5909 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 07:07:10.390  5637  5909 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-27 07:07:10.391  5637  5911 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: IncomingSocketThread/Receiver)
,09-27 07:07:10.392  5637  5911 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: IncomingSocketThread/Receiver)
,09-27 07:07:10.392  5637  5911 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-27 07:07:10.392  5637  5911 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-27 07:07:10.716   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 07:07:10.884  5637  5683 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-27 07:07:10.886  5637  5683 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,09-27 07:07:10.889  5637  5683 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-27 07:07:10.892  5637  5683 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-27 07:07:10.894  5637  5683 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-27 07:07:10.895  5637  5683 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,09-27 07:07:10.896  5637  5683 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 187)
,09-27 07:07:10.897  5637  5683 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,09-27 07:07:10.898  5637  5683 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-27 07:07:10.898  5637  5683 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 188)
09-27 07:07:10.900  5637  5683 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-27 07:07:10.901  5637  5683 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
09-27 07:07:10.904  5637  5683 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,09-27 07:07:10.906  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 07:07:10.906  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5de8318 added. We now have 3 listener(s)
09-27 07:07:10.910  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 07:07:10.910  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 07:07:10.911  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 07:07:10.911  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 07:07:10.911  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83f5171 added. We now have 3 listener(s)
,09-27 07:07:10.911  5637  5683 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 07:07:10.913  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 07:07:10.919  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 07:07:10.925  5637  5683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 07:07:10.925  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:10.925  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:10.925  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:10.925  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:10.925  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 07:07:10.925  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 07:07:10.925  5637  5683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 07:07:10.929  5637  5683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 07:07:10.930  5637  5683 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 07:07:10.934  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 07:07:10.936  5637  5683 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
09-27 07:07:10.937  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 07:07:10.938  5637  5683 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
09-27 07:07:10.938  5637  5683 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-27 07:07:10.938  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-27 07:07:10.939  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 07:07:10.939  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 07:07:10.939  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 07:07:10.939  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 07:07:10.940  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 07:07:10.941  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 07:07:10.942  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 07:07:10.942  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 07:07:10.942  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 07:07:10.942  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 07:07:10.942  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 07:07:10.942  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 07:07:10.944  5637  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 07:07:10.945  5877  5877 W Binder_6: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34875]" dev="sockfs" ino=34875 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:10.945  5877  5877 W Binder_6: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34875]" dev="sockfs" ino=34875 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 07:07:10.952  5637  5912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-27 07:07:10.954  5637  5683 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 07:07:10.954  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 07:07:10.960  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 07:07:10.961  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 07:07:10.961  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 07:07:10.963  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 07:07:10.964  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 07:07:10.964  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-27 07:07:10.964  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:10.964  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:10.964  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 07:07:10.966  5637  5683 D BluetoothAdapter: STATE_ON
,09-27 07:07:10.969  5836  5877 D BtGatt.GattService: registerClient() - UUID=686667cd-d485-4c2d-bf8d-5bf5dc086ef8
09-27 07:07:10.969  5836  5852 D BtGatt.GattService: onClientRegistered() - UUID=686667cd-d485-4c2d-bf8d-5bf5dc086ef8, clientIf=5
,09-27 07:07:10.970  5637  5648 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 07:07:10.972  5836  5854 D BtGatt.AdvertiseManager: message : 0
,09-27 07:07:10.974  5836  5854 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 07:07:10.985  5836  5852 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 07:07:10.991  5836  5852 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 07:07:10.992  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-27 07:07:10.992  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-27 07:07:10.994  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 07:07:10.995  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 07:07:10.996  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 07:07:10.996  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-27 07:07:10.996  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 07:07:10.996  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 07:07:10.996  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-27 07:07:10.999  5637  5637 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 07:07:10.999  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 07:07:11.500  5637  5637 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 07:07:11.500  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 07:07:11.501  5637  5637 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 07:07:12.238  5895  5895 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 07:07:12.242  5895  5895 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 07:07:12.247  5895  5895 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 07:07:12.252  5895  5895 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 07:07:12.269  5895  5895 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-27 07:07:12.315   927  2980 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-27 07:07:12.317   927  2980 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-27 07:07:12.317   927  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 07:07:12.330   927  2980 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-27 07:07:12.361   927  2980 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 07:07:12.795  5895  5895 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 07:07:12.831  5895  5895 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-27 07:07:12.832  5895  5895 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-27 07:07:12.840   927  2980 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 07:07:12.841   927  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 07:07:12.841   927  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-27 07:07:12.854   927  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 07:07:12.864   506   921 D CommandListener: Setting iface cfg
,09-27 07:07:12.871   927  2980 D WifiStateMachine: Start Dhcp Watchdog 3
,09-27 07:07:12.876   927  5917 D DhcpClient: Receive thread started
,09-27 07:07:12.881   927  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 07:07:12.881   927  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-27 07:07:12.882   927  2982 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-27 07:07:12.962   927  2980 E native  : do suspend false
,09-27 07:07:12.973   927  5916 D DhcpClient: Broadcasting DHCPDISCOVER
,09-27 07:07:12.988   927  5917 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172689, domain null
,09-27 07:07:12.988   927  5916 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172689 seconds
,09-27 07:07:12.990   927  5916 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-27 07:07:13.014   927  5917 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-27 07:07:13.015   927  5916 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-27 07:07:13.016   506   921 D CommandListener: Setting iface cfg
09-27 07:07:13.021   927  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-27 07:07:13.027   927  5916 D DhcpClient: Scheduling renewal in 86399s
,09-27 07:07:13.035   927  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-27 07:07:13.036   927  2980 D WifiConfigStore: No blacklist allowed without epno enabled
,09-27 07:07:13.037   927  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-27 07:07:13.039   927  2982 D ConnectivityService: Adding iface wlan0 to network 102
,09-27 07:07:13.050   927  2980 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-27 07:07:13.092   927  2982 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-27 07:07:13.093   927  2982 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-27 07:07:13.096   927  2982 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-27 07:07:13.098   927  2982 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-27 07:07:13.100   927  2982 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-27 07:07:13.107   927  2982 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 07:07:13.112   927  2982 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-27 07:07:13.112   927  2982 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-27 07:07:13.112   927  2982 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-27 07:07:13.112   927  2982 D ConnectivityService:    accepting network in place of null
09-27 07:07:13.112   927  2980 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-27 07:07:13.112   927  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 07:07:13.113   927  2982 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 07:07:13.137   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 07:07:13.158   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 07:07:13.161   927  2982 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-27 07:07:13.161   927  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 07:07:13.161  3767  3916 W QCNEJ   : |CORE| network available: 102
09-27 07:07:13.162   927  2982 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-27 07:07:13.165  3767  3916 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-27 07:07:13.165   927  5915 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152046, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-27 07:07:13.166   927   944 D Tethering: MasterInitialState.processMessage what=3
09-27 07:07:13.167  3767  3916 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-27 07:07:13.167  3767  3916 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-27 07:07:13.175  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:13.175  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:13.175  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:13.175  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:13.175  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:13.175  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 07:07:13.175  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 07:07:13.175  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 07:07:13.177  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 07:07:13.180  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:13.180  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:13.180  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:13.180  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:13.180  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:13.180  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 07:07:13.180  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 07:07:13.180  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 07:07:13.182  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 07:07:13.186  3738  3738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-27 07:07:13.187  5637  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 07:07:13.187  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 07:07:13.187  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 07:07:13.187  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 07:07:13.187  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 07:07:13.187  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 07:07:13.187  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 07:07:13.187  5637  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 07:07:13.189  5637  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 07:07:13.190  5060  5084 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 07:07:13.191  5060  5084 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 07:07:13.191  5060  5084 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-27 07:07:13.191  5060  5084 E SarControlService: no key has been found,reset the power
09-27 07:07:13.191  5060  5096 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 07:07:13.191  5060  5096 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 07:07:13.191  5060  5096 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 07:07:13.192  5085  5085 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 07:07:13.192  5085  5085 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-27 07:07:13.193  5060  5096 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 07:07:13.193  5060  5096 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-27 07:07:13.193  5060  5096 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 07:07:13.194  5085  5085 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 07:07:13.194  5085  5085 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 07:07:13.195  3738  3738 D SystemUpdateService: onCreate
,09-27 07:07:13.200  5085  5099 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@39bc1ad HexData = [00000000ec03000000000000ffffffff]
,09-27 07:07:13.200  5085  5099 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 07:07:13.200  5085  5099 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-27 07:07:13.200  5085  5085 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 07:07:13.201  5060  5070 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 07:07:13.201  3738  3738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 07:07:13.203  5085  5099 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@39bc1ad HexData = [00000000ed03000000000000ffffffff]
,09-27 07:07:13.203  5085  5099 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 07:07:13.203  5085  5099 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-27 07:07:13.203  5085  5085 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 07:07:13.204  5060  5071 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-27 07:07:13.215  3738  3738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-27 07:07:13.223  3738  5421 I iu.UploadsManager: num queued entries: 0
,09-27 07:07:13.224  3738  5421 I iu.UploadsManager: num updated entries: 0
09-27 07:07:13.224  3738  5421 I iu.SyncManager: NEXT; no task
,09-27 07:07:13.226  3738  3738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 07:07:13.228  3738  3738 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-27 07:07:13.229  5423  5423 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 07:07:13.233  5423  5423 D SprintDMHelper: simOperator: 
09-27 07:07:13.234  5423  5423 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 07:07:13.242  3738  5927 I SystemUpdateService: active receiver: enabled
,09-27 07:07:13.266  3738  5927 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 07:07:13.269   927  5914 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-27 07:07:13.272  3738  5927 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-27 07:07:13.272  3738  5927 I SystemUpdateService: now status is 0 (complete)
09-27 07:07:13.272  3738  5927 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 07:07:13.272  3738  5927 I SystemUpdateService: file has been verified
09-27 07:07:13.273  3738  5927 I SystemUpdateService: OTA package size = 21989297
,09-27 07:07:13.277  3738  5927 I SystemUpdateService: showing system update notification
,09-27 07:07:13.288  3738  3738 D SystemUpdateService: onDestroy
,09-27 07:07:13.328   927  5914 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 27 Sep 2016 11:07:13 GMT], X-Android-Received-Millis=[1474974433327], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474974433302]}
,09-27 07:07:13.328   927  2982 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-27 07:07:13.329   927  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-27 07:07:13.329   927  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-27 07:07:13.330   927  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-27 07:07:13.331  5034  5932 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-27 07:07:14.162   927  2982 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-27 07:07:14.498  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-27 07:07:14.498  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 07:07:14.499  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 07:07:14.499  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 07:07:14.499  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-27 07:07:14.500  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 07:07:14.500  5637  5912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-27 07:07:14.500  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 07:07:14.500  5637  5912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 07:07:14.500  5637  5912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 07:07:14.500  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-27 07:07:14.500  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 07:07:14.500  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 07:07:14.500  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 07:07:14.500  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-27 07:07:14.501  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 07:07:14.503  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:14.504  5637  5683 D BluetoothLeScanner: could not find callback wrapper
09-27 07:07:14.504  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 07:07:14.504  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 07:07:14.506  5836  5854 D BtGatt.AdvertiseManager: message : 1
09-27 07:07:14.507  5836  5854 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 07:07:14.521  5836  5852 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-27 07:07:14.522  5836  5852 D BtGatt.GattService: Client app is not null!
,09-27 07:07:14.523  5836  5846 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 07:07:14.524  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 07:07:14.524  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 07:07:14.524  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 07:07:14.524  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-27 07:07:14.525  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 07:07:14.527  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:14.527  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 07:07:14.528  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 07:07:14.528  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 07:07:14.531  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 07:07:14.531  5637  5637 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 07:07:14.531  5637  5637 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 07:07:14.531  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 07:07:14.532  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 07:07:14.532  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:14.534  5637  5683 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
09-27 07:07:14.535  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 07:07:14.536  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 07:07:14.537  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 07:07:14.537  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 07:07:14.538  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 07:07:14.538  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 07:07:14.543  5637  5683 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 07:07:14.543  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 07:07:14.548  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 07:07:14.548  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 07:07:14.549  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 07:07:14.554  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-27 07:07:14.554  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 07:07:14.555  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 07:07:14.556  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:14.558  5836  5846 D BtGatt.GattService: registerClient() - UUID=f6f599f5-d97a-4eeb-b24b-027dc71b3d8b
,09-27 07:07:14.559  5836  5852 D BtGatt.GattService: onClientRegistered() - UUID=f6f599f5-d97a-4eeb-b24b-027dc71b3d8b, clientIf=5
,09-27 07:07:14.559  5637  5648 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 07:07:14.560  5836  5876 D BtGatt.GattService: start scan with filters
,09-27 07:07:14.564  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 07:07:14.564  5836  5855 D BtGatt.ScanManager: handling starting scan
,09-27 07:07:14.565  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 07:07:14.565  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 07:07:14.565  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 07:07:14.567  5836  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48ea63a
,09-27 07:07:14.568  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 07:07:14.569  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 07:07:14.569  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 07:07:14.570  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 07:07:14.574  5836  5852 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-27 07:07:14.575  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 07:07:14.575  5836  5855 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 07:07:14.583  5836  5852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-27 07:07:14.583  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 07:07:14.583  5836  5855 D BtGatt.ScanManager: Starting BLE batch scan
,09-27 07:07:14.583  5836  5855 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 07:07:14.596  5836  5852 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-27 07:07:14.596  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 07:07:14.603  5836  5852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-27 07:07:14.603  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 07:07:15.070  5637  5637 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-27 07:07:15.070  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 07:07:15.070  5637  5637 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 07:07:15.903   927  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 07:07:17.576  5637  5683 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,09-27 07:07:17.577  5637  5683 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
,09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-27 07:07:17.577  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-27 07:07:17.578  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 07:07:17.578  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-27 07:07:17.582  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:17.584  5836  5846 D BtGatt.GattService: stopScan() - queue size =1
09-27 07:07:17.588  5836  5876 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 07:07:17.589  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 07:07:17.589  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 07:07:17.590  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 07:07:17.590  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 07:07:17.590  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 07:07:17.590  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-27 07:07:17.593  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:17.594  5836  5836 D BtGatt.ScanManager: awakened up at time 156476
09-27 07:07:17.597  5836  5876 D BtGatt.GattService: registerClient() - UUID=4d01855d-975f-4295-aa20-08db2e587142
09-27 07:07:17.598  5836  5852 D BtGatt.GattService: onClientRegistered() - UUID=4d01855d-975f-4295-aa20-08db2e587142, clientIf=5
09-27 07:07:17.599  5637  5647 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 07:07:17.599  5836  5847 D BtGatt.GattService: start scan with filters
,09-27 07:07:17.603  5836  5852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 07:07:17.603  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 07:07:17.603  5836  5855 D BtGatt.ScanManager: stopping BLe Batch
,09-27 07:07:17.606  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-27 07:07:17.606  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-27 07:07:17.607  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-27 07:07:17.607  5637  5683 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 07:07:17.607  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 07:07:17.607  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 07:07:17.608  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 07:07:17.608  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 07:07:17.608  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 07:07:17.608  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-27 07:07:17.609  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 07:07:17.609  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 07:07:17.609  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 07:07:17.608  5846  5846 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32629]" dev="sockfs" ino=32629 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:17.608  5846  5846 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32629]" dev="sockfs" ino=32629 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 07:07:17.609  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 07:07:17.609  5637  5940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 07:07:17.610  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:17.610  5836  5847 D BtGatt.GattService: stopScan() - queue size =0
,09-27 07:07:17.611  5836  5865 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 07:07:17.611  5836  5852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 07:07:17.611  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 07:07:17.611  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 07:07:17.611  5836  5855 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 07:07:17.611  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 07:07:17.611  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 07:07:17.612  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 07:07:17.612  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-27 07:07:17.613  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:17.614  5637  5940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 07:07:17.614  5637  5683 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 07:07:17.616  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-27 07:07:17.616  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 07:07:17.616  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
09-27 07:07:17.616  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:17.616  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 07:07:17.616  5637  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 07:07:17.617  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:17.619  5836  5847 D BtGatt.GattService: registerClient() - UUID=9daff9e1-7c35-4f45-b712-bc8bc3e83c98
09-27 07:07:17.620  5836  5852 D BtGatt.GattService: onClientRegistered() - UUID=9daff9e1-7c35-4f45-b712-bc8bc3e83c98, clientIf=5
09-27 07:07:17.620  5637  5647 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-27 07:07:17.621  5836  5854 D BtGatt.AdvertiseManager: message : 0
09-27 07:07:17.624  5836  5854 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 07:07:17.627  5836  5852 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-27 07:07:17.627  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 07:07:17.627  5836  5852 D BtGatt.GattService: current time is 156509048398
,09-27 07:07:17.628  5836  5852 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -77, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 95, 19, 61, -60, 91, 112, 1, -128, -61, 40, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62, 0, -97, 31, -8, 13, 97, 119, 1, -128, -73, 34, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, 81, 34, 97, 112, -14, -5, 1, -128, -80, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -87, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -71, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -76, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-27 07:07:17.629  5836  5855 D BtGatt.ScanManager: handling starting scan
09-27 07:07:17.630  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-27 07:07:17.631  5836  5852 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62]
,09-27 07:07:17.631  5836  5852 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
09-27 07:07:17.631  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-27 07:07:17.632  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-27 07:07:17.632  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-27 07:07:17.632  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-27 07:07:17.632  5836  5852 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-27 07:07:17.638  5836  5852 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 07:07:17.642  5836  5852 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-27 07:07:17.642  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 07:07:17.643  5836  5855 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 07:07:17.647  5836  5852 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 07:07:17.648  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-27 07:07:17.648  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 07:07:17.649  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 07:07:17.650  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 07:07:17.650  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:17.650  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 07:07:17.650  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 07:07:17.650  5637  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 07:07:17.650  5637  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 07:07:17.651  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 07:07:17.652  5836  5852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 07:07:17.652  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 07:07:17.653  5637  5637 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 07:07:17.653  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 07:07:17.653  5836  5855 D BtGatt.ScanManager: Starting BLE batch scan
09-27 07:07:17.653  5836  5855 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 07:07:17.662  5836  5852 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-27 07:07:17.662  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 07:07:17.666  5836  5852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 07:07:17.666  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 07:07:17.671  5836  5852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 07:07:17.671  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 07:07:17.672  5836  5855 D BtGatt.ScanManager: stopping BLe Batch
,09-27 07:07:17.676  5836  5852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 07:07:17.676  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 07:07:17.676  5836  5855 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 07:07:17.681  5836  5852 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-27 07:07:17.681  5836  5852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 07:07:18.154  5637  5637 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 07:07:18.154  5637  5637 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-27 07:07:18.154  5637  5637 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 07:07:19.056   927  2980 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 12 -> obsolete
,09-27 07:07:20.509  3589  5943 I VacuumService: Vacuum at: now=1474974440509 tag=VacuumService
,09-27 07:07:20.533  3589  5946 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,09-27 07:07:20.576  3589  5944 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-27 07:07:20.579  3589  5944 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-27 07:07:20.621  3589  5944 W Uploader:  no longer exists, so no auth token.
,09-27 07:07:20.627  3589  5946 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-27 07:07:21.115   927  2982 D ConnectivityService: handlePromptUnvalidated 102
,09-27 07:07:21.152  5637  5683 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-27 07:07:21.153  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 07:07:21.153  5637  5683 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 07:07:21.153  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 07:07:21.153  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-27 07:07:21.153  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 07:07:21.153  5637  5940 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 07:07:21.153  5637  5940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 07:07:21.153  5637  5683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 07:07:21.153  5637  5940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-27 07:07:21.153  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 07:07:21.154  5637  5683 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5de8318 removed from the list
09-27 07:07:21.154  5637  5637 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 07:07:21.154  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 07:07:21.154  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 07:07:21.154  5637  5637 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 07:07:21.154  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-27 07:07:21.154  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 07:07:21.154  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 07:07:21.155  5637  5683 D BluetoothAdapter: STATE_ON
09-27 07:07:21.155  5637  5683 D BluetoothLeScanner: could not find callback wrapper
09-27 07:07:21.155  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 07:07:21.155  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 07:07:21.156  5836  5854 D BtGatt.AdvertiseManager: message : 1
09-27 07:07:21.157  5836  5854 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 07:07:21.164  5836  5852 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-27 07:07:21.165  5836  5852 D BtGatt.GattService: Client app is not null!
,09-27 07:07:21.166  5836  5865 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 07:07:21.166  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 07:07:21.166  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-27 07:07:21.167  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-27 07:07:21.167  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 07:07:21.167  5637  5683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 07:07:21.168  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:21.168  5637  5683 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 07:07:21.168  5637  5683 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 07:07:21.169  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 07:07:21.170  5637  5683 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83f5171 removed from the list
,09-27 07:07:21.170  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 07:07:21.170  5637  5683 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 07:07:21.171  5637  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 07:07:21.171  5637  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 07:07:21.171  5637  5637 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 07:07:21.173  5637  5683 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
09-27 07:07:21.173  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-27 07:07:21.173  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 07:07:21.173  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-27 07:07:21.174  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 07:07:21.174  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-27 07:07:21.174  5637  5683 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 07:07:21.175  5637  5683 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,09-27 07:07:21.177  5637  5683 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,09-27 07:07:21.178  5637  5683 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
09-27 07:07:21.178  5637  5683 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,09-27 07:07:21.179  5637  5683 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
09-27 07:07:21.180  5637  5683 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
09-27 07:07:21.180  5637  5683 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
09-27 07:07:21.181  5637  5683 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,09-27 07:07:21.182  5637  5683 I StreamCopyingThreadTest: Starting test: testRun
09-27 07:07:21.184  5637  5952 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: My test thread name)
,09-27 07:07:21.286  3589  5955 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-27 07:07:21.531  3589  5956 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-27 07:07:21.634  3589  5944 W Uploader:  no longer exists, so no auth token.
,09-27 07:07:21.648  3589  5955 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-27 07:07:21.672  5637  5637 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 07:07:21.869  3589  5956 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-27 07:07:21.987  5895  5895 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 07:07:22.539  5637  5952 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 201
,09-27 07:07:22.539  5637  5952 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 201, name: My test thread name)
,09-27 07:07:22.540  5637  5952 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-27 07:07:22.613   927  2980 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 12 -> obsolete
,09-27 07:07:22.688  5637  5683 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-27 07:07:22.691  5637  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 203, name: My test thread name)
,09-27 07:07:22.692  5637  5957 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 203, thread name: My test thread name)
09-27 07:07:22.692  5637  5957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 203, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-27 07:07:22.697  5637  5683 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-27 07:07:22.698  5637  5683 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 07:07:22.702  5637  5683 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-27 07:07:22.706  5637  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 207, name: My test thread name)
,09-27 07:07:22.707  5637  5958 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 207, thread name: My test thread name): Test exception.
09-27 07:07:22.707  5637  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 207, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-27 07:07:22.713  5637  5683 I jxcore-log: *Native tests were executed*
09-27 07:07:22.713  5637  5683 I jxcore-log: 
,09-27 07:07:22.714  5637  5683 I jxcore-log: Total number of executed tests:  82
09-27 07:07:22.714  5637  5683 I jxcore-log: 
09-27 07:07:22.714  5637  5683 I jxcore-log: Number of passed tests:  82
09-27 07:07:22.714  5637  5683 I jxcore-log: 
09-27 07:07:22.714  5637  5683 I jxcore-log: Number of failed tests:  0
09-27 07:07:22.714  5637  5683 I jxcore-log: 
,09-27 07:07:22.714  5637  5683 I jxcore-log: Number of ignored tests:  0
09-27 07:07:22.714  5637  5683 I jxcore-log: 
09-27 07:07:22.716  5637  5683 I jxcore-log: Total duration:  21923
09-27 07:07:22.716  5637  5683 I jxcore-log: 
09-27 07:07:22.716  5637  5683 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-27 07:07:22.716  5637  5683 I jxcore-log: 
,09-27 07:07:22.723  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 07:07:22.723  5637  5683 I jxcore-log: 
09-27 07:07:22.729  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 07:07:22.729  5637  5683 I jxcore-log: 
09-27 07:07:22.732  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 07:07:22.732  5637  5683 I jxcore-log: 
09-27 07:07:22.735  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 07:07:22.735  5637  5683 I jxcore-log: 
,09-27 07:07:22.737  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 07:07:22.737  5637  5683 I jxcore-log: 
,09-27 07:07:22.739  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 07:07:22.739  5637  5683 I jxcore-log: 
09-27 07:07:22.739  5637  5637 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-27 07:07:22.743  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 07:07:22.743  5637  5683 I jxcore-log: 
,09-27 07:07:22.745  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 07:07:22.745  5637  5683 I jxcore-log: 
,09-27 07:07:22.747  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 07:07:22.747  5637  5683 I jxcore-log: 
09-27 07:07:22.747  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 07:07:22.747  5637  5683 I jxcore-log: 
,09-27 07:07:22.749  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-27 07:07:22.749  5637  5683 I jxcore-log: 
,09-27 07:07:22.751  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.751  5637  5683 I jxcore-log: 
,09-27 07:07:22.752  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.752  5637  5683 I jxcore-log: 
,09-27 07:07:22.753  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.753  5637  5683 I jxcore-log: 
,09-27 07:07:22.754  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.754  5637  5683 I jxcore-log: 
,09-27 07:07:22.756  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.756  5637  5683 I jxcore-log: 
,09-27 07:07:22.757  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.757  5637  5683 I jxcore-log: 
,09-27 07:07:22.758  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.758  5637  5683 I jxcore-log: 
,09-27 07:07:22.759  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.759  5637  5683 I jxcore-log: 
,09-27 07:07:22.760  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.760  5637  5683 I jxcore-log: 
09-27 07:07:22.761  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.761  5637  5683 I jxcore-log: 
09-27 07:07:22.761  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.761  5637  5683 I jxcore-log: 
,09-27 07:07:22.762  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.762  5637  5683 I jxcore-log: 
,09-27 07:07:22.763  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.763  5637  5683 I jxcore-log: 
,09-27 07:07:22.764  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.764  5637  5683 I jxcore-log: 
,09-27 07:07:22.766  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.766  5637  5683 I jxcore-log: 
,09-27 07:07:22.766  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 07:07:22.766  5637  5683 I jxcore-log: 
09-27 07:07:22.767  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 07:07:22.767  5637  5683 I jxcore-log: 
09-27 07:07:22.768  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 07:07:22.768  5637  5683 I jxcore-log: 
09-27 07:07:22.768  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.768  5637  5683 I jxcore-log: 
,09-27 07:07:22.770  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.770  5637  5683 I jxcore-log: 
,09-27 07:07:22.771  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.771  5637  5683 I jxcore-log: 
09-27 07:07:22.772  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 07:07:22.772  5637  5683 I jxcore-log: 
,09-27 07:07:22.773  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 07:07:22.773  5637  5683 I jxcore-log: 
,09-27 07:07:22.774  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 07:07:22.774  5637  5683 I jxcore-log: 
,09-27 07:07:22.775  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 07:07:22.775  5637  5683 I jxcore-log: 
,09-27 07:07:22.776  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 07:07:22.776  5637  5683 I jxcore-log: 
09-27 07:07:22.777  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-27 07:07:22.777  5637  5683 I jxcore-log: 
09-27 07:07:22.777  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 07:07:22.777  5637  5683 I jxcore-log: 
09-27 07:07:22.778  5637  5683 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-27 07:07:22.778  5637  5683 I jxcore-log: 
,09-27 07:07:23.228  5959  5959 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-27 07:07:23.233  5959  5959 D AndroidRuntime: CheckJNI is OFF
,09-27 07:07:23.262  5959  5959 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-27 07:07:23.297  5959  5959 I Radio-JNI: register_android_hardware_Radio DONE
,09-27 07:07:23.314  5959  5959 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-27 07:07:23.323   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-27 07:07:23.323   927   940 I ActivityManager: Killing 5637:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-27 07:07:23.405   927   938 I WindowState: WIN DEATH: Window{1c96d9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-27 07:07:23.407   927  2981 D WifiService: Client connection lost with reason: 4
,09-27 07:07:23.408   927   937 D GraphicsStats: Buffer count: 2
,09-27 07:07:23.465   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-27 07:07:23.465   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-27 07:07:23.466   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-27 07:07:23.466   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-27 07:07:23.466   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:23.466   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:23.466   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 07:07:23.466   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-27 07:07:23.467   927   940 I ActivityManager:   Force finishing activity ActivityRecord{b695a26 u0 com.test.thalitest/.MainActivity t2}
,09-27 07:07:23.467   927   950 I art     : Starting a blocking GC Explicit
,09-27 07:07:23.473   927  3423 W ActivityManager: Spurious death for ProcessRecord{b65e9cc 0:com.test.thalitest/u0a77}, curProc for 5637: null
,09-27 07:07:23.478   927   945 W WindowManager: Attempted to add application window with unknown token Token{4b72667 ActivityRecord{b695a26 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-27 07:07:23.478   927   945 W WindowManager: Token{4b72667 ActivityRecord{b695a26 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{4b72667 ActivityRecord{b695a26 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-27 07:07:23.478   927   945 W WindowManager: view not successfully added to wm, removing view
09-27 07:07:23.479   927   945 W WindowManager: Exception when adding starting window
09-27 07:07:23.479   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{db417f7 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-27 07:07:23.479   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-27 07:07:23.479   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-27 07:07:23.479   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-27 07:07:23.479   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-27 07:07:23.479   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-27 07:07:23.479   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:23.479   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:23.479   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 07:07:23.479   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-27 07:07:23.548   927   950 I art     : Explicit concurrent mark sweep GC freed 32542(2MB) AllocSpace objects, 9(340KB) LOS objects, 33% free, 28MB/43MB, paused 1.578ms total 80.169ms
,09-27 07:07:23.566   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-27 07:07:23.569  5959  5959 I art     : System.exit called, status: 0
,09-27 07:07:23.569  5959  5959 I AndroidRuntime: VM exiting with result code 0.
,09-27 07:07:23.573   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-27 07:07:23.584   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-27 07:07:23.587  3666  3666 I Keyboard.Facilitator: resetDictionaries() : en_US
09-27 07:07:23.591  5836  5836 D BluetoothMapAppObserver: onReceive
,09-27 07:07:23.591  5836  5836 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-27 07:07:23.597  4090  4206 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-27 07:07:23.598   927  2946 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-27 07:07:23.614  3666  5970 I Keyboard.Facilitator.DecoderInitializer: run()
,09-27 07:07:23.623  3666  5970 I Decoder : createOrResetDecoder
,09-27 07:07:23.623  3814  3814 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-27 07:07:23.637  3405  5973 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-27 07:07:23.658    28    28 W kworker/1:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 07:07:23.664  3589  3589 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-27 07:07:23.664  3589  3589 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-27 07:07:23.662    28    28 W kworker/1:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 07:07:23.672   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-27 07:07:23.672    28    28 W kworker/1:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 07:07:23.681  3847  3949 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-27 07:07:23.682   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-27 07:07:23.683   927   939 E PackageManager: Failed to write settings, restoring backup
09-27 07:07:23.683   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-27 07:07:23.683   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-27 07:07:23.683   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-27 07:07:23.683   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-27 07:07:23.683   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-27 07:07:23.683   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:23.683   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:23.683   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 07:07:23.686   927   940 E DropBoxManagerService: Can't write: system_server_wtf
09-27 07:07:23.686   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-27 07:07:23.686   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 07:07:23.686   927   940 E DropBoxManagerService: 	... 13 more
,09-27 07:07:23.686  3589  3589 I ConfigService: onCreate
,09-27 07:07:23.688  3738  5976 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-27 07:07:23.688  3738  5976 D AccountUtils: Clearing selected account for com.test.thalitest
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-27 07:07:23.690  3589  5977 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-27 07:07:23.691  3405  3432 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj2BE8F4932) - 
,09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-27 07:07:23.691  3589  5977 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-27 07:07:23.694  3589  5977 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-27 07:07:23.697   927   938 I ActivityManager: Start proc 5979:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-27 07:07:23.698  3847  3949 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-27 07:07:23.698  3847  3949 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3847
09-27 07:07:23.698  3847  3949 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:23.698  3847  3949 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 07:07:23.705   927  3877 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-27 07:07:23.706   927  5984 E DropBoxManagerService: Can't write: system_app_crash
09-27 07:07:23.706   927  5984 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 07:07:23.706   927  5984 E DropBoxManagerService: 	... 5 more
,09-27 07:07:23.717  3847  3949 I Process : Sending signal. PID: 3847 SIG: 9
,09-27 07:07:23.722  3666  5970 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-27 07:07:23.741  3738  5976 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-27 07:07:23.765  3738  5976 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:23.765  3738  5976 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:23.766  3738  5976 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 07:07:23.767  3738  5976 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-27 07:07:23.780  3405  3432 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-27 07:07:23.780  3405  3432 E AndroidRuntime: Process: android.process.acore, PID: 3405
09-27 07:07:23.780  3405  3432 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-27 07:07:23.780  3405  3432 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 07:07:23.783   927  5995 E DropBoxManagerService: Can't write: system_app_crash
09-27 07:07:23.783   927  5995 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 07:07:23.783   927  5995 E DropBoxManagerService: 	... 5 more
,09-27 07:07:23.821  3405  3432 I Process : Sending signal. PID: 3405 SIG: 9
,09-27 07:07:23.863   927  3839 D GraphicsStats: Buffer count: 1
,09-27 07:07:23.863   927  3858 I WindowState: WIN DEATH: Window{9f57fc5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
09-27 07:07:23.863   927  2945 W InputDispatcher: channel '9f57fc5 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-27 07:07:23.863   927  2945 E InputDispatcher: channel '9f57fc5 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-27 07:07:23.863   927  3858 W InputDispatcher: Attempted to unregister already unregistered input channel '9f57fc5 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-27 07:07:23.868   927  3424 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3847) has died
,09-27 07:07:23.869   927  3424 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-27 07:07:23.872  3738  5997 I GMPM-SVC: App measurement is starting up
,09-27 07:07:23.879   927   945 E WindowState: getStack: Window{9f57fc5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{25bc3e5 token=Token{dfc26dc ActivityRecord{59aef4f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
09-27 07:07:23.880   927   945 E WindowState: getStack: Window{9f57fc5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{25bc3e5 token=Token{dfc26dc ActivityRecord{59aef4f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
09-27 07:07:23.880   927   945 E WindowState: getStack: Window{9f57fc5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{25bc3e5 token=Token{dfc26dc ActivityRecord{59aef4f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
,09-27 07:07:23.880   927   945 E WindowState: getStack: Window{9f57fc5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{25bc3e5 token=Token{dfc26dc ActivityRecord{59aef4f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
09-27 07:07:23.881   927   945 E WindowState: getStack: Window{9f57fc5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{25bc3e5 token=Token{dfc26dc ActivityRecord{59aef4f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
09-27 07:07:23.881   927   945 E WindowState: getStack: Window{9f57fc5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{25bc3e5 token=Token{dfc26dc ActivityRecord{59aef4f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
09-27 07:07:23.882  3738  5997 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-27 07:07:23.889  3738  5997 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-27 07:07:24.060   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
