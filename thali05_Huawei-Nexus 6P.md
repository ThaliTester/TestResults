#### Test 87116923b621cb4_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-29 04:20:27.782  3917  4981 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
09-29 04:20:27.876  3917  4981 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
09-29 04:20:27.906  3917  3917 I ConfigFetchService: fetch service done; releasing wakelock
09-29 04:20:27.907  3917  3917 I ConfigFetchService: stopping self
09-29 04:20:27.930  5607  5652 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
09-29 04:20:27.980  5607  5652 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
09-29 04:20:28.009  5607  5652 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-29 04:20:29.583   535   535 I ServiceManager: Waiting for service AtCmdFwd...
09-29 04:20:29.881  5664  5664 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-29 04:20:29.887  5664  5664 D AndroidRuntime: CheckJNI is OFF
09-29 04:20:29.911  5664  5664 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-29 04:20:29.944  5664  5664 I Radio-JNI: register_android_hardware_Radio DONE
09-29 04:20:29.958  5664  5664 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-29 04:20:29.964   930  3202 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-29 04:20:30.014   930  3202 I ActivityManager: Start proc 5673:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-29 04:20:30.034  5664  5664 D AndroidRuntime: Shutting down VM
,09-29 04:20:30.356   930   940 I WindowManager: Screenshot max retries 4 of Token{c4b8170 ActivityRecord{387b3 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{34e3a2b u0 Starting com.test.thalitest} drawState=2
,09-29 04:20:30.441  5673  5673 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-29 04:20:30.474  5673  5673 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-29 04:20:30.546  5673  5673 I LibraryLoader: Time to load native libraries: 63 ms (timestamps 9934-9997)
09-29 04:20:30.547  5673  5673 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-29 04:20:30.582  5673  5673 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4ac8577}
,09-29 04:20:30.583  5673  5673 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-29 04:20:30.583  5673  5673 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-29 04:20:30.584   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:20:30.590  5673  5673 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-29 04:20:30.592  5673  5673 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-29 04:20:30.650  5673  5673 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-29 04:20:30.666  5673  5673 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-29 04:20:30.666  5673  5673 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-29 04:20:30.666  5673  5673 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-29 04:20:30.666  5673  5673 I Adreno  : Build Date                       : 12/06/15
09-29 04:20:30.666  5673  5673 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-29 04:20:30.666  5673  5673 I Adreno  : Local Branch                     : mybranch17112971
09-29 04:20:30.666  5673  5673 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-29 04:20:30.666  5673  5673 I Adreno  : Remote Branch                    : NONE
09-29 04:20:30.666  5673  5673 I Adreno  : Reconstruct Branch               : NOTHING
,09-29 04:20:30.717   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eb22e1e:true
,09-29 04:20:30.746   405   405 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34954]" dev="sockfs" ino=34954 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-29 04:20:30.746   405   405 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34954]" dev="sockfs" ino=34954 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 04:20:30.761  5673  5673 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-29 04:20:30.770  5673  5673 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-29 04:20:30.793  3007  3007 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33109]" dev="sockfs" ino=33109 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 04:20:30.793  3007  3007 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33109]" dev="sockfs" ino=33109 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-29 04:20:30.798  5673  5710 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-29 04:20:30.799  3821  3821 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15757]" dev="sockfs" ino=15757 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-29 04:20:30.799  3821  3821 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15757]" dev="sockfs" ino=15757 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-29 04:20:30.805  5673  5697 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-29 04:20:30.834  5673  5710 I OpenGLRenderer: Initialized EGL, version 1.4
,09-29 04:20:30.911   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +550ms (total +926ms)
,09-29 04:20:30.939  5673  5673 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5673
,09-29 04:20:31.023  5673  5673 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-29 04:20:31.143  5673  5713 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -604243664
,09-29 04:20:31.147  5673  5713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-29 04:20:31.147  5673  5713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-29 04:20:31.147  5673  5713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-29 04:20:31.147  5673  5713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-29 04:20:31.147  5673  5713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-29 04:20:31.147  5673  5713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242f63c added. We now have 1 listener(s)
09-29 04:20:31.149  5673  5713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-29 04:20:31.149  5673  5713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 04:20:31.150  5673  5713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 04:20:31.150  5673  5713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-29 04:20:31.153  5673  5713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87c504b added. We now have 1 listener(s)
09-29 04:20:31.153  5673  5713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 04:20:31.157   930  3023 D WifiService: New client listening to asynchronous messages
,09-29 04:20:31.157  5673  5713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 04:20:31.157  5673  5713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-29 04:20:31.157  5673  5713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-29 04:20:31.157  5673  5713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-29 04:20:31.157  5673  5713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-29 04:20:31.159  5673  5713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:20:31.160  5673  5713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-29 04:20:31.163  5673  5713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-29 04:20:31.164  5673  5713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 04:20:31.164  5673  5713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:31.164  5673  5713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:31.164  5673  5713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:31.164  5673  5713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:31.164  5673  5713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 04:20:31.164  5673  5713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 04:20:31.164  5673  5713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 04:20:31.164  5673  5713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-29 04:20:31.164  5673  5713 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 04:20:31.164  5673  5713 I io.jxcore.node.LifeCycleMonitor: start: OK
09-29 04:20:31.166  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:31.169  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:31.178  5673  5673 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-29 04:20:31.456  5673  5719 W jxcore-log: Initializing JXcore engine
09-29 04:20:31.456  5673  5719 W jxcore-log: JXcore engine is ready
,09-29 04:20:31.479  5719  5719 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11679 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-29 04:20:31.479  5719  5719 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15470]" dev="sockfs" ino=15470 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-29 04:20:31.479  5719  5719 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-29 04:20:31.479  5719  5719 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32013]" dev="sockfs" ino=32013 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-29 04:20:31.488  5673  5719 W jxcore-log: Starting JXcore engine
,09-29 04:20:31.558  5673  5719 W jxcore-log: Platform android
09-29 04:20:31.558  5673  5719 W jxcore-log: 
,09-29 04:20:31.558  5673  5719 W jxcore-log: Process ARCH arm
09-29 04:20:31.558  5673  5719 W jxcore-log: 
,09-29 04:20:31.585   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:20:31.657  5673  5719 I jxcore-log: JXcore Cordova bridge is ready!
09-29 04:20:31.657  5673  5719 I jxcore-log: 
,09-29 04:20:31.657  5673  5719 W jxcore-log: JXcore engine is started
,09-29 04:20:31.663  5673  5713 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-29 04:20:31.666  5673  5673 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-29 04:20:32.586   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:20:32.916  3614  3614 I ConfigService: onDestroy
,09-29 04:20:33.587   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:20:34.587   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-29 04:20:38.499  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-29 04:20:38.499  5673  5719 I jxcore-log: 
,09-29 04:20:38.501  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-29 04:20:38.501  5673  5719 I jxcore-log: 
,09-29 04:20:38.505  5673  5719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 04:20:38.505  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:38.505  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:38.505  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:38.505  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:38.505  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 04:20:38.505  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 04:20:38.505  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 04:20:38.506  5673  5719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 04:20:38.508  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-29 04:20:38.508  5673  5719 I jxcore-log: 
,09-29 04:20:38.509  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-29 04:20:38.509  5673  5719 I jxcore-log: 
,09-29 04:20:38.737  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 04:20:38.737  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef69442 added. We now have 2 listener(s)
09-29 04:20:38.738  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 04:20:38.738  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 04:20:38.738  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 04:20:38.738  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 04:20:38.738  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d356c53 added. We now have 2 listener(s)
09-29 04:20:38.738  5673  5719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 04:20:38.739  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 04:20:38.740  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:20:38.743  5673  5719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 04:20:38.743  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:38.743  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:38.743  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:38.743  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:38.743  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 04:20:38.743  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 04:20:38.743  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 04:20:38.744  5673  5719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 04:20:38.744  5673  5719 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 04:20:38.744  5673  5719 D ExecuteNativeTests: Running unit tests
09-29 04:20:38.744  5673  5719 D BluetoothAdapter: enable(): BT is already enabled..!
09-29 04:20:38.745   930  3453 D WifiService: setWifiEnabled: true pid=5673, uid=10077
,09-29 04:20:38.745   930  3453 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 04:20:38.749  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:38.755  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:41.375  4869  4912 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-29 04:20:41.376  4869  4869 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,09-29 04:20:42.057   930  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 04:20:42.406   930  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 04:20:44.589   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:20:45.090   930  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 04:20:45.590   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:20:46.592   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:20:47.593   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:20:48.594   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:20:48.749  5673  5719 I com.test.thalitest.ThaliTestRunner: Running UT
,09-29 04:20:48.810  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 04:20:48.810  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc836d added. We now have 3 listener(s)
09-29 04:20:48.811  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 04:20:48.811  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 04:20:48.811  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 04:20:48.811  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 04:20:48.811  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdd5ba2 added. We now have 3 listener(s)
,09-29 04:20:48.811  5673  5719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 04:20:48.812  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 04:20:48.814  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:20:48.818  5673  5719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 04:20:48.818  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:48.818  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:48.818  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:48.818  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:48.818  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 04:20:48.818  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 04:20:48.818  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 04:20:48.819  5673  5719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 04:20:48.819  5673  5719 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 04:20:48.822  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
09-29 04:20:48.823  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 04:20:48.823  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 04:20:48.823  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-29 04:20:48.823  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 04:20:48.824  5673  5719 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-29 04:20:48.824  5673  5719 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-29 04:20:48.824  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-29 04:20:48.825  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-29 04:20:48.825  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 04:20:48.825  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-29 04:20:48.825  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
09-29 04:20:48.825  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:48.826  5673  5719 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-29 04:20:48.827  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-29 04:20:48.829  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
09-29 04:20:48.829  5673  5719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-29 04:20:48.832  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:48.833  5673  5719 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-29 04:20:48.833  5673  5719 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-29 04:20:48.833  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-29 04:20:48.833  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 04:20:48.833  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-29 04:20:48.833  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 04:20:48.833  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 04:20:48.834  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-29 04:20:48.834  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 04:20:48.834  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-29 04:20:48.834  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 04:20:48.834  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-29 04:20:48.835  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:20:48.835  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 04:20:48.836  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-29 04:20:48.837  5673  5719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 04:20:48.837  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 04:20:48.838  5673  5722 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:48.836  4669  4669 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15189]" dev="sockfs" ino=15189 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 04:20:48.840  5673  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-29 04:20:48.841  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 04:20:48.842  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 04:20:48.842  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 04:20:48.836  4669  4669 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[15189]" dev="sockfs" ino=15189 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 04:20:48.843  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-29 04:20:48.843  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 04:20:48.843  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-29 04:20:48.844  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:20:48.844  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:20:48.844  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 04:20:48.844  5673  5719 D BluetoothAdapter: STATE_ON
,09-29 04:20:48.847  4647  4669 D BtGatt.GattService: registerClient() - UUID=599b15d8-9725-45ef-b6b9-45e570bffebd
09-29 04:20:48.848  4647  4719 D BtGatt.GattService: onClientRegistered() - UUID=599b15d8-9725-45ef-b6b9-45e570bffebd, clientIf=5
09-29 04:20:48.851  5673  5683 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-29 04:20:48.853  4647  4721 D BtGatt.AdvertiseManager: message : 0
09-29 04:20:48.858  4647  4721 D BtGatt.AdvertiseManager: starting multi advertising
09-29 04:20:48.875  4647  4719 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-29 04:20:48.884  4647  4719 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-29 04:20:48.886  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 04:20:48.886  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-29 04:20:48.886  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-29 04:20:48.887  5673  5719 I io.jxcore.node.ConnectionHelper: start: OK
09-29 04:20:48.887  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-29 04:20:48.888  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 04:20:48.888  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 04:20:48.888  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 04:20:48.888  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-29 04:20:48.888  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-29 04:20:48.892  5673  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 04:20:48.892  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 04:20:49.391  5673  5719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 04:20:49.391  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-29 04:20:49.391  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-29 04:20:49.391  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-29 04:20:49.391  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-29 04:20:49.391  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-29 04:20:49.392  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-29 04:20:49.393  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-29 04:20:49.394  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-29 04:20:49.394  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 04:20:49.394  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-29 04:20:49.394  5673  5673 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-29 04:20:49.394  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-29 04:20:49.394  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-29 04:20:49.394  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 04:20:49.394  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-29 04:20:49.394  5673  5673 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-29 04:20:49.398  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-29 04:20:49.398  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 04:20:49.398  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 04:20:49.399  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 04:20:49.399  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 04:20:49.399  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 04:20:49.400  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-29 04:20:49.400  5673  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 04:20:49.400  5673  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 04:20:49.400  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 04:20:49.400  5673  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 04:20:49.400  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 04:20:49.400  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 04:20:49.400  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 04:20:49.400  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 04:20:49.401  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-29 04:20:49.403  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:20:49.404  5673  5719 D BluetoothLeScanner: could not find callback wrapper
09-29 04:20:49.404  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 04:20:49.404  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-29 04:20:49.406  4647  4721 D BtGatt.AdvertiseManager: message : 1
09-29 04:20:49.408  4647  4721 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 04:20:49.420  4647  4719 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-29 04:20:49.420  4647  4719 D BtGatt.GattService: Client app is not null!
09-29 04:20:49.422  4647  4667 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 04:20:49.423  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 04:20:49.423  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 04:20:49.423  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-29 04:20:49.423  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-29 04:20:49.423  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-29 04:20:49.425  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 04:20:49.425  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 04:20:49.426  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 04:20:49.427  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 04:20:49.429  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 04:20:49.429  5673  5673 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-29 04:20:49.429  5673  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 04:20:49.429  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:20:49.429  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:20:49.429  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:20:49.430  5673  5719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-29 04:20:49.430  5673  5719 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-29 04:20:49.431  5673  5719 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-29 04:20:49.431  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-29 04:20:49.431  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 04:20:49.431  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-29 04:20:49.431  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 04:20:49.431  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:20:49.433  4667  4667 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33947]" dev="sockfs" ino=33947 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 04:20:49.433  4667  4667 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33947]" dev="sockfs" ino=33947 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 04:20:49.433  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-29 04:20:49.434  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 04:20:49.434  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 04:20:49.435  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 04:20:49.435  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 04:20:49.435  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-29 04:20:49.435  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:20:49.435  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-29 04:20:49.435  5673  5725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:49.438  5673  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-29 04:20:49.444  5673  5719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 04:20:49.444  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 04:20:49.448  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 04:20:49.449  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 04:20:49.449  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 04:20:49.452  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-29 04:20:49.453  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 04:20:49.453  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-29 04:20:49.453  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:20:49.453  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:20:49.453  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 04:20:49.454  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:20:49.456  4647  4890 D BtGatt.GattService: registerClient() - UUID=c32d25ca-545b-498a-8bb7-eca4903f0132
09-29 04:20:49.456  4647  4719 D BtGatt.GattService: onClientRegistered() - UUID=c32d25ca-545b-498a-8bb7-eca4903f0132, clientIf=5
,09-29 04:20:49.456  5673  5683 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-29 04:20:49.458  4647  4721 D BtGatt.AdvertiseManager: message : 0
09-29 04:20:49.461  4647  4721 D BtGatt.AdvertiseManager: starting multi advertising
09-29 04:20:49.471  4647  4719 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-29 04:20:49.478  4647  4719 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-29 04:20:49.478  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 04:20:49.479  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 04:20:49.480  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 04:20:49.481  5673  5719 I io.jxcore.node.ConnectionHelper: start: OK
09-29 04:20:49.482  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 04:20:49.482  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 04:20:49.482  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 04:20:49.482  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 04:20:49.482  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-29 04:20:49.482  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-29 04:20:49.485  5673  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-29 04:20:49.485  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 04:20:49.595   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-29 04:20:49.985  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
09-29 04:20:49.985  5673  5719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-29 04:20:49.985  5673  5719 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-29 04:20:49.986  5673  5719 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-29 04:20:49.986  5673  5719 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-29 04:20:49.986  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-29 04:20:49.986  5673  5673 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-29 04:20:49.987  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-29 04:20:49.987  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-29 04:20:49.987  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-29 04:20:49.987  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-29 04:20:49.987  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-29 04:20:49.987  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-29 04:20:49.987  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-29 04:20:49.987  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-29 04:20:49.987  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-29 04:20:49.989  4647  4721 D BtGatt.AdvertiseManager: message : 1
,09-29 04:20:49.990  4647  4721 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 04:20:50.015  4647  4719 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-29 04:20:50.016  4647  4719 D BtGatt.GattService: Client app is not null!
,09-29 04:20:50.017  4647  4890 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 04:20:50.018  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 04:20:50.018  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 04:20:50.018  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 04:20:50.018  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-29 04:20:50.018  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 04:20:50.019  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-29 04:20:50.019  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:20:50.019  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:20:50.019  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 04:20:50.020  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:20:50.023  4647  4878 D BtGatt.GattService: registerClient() - UUID=14fb8c80-b80e-42b8-ae83-736856f23a4c
09-29 04:20:50.023  4647  4719 D BtGatt.GattService: onClientRegistered() - UUID=14fb8c80-b80e-42b8-ae83-736856f23a4c, clientIf=5
,09-29 04:20:50.024  5673  5683 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-29 04:20:50.025  4647  4721 D BtGatt.AdvertiseManager: message : 0
,09-29 04:20:50.029  4647  4721 D BtGatt.AdvertiseManager: starting multi advertising
,09-29 04:20:50.039  4647  4719 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-29 04:20:50.045  4647  4719 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-29 04:20:50.046  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-29 04:20:50.046  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 04:20:50.046  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 04:20:50.046  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 04:20:50.046  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 04:20:50.046  5673  5719 I io.jxcore.node.ConnectionHelper: start: OK
09-29 04:20:50.047  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 04:20:50.047  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 04:20:50.047  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 04:20:50.047  5673  5719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 04:20:50.047  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-29 04:20:50.048  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 04:20:50.048  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 04:20:50.048  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 04:20:50.048  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 04:20:50.048  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-29 04:20:50.048  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 04:20:50.048  5673  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-29 04:20:50.048  5673  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 04:20:50.048  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 04:20:50.048  5673  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 04:20:50.048  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-29 04:20:50.048  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 04:20:50.048  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 04:20:50.048  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 04:20:50.048  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 04:20:50.049  5673  5719 D BluetoothAdapter: STATE_ON
,09-29 04:20:50.049  5673  5719 D BluetoothLeScanner: could not find callback wrapper
09-29 04:20:50.049  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 04:20:50.049  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-29 04:20:50.050  4647  4721 D BtGatt.AdvertiseManager: message : 1
09-29 04:20:50.051  4647  4721 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 04:20:50.057  4647  4719 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-29 04:20:50.057  4647  4719 D BtGatt.GattService: Client app is not null!
09-29 04:20:50.057  4647  4667 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 04:20:50.058  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 04:20:50.058  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 04:20:50.058  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-29 04:20:50.058  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-29 04:20:50.058  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-29 04:20:50.059  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:20:50.059  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 04:20:50.059  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 04:20:50.060  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 04:20:50.061  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 04:20:50.061  5673  5673 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-29 04:20:50.061  5673  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 04:20:50.061  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:20:50.061  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:20:50.061  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 04:20:50.063  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,09-29 04:20:50.063  5673  5719 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-29 04:20:50.065  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-29 04:20:50.065  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-29 04:20:50.067  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
09-29 04:20:50.067  5673  5719 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-29 04:20:50.068  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-29 04:20:50.068  5673  5719 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-29 04:20:50.069  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,09-29 04:20:50.069  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 04:20:50.069  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 04:20:50.069  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 04:20:50.069  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 04:20:50.069  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 04:20:50.070  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 04:20:50.070  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 04:20:50.070  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-29 04:20:50.070  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 04:20:50.070  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 04:20:50.070  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 04:20:50.070  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 04:20:50.070  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-29 04:20:50.071  5673  5719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 04:20:50.072  5673  5719 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 04:20:50.072  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-29 04:20:50.076  5673  5719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-29 04:20:50.076  5673  5719 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-29 04:20:50.076  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-29 04:20:50.076  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-29 04:20:50.077  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-29 04:20:50.077  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-29 04:20:50.077  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-29 04:20:50.077  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 04:20:50.077  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 04:20:50.077  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-29 04:20:50.077  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 04:20:50.078  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-29 04:20:50.079  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 04:20:50.079  5673  5719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-29 04:20:50.080  5673  5719 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 04:20:50.080  5673  5719 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-29 04:20:50.080  5673  5719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-29 04:20:50.081  5673  5719 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 04:20:50.081  5673  5719 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-29 04:20:50.081  5673  5719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 04:20:50.081  5673  5719 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 04:20:50.081  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-29 04:20:50.086  4669  4669 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33953]" dev="sockfs" ino=33953 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 04:20:50.087  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-29 04:20:50.088  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-29 04:20:50.088  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-29 04:20:50.088  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-29 04:20:50.088  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-29 04:20:50.088  5673  5719 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-29 04:20:50.088  5673  5719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-29 04:20:50.086  4669  4669 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33953]" dev="sockfs" ino=33953 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 04:20:50.089  5673  5719 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-29 04:20:50.089  5673  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
09-29 04:20:50.089  5673  5729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-29 04:20:50.089  5673  5729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:50.090  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-29 04:20:50.090  5673  5719 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-29 04:20:50.091  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-29 04:20:50.091  5673  5719 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-29 04:20:50.092  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,09-29 04:20:50.092  5673  5719 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-29 04:20:50.092  5673  5719 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-29 04:20:50.092  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 04:20:50.093  5673  5719 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-29 04:20:50.093  5673  5719 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-29 04:20:50.093  5673  5719 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-29 04:20:50.093  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 04:20:50.093  5673  5719 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-29 04:20:50.093  5673  5719 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-29 04:20:50.093  5673  5719 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 04:20:50.093  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 04:20:50.093  5673  5719 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-29 04:20:50.094  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-29 04:20:50.094  5673  5719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-29 04:20:50.094  5673  5719 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-29 04:20:50.094  5673  5719 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-29 04:20:50.094  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-29 04:20:50.094  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-29 04:20:50.094  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-29 04:20:50.094  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 04:20:50.094  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:20:50.095  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-29 04:20:50.095  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 04:20:50.096  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 04:20:50.096  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 04:20:50.096  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-29 04:20:50.096  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:20:50.096  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 04:20:50.096  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 04:20:50.097  5673  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:50.100  5673  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-29 04:20:50.096  4878  4878 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34979]" dev="sockfs" ino=34979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 04:20:50.096  4878  4878 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[34979]" dev="sockfs" ino=34979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 04:20:50.100  5673  5719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 04:20:50.100  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 04:20:50.104  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 04:20:50.105  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 04:20:50.105  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 04:20:50.108  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-29 04:20:50.108  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 04:20:50.108  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-29 04:20:50.108  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:20:50.108  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:20:50.109  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 04:20:50.109  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:20:50.112  4647  4889 D BtGatt.GattService: registerClient() - UUID=0d1aca1e-a4cb-4944-a547-8035604b5b49
09-29 04:20:50.112  4647  4719 D BtGatt.GattService: onClientRegistered() - UUID=0d1aca1e-a4cb-4944-a547-8035604b5b49, clientIf=5
09-29 04:20:50.113  5673  5684 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-29 04:20:50.114  4647  4721 D BtGatt.AdvertiseManager: message : 0
09-29 04:20:50.117  4647  4721 D BtGatt.AdvertiseManager: starting multi advertising
09-29 04:20:50.125  4647  4719 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-29 04:20:50.129  4647  4719 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-29 04:20:50.130  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 04:20:50.130  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 04:20:50.131  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 04:20:50.132  5673  5719 I io.jxcore.node.ConnectionHelper: start: OK
09-29 04:20:50.132  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 04:20:50.132  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 04:20:50.132  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 04:20:50.132  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 04:20:50.132  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-29 04:20:50.132  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-29 04:20:50.134  5673  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 04:20:50.134  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 04:20:50.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 04:20:50.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 04:20:50.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-29 04:20:50.633  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 04:20:50.634  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-29 04:20:50.634  5673  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 04:20:50.634  5673  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-29 04:20:50.634  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 04:20:50.634  5673  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 04:20:50.634  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 04:20:50.634  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-29 04:20:50.635  5673  5673 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-29 04:20:50.636  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-29 04:20:50.636  5673  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 04:20:50.638  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc836d removed from the list
,09-29 04:20:50.638  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 04:20:50.638  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-29 04:20:50.638  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 04:20:50.639  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-29 04:20:50.639  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 04:20:50.639  5673  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
,09-29 04:20:50.639  5673  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
09-29 04:20:50.640  4647  4867 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-29 04:20:50.640  5673  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
09-29 04:20:50.640  5673  5729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
09-29 04:20:50.641  5673  5719 D BluetoothAdapter: STATE_ON
,09-29 04:20:50.641  5673  5719 D BluetoothLeScanner: could not find callback wrapper
09-29 04:20:50.641  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 04:20:50.641  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-29 04:20:50.643  4647  4721 D BtGatt.AdvertiseManager: message : 1
,09-29 04:20:50.644  4647  4721 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 04:20:50.657  4647  4719 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-29 04:20:50.657  4647  4719 D BtGatt.GattService: Client app is not null!
,09-29 04:20:50.659  4647  4669 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 04:20:50.660  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 04:20:50.660  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-29 04:20:50.660  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-29 04:20:50.660  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-29 04:20:50.660  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-29 04:20:50.662  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:20:50.662  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 04:20:50.663  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-29 04:20:50.664  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 04:20:50.665  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:20:50.665  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdd5ba2 removed from the list
09-29 04:20:50.665  5673  5719 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 04:20:50.665  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:20:50.665  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 04:20:50.666  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:20:50.668  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
09-29 04:20:50.669  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-29 04:20:50.670  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:20:50.671  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-29 04:20:50.671  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-29 04:20:50.672  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 04:20:50.672  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 04:20:50.672  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 04:20:50.672  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 04:20:50.673  5673  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 04:20:50.674  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
09-29 04:20:50.675  5673  5719 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-29 04:20:50.675  5673  5719 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-29 04:20:50.675  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 04:20:50.675  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 04:20:50.675  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 04:20:50.677  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
09-29 04:20:50.677  5673  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-29 04:20:50.673  4889  4889 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32067]" dev="sockfs" ino=32067 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 04:20:50.673  4889  4889 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32067]" dev="sockfs" ino=32067 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 04:20:50.683  5673  5719 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,09-29 04:20:50.684  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 04:20:50.684  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 04:20:50.684  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 04:20:50.684  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 04:20:50.684  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 04:20:50.684  5673  5732 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 04:20:50.684  5673  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 04:20:50.684  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-29 04:20:50.685  5673  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 04:20:50.685  5673  5719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc836d not in the list
09-29 04:20:50.685  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 04:20:50.685  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 04:20:50.685  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 04:20:50.685  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 04:20:50.685  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-29 04:20:50.685  5673  5719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 04:20:50.685  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 04:20:50.685  5673  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 04:20:50.686  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:20:50.687  5673  5719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdd5ba2 not in the list
09-29 04:20:50.687  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-29 04:20:50.687  5673  5719 D io.jxcore.node.ConnectivityMonitor: stop
09-29 04:20:50.687  5673  5719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 04:20:50.687  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:20:50.687  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 04:20:50.687  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:20:50.688  5673  5719 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
09-29 04:20:50.689  5673  5719 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-29 04:20:50.689  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 04:20:50.689  5673  5719 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-29 04:20:50.689  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 04:20:50.689  5673  5719 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-29 04:20:50.689  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 04:20:50.690  5673  5719 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,09-29 04:20:50.690  5673  5719 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,09-29 04:20:50.692  5673  5719 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
09-29 04:20:50.692  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-29 04:20:50.693  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-29 04:20:50.693  5673  5719 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
09-29 04:20:50.694  5673  5719 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-29 04:20:50.694  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 04:20:50.694  5673  5719 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-29 04:20:50.694  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 04:20:50.694  5673  5719 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-29 04:20:50.694  5673  5719 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-29 04:20:50.695  5673  5719 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-29 04:20:50.695  5673  5719 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-29 04:20:50.695  5673  5719 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-29 04:20:50.696  5673  5719 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
09-29 04:20:50.696  5673  5719 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-29 04:20:50.696  5673  5719 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-29 04:20:50.696  5673  5719 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-29 04:20:50.696  5673  5719 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-29 04:20:50.697  5673  5719 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,09-29 04:20:50.698  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 04:20:50.698  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@437f152 added. We now have 3 listener(s)
,09-29 04:20:50.700  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 04:20:50.700  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 04:20:50.700  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 04:20:50.700  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 04:20:50.700  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec4ec23 added. We now have 3 listener(s)
09-29 04:20:50.700  5673  5719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 04:20:50.701  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 04:20:50.703  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 04:20:50.707  5673  5719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 04:20:50.707  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:50.707  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:50.707  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:50.707  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:50.707  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 04:20:50.707  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 04:20:50.707  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 04:20:50.709  5673  5719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 04:20:50.709  5673  5719 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 04:20:50.710  5673  5719 D BluetoothAdapter: enable(): BT is already enabled..!
09-29 04:20:50.711   930  3820 D WifiService: setWifiEnabled: true pid=5673, uid=10077
09-29 04:20:50.711   930  3820 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-29 04:20:50.711  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:50.712  5673  5719 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,09-29 04:20:50.714  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:50.716  5673  5719 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,09-29 04:20:50.716  5673  5719 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-29 04:20:50.719   930  3203 D WifiService: setWifiEnabled: false pid=5673, uid=10077
,09-29 04:20:50.719   930  3203 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 04:20:50.722   930  3022 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-29 04:20:50.722   930  3022 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-29 04:20:50.722   930  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 04:20:50.722   930  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 04:20:50.730   930  5403 D DhcpClient: Clearing IP address
,09-29 04:20:50.731   507   924 D CommandListener: Clearing all IP addresses on wlan0
,09-29 04:20:50.738   507   924 D CommandListener: Setting iface cfg
,09-29 04:20:50.746  3614  5457 V NativeCrypto: Read error: ssl=0x7f93d79800: I/O error during system call, Connection timed out
,09-29 04:20:50.747   930  5404 D DhcpClient: Receive thread stopped
09-29 04:20:50.748  3614  5457 V NativeCrypto: SSL shutdown failed: ssl=0x7f93d79800: I/O error during system call, Broken pipe
09-29 04:20:50.749   930  3820 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-29 04:20:50.750   930  5401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-29 04:20:50.752   930  5401 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-29 04:20:50.752   930  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-29 04:20:50.752   930  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 04:20:50.753   930  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-29 04:20:50.755   930  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-29 04:20:50.755   930  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-29 04:20:50.760   533   533 E Parcel  : Reading a NULL string not supported here.
09-29 04:20:50.761   930   930 D RttService: SCAN_AVAILABLE : 1
09-29 04:20:50.762   930  3130 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-29 04:20:50.762   930  3024 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-29 04:20:50.764  3800  3955 W QCNEJ   : |CORE| network lost: 100
,09-29 04:20:50.765  3800  3955 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-29 04:20:50.766   930  3869 I ActivityManager: Killing 5080:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,09-29 04:20:50.770   930  3022 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-29 04:20:50.790   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 04:20:50.811   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 04:20:50.813   930  3024 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-29 04:20:50.813   930  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-29 04:20:50.822   930  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 04:20:50.823   507   924 D CommandListener: Clearing all IP addresses on wlan0
,09-29 04:20:50.825   930   947 D Tethering: MasterInitialState.processMessage what=3
,09-29 04:20:50.830   930  3022 D DhcpClient: doQuit
,09-29 04:20:50.830   930  3022 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-29 04:20:50.831   930  5403 D DhcpClient: onQuitting
09-29 04:20:50.832  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:50.832  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:50.832  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:50.832  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:50.832  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:50.832  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:50.832  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:50.832  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:20:50.832  3501  3501 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-29 04:20:50.836  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:50.828  5283  5283 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4e979d3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-29 04:20:50.840  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:50.840  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:50.840  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:50.840  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 04:20:50.840  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:50.840  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:50.840  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:50.840  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:50.840  3917  3917 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-29 04:20:50.842  5068  5090 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-29 04:20:50.842  5068  5090 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 04:20:50.843  5068  5090 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-29 04:20:50.843  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:50.843  5068  5090 E SarControlService: no key has been found,reset the power
09-29 04:20:50.843  5068  5102 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 04:20:50.843  5068  5102 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 04:20:50.843  5068  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 04:20:50.843  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 04:20:50.844  5093  5093 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 04:20:50.845  5068  5102 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-29 04:20:50.845  5068  5102 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 04:20:50.847  5068  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 04:20:50.848  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 04:20:50.848  5093  5093 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-29 04:20:50.849  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:50.849  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:50.849  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:50.849  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 04:20:50.849  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:50.849  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:50.849  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:50.849  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:20:50.849  3917  3917 D SystemUpdateService: onCreate
09-29 04:20:50.851  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e50fe11 HexData = [00000000ea03000000000000ffffffff]
09-29 04:20:50.851  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 04:20:50.851  5093  5107 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-29 04:20:50.851  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 04:20:50.851  5068  5079 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 04:20:50.852  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:50.855  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:50.855  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:50.855  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:50.855  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 04:20:50.855  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:50.855  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:50.855  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:50.855  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:50.856  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:50.857  3917  3917 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-29 04:20:50.858  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e50fe11 HexData = [00000000eb03000000000000ffffffff]
09-29 04:20:50.858  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:50.858  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 04:20:50.858  5093  5107 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-29 04:20:50.859  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 04:20:50.859  5068  5078 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-29 04:20:50.859  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:50.861  3501  3501 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-29 04:20:50.865  3501  3501 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-29 04:20:50.865  3917  5742 I SystemUpdateService: active receiver: enabled
,09-29 04:20:50.876  3917  3917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-29 04:20:50.881  3917  5428 I iu.UploadsManager: num queued entries: 0
,09-29 04:20:50.881  3917  5428 I iu.UploadsManager: num updated entries: 0
09-29 04:20:50.883  3917  3917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-29 04:20:50.884  3917  3917 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-29 04:20:50.886  5431  5431 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 04:20:50.891  5431  5431 D SprintDMHelper: simOperator: 
,09-29 04:20:50.891  5431  5431 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-29 04:20:50.893   507   924 E Netd    : netlink response contains error (No such file or directory)
,09-29 04:20:50.894   930  3024 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-29 04:20:50.897  3501  3501 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-29 04:20:50.901  3917  5742 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 04:20:50.903  3917  5428 I iu.SyncManager: NEXT; no task
,09-29 04:20:50.904  5043  5746 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-29 04:20:50.906  3501  3501 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-29 04:20:50.906  3917  5742 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-29 04:20:50.906  3917  5742 I SystemUpdateService: now status is 0 (complete)
09-29 04:20:50.906  3917  5742 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-29 04:20:50.906  3917  5742 I SystemUpdateService: file has been verified
09-29 04:20:50.907  3917  5742 I SystemUpdateService: OTA package size = 21989297
,09-29 04:20:50.912  3917  5742 I SystemUpdateService: showing system update notification
,09-29 04:20:50.917   930  3203 I ActivityManager: Start proc 5747:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-29 04:20:50.918   930  3022 D wifi    : In wifi stop Hal
09-29 04:20:50.918   930  3022 D wifi    : halHandle = 0x7f92428080, mVM = 0x7faea4d140, mCls = 0x100a02
09-29 04:20:50.918   930  3500 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 04:20:50.918   930  3500 D WifiHAL : Got a signal to exit!!!
09-29 04:20:50.919   930  3500 I WifiHAL : Exit wifi_event_loop
09-29 04:20:50.919   930  3022 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-29 04:20:50.919  5043  5043 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 04:20:50.919   930  3022 E WifiHAL : Event processing terminated
09-29 04:20:50.919   930  3022 D wifi    : In wifi cleaned up handler
09-29 04:20:50.919   930  3022 I WifiHAL : Internal cleanup completed
09-29 04:20:50.922  4140  4266 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 04:20:50.922  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:50.923  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:50.924  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:50.931  3917  3917 D SystemUpdateService: onDestroy
,09-29 04:20:50.954   930  3500 D wifi    : set interface wlan0 flags (DOWN)
,09-29 04:20:50.954   930  3022 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 04:20:50.969  5747  5747 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-29 04:20:50.977   930  3814 I ActivityManager: Killing 5008:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-29 04:20:51.021   507   924 E Netd    : netlink response contains error (No such file or directory)
,09-29 04:20:51.158   930   947 D Tethering: InitialState.processMessage what=4
,09-29 04:20:51.162   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 04:20:51.187  5673  5673 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 04:20:51.224  5673  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:51.227   930   940 D WifiService: setWifiEnabled: true pid=5673, uid=10077
,09-29 04:20:51.227   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 04:20:51.235   507   924 D SoftapController: Softap fwReload - Ok
,09-29 04:20:51.240   507   924 D CommandListener: Setting iface cfg
,09-29 04:20:51.240   507   924 D CommandListener: Trying to bring down wlan0
09-29 04:20:51.241   507   924 D CommandListener: Clearing all IP addresses on wlan0
,09-29 04:20:51.245   930  3022 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 04:20:51.735   930  3869 D WifiService: setWifiEnabled: true pid=5673, uid=10077
09-29 04:20:51.738   930  3869 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 04:20:51.857   930  3022 D wifi    : set interface wlan0 flags (UP)
09-29 04:20:51.858   930  3022 I WifiHAL : Initializing wifi
09-29 04:20:51.858   930  3022 I WifiHAL : Creating socket
09-29 04:20:51.864   930  3022 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-29 04:20:51.864   930  3022 D wifi    : Did set static halHandle = 0x7f92428080
,09-29 04:20:51.864   930  3022 D wifi    : halHandle = 0x7f92428080, mVM = 0x7faea4d140, mCls = 0x182a
09-29 04:20:51.864   930  3022 D wifi    : array field set
09-29 04:20:51.865   930  3022 I WifiNative-HAL: interface[0] = wlan0
09-29 04:20:51.866   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-29 04:20:51.868   930  5769 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547914678400
,09-29 04:20:51.869   930  5769 D wifi    : waitForHalEvents called, vm = 0x7faea4d140, obj = 0x182a, env = 0x7f94552fc0
,09-29 04:20:51.941  5770  5770 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 04:20:51.963  5770  5770 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 04:20:51.968   930  3022 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-29 04:20:51.972  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:51.974  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:51.976  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:51.991  5770  5770 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 04:20:51.991  5770  5770 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-29 04:20:52.006   930  3022 D WifiConfigStore: Loading config and enabling all networks 
,09-29 04:20:52.011  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:52.011  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:52.011  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:52.011  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:52.011  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:52.011  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:52.011  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:52.011  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:20:52.013  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:52.016  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:52.016  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:52.016  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:52.016  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:52.016  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:52.016  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:52.016  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:52.016  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:20:52.018   930  3022 D WifiConfigStore: loaded 0 passpoint configs
,09-29 04:20:52.018   930  3022 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-29 04:20:52.018  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:52.019   930  3022 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-29 04:20:52.020   930  3022 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-29 04:20:52.021   930  3022 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-29 04:20:52.021   930  3022 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-29 04:20:52.021   930  3022 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-29 04:20:52.021   930  3022 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-29 04:20:52.023  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:52.023  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:52.023  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:52.023  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:52.023  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:52.023  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:52.023  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:52.023  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:52.024  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:52.025  5043  5043 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 04:20:52.025   930  3022 D WifiNative-HAL: Setting external_sim to 1
09-29 04:20:52.026   930  3022 D wifi    : setting dfs flag to true, 0x7f9706bfc0
09-29 04:20:52.026   930  3022 D WifiStateMachine: Setting OUI to DA-A1-19
09-29 04:20:52.026   930  3022 D wifi    : setting scan oui 0x7f9706bfc0
09-29 04:20:52.026   930  3022 D WifiHAL : Sending mac address OUI
,09-29 04:20:52.030   930  3022 E native  : do suspend false
,09-29 04:20:52.037   930  3022 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-29 04:20:52.037   930   930 D RttService: SCAN_AVAILABLE : 3
09-29 04:20:52.037   930  3130 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-29 04:20:52.037   507   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-29 04:20:52.038   507   924 D CommandListener: Setting iface cfg
,09-29 04:20:52.042   930  3021 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-29 04:20:52.042   930  3021 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 04:20:52.050   930  3021 D WifiNative-HAL: p2pGetDeviceAddress
,09-29 04:20:52.054   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=151506 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
09-29 04:20:52.054   930  3021 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-29 04:20:52.241  5673  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:52.256  4647  4715 D BluetoothAdapterState: Current state: ON, message: 23
,09-29 04:20:52.256  4647  4715 D BluetoothAdapterProperties: Setting state to 13
,09-29 04:20:52.257  4647  4715 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-29 04:20:52.258  4647  4715 D BluetoothAdapterProperties: onBluetoothDisable()
09-29 04:20:52.259  4647  4715 I BluetoothAdapterState: Entering PendingCommandState
09-29 04:20:52.262  4647  4647 D BluetoothMapService: onReceive
09-29 04:20:52.262  4647  4647 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 04:20:52.262  4647  4647 D BluetoothMapService: STATE_TURNING_OFF
09-29 04:20:52.262  4647  4647 D BluetoothMapService: MAP Service closeService in
09-29 04:20:52.262  4647  4647 D BluetoothMapMasInstance0: MAP Service shutdown
09-29 04:20:52.262  4647  4647 D ObexServerSockets0: shutdown(block = true)
09-29 04:20:52.263  4647  4647 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 04:20:52.263  4647  4892 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-29 04:20:52.263  4647  4647 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 04:20:52.264  4647  4867 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-29 04:20:52.264  4647  4893 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-29 04:20:52.266  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:52.266  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:52.266  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:52.266  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:52.266  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:52.266  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 04:20:52.266  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:52.266  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:52.266  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:20:52.267  4647  4647 I BtOppRfcommListener: stopping Accept Thread
09-29 04:20:52.267  4647  5341 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-29 04:20:52.267  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:52.267  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:52.267  4647  5341 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-29 04:20:52.270  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:52.270  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:52.270  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:52.270  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:52.270  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:52.270  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 04:20:52.270  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:52.270  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:52.270  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:52.272  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:52.272  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:52.275  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:52.275  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:52.275  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:52.275  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:52.275  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:52.275  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 04:20:52.275  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:52.275  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:52.275  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:52.276  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:52.276  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:52.282   930   943 I ActivityManager: Start proc 5785:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-29 04:20:52.283  4647  4719 D BluetoothAdapterProperties: Scan Mode:20
,09-29 04:20:52.284  4647  4715 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-29 04:20:52.287  4647  4647 D HeadsetService: Received stop request...Stopping profile...
09-29 04:20:52.287  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:52.289   930   930 D BluetoothHeadset: Proxy object disconnected
09-29 04:20:52.289   930   930 D BluetoothHeadset: Proxy object disconnected
,09-29 04:20:52.289   930   930 D BluetoothHeadset: Proxy object disconnected
09-29 04:20:52.289  3852  4039 D BluetoothHeadset: Proxy object disconnected
,09-29 04:20:52.289  4647  4647 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:52.290  4647  4647 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:52.290  4647  4647 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:52.290  4647  4647 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:52.290  3177  3195 D BluetoothHeadset: Proxy object disconnected
09-29 04:20:52.290  4647  4647 D A2dpService: Received stop request...Stopping profile...
09-29 04:20:52.291  4647  4884 D A2dpStateMachine: Exit Disconnected: -1
09-29 04:20:52.292  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:52.293  3177  3177 D HeadsetProfile: Bluetooth service disconnected
09-29 04:20:52.294   930   930 D BluetoothA2dp: Proxy object disconnected
09-29 04:20:52.294  3177  3177 D BluetoothA2dp: Proxy object disconnected
09-29 04:20:52.295  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:52.298  4647  4647 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-29 04:20:52.298  4647  4647 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 04:20:52.298  4647  4862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 04:20:52.298  4647  4862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 04:20:52.298  4647  4862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 04:20:52.298  4647  4719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-29 04:20:52.299  4647  4719 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-29 04:20:52.300  4647  4647 D HidService: Received stop request...Stopping profile...
09-29 04:20:52.300  4647  4647 D HidService: Stopping Bluetooth HidService
09-29 04:20:52.301  4647  4647 D HealthService: Received stop request...Stopping profile...
09-29 04:20:52.301  3177  3177 D BluetoothInputDevice: Proxy object disconnected
09-29 04:20:52.302  3177  3177 D HidProfile: Bluetooth service disconnected
09-29 04:20:52.303  4647  4647 D PanService: Received stop request...Stopping profile...
,09-29 04:20:52.303  3177  3177 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 04:20:52.303  3177  3177 D PanProfile: Bluetooth service disconnected
09-29 04:20:52.304  4647  4647 V BluetoothAdapterState: isTurningOff()=true
,09-29 04:20:52.304  4647  4647 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:52.304  4647  4647 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:52.304  4647  4647 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:52.305  4647  4647 D BluetoothMapService: Received stop request...Stopping profile...
09-29 04:20:52.305  4647  4647 D BluetoothMapService: stop()
,09-29 04:20:52.305  4647  4647 D BluetoothMapAppObserver: deinitObservers()
09-29 04:20:52.305  4647  4647 D BluetoothMapAppObserver: removeReceiver()
09-29 04:20:52.307  3177  3177 D BluetoothMap: Proxy object disconnected
09-29 04:20:52.307  3177  3177 D MapProfile: Bluetooth service disconnected
,09-29 04:20:52.309  4647  4862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-29 04:20:52.309  4647  4862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 04:20:52.309  4647  4647 D SapService: Received stop request...Stopping profile...
09-29 04:20:52.309  4647  4647 V SapService: stop()
09-29 04:20:52.309  4647  4862 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 04:20:52.309  4647  4862 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 04:20:52.309  4647  4862 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 04:20:52.309  4647  4862 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 04:20:52.310  4647  4719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-29 04:20:52.310  4647  4647 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:52.311  4647  4647 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:52.311  4647  4647 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:52.311  4647  4647 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:52.311  4647  4647 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:52.311  4647  4647 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:52.311  4647  4647 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:52.311  4647  4647 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:52.312  4647  4647 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-29 04:20:52.312  4647  4719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 04:20:52.312  4647  4647 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 04:20:52.312  4647  4647 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-29 04:20:52.312  4647  4719 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-29 04:20:52.313  4647  4647 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-29 04:20:52.313  4647  4647 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:52.313  4647  4647 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:52.313  4647  4647 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:52.314  4647  4647 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:52.314  4647  4647 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-29 04:20:52.314  4647  4647 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-29 04:20:52.315  4647  4647 D BluetoothMapService: MAP Service closeService in
,09-29 04:20:52.315  4647  4647 V BluetoothAdapterState: isTurningOff()=true
,09-29 04:20:52.315  4647  4647 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:52.315  4647  4647 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:52.316  4647  4647 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:52.316  4647  4647 D BluetoothMapService: cleanup()
09-29 04:20:52.316  4647  4647 D BluetoothMapService: MAP Service closeService in
09-29 04:20:52.316  4647  4647 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:52.316  4647  4647 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:52.316  4647  4647 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 04:20:52.316  4647  4647 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:52.316  4647  4715 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-29 04:20:52.317  4647  4715 D BluetoothAdapterProperties: Setting state to 15
09-29 04:20:52.317  4647  4715 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-29 04:20:52.318  3177  3193 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 04:20:52.318  3177  3991 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 04:20:52.318  4647  4715 I BluetoothAdapterState: Entering BleOnState
,09-29 04:20:52.320   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-29 04:20:52.321  3177  3195 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-29 04:20:52.322  3177  3193 D BluetoothMap: onBluetoothStateChange: up=false
,09-29 04:20:52.322  3177  3991 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 04:20:52.323   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 04:20:52.323   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 04:20:52.323   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 04:20:52.325  3852  3875 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 04:20:52.325  3177  3195 D BluetoothPan: onBluetoothStateChange on: false
09-29 04:20:52.326  4647  4715 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-29 04:20:52.326  4647  4715 D BluetoothAdapterProperties: Setting state to 16
09-29 04:20:52.326  4647  4715 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 04:20:52.327  4647  4715 D BluetoothAdapterProperties: onBleDisable
09-29 04:20:52.327  4647  4715 I BluetoothAdapterState: Entering PendingCommandState
,09-29 04:20:52.328  4647  4716 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-29 04:20:52.328  5785  5785 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-29 04:20:52.329  4647  4719 D BluetoothAdapterProperties: Scan Mode:20
09-29 04:20:52.329  4647  4862 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 04:20:52.329  4647  4862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-29 04:20:52.331  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:52.333  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:52.334  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:52.336  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:52.337  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:52.338  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:52.344  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 04:20:52.350   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b714b63:true
09-29 04:20:52.351  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 04:20:52.367   930  3869 I ActivityManager: Start proc 5797:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-29 04:20:52.374  5785  5785 D LocalBluetoothProfileManager: Adding local MAP profile
09-29 04:20:52.379  5785  5785 D BluetoothMap: Create BluetoothMap proxy object
,09-29 04:20:52.388  5785  5785 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-29 04:20:52.403  5797  5797 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-29 04:20:52.407  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-29 04:20:52.410   930  3872 I ActivityManager: Killing 5283:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-29 04:20:52.536  4647  4719 I bt_hci  : shut_down
,09-29 04:20:52.538  4647  4723 D bt_hwcfg: hw_epilog_process
09-29 04:20:52.539  4647  4723 I bt_vendor: low_power_mode_cb
,09-29 04:20:52.542  4647  4723 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-29 04:20:52.542  4647  4723 I bt_vendor: epilog_cb
,09-29 04:20:52.542  4647  4723 I bt_hci  : epilog_finished_callback
,09-29 04:20:52.544  4647  4719 I bt_hci_h4: hal_close
09-29 04:20:52.544  4647  4719 I bt_userial_vendor: device fd = 54 close
,09-29 04:20:52.621  5797  5797 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-29 04:20:52.621  5797  5797 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 04:20:52.621  5797  5797 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 04:20:52.621  5797  5797 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 04:20:52.621  5797  5797 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.k.d(PG:583)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 04:20:52.621  5797  5797 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 04:20:52.621  5797  5797 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 04:20:52.621  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 04:20:52.622  5797  5797 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 04:20:52.622  5797  5797 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 04:20:52.622  5797  5797 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 04:20:52.625  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 04:20:52.631  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 04:20:52.642  5785  5785 D DockEventReceiver: finishStartingService: stopping service
09-29 04:20:52.643   930  3453 I ActivityManager: Killing 4729:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-29 04:20:52.687  4647  4716 D bt_stack_manager: event_shut_down_stack finished.
09-29 04:20:52.688  4647  4715 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-29 04:20:52.691  4647  4647 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 04:20:52.691  4647  4715 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-29 04:20:52.691  4647  4647 D BtGatt.GattService: Received stop request...Stopping profile...
09-29 04:20:52.691  4647  4647 D BtGatt.GattService: stop()
09-29 04:20:52.691  4647  4647 D BtGatt.AdvertiseManager: advertise clients cleared
09-29 04:20:52.693  4647  4647 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:52.693  4647  4647 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:52.693  4647  4647 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:52.693  4647  4647 V BluetoothAdapterState: isBleTurningOff()=true
09-29 04:20:52.694  4647  4715 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-29 04:20:52.694  4647  4715 D BluetoothAdapterProperties: Setting state to 10
09-29 04:20:52.694  4647  4715 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-29 04:20:52.695  4647  4715 I BluetoothAdapterState: Entering OffState
09-29 04:20:52.695   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-29 04:20:52.701  4647  4647 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-29 04:20:52.701  4647  4647 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-29 04:20:52.701  4647  4647 I BluetoothServiceJni: cleanupNative: return from cleanup
09-29 04:20:52.703  4647  4716 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-29 04:20:52.706  4647  4647 I art     : System.exit called, status: 0
,09-29 04:20:52.707  4647  4647 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-29 04:20:52.755  5673  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:52.757   380   380 E lowmemorykiller: Error writing /proc/4647/oom_score_adj; errno=22
,09-29 04:20:52.757   930   947 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,09-29 04:20:52.758   930   947 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
,09-29 04:20:52.759   930   947 W ActivityManager: Application dead when creating service ServiceRecord{c4b6c9a u0 com.android.bluetooth/.btservice.AdapterService}
,09-29 04:20:52.764   930   947 I ActivityManager: Process com.android.bluetooth (pid 4647) has died
,09-29 04:20:52.765   930   947 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-29 04:20:52.766   930   947 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
,09-29 04:20:52.767   930   947 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
09-29 04:20:52.767   930   947 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-29 04:20:52.767   930   947 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-29 04:20:52.767   930   947 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-29 04:20:52.767   930   947 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-29 04:20:52.767   930   947 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-29 04:20:52.767   930   947 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-29 04:20:52.767   930   947 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
09-29 04:20:52.767   930   947 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
09-29 04:20:52.767   930   947 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
09-29 04:20:52.767   930   947 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
09-29 04:20:52.767   930   947 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
09-29 04:20:52.767   930   947 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
09-29 04:20:52.767   930   947 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
09-29 04:20:52.767   930   947 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
09-29 04:20:52.767   930   947 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:20:52.767   930   947 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:20:52.767   930   947 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 04:20:52.767   930   947 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-29 04:20:52.767   930   940 W ActivityManager: Spurious death for ProcessRecord{284ac62 0:com.android.bluetooth/1002}, curProc for 4647: null
,09-29 04:20:52.867  5797  5820 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-29 04:20:52.876   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b9445a8:true
,09-29 04:20:55.204  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 04:20:55.209  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 04:20:55.214  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 04:20:55.219  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 04:20:55.756   930   947 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,09-29 04:20:55.798   930   947 I ActivityManager: Start proc 5831:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-29 04:20:55.895  5831  5831 D AdapterServiceConfig: Adding HeadsetService
,09-29 04:20:55.896  5831  5831 D AdapterServiceConfig: Adding A2dpService
09-29 04:20:55.896  5831  5831 D AdapterServiceConfig: Adding HidService
09-29 04:20:55.896  5831  5831 D AdapterServiceConfig: Adding HealthService
09-29 04:20:55.896  5831  5831 D AdapterServiceConfig: Adding PanService
09-29 04:20:55.896  5831  5831 D AdapterServiceConfig: Adding GattService
09-29 04:20:55.896  5831  5831 D AdapterServiceConfig: Adding BluetoothMapService
09-29 04:20:55.897  5831  5831 D AdapterServiceConfig: Adding SapService
,09-29 04:20:55.911   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b276e3e:true
,09-29 04:20:55.912  5831  5831 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 04:20:55.914  5831  5831 I bt_bluedroid: init
,09-29 04:20:55.915  5831  5843 I BluetoothAdapterState: Entering OffState
,09-29 04:20:55.917  5831  5844 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-29 04:20:55.917  5831  5844 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-29 04:20:55.917  5831  5844 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-29 04:20:55.918  5831  5844 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-29 04:20:55.918  5831  5831 I bt_bluedroid: get_profile_interface socket
,09-29 04:20:55.920  5831  5831 I bt_bluedroid: get_profile_interface sdp
09-29 04:20:55.920  5831  5847 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 04:20:55.922  5831  5847 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 04:20:55.927  5831  5842 I bt_bluedroid: config_hci_snoop_log
,09-29 04:20:55.928   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-29 04:20:55.933  5831  5843 D BluetoothAdapterState: Current state: OFF, message: 0
,09-29 04:20:55.933  5831  5843 D BluetoothAdapterProperties: Setting state to 14
09-29 04:20:55.933  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-29 04:20:55.934  5831  5843 D BluetoothBondStateMachine: make
,09-29 04:20:55.936  5831  5848 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 04:20:55.938  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
,09-29 04:20:55.939  5831  5831 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 04:20:55.941  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
09-29 04:20:55.942  5831  5831 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-29 04:20:55.942  5831  5831 D BtGatt.GattService: Received start request. Starting profile...
,09-29 04:20:55.942  5831  5831 D BtGatt.GattService: start()
09-29 04:20:55.943  5831  5831 I bt_bluedroid: get_profile_interface gatt
09-29 04:20:55.943  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
09-29 04:20:55.944  5831  5831 D BtGatt.AdvertiseManager: advertise manager created
,09-29 04:20:55.948  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:55.948  5831  5831 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:55.948  5831  5831 V BluetoothAdapterState: isBleTurningOn()=true
09-29 04:20:55.948  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:55.949  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-29 04:20:55.950  5831  5843 I bt_bluedroid: bt_bluedroid
,09-29 04:20:55.950  5831  5844 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-29 04:20:55.950  5831  5844 I bt_hci  : start_up
,09-29 04:20:55.955  5831  5844 I bt_vendor: alloc value 0xf3cd7871
,09-29 04:20:55.955  5831  5844 I bt_vendor: init
09-29 04:20:55.955  5831  5844 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-29 04:20:55.955  5831  5844 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 04:20:56.066  5831  5844 D bt_hci  : start_up starting async portion
,09-29 04:20:56.067  5831  5851 I bt_hci  : event_finish_startup
09-29 04:20:56.067  5831  5851 I bt_hci_h4: hal_open
09-29 04:20:56.067  5831  5851 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-29 04:20:56.063  5852  5852 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-29 04:20:56.068  5831  5851 I bt_userial_vendor: device fd = 54 open
,09-29 04:20:56.080  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 04:20:56.082  5831  5851 D bt_hwcfg: Chipset BCM4358A3
,09-29 04:20:56.082  5831  5851 D bt_hwcfg: Target name = [BCM4358A3]
09-29 04:20:56.082  5831  5851 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 04:20:56.278  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-29 04:20:56.467  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-29 04:20:56.467  5831  5851 D bt_hwcfg: Settlement delay -- 100 ms
,09-29 04:20:56.467  5831  5851 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 04:20:56.591  5831  5851 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 04:20:56.592  5831  5851 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-29 04:20:56.593  5831  5851 I bt_hwcfg: vendor lib fwcfg completed
09-29 04:20:56.593  5831  5851 I bt_vendor: firmware callback
09-29 04:20:56.593  5831  5851 I bt_hci  : firmware_config_callback
,09-29 04:20:56.603  5831  5854 I bt_btu  : btu_task pending for preload complete event
,09-29 04:20:56.604  5831  5854 I bt_btu_task: Bluetooth chip preload is complete
,09-29 04:20:56.604  5831  5854 I bt_btu  : btu_task received preload complete event
,09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_HCI
09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_AVRC
09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_A2D
09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_BNEP
09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTM
,09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_GAP
09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_PAN
09-29 04:20:56.612  5831  5854 I         : BTE_InitTraceLevels -- TRC_SDP
09-29 04:20:56.613  5831  5854 I         : BTE_InitTraceLevels -- TRC_GATT
09-29 04:20:56.613  5831  5854 I         : BTE_InitTraceLevels -- TRC_SMP
09-29 04:20:56.613  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-29 04:20:56.613  5831  5854 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 04:20:56.693  5831  5854 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c55549
09-29 04:20:56.694  5831  5854 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c55549 
,09-29 04:20:56.712  5831  5847 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 04:20:56.714  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 04:20:56.715  5831  5847 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 04:20:56.718  5831  5847 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 04:20:56.721  5831  5847 D BluetoothAdapterProperties: Scan Mode:20
09-29 04:20:56.722  5831  5847 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 04:20:56.722  5831  5847 D bt_hci  : do_postload posting postload work item
,09-29 04:20:56.722  5831  5851 I bt_hci  : event_postload
09-29 04:20:56.722  5831  5851 I bt_vendor: sco_config_cb
,09-29 04:20:56.722  5831  5851 I bt_hci  : sco_config_callback postload finished.
,09-29 04:20:56.726  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:56.728  5831  5847 D bt_bte_conf: Device ID record 1 : primary
09-29 04:20:56.728  5831  5847 D bt_bte_conf:   vendorId            = 000f
09-29 04:20:56.728  5831  5847 D bt_bte_conf:   vendorIdSource      = 0001
,09-29 04:20:56.729  5831  5847 D bt_bte_conf:   product             = 1200
09-29 04:20:56.729  5831  5847 D bt_bte_conf:   version             = 1436
,09-29 04:20:56.729  5831  5847 D bt_bte_conf:   clientExecutableURL = 
09-29 04:20:56.729  5831  5847 D bt_bte_conf:   serviceDescription  = 
,09-29 04:20:56.729  5831  5847 D bt_bte_conf:   documentationURL    = 
09-29 04:20:56.729  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:56.729  5831  5847 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-29 04:20:56.729  5831  5851 I bt_vendor: low_power_mode_cb
,09-29 04:20:56.729  5831  5844 D bt_stack_manager: event_start_up_stack finished
09-29 04:20:56.730  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 04:20:56.730  5831  5843 D BluetoothAdapterProperties: Setting state to 15
09-29 04:20:56.730  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-29 04:20:56.731  5831  5843 I BluetoothAdapterState: Entering BleOnState
09-29 04:20:56.732  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:56.735  5831  5843 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-29 04:20:56.735  5831  5843 D BluetoothAdapterProperties: Setting state to 11
09-29 04:20:56.735  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-29 04:20:56.743  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:56.745  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:56.749  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:56.749  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
09-29 04:20:56.750  5831  5831 D HeadsetService: Received start request. Starting profile...
09-29 04:20:56.754  5831  5831 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 04:20:56.754  5831  5831 D HeadsetStateMachine: make
09-29 04:20:56.759  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
,09-29 04:20:56.762  5831  5831 D HeadsetStateMachine: max_hf_connections = 1
09-29 04:20:56.762  5831  5831 I bt_bluedroid: get_profile_interface handsfree
,09-29 04:20:56.763  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-29 04:20:56.763  5831  5847 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-29 04:20:56.766  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
09-29 04:20:56.767  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 04:20:56.767  5831  5831 D A2dpService: Received start request. Starting profile...
09-29 04:20:56.768  5831  5831 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-29 04:20:56.769  5831  5831 I bt_bluedroid: get_profile_interface avrcp
,09-29 04:20:56.775  5831  5831 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-29 04:20:56.775  5831  5831 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 04:20:56.775  5831  5831 D A2dpStateMachine: make
,09-29 04:20:56.777  5831  5831 I bt_bluedroid: get_profile_interface a2dp
,09-29 04:20:56.779  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-29 04:20:56.780  5831  5831 I BluetoothHidServiceJni: classInitNative: succeeds
09-29 04:20:56.780  5831  5862 D A2dpStateMachine: Enter Disconnected: -2
09-29 04:20:56.781  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:20:56.783  5831  5831 D HidService: Received start request. Starting profile...
,09-29 04:20:56.783  5831  5831 I bt_bluedroid: get_profile_interface hidhost
09-29 04:20:56.783  5831  5831 D HidService: setHidService(): set to: null
09-29 04:20:56.783  5831  5847 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c3656d
09-29 04:20:56.783  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 04:20:56.784  5831  5831 I BluetoothHealthServiceJni: classInitNative: succeeds
09-29 04:20:56.784  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-29 04:20:56.784  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:20:56.785  5831  5831 D HealthService: Received start request. Starting profile...
,09-29 04:20:56.786  5785  5785 D BluetoothInputDevice: Proxy object connected
09-29 04:20:56.786  5831  5831 I bt_bluedroid: get_profile_interface health
09-29 04:20:56.786  5785  5785 D HidProfile: Bluetooth service connected
,09-29 04:20:56.787  5831  5831 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-29 04:20:56.788  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:20:56.789  5831  5831 D PanService: Received start request. Starting profile...
09-29 04:20:56.789  5831  5831 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-29 04:20:56.789  5831  5831 I bt_bluedroid: get_profile_interface pan
09-29 04:20:56.790  5831  5847 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-29 04:20:56.791  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
09-29 04:20:56.792  5785  5785 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 04:20:56.792  5831  5831 D BluetoothMapService: Received start request. Starting profile...
09-29 04:20:56.792  5831  5831 D BluetoothMapService: start()
09-29 04:20:56.793  5785  5785 D PanProfile: Bluetooth service connected
09-29 04:20:56.793  5785  5785 D BluetoothMap: Proxy object connected
09-29 04:20:56.793  5785  5785 D MapProfile: Bluetooth service connected
09-29 04:20:56.793  5785  5785 D BluetoothMap: getConnectedDevices()
09-29 04:20:56.794  5785  5785 D BluetoothMap: Bluetooth is Not enabled
,09-29 04:20:56.795  5831  5831 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-29 04:20:56.796  5831  5831 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-29 04:20:56.796  5831  5831 D BluetoothMapAppObserver: createReceiver()
09-29 04:20:56.797  5831  5831 D BluetoothMapAppObserver: initObservers()
09-29 04:20:56.797  5831  5831 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-29 04:20:56.802  5831  5831 V SapService: SapBinder()
,09-29 04:20:56.802  5831  5831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:20:56.803  5831  5831 D SapService: Received start request. Starting profile...
,09-29 04:20:56.803  5831  5831 V SapService: start()
,09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:56.806  5831  5860 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:56.806  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:56.807  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:56.808  5831  5831 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:56.808  5831  5831 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:56.808  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:56.808  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:56.808  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-29 04:20:56.808  5831  5843 D BluetoothAdapterProperties: ScanMode =  20
09-29 04:20:56.808  5831  5843 D BluetoothAdapterProperties: State =  11
09-29 04:20:56.808  5831  5843 D BluetoothAdapterProperties: Setting state to 12
09-29 04:20:56.808  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-29 04:20:56.809  5831  5843 I BluetoothAdapterState: Entering OnState
,09-29 04:20:56.809  3177  3193 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:56.809  3177  3991 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-29 04:20:56.810  5831  5847 D BluetoothAdapterProperties: Scan Mode:21
09-29 04:20:56.811  5831  5847 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 04:20:56.812  3177  3177 D BluetoothInputDevice: Proxy object connected
09-29 04:20:56.812  3177  3177 D HidProfile: Bluetooth service connected
09-29 04:20:56.813  5785  5796 D BluetoothMap: onBluetoothStateChange: up=true
09-29 04:20:56.813   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:56.813  3177  3193 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 04:20:56.815  5673  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-29 04:20:56.816  3177  3991 D BluetoothMap: onBluetoothStateChange: up=true
09-29 04:20:56.817  3177  3177 D BluetoothA2dp: Proxy object connected
,09-29 04:20:56.818  5673  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-29 04:20:56.819  3177  3193 D BluetoothPbap: onBluetoothStateChange: up=true
,09-29 04:20:56.820  3177  3177 D BluetoothMap: Proxy object connected
09-29 04:20:56.820  3177  3177 D MapProfile: Bluetooth service connected
09-29 04:20:56.820  3177  3177 D BluetoothMap: getConnectedDevices()
,09-29 04:20:56.821  5785  5795 D BluetoothPbap: onBluetoothStateChange: up=true
,09-29 04:20:56.823  5831  5831 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-29 04:20:56.824  5831  5831 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-29 04:20:56.824  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:56.824  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:56.824  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:56.824  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:56.824  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:56.824  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:56.824  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:56.824  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:20:56.825  5831  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:56.825  5785  5796 D BluetoothPan: onBluetoothStateChange on: true
09-29 04:20:56.826   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:56.827  5785  5795 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 04:20:56.827   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:56.827   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-29 04:20:56.827  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:56.828  5831  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:56.828   930   930 D BluetoothA2dp: Proxy object connected
09-29 04:20:56.828  3852  3875 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:56.829  3177  3991 D BluetoothPan: onBluetoothStateChange on: true
09-29 04:20:56.830  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:56.830  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:56.830  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:56.830  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:56.830  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:56.830  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:56.830  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:56.830  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:56.832  5831  5831 D ObexServerSockets: Succeed to create listening sockets 
09-29 04:20:56.832  5831  5831 D ObexServerSockets0: startAccept()
09-29 04:20:56.832  3177  3177 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 04:20:56.832  5831  5831 D ObexServerSockets0: prepareForNewConnect()
09-29 04:20:56.832  3177  3177 D PanProfile: Bluetooth service connected
09-29 04:20:56.832   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,09-29 04:20:56.834  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:56.834  5831  5831 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-29 04:20:56.835  5831  5831 D BluetoothSdpJni: SDP Create record success - handle: 0
09-29 04:20:56.835  5831  5868 D ObexServerSockets0: Accepting socket connection...
09-29 04:20:56.836  5831  5869 D ObexServerSockets0: Accepting socket connection...
09-29 04:20:56.837  5831  5831 D BluetoothMapService: onReceive
09-29 04:20:56.837  5785  5785 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-29 04:20:56.837  5831  5831 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 04:20:56.837  5831  5831 D BluetoothMapService: STATE_ON
09-29 04:20:56.837  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:56.837  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:56.837  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:56.837  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:56.837  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:56.837  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:56.837  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:56.837  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:56.839  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:56.840  5831  5871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:56.840  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:56.841  5785  5785 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-29 04:20:56.842  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:56.842  5831  5871 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-29 04:20:56.842  5831  5871 D BluetoothSdpJni: SDP Create record success - handle: 1
09-29 04:20:56.843  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:56.847  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 04:20:56.849  5785  5785 D BluetoothA2dp: Proxy object connected
,09-29 04:20:56.853  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 04:20:56.859  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-29 04:20:56.861  3177  3177 D BluetoothPbap: Proxy object connected
09-29 04:20:56.861  3177  3177 D PbapServerProfile: Bluetooth service connected
09-29 04:20:56.863  5785  5785 D BluetoothPbap: Proxy object connected
09-29 04:20:56.864  5785  5785 D PbapServerProfile: Bluetooth service connected
,09-29 04:20:56.866  5831  5831 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 04:20:56.866  5831  5831 D ObexServerSockets0: prepareForNewConnect()
,09-29 04:20:56.868  5831  5876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 04:20:56.882  5831  5880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 04:20:56.883  5831  5880 I BtOppRfcommListener: Accept thread started.
,09-29 04:20:56.911   930   930 D BluetoothHeadset: Proxy object connected
09-29 04:20:56.911   930   930 D BluetoothHeadset: Proxy object connected
,09-29 04:20:56.911   930   930 D BluetoothHeadset: Proxy object connected
,09-29 04:20:56.912  3852  4076 D BluetoothHeadset: Proxy object connected
09-29 04:20:56.912  3177  3991 D BluetoothHeadset: Proxy object connected
09-29 04:20:56.912  3177  3177 D HeadsetProfile: Bluetooth service connected
,09-29 04:20:56.914   930   947 D BluetoothHeadset: Proxy object connected
,09-29 04:20:56.927   930   947 D BluetoothHeadset: Proxy object connected
,09-29 04:20:56.928   930   947 D BluetoothHeadset: Proxy object connected
,09-29 04:20:56.929  3852  3876 D BluetoothHeadset: Proxy object connected
,09-29 04:20:56.944  5785  5795 D BluetoothHeadset: Proxy object connected
,09-29 04:20:56.945  5785  5785 D HeadsetProfile: Bluetooth service connected
,09-29 04:20:57.285  5673  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:57.288  5673  5719 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 04:20:57.288  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 04:20:57.297  5673  5719 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,09-29 04:20:57.300  5673  5719 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,09-29 04:20:57.304  5673  5719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:57.309  5831  5843 D BluetoothAdapterState: Current state: ON, message: 23
,09-29 04:20:57.309  5831  5843 D BluetoothAdapterProperties: Setting state to 13
09-29 04:20:57.309  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-29 04:20:57.311  5831  5843 D BluetoothAdapterProperties: onBluetoothDisable()
09-29 04:20:57.312  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
09-29 04:20:57.316  5831  5831 D BluetoothMapService: onReceive
,09-29 04:20:57.317  5831  5831 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 04:20:57.317  5831  5831 D BluetoothMapService: STATE_TURNING_OFF
,09-29 04:20:57.318  5831  5831 D BluetoothMapService: MAP Service closeService in
09-29 04:20:57.318  5831  5847 D BluetoothAdapterProperties: Scan Mode:20
09-29 04:20:57.318  5831  5831 D BluetoothMapMasInstance0: MAP Service shutdown
,09-29 04:20:57.318  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-29 04:20:57.318  5831  5831 D ObexServerSockets0: shutdown(block = true)
,09-29 04:20:57.322  5831  5868 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-29 04:20:57.323  5831  5831 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-29 04:20:57.323  5831  5831 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 04:20:57.323  5831  5869 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-29 04:20:57.324  5831  5856 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-29 04:20:57.325  5831  5831 I BtOppRfcommListener: stopping Accept Thread
09-29 04:20:57.325  5831  5880 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-29 04:20:57.326  5831  5880 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-29 04:20:57.327  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:57.327  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:57.327  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:57.327  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:57.327  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:57.327  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 04:20:57.327  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:57.327  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:57.327  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:57.329  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:57.329  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:57.332  5831  5831 D HeadsetService: Received stop request...Stopping profile...
09-29 04:20:57.335  5831  5831 V BluetoothAdapterState: isTurningOff()=true
,09-29 04:20:57.335  5831  5831 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:57.335  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:57.335  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 04:20:57.336  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:57.336  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:57.336  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:57.336  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:57.336  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:57.336  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 04:20:57.336  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:57.336  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:57.336  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:57.336  5831  5831 D A2dpService: Received stop request...Stopping profile...
09-29 04:20:57.337  5831  5862 D A2dpStateMachine: Exit Disconnected: -1
09-29 04:20:57.337  5673  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:57.337  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:57.340  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:57.345  5831  5831 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-29 04:20:57.345  5831  5831 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 04:20:57.345  5831  5854 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 04:20:57.346  5831  5854 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 04:20:57.346  5831  5854 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 04:20:57.346  5831  5831 D HidService: Received stop request...Stopping profile...
09-29 04:20:57.346  5831  5831 D HidService: Stopping Bluetooth HidService
,09-29 04:20:57.347  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:57.348  5831  5831 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:57.348  5831  5831 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:57.348  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:57.348  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-29 04:20:57.348  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:57.348  5831  5847 E bt_btif : btif_hf_upstreams_evt: Invalid index 63256
09-29 04:20:57.350  5831  5854 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 04:20:57.350  5831  5854 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-29 04:20:57.351  5831  5831 D HealthService: Received stop request...Stopping profile...
,09-29 04:20:57.352  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-29 04:20:57.352  5831  5831 D PanService: Received stop request...Stopping profile...
09-29 04:20:57.352  5831  5854 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 04:20:57.352  5831  5854 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 04:20:57.352  5831  5854 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-29 04:20:57.353  5831  5854 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-29 04:20:57.354  5831  5831 D BluetoothMapService: Received stop request...Stopping profile...
09-29 04:20:57.354  5831  5831 D BluetoothMapService: stop()
09-29 04:20:57.355  5831  5831 D BluetoothMapAppObserver: deinitObservers()
09-29 04:20:57.355  5831  5831 D BluetoothMapAppObserver: removeReceiver()
09-29 04:20:57.357  5831  5831 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:57.357  5831  5831 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:57.357  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:57.357  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 04:20:57.357  5831  5831 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-29 04:20:57.357  5831  5831 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 04:20:57.357  5831  5847 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 04:20:57.358  5831  5831 D SapService: Received stop request...Stopping profile...
09-29 04:20:57.358  5831  5831 V SapService: stop()
09-29 04:20:57.358  3177  3177 D BluetoothA2dp: Proxy object disconnected
09-29 04:20:57.359  3177  3177 D BluetoothInputDevice: Proxy object disconnected
09-29 04:20:57.359  3177  3177 D HidProfile: Bluetooth service disconnected
,09-29 04:20:57.359  3177  3177 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 04:20:57.359  3177  3177 D PanProfile: Bluetooth service disconnected
09-29 04:20:57.359  3177  3177 D BluetoothMap: Proxy object disconnected
09-29 04:20:57.359  3177  3177 D MapProfile: Bluetooth service disconnected
09-29 04:20:57.359  5831  5831 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:57.359  5831  5831 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:57.359  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:57.359  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 04:20:57.359  5831  5831 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-29 04:20:57.359  5831  5847 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-29 04:20:57.360  5831  5831 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-29 04:20:57.360  5831  5831 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:57.360  5831  5831 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:57.360  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:57.360  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:57.360  5831  5831 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-29 04:20:57.360  5831  5831 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-29 04:20:57.361  5831  5831 D BluetoothMapService: MAP Service closeService in
09-29 04:20:57.361  5831  5831 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:57.361  5831  5831 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:57.361  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:57.361  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:57.362  5831  5831 D BluetoothMapService: cleanup()
09-29 04:20:57.362  5831  5831 D BluetoothMapService: MAP Service closeService in
09-29 04:20:57.362  5831  5831 V BluetoothAdapterState: isTurningOff()=true
09-29 04:20:57.362  5831  5831 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:57.362  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 04:20:57.362  5831  5831 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:57.363  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-29 04:20:57.363  5831  5843 D BluetoothAdapterProperties: Setting state to 15
09-29 04:20:57.363  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-29 04:20:57.363  5831  5843 I BluetoothAdapterState: Entering BleOnState
09-29 04:20:57.364  3177  3991 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 04:20:57.365  3177  3991 D BluetoothHeadset: Proxy object disconnected
09-29 04:20:57.365  3177  3177 D HeadsetProfile: Bluetooth service disconnected
09-29 04:20:57.365  3177  3195 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-29 04:20:57.375  5785  5795 D BluetoothHeadset: Proxy object disconnected
,09-29 04:20:57.376   930   930 D BluetoothHeadset: Proxy object disconnected
09-29 04:20:57.376   930   930 D BluetoothHeadset: Proxy object disconnected
09-29 04:20:57.376   930   930 D BluetoothHeadset: Proxy object disconnected
09-29 04:20:57.376  3852  4039 D BluetoothHeadset: Proxy object disconnected
09-29 04:20:57.377  3177  3991 D BluetoothHeadset: Proxy object disconnected
09-29 04:20:57.377   930   930 D BluetoothA2dp: Proxy object disconnected
09-29 04:20:57.377  3177  3177 D HeadsetProfile: Bluetooth service disconnected
,09-29 04:20:57.378  5785  5882 D BluetoothMap: onBluetoothStateChange: up=false
,09-29 04:20:57.378   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 04:20:57.378  3177  3195 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 04:20:57.379  3177  3193 D BluetoothMap: onBluetoothStateChange: up=false
09-29 04:20:57.379  3177  3991 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 04:20:57.380  5785  5795 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 04:20:57.380  5785  5796 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 04:20:57.381  5785  5882 D BluetoothPan: onBluetoothStateChange on: false
09-29 04:20:57.381   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 04:20:57.381  5785  5795 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 04:20:57.382   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-29 04:20:57.382   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 04:20:57.382  3852  3875 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 04:20:57.382  3177  3195 D BluetoothPan: onBluetoothStateChange on: false
09-29 04:20:57.383  5785  5796 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 04:20:57.383  5831  5843 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-29 04:20:57.384  5831  5843 D BluetoothAdapterProperties: Setting state to 16
09-29 04:20:57.384  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 04:20:57.384  5831  5843 D BluetoothAdapterProperties: onBleDisable
09-29 04:20:57.384  5831  5843 I BluetoothAdapterState: Entering PendingCommandState
09-29 04:20:57.384  5785  5785 I art     : Waiting for a blocking GC DisableMovingGc
,09-29 04:20:57.385  5831  5844 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-29 04:20:57.386  5785  5785 I art     : Starting a blocking GC DisableMovingGc
09-29 04:20:57.386  5831  5854 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 04:20:57.387  5831  5854 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 04:20:57.387  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:57.389  5831  5847 D BluetoothAdapterProperties: Scan Mode:20
09-29 04:20:57.390  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:57.391  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:57.391  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 04:20:57.393  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:57.394  5785  5785 D HeadsetProfile: Bluetooth service disconnected
09-29 04:20:57.397  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 04:20:57.410  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-29 04:20:57.449  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 04:20:57.452  5797  5814 I art     : Waiting for a blocking GC DisableMovingGc
,09-29 04:20:57.454  5797  5814 I art     : Starting a blocking GC DisableMovingGc
,09-29 04:20:57.454  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 04:20:57.456  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-29 04:20:57.587  5831  5847 I bt_hci  : shut_down
,09-29 04:20:57.587  5831  5851 D bt_hwcfg: hw_epilog_process
09-29 04:20:57.589  5831  5851 I bt_vendor: low_power_mode_cb
,09-29 04:20:57.592  5831  5851 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-29 04:20:57.593  5831  5851 I bt_vendor: epilog_cb
,09-29 04:20:57.593  5831  5851 I bt_hci  : epilog_finished_callback
09-29 04:20:57.594  5831  5847 I bt_hci_h4: hal_close
09-29 04:20:57.595  5831  5847 I bt_userial_vendor: device fd = 54 close
,09-29 04:20:57.724  5831  5844 D bt_stack_manager: event_shut_down_stack finished.
,09-29 04:20:57.724  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-29 04:20:57.728  5831  5843 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-29 04:20:57.729  5831  5831 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 04:20:57.730  5831  5831 D BtGatt.GattService: Received stop request...Stopping profile...
09-29 04:20:57.730  5831  5831 D BtGatt.GattService: stop()
09-29 04:20:57.731  5831  5831 D BtGatt.AdvertiseManager: advertise clients cleared
,09-29 04:20:57.733  5831  5831 V BluetoothAdapterState: isTurningOff()=false
,09-29 04:20:57.734  5831  5831 V BluetoothAdapterState: isTurningOn()=false
,09-29 04:20:57.734  5831  5831 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:57.734  5831  5831 V BluetoothAdapterState: isBleTurningOff()=true
09-29 04:20:57.734  5831  5843 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-29 04:20:57.735  5831  5843 D BluetoothAdapterProperties: Setting state to 10
09-29 04:20:57.735  5831  5843 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-29 04:20:57.735  5831  5843 I BluetoothAdapterState: Entering OffState
,09-29 04:20:57.736   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-29 04:20:57.749  5831  5831 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-29 04:20:57.749  5831  5831 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-29 04:20:57.750  5831  5831 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-29 04:20:57.752  5831  5844 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-29 04:20:57.759  5831  5831 I art     : System.exit called, status: 0
,09-29 04:20:57.760  5831  5831 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-29 04:20:57.793   930   940 I ActivityManager: Process com.android.bluetooth (pid 5831) has died
,09-29 04:20:57.808  5673  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:57.808  5673  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:57.808  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:57.808  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:57.808  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:57.808  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 04:20:57.808  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:57.808  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:57.808  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:57.808  5673  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 04:20:57.808  5673  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:57.809  5673  5719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:57.827   930   947 I ActivityManager: Start proc 5887:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-29 04:20:57.887  5887  5887 D AdapterServiceConfig: Adding HeadsetService
,09-29 04:20:57.887  5887  5887 D AdapterServiceConfig: Adding A2dpService
09-29 04:20:57.887  5887  5887 D AdapterServiceConfig: Adding HidService
09-29 04:20:57.887  5887  5887 D AdapterServiceConfig: Adding HealthService
09-29 04:20:57.888  5887  5887 D AdapterServiceConfig: Adding PanService
09-29 04:20:57.888  5887  5887 D AdapterServiceConfig: Adding GattService
09-29 04:20:57.888  5887  5887 D AdapterServiceConfig: Adding BluetoothMapService
09-29 04:20:57.888  5887  5887 D AdapterServiceConfig: Adding SapService
,09-29 04:20:57.897   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@76fe85f:true
,09-29 04:20:57.897  5887  5887 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 04:20:57.900  5887  5887 I bt_bluedroid: init
,09-29 04:20:57.900  5887  5899 I BluetoothAdapterState: Entering OffState
,09-29 04:20:57.902  5887  5900 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-29 04:20:57.902  5887  5900 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-29 04:20:57.902  5887  5900 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-29 04:20:57.903  5887  5900 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-29 04:20:57.903  5887  5887 I bt_bluedroid: get_profile_interface socket
,09-29 04:20:57.905  5887  5903 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 04:20:57.905  5887  5887 I bt_bluedroid: get_profile_interface sdp
,09-29 04:20:57.906  5887  5903 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 04:20:57.910  5887  5898 I bt_bluedroid: config_hci_snoop_log
,09-29 04:20:57.910   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-29 04:20:57.914  5887  5899 D BluetoothAdapterState: Current state: OFF, message: 0
,09-29 04:20:57.914  5887  5899 D BluetoothAdapterProperties: Setting state to 14
09-29 04:20:57.914  5887  5899 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-29 04:20:57.916  5887  5899 D BluetoothBondStateMachine: make
,09-29 04:20:57.917  5887  5904 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 04:20:57.920  5887  5899 I BluetoothAdapterState: Entering PendingCommandState
,09-29 04:20:57.921  5887  5887 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 04:20:57.923  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
09-29 04:20:57.924  5887  5887 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-29 04:20:57.924  5887  5887 D BtGatt.GattService: Received start request. Starting profile...
,09-29 04:20:57.924  5887  5887 D BtGatt.GattService: start()
09-29 04:20:57.924  5887  5887 I bt_bluedroid: get_profile_interface gatt
09-29 04:20:57.925  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:20:57.926  5887  5887 D BtGatt.AdvertiseManager: advertise manager created
,09-29 04:20:57.930  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:57.930  5887  5887 V BluetoothAdapterState: isTurningOn()=false
09-29 04:20:57.931  5887  5887 V BluetoothAdapterState: isBleTurningOn()=true
09-29 04:20:57.931  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:57.931  5887  5899 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-29 04:20:57.932  5887  5899 I bt_bluedroid: bt_bluedroid
,09-29 04:20:57.932  5887  5900 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-29 04:20:57.932  5887  5900 I bt_hci  : start_up
,09-29 04:20:57.937  5887  5900 I bt_vendor: alloc value 0xf3cd7871
09-29 04:20:57.937  5887  5900 I bt_vendor: init
,09-29 04:20:57.937  5887  5900 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-29 04:20:57.937  5887  5900 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 04:20:58.045  5887  5900 D bt_hci  : start_up starting async portion
09-29 04:20:58.046  5887  5907 I bt_hci  : event_finish_startup
09-29 04:20:58.046  5887  5907 I bt_hci_h4: hal_open
09-29 04:20:58.046  5887  5907 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-29 04:20:58.043  5908  5908 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-29 04:20:58.048  5887  5907 I bt_userial_vendor: device fd = 54 open
,09-29 04:20:58.060  5887  5907 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 04:20:58.062  5887  5907 D bt_hwcfg: Chipset BCM4358A3
,09-29 04:20:58.063  5887  5907 D bt_hwcfg: Target name = [BCM4358A3]
09-29 04:20:58.063  5887  5907 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 04:20:58.317  5887  5899 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-29 04:20:58.459  5887  5907 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-29 04:20:58.459  5887  5907 D bt_hwcfg: Settlement delay -- 100 ms
,09-29 04:20:58.459  5887  5907 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 04:20:58.584  5887  5907 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 04:20:58.584  5887  5907 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-29 04:20:58.586  5887  5907 I bt_hwcfg: vendor lib fwcfg completed
,09-29 04:20:58.586  5887  5907 I bt_vendor: firmware callback
,09-29 04:20:58.586  5887  5907 I bt_hci  : firmware_config_callback
,09-29 04:20:58.596  5887  5910 I bt_btu  : btu_task pending for preload complete event
,09-29 04:20:58.596  5887  5910 I bt_btu_task: Bluetooth chip preload is complete
,09-29 04:20:58.596  5887  5910 I bt_btu  : btu_task received preload complete event
,09-29 04:20:58.602  5887  5910 I         : BTE_InitTraceLevels -- TRC_HCI
,09-29 04:20:58.602  5887  5910 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-29 04:20:58.602  5887  5910 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_A2D
09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_BNEP
09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_BTM
09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_GAP
09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_PAN
,09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_SDP
09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_GATT
09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_SMP
09-29 04:20:58.603  5887  5910 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-29 04:20:58.604  5887  5910 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 04:20:58.682  5887  5910 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c55549
,09-29 04:20:58.682  5887  5910 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c55549 
,09-29 04:20:58.700  5887  5903 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 04:20:58.702  5887  5903 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 04:20:58.702  5887  5903 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-29 04:20:58.704  5887  5903 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 04:20:58.708  5887  5903 D BluetoothAdapterProperties: Scan Mode:20
,09-29 04:20:58.708  5887  5903 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 04:20:58.708  5887  5903 D bt_hci  : do_postload posting postload work item
09-29 04:20:58.709  5887  5907 I bt_hci  : event_postload
,09-29 04:20:58.709  5887  5907 I bt_vendor: sco_config_cb
09-29 04:20:58.709  5887  5907 I bt_hci  : sco_config_callback postload finished.
,09-29 04:20:58.711  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:58.714  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:58.714  5887  5903 D bt_bte_conf: Device ID record 1 : primary
09-29 04:20:58.714  5887  5903 D bt_bte_conf:   vendorId            = 000f
09-29 04:20:58.714  5887  5903 D bt_bte_conf:   vendorIdSource      = 0001
09-29 04:20:58.715  5887  5903 D bt_bte_conf:   product             = 1200
,09-29 04:20:58.715  5887  5903 D bt_bte_conf:   version             = 1436
09-29 04:20:58.715  5887  5903 D bt_bte_conf:   clientExecutableURL = 
09-29 04:20:58.715  5887  5903 D bt_bte_conf:   serviceDescription  = 
09-29 04:20:58.715  5887  5903 D bt_bte_conf:   documentationURL    = 
09-29 04:20:58.715  5887  5903 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-29 04:20:58.715  5887  5900 D bt_stack_manager: event_start_up_stack finished
09-29 04:20:58.716  5887  5899 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 04:20:58.716  5887  5899 D BluetoothAdapterProperties: Setting state to 15
09-29 04:20:58.716  5887  5899 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-29 04:20:58.716  5887  5907 I bt_vendor: low_power_mode_cb
09-29 04:20:58.717  5887  5899 I BluetoothAdapterState: Entering BleOnState
,09-29 04:20:58.721  5887  5899 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-29 04:20:58.721  5887  5899 D BluetoothAdapterProperties: Setting state to 11
09-29 04:20:58.721  5887  5899 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-29 04:20:58.725  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:20:58.727  5887  5887 D HeadsetService: Received start request. Starting profile...
09-29 04:20:58.731  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:58.732  5887  5887 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 04:20:58.733  5887  5887 D HeadsetStateMachine: make
,09-29 04:20:58.733  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:58.743  5887  5887 D HeadsetStateMachine: max_hf_connections = 1
,09-29 04:20:58.743  5887  5887 I bt_bluedroid: get_profile_interface handsfree
09-29 04:20:58.743  5887  5903 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-29 04:20:58.743  5887  5903 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-29 04:20:58.744  5887  5899 I BluetoothAdapterState: Entering PendingCommandState
,09-29 04:20:58.746  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:20:58.747  5887  5887 D A2dpService: Received start request. Starting profile...
,09-29 04:20:58.747  5887  5887 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-29 04:20:58.748  5887  5887 I bt_bluedroid: get_profile_interface avrcp
,09-29 04:20:58.753  5887  5887 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-29 04:20:58.753  5887  5887 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 04:20:58.753  5887  5887 D A2dpStateMachine: make
09-29 04:20:58.754  5887  5887 I bt_bluedroid: get_profile_interface a2dp
,09-29 04:20:58.756  5887  5918 D A2dpStateMachine: Enter Disconnected: -2
,09-29 04:20:58.758  5887  5887 I BluetoothHidServiceJni: classInitNative: succeeds
,09-29 04:20:58.759  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
09-29 04:20:58.759  5887  5903 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-29 04:20:58.759  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 04:20:58.759  5887  5887 D HidService: Received start request. Starting profile...
09-29 04:20:58.759  5887  5887 I bt_bluedroid: get_profile_interface hidhost
09-29 04:20:58.759  5887  5887 D HidService: setHidService(): set to: null
09-29 04:20:58.759  5887  5903 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c3656d
,09-29 04:20:58.760  5887  5903 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 04:20:58.760  5887  5887 I BluetoothHealthServiceJni: classInitNative: succeeds
09-29 04:20:58.761  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
09-29 04:20:58.761  5887  5887 D HealthService: Received start request. Starting profile...
,09-29 04:20:58.763  5887  5887 I bt_bluedroid: get_profile_interface health
09-29 04:20:58.763  5887  5887 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-29 04:20:58.764  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:20:58.765  5887  5887 D PanService: Received start request. Starting profile...
09-29 04:20:58.765  5887  5887 D BluetoothPanServiceJni: initializeNative(L110): pan
09-29 04:20:58.765  5887  5887 I bt_bluedroid: get_profile_interface pan
09-29 04:20:58.765  5887  5903 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-29 04:20:58.768  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
09-29 04:20:58.769  5887  5887 D BluetoothMapService: Received start request. Starting profile...
,09-29 04:20:58.769  5887  5887 D BluetoothMapService: start()
,09-29 04:20:58.772  5887  5887 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-29 04:20:58.773  5887  5887 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-29 04:20:58.773  5887  5887 D BluetoothMapAppObserver: createReceiver()
09-29 04:20:58.774  5887  5887 D BluetoothMapAppObserver: initObservers()
09-29 04:20:58.774  5887  5887 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-29 04:20:58.780  5887  5887 V SapService: SapBinder()
09-29 04:20:58.780  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:20:58.781  5887  5887 D SapService: Received start request. Starting profile...
09-29 04:20:58.781  5887  5887 V SapService: start()
,09-29 04:20:58.782  5887  5887 V BluetoothAdapterState: isTurningOff()=false
,09-29 04:20:58.782  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:58.782  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:58.782  5887  5916 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-29 04:20:58.782  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:58.782  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:58.783  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:58.783  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:58.783  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:58.783  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:58.783  5887  5887 V BluetoothAdapterState: isTurningOn()=true
,09-29 04:20:58.783  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:58.783  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 04:20:58.784  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:58.784  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:58.784  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:58.784  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:58.784  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:58.784  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:58.784  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:58.784  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:58.785  5887  5887 V BluetoothAdapterState: isTurningOff()=false
,09-29 04:20:58.785  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:58.785  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:58.785  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 04:20:58.786  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-29 04:20:58.786  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-29 04:20:58.786  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-29 04:20:58.786  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-29 04:20:58.786  5887  5899 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-29 04:20:58.786  5887  5899 D BluetoothAdapterProperties: ScanMode =  20
09-29 04:20:58.786  5887  5899 D BluetoothAdapterProperties: State =  11
,09-29 04:20:58.788  5887  5903 D BluetoothAdapterProperties: Scan Mode:21
,09-29 04:20:58.788  5887  5899 D BluetoothAdapterProperties: Setting state to 12
09-29 04:20:58.789  5887  5899 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-29 04:20:58.789  5887  5903 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-29 04:20:58.789  3177  3195 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:58.790  3177  3193 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 04:20:58.791  5887  5899 I BluetoothAdapterState: Entering OnState
,09-29 04:20:58.792  5785  5796 D BluetoothMap: onBluetoothStateChange: up=true
,09-29 04:20:58.793   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:58.793  3177  3177 D BluetoothInputDevice: Proxy object connected
09-29 04:20:58.794  3177  3177 D HidProfile: Bluetooth service connected
09-29 04:20:58.794  3177  3195 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 04:20:58.795  5785  5785 D BluetoothMap: Proxy object connected
,09-29 04:20:58.795  5785  5785 D MapProfile: Bluetooth service connected
09-29 04:20:58.795  5785  5785 D BluetoothMap: getConnectedDevices()
09-29 04:20:58.796  3177  3193 D BluetoothMap: onBluetoothStateChange: up=true
09-29 04:20:58.796  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:58.796  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:58.796  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:58.796  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:58.796  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:58.796  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:58.796  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:58.796  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:58.797  3177  3177 D BluetoothA2dp: Proxy object connected
09-29 04:20:58.798  3177  3991 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 04:20:58.799  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:58.799  3177  3177 D BluetoothMap: Proxy object connected
09-29 04:20:58.799  3177  3177 D MapProfile: Bluetooth service connected
09-29 04:20:58.799  3177  3177 D BluetoothMap: getConnectedDevices()
,09-29 04:20:58.799  5785  5883 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:58.800  5887  5887 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 04:20:58.800  5785  5795 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 04:20:58.800  5887  5887 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-29 04:20:58.803  5785  5796 D BluetoothPan: onBluetoothStateChange on: true
,09-29 04:20:58.804  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:58.804  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:58.804  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:58.804  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:58.804  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:58.804  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:58.804  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:58.804  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:58.805   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:58.805  5785  5882 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 04:20:58.805  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:58.807   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-29 04:20:58.807   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 04:20:58.807   930   930 D BluetoothA2dp: Proxy object connected
09-29 04:20:58.807  3852  3875 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 04:20:58.808  3177  3193 D BluetoothPan: onBluetoothStateChange on: true
09-29 04:20:58.809  5785  5795 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 04:20:58.811  5785  5785 D BluetoothInputDevice: Proxy object connected
09-29 04:20:58.811  5785  5785 D HidProfile: Bluetooth service connected
09-29 04:20:58.813  5887  5887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:58.813  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:58.813   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
09-29 04:20:58.814  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:58.814  5887  5887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:58.815  5785  5785 D BluetoothA2dp: Proxy object connected
09-29 04:20:58.815  5887  5887 D ObexServerSockets: Succeed to create listening sockets 
09-29 04:20:58.815  5887  5887 D ObexServerSockets0: startAccept()
09-29 04:20:58.815  5887  5887 D ObexServerSockets0: prepareForNewConnect()
09-29 04:20:58.817  5887  5887 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-29 04:20:58.818  5887  5887 D BluetoothSdpJni: SDP Create record success - handle: 0
09-29 04:20:58.818  5887  5925 D ObexServerSockets0: Accepting socket connection...
09-29 04:20:58.818  5887  5926 D ObexServerSockets0: Accepting socket connection...
09-29 04:20:58.819  3177  3177 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 04:20:58.819  3177  3177 D PanProfile: Bluetooth service connected
09-29 04:20:58.819  5887  5887 D BluetoothMapService: onReceive
09-29 04:20:58.820  5887  5887 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-29 04:20:58.820  5887  5887 D BluetoothMapService: STATE_ON
09-29 04:20:58.820  5673  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:58.820  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:58.820  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:58.820  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:20:58.820  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:58.820  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:58.820  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:58.820  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:20:58.822  5887  5927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:20:58.822  5673  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:20:58.823  5887  5927 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-29 04:20:58.823  5673  5719 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
09-29 04:20:58.823  5887  5927 D BluetoothSdpJni: SDP Create record success - handle: 1
09-29 04:20:58.824   930   940 D WifiService: setWifiEnabled: false pid=5673, uid=10077
09-29 04:20:58.824  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 04:20:58.824   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-29 04:20:58.824  5673  5719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:58.826  5785  5785 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 04:20:58.826  5785  5785 D PanProfile: Bluetooth service connected
09-29 04:20:58.826   930   930 D RttService: SCAN_AVAILABLE : 1
,09-29 04:20:58.827   930  3130 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 04:20:58.834  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 04:20:58.838  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-29 04:20:58.843  5785  5785 D BluetoothPbap: Proxy object connected
09-29 04:20:58.843  3177  3177 D BluetoothPbap: Proxy object connected
,09-29 04:20:58.843  3177  3177 D PbapServerProfile: Bluetooth service connected
09-29 04:20:58.843  5785  5785 D PbapServerProfile: Bluetooth service connected
,09-29 04:20:58.844   930  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-29 04:20:58.845   507   924 D CommandListener: Clearing all IP addresses on wlan0
,09-29 04:20:58.849   930  3022 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-29 04:20:58.850  5770  5770 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-29 04:20:58.850  5887  5887 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 04:20:58.850  5887  5887 D ObexServerSockets0: prepareForNewConnect()
,09-29 04:20:58.857  5887  5932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 04:20:58.859  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:58.859  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:58.859  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:58.859  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 04:20:58.859  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:58.859  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:58.859  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:58.859  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:20:58.862  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:58.865  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:58.865  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:58.865  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:58.865  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 04:20:58.865  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:58.865  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:58.865  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:58.865  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:20:58.867  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:58.870  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-29 04:20:58.873  5887  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 04:20:58.874  5887  5936 I BtOppRfcommListener: Accept thread started.
,09-29 04:20:58.881  5770  5770 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-29 04:20:58.888  5770  5770 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-29 04:20:58.892  5785  5883 D BluetoothHeadset: Proxy object connected
09-29 04:20:58.892   930   930 D BluetoothHeadset: Proxy object connected
,09-29 04:20:58.892   930   930 D BluetoothHeadset: Proxy object connected
09-29 04:20:58.892   930   930 D BluetoothHeadset: Proxy object connected
09-29 04:20:58.893  3852  4076 D BluetoothHeadset: Proxy object connected
09-29 04:20:58.893  3177  3195 D BluetoothHeadset: Proxy object connected
09-29 04:20:58.893  3177  3177 D HeadsetProfile: Bluetooth service connected
09-29 04:20:58.894   930   947 D BluetoothHeadset: Proxy object connected
09-29 04:20:58.896  5785  5785 D HeadsetProfile: Bluetooth service connected
,09-29 04:20:58.900  5785  5882 D BluetoothHeadset: Proxy object connected
,09-29 04:20:58.901  5785  5785 D HeadsetProfile: Bluetooth service connected
,09-29 04:20:58.905   930   947 D BluetoothHeadset: Proxy object connected
,09-29 04:20:58.907   930   947 D BluetoothHeadset: Proxy object connected
,09-29 04:20:58.908  3852  3876 D BluetoothHeadset: Proxy object connected
,09-29 04:20:58.991   930  3022 D wifi    : In wifi stop Hal
09-29 04:20:58.991  5043  5043 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 04:20:58.991   930  3022 D wifi    : halHandle = 0x7f92428080, mVM = 0x7faea4d140, mCls = 0x182a
09-29 04:20:58.991   930  5769 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 04:20:58.991   930  5769 D WifiHAL : Got a signal to exit!!!
09-29 04:20:58.991   930  5769 I WifiHAL : Exit wifi_event_loop
09-29 04:20:58.992   930  3022 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-29 04:20:58.992   930  3022 E WifiHAL : Event processing terminated
09-29 04:20:58.992   930  3022 D wifi    : In wifi cleaned up handler
09-29 04:20:58.992   930  3022 I WifiHAL : Internal cleanup completed
09-29 04:20:58.994  4140  4266 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 04:20:58.996  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:58.999  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:59.023   930  5769 D wifi    : set interface wlan0 flags (DOWN)
,09-29 04:20:59.023   930  3022 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 04:20:59.087   507   924 E Netd    : netlink response contains error (No such file or directory)
,09-29 04:20:59.231   930   947 D Tethering: InitialState.processMessage what=4
,09-29 04:20:59.237   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 04:20:59.331  5673  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:20:59.331  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:20:59.331  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:20:59.331  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 04:20:59.331  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:20:59.331  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:20:59.331  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:20:59.331  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:20:59.337  5673  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:20:59.340   930   941 D WifiService: setWifiEnabled: true pid=5673, uid=10077
09-29 04:20:59.340   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 04:20:59.343  5673  5719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:20:59.348   507   924 D SoftapController: Softap fwReload - Ok
,09-29 04:20:59.351   507   924 D CommandListener: Setting iface cfg
,09-29 04:20:59.351   507   924 D CommandListener: Trying to bring down wlan0
,09-29 04:20:59.351   507   924 D CommandListener: Clearing all IP addresses on wlan0
,09-29 04:20:59.355   930  3022 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 04:20:59.848   930  3821 D WifiService: setWifiEnabled: true pid=5673, uid=10077
,09-29 04:20:59.851   930  3821 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 04:20:59.966   930  3022 D wifi    : set interface wlan0 flags (UP)
,09-29 04:20:59.966   930  3022 I WifiHAL : Initializing wifi
,09-29 04:20:59.966   930  3022 I WifiHAL : Creating socket
,09-29 04:20:59.971   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-29 04:20:59.974   930  3022 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-29 04:20:59.974   930  3022 D wifi    : Did set static halHandle = 0x7f92428080
,09-29 04:20:59.974   930  3022 D wifi    : halHandle = 0x7f92428080, mVM = 0x7faea4d140, mCls = 0x2015c6
09-29 04:20:59.974   930  3022 D wifi    : array field set
09-29 04:20:59.974   930  3022 I WifiNative-HAL: interface[0] = wlan0
,09-29 04:20:59.977   930  5946 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547914678400
09-29 04:20:59.977   930  5946 D wifi    : waitForHalEvents called, vm = 0x7faea4d140, obj = 0x2015c6, env = 0x7f94553b00
09-29 04:20:59.979   930  3022 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-29 04:20:59.980   930  3022 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-29 04:20:59.984  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:20:59.987  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:21:00.034  5947  5947 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 04:21:00.055  5947  5947 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 04:21:00.077  5947  5947 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-29 04:21:00.077  5947  5947 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-29 04:21:00.354   930  3820 D WifiService: setWifiEnabled: true pid=5673, uid=10077
,09-29 04:21:00.354   930  3820 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 04:21:00.858   930  3869 D WifiService: setWifiEnabled: true pid=5673, uid=10077
,09-29 04:21:00.858   930  3869 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 04:21:00.993   930  3022 D WifiConfigStore: Loading config and enabling all networks 
,09-29 04:21:01.001  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:21:01.001  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:21:01.001  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:21:01.001  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:21:01.001  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:21:01.001  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:21:01.001  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:21:01.001  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:21:01.004  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:21:01.009  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:21:01.009  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:21:01.009  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:21:01.009  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:21:01.009  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:21:01.009  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:21:01.009  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:21:01.009  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 04:21:01.011  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:21:01.012   930  3022 D WifiConfigStore: loaded 0 passpoint configs
09-29 04:21:01.012   930  3022 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-29 04:21:01.013   930  3022 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-29 04:21:01.014   930  3022 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-29 04:21:01.015   930  3022 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-29 04:21:01.016   930  3022 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-29 04:21:01.016   930  3022 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-29 04:21:01.016   930  3022 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-29 04:21:01.020   930  3022 D WifiNative-HAL: Setting external_sim to 1
,09-29 04:21:01.021  5043  5043 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 04:21:01.021   930  3022 D wifi    : setting dfs flag to true, 0x7f9706b920
09-29 04:21:01.022   930  3022 D WifiStateMachine: Setting OUI to DA-A1-19
09-29 04:21:01.022   930  3022 D wifi    : setting scan oui 0x7f9706b920
09-29 04:21:01.022   930  3022 D WifiHAL : Sending mac address OUI
,09-29 04:21:01.026   930  3022 E native  : do suspend false
,09-29 04:21:01.034   930  3022 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-29 04:21:01.034   930   930 D RttService: SCAN_AVAILABLE : 3
09-29 04:21:01.034   507   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-29 04:21:01.035   930  3130 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-29 04:21:01.036   507   924 D CommandListener: Setting iface cfg
,09-29 04:21:01.039   930  3021 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
,09-29 04:21:01.039   930  3021 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 04:21:01.049   930  3021 D WifiNative-HAL: p2pGetDeviceAddress
,09-29 04:21:01.050   930  3021 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-29 04:21:01.055   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=160507 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-29 04:21:01.369  5673  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:21:01.369  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:21:01.369  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:21:01.369  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:21:01.369  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:21:01.369  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:21:01.369  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:21:01.369  5673  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:21:01.374  5673  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 04:21:01.379  5673  5719 D BluetoothAdapter: enable(): BT is already enabled..!
,09-29 04:21:01.380   930   940 D WifiService: setWifiEnabled: true pid=5673, uid=10077
09-29 04:21:01.380   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-29 04:21:01.381  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 04:21:01.381  5673  5719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 04:21:01.381  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 04:21:01.381  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-29 04:21:01.382  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@437f152 removed from the list
,09-29 04:21:01.382  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 04:21:01.382  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec4ec23 removed from the list
09-29 04:21:01.382  5673  5719 D io.jxcore.node.ConnectivityMonitor: stop
09-29 04:21:01.382  5673  5719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 04:21:01.382  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 04:21:01.385  5673  5719 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,09-29 04:21:01.388  5673  5719 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,09-29 04:21:01.392  5673  5958 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-29 04:21:01.392  5673  5958 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 04:21:01.903  5673  5958 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-29 04:21:01.904  5673  5958 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-29 04:21:01.905  5673  5958 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 04:21:01.906  5673  5960 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-29 04:21:01.906  5673  5960 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-29 04:21:01.906  5673  5958 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 04:21:01.906  5673  5960 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 04:21:01.908  5673  5960 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 04:21:01.908  5673  5958 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-29 04:21:01.913  5673  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: OutgoingSocketThread/Sender)
,09-29 04:21:01.913  5673  5960 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-29 04:21:01.918  5673  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: OutgoingSocketThread/Receiver)
,09-29 04:21:01.919  5673  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: IncomingSocketThread/Sender)
09-29 04:21:01.919  5673  5963 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: OutgoingSocketThread/Receiver)
09-29 04:21:01.920  5673  5963 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 04:21:01.920  5673  5963 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 04:21:01.920  5673  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Receiver)
09-29 04:21:01.921  5673  5965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: IncomingSocketThread/Receiver)
09-29 04:21:01.921  5673  5965 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-29 04:21:01.922  5673  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-29 04:21:02.397  5673  5719 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-29 04:21:02.400  5673  5719 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,09-29 04:21:02.402  5673  5719 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
09-29 04:21:02.407  5673  5719 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,09-29 04:21:02.407   930  3022 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 9, 11 -> obsolete
,09-29 04:21:02.409  5673  5719 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-29 04:21:02.411  5673  5719 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
09-29 04:21:02.412  5673  5719 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-29 04:21:02.413  5673  5719 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-29 04:21:02.418  5673  5719 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-29 04:21:02.419  5673  5719 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c339605 Bundle[{}]
09-29 04:21:02.420  5673  5719 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-29 04:21:02.420  5673  5719 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-29 04:21:02.420  5673  5719 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-29 04:21:02.421  5673  5719 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
09-29 04:21:02.422  5673  5719 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-29 04:21:02.423  5673  5719 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,09-29 04:21:02.424  5673  5719 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-29 04:21:02.426  5673  5719 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,09-29 04:21:02.427  5673  5719 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-29 04:21:02.429  5673  5719 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,09-29 04:21:02.430  5673  5719 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-29 04:21:02.434  5673  5719 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,09-29 04:21:02.437  5673  5719 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-29 04:21:02.439  5673  5719 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,09-29 04:21:02.441  5673  5719 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,09-29 04:21:02.442  5673  5719 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,09-29 04:21:02.443  5673  5719 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
09-29 04:21:02.445  5673  5719 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-29 04:21:02.448  5673  5966 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-29 04:21:02.448  5673  5966 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 04:21:02.453  5673  5966 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-29 04:21:02.453  5673  5966 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-29 04:21:02.453  5673  5966 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 04:21:02.453  5673  5966 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 04:21:02.454  5673  5968 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-29 04:21:02.454  5673  5968 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-29 04:21:02.455  5673  5968 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 04:21:02.455  5673  5969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 175, name: OutgoingSocketThread/Sender)
09-29 04:21:02.455  5673  5966 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-29 04:21:02.456  5673  5968 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 04:21:02.458  5673  5970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: OutgoingSocketThread/Receiver)
,09-29 04:21:02.458  5673  5971 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: IncomingSocketThread/Sender)
09-29 04:21:02.459  5673  5968 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-29 04:21:02.459  5673  5970 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 176, thread name: OutgoingSocketThread/Receiver)
09-29 04:21:02.459  5673  5970 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 04:21:02.459  5673  5970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-29 04:21:02.459  5673  5972 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: IncomingSocketThread/Receiver)
09-29 04:21:02.460  5673  5972 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: IncomingSocketThread/Receiver)
,09-29 04:21:02.461  5673  5972 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-29 04:21:02.461  5673  5972 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 04:21:02.953  5673  5719 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
09-29 04:21:02.955  5673  5719 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
09-29 04:21:02.957  5673  5719 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-29 04:21:02.962  5673  5719 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-29 04:21:02.965  5673  5719 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-29 04:21:02.967  5673  5719 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
09-29 04:21:02.967  5673  5719 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 187)
09-29 04:21:02.969  5673  5719 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
09-29 04:21:02.969  5673  5719 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-29 04:21:02.969  5673  5719 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 188)
09-29 04:21:02.970  5673  5719 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-29 04:21:02.973  5673  5719 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,09-29 04:21:02.974  5673  5719 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
09-29 04:21:02.975  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 04:21:02.975  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@803b34c added. We now have 3 listener(s)
,09-29 04:21:02.978  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 04:21:02.978  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 04:21:02.979  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 04:21:02.979  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 04:21:02.979  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcaf95 added. We now have 3 listener(s)
09-29 04:21:02.979  5673  5719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 04:21:02.980  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 04:21:02.986  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 04:21:02.992  5673  5719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 04:21:02.992  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:21:02.992  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:21:02.992  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:21:02.992  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:21:02.992  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 04:21:02.992  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 04:21:02.992  5673  5719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 04:21:02.995  5673  5719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 04:21:02.995  5673  5719 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 04:21:02.998  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 04:21:03.000  5673  5719 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,09-29 04:21:03.001  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 04:21:03.001  5673  5719 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
09-29 04:21:03.001  5673  5719 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-29 04:21:03.002  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-29 04:21:03.002  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-29 04:21:03.002  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-29 04:21:03.002  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 04:21:03.002  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:21:03.003  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-29 04:21:03.004  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 04:21:03.004  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 04:21:03.004  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 04:21:03.004  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-29 04:21:03.004  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 04:21:03.004  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 04:21:03.005  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 04:21:03.006  5673  5973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:21:03.010  5673  5719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 04:21:03.010  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 04:21:03.006  5915  5915 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34135]" dev="sockfs" ino=34135 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 04:21:03.014  5673  5973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-29 04:21:03.006  5915  5915 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34135]" dev="sockfs" ino=34135 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 04:21:03.017  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 04:21:03.018  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 04:21:03.018  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 04:21:03.020  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-29 04:21:03.020  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 04:21:03.020  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-29 04:21:03.020  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:21:03.020  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:21:03.020  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 04:21:03.021  5673  5719 D BluetoothAdapter: STATE_ON
,09-29 04:21:03.023  5887  5897 D BtGatt.GattService: registerClient() - UUID=d016cee4-8b67-4510-9f58-ea6ccb85a6ed
,09-29 04:21:03.024  5887  5903 D BtGatt.GattService: onClientRegistered() - UUID=d016cee4-8b67-4510-9f58-ea6ccb85a6ed, clientIf=5
,09-29 04:21:03.025  5673  5684 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-29 04:21:03.026  5887  5905 D BtGatt.AdvertiseManager: message : 0
,09-29 04:21:03.028  5887  5905 D BtGatt.AdvertiseManager: starting multi advertising
,09-29 04:21:03.038  5887  5903 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-29 04:21:03.044  5887  5903 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-29 04:21:03.044  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 04:21:03.044  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-29 04:21:03.046  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 04:21:03.047  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-29 04:21:03.047  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 04:21:03.047  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 04:21:03.047  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 04:21:03.047  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-29 04:21:03.047  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-29 04:21:03.050  5673  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 04:21:03.050  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 04:21:03.551  5673  5673 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-29 04:21:03.551  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 04:21:03.551  5673  5673 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-29 04:21:04.270   930  3022 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-29 04:21:04.271   930  3022 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-29 04:21:04.271   930  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 04:21:04.283   930  3022 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-29 04:21:04.318   930  3022 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-29 04:21:04.320  5947  5947 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-29 04:21:04.596   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:21:04.741  5947  5947 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-29 04:21:04.775  5947  5947 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-29 04:21:04.776  5947  5947 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-29 04:21:04.785   930  3022 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-29 04:21:04.785   930  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 04:21:04.785   930  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-29 04:21:04.802   930  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 04:21:04.814   507   924 D CommandListener: Setting iface cfg
,09-29 04:21:04.820   930  3022 D WifiStateMachine: Start Dhcp Watchdog 2
,09-29 04:21:04.826   930  5978 D DhcpClient: Receive thread started
,09-29 04:21:04.831   930  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 04:21:04.831   930  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-29 04:21:04.831   930  3024 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-29 04:21:04.912   930  3022 E native  : do suspend false
,09-29 04:21:04.922   930  5977 D DhcpClient: Broadcasting DHCPDISCOVER
,09-29 04:21:04.936   930  5978 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172678, domain null
,09-29 04:21:04.937   930  5977 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172678 seconds
,09-29 04:21:04.939   930  5977 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-29 04:21:04.959   930  5978 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-29 04:21:04.960   930  5977 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-29 04:21:04.963   507   924 D CommandListener: Setting iface cfg
,09-29 04:21:04.968   930  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-29 04:21:04.972   930  5977 D DhcpClient: Scheduling renewal in 86399s
,09-29 04:21:04.983   930  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-29 04:21:04.983   930  3022 D WifiConfigStore: No blacklist allowed without epno enabled
09-29 04:21:04.985   930  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-29 04:21:04.988   930  3022 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-29 04:21:04.998   930  3024 D ConnectivityService: Adding iface wlan0 to network 101
,09-29 04:21:05.049   930  3024 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-29 04:21:05.049   930  3024 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-29 04:21:05.053   930  3024 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-29 04:21:05.054   930  3024 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-29 04:21:05.056   930  3024 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-29 04:21:05.063   930  3024 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 04:21:05.067   930  3024 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-29 04:21:05.068   930  3024 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-29 04:21:05.068   930  3024 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-29 04:21:05.068   930  3024 D ConnectivityService:    accepting network in place of null
09-29 04:21:05.068   930  3022 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-29 04:21:05.068   930  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 04:21:05.069   930  3024 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 04:21:05.091   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 04:21:05.112   507   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 04:21:05.115   930  3024 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-29 04:21:05.115  3800  3955 W QCNEJ   : |CORE| network available: 101
,09-29 04:21:05.115   930  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-29 04:21:05.117   930  3024 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-29 04:21:05.119   930   947 D Tethering: MasterInitialState.processMessage what=3
09-29 04:21:05.121  3800  3955 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-29 04:21:05.123  3800  3955 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-29 04:21:05.124  3800  3955 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-29 04:21:05.125  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:21:05.125  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:21:05.125  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:21:05.125  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:21:05.125  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:21:05.125  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 04:21:05.125  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 04:21:05.125  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 04:21:05.128  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 04:21:05.129  5068  5090 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-29 04:21:05.129  5068  5090 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 04:21:05.129  5068  5090 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-29 04:21:05.131  5068  5090 E SarControlService: no key has been found,reset the power
09-29 04:21:05.131  5068  5102 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 04:21:05.132  3917  3917 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-29 04:21:05.133  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:21:05.133  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:21:05.133  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:21:05.133  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:21:05.133  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:21:05.133  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 04:21:05.133  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 04:21:05.133  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 04:21:05.131  5068  5102 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 04:21:05.133  5068  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-29 04:21:05.134  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 04:21:05.134  5093  5093 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 04:21:05.134  5068  5102 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-29 04:21:05.134  5068  5102 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 04:21:05.134  5068  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-29 04:21:05.135  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 04:21:05.135  5093  5093 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-29 04:21:05.137  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 04:21:05.139  3917  3917 D SystemUpdateService: onCreate
,09-29 04:21:05.141  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e50fe11 HexData = [00000000ec03000000000000ffffffff]
,09-29 04:21:05.142  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 04:21:05.142  5093  5107 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-29 04:21:05.142  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 04:21:05.142  5068  5079 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 04:21:05.145  5673  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 04:21:05.145  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 04:21:05.145  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 04:21:05.145  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 04:21:05.145  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 04:21:05.145  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 04:21:05.145  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 04:21:05.145  5673  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 04:21:05.145  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e50fe11 HexData = [00000000ed03000000000000ffffffff]
09-29 04:21:05.146  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 04:21:05.146  5093  5107 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-29 04:21:05.146  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-29 04:21:05.147  5068  5078 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-29 04:21:05.147  3917  3917 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-29 04:21:05.148  5673  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 04:21:05.151   930  5976 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164602, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-29 04:21:05.155  3917  5988 I SystemUpdateService: active receiver: enabled
,09-29 04:21:05.160  3917  5988 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 04:21:05.167  3917  3917 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-29 04:21:05.169  3917  5428 I iu.UploadsManager: num queued entries: 0
,09-29 04:21:05.170  3917  5428 I iu.UploadsManager: num updated entries: 0
09-29 04:21:05.170  3917  5428 I iu.SyncManager: NEXT; no task
,09-29 04:21:05.173  3917  5988 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-29 04:21:05.173  3917  5988 I SystemUpdateService: now status is 0 (complete)
09-29 04:21:05.174  3917  5988 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 04:21:05.174  3917  5988 I SystemUpdateService: file has been verified
09-29 04:21:05.174  3917  5988 I SystemUpdateService: OTA package size = 21989297
,09-29 04:21:05.176  3917  3917 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 04:21:05.177  3917  3917 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 04:21:05.179  5431  5431 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 04:21:05.187  5431  5431 D SprintDMHelper: simOperator: 
,09-29 04:21:05.187  5431  5431 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 04:21:05.204  3917  5988 I SystemUpdateService: showing system update notification
,09-29 04:21:05.217   930  5975 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.206,2a00:1450:400d:807::200e
,09-29 04:21:05.231  3917  3917 D SystemUpdateService: onDestroy
,09-29 04:21:05.241  3614  5998 I VacuumService: Vacuum at: now=1475137265241 tag=VacuumService
,09-29 04:21:05.272   930  5975 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 29 Sep 2016 08:21:04 GMT], X-Android-Received-Millis=[1475137265271], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475137265242]}
,09-29 04:21:05.272   930  3024 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-29 04:21:05.273   930  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-29 04:21:05.273   930  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-29 04:21:05.274   930  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-29 04:21:05.282  3614  6002 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,09-29 04:21:05.302  5043  5994 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-29 04:21:05.314  3614  5999 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
09-29 04:21:05.316  3614  5999 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-29 04:21:05.360  3614  5999 W Uploader:  no longer exists, so no auth token.
,09-29 04:21:05.365  3614  6002 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-29 04:21:05.597   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:21:05.643  3614  6005 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-29 04:21:05.778  3614  6002 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-29 04:21:05.945  3614  6005 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-29 04:21:06.021  3614  5999 W Uploader:  no longer exists, so no auth token.
,09-29 04:21:06.033  3614  6002 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-29 04:21:06.117   930  3024 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-29 04:21:06.126  3614  6005 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-29 04:21:06.280   930  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,09-29 04:21:06.293   930  3024 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 04:21:06.298  3800  3955 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-29 04:21:06.298  3800  3955 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-29 04:21:06.549  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-29 04:21:06.550  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-29 04:21:06.550  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 04:21:06.550  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-29 04:21:06.550  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-29 04:21:06.551  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-29 04:21:06.551  5673  5973 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-29 04:21:06.551  5673  5973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 04:21:06.551  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-29 04:21:06.551  5673  5973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 04:21:06.551  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 04:21:06.551  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 04:21:06.551  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-29 04:21:06.551  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 04:21:06.552  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 04:21:06.552  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 04:21:06.554  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:21:06.554  5673  5719 D BluetoothLeScanner: could not find callback wrapper
09-29 04:21:06.554  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 04:21:06.555  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-29 04:21:06.556  5887  5905 D BtGatt.AdvertiseManager: message : 1
09-29 04:21:06.558  5887  5905 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 04:21:06.571  5887  5903 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-29 04:21:06.571  5887  5903 D BtGatt.GattService: Client app is not null!
09-29 04:21:06.573  5887  5923 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 04:21:06.573  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 04:21:06.574  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 04:21:06.574  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-29 04:21:06.574  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-29 04:21:06.574  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-29 04:21:06.577  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:21:06.577  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 04:21:06.577  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-29 04:21:06.578  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-29 04:21:06.580  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 04:21:06.580  5673  5673 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-29 04:21:06.580  5673  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 04:21:06.581  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:21:06.581  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-29 04:21:06.581  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 04:21:06.584  5673  5719 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
09-29 04:21:06.584  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 04:21:06.590  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 04:21:06.590  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 04:21:06.590  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 04:21:06.590  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:21:06.590  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-29 04:21:06.595  5673  5719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 04:21:06.595  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 04:21:06.597   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:21:06.600  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 04:21:06.601  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-29 04:21:06.601  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 04:21:06.608  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-29 04:21:06.608  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-29 04:21:06.610  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 04:21:06.611  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:21:06.614  5887  5897 D BtGatt.GattService: registerClient() - UUID=fedb4f0f-781e-4ab3-974a-f5a5e7cf9aee
,09-29 04:21:06.614  5887  5903 D BtGatt.GattService: onClientRegistered() - UUID=fedb4f0f-781e-4ab3-974a-f5a5e7cf9aee, clientIf=5
09-29 04:21:06.615  5673  5684 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-29 04:21:06.616  5887  5924 D BtGatt.GattService: start scan with filters
,09-29 04:21:06.620  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 04:21:06.620  5887  5906 D BtGatt.ScanManager: handling starting scan
,09-29 04:21:06.621  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 04:21:06.621  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 04:21:06.621  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-29 04:21:06.623  5887  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f4934e
,09-29 04:21:06.624  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 04:21:06.624  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 04:21:06.624  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 04:21:06.626  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-29 04:21:06.631  5887  5903 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-29 04:21:06.631  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 04:21:06.632  5887  5906 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 04:21:06.638  3614  6004 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-29 04:21:06.639  3614  6004 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,09-29 04:21:06.641  5887  5903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 04:21:06.641  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 04:21:06.641  5887  5906 D BtGatt.ScanManager: Starting BLE batch scan
09-29 04:21:06.641  5887  5906 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-29 04:21:06.651  5887  5903 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 04:21:06.651  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 04:21:06.656  5887  5903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-29 04:21:06.657  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 04:21:07.050   930  3022 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 12 -> obsolete
,09-29 04:21:07.125  5673  5673 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-29 04:21:07.126  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 04:21:07.126  5673  5673 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-29 04:21:07.598   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:21:07.839   930  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 04:21:08.599   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 04:21:09.600   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-29 04:21:09.631  5673  5719 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
09-29 04:21:09.632  5673  5719 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-29 04:21:09.632  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-29 04:21:09.633  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 04:21:09.633  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 04:21:09.635  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:21:09.637  5887  5897 D BtGatt.GattService: stopScan() - queue size =1
,09-29 04:21:09.643  5887  5924 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 04:21:09.644  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 04:21:09.645  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-29 04:21:09.645  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 04:21:09.647  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 04:21:09.647  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 04:21:09.647  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 04:21:09.649  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:21:09.650  5887  5887 D BtGatt.ScanManager: awakened up at time 169101
09-29 04:21:09.652  5887  5898 D BtGatt.GattService: registerClient() - UUID=e4e1d120-c8f3-48f6-91b6-cb19cd60f48e
09-29 04:21:09.652  5887  5903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-29 04:21:09.653  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 04:21:09.653  5887  5906 D BtGatt.ScanManager: stopping BLe Batch
09-29 04:21:09.654  5887  5903 D BtGatt.GattService: onClientRegistered() - UUID=e4e1d120-c8f3-48f6-91b6-cb19cd60f48e, clientIf=5
09-29 04:21:09.654  5673  5683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-29 04:21:09.655  5887  5923 D BtGatt.GattService: start scan with filters
,09-29 04:21:09.659  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-29 04:21:09.659  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 04:21:09.659  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-29 04:21:09.659  5673  5719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-29 04:21:09.659  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 04:21:09.659  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 04:21:09.660  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-29 04:21:09.660  5887  5903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 04:21:09.661  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 04:21:09.661  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 04:21:09.661  5887  5906 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-29 04:21:09.661  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 04:21:09.661  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 04:21:09.661  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 04:21:09.661  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-29 04:21:09.662  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 04:21:09.662  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 04:21:09.662  5673  6011 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 04:21:09.663  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:21:09.664  5887  5923 D BtGatt.GattService: stopScan() - queue size =0
09-29 04:21:09.663  5924  5924 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33550]" dev="sockfs" ino=33550 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 04:21:09.663  5924  5924 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33550]" dev="sockfs" ino=33550 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 04:21:09.665  5887  5915 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 04:21:09.666  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 04:21:09.666  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 04:21:09.666  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 04:21:09.666  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 04:21:09.666  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 04:21:09.667  5673  6011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-29 04:21:09.667  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:21:09.669  5673  5719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 04:21:09.671  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-29 04:21:09.671  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 04:21:09.672  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
09-29 04:21:09.672  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:21:09.672  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-29 04:21:09.672  5673  5719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-29 04:21:09.673  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:21:09.675  5887  5898 D BtGatt.GattService: registerClient() - UUID=fc14193f-2ef3-46c0-b53d-b0dd3c654a69
09-29 04:21:09.676  5887  5903 D BtGatt.GattService: onClientRegistered() - UUID=fc14193f-2ef3-46c0-b53d-b0dd3c654a69, clientIf=5
09-29 04:21:09.676  5673  5684 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-29 04:21:09.679  5887  5905 D BtGatt.AdvertiseManager: message : 0
,09-29 04:21:09.681  5887  5905 D BtGatt.AdvertiseManager: starting multi advertising
,09-29 04:21:09.684  5887  5903 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=10
09-29 04:21:09.684  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 04:21:09.684  5887  5903 D BtGatt.GattService: current time is 169135985212
09-29 04:21:09.685  5887  5903 D BtGatt.GattService: Batch record : [77, 117, 77, -92, 14, 110, 1, -128, -59, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0, -9, -41, -38, 3, -84, 69, 1, -128, -81, 4, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -71, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -76, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -73, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -75, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -40, 92, -117, 79, -22, 67, 1, -128, -62, 48, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, -40, 92, -117, 79, -22, 67, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 71, -122, -77, 84, 69, -12, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-29 04:21:09.686  5887  5903 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
09-29 04:21:09.687  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0]
09-29 04:21:09.687  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-29 04:21:09.687  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-29 04:21:09.687  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-29 04:21:09.688  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1,, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-29 04:21:09.688  5887  5903 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
09-29 04:21:09.688  5887  5903 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
09-29 04:21:09.688  5887  5906 D BtGatt.ScanManager: handling starting scan
09-29 04:21:09.689  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-29 04:21:09.689  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-29 04:21:09.694  5887  5903 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-29 04:21:09.698  5887  5903 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 04:21:09.698  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 04:21:09.698  5887  5906 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 04:21:09.703  5887  5903 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-29 04:21:09.703  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-29 04:21:09.703  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 04:21:09.705  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 04:21:09.707  5887  5903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 04:21:09.707  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 04:21:09.707  5887  5906 D BtGatt.ScanManager: Starting BLE batch scan
09-29 04:21:09.708  5887  5906 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 04:21:09.708  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-29 04:21:09.708  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:21:09.708  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-29 04:21:09.708  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-29 04:21:09.708  5673  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-29 04:21:09.708  5673  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-29 04:21:09.708  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-29 04:21:09.710  5673  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 04:21:09.711  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-29 04:21:09.718  5887  5903 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-29 04:21:09.718  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 04:21:09.722  5887  5903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-29 04:21:09.722  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 04:21:09.728  5887  5903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-29 04:21:09.728  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 04:21:09.728  5887  5906 D BtGatt.ScanManager: stopping BLe Batch
,09-29 04:21:09.732  5887  5903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 04:21:09.732  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 04:21:09.733  5887  5906 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 04:21:09.737  5887  5903 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-29 04:21:09.737  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 04:21:10.212  5673  5673 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-29 04:21:10.212  5673  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 04:21:10.212  5673  5673 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-29 04:21:10.870   930  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 04:21:13.070   930  3024 D ConnectivityService: handlePromptUnvalidated 101
,09-29 04:21:13.212  5673  5719 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-29 04:21:13.213  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 04:21:13.213  5673  5719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 04:21:13.213  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 04:21:13.213  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-29 04:21:13.214  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 04:21:13.214  5673  6011 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 04:21:13.214  5673  5719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 04:21:13.214  5673  6011 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-29 04:21:13.214  5673  6011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-29 04:21:13.214  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 04:21:13.214  5673  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 04:21:13.214  5673  5719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@803b34c removed from the list
,09-29 04:21:13.215  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 04:21:13.215  5673  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 04:21:13.215  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 04:21:13.215  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 04:21:13.215  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 04:21:13.216  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-29 04:21:13.218  5673  5719 D BluetoothAdapter: STATE_ON
09-29 04:21:13.218  5673  5719 D BluetoothLeScanner: could not find callback wrapper
09-29 04:21:13.218  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 04:21:13.218  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-29 04:21:13.222  5887  5905 D BtGatt.AdvertiseManager: message : 1
09-29 04:21:13.223  5887  5905 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-29 04:21:13.236  5887  5903 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-29 04:21:13.236  5887  5903 D BtGatt.GattService: Client app is not null!
,09-29 04:21:13.237  5887  5915 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 04:21:13.238  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 04:21:13.238  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-29 04:21:13.238  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-29 04:21:13.238  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-29 04:21:13.238  5673  5719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-29 04:21:13.240  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 04:21:13.240  5673  5719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-29 04:21:13.240  5673  5719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 04:21:13.241  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-29 04:21:13.243  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:21:13.243  5673  5719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcaf95 removed from the list
09-29 04:21:13.243  5673  5719 D io.jxcore.node.ConnectivityMonitor: stop
09-29 04:21:13.243  5673  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 04:21:13.243  5673  5719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 04:21:13.243  5673  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 04:21:13.246  5673  5719 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,09-29 04:21:13.246  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-29 04:21:13.246  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 04:21:13.246  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-29 04:21:13.246  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 04:21:13.247  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-29 04:21:13.247  5673  5719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 04:21:13.248  5673  5719 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
09-29 04:21:13.249  5673  5719 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,09-29 04:21:13.250  5673  5719 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
09-29 04:21:13.252  5673  5719 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
09-29 04:21:13.254  5673  5719 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
09-29 04:21:13.255  5673  5719 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,09-29 04:21:13.256  5673  5719 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,09-29 04:21:13.257  5673  5719 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,09-29 04:21:13.259  5673  5719 I StreamCopyingThreadTest: Starting test: testRun
,09-29 04:21:13.262  5673  6013 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: My test thread name)
,09-29 04:21:13.744  5673  5673 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 04:21:15.137  5673  6013 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 201
,09-29 04:21:15.137  5673  6013 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 201, name: My test thread name)
09-29 04:21:15.138  5673  6013 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-29 04:21:15.267  5673  5719 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-29 04:21:15.271  5673  6015 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 203, name: My test thread name)
,09-29 04:21:15.271  5673  6015 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 203, thread name: My test thread name)
09-29 04:21:15.271  5673  6015 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 203, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-29 04:21:15.274  5673  5719 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-29 04:21:15.276  5673  5719 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 04:21:15.281  5673  5719 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-29 04:21:15.285  5673  6016 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 207, name: My test thread name)
,09-29 04:21:15.286  5673  6016 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 207, thread name: My test thread name): Test exception.
09-29 04:21:15.286  5673  6016 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 207, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-29 04:21:15.293  5673  5719 I jxcore-log: *Native tests were executed*
09-29 04:21:15.293  5673  5719 I jxcore-log: 
,09-29 04:21:15.294  5673  5719 I jxcore-log: Total number of executed tests:  82
09-29 04:21:15.294  5673  5719 I jxcore-log: 
,09-29 04:21:15.294  5673  5719 I jxcore-log: Number of passed tests:  82
09-29 04:21:15.294  5673  5719 I jxcore-log: 
,09-29 04:21:15.295  5673  5719 I jxcore-log: Number of failed tests:  0
09-29 04:21:15.295  5673  5719 I jxcore-log: 
09-29 04:21:15.295  5673  5719 I jxcore-log: Number of ignored tests:  0
09-29 04:21:15.295  5673  5719 I jxcore-log: 
09-29 04:21:15.297  5673  5719 I jxcore-log: Total duration:  26479
09-29 04:21:15.297  5673  5719 I jxcore-log: 
09-29 04:21:15.298  5673  5719 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-29 04:21:15.298  5673  5719 I jxcore-log: 
,09-29 04:21:15.307  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 04:21:15.307  5673  5719 I jxcore-log: 
,09-29 04:21:15.312  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 04:21:15.312  5673  5719 I jxcore-log: 
,09-29 04:21:15.314  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 04:21:15.314  5673  5719 I jxcore-log: 
09-29 04:21:15.316  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 04:21:15.316  5673  5719 I jxcore-log: 
,09-29 04:21:15.318  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 04:21:15.318  5673  5719 I jxcore-log: 
,09-29 04:21:15.321  5673  5673 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-29 04:21:15.321  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 04:21:15.321  5673  5719 I jxcore-log: 
,09-29 04:21:15.325  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 04:21:15.325  5673  5719 I jxcore-log: 
,09-29 04:21:15.327  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.327  5673  5719 I jxcore-log: 
,09-29 04:21:15.329  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 04:21:15.329  5673  5719 I jxcore-log: 
,09-29 04:21:15.330  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 04:21:15.330  5673  5719 I jxcore-log: 
,09-29 04:21:15.332  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 04:21:15.332  5673  5719 I jxcore-log: 
,09-29 04:21:15.333  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-29 04:21:15.333  5673  5719 I jxcore-log: 
09-29 04:21:15.334  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.334  5673  5719 I jxcore-log: 
09-29 04:21:15.334  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.334  5673  5719 I jxcore-log: 
,09-29 04:21:15.336  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.336  5673  5719 I jxcore-log: 
,09-29 04:21:15.338  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.338  5673  5719 I jxcore-log: 
,09-29 04:21:15.339  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.339  5673  5719 I jxcore-log: 
09-29 04:21:15.341  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.341  5673  5719 I jxcore-log: 
09-29 04:21:15.341  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.341  5673  5719 I jxcore-log: 
,09-29 04:21:15.342  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.342  5673  5719 I jxcore-log: 
09-29 04:21:15.343  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.343  5673  5719 I jxcore-log: 
,09-29 04:21:15.345  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.345  5673  5719 I jxcore-log: 
09-29 04:21:15.346  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.346  5673  5719 I jxcore-log: 
09-29 04:21:15.347  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.347  5673  5719 I jxcore-log: 
,09-29 04:21:15.347  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.347  5673  5719 I jxcore-log: 
09-29 04:21:15.347  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.347  5673  5719 I jxcore-log: 
09-29 04:21:15.348  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.348  5673  5719 I jxcore-log: 
09-29 04:21:15.349  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 04:21:15.349  5673  5719 I jxcore-log: 
,09-29 04:21:15.350  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 04:21:15.350  5673  5719 I jxcore-log: 
,09-29 04:21:15.351  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-29 04:21:15.351  5673  5719 I jxcore-log: 
09-29 04:21:15.352  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.352  5673  5719 I jxcore-log: 
09-29 04:21:15.353  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.353  5673  5719 I jxcore-log: 
,09-29 04:21:15.353  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.353  5673  5719 I jxcore-log: 
09-29 04:21:15.354  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-29 04:21:15.354  5673  5719 I jxcore-log: 
09-29 04:21:15.354  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 04:21:15.354  5673  5719 I jxcore-log: 
09-29 04:21:15.355  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 04:21:15.355  5673  5719 I jxcore-log: 
09-29 04:21:15.355  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 04:21:15.355  5673  5719 I jxcore-log: 
,09-29 04:21:15.356  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-29 04:21:15.356  5673  5719 I jxcore-log: 
,09-29 04:21:15.358  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-29 04:21:15.358  5673  5719 I jxcore-log: 
,09-29 04:21:15.359  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-29 04:21:15.359  5673  5719 I jxcore-log: 
,09-29 04:21:15.360  5673  5719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-29 04:21:15.360  5673  5719 I jxcore-log: 
,09-29 04:21:15.798  6017  6017 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-29 04:21:15.803  6017  6017 D AndroidRuntime: CheckJNI is OFF
,09-29 04:21:15.827  6017  6017 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-29 04:21:15.858  6017  6017 I Radio-JNI: register_android_hardware_Radio DONE
,09-29 04:21:15.874  6017  6017 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-29 04:21:15.885   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-29 04:21:15.886   930   943 I ActivityManager: Killing 5673:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-29 04:21:15.973   930  3023 D WifiService: Client connection lost with reason: 4
09-29 04:21:15.973   930  3814 D GraphicsStats: Buffer count: 2
,09-29 04:21:15.973   930   940 I WindowState: WIN DEATH: Window{3545ace u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-29 04:21:16.034   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-29 04:21:16.035   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-29 04:21:16.035   930   954 I art     : Starting a blocking GC Explicit
09-29 04:21:16.036   930   943 E ActivityManager: Failure starting process com.test.thalitest
09-29 04:21:16.036   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-29 04:21:16.036   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:21:16.036   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:21:16.036   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 04:21:16.036   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-29 04:21:16.037   930   943 I ActivityManager:   Force finishing activity ActivityRecord{387b3 u0 com.test.thalitest/.MainActivity t2}
,09-29 04:21:16.044   930  3203 W ActivityManager: Spurious death for ProcessRecord{dc0032e 0:com.test.thalitest/u0a77}, curProc for 5673: null
,09-29 04:21:16.048   930   948 W WindowManager: Attempted to add application window with unknown token Token{c4b8170 ActivityRecord{387b3 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-29 04:21:16.048   930  3022 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
09-29 04:21:16.048   930   948 W WindowManager: Token{c4b8170 ActivityRecord{387b3 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{c4b8170 ActivityRecord{387b3 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-29 04:21:16.049   930   948 W WindowManager: view not successfully added to wm, removing view
09-29 04:21:16.049   930   948 W WindowManager: Exception when adding starting window
09-29 04:21:16.049   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{6fb5ce1 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-29 04:21:16.049   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-29 04:21:16.049   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-29 04:21:16.049   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-29 04:21:16.049   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-29 04:21:16.049   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-29 04:21:16.049   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:21:16.049   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:21:16.049   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 04:21:16.049   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-29 04:21:16.116   930   954 I art     : Explicit concurrent mark sweep GC freed 50778(3MB) AllocSpace objects, 9(284KB) LOS objects, 33% free, 28MB/43MB, paused 1.388ms total 80.770ms
,09-29 04:21:16.134   930   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-29 04:21:16.137  6017  6017 I art     : System.exit called, status: 0
,09-29 04:21:16.137  6017  6017 I AndroidRuntime: VM exiting with result code 0.
,09-29 04:21:16.140   930   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-29 04:21:16.147   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-29 04:21:16.149  3731  3731 I Keyboard.Facilitator: resetDictionaries() : en_US
09-29 04:21:16.151  5887  5887 D BluetoothMapAppObserver: onReceive
09-29 04:21:16.151  5887  5887 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-29 04:21:16.161  4140  4236 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-29 04:21:16.168   930  2987 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-29 04:21:16.174  3731  6028 I Keyboard.Facilitator.DecoderInitializer: run()
,09-29 04:21:16.188  3731  6028 I Decoder : createOrResetDecoder
,09-29 04:21:16.189  3852  3852 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-29 04:21:16.197  3439  6030 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-29 04:21:16.228   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-29 04:21:16.237  3614  3614 I ConfigService: onCreate
,09-29 04:21:16.250  3614  3614 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-29 04:21:16.250  3614  3614 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-29 04:21:16.249    29    29 W kworker/2:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 04:21:16.262  3731  6028 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-29 04:21:16.259    29    29 W kworker/2:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 04:21:16.279    29    29 W kworker/2:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 04:21:16.308  3917  6035 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-29 04:21:16.318  3917  6035 D AccountUtils: Clearing selected account for com.test.thalitest
,09-29 04:21:16.325  3439  6030 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
,--------- beginning of crash
09-29 04:21:16.327  3439  6030 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-29 04:21:16.327  3439  6030 E AndroidRuntime: Process: android.process.acore, PID: 3439
09-29 04:21:16.327  3439  6030 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:21:16.327  3439  6030 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-29 04:21:16.333   930  6038 E DropBoxManagerService: Can't write: system_app_crash
09-29 04:21:16.333   930  6038 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 04:21:16.333   930  6038 E DropBoxManagerService: 	... 5 more
,09-29 04:21:16.345  3917  6035 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-29 04:21:16.336  3439  6030 I Process : Sending signal. PID: 3439 SIG: 9
,09-29 04:21:16.370  3917  6035 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:21:16.370  3917  6035 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 04:21:16.370  3917  6035 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-29 04:21:16.370  3917  6035 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-29 04:21:16.394   930  3454 I ActivityManager: Process android.process.acore (pid 3439) has died
,09-29 04:21:16.394   930  3454 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-29 04:21:16.670   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
