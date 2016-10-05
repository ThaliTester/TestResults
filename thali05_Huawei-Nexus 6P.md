#### Test 87899936caa6543_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-05 10:26:15.157   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-05 10:26:15.157   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
10-05 10:26:15.648  5550  5550 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-05 10:26:15.654  5550  5550 D AndroidRuntime: CheckJNI is OFF
10-05 10:26:15.682  5550  5550 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-05 10:26:15.717  5550  5550 I Radio-JNI: register_android_hardware_Radio DONE
10-05 10:26:15.733  5550  5550 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-05 10:26:15.737   930   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-05 10:26:15.778   930   940 I ActivityManager: Start proc 5559:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-05 10:26:15.792  5550  5550 D AndroidRuntime: Shutting down VM
,10-05 10:26:16.035   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 10:26:16.124   930  3748 I WindowManager: Screenshot max retries 4 of Token{ea1918c ActivityRecord{8fd96bf u0 com.test.thalitest/.MainActivity t2}} appWin=Window{19eb7 u0 Starting com.test.thalitest} drawState=2
,10-05 10:26:16.192  5559  5559 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-05 10:26:16.224  5559  5559 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-05 10:26:16.245  5559  5559 I LibraryLoader: Time to load native libraries: 16 ms (timestamps 694-710)
,10-05 10:26:16.245  5559  5559 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-05 10:26:16.262  5559  5559 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {db6a355}
10-05 10:26:16.263  5559  5559 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-05 10:26:16.263  5559  5559 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
10-05 10:26:16.266  5559  5559 I BrowserStartupController: Initializing chromium process, singleProcess=true
10-05 10:26:16.267  5559  5559 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-05 10:26:16.297  5559  5559 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-05 10:26:16.306  5559  5559 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-05 10:26:16.306  5559  5559 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-05 10:26:16.306  5559  5559 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-05 10:26:16.306  5559  5559 I Adreno  : Build Date                       : 12/06/15
10-05 10:26:16.306  5559  5559 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-05 10:26:16.306  5559  5559 I Adreno  : Local Branch                     : mybranch17112971
10-05 10:26:16.306  5559  5559 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-05 10:26:16.306  5559  5559 I Adreno  : Remote Branch                    : NONE
10-05 10:26:16.306  5559  5559 I Adreno  : Reconstruct Branch               : NOTHING
,10-05 10:26:16.337   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d99789a:true
,10-05 10:26:16.359   408   408 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33886]" dev="sockfs" ino=33886 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 10:26:16.359   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33886]" dev="sockfs" ino=33886 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 10:26:16.370  5559  5559 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-05 10:26:16.378  5559  5559 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-05 10:26:16.395   725   725 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33604]" dev="sockfs" ino=33604 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 10:26:16.399  5559  5596 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-05 10:26:16.395   725   725 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33604]" dev="sockfs" ino=33604 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 10:26:16.399  3123  3123 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[16888]" dev="sockfs" ino=16888 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-05 10:26:16.399  3123  3123 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[16888]" dev="sockfs" ino=16888 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-05 10:26:16.404  5559  5583 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-05 10:26:16.435  5559  5596 I OpenGLRenderer: Initialized EGL, version 1.4
,10-05 10:26:16.506   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +379ms (total +755ms)
,10-05 10:26:16.529  5559  5559 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5559
,10-05 10:26:16.658  5559  5559 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-05 10:26:16.752  5559  5599 D jxcore_app_log: JniHelper::setJavaVM(0xf513c000), pthread_self() = -585361104
,10-05 10:26:16.756  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-05 10:26:16.756  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-05 10:26:16.756  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-05 10:26:16.756  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-05 10:26:16.756  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-05 10:26:16.756  5559  5599 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9064d93 added. We now have 1 listener(s)
,10-05 10:26:16.759  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-05 10:26:16.759  5559  5599 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 10:26:16.760  5559  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-05 10:26:16.760  5559  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-05 10:26:16.762  5559  5599 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a37f4ce added. We now have 1 listener(s)
10-05 10:26:16.763  5559  5599 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 10:26:16.767   930  2900 D WifiService: New client listening to asynchronous messages
,10-05 10:26:16.767  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 10:26:16.767  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-05 10:26:16.767  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-05 10:26:16.767  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-05 10:26:16.767  5559  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-05 10:26:16.769  5559  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 10:26:16.769  5559  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-05 10:26:16.773  5559  5599 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-05 10:26:16.773  5559  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:26:16.773  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:16.773  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:16.773  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:16.773  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:26:16.773  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:16.773  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:16.773  5559  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:26:16.774  5559  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-05 10:26:16.774  5559  5599 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:26:16.774  5559  5599 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-05 10:26:16.871  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:16.874  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:16.876  5559  5559 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-05 10:26:17.067  5559  5605 W jxcore-log: Initializing JXcore engine
10-05 10:26:17.067  5559  5605 W jxcore-log: JXcore engine is ready
,10-05 10:26:17.089  5605  5605 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12530 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-05 10:26:17.092  5605  5605 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16415]" dev="sockfs" ino=16415 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-05 10:26:17.092  5605  5605 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-05 10:26:17.092  5605  5605 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33580]" dev="sockfs" ino=33580 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-05 10:26:17.101  5559  5605 W jxcore-log: Starting JXcore engine
,10-05 10:26:17.159  5559  5605 W jxcore-log: Platform android
10-05 10:26:17.159  5559  5605 W jxcore-log: 
,10-05 10:26:17.159  5559  5605 W jxcore-log: Process ARCH arm
10-05 10:26:17.159  5559  5605 W jxcore-log: 
,10-05 10:26:17.217   930  2899 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 10:26:17.255  5559  5605 I jxcore-log: JXcore Cordova bridge is ready!
10-05 10:26:17.255  5559  5605 I jxcore-log: 
,10-05 10:26:17.255  5559  5605 W jxcore-log: JXcore engine is started
,10-05 10:26:17.266  5559  5599 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-05 10:26:17.271  5559  5559 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-05 10:26:19.157   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 10:26:22.181   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 10:26:25.158   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:25.213   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 10:26:26.159   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:27.155  5559  5605 I jxcore-log: 2016-10-05 14:26:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-05 10:26:27.155  5559  5605 I jxcore-log: 
,10-05 10:26:27.157  5559  5605 I jxcore-log: 2016-10-05 14:26:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-05 10:26:27.157  5559  5605 I jxcore-log: 
,10-05 10:26:27.161   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:27.162  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:26:27.162  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:27.162  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:27.162  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:27.162  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:26:27.162  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:27.162  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:27.162  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:26:27.164  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 10:26:27.165  5559  5605 I jxcore-log: 2016-10-05 14:26:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-05 10:26:27.165  5559  5605 I jxcore-log: 
10-05 10:26:27.166  5559  5605 I jxcore-log: 2016-10-05 14:26:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-05 10:26:27.166  5559  5605 I jxcore-log: 
,10-05 10:26:27.423  5559  5605 I jxcore-log: 2016-10-05 14:26:27 - DEBUG UnitTest_app: 'Running unit tests'
10-05 10:26:27.423  5559  5605 I jxcore-log: 
,10-05 10:26:27.424  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 10:26:27.424  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0ba0d added. We now have 2 listener(s)
,10-05 10:26:27.425  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 10:26:27.425  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:26:27.425  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 10:26:27.425  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:26:27.425  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2d5dc2 added. We now have 2 listener(s)
10-05 10:26:27.425  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:26:27.426  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 10:26:27.427  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:26:27.431  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:26:27.431  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:27.431  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:27.431  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:27.431  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:26:27.431  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:27.431  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:27.431  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:26:27.432  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:27.432  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:26:27.432  5559  5605 D executeNativeTests: Running unit tests
,10-05 10:26:27.438  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:27.445  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:27.469  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 10:26:27.469  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 added. We now have 3 listener(s)
10-05 10:26:27.469  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:26:27.469  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:26:27.469  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 10:26:27.469  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 10:26:27.469  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 added. We now have 3 listener(s)
10-05 10:26:27.470  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:26:27.470  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 10:26:27.471  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 10:26:27.474  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:26:27.474  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:27.474  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:27.474  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:27.474  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:26:27.474  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:27.474  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:27.474  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:26:27.474  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:27.475  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:26:27.476  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-05 10:26:27.476  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-05 10:26:27.476  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 10:26:27.476  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 10:26:27.477  5559  5605 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-05 10:26:27.477  5559  5605 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-05 10:26:27.477  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-05 10:26:27.477  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-05 10:26:27.477  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 10:26:27.477  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 10:26:27.477  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:27.477  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:27.477  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-05 10:26:27.477  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:27.478  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:27.478  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:26:27.478  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:27.478  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:26:27.478  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 removed from the list
10-05 10:26:27.478  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:27.478  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 removed from the list
10-05 10:26:27.482  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:27.491  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:27.492  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:27.492  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:27.492  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:27.493  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:27.493  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:27.493  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:27.493  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:26:27.493  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:27.494  5559  5605 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-05 10:26:27.494  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:27.494  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:27.494  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:27.494  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:27.494  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:27.494  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:27.495  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:27.495  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:27.495  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:27.495  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:27.495  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:27.495  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:27.495  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:27.495  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:27.495  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:27.495  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:27.495  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 10:26:27.495  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:27.495  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-05 10:26:27.498  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-05 10:26:27.499  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-05 10:26:27.499  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-05 10:26:27.499  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-05 10:26:27.499  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-05 10:26:27.499  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-05 10:26:27.499  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:27.499  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:27.499  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:27.499  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 10:26:27.499  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:27.499  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:27.499  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:27.499  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:27.499  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:27.499  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:27.499  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:27.499  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:27.499  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:27.499  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:27.499  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:27.500  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:27.500  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:27.500  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:27.500  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:27.500  5559  5605 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-05 10:26:27.501  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:26:27.503  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:26:27.503  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:27.503  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:27.503  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:27.503  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:26:27.503  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:27.503  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:27.503  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:26:27.504  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:27.504  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:26:27.504  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 10:26:27.504  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-05 10:26:27.504  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 10:26:27.504  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:26:27.504  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 10:26:27.506  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:27.507  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:27.508  5559  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 10:26:27.508  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 10:26:27.510  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-05 10:26:27.511  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 10:26:27.512  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 10:26:27.513  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-05 10:26:27.514  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-05 10:26:27.514  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 10:26:27.514  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 10:26:27.514  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 10:26:27.514  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 10:26:27.514  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 10:26:27.515  5559  5605 D BluetoothAdapter: STATE_ON
10-05 10:26:27.517  4508  4739 D BtGatt.GattService: registerClient() - UUID=4e97085b-7425-4a74-a4ac-42c54d0c0600
10-05 10:26:27.517  4508  4569 D BtGatt.GattService: onClientRegistered() - UUID=4e97085b-7425-4a74-a4ac-42c54d0c0600, clientIf=5
10-05 10:26:27.519  5559  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 10:26:27.520  4508  4731 D BtGatt.GattService: start scan with filters
10-05 10:26:27.526  4508  4574 D BtGatt.ScanManager: handling starting scan
10-05 10:26:27.526  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 10:26:27.526  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 10:26:27.526  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:26:27.526  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 10:26:27.526  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 10:26:27.526  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 10:26:27.526  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-05 10:26:27.527  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 10:26:27.527  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 10:26:27.527  4508  4574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:26:27.528  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 10:26:27.528  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 10:26:27.529  5559  5605 I io.jxcore.node.ConnectionHelper: start: OK
10-05 10:26:27.535  4508  4569 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 10:26:27.535  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:27.536  4508  4574 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 10:26:27.543  4508  4569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 10:26:27.543  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:27.543  4508  4574 D BtGatt.ScanManager: Starting BLE batch scan
10-05 10:26:27.544  4508  4574 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-05 10:26:27.555  4508  4569 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 10:26:27.555  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:27.562  4508  4569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 10:26:27.562  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:26:28.029  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-05 10:26:28.030  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 10:26:28.030  5559  5559 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 10:26:28.162   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:28.232   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 10:26:28.235   930  2904 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-05 10:26:29.163   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:30.163   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-05 10:26:31.257   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 10:26:31.265   930  2904 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-05 10:26:32.533  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 10:26:32.534  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:32.534  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 10:26:32.534  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:32.534  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 10:26:32.534  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:32.534  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-05 10:26:32.534  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 10:26:32.534  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 10:26:32.534  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 10:26:32.535  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 10:26:32.535  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 10:26:32.536  5559  5605 D BluetoothAdapter: STATE_ON
10-05 10:26:32.537  4508  4740 D BtGatt.GattService: stopScan() - queue size =1
,10-05 10:26:32.538  4508  4739 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 10:26:32.538  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 10:26:32.539  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 10:26:32.539  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 10:26:32.539  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:26:32.539  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 10:26:32.539  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 10:26:32.539  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 10:26:32.539  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 10:26:32.540  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:26:32.541  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 10:26:32.541  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 10:26:32.541  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 10:26:32.541  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 10:26:32.542  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 10:26:32.543  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:32.543  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:32.544  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:26:32.544  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:32.544  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:32.544  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:32.544  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:32.544  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:26:32.544  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:32.544  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:32.544  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-05 10:26:32.545  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:26:32.547  4508  4508 D BtGatt.ScanManager: awakened up at time 237012
,10-05 10:26:32.555  4508  4569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-05 10:26:32.556  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:32.556  4508  4574 D BtGatt.ScanManager: stopping BLe Batch
,10-05 10:26:32.566  4508  4569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-05 10:26:32.566  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:32.566  4508  4574 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 10:26:32.592  4508  4569 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-05 10:26:32.593  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:32.593  4508  4569 D BtGatt.GattService: current time is 237058488291
10-05 10:26:32.594  4508  4569 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -95, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -93, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -89, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -88, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -81, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-05 10:26:32.596  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-05 10:26:32.597  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-05 10:26:32.597  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-05 10:26:32.597  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-05 10:26:32.598  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-05 10:26:32.598  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-05 10:26:33.046  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 10:26:35.165   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:36.166   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:37.168   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:37.314   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 10:26:37.546  5559  5605 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-05 10:26:37.552  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 10:26:37.563  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:26:37.563  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:37.563  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:37.563  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:37.563  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:26:37.563  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:37.563  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:37.563  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:26:37.569  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:37.569  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:26:37.570  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 10:26:37.570  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 10:26:37.570  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-05 10:26:37.570  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:26:37.570  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 10:26:37.575  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:37.577  5559  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-05 10:26:37.577  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 10:26:37.580  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:37.586  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 10:26:37.587  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 10:26:37.587  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 10:26:37.591  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 10:26:37.591  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 10:26:37.591  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-05 10:26:37.591  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 10:26:37.591  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 10:26:37.593  5559  5605 D BluetoothAdapter: STATE_ON
,10-05 10:26:37.596  4508  4739 D BtGatt.GattService: registerClient() - UUID=7db73b52-e235-4eed-8e11-fbb1adce31fe
10-05 10:26:37.597  4508  4569 D BtGatt.GattService: onClientRegistered() - UUID=7db73b52-e235-4eed-8e11-fbb1adce31fe, clientIf=5
10-05 10:26:37.598  5559  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 10:26:37.598  4508  4521 D BtGatt.GattService: start scan with filters
,10-05 10:26:37.602  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 10:26:37.603  4508  4574 D BtGatt.ScanManager: handling starting scan
10-05 10:26:37.603  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 10:26:37.603  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:26:37.603  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-05 10:26:37.603  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 10:26:37.603  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 10:26:37.603  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 10:26:37.608  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 10:26:37.608  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-05 10:26:37.609  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 10:26:37.610  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 10:26:37.612  4508  4569 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 10:26:37.612  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:37.612  4508  4574 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 10:26:37.613  5559  5605 I io.jxcore.node.ConnectionHelper: start: OK
10-05 10:26:37.617  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:37.617  5559  5605 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-05 10:26:37.617  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:37.617  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 10:26:37.617  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:37.617  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 10:26:37.617  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:37.617  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-05 10:26:37.617  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 10:26:37.617  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 10:26:37.617  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 10:26:37.618  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 10:26:37.618  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 10:26:37.618  5559  5605 D BluetoothAdapter: STATE_ON
10-05 10:26:37.619  4508  4521 D BtGatt.GattService: stopScan() - queue size =1
10-05 10:26:37.620  4508  4569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 10:26:37.620  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:37.620  4508  4731 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 10:26:37.620  4508  4574 D BtGatt.ScanManager: Starting BLE batch scan
10-05 10:26:37.620  4508  4574 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 10:26:37.621  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 10:26:37.621  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 10:26:37.621  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 10:26:37.621  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:26:37.621  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 10:26:37.621  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 10:26:37.621  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 10:26:37.621  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 10:26:37.623  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:26:37.623  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 10:26:37.623  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 10:26:37.623  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 10:26:37.623  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 10:26:37.623  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:26:37.625  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:37.625  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:26:37.625  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:37.625  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:26:37.625  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:26:37.625  5559  5559 I io.jxcore.node.Connecti,onHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:26:37.625  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 10:26:37.625  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:37.625  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:26:37.625  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:37.625  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:37.625  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:37.626  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:37.626  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:37.627  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:37.627  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:37.627  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:37.627  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:37.628  5559  5605 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-05 10:26:37.630  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:26:37.633  4508  4569 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 10:26:37.633  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:37.634  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:26:37.634  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:37.634  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:37.634  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:37.634  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:26:37.634  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:37.634  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:37.634  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:26:37.639  4508  4569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 10:26:37.639  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:26:37.640  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:37.640  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:26:37.640  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-05 10:26:37.640  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 10:26:37.640  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 10:26:37.640  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:26:37.640  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-05 10:26:37.642  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:37.644  5559  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 10:26:37.644  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 10:26:37.645  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:37.648  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 10:26:37.649  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 10:26:37.649  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 10:26:37.652  4508  4569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-05 10:26:37.652  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:37.652  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 10:26:37.652  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 10:26:37.652  4508  4574 D BtGatt.ScanManager: stopping BLe Batch
10-05 10:26:37.652  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 10:26:37.652  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 10:26:37.652  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-05 10:26:37.653  5559  5605 D BluetoothAdapter: STATE_ON
10-05 10:26:37.656  4508  4740 D BtGatt.GattService: registerClient() - UUID=ad3c006a-2e9a-4a8a-8697-b5a56746c9fa
10-05 10:26:37.657  4508  4569 D BtGatt.GattService: onClientRegistered() - UUID=ad3c006a-2e9a-4a8a-8697-b5a56746c9fa, clientIf=5
10-05 10:26:37.657  5559  5569 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 10:26:37.657  4508  4522 D BtGatt.GattService: start scan with filters
10-05 10:26:37.658  4508  4569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 10:26:37.658  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:37.659  4508  4574 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-05 10:26:37.660  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 10:26:37.660  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,10-05 10:26:37.660  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:26:37.660  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 10:26:37.660  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 10:26:37.660  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 10:26:37.660  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 10:26:37.664  4508  4569 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 10:26:37.664  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 10:26:37.664  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:37.664  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 10:26:37.664  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 10:26:37.665  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 10:26:37.666  4508  4574 D BtGatt.ScanManager: handling starting scan
10-05 10:26:37.668  5559  5605 I io.jxcore.node.ConnectionHelper: start: OK
,10-05 10:26:37.672  4508  4569 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-05 10:26:37.672  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:37.672  4508  4574 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 10:26:37.678  4508  4569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 10:26:37.678  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:37.678  4508  4574 D BtGatt.ScanManager: Starting BLE batch scan
,10-05 10:26:37.678  4508  4574 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-05 10:26:37.689  4508  4569 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-05 10:26:37.689  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:26:37.695  4508  4569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 10:26:37.695  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:26:38.166  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-05 10:26:38.166  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 10:26:38.166  5559  5559 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-05 10:26:38.169   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:39.170   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:40.171   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-05 10:26:42.668  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 10:26:42.668  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:42.669  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-05 10:26:42.669  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:42.669  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 10:26:42.669  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:42.669  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 10:26:42.670  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 10:26:42.670  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 10:26:42.670  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 10:26:42.670  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 10:26:42.670  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 10:26:42.672  5559  5605 D BluetoothAdapter: STATE_ON
,10-05 10:26:42.674  4508  4522 D BtGatt.GattService: stopScan() - queue size =1
10-05 10:26:42.676  4508  4521 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-05 10:26:42.677  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 10:26:42.677  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-05 10:26:42.677  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 10:26:42.678  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:26:42.678  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 10:26:42.678  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-05 10:26:42.678  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 10:26:42.679  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 10:26:42.684  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:26:42.684  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 10:26:42.684  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 10:26:42.685  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 10:26:42.685  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 10:26:42.684  4508  4508 D BtGatt.ScanManager: awakened up at time 247149
,10-05 10:26:42.686  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:26:42.688  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:26:42.688  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:26:42.689  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-05 10:26:42.692  4508  4569 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-05 10:26:42.692  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:26:42.692  4508  4574 D BtGatt.ScanManager: stopping BLe Batch
,10-05 10:26:42.702  4508  4569 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 10:26:42.703  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:26:42.703  4508  4574 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 10:26:42.722  4508  4569 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-05 10:26:42.723  4508  4569 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:26:42.723  4508  4569 D BtGatt.GattService: current time is 247188348676
10-05 10:26:42.723  4508  4569 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -87, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -95, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -95, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -88, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-05 10:26:42.724  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-05 10:26:42.724  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-05 10:26:42.724  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-05 10:26:42.725  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-05 10:26:42.725  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-05 10:26:42.726  4508  4569 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-05 10:26:43.190  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 10:26:43.190  5559  5559 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:43.190  5559  5559 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 10:26:47.690  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 10:26:47.690  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:47.690  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.690  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.690  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.691  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:26:47.691  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 10:26:47.691  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:47.691  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.691  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.692  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.692  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.693  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.694  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:47.697  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 10:26:47.697  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:47.697  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.697  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.699  5559  5605 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-05 10:26:47.703  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 10:26:47.703  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:47.703  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.704  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.704  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.704  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.704  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:47.704  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
,10-05 10:26:47.704  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.705  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.705  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.705  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.705  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.705  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.705  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.708  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 10:26:47.709  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:47.709  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:26:47.709  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
,10-05 10:26:47.711  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-05 10:26:47.711  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:47.711  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:47.711  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.711  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.711  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.711  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.712  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:47.712  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
,10-05 10:26:47.712  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.712  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.712  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.712  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.712  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.712  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.712  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.714  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:47.714  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 10:26:47.714  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.715  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.716  5559  5605 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-05 10:26:47.716  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:47.716  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:47.716  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.716  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.716  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.717  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:47.717  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:47.717  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:47.717  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.717  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.717  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.717  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.717  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:47.717  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.717  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.719  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:47.719  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:47.719  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.720  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.721  5559  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-05 10:26:47.721  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:47.721  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 10:26:47.721  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.721  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.722  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.722  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.722  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:47.722  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:47.722  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:26:47.722  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
,10-05 10:26:47.722  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.722  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.722  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.723  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.723  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:47.724  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:47.725  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:47.725  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.725  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.726  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-05 10:26:47.726  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-05 10:26:47.726  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 10:26:47.726  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-05 10:26:47.726  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 10:26:47.727  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 10:26:47.727  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-05 10:26:47.727  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 10:26:47.727  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-05 10:26:47.727  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:47.727  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:47.727  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.728  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.728  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.728  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:47.728  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:47.728  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:47.728  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.728  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.728  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.728  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.729  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.729  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.729  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:47.730  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:47.730  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:47.730  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.730  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.732  5559  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 10:26:47.732  5559  5605 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,10-05 10:26:47.732  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-05 10:26:47.738  5559  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 10:26:47.739  5559  5605 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-05 10:26:47.739  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-05 10:26:47.739  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-05 10:26:47.739  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,10-05 10:26:47.739  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-05 10:26:47.739  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-05 10:26:47.739  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-05 10:26:47.739  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-05 10:26:47.739  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-05 10:26:47.740  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-05 10:26:47.741  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-05 10:26:47.742  5559  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-05 10:26:47.742  5559  5605 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 10:26:47.742  5559  5605 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-05 10:26:47.742  5559  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 10:26:47.742  5559  5605 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 10:26:47.743  5559  5605 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,10-05 10:26:47.743  5559  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 10:26:47.743  5559  5605 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 10:26:47.743  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-05 10:26:47.748  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-05 10:26:47.749  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-05 10:26:47.749  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-05 10:26:47.750  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-05 10:26:47.750  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-05 10:26:47.750  5559  5605 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-05 10:26:47.750  5559  5605 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 10:26:47.751  5559  5605 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-05 10:26:47.751  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
,10-05 10:26:47.751  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-05 10:26:47.751  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-05 10:26:47.752  5559  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-05 10:26:47.752  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:47.752  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:47.752  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.752  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.752  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.752  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.752  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:47.752  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-05 10:26:47.753  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:47.753  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.753  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.753  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 10:26:47.753  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.754  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.754  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.754  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.754  5559  5607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-05 10:26:47.756  5559  5606 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-05 10:26:47.756  5559  5606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 10:26:47.755  4740  4740 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30276]" dev="sockfs" ino=30276 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-05 10:26:47.755  4740  4740 W Binder_5: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30276]" dev="sockfs" ino=30276 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-05 10:26:47.756  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:47.756  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:47.756  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:26:47.756  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.757  5559  5605 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-05 10:26:47.758  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:47.759  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:47.759  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.759  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.759  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.759  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.759  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:47.759  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:47.759  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.759  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.759  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.759  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.759  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.759  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 10:26:47.759  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.761  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:47.761  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:47.761  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.761  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.762  5559  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-05 10:26:47.762  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:47.762  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:47.762  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.762  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.762  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.763  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.763  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 10:26:47.763  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:47.763  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.763  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.763  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.763  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.763  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.763  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.763  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.765  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:47.765  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:47.765  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.765  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.766  5559  5605 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-05 10:26:47.766  5559  5605 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-05 10:26:47.766  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 10:26:47.766  5559  5605 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-05 10:26:47.766  5559  5605 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,10-05 10:26:47.766  5559  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-05 10:26:47.767  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 10:26:47.767  5559  5605 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-05 10:26:47.767  5559  5605 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-05 10:26:47.767  5559  5605 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-05 10:26:47.767  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 10:26:47.767  5559  5605 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-05 10:26:47.767  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:47.767  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:47.767  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:47.767  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.767  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.767  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.767  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:47.768  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:47.768  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.768  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
,10-05 10:26:47.768  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.768  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.768  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.768  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.768  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.769  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:47.769  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:47.769  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.769  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:47.770  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:47.770  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.770  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:47.770  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:47.770  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:47.770  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:47.770  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
,10-05 10:26:47.770  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:47.770  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:47.770  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:50.172   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:51.173   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:52.174   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:52.771  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:26:52.771  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:52.772  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:52.772  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.772  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.772  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 10:26:52.772  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:52.773  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:52.773  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:52.773  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:52.773  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 10:26:52.773  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.773  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.774  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:52.774  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:52.774  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:52.774  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
,10-05 10:26:52.775  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:52.775  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.775  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.775  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.775  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.778  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 10:26:52.778  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:52.778  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:52.779  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
,10-05 10:26:52.783  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-05 10:26:52.784  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 10:26:52.786  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-05 10:26:52.788  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-05 10:26:52.789  5559  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-05 10:26:52.789  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-05 10:26:52.789  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-05 10:26:52.789  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-05 10:26:52.789  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 10:26:52.790  5559  5559 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-05 10:26:52.790  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:52.790  5559  5608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 10:26:52.790  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-05 10:26:52.790  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-05 10:26:52.791  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-05 10:26:52.791  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.791  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-05 10:26:52.789  4740  4740 W Binder_5: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31586]" dev="sockfs" ino=31586 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-05 10:26:52.789  4740  4740 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31586]" dev="sockfs" ino=31586 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-05 10:26:52.791  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-05 10:26:52.792  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:52.792  5559  5559 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-05 10:26:52.792  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:52.793  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 10:26:52.793  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-05 10:26:52.793  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 10:26:52.793  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.793  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.794  5559  5608 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-05 10:26:52.794  5559  5608 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-05 10:26:52.794  5559  5608 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-05 10:26:52.796  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:26:52.796  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-05 10:26:52.796  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:52.796  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:26:52.796  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:52.796  5559  5559 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-05 10:26:52.796  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 10:26:52.796  5559  5559 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:52.796  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:52.796  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:26:52.796  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:52.796  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.797  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.797  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 10:26:52.797  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:52.797  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:26:52.797  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:52.797  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 10:26:52.797  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.797  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:52.797  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.797  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.799  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:52.799  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:52.799  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:52.799  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:52.801  5559  5605 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-05 10:26:52.802  5559  5605 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-05 10:26:52.802  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-05 10:26:52.802  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 10:26:52.802  5559  5605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 10:26:52.802  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:52.803  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:52.803  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:52.803  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:52.803  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.803  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.803  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:52.803  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:52.803  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:26:52.803  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:52.803  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:52.803  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.804  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.804  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.804  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.807  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:52.807  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:52.807  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:52.807  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
,10-05 10:26:52.814  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:26:52.814  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:52.814  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:52.814  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:52.814  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.814  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.814  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:52.814  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:52.814  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:26:52.814  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:52.815  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:52.815  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.815  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.815  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.815  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.816  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:52.816  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:52.816  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:52.816  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
10-05 10:26:52.817  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 10:26:52.817  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:26:52.817  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:26:52.818  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:26:52.818  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.818  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.818  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:26:52.818  5559  5605 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b8c40 not in the list
10-05 10:26:52.818  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:52.818  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
,10-05 10:26:52.818  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:52.818  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.818  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.818  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:52.818  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:52.820  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:26:52.820  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:26:52.820  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:52.820  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a66779 not in the list
,10-05 10:26:52.821  5559  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-05 10:26:52.821  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 10:26:52.821  5559  5605 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-05 10:26:52.822  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 10:26:52.822  5559  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-05 10:26:52.822  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 10:26:52.824  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-05 10:26:52.824  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,10-05 10:26:52.825  5559  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,10-05 10:26:52.826  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-05 10:26:52.826  5559  5605 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-05 10:26:52.827  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-05 10:26:52.827  5559  5605 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-05 10:26:52.827  5559  5605 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-05 10:26:52.827  5559  5605 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-05 10:26:52.828  5559  5605 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-05 10:26:52.828  5559  5605 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-05 10:26:52.828  5559  5605 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,10-05 10:26:52.828  5559  5605 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-05 10:26:52.828  5559  5605 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-05 10:26:52.830  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:26:52.830  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e7c1bb3 added. We now have 3 listener(s)
10-05 10:26:52.830  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 10:26:52.832  5559  5605 D BluetoothAdapter: enable(): BT is already enabled..!
10-05 10:26:52.833   930  3338 D WifiService: setWifiEnabled: true pid=5559, uid=10077
10-05 10:26:52.833   930  3338 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 10:26:52.886  4508  4715 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-05 10:26:52.886  4508  4729 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
10-05 10:26:52.886  5559  5606 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-05 10:26:52.887  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-05 10:26:52.887  5559  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,10-05 10:26:53.176   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:53.297  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 10:26:54.177   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:26:55.177   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-05 10:26:57.224   930  2899 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 10:26:57.838  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 10:26:57.839  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aba8570 added. We now have 4 listener(s)
,10-05 10:26:57.839  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:26:57.850  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:57.850  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aba8570 removed from the list
10-05 10:26:57.850  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:57.850  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:26:57.850  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:26:57.854  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 10:26:57.856  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab320e9 added. We now have 4 listener(s)
,10-05 10:26:57.856  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:26:57.859  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:26:57.859  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab320e9 removed from the list
10-05 10:26:57.859  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:26:57.859  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 10:26:57.859  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:26:57.860  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:26:57.860  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f82316e added. We now have 4 listener(s)
10-05 10:26:57.860  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 10:26:57.864   930   941 D WifiService: setWifiEnabled: false pid=5559, uid=10077
10-05 10:26:57.864   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 10:26:57.868   930  2899 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-05 10:26:57.869   930  2899 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-05 10:26:57.869   930  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-05 10:26:57.869   930  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 10:26:57.874  4508  4565 D BluetoothAdapterState: Current state: ON, message: 23
,10-05 10:26:57.875  4508  4565 D BluetoothAdapterProperties: Setting state to 13
,10-05 10:26:57.875  4508  4565 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-05 10:26:57.877  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:26:57.877  4508  4565 D BluetoothAdapterProperties: onBluetoothDisable()
10-05 10:26:57.878  4508  4565 I BluetoothAdapterState: Entering PendingCommandState
10-05 10:26:57.879  4508  4569 D BluetoothAdapterProperties: Scan Mode:20
10-05 10:26:57.880  4508  4565 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-05 10:26:57.881  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.881  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:26:57.881  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:57.881  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:57.881  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:57.881  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:57.881  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:57.881  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:57.881  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:26:57.881   507   911 D CommandListener: Clearing all IP addresses on wlan0
10-05 10:26:57.881  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.882  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:57.882  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:26:57.883  4508  4508 D HeadsetService: Received stop request...Stopping profile...
10-05 10:26:57.883   930  5290 D DhcpClient: Clearing IP address
10-05 10:26:57.886  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:57.886  3055  3067 D BluetoothHeadset: Proxy object disconnected
10-05 10:26:57.886  3055  3055 D HeadsetProfile: Bluetooth service disconnected
,10-05 10:26:57.887   930   930 D BluetoothHeadset: Proxy object disconnected
,10-05 10:26:57.887   930   930 D BluetoothHeadset: Proxy object disconnected
10-05 10:26:57.887   930   930 D BluetoothHeadset: Proxy object disconnected
10-05 10:26:57.887  3702  3951 D BluetoothHeadset: Proxy object disconnected
,10-05 10:26:57.887  4508  4508 D A2dpService: Received stop request...Stopping profile...
10-05 10:26:57.888  4508  4734 D A2dpStateMachine: Exit Disconnected: -1
10-05 10:26:57.889   507   911 D CommandListener: Setting iface cfg
10-05 10:26:57.890   930   930 D BluetoothA2dp: Proxy object disconnected
,10-05 10:26:57.890  4508  4508 V BluetoothAdapterState: isTurningOff()=true
,10-05 10:26:57.890  4508  4508 V BluetoothAdapterState: isTurningOn()=false
10-05 10:26:57.890  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:26:57.890  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:26:57.891  3055  3055 D BluetoothA2dp: Proxy object disconnected
10-05 10:26:57.893  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:57.893   930  5291 D DhcpClient: Receive thread stopped
,10-05 10:26:57.894  4508  4508 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-05 10:26:57.894  4508  4508 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-05 10:26:57.894  4508  4569 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-05 10:26:57.895  4508  4715 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:26:57.895  4508  4508 V BluetoothAdapterState: isTurningOff()=true
10-05 10:26:57.895  4508  4715 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:26:57.895  4508  4508 V BluetoothAdapterState: isTurningOn()=false
10-05 10:26:57.895  4508  4715 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:26:57.895  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:26:57.895  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:26:57.895  4508  4569 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-05 10:26:57.896  4508  4508 D HidService: Received stop request...Stopping profile...
10-05 10:26:57.896  4508  4508 D HidService: Stopping Bluetooth HidService
10-05 10:26:57.897  3055  3055 D BluetoothInputDevice: Proxy object disconnected
10-05 10:26:57.897  3055  3055 D HidProfile: Bluetooth service disconnected
10-05 10:26:57.898  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.898  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:26:57.898  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:57.898  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:57.898  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:57.898  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:57.898  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:57.898  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:57.898  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:26:57.899  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:26:57.900  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:57.902  3509  5346 V NativeCrypto: Read error: ssl=0x7f888af000: I/O error during system call, Connection timed out
10-05 10:26:57.903  3509  5346 V NativeCrypto: SSL shutdown failed: ssl=0x7f888af000: I/O error during system call, Broken pipe
10-05 10:26:57.904  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:26:57.904  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:26:57.904  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:57.904  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:57.904  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:57.904  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:57.904  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:57.904  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:57.904  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:26:57.905  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:26:57.905  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:26:57.906   930  3709 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-05 10:26:57.906  4508  4508 D HealthService: Received stop request...Stopping profile...
10-05 10:26:57.906   930  5288 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,10-05 10:26:57.906  4508  4715 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:26:57.906  4508  4715 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:26:57.906  4508  4715 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 10:26:57.907  4508  4715 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 10:26:57.907  4508  4715 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 10:26:57.907  4508  4715 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 10:26:57.907  4508  4569 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-05 10:26:57.908   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-05 10:26:57.909   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-05 10:26:57.912  4508  4508 D PanService: Received stop request...Stopping profile...
10-05 10:26:57.912   534   534 E Parcel  : Reading a NULL string not supported here.
10-05 10:26:57.913  4508  4508 V BluetoothAdapterState: isTurningOff()=true
10-05 10:26:57.913  4508  4508 V BluetoothAdapterState: isTurningOn()=false
10-05 10:26:57.913  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:26:57.913  3055  3055 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 10:26:57.913  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:26:57.913  3055  3055 D PanProfile: Bluetooth service disconnected
10-05 10:26:57.914   930  2904 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-05 10:26:57.914  4508  4508 D BluetoothMapService: Received stop request...Stopping profile...
10-05 10:26:57.914  4508  4508 D BluetoothMapService: stop()
10-05 10:26:57.914  4508  4508 D BluetoothMapAppObserver: deinitObservers()
10-05 10:26:57.914  4508  4508 D BluetoothMapAppObserver: removeReceiver()
10-05 10:26:57.915  3667  3819 W QCNEJ   : |CORE| network lost: 100
10-05 10:26:57.915   930  5288 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-05 10:26:57.915  3667  3819 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-05 10:26:57.917   930   930 D RttService: SCAN_AVAILABLE : 1
10-05 10:26:57.917   930  3008 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-05 10:26:57.918  3055  3055 D BluetoothMap: Proxy object disconnected
10-05 10:26:57.918  3055  3055 D MapProfile: Bluetooth service disconnected
10-05 10:26:57.920  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.920  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:26:57.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:57.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:57.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:57.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:57.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:26:57.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:26:57.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:26:57.920  4508  4508 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-05 10:26:57.920  4508  4508 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,10-05 10:26:57.920  4508  4569 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 10:26:57.921  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.921  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:26:57.921  4508  4508 D SapService: Received stop request...Stopping profile...
10-05 10:26:57.921  4508  4508 V SapService: stop()
10-05 10:26:57.926  4508  4508 V BluetoothAdapterState: isTurningOff()=true
10-05 10:26:57.926  4508  4508 V BluetoothAdapterState: isTurningOn()=false
10-05 10:26:57.926  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:26:57.926  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:26:57.926  4508  4508 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-05 10:26:57.926  4508  4508 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-05 10:26:57.927  4508  4508 V BluetoothAdapterState: isTurningOff()=true
10-05 10:26:57.927  4508  4508 V BluetoothAdapterState: isTurningOn()=false
10-05 10:26:57.927  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:26:57.927  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:26:57.927  4508  4508 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-05 10:26:57.927  4508  4508 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-05 10:26:57.927  4508  4569 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-05 10:26:57.928  4508  4508 D BluetoothMapService: MAP Service closeService in
10-05 10:26:57.928  4508  4508 D BluetoothMapMasInstance0: MAP Service shutdown
10-05 10:26:57.928  4508  4508 D ObexServerSockets0: shutdown(block = true)
10-05 10:26:57.929  4508  4508 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 10:26:57.929  4508  4742 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-05 10:26:57.929  4508  4508 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 10:26:57.929  4508  4729 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-05 10:26:57.929  4508  4743 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-05 10:26:57.930  4508  4508 V BluetoothAdapterState: isTurningOff()=true
10-05 10:26:57.930  4508  4508 V BluetoothAdapterState: isTurningOn()=false
10-05 10:26:57.930  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:26:57.930  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:26:57.930  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.931  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:26:57.931  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:57.931  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:57.931  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:57.931  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:57.931  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:26:57.931  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:26:57.931  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:26:57.931  4508  4508 D BluetoothMapService: cleanup()
,10-05 10:26:57.931  4508  4508 D BluetoothMapService: MAP Service closeService in
10-05 10:26:57.931  4508  4508 V BluetoothAdapterState: isTurningOff()=true
10-05 10:26:57.931  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.931  4508  4508 V BluetoothAdapterState: isTurningOn()=false
10-05 10:26:57.932  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:26:57.932  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:26:57.932  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:26:57.932  4508  4565 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-05 10:26:57.932  4508  4565 D BluetoothAdapterProperties: Setting state to 15
10-05 10:26:57.932  4508  4565 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-05 10:26:57.932  4508  4508 I BtOppRfcommListener: stopping Accept Thread
10-05 10:26:57.932  4508  5220 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,10-05 10:26:57.932  4508  5220 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-05 10:26:57.934  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.934  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:26:57.934  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:57.934  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:57.934  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:57.934  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:57.934  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:26:57.934  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:26:57.934  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:26:57.935  4508  4565 I BluetoothAdapterState: Entering BleOnState
10-05 10:26:57.935  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.935  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:26:57.938  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.938  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:26:57.938  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:57.938  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:57.938  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:26:57.938  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:57.938  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:26:57.938  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:26:57.938  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 10:26:57.939   930  2899 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-05 10:26:57.939   930   943 I ActivityManager: Start proc 5617:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-05 10:26:57.940  3055  3885 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-05 10:26:57.942  3055  3066 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 10:26:57.942  3055  3067 D BluetoothPan: onBluetoothStateChange on: false
10-05 10:26:57.944  3055  3888 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-05 10:26:57.944   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 10:26:57.946  3055  3885 D BluetoothPbap: onBluetoothStateChange: up=false
10-05 10:26:57.947  3702  3723 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 10:26:57.947   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 10:26:57.947   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 10:26:57.947   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 10:26:57.948  3055  3066 D BluetoothMap: onBluetoothStateChange: up=false
10-05 10:26:57.949  4508  4565 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-05 10:26:57.949  4508  4565 D BluetoothAdapterProperties: Setting state to 16
10-05 10:26:57.949  4508  4565 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-05 10:26:57.949   930  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 10:26:57.949  4508  4565 D BluetoothAdapterProperties: onBleDisable
10-05 10:26:57.950  4508  4565 I BluetoothAdapterState: Entering PendingCommandState
10-05 10:26:57.950  4508  4566 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-05 10:26:57.951  4508  4715 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-05 10:26:57.951  4508  4715 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:26:57.952  4508  4569 D BluetoothAdapterProperties: Scan Mode:20
10-05 10:26:57.954   507   911 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-05 10:26:57.954  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:57.956  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:57.957  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:57.959  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:57.961  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:57.962  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:57.977   507   911 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 10:26:57.978   507   911 D CommandListener: Clearing all IP addresses on wlan0
10-05 10:26:57.978   930  2904 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-05 10:26:57.979   507   911 D TetherController: Setting IP forward enable = 0
,10-05 10:26:57.979   930  2904 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 10:26:57.980   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-05 10:26:57.982  5174  5174 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3cd8591 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-05 10:26:57.982  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:26:57.984  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:57.985  3823  3823 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-05 10:26:57.986  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:57.987   930  2899 D DhcpClient: doQuit
10-05 10:26:57.987   930  2899 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-05 10:26:57.987  4952  4976 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-05 10:26:57.987   930  5290 D DhcpClient: onQuitting
10-05 10:26:57.987  4952  4976 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-05 10:26:57.987  4952  4976 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-05 10:26:57.988  4952  4976 E SarControlService: no key has been found,reset the power
10-05 10:26:57.988  4952  4989 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 10:26:57.988  4952  4989 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 10:26:57.988  4952  4989 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 10:26:57.989  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 10:26:57.989  4977  4977 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 10:26:57.989  3370  3370 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-05 10:26:57.992  4977  4991 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cee853f HexData = [00000000ea03000000000000ffffffff]
10-05 10:26:57.993  4977  4991 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 10:26:57.993  4977  4991 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,10-05 10:26:57.993  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.993  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:26:57.993  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:57.993  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:57.993  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:26:57.993  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:57.993  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:26:57.993  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:26:57.993  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:26:57.993  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 10:26:57.994  4952  4963 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 10:26:57.994  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.994  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:26:57.994  4952  4989 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 10:26:57.994  4952  4989 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 10:26:57.994  4952  4989 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 10:26:57.995  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 10:26:57.995  4977  4977 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 10:26:57.996  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:57.996  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:26:57.996  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:57.996  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:57.996  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:26:57.996  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:57.996  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:26:57.996  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:26:57.996  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:26:57.997  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:26:57.997  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:26:58.000  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:58.000  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:26:58.000  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:26:58.000  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:26:58.000  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:26:58.000  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:26:58.000  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:26:58.000  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:26:58.000  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:26:58.001  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:26:58.001  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:26:58.003  4977  4991 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cee853f HexData = [00000000eb03000000000000ffffffff]
10-05 10:26:58.003  4977  4991 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 10:26:58.003  4977  4991 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-05 10:26:58.003  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 10:26:58.004  4952  4962 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-05 10:26:58.006  5617  5617 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-05 10:26:58.012  3370  3370 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-05 10:26:58.015  3370  3370 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-05 10:26:58.017   507   904 W SocketClient: write error (Broken pipe)
10-05 10:26:58.017   507   904 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
,10-05 10:26:58.017   507   904 W SocketListener: Error sending broadcast (Broken pipe)
,10-05 10:26:58.019  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 10:26:58.023   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f5e8202:true
,10-05 10:26:58.025  3509  3509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 10:26:58.036   930  3079 I ActivityManager: Start proc 5639:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-05 10:26:58.043  3370  3370 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-05 10:26:58.055  3370  3370 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-05 10:26:58.056   507   904 W SocketClient: write error (Broken pipe)
10-05 10:26:58.056   507   904 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-05 10:26:58.056   507   904 W SocketListener: Error sending broadcast (Broken pipe)
,10-05 10:26:58.063  5617  5617 D LocalBluetoothProfileManager: Adding local MAP profile
,10-05 10:26:58.065  5617  5617 D BluetoothMap: Create BluetoothMap proxy object
,10-05 10:26:58.078  5639  5639 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-05 10:26:58.083  5617  5617 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-05 10:26:58.102  5617  5617 D DockEventReceiver: finishStartingService: stopping service
,10-05 10:26:58.105   930  3788 I ActivityManager: Killing 4859:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-05 10:26:58.157  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-05 10:26:58.157   930  2899 D wifi    : In wifi stop Hal
10-05 10:26:58.157   930  2899 D wifi    : halHandle = 0x7f76da3080, mVM = 0x7f933cd140, mCls = 0x100a02
,10-05 10:26:58.157   930  3369 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-05 10:26:58.157   930  3369 D WifiHAL : Got a signal to exit!!!
10-05 10:26:58.157   930  3369 I WifiHAL : Exit wifi_event_loop
10-05 10:26:58.159   930  2899 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-05 10:26:58.159   930  2899 E WifiHAL : Event processing terminated
10-05 10:26:58.159   930  2899 D wifi    : In wifi cleaned up handler
10-05 10:26:58.159   930  2899 I WifiHAL : Internal cleanup completed
10-05 10:26:58.161  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:58.161  4064  4148 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 10:26:58.162  4508  4569 I bt_hci  : shut_down
10-05 10:26:58.163  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:58.164  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:26:58.165  4508  4575 D bt_hwcfg: hw_epilog_process
10-05 10:26:58.165  4508  4575 I bt_vendor: low_power_mode_cb
,10-05 10:26:58.168  4508  4575 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-05 10:26:58.168  4508  4575 I bt_vendor: epilog_cb
10-05 10:26:58.168  4508  4575 I bt_hci  : epilog_finished_callback
,10-05 10:26:58.170  4508  4569 I bt_hci_h4: hal_close
,10-05 10:26:58.171  4508  4569 I bt_userial_vendor: device fd = 54 close
,10-05 10:26:58.176   930  3369 D wifi    : set interface wlan0 flags (DOWN)
,10-05 10:26:58.177   507   904 W SocketClient: write error (Broken pipe)
10-05 10:26:58.177   930  2899 D WifiNative-HAL: HAL event thread stopped successfully
10-05 10:26:58.177   507   904 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 down'
10-05 10:26:58.177   507   904 W SocketListener: Error sending broadcast (Broken pipe)
,10-05 10:26:58.280  4508  4566 D bt_stack_manager: event_shut_down_stack finished.
,10-05 10:26:58.280  4508  4565 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-05 10:26:58.282  4508  4565 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-05 10:26:58.282  4508  4508 D BtGatt.DebugUtils: handleDebugAction() action=null
10-05 10:26:58.283  4508  4508 D BtGatt.GattService: Received stop request...Stopping profile...
10-05 10:26:58.283  4508  4508 D BtGatt.GattService: stop()
10-05 10:26:58.283  4508  4508 D BtGatt.AdvertiseManager: advertise clients cleared
,10-05 10:26:58.284  4508  4508 V BluetoothAdapterState: isTurningOff()=false
10-05 10:26:58.284  4508  4508 V BluetoothAdapterState: isTurningOn()=false
10-05 10:26:58.285  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:26:58.285  4508  4508 V BluetoothAdapterState: isBleTurningOff()=true
10-05 10:26:58.285  4508  4565 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-05 10:26:58.285  4508  4565 D BluetoothAdapterProperties: Setting state to 10
,10-05 10:26:58.285  4508  4565 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,10-05 10:26:58.286  4508  4565 I BluetoothAdapterState: Entering OffState
10-05 10:26:58.287   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-05 10:26:58.296  4508  4508 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-05 10:26:58.296  4508  4508 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-05 10:26:58.296  4508  4508 I BluetoothServiceJni: cleanupNative: return from cleanup
10-05 10:26:58.297  4508  4566 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-05 10:26:58.301  4508  4508 I art     : System.exit called, status: 0
,10-05 10:26:58.301  4508  4508 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-05 10:26:58.336  5639  5639 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:26:58.336  5639  5639 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:26:58.336  5639  5639 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:26:58.336  5639  5639 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.e.b(PG:170)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:26:58.336  5639  5639 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.k.d(PG:583)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.e.b(PG:170)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:26:58.336  5639  5639 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:26:58.336  5639  5639 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:26:58.336  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:26:58.337  5639  5639 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 10:26:58.337  5639  5639 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:26:58.337  5639  5639 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:26:58.341   930  3123 I ActivityManager: Process com.android.bluetooth (pid 4508) has died
10-05 10:26:58.342  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 10:26:58.355   930  3788 I ActivityManager: Start proc 5670:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
10-05 10:26:58.358  5617  5617 D DockEventReceiver: finishStartingService: stopping service
10-05 10:26:58.359   930  3860 I ActivityManager: Killing 5035:com.google.android.deskclock/u0a66 (adj 15): empty #17
,10-05 10:26:58.379   930   947 D Tethering: InitialState.processMessage what=4
10-05 10:26:58.387   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-05 10:26:58.436  5670  5670 D AdapterServiceConfig: Adding HeadsetService
,10-05 10:26:58.436  5670  5670 D AdapterServiceConfig: Adding A2dpService
10-05 10:26:58.436  5670  5670 D AdapterServiceConfig: Adding HidService
10-05 10:26:58.436  5670  5670 D AdapterServiceConfig: Adding HealthService
10-05 10:26:58.436  5670  5670 D AdapterServiceConfig: Adding PanService
10-05 10:26:58.436  5670  5670 D AdapterServiceConfig: Adding GattService
10-05 10:26:58.436  5670  5670 D AdapterServiceConfig: Adding BluetoothMapService
10-05 10:26:58.437  5670  5670 D AdapterServiceConfig: Adding SapService
10-05 10:26:58.438   930  3789 I ActivityManager: Killing 5368:com.qualcomm.timeservice/1000 (adj 15): empty #17
,10-05 10:26:58.461  3509  3509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 10:26:58.468  3866  3866 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-05 10:26:58.473  3866  3866 D SystemUpdateService: onCreate
,10-05 10:26:58.477  3866  3866 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 10:26:58.484  3866  3866 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-05 10:26:58.486  3866  5315 I iu.UploadsManager: num queued entries: 0
10-05 10:26:58.486  3866  5315 I iu.UploadsManager: num updated entries: 0
10-05 10:26:58.487  3866  5315 I iu.SyncManager: NEXT; no task
,10-05 10:26:58.491  3866  3866 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 10:26:58.493  3866  3866 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 10:26:58.494  3866  5683 I SystemUpdateService: active receiver: enabled
,10-05 10:26:58.502  3866  5683 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 10:26:58.505   930  3338 I ActivityManager: Start proc 5685:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-05 10:26:58.509  3866  5683 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-05 10:26:58.509  3866  5683 I SystemUpdateService: now status is 0 (complete)
10-05 10:26:58.509  3866  5683 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,10-05 10:26:58.509  3866  5683 I SystemUpdateService: file has been verified
10-05 10:26:58.509  3866  5683 I SystemUpdateService: OTA package size = 21989297
,10-05 10:26:58.522  3866  5683 I SystemUpdateService: showing system update notification
,10-05 10:26:58.541  5685  5685 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-05 10:26:58.544  5685  5685 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 10:26:58.553  5685  5685 D SprintDMHelper: simOperator: 
,10-05 10:26:58.553  5685  5685 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 10:26:58.564   930   940 I ActivityManager: Start proc 5697:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-05 10:26:58.587  3866  3866 D SystemUpdateService: onDestroy
,10-05 10:26:58.588   930  3789 I ActivityManager: Killing 5350:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-05 10:26:58.688  4926  5711 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-05 10:26:58.697   930  3123 I ActivityManager: Start proc 5712:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-05 10:26:58.699   930  3860 I ActivityManager: Killing 5174:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-05 10:26:58.732  5639  5664 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-05 10:26:58.758  5712  5712 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-05 10:26:58.792   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff885d6:true
,10-05 10:26:58.950   930  3788 I ActivityManager: Killing 4579:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-05 10:26:58.992   930   940 I ActivityManager: Start proc 5726:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-05 10:26:59.024  5726  5726 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-05 10:26:59.032   930  3123 I ActivityManager: Killing 5418:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-05 10:26:59.044   507   911 E Netd    : netlink response contains error (No such file or directory)
,10-05 10:26:59.045   507   911 D TetherController: Setting IP forward enable = 0
,10-05 10:26:59.045   930  2904 E NetdConnector: NDC Command {113 network destroy 100} took too long (1065ms)
10-05 10:26:59.045   930  2897 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1060ms)
10-05 10:26:59.046   930  2904 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-05 10:26:59.046   930  2904 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-05 10:26:59.046   930  2896 E NetdConnector: NDC Command {115 bandwidth gettetherstats} took too long (658ms)
,10-05 10:27:02.884   930  3709 D WifiService: setWifiEnabled: true pid=5559, uid=10077
10-05 10:27:02.884   930  3709 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 10:27:02.892   507   911 D SoftapController: Softap fwReload - Ok
,10-05 10:27:02.898   507   911 D CommandListener: Setting iface cfg
10-05 10:27:02.899   507   911 D CommandListener: Trying to bring down wlan0
,10-05 10:27:02.901   507   911 D CommandListener: Clearing all IP addresses on wlan0
,10-05 10:27:02.909   930  2899 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 10:27:03.476   930  2899 D wifi    : set interface wlan0 flags (UP)
10-05 10:27:03.480   930  2899 I WifiHAL : Initializing wifi
10-05 10:27:03.480   930  2899 I WifiHAL : Creating socket
10-05 10:27:03.483   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-05 10:27:03.488   930  2899 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-05 10:27:03.489   930  2899 D wifi    : Did set static halHandle = 0x7f76da3080
10-05 10:27:03.490   930  2899 D wifi    : halHandle = 0x7f76da3080, mVM = 0x7f933cd140, mCls = 0x1019f6
10-05 10:27:03.490   930  2899 D wifi    : array field set
10-05 10:27:03.490   930  2899 I WifiNative-HAL: interface[0] = wlan0
10-05 10:27:03.492   930  5751 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547454857344
10-05 10:27:03.492   930  5751 D wifi    : waitForHalEvents called, vm = 0x7f933cd140, obj = 0x1019f6, env = 0x7f88910800
,10-05 10:27:03.566  5752  5752 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-05 10:27:03.583  5752  5752 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 10:27:03.591  5752  5752 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 10:27:03.591  5752  5752 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-05 10:27:03.596   930  2899 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-05 10:27:03.600  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:03.605  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:27:03.605  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:03.605  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:03.605  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:03.605  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:03.605  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:03.605  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:03.605  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:03.605  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:03.605  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:03.605  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:03.606   930  2899 D WifiConfigStore: Loading config and enabling all networks 
10-05 10:27:03.608  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:03.609  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:03.609  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:03.609  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:03.609  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:03.609  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:03.609  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:03.609  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:03.609  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:03.609  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:03.609  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:03.610  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:27:03.610  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:03.610  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:03.610  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:03.610  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:03.610  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:03.610  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:03.610  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:03.610  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:03.610  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:03.610  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 10:27:03.612  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:03.614  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:03.615   930  2899 D WifiConfigStore: loaded 0 passpoint configs
10-05 10:27:03.615   930  2899 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-05 10:27:03.616   930  2899 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-05 10:27:03.616   930  2899 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-05 10:27:03.617   930  2899 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-05 10:27:03.617   930  2899 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-05 10:27:03.617   930  2899 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,10-05 10:27:03.617   930  2899 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-05 10:27:03.619   930  2899 D WifiNative-HAL: Setting external_sim to 1
,10-05 10:27:03.620   930  2899 D wifi    : setting dfs flag to true, 0x7f7a93f160
,10-05 10:27:03.620  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 10:27:03.620   930  2899 D WifiStateMachine: Setting OUI to DA-A1-19
,10-05 10:27:03.620   930  2899 D wifi    : setting scan oui 0x7f7a93f160
10-05 10:27:03.620   930  2899 D WifiHAL : Sending mac address OUI
,10-05 10:27:03.623   930  2899 E native  : do suspend false
,10-05 10:27:03.629   930  2899 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-05 10:27:03.630   930   930 D RttService: SCAN_AVAILABLE : 3
10-05 10:27:03.630   507   911 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-05 10:27:03.630   930  3008 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-05 10:27:03.631   507   911 D CommandListener: Setting iface cfg
,10-05 10:27:03.634   930  2898 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-05 10:27:03.634   930  2898 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-05 10:27:03.643   930  2898 D WifiNative-HAL: p2pGetDeviceAddress
,10-05 10:27:03.643   930  2898 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-05 10:27:03.648   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268113 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-05 10:27:06.823  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 10:27:06.833  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 10:27:06.839  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 10:27:06.845  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 10:27:06.874   930  2899 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-05 10:27:06.875   930  2899 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-05 10:27:06.875   930  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 10:27:06.887   930  2899 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-05 10:27:06.924   930  2899 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-05 10:27:06.927  5752  5752 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-05 10:27:07.362  5752  5752 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-05 10:27:07.405  5752  5752 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-05 10:27:07.407  5752  5752 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-05 10:27:07.418   930  2899 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 10:27:07.418   930  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 10:27:07.418   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-05 10:27:07.435   930  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 10:27:07.445   507   911 D CommandListener: Setting iface cfg
,10-05 10:27:07.449   930  2899 D WifiStateMachine: Start Dhcp Watchdog 2
,10-05 10:27:07.457   930  5758 D DhcpClient: Receive thread started
,10-05 10:27:07.462   930  2899 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-05 10:27:07.462   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-05 10:27:07.462   930  2904 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-05 10:27:07.549   930  2899 E native  : do suspend false
,10-05 10:27:07.565   930  5757 D DhcpClient: Broadcasting DHCPDISCOVER
,10-05 10:27:07.591   930  5758 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,10-05 10:27:07.592   930  5757 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,10-05 10:27:07.594   930  5757 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-05 10:27:07.611   930  5758 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-05 10:27:07.612   930  5757 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-05 10:27:07.615   507   911 D CommandListener: Setting iface cfg
,10-05 10:27:07.622   930  2899 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-05 10:27:07.624   930  5757 D DhcpClient: Scheduling renewal in 86399s
,10-05 10:27:07.634   930  2899 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-05 10:27:07.636   930  2899 D WifiConfigStore: No blacklist allowed without epno enabled
,10-05 10:27:07.637   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-05 10:27:07.641   930  2904 D ConnectivityService: Adding iface wlan0 to network 101
10-05 10:27:07.650   930  2899 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-05 10:27:07.697   930  2904 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-05 10:27:07.697   930  2904 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
10-05 10:27:07.699   930  2904 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-05 10:27:07.700   930  2904 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-05 10:27:07.703   930  2904 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-05 10:27:07.711   930  2904 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-05 10:27:07.715   930  2904 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-05 10:27:07.715   930  2904 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-05 10:27:07.715   930  2904 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-05 10:27:07.715   930  2899 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-05 10:27:07.716   930  2904 D ConnectivityService:    accepting network in place of null
10-05 10:27:07.716   930  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-05 10:27:07.716   930  2904 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 10:27:07.731   930  5756 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272196, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-05 10:27:07.739   507   911 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 10:27:07.759   507   911 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 10:27:07.762   930  2904 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-05 10:27:07.762   930  2904 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 10:27:07.762  3667  3819 W QCNEJ   : |CORE| network available: 101
10-05 10:27:07.763   930  2904 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-05 10:27:07.764   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-05 10:27:07.767  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:27:07.767  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:07.767  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:07.767  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:07.767  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:07.767  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:07.767  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:07.767  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:07.767  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:27:07.767  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.767  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:07.771  3667  3819 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-05 10:27:07.774  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.774  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:07.774  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:07.774  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:07.774  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:07.774  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:07.774  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:07.774  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:07.774  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:27:07.774  3667  3819 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-05 10:27:07.774  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.774  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:07.775  3667  3819 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-05 10:27:07.776  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.776  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:07.776  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:07.776  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:07.776  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:07.776  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:07.776  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:07.776  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:07.776  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:27:07.776  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.776  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:07.779  3823  3823 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-05 10:27:07.780  4952  4976 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 10:27:07.781  4952  4976 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 10:27:07.781  4952  4976 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-05 10:27:07.781  4952  4976 E SarControlService: no key has been found,reset the power
10-05 10:27:07.781  4952  4989 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 10:27:07.781  4952  4989 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 10:27:07.781  4952  4989 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-05 10:27:07.782  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-05 10:27:07.782  4977  4977 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 10:27:07.784  4952  4989 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 10:27:07.784  4952  4989 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 10:27:07.784  4952  4989 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 10:27:07.786  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 10:27:07.786  3866  3866 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-05 10:27:07.788  4977  4977 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-05 10:27:07.790  3866  3866 D SystemUpdateService: onCreate
,10-05 10:27:07.794  4977  4991 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cee853f HexData = [00000000ec03000000000000ffffffff]
10-05 10:27:07.794  4977  4991 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 10:27:07.794  4977  4991 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-05 10:27:07.794  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 10:27:07.794  4952  4963 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 10:27:07.794  4977  4991 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cee853f HexData = [00000000ed03000000000000ffffffff]
10-05 10:27:07.794  4977  4991 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 10:27:07.795  4977  4991 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-05 10:27:07.795  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-05 10:27:07.795  4952  4962 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-05 10:27:07.797  3866  3866 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 10:27:07.802   930  5755 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-05 10:27:07.809  3866  3866 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-05 10:27:07.815  3866  5315 I iu.UploadsManager: num queued entries: 0
,10-05 10:27:07.816  3866  5315 I iu.UploadsManager: num updated entries: 0
,10-05 10:27:07.817  3866  5315 I iu.SyncManager: NEXT; no task
,10-05 10:27:07.819  3866  5768 I SystemUpdateService: active receiver: enabled
,10-05 10:27:07.821  3866  3866 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 10:27:07.823  3866  3866 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-05 10:27:07.824  5685  5685 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 10:27:07.828  5685  5685 D SprintDMHelper: simOperator: 
10-05 10:27:07.828  5685  5685 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 10:27:07.850   930  5755 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 05 Oct 2016 14:27:07 GMT], X-Android-Received-Millis=[1475677627849], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475677627828]}
,10-05 10:27:07.850  3866  5768 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 10:27:07.850   930  2904 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-05 10:27:07.850   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-05 10:27:07.851   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-05 10:27:07.852   930  2904 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-05 10:27:07.864  3866  5768 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-05 10:27:07.865  3866  5768 I SystemUpdateService: now status is 0 (complete)
10-05 10:27:07.865  3866  5768 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 10:27:07.865  3866  5768 I SystemUpdateService: file has been verified
10-05 10:27:07.865  3866  5768 I SystemUpdateService: OTA package size = 21989297
,10-05 10:27:07.871  3866  5768 I SystemUpdateService: showing system update notification
,10-05 10:27:07.880  3866  3866 D SystemUpdateService: onDestroy
,10-05 10:27:07.888   930   940 D WifiService: setWifiEnabled: false pid=5559, uid=10077
,10-05 10:27:07.888   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-05 10:27:07.890   930  2899 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-05 10:27:07.890   930  2899 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-05 10:27:07.890   930  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 10:27:07.890   930  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 10:27:07.899   930  5757 D DhcpClient: Clearing IP address
,10-05 10:27:07.899   507   911 D CommandListener: Clearing all IP addresses on wlan0
,10-05 10:27:07.901   507   911 D CommandListener: Setting iface cfg
,10-05 10:27:07.912   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-05 10:27:07.912   930   930 D RttService: SCAN_AVAILABLE : 1
10-05 10:27:07.913   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-05 10:27:07.913   930  3008 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-05 10:27:07.917   930  2904 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-05 10:27:07.917   534   534 E Parcel  : Reading a NULL string not supported here.
,10-05 10:27:07.919  3667  3819 W QCNEJ   : |CORE| network lost: 101
,10-05 10:27:07.919  4926  5772 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
10-05 10:27:07.919  3667  3819 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-05 10:27:07.926   930  2899 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-05 10:27:07.926   930  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-05 10:27:07.929   930  5758 D DhcpClient: Receive thread stopped
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: java.net.ConnectException: failed to connect to clients3.google.com/216.58.214.238 (port 80) after 5000ms: connect failed: ENETUNREACH (Network is unreachable)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:124)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.connect(Native Method)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
10-05 10:27:07.930  4926  5772 W Babel_NetworkCon,nectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
10-05 10:27:07.930  4926  5772 W Babel_NetworkConnectionCheckingService: 	... 21 more
10-05 10:27:07.930  4926  5772 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-05 10:27:07.945   507   911 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 10:27:07.965   507   911 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 10:27:07.966   507   911 D CommandListener: Clearing all IP addresses on wlan0
10-05 10:27:07.966   930  2904 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-05 10:27:07.966   930  2904 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-05 10:27:07.969   930  2899 D DhcpClient: doQuit
10-05 10:27:07.969   930  2899 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-05 10:27:07.970   930  5757 D DhcpClient: onQuitting
10-05 10:27:07.970   930   947 D Tethering: MasterInitialState.processMessage what=3
10-05 10:27:07.970  5752  5752 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-05 10:27:07.971  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.972  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:07.972  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:07.972  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:07.972  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:07.972  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:07.972  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:07.972  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:07.972  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:07.972  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.972  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:07.973  3823  3823 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-05 10:27:07.973  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.973  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:07.973  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:07.973  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:07.973  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:07.973  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:07.973  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:07.973  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:07.973  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 10:27:07.973  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:27:07.973  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:07.975  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.975  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:07.975  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:07.975  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:07.975  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:07.975  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:07.975  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:07.975  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:07.975  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:07.975  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:07.975  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 10:27:07.976  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:07.977  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:07.978  3866  3866 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-05 10:27:07.978  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:07.980  4952  4976 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 10:27:07.980  4952  4976 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 10:27:07.980  4952  4976 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-05 10:27:07.980  4952  4976 E SarControlService: no key has been found,reset the power
10-05 10:27:07.980  4952  4989 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 10:27:07.980  4952  4989 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 10:27:07.980  4952  4989 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 10:27:07.981  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 10:27:07.981  4977  4977 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-05 10:27:07.982  4952  4989 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-05 10:27:07.982  4952  4989 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 10:27:07.982  4952  4989 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 10:27:07.983  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 10:27:07.983  4977  4977 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 10:27:07.986  3866  3866 D SystemUpdateService: onCreate
10-05 10:27:07.987  4977  4991 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cee853f HexData = [00000000ee03000000000000ffffffff]
,10-05 10:27:07.987  4977  4991 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 10:27:07.988  4977  4991 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-05 10:27:07.988  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 10:27:07.989  4952  4962 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-05 10:27:07.991  4977  4991 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cee853f HexData = [00000000ef03000000000000ffffffff]
10-05 10:27:07.991  4977  4991 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-05 10:27:07.991  4977  4991 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-05 10:27:07.992  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 10:27:07.992  4952  4963 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-05 10:27:07.992  3866  3866 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 10:27:07.997  3866  5786 I SystemUpdateService: active receiver: enabled
,10-05 10:27:07.999  5752  5752 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-05 10:27:08.000  3866  3866 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-05 10:27:08.004  5752  5752 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-05 10:27:08.006  3866  5315 I iu.UploadsManager: num queued entries: 0
,10-05 10:27:08.007  3866  5315 I iu.UploadsManager: num updated entries: 0
10-05 10:27:08.008  3866  5315 I iu.SyncManager: NEXT; no task
,10-05 10:27:08.009  3866  3866 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 10:27:08.011  3866  3866 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-05 10:27:08.012  5685  5685 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 10:27:08.016  5685  5685 D SprintDMHelper: simOperator: 
10-05 10:27:08.016  5685  5685 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 10:27:08.020   507   911 E Netd    : netlink response contains error (No such file or directory)
,10-05 10:27:08.024  3866  5786 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 10:27:08.027  4926  5790 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-05 10:27:08.031  3866  5786 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-05 10:27:08.031  5752  5752 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-05 10:27:08.031  3866  5786 I SystemUpdateService: now status is 0 (complete)
10-05 10:27:08.031  3866  5786 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 10:27:08.031  3866  5786 I SystemUpdateService: file has been verified
10-05 10:27:08.032  3866  5786 I SystemUpdateService: OTA package size = 21989297
,10-05 10:27:08.042  5752  5752 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-05 10:27:08.047  3866  5786 I SystemUpdateService: showing system update notification
,10-05 10:27:08.055  3866  3866 D SystemUpdateService: onDestroy
,10-05 10:27:08.144   930  2899 D wifi    : In wifi stop Hal
,10-05 10:27:08.144   930  2899 D wifi    : halHandle = 0x7f76da3080, mVM = 0x7f933cd140, mCls = 0x1019f6
10-05 10:27:08.145  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 10:27:08.145   930  5751 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-05 10:27:08.146   930  5751 D WifiHAL : Got a signal to exit!!!
10-05 10:27:08.146   930  5751 I WifiHAL : Exit wifi_event_loop
,10-05 10:27:08.147  4064  4148 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 10:27:08.147   930  2899 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-05 10:27:08.147   930  2899 E WifiHAL : Event processing terminated
10-05 10:27:08.147   930  2899 D wifi    : In wifi cleaned up handler
10-05 10:27:08.147   930  2899 I WifiHAL : Internal cleanup completed
10-05 10:27:08.149  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:08.149  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:08.150  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:08.174   930  5751 D wifi    : set interface wlan0 flags (DOWN)
,10-05 10:27:08.175   930  2899 D WifiNative-HAL: HAL event thread stopped successfully
,10-05 10:27:08.378   930   947 D Tethering: InitialState.processMessage what=4
,10-05 10:27:08.382   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-05 10:27:08.764   930  2904 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-05 10:27:10.179   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:11.180   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:12.180   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:12.927   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25da321:true
,10-05 10:27:12.928  5670  5670 D BluetoothAdapterState: make() - Creating AdapterState
,10-05 10:27:12.934  5670  5670 I bt_bluedroid: init
,10-05 10:27:12.934  5670  5792 I BluetoothAdapterState: Entering OffState
,10-05 10:27:12.938  5670  5793 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-05 10:27:12.939  5670  5793 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-05 10:27:12.939  5670  5793 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-05 10:27:12.939  5670  5793 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-05 10:27:12.940  5670  5670 I bt_bluedroid: get_profile_interface socket
,10-05 10:27:12.944  5670  5670 I bt_bluedroid: get_profile_interface sdp
,10-05 10:27:12.944  5670  5796 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 10:27:12.949  5670  5796 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 10:27:12.953  5670  5681 I bt_bluedroid: config_hci_snoop_log
,10-05 10:27:12.955   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-05 10:27:12.962  5670  5792 D BluetoothAdapterState: Current state: OFF, message: 0
,10-05 10:27:12.962  5670  5792 D BluetoothAdapterProperties: Setting state to 14
10-05 10:27:12.963  5670  5792 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-05 10:27:12.965  5670  5792 D BluetoothBondStateMachine: make
,10-05 10:27:12.969  5670  5797 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-05 10:27:12.974  5670  5792 I BluetoothAdapterState: Entering PendingCommandState
,10-05 10:27:12.975  5670  5670 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-05 10:27:12.980  5670  5670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
,10-05 10:27:12.981  5670  5670 D BtGatt.DebugUtils: handleDebugAction() action=null
10-05 10:27:12.982  5670  5670 D BtGatt.GattService: Received start request. Starting profile...
,10-05 10:27:12.982  5670  5670 D BtGatt.GattService: start()
10-05 10:27:12.982  5670  5670 I bt_bluedroid: get_profile_interface gatt
,10-05 10:27:12.983  5670  5670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:12.984  5670  5670 D BtGatt.AdvertiseManager: advertise manager created
,10-05 10:27:12.995  5670  5670 V BluetoothAdapterState: isTurningOff()=false
,10-05 10:27:12.995  5670  5670 V BluetoothAdapterState: isTurningOn()=false
10-05 10:27:12.995  5670  5670 V BluetoothAdapterState: isBleTurningOn()=true
10-05 10:27:12.995  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:12.996  5670  5792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-05 10:27:12.998  5670  5792 I bt_bluedroid: bt_bluedroid
10-05 10:27:12.999  5670  5793 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-05 10:27:12.999  5670  5793 I bt_hci  : start_up
,10-05 10:27:13.009  5670  5793 I bt_vendor: alloc value 0xf3ded871
10-05 10:27:13.009  5670  5793 I bt_vendor: init
,10-05 10:27:13.009  5670  5793 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-05 10:27:13.009  5670  5793 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-05 10:27:13.125  5670  5793 D bt_hci  : start_up starting async portion
,10-05 10:27:13.126  5670  5800 I bt_hci  : event_finish_startup
,10-05 10:27:13.127  5670  5800 I bt_hci_h4: hal_open
10-05 10:27:13.127  5670  5800 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-05 10:27:13.131  5670  5800 I bt_userial_vendor: device fd = 54 open
,10-05 10:27:13.125  5801  5801 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 10:27:13.145  5670  5800 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 10:27:13.147  5670  5800 D bt_hwcfg: Chipset BCM4358A3
,10-05 10:27:13.148  5670  5800 D bt_hwcfg: Target name = [BCM4358A3]
10-05 10:27:13.148  5670  5800 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-05 10:27:13.183   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:13.530  5670  5800 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-05 10:27:13.530  5670  5800 D bt_hwcfg: Settlement delay -- 100 ms
10-05 10:27:13.531  5670  5800 I bt_hwcfg: Setting fw settlement delay to 100 
,10-05 10:27:13.664  5670  5800 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-05 10:27:13.665  5670  5800 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-05 10:27:13.666  5670  5800 I bt_hwcfg: vendor lib fwcfg completed
10-05 10:27:13.666  5670  5800 I bt_vendor: firmware callback
10-05 10:27:13.667  5670  5800 I bt_hci  : firmware_config_callback
,10-05 10:27:13.675  5670  5803 I bt_btu  : btu_task pending for preload complete event
,10-05 10:27:13.675  5670  5803 I bt_btu_task: Bluetooth chip preload is complete
10-05 10:27:13.675  5670  5803 I bt_btu  : btu_task received preload complete event
,10-05 10:27:13.683  5670  5803 I         : BTE_InitTraceLevels -- TRC_HCI
,10-05 10:27:13.683  5670  5803 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-05 10:27:13.684  5670  5803 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-05 10:27:13.684  5670  5803 I         : BTE_InitTraceLevels -- TRC_AVDT
10-05 10:27:13.684  5670  5803 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-05 10:27:13.684  5670  5803 I         : BTE_InitTraceLevels -- TRC_A2D
10-05 10:27:13.684  5670  5803 I         : BTE_InitTraceLevels -- TRC_BNEP
10-05 10:27:13.684  5670  5803 I         : BTE_InitTraceLevels -- TRC_BTM
10-05 10:27:13.684  5670  5803 I         : BTE_InitTraceLevels -- TRC_GAP
,10-05 10:27:13.685  5670  5803 I         : BTE_InitTraceLevels -- TRC_PAN
10-05 10:27:13.685  5670  5803 I         : BTE_InitTraceLevels -- TRC_SDP
,10-05 10:27:13.685  5670  5803 I         : BTE_InitTraceLevels -- TRC_GATT
10-05 10:27:13.685  5670  5803 I         : BTE_InitTraceLevels -- TRC_SMP
,10-05 10:27:13.685  5670  5803 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-05 10:27:13.685  5670  5803 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-05 10:27:13.769  5670  5803 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d6b549
10-05 10:27:13.769  5670  5803 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d6b549 
,10-05 10:27:13.786  5670  5796 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-05 10:27:13.787  5670  5796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-05 10:27:13.788  5670  5796 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 10:27:13.790  5670  5796 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 10:27:13.793  5670  5796 D BluetoothAdapterProperties: Scan Mode:20
10-05 10:27:13.793  5670  5796 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 10:27:13.794  5670  5796 D bt_hci  : do_postload posting postload work item
10-05 10:27:13.794  5670  5800 I bt_hci  : event_postload
10-05 10:27:13.794  5670  5800 I bt_vendor: sco_config_cb
,10-05 10:27:13.794  5670  5800 I bt_hci  : sco_config_callback postload finished.
,10-05 10:27:13.798  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:13.802  5670  5800 I bt_vendor: low_power_mode_cb
,10-05 10:27:13.802  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:13.803  5670  5796 D bt_bte_conf: Device ID record 1 : primary
10-05 10:27:13.804  5670  5796 D bt_bte_conf:   vendorId            = 000f
10-05 10:27:13.804  5670  5796 D bt_bte_conf:   vendorIdSource      = 0001
10-05 10:27:13.804  5670  5796 D bt_bte_conf:   product             = 1200
,10-05 10:27:13.804  5670  5796 D bt_bte_conf:   version             = 1436
10-05 10:27:13.804  5670  5796 D bt_bte_conf:   clientExecutableURL = 
,10-05 10:27:13.804  5670  5796 D bt_bte_conf:   serviceDescription  = 
10-05 10:27:13.804  5670  5796 D bt_bte_conf:   documentationURL    = 
10-05 10:27:13.804  5670  5796 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-05 10:27:13.804  5670  5793 D bt_stack_manager: event_start_up_stack finished
10-05 10:27:13.804  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:13.805  5670  5792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-05 10:27:13.805  5670  5792 D BluetoothAdapterProperties: Setting state to 15
10-05 10:27:13.805  5670  5792 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-05 10:27:13.806  5670  5792 I BluetoothAdapterState: Entering BleOnState
,10-05 10:27:13.810  5670  5792 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-05 10:27:13.810  5670  5792 D BluetoothAdapterProperties: Setting state to 11
10-05 10:27:13.810  5670  5792 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-05 10:27:13.815  5670  5670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:13.816  5670  5670 D HeadsetService: Received start request. Starting profile...
,10-05 10:27:13.818  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:13.819  5670  5670 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-05 10:27:13.819  5670  5670 D HeadsetStateMachine: make
10-05 10:27:13.820  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:13.822  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:13.833  5670  5792 I BluetoothAdapterState: Entering PendingCommandState
,10-05 10:27:13.834  5670  5670 D HeadsetStateMachine: max_hf_connections = 1
,10-05 10:27:13.834  5670  5670 I bt_bluedroid: get_profile_interface handsfree
10-05 10:27:13.835  5670  5796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-05 10:27:13.835  5670  5796 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-05 10:27:13.838  5670  5670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
,10-05 10:27:13.838  5670  5670 D A2dpService: Received start request. Starting profile...
,10-05 10:27:13.839  5670  5670 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-05 10:27:13.839  5670  5670 I bt_bluedroid: get_profile_interface avrcp
,10-05 10:27:13.844  5670  5670 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-05 10:27:13.845  5670  5670 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-05 10:27:13.845  5670  5670 D A2dpStateMachine: make
10-05 10:27:13.846  5670  5670 I bt_bluedroid: get_profile_interface a2dp
10-05 10:27:13.847  5670  5811 D A2dpStateMachine: Enter Disconnected: -2
10-05 10:27:13.848  5670  5670 I BluetoothHidServiceJni: classInitNative: succeeds
10-05 10:27:13.849  5670  5796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-05 10:27:13.849  5670  5670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:13.849  3509  3509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 10:27:13.850  5670  5670 D HidService: Received start request. Starting profile...
10-05 10:27:13.851  5670  5670 I bt_bluedroid: get_profile_interface hidhost
10-05 10:27:13.851  5670  5670 D HidService: setHidService(): set to: null
10-05 10:27:13.851  5670  5796 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d4c56d
10-05 10:27:13.851  5670  5796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-05 10:27:13.851  5670  5670 I BluetoothHealthServiceJni: classInitNative: succeeds
10-05 10:27:13.852  5670  5670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:13.852  5617  5617 D BluetoothInputDevice: Proxy object connected
10-05 10:27:13.853  5670  5670 D HealthService: Received start request. Starting profile...
10-05 10:27:13.853  5617  5617 D HidProfile: Bluetooth service connected
,10-05 10:27:13.854  5670  5670 I bt_bluedroid: get_profile_interface health
,10-05 10:27:13.855  5670  5670 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-05 10:27:13.856  5670  5670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
,10-05 10:27:13.857  5617  5617 D BluetoothPan: BluetoothPAN Proxy object connected
,10-05 10:27:13.857  5617  5617 D PanProfile: Bluetooth service connected
,10-05 10:27:13.858  5670  5670 D PanService: Received start request. Starting profile...
10-05 10:27:13.858  5670  5670 D BluetoothPanServiceJni: initializeNative(L110): pan
,10-05 10:27:13.858  5670  5670 I bt_bluedroid: get_profile_interface pan
10-05 10:27:13.859  5670  5796 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-05 10:27:13.860  5670  5670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:13.861  5617  5617 D BluetoothMap: Proxy object connected
10-05 10:27:13.862  5670  5670 D BluetoothMapService: Received start request. Starting profile...
10-05 10:27:13.862  5670  5670 D BluetoothMapService: start()
10-05 10:27:13.862  5617  5617 D MapProfile: Bluetooth service connected
10-05 10:27:13.862  5617  5617 D BluetoothMap: getConnectedDevices()
,10-05 10:27:13.863  5617  5617 D BluetoothMap: Bluetooth is Not enabled
,10-05 10:27:13.864  5670  5670 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-05 10:27:13.865  5670  5670 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-05 10:27:13.865  5670  5670 D BluetoothMapAppObserver: createReceiver()
10-05 10:27:13.867  5670  5670 D BluetoothMapAppObserver: initObservers()
10-05 10:27:13.867  5670  5670 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-05 10:27:13.873  5670  5670 V SapService: SapBinder()
,10-05 10:27:13.873  5670  5670 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:13.874  5670  5670 D SapService: Received start request. Starting profile...
,10-05 10:27:13.874  5670  5670 V SapService: start()
,10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isTurningOn()=true
,10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:13.876  5670  5809 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:13.876  5670  5670 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isTurningOn()=true
,10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:13.877  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:13.878  5670  5670 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:13.878  5670  5670 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:13.878  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:13.878  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:13.878  5670  5792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-05 10:27:13.878  5670  5792 D BluetoothAdapterProperties: ScanMode =  20
10-05 10:27:13.878  5670  5792 D BluetoothAdapterProperties: State =  11
,10-05 10:27:13.882  5670  5796 D BluetoothAdapterProperties: Scan Mode:21
10-05 10:27:13.882  5670  5792 D BluetoothAdapterProperties: Setting state to 12
,10-05 10:27:13.882  5670  5792 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-05 10:27:13.882  5670  5796 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 10:27:13.882  5559  5559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 10:27:13.882  5670  5792 I BluetoothAdapterState: Entering OnState
10-05 10:27:13.882  3055  3885 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 10:27:13.884  3055  3055 D BluetoothInputDevice: Proxy object connected
10-05 10:27:13.884  3055  3055 D HidProfile: Bluetooth service connected
10-05 10:27:13.884  5617  5629 D BluetoothMap: onBluetoothStateChange: up=true
10-05 10:27:13.884  3055  3066 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 10:27:13.886  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:13.886  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:13.886  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:13.886  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:13.886  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:13.886  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:13.886  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:13.886  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:13.886  3055  3067 D BluetoothPan: onBluetoothStateChange on: true
10-05 10:27:13.887  3055  3055 D BluetoothA2dp: Proxy object connected
,10-05 10:27:13.888  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 10:27:13.888  5617  5631 D BluetoothPan: onBluetoothStateChange on: true
10-05 10:27:13.889  5617  5629 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 10:27:13.889  5617  5631 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 10:27:13.889  3055  3055 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 10:27:13.889  3055  3055 D PanProfile: Bluetooth service connected
10-05 10:27:13.890  3055  3888 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:13.890   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:13.891  3055  3885 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 10:27:13.891  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:13.891  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:13.891  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:13.891  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:13.891  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:13.891  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:13.891  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:13.891  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:13.892  5670  5670 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-05 10:27:13.892  3702  3721 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:13.892  5670  5670 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-05 10:27:13.893   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:13.893   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 10:27:13.893   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:13.893  3055  3066 D BluetoothMap: onBluetoothStateChange: up=true
10-05 10:27:13.893   930   930 D BluetoothA2dp: Proxy object connected
10-05 10:27:13.893  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:13.895  5670  5670 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 10:27:13.895  3055  3055 D BluetoothMap: Proxy object connected
10-05 10:27:13.895  3055  3055 D MapProfile: Bluetooth service connected
10-05 10:27:13.895  3055  3055 D BluetoothMap: getConnectedDevices()
,10-05 10:27:13.900  5670  5670 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 10:27:13.901  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:13.901  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:13.901  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:13.901  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:13.901  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:13.901  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:13.901  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:13.901  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:13.901   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-05 10:27:13.902  5670  5670 D ObexServerSockets: Succeed to create listening sockets 
10-05 10:27:13.902  5670  5670 D ObexServerSockets0: startAccept()
10-05 10:27:13.902  5670  5670 D ObexServerSockets0: prepareForNewConnect()
,10-05 10:27:13.902  5617  5617 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-05 10:27:13.904  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:13.904  5559  5559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 10:27:13.904  5670  5670 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-05 10:27:13.905  5670  5670 D BluetoothSdpJni: SDP Create record success - handle: 0
10-05 10:27:13.905  5670  5821 D ObexServerSockets0: Accepting socket connection...
10-05 10:27:13.905  5670  5670 D BluetoothMapService: onReceive
10-05 10:27:13.905  5670  5670 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 10:27:13.905  5670  5670 D BluetoothMapService: STATE_ON
10-05 10:27:13.905  5670  5822 D ObexServerSockets0: Accepting socket connection...
10-05 10:27:13.905  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:13.907  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:13.907  5617  5617 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-05 10:27:13.908  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:13.909  5670  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 10:27:13.911  5670  5823 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-05 10:27:13.911  5670  5823 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-05 10:27:13.917  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 10:27:13.920  5617  5617 D BluetoothA2dp: Proxy object connected
,10-05 10:27:13.924  3509  3509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 10:27:13.927  5617  5617 D DockEventReceiver: finishStartingService: stopping service
,10-05 10:27:13.932  5670  5670 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-05 10:27:13.932  5670  5670 D ObexServerSockets0: prepareForNewConnect()
,10-05 10:27:13.934  3055  3055 D BluetoothPbap: Proxy object connected
10-05 10:27:13.934  3055  3055 D PbapServerProfile: Bluetooth service connected
,10-05 10:27:13.935  5617  5617 D BluetoothPbap: Proxy object connected
10-05 10:27:13.935  5617  5617 D PbapServerProfile: Bluetooth service connected
,10-05 10:27:13.939  5670  5827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 10:27:13.953  5670  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 10:27:13.955  5670  5831 I BtOppRfcommListener: Accept thread started.
,10-05 10:27:13.991  3055  3888 D BluetoothHeadset: Proxy object connected
10-05 10:27:13.991   930   947 D BluetoothHeadset: Proxy object connected
,10-05 10:27:13.992  3055  3055 D HeadsetProfile: Bluetooth service connected
10-05 10:27:13.992   930   930 D BluetoothHeadset: Proxy object connected
10-05 10:27:13.992   930   930 D BluetoothHeadset: Proxy object connected
10-05 10:27:13.992   930   930 D BluetoothHeadset: Proxy object connected
10-05 10:27:13.992  3702  3723 D BluetoothHeadset: Proxy object connected
,10-05 10:27:13.993  3702  4049 D BluetoothHeadset: Proxy object connected
10-05 10:27:13.993   930   947 D BluetoothHeadset: Proxy object connected
10-05 10:27:13.993   930   947 D BluetoothHeadset: Proxy object connected
,10-05 10:27:14.012  5617  5629 D BluetoothHeadset: Proxy object connected
,10-05 10:27:14.013  5617  5617 D HeadsetProfile: Bluetooth service connected
,10-05 10:27:14.183   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:15.184   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-05 10:27:15.723   930  2904 D ConnectivityService: handlePromptUnvalidated 101
,10-05 10:27:17.906  5670  5792 D BluetoothAdapterState: Current state: ON, message: 23
,10-05 10:27:17.906  5670  5792 D BluetoothAdapterProperties: Setting state to 13
,10-05 10:27:17.907  5670  5792 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-05 10:27:17.908  5670  5792 D BluetoothAdapterProperties: onBluetoothDisable()
,10-05 10:27:17.910  5670  5792 I BluetoothAdapterState: Entering PendingCommandState
,10-05 10:27:17.915  5670  5670 D BluetoothMapService: onReceive
,10-05 10:27:17.916  5670  5670 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-05 10:27:17.916  5670  5670 D BluetoothMapService: STATE_TURNING_OFF
10-05 10:27:17.916  5670  5670 D BluetoothMapService: MAP Service closeService in
10-05 10:27:17.916  5670  5670 D BluetoothMapMasInstance0: MAP Service shutdown
10-05 10:27:17.916  5670  5670 D ObexServerSockets0: shutdown(block = true)
10-05 10:27:17.917  5670  5670 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 10:27:17.918  5670  5821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-05 10:27:17.918  5670  5805 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-05 10:27:17.919  5670  5822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-05 10:27:17.919  5670  5670 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 10:27:17.919  5670  5796 D BluetoothAdapterProperties: Scan Mode:20
,10-05 10:27:17.920  5670  5792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-05 10:27:17.924  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 10:27:17.928  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:27:17.928  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:17.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:17.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:17.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:17.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:17.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:17.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:17.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:17.931  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:17.931  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:17.931  5670  5670 I BtOppRfcommListener: stopping Accept Thread
10-05 10:27:17.931  5670  5831 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-05 10:27:17.932  5670  5831 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-05 10:27:17.933  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:17.933  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:17.933  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:17.933  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:17.933  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:17.933  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:17.933  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:17.933  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:17.933  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 10:27:17.934  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:17.935  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 10:27:17.939  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 10:27:17.939  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:17.939  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:17.939  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:17.939  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:17.939  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 10:27:17.939  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:17.939  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:17.939  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:17.940  5670  5670 D HeadsetService: Received stop request...Stopping profile...
10-05 10:27:17.940  5559  5559 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 10:27:17.940  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:17.942  5617  5631 D BluetoothHeadset: Proxy object disconnected
10-05 10:27:17.942  3055  3885 D BluetoothHeadset: Proxy object disconnected
10-05 10:27:17.942  3055  3055 D HeadsetProfile: Bluetooth service disconnected
10-05 10:27:17.942   930   930 D BluetoothHeadset: Proxy object disconnected
,10-05 10:27:17.942   930   930 D BluetoothHeadset: Proxy object disconnected
10-05 10:27:17.942   930   930 D BluetoothHeadset: Proxy object disconnected
10-05 10:27:17.943  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:17.943  3702  3951 D BluetoothHeadset: Proxy object disconnected
10-05 10:27:17.943  5617  5617 D DockEventReceiver: finishStartingService: stopping service
10-05 10:27:17.945  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:17.945  5670  5670 D A2dpService: Received stop request...Stopping profile...
,10-05 10:27:17.945  5670  5811 D A2dpStateMachine: Exit Disconnected: -1
10-05 10:27:17.945  5617  5617 D HeadsetProfile: Bluetooth service disconnected
10-05 10:27:17.946  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:17.948  3055  3055 D BluetoothA2dp: Proxy object disconnected
10-05 10:27:17.948   930   930 D BluetoothA2dp: Proxy object disconnected
,10-05 10:27:17.949  5670  5670 D HidService: Received stop request...Stopping profile...
,10-05 10:27:17.949  5670  5670 D HidService: Stopping Bluetooth HidService
10-05 10:27:17.950  3055  3055 D BluetoothInputDevice: Proxy object disconnected
10-05 10:27:17.950  3055  3055 D HidProfile: Bluetooth service disconnected
,10-05 10:27:17.952  5617  5617 D BluetoothA2dp: Proxy object disconnected
,10-05 10:27:17.952  5617  5617 D BluetoothInputDevice: Proxy object disconnected
10-05 10:27:17.952  5617  5617 D HidProfile: Bluetooth service disconnected
,10-05 10:27:17.953  5670  5670 D HealthService: Received stop request...Stopping profile...
,10-05 10:27:17.955  5670  5670 D PanService: Received stop request...Stopping profile...
10-05 10:27:17.955  3055  3055 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 10:27:17.956  3055  3055 D PanProfile: Bluetooth service disconnected
10-05 10:27:17.957  5670  5670 D BluetoothMapService: Received stop request...Stopping profile...
10-05 10:27:17.957  5670  5670 D BluetoothMapService: stop()
,10-05 10:27:17.958  5617  5617 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-05 10:27:17.958  5617  5617 D PanProfile: Bluetooth service disconnected
10-05 10:27:17.959  3509  3509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 10:27:17.959  5670  5670 D BluetoothMapAppObserver: deinitObservers()
10-05 10:27:17.959  5670  5670 D BluetoothMapAppObserver: removeReceiver()
,10-05 10:27:17.962  5617  5617 D BluetoothMap: Proxy object disconnected
,10-05 10:27:17.962  5617  5617 D MapProfile: Bluetooth service disconnected
10-05 10:27:17.962  3055  3055 D BluetoothMap: Proxy object disconnected
10-05 10:27:17.962  3055  3055 D MapProfile: Bluetooth service disconnected
10-05 10:27:17.962  5670  5670 D SapService: Received stop request...Stopping profile...
10-05 10:27:17.962  5670  5670 V SapService: stop()
,10-05 10:27:17.964  5670  5670 V BluetoothAdapterState: isTurningOff()=true
10-05 10:27:17.964  5670  5670 V BluetoothAdapterState: isTurningOn()=false
10-05 10:27:17.964  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:17.964  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 10:27:17.965  5670  5670 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-05 10:27:17.965  5670  5670 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-05 10:27:17.966  5670  5803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:27:17.966  5670  5803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:27:17.966  5670  5670 V BluetoothAdapterState: isTurningOff()=true
10-05 10:27:17.966  5670  5803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:27:17.966  5670  5670 V BluetoothAdapterState: isTurningOn()=false
10-05 10:27:17.966  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:17.966  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:17.966  5670  5796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-05 10:27:17.966  5670  5796 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-05 10:27:17.967  5670  5803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-05 10:27:17.967  5670  5803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:27:17.967  5670  5670 V BluetoothAdapterState: isTurningOff()=true
10-05 10:27:17.967  5670  5670 V BluetoothAdapterState: isTurningOn()=false
10-05 10:27:17.967  5670  5796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-05 10:27:17.967  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 10:27:17.967  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:17.967  5670  5803 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 10:27:17.967  5670  5803 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 10:27:17.967  5670  5803 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 10:27:17.967  5670  5803 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 10:27:17.967  5670  5670 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-05 10:27:17.967  5670  5670 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-05 10:27:17.967  5670  5796 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 10:27:17.968  5670  5670 V BluetoothAdapterState: isTurningOff()=true
10-05 10:27:17.968  5670  5670 V BluetoothAdapterState: isTurningOn()=false
10-05 10:27:17.968  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:17.968  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:17.968  5670  5670 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-05 10:27:17.968  5670  5796 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-05 10:27:17.969  5670  5670 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-05 10:27:17.969  5670  5670 V BluetoothAdapterState: isTurningOff()=true
10-05 10:27:17.969  5670  5670 V BluetoothAdapterState: isTurningOn()=false
10-05 10:27:17.969  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:17.969  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:17.969  5670  5670 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-05 10:27:17.969  5670  5670 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-05 10:27:17.972  3055  3055 D BluetoothPbap: Proxy object disconnected
10-05 10:27:17.972  3055  3055 D PbapServerProfile: Bluetooth service disconnected
10-05 10:27:17.972  5617  5617 D BluetoothPbap: Proxy object disconnected
10-05 10:27:17.972  5617  5617 D PbapServerProfile: Bluetooth service disconnected
,10-05 10:27:17.974  5670  5670 D BluetoothMapService: MAP Service closeService in
10-05 10:27:17.974  5670  5670 V BluetoothAdapterState: isTurningOff()=true
10-05 10:27:17.975  5670  5670 V BluetoothAdapterState: isTurningOn()=false
10-05 10:27:17.975  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:17.975  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 10:27:17.975  5670  5670 D BluetoothMapService: cleanup()
10-05 10:27:17.975  5670  5670 D BluetoothMapService: MAP Service closeService in
10-05 10:27:17.975  5670  5670 V BluetoothAdapterState: isTurningOff()=true
10-05 10:27:17.975  5670  5670 V BluetoothAdapterState: isTurningOn()=false
10-05 10:27:17.975  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:17.975  5670  5670 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:17.976  5670  5792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-05 10:27:17.976  5670  5792 D BluetoothAdapterProperties: Setting state to 15
10-05 10:27:17.976  5670  5792 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-05 10:27:17.976  3055  3885 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-05 10:27:17.977  5670  5792 I BluetoothAdapterState: Entering BleOnState
,10-05 10:27:17.977  5617  5631 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 10:27:17.977  5617  5629 D BluetoothMap: onBluetoothStateChange: up=false
10-05 10:27:17.978  3055  3067 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-05 10:27:17.979  3055  3066 D BluetoothPan: onBluetoothStateChange on: false
10-05 10:27:17.979  5617  5631 D BluetoothPan: onBluetoothStateChange on: false
10-05 10:27:17.980  5617  5629 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-05 10:27:17.980  5617  5631 D BluetoothPbap: onBluetoothStateChange: up=false
10-05 10:27:17.981  3055  3888 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 10:27:17.981   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 10:27:17.981  3055  3885 D BluetoothPbap: onBluetoothStateChange: up=false
10-05 10:27:17.982  3702  3721 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 10:27:17.982   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 10:27:17.982   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 10:27:17.982   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-05 10:27:17.982  3055  3067 D BluetoothMap: onBluetoothStateChange: up=false
10-05 10:27:17.983  5617  5629 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 10:27:17.983  5670  5792 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-05 10:27:17.983  5670  5792 D BluetoothAdapterProperties: Setting state to 16
10-05 10:27:17.983  5670  5792 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-05 10:27:17.984  5670  5792 D BluetoothAdapterProperties: onBleDisable
10-05 10:27:17.984  5670  5792 I BluetoothAdapterState: Entering PendingCommandState
10-05 10:27:17.985  5670  5793 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-05 10:27:17.985  5670  5796 D BluetoothAdapterProperties: Scan Mode:20
10-05 10:27:17.986  5670  5803 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-05 10:27:17.986  5670  5803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 10:27:17.986  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:17.988  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:17.990  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:17.991  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:17.993  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:17.995  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:17.997  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 10:27:18.001  3509  3509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 10:27:18.003  5617  5617 D DockEventReceiver: finishStartingService: stopping service
,10-05 10:27:18.199  5670  5796 I bt_hci  : shut_down
,10-05 10:27:18.209  5670  5800 D bt_hwcfg: hw_epilog_process
,10-05 10:27:18.209  5670  5800 I bt_vendor: low_power_mode_cb
,10-05 10:27:18.212  5670  5800 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-05 10:27:18.212  5670  5800 I bt_vendor: epilog_cb
10-05 10:27:18.212  5670  5800 I bt_hci  : epilog_finished_callback
,10-05 10:27:18.215  5670  5796 I bt_hci_h4: hal_close
,10-05 10:27:18.216  5670  5796 I bt_userial_vendor: device fd = 54 close
,10-05 10:27:18.322  5670  5793 D bt_stack_manager: event_shut_down_stack finished.
,10-05 10:27:18.322  5670  5792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-05 10:27:18.327  5670  5792 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-05 10:27:18.327  5670  5670 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-05 10:27:18.329  5670  5670 D BtGatt.GattService: Received stop request...Stopping profile...
,10-05 10:27:18.329  5670  5670 D BtGatt.GattService: stop()
,10-05 10:27:18.330  5670  5670 D BtGatt.AdvertiseManager: advertise clients cleared
10-05 10:27:18.333  5670  5670 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:18.333  5670  5670 V BluetoothAdapterState: isTurningOn()=false
,10-05 10:27:18.333  5670  5670 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:18.333  5670  5670 V BluetoothAdapterState: isBleTurningOff()=true
10-05 10:27:18.334  5670  5792 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-05 10:27:18.334  5670  5792 D BluetoothAdapterProperties: Setting state to 10
,10-05 10:27:18.334  5670  5792 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-05 10:27:18.335  5670  5792 I BluetoothAdapterState: Entering OffState
10-05 10:27:18.336   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-05 10:27:18.354  5670  5670 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-05 10:27:18.354  5670  5670 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-05 10:27:18.354  5670  5670 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-05 10:27:18.357  5670  5793 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-05 10:27:18.365  5670  5670 I art     : System.exit called, status: 0
,10-05 10:27:18.366  5670  5670 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-05 10:27:18.395   930  3339 I ActivityManager: Process com.android.bluetooth (pid 5670) has died
,10-05 10:27:22.904  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 10:27:22.904  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:22.908  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:27:22.909  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f82316e removed from the list
10-05 10:27:22.909  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 10:27:22.909  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:22.909  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:22.912  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 10:27:22.912  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59a889c added. We now have 4 listener(s)
10-05 10:27:22.912  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 10:27:22.914  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:22.914  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59a889c removed from the list
10-05 10:27:22.914  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:27:22.914  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:22.915  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:22.917  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:22.917  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d13e2a5 added. We now have 4 listener(s)
10-05 10:27:22.917  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 10:27:27.928  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:27.966   930   947 I ActivityManager: Start proc 5839:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-05 10:27:28.048  5839  5839 D AdapterServiceConfig: Adding HeadsetService
,10-05 10:27:28.049  5839  5839 D AdapterServiceConfig: Adding A2dpService
10-05 10:27:28.049  5839  5839 D AdapterServiceConfig: Adding HidService
10-05 10:27:28.049  5839  5839 D AdapterServiceConfig: Adding HealthService
10-05 10:27:28.049  5839  5839 D AdapterServiceConfig: Adding PanService
10-05 10:27:28.049  5839  5839 D AdapterServiceConfig: Adding GattService
10-05 10:27:28.049  5839  5839 D AdapterServiceConfig: Adding BluetoothMapService
10-05 10:27:28.050  5839  5839 D AdapterServiceConfig: Adding SapService
,10-05 10:27:28.060   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4d61606:true
,10-05 10:27:28.060  5839  5839 D BluetoothAdapterState: make() - Creating AdapterState
,10-05 10:27:28.073  5839  5839 I bt_bluedroid: init
10-05 10:27:28.074  5839  5851 I BluetoothAdapterState: Entering OffState
,10-05 10:27:28.076  5839  5852 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-05 10:27:28.076  5839  5852 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-05 10:27:28.076  5839  5852 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-05 10:27:28.076  5839  5852 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-05 10:27:28.077  5839  5839 I bt_bluedroid: get_profile_interface socket
,10-05 10:27:28.079  5839  5855 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 10:27:28.080  5839  5839 I bt_bluedroid: get_profile_interface sdp
10-05 10:27:28.080  5839  5855 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 10:27:28.088  5839  5850 I bt_bluedroid: config_hci_snoop_log
10-05 10:27:28.089   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-05 10:27:28.092  5839  5851 D BluetoothAdapterState: Current state: OFF, message: 0
10-05 10:27:28.093  5839  5851 D BluetoothAdapterProperties: Setting state to 14
10-05 10:27:28.093  5839  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-05 10:27:28.095  5839  5851 D BluetoothBondStateMachine: make
,10-05 10:27:28.097  5839  5856 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-05 10:27:28.100  5839  5851 I BluetoothAdapterState: Entering PendingCommandState
,10-05 10:27:28.101  5839  5839 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
10-05 10:27:28.103  5839  5839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:28.104  5839  5839 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-05 10:27:28.104  5839  5839 D BtGatt.GattService: Received start request. Starting profile...
10-05 10:27:28.104  5839  5839 D BtGatt.GattService: start()
10-05 10:27:28.104  5839  5839 I bt_bluedroid: get_profile_interface gatt
,10-05 10:27:28.105  5839  5839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:28.105  5839  5839 D BtGatt.AdvertiseManager: advertise manager created
,10-05 10:27:28.111  5839  5839 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:28.111  5839  5839 V BluetoothAdapterState: isTurningOn()=false
10-05 10:27:28.111  5839  5839 V BluetoothAdapterState: isBleTurningOn()=true
,10-05 10:27:28.111  5839  5839 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:28.111  5839  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-05 10:27:28.113  5839  5851 I bt_bluedroid: bt_bluedroid
10-05 10:27:28.113  5839  5852 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-05 10:27:28.113  5839  5852 I bt_hci  : start_up
,10-05 10:27:28.119  5839  5852 I bt_vendor: alloc value 0xf3df9871
,10-05 10:27:28.119  5839  5852 I bt_vendor: init
10-05 10:27:28.119  5839  5852 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-05 10:27:28.119  5839  5852 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-05 10:27:28.229  5839  5852 D bt_hci  : start_up starting async portion
10-05 10:27:28.229  5839  5859 I bt_hci  : event_finish_startup
,10-05 10:27:28.230  5839  5859 I bt_hci_h4: hal_open
10-05 10:27:28.230  5839  5859 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-05 10:27:28.232  5839  5859 I bt_userial_vendor: device fd = 54 open
,10-05 10:27:28.229  5860  5860 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 10:27:28.248  5839  5859 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 10:27:28.252  5839  5859 D bt_hwcfg: Chipset BCM4358A3
10-05 10:27:28.252  5839  5859 D bt_hwcfg: Target name = [BCM4358A3]
,10-05 10:27:28.253  5839  5859 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-05 10:27:28.757  5839  5859 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-05 10:27:28.758  5839  5859 D bt_hwcfg: Settlement delay -- 100 ms
,10-05 10:27:28.758  5839  5859 I bt_hwcfg: Setting fw settlement delay to 100 
,10-05 10:27:28.894  5839  5859 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 10:27:28.894  5839  5859 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-05 10:27:28.896  5839  5859 I bt_hwcfg: vendor lib fwcfg completed
10-05 10:27:28.896  5839  5859 I bt_vendor: firmware callback
10-05 10:27:28.896  5839  5859 I bt_hci  : firmware_config_callback
,10-05 10:27:28.908  5839  5862 I bt_btu  : btu_task pending for preload complete event
,10-05 10:27:28.909  5839  5862 I bt_btu_task: Bluetooth chip preload is complete
10-05 10:27:28.909  5839  5862 I bt_btu  : btu_task received preload complete event
,10-05 10:27:28.917  5839  5862 I         : BTE_InitTraceLevels -- TRC_HCI
,10-05 10:27:28.917  5839  5862 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-05 10:27:28.917  5839  5862 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-05 10:27:28.917  5839  5862 I         : BTE_InitTraceLevels -- TRC_AVDT
10-05 10:27:28.917  5839  5862 I         : BTE_InitTraceLevels -- TRC_AVRC
10-05 10:27:28.917  5839  5862 I         : BTE_InitTraceLevels -- TRC_A2D
10-05 10:27:28.917  5839  5862 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-05 10:27:28.918  5839  5862 I         : BTE_InitTraceLevels -- TRC_BTM
10-05 10:27:28.918  5839  5862 I         : BTE_InitTraceLevels -- TRC_GAP
10-05 10:27:28.918  5839  5862 I         : BTE_InitTraceLevels -- TRC_PAN
10-05 10:27:28.918  5839  5862 I         : BTE_InitTraceLevels -- TRC_SDP
,10-05 10:27:28.918  5839  5862 I         : BTE_InitTraceLevels -- TRC_GATT
10-05 10:27:28.918  5839  5862 I         : BTE_InitTraceLevels -- TRC_SMP
10-05 10:27:28.918  5839  5862 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-05 10:27:28.918  5839  5862 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-05 10:27:29.015  5839  5862 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d77549
,10-05 10:27:29.015  5839  5862 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d77549 
,10-05 10:27:29.034  5839  5855 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-05 10:27:29.036  5839  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-05 10:27:29.036  5839  5855 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 10:27:29.040  5839  5855 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 10:27:29.043  5839  5855 D BluetoothAdapterProperties: Scan Mode:20
10-05 10:27:29.043  5839  5855 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-05 10:27:29.043  5839  5855 D bt_hci  : do_postload posting postload work item
10-05 10:27:29.043  5839  5859 I bt_hci  : event_postload
10-05 10:27:29.043  5839  5859 I bt_vendor: sco_config_cb
10-05 10:27:29.043  5839  5859 I bt_hci  : sco_config_callback postload finished.
,10-05 10:27:29.048  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:29.052  5839  5859 I bt_vendor: low_power_mode_cb
,10-05 10:27:29.053  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:29.054  5839  5855 D bt_bte_conf: Device ID record 1 : primary
10-05 10:27:29.054  5839  5855 D bt_bte_conf:   vendorId            = 000f
10-05 10:27:29.054  5839  5855 D bt_bte_conf:   vendorIdSource      = 0001
10-05 10:27:29.054  5839  5855 D bt_bte_conf:   product             = 1200
,10-05 10:27:29.054  5839  5855 D bt_bte_conf:   version             = 1436
10-05 10:27:29.054  5839  5855 D bt_bte_conf:   clientExecutableURL = 
10-05 10:27:29.054  5839  5855 D bt_bte_conf:   serviceDescription  = 
10-05 10:27:29.054  5839  5855 D bt_bte_conf:   documentationURL    = 
10-05 10:27:29.054  5839  5855 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-05 10:27:29.054  5839  5852 D bt_stack_manager: event_start_up_stack finished
,10-05 10:27:29.055  5839  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-05 10:27:29.055  5839  5851 D BluetoothAdapterProperties: Setting state to 15
10-05 10:27:29.055  5839  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-05 10:27:29.056  5839  5851 I BluetoothAdapterState: Entering BleOnState
,10-05 10:27:29.059  5839  5851 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-05 10:27:29.059  5839  5851 D BluetoothAdapterProperties: Setting state to 11
,10-05 10:27:29.059  5839  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-05 10:27:29.066  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:29.067  5839  5839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
,10-05 10:27:29.068  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:29.068  5839  5839 D HeadsetService: Received start request. Starting profile...
10-05 10:27:29.070  5839  5839 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-05 10:27:29.070  5839  5839 D HeadsetStateMachine: make
,10-05 10:27:29.080  5839  5839 D HeadsetStateMachine: max_hf_connections = 1
,10-05 10:27:29.080  5839  5839 I bt_bluedroid: get_profile_interface handsfree
10-05 10:27:29.080  5839  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-05 10:27:29.081  5839  5855 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-05 10:27:29.084  5839  5851 I BluetoothAdapterState: Entering PendingCommandState
,10-05 10:27:29.084  5839  5839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:29.085  5839  5839 D A2dpService: Received start request. Starting profile...
10-05 10:27:29.086  5839  5839 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-05 10:27:29.086  5839  5839 I bt_bluedroid: get_profile_interface avrcp
,10-05 10:27:29.091  5839  5839 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-05 10:27:29.092  5839  5839 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-05 10:27:29.092  5839  5839 D A2dpStateMachine: make
,10-05 10:27:29.093  5839  5839 I bt_bluedroid: get_profile_interface a2dp
,10-05 10:27:29.093  5839  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-05 10:27:29.094  5839  5870 D A2dpStateMachine: Enter Disconnected: -2
10-05 10:27:29.096  5839  5839 I BluetoothHidServiceJni: classInitNative: succeeds
10-05 10:27:29.096  5839  5839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:29.098  5839  5839 D HidService: Received start request. Starting profile...
10-05 10:27:29.098  5839  5839 I bt_bluedroid: get_profile_interface hidhost
10-05 10:27:29.099  5839  5839 D HidService: setHidService(): set to: null
10-05 10:27:29.099  5839  5855 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d5856d
10-05 10:27:29.099  5839  5855 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-05 10:27:29.100  3509  3509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 10:27:29.100  5839  5839 I BluetoothHealthServiceJni: classInitNative: succeeds
10-05 10:27:29.101  5839  5839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
10-05 10:27:29.101  5839  5839 D HealthService: Received start request. Starting profile...
,10-05 10:27:29.103  5839  5839 I bt_bluedroid: get_profile_interface health
10-05 10:27:29.104  5839  5839 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-05 10:27:29.104  5839  5839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
,10-05 10:27:29.105  5839  5839 D PanService: Received start request. Starting profile...
,10-05 10:27:29.106  5839  5839 D BluetoothPanServiceJni: initializeNative(L110): pan
10-05 10:27:29.106  5839  5839 I bt_bluedroid: get_profile_interface pan
10-05 10:27:29.106  5839  5855 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-05 10:27:29.108  5839  5839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
,10-05 10:27:29.109  5839  5839 D BluetoothMapService: Received start request. Starting profile...
10-05 10:27:29.109  5839  5839 D BluetoothMapService: start()
,10-05 10:27:29.112  5839  5839 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-05 10:27:29.113  5839  5839 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-05 10:27:29.113  5839  5839 D BluetoothMapAppObserver: createReceiver()
,10-05 10:27:29.114  5839  5839 D BluetoothMapAppObserver: initObservers()
,10-05 10:27:29.114  5839  5839 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-05 10:27:29.120  5839  5839 V BluetoothAdapterState: isTurningOff()=false
,10-05 10:27:29.120  5839  5839 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:29.120  5839  5839 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:29.120  5839  5839 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:29.121  5839  5868 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,10-05 10:27:29.122  5839  5839 V SapService: SapBinder()
10-05 10:27:29.122  5839  5839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
,10-05 10:27:29.123  5839  5839 D SapService: Received start request. Starting profile...
10-05 10:27:29.123  5839  5839 V SapService: start()
,10-05 10:27:29.124  5839  5839 V BluetoothAdapterState: isTurningOff()=false
,10-05 10:27:29.124  5839  5839 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:29.124  5839  5839 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:29.124  5839  5839 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:29.124  5839  5839 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:29.125  5839  5839 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:29.125  5839  5839 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:29.125  5839  5839 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:29.125  5839  5839 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:29.125  5839  5839 V BluetoothAdapterState: isTurningOn()=true
,10-05 10:27:29.125  5839  5839 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 10:27:29.126  5839  5839 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 10:27:29.126  5839  5839 V BluetoothAdapterState: isTurningOff()=false
,10-05 10:27:29.126  5839  5839 V BluetoothAdapterState: isTurningOn()=true
,10-05 10:27:29.126  5839  5839 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:29.126  5839  5839 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:29.126  5839  5839 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:29.126  5839  5839 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:29.126  5839  5839 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:29.126  5839  5839 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:29.127  5839  5839 V BluetoothAdapterState: isTurningOff()=false
10-05 10:27:29.127  5839  5839 V BluetoothAdapterState: isTurningOn()=true
10-05 10:27:29.127  5839  5839 V BluetoothAdapterState: isBleTurningOn()=false
10-05 10:27:29.127  5839  5839 V BluetoothAdapterState: isBleTurningOff()=false
10-05 10:27:29.128  5839  5851 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-05 10:27:29.128  5839  5851 D BluetoothAdapterProperties: ScanMode =  20
10-05 10:27:29.128  5839  5851 D BluetoothAdapterProperties: State =  11
10-05 10:27:29.128  5839  5851 D BluetoothAdapterProperties: Setting state to 12
10-05 10:27:29.128  5839  5851 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-05 10:27:29.129  3055  3888 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 10:27:29.129  5839  5855 D BluetoothAdapterProperties: Scan Mode:21
10-05 10:27:29.129  5839  5855 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 10:27:29.130  5559  5559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 10:27:29.130  5839  5851 I BluetoothAdapterState: Entering OnState
10-05 10:27:29.132  3055  3055 D BluetoothInputDevice: Proxy object connected
10-05 10:27:29.132  3055  3055 D HidProfile: Bluetooth service connected
10-05 10:27:29.132  5617  5631 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:29.133  5617  5629 D BluetoothMap: onBluetoothStateChange: up=true
10-05 10:27:29.134  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:29.134  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:29.134  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:29.134  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:29.134  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:29.134  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:29.134  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:29.134  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 10:27:29.135  3055  3885 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-05 10:27:29.137  3055  3066 D BluetoothPan: onBluetoothStateChange on: true
10-05 10:27:29.137  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:29.138  5617  5629 D BluetoothPan: onBluetoothStateChange on: true
10-05 10:27:29.140  3055  3055 D BluetoothA2dp: Proxy object connected
10-05 10:27:29.140  5617  5629 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 10:27:29.140  5839  5839 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-05 10:27:29.141  5839  5839 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-05 10:27:29.142  3055  3055 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 10:27:29.142  5617  5617 D BluetoothMap: Proxy object connected
10-05 10:27:29.142  3055  3055 D PanProfile: Bluetooth service connected
,10-05 10:27:29.142  5617  5617 D MapProfile: Bluetooth service connected
10-05 10:27:29.142  5617  5617 D BluetoothMap: getConnectedDevices()
10-05 10:27:29.143  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:29.143  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:29.143  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:29.143  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:29.143  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:29.143  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:29.143  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:29.143  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 10:27:29.143  5839  5839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 10:27:29.143  5617  5631 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 10:27:29.145  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:29.145  3055  3885 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:29.145  5839  5839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 10:27:29.145   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:29.145  3055  3066 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 10:27:29.146  5839  5839 D ObexServerSockets: Succeed to create listening sockets 
10-05 10:27:29.146  5839  5839 D ObexServerSockets0: startAccept()
10-05 10:27:29.146  5839  5839 D ObexServerSockets0: prepareForNewConnect()
10-05 10:27:29.147  3702  3721 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:29.147   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:29.147   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 10:27:29.148   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 10:27:29.148   930   930 D BluetoothA2dp: Proxy object connected
10-05 10:27:29.148  3055  3888 D BluetoothMap: onBluetoothStateChange: up=true
10-05 10:27:29.148  5839  5839 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-05 10:27:29.148  5839  5839 D BluetoothSdpJni: SDP Create record success - handle: 0
10-05 10:27:29.149  5839  5878 D ObexServerSockets0: Accepting socket connection...
10-05 10:27:29.149  5839  5879 D ObexServerSockets0: Accepting socket connection...
10-05 10:27:29.150  3055  3055 D BluetoothMap: Proxy object connected
,10-05 10:27:29.150  3055  3055 D MapProfile: Bluetooth service connected
10-05 10:27:29.150  3055  3055 D BluetoothMap: getConnectedDevices()
10-05 10:27:29.150  5617  5629 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 10:27:29.152  5617  5617 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 10:27:29.152  5617  5617 D PanProfile: Bluetooth service connected
10-05 10:27:29.152  5617  5617 D BluetoothInputDevice: Proxy object connected
10-05 10:27:29.152  5617  5617 D HidProfile: Bluetooth service connected
10-05 10:27:29.153  5559  5559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 10:27:29.154   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-05 10:27:29.154  5839  5839 D BluetoothMapService: onReceive
10-05 10:27:29.154  5839  5839 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 10:27:29.154  5617  5617 D BluetoothA2dp: Proxy object connected
10-05 10:27:29.155  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:29.155  5839  5839 D BluetoothMapService: STATE_ON
10-05 10:27:29.156  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:29.157  5839  5880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 10:27:29.158  5839  5880 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-05 10:27:29.158  5839  5880 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-05 10:27:29.160  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 10:27:29.167  3509  3509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 10:27:29.168  5617  5617 D DockEventReceiver: finishStartingService: stopping service
,10-05 10:27:29.176  3055  3055 D BluetoothPbap: Proxy object connected
,10-05 10:27:29.176  3055  3055 D PbapServerProfile: Bluetooth service connected
10-05 10:27:29.176  5839  5839 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-05 10:27:29.176  5839  5839 D ObexServerSockets0: prepareForNewConnect()
10-05 10:27:29.177  5839  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 10:27:29.181  5617  5617 D BluetoothPbap: Proxy object connected
,10-05 10:27:29.181  5617  5617 D PbapServerProfile: Bluetooth service connected
,10-05 10:27:29.196  5839  5888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 10:27:29.197  5839  5888 I BtOppRfcommListener: Accept thread started.
,10-05 10:27:29.234  5617  5629 D BluetoothHeadset: Proxy object connected
,10-05 10:27:29.235  3055  3885 D BluetoothHeadset: Proxy object connected
10-05 10:27:29.235   930   930 D BluetoothHeadset: Proxy object connected
10-05 10:27:29.235   930   930 D BluetoothHeadset: Proxy object connected
10-05 10:27:29.235   930   930 D BluetoothHeadset: Proxy object connected
10-05 10:27:29.235  3055  3055 D HeadsetProfile: Bluetooth service connected
10-05 10:27:29.235  3702  3723 D BluetoothHeadset: Proxy object connected
10-05 10:27:29.237  5617  5617 D HeadsetProfile: Bluetooth service connected
,10-05 10:27:29.245  3055  3066 D BluetoothHeadset: Proxy object connected
,10-05 10:27:29.246   930   947 D BluetoothHeadset: Proxy object connected
10-05 10:27:29.246  3055  3055 D HeadsetProfile: Bluetooth service connected
,10-05 10:27:29.247  3702  4049 D BluetoothHeadset: Proxy object connected
10-05 10:27:29.247   930   947 D BluetoothHeadset: Proxy object connected
,10-05 10:27:29.248   930   947 D BluetoothHeadset: Proxy object connected
,10-05 10:27:32.945  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:32.945  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:32.945  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:32.945  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 10:27:32.945  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:32.945  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:32.945  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:32.945  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 10:27:32.951  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 10:27:32.952  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:32.952  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d13e2a5 removed from the list
10-05 10:27:32.952  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:27:32.953  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:32.953  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:32.954  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:32.955  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@123f67a added. We now have 4 listener(s)
10-05 10:27:32.955  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 10:27:32.960   930   941 D WifiService: setWifiEnabled: false pid=5559, uid=10077
,10-05 10:27:32.960   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 10:27:35.185   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:36.187   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:37.188   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:37.970  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:37.971   930  3860 D WifiService: setWifiEnabled: true pid=5559, uid=10077
10-05 10:27:37.971   930  3860 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 10:27:37.982   507   911 D SoftapController: Softap fwReload - Ok
,10-05 10:27:37.987   507   911 D CommandListener: Setting iface cfg
10-05 10:27:37.988   507   911 D CommandListener: Trying to bring down wlan0
10-05 10:27:37.989   507   911 D CommandListener: Clearing all IP addresses on wlan0
,10-05 10:27:37.993   930  2899 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 10:27:38.190   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:38.657   930  2899 D wifi    : set interface wlan0 flags (UP)
,10-05 10:27:38.659   930  2899 I WifiHAL : Initializing wifi
10-05 10:27:38.659   930  2899 I WifiHAL : Creating socket
,10-05 10:27:38.665   930  2899 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-05 10:27:38.665   930  2899 D wifi    : Did set static halHandle = 0x7f76da3080
10-05 10:27:38.665   930  2899 D wifi    : halHandle = 0x7f76da3080, mVM = 0x7f933cd140, mCls = 0x2015de
10-05 10:27:38.666   930  2899 D wifi    : array field set
,10-05 10:27:38.666   930  2899 I WifiNative-HAL: interface[0] = wlan0
10-05 10:27:38.668   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-05 10:27:38.668   930  5893 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547454857344
10-05 10:27:38.668   930  5893 D wifi    : waitForHalEvents called, vm = 0x7f933cd140, obj = 0x2015de, env = 0x7f8891f440
,10-05 10:27:38.729  5894  5894 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-05 10:27:38.752  5894  5894 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 10:27:38.762  5894  5894 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 10:27:38.762  5894  5894 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-05 10:27:38.769   930  2899 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-05 10:27:38.776  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:38.787   930  2899 D WifiConfigStore: Loading config and enabling all networks 
,10-05 10:27:38.790  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:38.790  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:38.790  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:38.790  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:38.790  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:38.790  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:38.790  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:38.790  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 10:27:38.794  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 10:27:38.800  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:38.800  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:38.800  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:38.800  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:38.800  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:38.800  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 10:27:38.800  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 10:27:38.800  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 10:27:38.801   930  2899 D WifiConfigStore: loaded 0 passpoint configs
10-05 10:27:38.801   930  2899 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-05 10:27:38.802   930  2899 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-05 10:27:38.803   930  2899 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-05 10:27:38.803  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 10:27:38.804   930  2899 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-05 10:27:38.805   930  2899 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-05 10:27:38.805   930  2899 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-05 10:27:38.805  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:38.805   930  2899 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-05 10:27:38.809  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-05 10:27:38.809   930  2899 D WifiNative-HAL: Setting external_sim to 1
10-05 10:27:38.809   930  2899 D wifi    : setting dfs flag to true, 0x7f7a936560
10-05 10:27:38.809   930  2899 D WifiStateMachine: Setting OUI to DA-A1-19
10-05 10:27:38.810   930  2899 D wifi    : setting scan oui 0x7f7a936560
10-05 10:27:38.810   930  2899 D WifiHAL : Sending mac address OUI
,10-05 10:27:38.814   930  2899 E native  : do suspend false
,10-05 10:27:38.820   930  2899 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-05 10:27:38.821   507   911 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-05 10:27:38.821   930   930 D RttService: SCAN_AVAILABLE : 3
10-05 10:27:38.821   930  3008 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-05 10:27:38.822   507   911 D CommandListener: Setting iface cfg
,10-05 10:27:38.825   930  2898 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-05 10:27:38.825   930  2898 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-05 10:27:38.834   930  2898 D WifiNative-HAL: p2pGetDeviceAddress
,10-05 10:27:38.838   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303303 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
10-05 10:27:38.838   930  2898 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-05 10:27:39.191   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 10:27:40.191   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-05 10:27:42.000  5894  5894 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 10:27:42.006  5894  5894 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 10:27:42.011  5894  5894 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 10:27:42.015  5894  5894 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 10:27:42.073   930  2899 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-05 10:27:42.074   930  2899 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-05 10:27:42.074   930  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 10:27:42.086   930  2899 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-05 10:27:42.115   930  2899 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-05 10:27:42.117  5894  5894 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-05 10:27:42.538  5894  5894 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-05 10:27:42.578  5894  5894 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-05 10:27:42.579  5894  5894 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-05 10:27:42.590   930  2899 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-05 10:27:42.591   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
10-05 10:27:42.591   930  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 10:27:42.606   930  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 10:27:42.615   507   911 D CommandListener: Setting iface cfg
,10-05 10:27:42.619   930  2899 D WifiStateMachine: Start Dhcp Watchdog 3
,10-05 10:27:42.624   930  5899 D DhcpClient: Receive thread started
,10-05 10:27:42.627   930  2899 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-05 10:27:42.628   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 10:27:42.628   930  2904 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-05 10:27:42.708   930  2899 E native  : do suspend false
,10-05 10:27:42.718   930  5898 D DhcpClient: Broadcasting DHCPDISCOVER
,10-05 10:27:42.738   930  5899 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-05 10:27:42.738   930  5898 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-05 10:27:42.740   930  5898 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-05 10:27:42.754   930  5899 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-05 10:27:42.755   930  5898 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-05 10:27:42.758   507   911 D CommandListener: Setting iface cfg
,10-05 10:27:42.763   930  2899 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-05 10:27:42.770   930  5898 D DhcpClient: Scheduling renewal in 86399s
,10-05 10:27:42.784   930  2899 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-05 10:27:42.786   930  2899 D WifiConfigStore: No blacklist allowed without epno enabled
,10-05 10:27:42.787   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-05 10:27:42.793   930  2904 D ConnectivityService: Adding iface wlan0 to network 102
10-05 10:27:42.802   930  2899 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-05 10:27:42.843   930  2904 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-05 10:27:42.843   930  2904 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-05 10:27:42.846   930  2904 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-05 10:27:42.849   930  2904 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-05 10:27:42.850   930  2904 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-05 10:27:42.857   930  2904 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 10:27:42.862   930  2904 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-05 10:27:42.862   930  2904 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-05 10:27:42.862   930  2904 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,10-05 10:27:42.862   930  2899 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-05 10:27:42.862   930  2904 D ConnectivityService:    accepting network in place of null
10-05 10:27:42.862   930  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 10:27:42.863   930  2904 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 10:27:42.877   930  5897 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307342, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-05 10:27:42.885   507   911 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 10:27:42.906   507   911 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 10:27:42.910   930  2904 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-05 10:27:42.910   930  2904 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 10:27:42.910  3667  3819 W QCNEJ   : |CORE| network available: 102
10-05 10:27:42.911   930  2904 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-05 10:27:42.912   930   947 D Tethering: MasterInitialState.processMessage what=3
10-05 10:27:42.913  3667  3819 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-05 10:27:42.915  3667  3819 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-05 10:27:42.915  3667  3819 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-05 10:27:42.920  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:42.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:42.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:42.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:42.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:42.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:42.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:42.920  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:27:42.922  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:42.923  4952  4976 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-05 10:27:42.926  3866  3866 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-05 10:27:42.928  4952  4976 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 10:27:42.928  4952  4976 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-05 10:27:42.928  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:42.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:42.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:42.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:42.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:42.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:42.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:42.928  5559  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:27:42.928  4952  4976 E SarControlService: no key has been found,reset the power
10-05 10:27:42.928  4952  4989 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 10:27:42.928  4952  4989 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 10:27:42.928  4952  4989 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 10:27:42.929  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 10:27:42.929  4977  4977 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 10:27:42.930  4952  4989 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 10:27:42.930  4952  4989 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-05 10:27:42.930  4952  4989 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 10:27:42.930  5559  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:42.930  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 10:27:42.930  4977  4977 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 10:27:42.933  3823  3823 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-05 10:27:42.937  4977  4991 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cee853f HexData = [00000000f003000000000000ffffffff]
,10-05 10:27:42.937  4977  4991 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 10:27:42.937  4977  4991 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-05 10:27:42.937  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 10:27:42.937  4952  4962 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 10:27:42.938  3866  3866 D SystemUpdateService: onCreate
10-05 10:27:42.942  3866  3866 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-05 10:27:42.942  4977  4991 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cee853f HexData = [00000000f103000000000000ffffffff]
10-05 10:27:42.942  4977  4991 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 10:27:42.943  4977  4991 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-05 10:27:42.943  4977  4977 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 10:27:42.943  4952  4963 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-05 10:27:42.944   930  5896 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-05 10:27:42.954  3866  3866 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-05 10:27:42.959  3866  5315 I iu.UploadsManager: num queued entries: 0
,10-05 10:27:42.959  3866  5315 I iu.UploadsManager: num updated entries: 0
10-05 10:27:42.959  3866  5315 I iu.SyncManager: NEXT; no task
,10-05 10:27:42.962  3866  5909 I SystemUpdateService: active receiver: enabled
,10-05 10:27:42.965  3866  3866 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 10:27:42.966  3866  3866 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-05 10:27:42.968  5685  5685 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 10:27:42.971  5685  5685 D SprintDMHelper: simOperator: 
,10-05 10:27:42.971  5685  5685 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 10:27:42.981  3866  5909 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 10:27:42.987  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 10:27:42.987  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:42.987  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:42.987  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:42.987  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:42.987  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:42.987  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:42.987  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:27:42.989  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:42.989  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:42.989  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@123f67a removed from the list
10-05 10:27:42.989  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:27:42.989  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:42.989  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:42.991   930  5896 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 05 Oct 2016 14:27:42 GMT], X-Android-Received-Millis=[1475677662990], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475677662969]}
10-05 10:27:42.991   930  2904 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-05 10:27:42.991   930  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-05 10:27:42.991   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-05 10:27:42.992   930  2904 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-05 10:27:42.993  5559  5916 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
10-05 10:27:42.993  5559  5916 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-05 10:27:43.010  3866  5909 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-05 10:27:43.010  3866  5909 I SystemUpdateService: now status is 0 (complete)
10-05 10:27:43.010  3866  5909 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 10:27:43.010  3866  5909 I SystemUpdateService: file has been verified
10-05 10:27:43.010  3866  5909 I SystemUpdateService: OTA package size = 21989297
,10-05 10:27:43.016  3866  5909 I SystemUpdateService: showing system update notification
,10-05 10:27:43.028  3866  3866 D SystemUpdateService: onDestroy
,10-05 10:27:43.110  4926  5914 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-05 10:27:45.651   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 10:27:46.004  5559  5916 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,10-05 10:27:46.004  5559  5922 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
10-05 10:27:46.005  5559  5916 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-05 10:27:46.006  5559  5922 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-05 10:27:46.006  5559  5922 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 10:27:46.006  5559  5916 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 10:27:46.008  5559  5916 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 10:27:46.008  5559  5922 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 10:27:46.012  5559  5922 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
10-05 10:27:46.012  5559  5916 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-05 10:27:46.012  5559  5924 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:46.012  5559  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 10:27:46.014  5559  5925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:46.014  5559  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-05 10:27:46.016  5559  5926 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:46.016  5559  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-05 10:27:46.018  5559  5927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:46.018  5559  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:27:46.018  5559  5926 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:46.018  5559  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 10:27:46.018  5559  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 10:27:46.018  5559  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 10:27:46.018  5559  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 10:27:46.019  5559  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 10:27:46.019  5559  5927 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:46.019  5559  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 10:27:46.019  5559  5925 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 156, thread name: IncomingSocketThread/Sender): Socket closed
10-05 10:27:46.019  5559  5926 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 10:27:46.019  5559  5926 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-05 10:27:46.019  5559  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 10:27:46.019  5559  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 10:27:46.020  5559  5925 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 156, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:46.020  5559  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-05 10:27:46.020  5559  5926 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 10:27:46.020  5559  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-05 10:27:46.020  5559  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 10:27:46.020  5559  5925 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-05 10:27:46.020  5559  5925 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 10:27:46.020  5559  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 10:27:46.020  5559  5925 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:46.020  5559  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,10-05 10:27:46.020  5559  5927 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 10:27:46.020  5559  5927 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 10:27:46.020  5559  5927 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,10-05 10:27:46.021  5559  5927 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:46.021  5559  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-05 10:27:46.021  5559  5924 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 157, thread name: OutgoingSocketThread/Sender): Socket closed
10-05 10:27:46.021  5559  5924 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:46.021  5559  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-05 10:27:46.021  5559  5924 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-05 10:27:46.021  5559  5926 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-05 10:27:46.021  5559  5924 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 10:27:46.022  5559  5926 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:46.022  5559  5926 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,10-05 10:27:46.022  5559  5924 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:46.022  5559  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,10-05 10:27:48.665   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 10:27:49.006  5559  5605 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-05 10:27:49.007  5559  5605 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-05 10:27:49.014  5559  5605 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fdd15d3 Bundle[{}]
10-05 10:27:49.015  5559  5605 I io.jxcore.node.LifeCycleMonitor: start: OK
10-05 10:27:49.015  5559  5605 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-05 10:27:49.016  5559  5605 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-05 10:27:49.017  5559  5605 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-05 10:27:49.019  5559  5605 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-05 10:27:49.021  5559  5605 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-05 10:27:49.028  5559  5605 I System.out: Running OutgoingSocketThread
,10-05 10:27:49.031  5559  5928 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,10-05 10:27:49.031  5559  5928 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-05 10:27:50.865   930  2904 D ConnectivityService: handlePromptUnvalidated 102
,10-05 10:27:52.043  5559  5928 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,10-05 10:27:52.043  5559  5928 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-05 10:27:52.043  5559  5928 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 10:27:52.044  5559  5928 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 10:27:52.046  5559  5929 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
10-05 10:27:52.046  5559  5929 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,10-05 10:27:52.046  5559  5928 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-05 10:27:52.046  5559  5929 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 10:27:52.049  5559  5929 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 10:27:52.050  5559  5931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:52.050  5559  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:27:52.051  5559  5929 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,10-05 10:27:52.053  5559  5932 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:52.053  5559  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:27:52.055  5559  5933 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:52.055  5559  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-05 10:27:52.055  5559  5932 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:52.055  5559  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:27:52.055  5559  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 10:27:52.055  5559  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 10:27:52.056  5559  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 10:27:52.056  5559  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 10:27:52.056  5559  5931 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 168, thread name: OutgoingSocketThread/Sender): Socket closed
10-05 10:27:52.056  5559  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 10:27:52.057  5559  5931 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:52.057  5559  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-05 10:27:52.057  5559  5933 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:52.057  5559  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 10:27:52.057  5559  5932 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 10:27:52.057  5559  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 10:27:52.057  5559  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 10:27:52.057  5559  5931 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-05 10:27:52.057  5559  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 10:27:52.057  5559  5931 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 10:27:52.057  5559  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 10:27:52.057  5559  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 10:27:52.057  5559  5931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:52.057  5559  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-05 10:27:52.057  5559  5932 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 10:27:52.057  5559  5933 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 10:27:52.057  5559  5933 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-05 10:27:52.057  5559  5932 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-05 10:27:52.057  5559  5933 I io.jxcore.node.IncomingSocketThread: The sending thread is done
10-05 10:27:52.057  5559  5932 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:52.057  5559  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-05 10:27:52.058  5559  5933 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 10:27:52.058  5559  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-05 10:27:52.056  5559  5934 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:52.056  5559  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 10:27:52.059  5559  5934 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:52.059  5559  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 10:27:52.059  5559  5934 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 10:27:52.059  5559  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-05 10:27:52.059  5559  5934 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 10:27:52.059  5559  5934 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 10:27:52.059  5559  5934 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 10:27:52.060  5559  5934 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 10:27:52.060  5559  5934 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 10:27:52.060  5559  5934 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-05 10:27:52.060  5559  5934 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
,10-05 10:27:52.060  5559  5934 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 10:27:52.060  5559  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,10-05 10:27:53.836   930  2899 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-05 10:27:55.041  5559  5605 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 180)
,10-05 10:27:55.042  5559  5605 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-05 10:27:55.043  5559  5605 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,10-05 10:27:55.050  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 10:27:55.051  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc54e2b added. We now have 3 listener(s)
,10-05 10:27:55.054  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:27:55.055  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-05 10:27:55.055  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 10:27:55.055  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.055  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b159288 added. We now have 4 listener(s)
10-05 10:27:55.055  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 10:27:55.057  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 10:27:55.063  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 10:27:55.070  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:27:55.070  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:55.070  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:55.070  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:55.070  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:55.070  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:55.070  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:55.070  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:27:55.072  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 10:27:55.072  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:27:55.072  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 10:27:55.073  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb0046 added. We now have 4 listener(s)
,10-05 10:27:55.074  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 10:27:55.075  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:27:55.075  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 10:27:55.075  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.075  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@148a207 added. We now have 5 listener(s)
10-05 10:27:55.075  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:27:55.075  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:27:55.075  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:27:55.075  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:27:55.076  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 10:27:55.076  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.076  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:27:55.076  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:27:55.076  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:27:55.076  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc54e2b removed from the list
10-05 10:27:55.076  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.076  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b159288 removed from the list
10-05 10:27:55.076  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:55.080  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:55.080  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:27:55.080  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:55.081  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.081  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:55.083  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:27:55.083  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:27:55.083  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 10:27:55.083  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b159288 not in the list
10-05 10:27:55.083  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.084  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:55.086  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:27:55.086  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 10:27:55.086  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.087  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@148a207 removed from the list
10-05 10:27:55.087  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:27:55.087  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.087  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:55.087  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:27:55.087  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:27:55.087  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb0046 removed from the list
,10-05 10:27:55.088  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 10:27:55.088  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b54f34 added. We now have 3 listener(s)
,10-05 10:27:55.091  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:27:55.091  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:27:55.091  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 10:27:55.091  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.092  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28cc15d added. We now have 4 listener(s)
10-05 10:27:55.092  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:27:55.092  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 10:27:55.096  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 10:27:55.100  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:27:55.100  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:55.100  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:55.100  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:55.100  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:55.100  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:55.100  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:55.100  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:27:55.102  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:55.102  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:27:55.102  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 10:27:55.102  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c357a3 added. We now have 4 listener(s)
,10-05 10:27:55.104  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:27:55.104  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:27:55.104  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 10:27:55.105  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.105  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf22aa0 added. We now have 5 listener(s)
10-05 10:27:55.105  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:27:55.105  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 10:27:55.105  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 10:27:55.105  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 10:27:55.105  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:27:55.105  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-05 10:27:55.106  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:55.109  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:55.111  5559  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 10:27:55.111  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 10:27:55.114  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 10:27:55.115  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 10:27:55.115  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 10:27:55.118  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 10:27:55.118  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 10:27:55.118  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 10:27:55.118  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 10:27:55.118  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-05 10:27:55.119  5559  5605 D BluetoothAdapter: STATE_ON
10-05 10:27:55.121  5839  5867 D BtGatt.GattService: registerClient() - UUID=a66331f8-bcdb-4099-adc5-a0751185245a
,10-05 10:27:55.122  5839  5855 D BtGatt.GattService: onClientRegistered() - UUID=a66331f8-bcdb-4099-adc5-a0751185245a, clientIf=5
10-05 10:27:55.123  5559  5569 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 10:27:55.124  5839  5849 D BtGatt.GattService: start scan with filters
,10-05 10:27:55.128  5839  5858 D BtGatt.ScanManager: handling starting scan
,10-05 10:27:55.128  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 10:27:55.128  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 10:27:55.128  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:27:55.128  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 10:27:55.128  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 10:27:55.128  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 10:27:55.128  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-05 10:27:55.129  5839  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc22a4
,10-05 10:27:55.130  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 10:27:55.130  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 10:27:55.130  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 10:27:55.132  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 10:27:55.134  5559  5605 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-05 10:27:55.134  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 10:27:55.134  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 10:27:55.134  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.134  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 10:27:55.134  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:27:55.135  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 10:27:55.135  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 10:27:55.135  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 10:27:55.135  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 10:27:55.135  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 10:27:55.135  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-05 10:27:55.136  5559  5605 D BluetoothAdapter: STATE_ON
10-05 10:27:55.136  5839  5855 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 10:27:55.137  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.137  5839  5849 D BtGatt.GattService: stopScan() - queue size =1
,10-05 10:27:55.137  5839  5858 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 10:27:55.137  5839  5876 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 10:27:55.138  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 10:27:55.138  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 10:27:55.138  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 10:27:55.138  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:27:55.138  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-05 10:27:55.138  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 10:27:55.138  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 10:27:55.138  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 10:27:55.139  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:27:55.139  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 10:27:55.139  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 10:27:55.139  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 10:27:55.139  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-05 10:27:55.140  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:27:55.141  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:27:55.141  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:27:55.141  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:27:55.143  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:27:55.143  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:27:55.143  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:27:55.143  5839  5855 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 10:27:55.143  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:27:55.143  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:27:55.143  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.143  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:27:55.144  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:27:55.144  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:27:55.144  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b54f34 removed from the list
10-05 10:27:55.144  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.144  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28cc15d removed from the list
10-05 10:27:55.144  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:27:55.144  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:55.144  5839  5858 D BtGatt.ScanManager: Starting BLE batch scan
10-05 10:27:55.144  5839  5858 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 10:27:55.145  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.145  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:55.146  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:27:55.147  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:27:55.147  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.147  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28cc15d not in the list
10-05 10:27:55.147  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.147  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:55.148  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:27:55.148  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:27:55.148  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.148  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf22aa0 removed from the list
10-05 10:27:55.148  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:27:55.149  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.149  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:55.149  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:27:55.149  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:27:55.149  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c357a3 removed from the list
10-05 10:27:55.150  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 10:27:55.150  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55f50cc added. We now have 3 listener(s)
10-05 10:27:55.151  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:27:55.152  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:27:55.152  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 10:27:55.152  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.152  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfbbf15 added. We now have 4 listener(s)
10-05 10:27:55.152  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:27:55.153  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 10:27:55.155  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 10:27:55.156  5839  5855 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 10:27:55.156  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:27:55.162  5839  5855 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-05 10:27:55.162  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.163  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:27:55.163  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:55.163  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:55.163  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:55.163  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:55.163  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:55.163  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:55.163  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:27:55.164  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:55.165  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:27:55.165  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 10:27:55.165  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65a181b added. We now have 4 listener(s)
10-05 10:27:55.166  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:27:55.166  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:27:55.166  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 10:27:55.166  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.166  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@796adb8 added. We now have 5 listener(s)
10-05 10:27:55.166  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:27:55.166  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 10:27:55.167  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:55.167  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 10:27:55.167  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 10:27:55.167  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 10:27:55.167  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:27:55.167  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 10:27:55.169  5839  5855 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 10:27:55.169  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.169  5839  5858 D BtGatt.ScanManager: stopping BLe Batch
10-05 10:27:55.169  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:55.170  5559  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 10:27:55.170  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 10:27:55.173  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 10:27:55.173  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 10:27:55.174  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 10:27:55.174  5839  5855 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 10:27:55.175  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:27:55.175  5839  5858 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 10:27:55.178  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 10:27:55.178  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 10:27:55.179  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 10:27:55.179  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 10:27:55.179  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-05 10:27:55.180  5559  5605 D BluetoothAdapter: STATE_ON
10-05 10:27:55.180  5839  5855 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-05 10:27:55.180  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:27:55.182  5839  5876 D BtGatt.GattService: registerClient() - UUID=4b565ea3-a95f-4860-bb28-2c368ad63bd8
10-05 10:27:55.183  5839  5855 D BtGatt.GattService: onClientRegistered() - UUID=4b565ea3-a95f-4860-bb28-2c368ad63bd8, clientIf=5
,10-05 10:27:55.183  5559  5569 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 10:27:55.183  5839  5850 D BtGatt.GattService: start scan with filters
,10-05 10:27:55.185  5839  5858 D BtGatt.ScanManager: handling starting scan
,10-05 10:27:55.185  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 10:27:55.185  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 10:27:55.186  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:27:55.186  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 10:27:55.186  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 10:27:55.186  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 10:27:55.186  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 10:27:55.188  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 10:27:55.189  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 10:27:55.189  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 10:27:55.190  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-05 10:27:55.190  5839  5855 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 10:27:55.191  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:27:55.191  5839  5858 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 10:27:55.196  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-05 10:27:55.196  5559  5605 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-05 10:27:55.196  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:27:55.197  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:27:55.197  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:27:55.197  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:27:55.197  5839  5855 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 10:27:55.197  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.197  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.197  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 10:27:55.197  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 10:27:55.197  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:27:55.197  5839  5858 D BtGatt.ScanManager: Starting BLE batch scan
10-05 10:27:55.197  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55f50cc removed from the list
10-05 10:27:55.197  5839  5858 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 10:27:55.197  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.197  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfbbf15 removed from the list
10-05 10:27:55.198  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:27:55.198  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 10:27:55.199  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.199  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-05 10:27:55.199  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.199  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 10:27:55.200  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:27:55.200  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 10:27:55.200  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.200  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfbbf15 not in the list
10-05 10:27:55.200  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 10:27:55.200  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 10:27:55.200  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 10:27:55.200  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 10:27:55.201  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 10:27:55.201  5559  5605 D BluetoothAdapter: STATE_ON
,10-05 10:27:55.201  5839  5850 D BtGatt.GattService: stopScan() - queue size =1
,10-05 10:27:55.202  5839  5875 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 10:27:55.202  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 10:27:55.202  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 10:27:55.202  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 10:27:55.202  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:27:55.202  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 10:27:55.203  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 10:27:55.203  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 10:27:55.203  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-05 10:27:55.203  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:27:55.204  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 10:27:55.204  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 10:27:55.204  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 10:27:55.204  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 10:27:55.204  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:55.205  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 10:27:55.205  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:27:55.205  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.205  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:27:55.205  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@796adb8 removed from the list
10-05 10:27:55.205  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:27:55.205  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:27:55.205  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.205  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:55.205  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:27:55.205  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:27:55.205  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-05 10:27:55.205  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65a181b removed from the list
10-05 10:27:55.206  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 10:27:55.206  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e4ed64 added. We now have 3 listener(s)
10-05 10:27:55.207  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:27:55.207  5839  5855 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 10:27:55.207  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:27:55.207  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.207  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 10:27:55.207  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.207  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@625bbcd added. We now have 4 listener(s)
10-05 10:27:55.207  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:27:55.208  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 10:27:55.212  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:27:55.213  5839  5855 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 10:27:55.213  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:27:55.215  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:27:55.215  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:55.215  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:55.215  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:55.215  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:55.215  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:55.215  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:55.215  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 10:27:55.217  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:55.217  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:27:55.217  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 10:27:55.217  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e096f93 added. We now have 4 listener(s)
10-05 10:27:55.218  5839  5855 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 10:27:55.218  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.218  5839  5858 D BtGatt.ScanManager: stopping BLe Batch
10-05 10:27:55.218  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:27:55.219  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:27:55.219  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 10:27:55.219  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.219  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b57bd0 added. We now have 5 listener(s)
10-05 10:27:55.219  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:27:55.219  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-05 10:27:55.219  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 10:27:55.219  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 10:27:55.219  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 10:27:55.219  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 10:27:55.219  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:55.222  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:55.222  5559  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 10:27:55.222  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 10:27:55.223  5839  5855 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 10:27:55.223  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.223  5839  5858 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 10:27:55.227  5839  5855 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 10:27:55.228  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.228  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 10:27:55.229  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 10:27:55.229  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 10:27:55.233  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 10:27:55.233  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-05 10:27:55.233  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 10:27:55.233  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 10:27:55.233  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 10:27:55.234  5559  5605 D BluetoothAdapter: STATE_ON
,10-05 10:27:55.236  5839  5867 D BtGatt.GattService: registerClient() - UUID=373c7b28-7f34-47a5-b66b-770a4df4ce35
,10-05 10:27:55.237  5839  5855 D BtGatt.GattService: onClientRegistered() - UUID=373c7b28-7f34-47a5-b66b-770a4df4ce35, clientIf=5
10-05 10:27:55.237  5559  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 10:27:55.237  5839  5876 D BtGatt.GattService: start scan with filters
10-05 10:27:55.239  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 10:27:55.239  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 10:27:55.239  5839  5858 D BtGatt.ScanManager: handling starting scan
,10-05 10:27:55.239  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:27:55.239  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 10:27:55.240  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 10:27:55.240  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 10:27:55.240  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 10:27:55.242  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 10:27:55.242  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 10:27:55.242  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 10:27:55.243  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 10:27:55.244  5839  5855 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 10:27:55.244  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.244  5839  5858 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 10:27:55.246  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 10:27:55.246  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:27:55.246  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:27:55.246  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:27:55.247  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.247  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 10:27:55.247  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 10:27:55.247  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:27:55.247  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e4ed64 removed from the list
10-05 10:27:55.247  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.247  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@625bbcd removed from the list
10-05 10:27:55.247  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:27:55.247  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 10:27:55.247  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,10-05 10:27:55.247  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-05 10:27:55.247  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.247  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:27:55.248  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:27:55.248  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 10:27:55.248  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.248  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@625bbcd not in the list
10-05 10:27:55.248  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 10:27:55.248  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 10:27:55.248  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 10:27:55.249  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 10:27:55.249  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 10:27:55.249  5839  5855 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-05 10:27:55.249  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.249  5559  5605 D BluetoothAdapter: STATE_ON
10-05 10:27:55.249  5839  5858 D BtGatt.ScanManager: Starting BLE batch scan
10-05 10:27:55.249  5839  5858 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 10:27:55.250  5839  5876 D BtGatt.GattService: stopScan() - queue size =1
10-05 10:27:55.250  5839  5875 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 10:27:55.250  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 10:27:55.250  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 10:27:55.250  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 10:27:55.250  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 10:27:55.250  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 10:27:55.250  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 10:27:55.251  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 10:27:55.251  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 10:27:55.251  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:27:55.252  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 10:27:55.252  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 10:27:55.252  5559  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 10:27:55.252  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 10:27:55.252  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:55.255  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 10:27:55.255  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:27:55.255  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.255  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:27:55.255  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b57bd0 removed from the list
10-05 10:27:55.255  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:27:55.255  5559  5559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 10:27:55.255  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.255  5559  5559 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 10:27:55.255  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:55.255  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 10:27:55.255  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:27:55.255  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e096f93 removed from the list
10-05 10:27:55.256  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 10:27:55.256  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9be84fc added. We now have 3 listener(s)
10-05 10:27:55.257  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:27:55.257  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:27:55.257  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 10:27:55.257  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.257  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b9785 added. We now have 4 listener(s)
10-05 10:27:55.257  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:27:55.258  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 10:27:55.258  5839  5855 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 10:27:55.258  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.260  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 10:27:55.262  5839  5855 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 10:27:55.262  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.264  5559  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 10:27:55.264  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 10:27:55.264  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 10:27:55.264  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 10:27:55.264  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 10:27:55.264  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:55.264  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 10:27:55.264  5559  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 10:27:55.265  5559  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 10:27:55.266  5559  5605 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 10:27:55.266  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 10:27:55.266  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36d3e0b added. We now have 4 listener(s)
10-05 10:27:55.267  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 10:27:55.267  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 10:27:55.267  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 10:27:55.267  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 10:27:55.267  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ecf4e8 added. We now have 5 listener(s)
10-05 10:27:55.267  5559  5605 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 10:27:55.267  5559  5605 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 10:27:55.267  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 10:27:55.267  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:27:55.267  5559  5605 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 10:27:55.268  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:27:55.268  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.268  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 10:27:55.268  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 10:27:55.268  5839  5855 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 10:27:55.268  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.268  5839  5858 D BtGatt.ScanManager: stopping BLe Batch
,10-05 10:27:55.268  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:27:55.268  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9be84fc removed from the list
10-05 10:27:55.268  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.269  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b9785 removed from the list
10-05 10:27:55.270  5559  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 10:27:55.270  5559  5605 D io.jxcore.node.ConnectivityMonitor: stop
10-05 10:27:55.270  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:55.271  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 10:27:55.271  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 10:27:55.272  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:27:55.272  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:27:55.272  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.272  5559  5605 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98b9785 not in the list
,10-05 10:27:55.272  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.272  5839  5855 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 10:27:55.273  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:55.273  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 10:27:55.273  5839  5858 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 10:27:55.274  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 10:27:55.274  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 10:27:55.274  5559  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 10:27:55.274  5559  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ecf4e8 removed from the list
10-05 10:27:55.274  5559  5605 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 10:27:55.274  5559  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 10:27:55.274  5559  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 10:27:55.274  5559  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 10:27:55.274  5559  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 10:27:55.275  5559  5605 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36d3e0b removed from the list
,10-05 10:27:55.275  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-05 10:27:55.276  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-05 10:27:55.276  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-05 10:27:55.276  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 10:27:55.276  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,10-05 10:27:55.276  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 10:27:55.277  5839  5855 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 10:27:55.277  5839  5855 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 10:27:55.642  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 10:27:55.706  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 10:27:55.756  5559  5559 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 10:27:57.427  5559  5935 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 10:27:57.427  5559  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:27:58.233  5559  5935 W !!      : call onHalfStreamCopied
,10-05 10:27:58.233  5559  5935 I testCopyDataAndClose: closing input stream
,10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 189, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 10:27:59.014  5559  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-05 10:28:03.107  5559  5936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
10-05 10:28:03.107  5559  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:28:03.776   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 10:28:05.107  5559  5605 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 192. Connection data: Peer properties: [null null].
10-05 10:28:05.107  5559  5605 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:28:05.107  5559  5605 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 192, name: My test thread name)
,10-05 10:28:05.192   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-05 10:28:05.192   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-05 10:28:05.245  5559  5937 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 10:28:05.245  5559  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:28:05.283  5559  5936 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 10:28:05.283  5559  5936 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
10-05 10:28:05.283  5559  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,10-05 10:28:06.809   930  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 194, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 10:28:06.849  5559  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-05 10:28:10.922  5559  5938 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
10-05 10:28:10.922  5559  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:28:10.922  5559  5938 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: My test thread name). Connection data: Peer properties: [null null].
10-05 10:28:10.922  5559  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 10:28:10.923  5559  5938 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 10:28:10.923  5559  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 10:28:10.923  5559  5938 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 10:28:10.923  5559  5938 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 10:28:10.923  5559  5938 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 10:28:10.923  5559  5938 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-05 10:28:10.923  5559  5938 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 10:28:10.924  5559  5938 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
10-05 10:28:10.924  5559  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-05 10:28:10.925  5559  5605 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 10:28:10.928  5559  5939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
10-05 10:28:10.928  5559  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 10:28:10.929  5559  5939 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 200, thread name: My test thread name): Test exception.
10-05 10:28:10.929  5559  5939 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
10-05 10:28:10.929  5559  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-05 10:28:10.929  5559  5939 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-05 10:28:10.930  5559  5939 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
10-05 10:28:10.930  5559  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-05 10:28:10.935  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
10-05 10:28:10.935  5559  5605 I jxcore-log: 
,10-05 10:28:10.935  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-05 10:28:10.935  5559  5605 I jxcore-log: 
10-05 10:28:10.936  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'Number of failed tests:  2'
10-05 10:28:10.936  5559  5605 I jxcore-log: 
10-05 10:28:10.936  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-05 10:28:10.936  5559  5605 I jxcore-log: 
10-05 10:28:10.936  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'Total duration:  103464'
10-05 10:28:10.936  5559  5605 I jxcore-log: 
10-05 10:28:10.937  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'Failures: 
10-05 10:28:10.937  5559  5605 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
10-05 10:28:10.937  5559  5605 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
10-05 10:28:10.937  5559  5605 I jxcore-log:      but: was ""
10-05 10:28:10.937  5559  5605 I jxcore-log: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
10-05 10:28:10.937  5559  5605 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
10-05 10:28:10.937  5559  5605 I jxcore-log:      but: was ""
10-05 10:28:10.937  5559  5605 I jxcore-log: '
10-05 10:28:10.937  5559  5605 I jxcore-log: 
,10-05 10:28:10.938  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-05 10:28:10.938  5559  5605 I jxcore-log: 
10-05 10:28:10.939  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-05 10:28:10.939  5559  5605 I jxcore-log: 
,10-05 10:28:10.942  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.942  5559  5605 I jxcore-log: 
10-05 10:28:10.943  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.943  5559  5605 I jxcore-log: 
10-05 10:28:10.943  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.943  5559  5605 I jxcore-log: 
10-05 10:28:10.943  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.943  5559  5605 I jxcore-log: 
,10-05 10:28:10.944  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-05 10:28:10.944  5559  5605 I jxcore-log: 
10-05 10:28:10.944  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 10:28:10.944  5559  5605 I jxcore-log: 
10-05 10:28:10.944  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.944  5559  5605 I jxcore-log: 
10-05 10:28:10.945  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.945  5559  5605 I jxcore-log: 
,10-05 10:28:10.945  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-05 10:28:10.945  5559  5605 I jxcore-log: 
10-05 10:28:10.945  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 10:28:10.945  5559  5605 I jxcore-log: 
10-05 10:28:10.945  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 10:28:10.945  5559  5605 I jxcore-log: 
10-05 10:28:10.945  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.945  5559  5605 I jxcore-log: 
10-05 10:28:10.946  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.946  5559  5605 I jxcore-log: 
10-05 10:28:10.946  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 10:28:10.946  5559  5605 I jxcore-log: 
,10-05 10:28:10.946  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.946  5559  5605 I jxcore-log: 
10-05 10:28:10.947  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 10:28:10.947  5559  5605 I jxcore-log: 
10-05 10:28:10.947  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 10:28:10.947  5559  5605 I jxcore-log: 
10-05 10:28:10.947  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.947  5559  5605 I jxcore-log: 
10-05 10:28:10.947  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.947  5559  5605 I jxcore-log: 
10-05 10:28:10.947  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.947  5559  5605 I jxcore-log: 
10-05 10:28:10.948  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 10:28:10.948  5559  5605 I jxcore-log: 
,10-05 10:28:10.948  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 10:28:10.948  5559  5605 I jxcore-log: 
10-05 10:28:10.949  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 10:28:10.949  5559  5605 I jxcore-log: 
10-05 10:28:10.950  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.950  5559  5605 I jxcore-log: 
10-05 10:28:10.950  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.950  5559  5605 I jxcore-log: 
10-05 10:28:10.950  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.950  5559  5605 I jxcore-log: 
10-05 10:28:10.951  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.951  5559  5605 I jxcore-log: 
,10-05 10:28:10.951  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.951  5559  5605 I jxcore-log: 
10-05 10:28:10.951  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.951  5559  5605 I jxcore-log: 
10-05 10:28:10.951  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.951  5559  5605 I jxcore-log: 
10-05 10:28:10.952  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.952  5559  5605 I jxcore-log: 
10-05 10:28:10.952  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.952  5559  5605 I jxcore-log: 
10-05 10:28:10.952  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.952  5559  5605 I jxcore-log: 
10-05 10:28:10.952  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.952  5559  5605 I jxcore-log: 
10-05 10:28:10.952  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.952  5559  5605 I jxcore-log: 
,10-05 10:28:10.953  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.953  5559  5605 I jxcore-log: 
10-05 10:28:10.953  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.953  5559  5605 I jxcore-log: 
10-05 10:28:10.953  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 10:28:10.953  5559  5605 I jxcore-log: 
10-05 10:28:10.953  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-05 10:28:10.953  5559  5605 I jxcore-log: 
10-05 10:28:10.954  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-05 10:28:10.954  5559  5605 I jxcore-log: 
10-05 10:28:10.954  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.954  5559  5605 I jxcore-log: 
10-05 10:28:10.954  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.954  5559  5605 I jxcore-log: 
,10-05 10:28:10.954  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.954  5559  5605 I jxcore-log: 
10-05 10:28:10.954  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.954  5559  5605 I jxcore-log: 
10-05 10:28:10.955  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.955  5559  5605 I jxcore-log: 
10-05 10:28:10.955  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 10:28:10.955  5559  5605 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-05 10:28:10.955  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.955  5559  5605 I jxcore-log: 
,10-05 10:28:10.956  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.956  5559  5605 I jxcore-log: 
10-05 10:28:10.956  5559  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 10:28:10.956  5559  5605 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-05 10:28:10.956  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 10:28:10.956  5559  5605 I jxcore-log: 
10-05 10:28:10.956  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 10:28:10.956  5559  5605 I jxcore-log: 
10-05 10:28:10.956  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 10:28:10.956  5559  5605 I jxcore-log: 
10-05 10:28:10.957  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 10:28:10.957  5559  5605 I jxcore-log: 
,10-05 10:28:10.962  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-05 10:28:10.962  5559  5605 I jxcore-log: 
10-05 10:28:10.962  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - WARN testUtils: 'myNameCallback not set!'
10-05 10:28:10.962  5559  5605 I jxcore-log: 
10-05 10:28:10.963  5559  5605 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-05 10:28:10.963  5559  5605 I jxcore-log: 2016-10-05 14:28:10 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-05 10:28:10.963  5559  5605 I jxcore-log: 
,10-05 10:28:10.969  5559  5559 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-05 10:28:13.005  5559  5605 I jxcore-log: 2016-10-05 14:28:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-05 10:28:13.005  5559  5605 I jxcore-log: 
,10-05 10:28:13.350  5559  5605 I jxcore-log: 2016-10-05 14:28:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-05 10:28:13.350  5559  5605 I jxcore-log: 
,10-05 10:28:13.364  5559  5605 I jxcore-log: 2016-10-05 14:28:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-05 10:28:13.364  5559  5605 I jxcore-log: 
,10-05 10:28:14.484  5559  5605 I jxcore-log: 2016-10-05 14:28:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-05 10:28:14.484  5559  5605 I jxcore-log: 
,10-05 10:28:14.652  5559  5605 I jxcore-log: 2016-10-05 14:28:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-05 10:28:14.652  5559  5605 I jxcore-log: 
,10-05 10:28:14.656  5559  5605 I jxcore-log: 2016-10-05 14:28:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-05 10:28:14.656  5559  5605 I jxcore-log: 
,10-05 10:28:14.661  5559  5605 I jxcore-log: 2016-10-05 14:28:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-05 10:28:14.661  5559  5605 I jxcore-log: 
,10-05 10:28:15.212  5559  5605 I jxcore-log: 2016-10-05 14:28:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-05 10:28:15.212  5559  5605 I jxcore-log: 
,10-05 10:28:15.265  5559  5605 I jxcore-log: 2016-10-05 14:28:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-05 10:28:15.265  5559  5605 I jxcore-log: 
,10-05 10:28:15.278  5559  5605 I jxcore-log: 2016-10-05 14:28:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-05 10:28:15.278  5559  5605 I jxcore-log: 
,10-05 10:28:15.283  5559  5605 I jxcore-log: 2016-10-05 14:28:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-05 10:28:15.283  5559  5605 I jxcore-log: 
,10-05 10:28:15.569  5559  5605 I jxcore-log: 2016-10-05 14:28:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-05 10:28:15.569  5559  5605 I jxcore-log: 
,10-05 10:28:15.698  5559  5605 I jxcore-log: 2016-10-05 14:28:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-05 10:28:15.698  5559  5605 I jxcore-log: 
,10-05 10:28:15.938  5559  5605 I jxcore-log: 2016-10-05 14:28:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-05 10:28:15.938  5559  5605 I jxcore-log: 
,10-05 10:28:15.948  5559  5605 I jxcore-log: 2016-10-05 14:28:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-05 10:28:15.948  5559  5605 I jxcore-log: 
,10-05 10:28:15.952  5559  5605 I jxcore-log: 2016-10-05 14:28:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-05 10:28:15.952  5559  5605 I jxcore-log: 
,10-05 10:28:16.085  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-05 10:28:16.085  5559  5605 I jxcore-log: 
,10-05 10:28:16.092  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-05 10:28:16.092  5559  5605 I jxcore-log: 
,10-05 10:28:16.119  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-05 10:28:16.119  5559  5605 I jxcore-log: 
,10-05 10:28:16.154  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-05 10:28:16.154  5559  5605 I jxcore-log: 
,10-05 10:28:16.161  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-05 10:28:16.161  5559  5605 I jxcore-log: 
,10-05 10:28:16.168  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-05 10:28:16.168  5559  5605 I jxcore-log: 
,10-05 10:28:16.183  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-05 10:28:16.183  5559  5605 I jxcore-log: 
,10-05 10:28:16.188  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-05 10:28:16.188  5559  5605 I jxcore-log: 
,10-05 10:28:16.193  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-05 10:28:16.193  5559  5605 I jxcore-log: 
,10-05 10:28:16.199  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-05 10:28:16.199  5559  5605 I jxcore-log: 
,10-05 10:28:16.212  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-05 10:28:16.212  5559  5605 I jxcore-log: 
,10-05 10:28:16.233  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-05 10:28:16.233  5559  5605 I jxcore-log: 
,10-05 10:28:16.242  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-05 10:28:16.242  5559  5605 I jxcore-log: 
,10-05 10:28:16.253  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-05 10:28:16.253  5559  5605 I jxcore-log: 
,10-05 10:28:16.263  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-05 10:28:16.263  5559  5605 I jxcore-log: 
,10-05 10:28:16.275  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-05 10:28:16.275  5559  5605 I jxcore-log: 
,10-05 10:28:16.284  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-05 10:28:16.284  5559  5605 I jxcore-log: 
,10-05 10:28:16.289  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-05 10:28:16.289  5559  5605 I jxcore-log: 
,10-05 10:28:16.310  5559  5605 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-05 10:28:16.312  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - INFO testUtils: 'BLE multiple advertisement supported'
10-05 10:28:16.312  5559  5605 I jxcore-log: 
,10-05 10:28:16.909  5559  5605 I jxcore-log: 2016-10-05 14:28:16 - DEBUG CoordinatedClient: 'connected to the test server'
10-05 10:28:16.909  5559  5605 I jxcore-log: 
,10-05 10:28:17.070  5559  5605 I jxcore-log: 2016-10-05 14:28:17 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-05 10:28:17.070  5559  5605 I jxcore-log: 
,10-05 10:28:17.073  5559  5605 I jxcore-log: 2016-10-05 14:28:17 - DEBUG CoordinatedClient: 'test client failed'
10-05 10:28:17.073  5559  5605 I jxcore-log: 
,10-05 10:28:17.077  5559  5605 I jxcore-log: 2016-10-05 14:28:17 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-05 10:28:17.077  5559  5605 I jxcore-log: 
,10-05 10:28:17.083  5559  5605 I jxcore-log: 2016-10-05 14:28:17 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-05 10:28:17.083  5559  5605 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-05 10:28:17.083  5559  5605 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-05 10:28:17.083  5559  5605 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-05 10:28:17.083  5559  5605 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-05 10:28:17.083  5559  5605 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-05 10:28:17.083  5559  5605 I jxcore-log: 
,10-05 10:28:17.084  5559  5605 I jxcore-log: 2016-10-05 14:28:17 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-05 10:28:17.084  5559  5605 I jxcore-log: 
,10-05 10:28:17.679  5948  5948 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-05 10:28:17.701  5948  5948 D AndroidRuntime: CheckJNI is OFF
,10-05 10:28:17.729  5948  5948 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-05 10:28:17.767  5948  5948 I Radio-JNI: register_android_hardware_Radio DONE
,10-05 10:28:17.784  5948  5948 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-05 10:28:17.795   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-05 10:28:17.795   930   943 I ActivityManager: Killing 5559:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-05 10:28:17.897   930  3709 I WindowState: WIN DEATH: Window{4113c4a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-05 10:28:17.897   930  3339 D GraphicsStats: Buffer count: 2
10-05 10:28:17.898   930  2900 D WifiService: Client connection lost with reason: 4
,10-05 10:28:17.937   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-05 10:28:17.938   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-05 10:28:17.939   930   943 E ActivityManager: Failure starting process com.test.thalitest
10-05 10:28:17.939   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-05 10:28:17.939   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:28:17.939   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:28:17.939   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-05 10:28:17.939   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-05 10:28:17.940   930   943 I ActivityManager:   Force finishing activity ActivityRecord{8fd96bf u0 com.test.thalitest/.MainActivity t2}
10-05 10:28:17.941   930   953 I art     : Starting a blocking GC Explicit
,10-05 10:28:17.953   930   941 W ActivityManager: Spurious death for ProcessRecord{a1f7236 0:com.test.thalitest/u0a77}, curProc for 5559: null
,10-05 10:28:17.956   930   948 W WindowManager: Attempted to add application window with unknown token Token{ea1918c ActivityRecord{8fd96bf u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,10-05 10:28:17.957   930   948 W WindowManager: Token{ea1918c ActivityRecord{8fd96bf u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{ea1918c ActivityRecord{8fd96bf u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
10-05 10:28:17.957   930   948 W WindowManager: view not successfully added to wm, removing view
10-05 10:28:17.957   930   948 W WindowManager: Exception when adding starting window
10-05 10:28:17.957   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{a802009 V.E...... R.....ID 0,0-0,0} not attached to window manager
10-05 10:28:17.957   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
10-05 10:28:17.957   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
10-05 10:28:17.957   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
10-05 10:28:17.957   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
10-05 10:28:17.957   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
10-05 10:28:17.957   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:28:17.957   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:28:17.957   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-05 10:28:17.957   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-05 10:28:18.025   930   953 I art     : Explicit concurrent mark sweep GC freed 56265(3MB) AllocSpace objects, 15(496KB) LOS objects, 33% free, 29MB/43MB, paused 1.523ms total 83.810ms
,10-05 10:28:18.044   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-05 10:28:18.046  5948  5948 I art     : System.exit called, status: 0
,10-05 10:28:18.046  5948  5948 I AndroidRuntime: VM exiting with result code 0.
,10-05 10:28:18.060   930   953 I ActivityManager: Start proc 5958:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-05 10:28:18.061   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-05 10:28:18.067   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-05 10:28:18.073  4064  4115 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-05 10:28:18.072  5839  5839 D BluetoothMapAppObserver: onReceive
10-05 10:28:18.074  5839  5839 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-05 10:28:18.082   930  2865 I InputReader: Reconfiguring input devices.  changes=0x00000010
10-05 10:28:18.082  3597  3597 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-05 10:28:18.105  3321  5971 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-05 10:28:18.106  3597  5970 I Keyboard.Facilitator.DecoderInitializer: run()
,10-05 10:28:18.131  3597  5970 I Decoder : createOrResetDecoder
,10-05 10:28:18.135  3702  3702 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-05 10:28:18.145    13    13 W kworker/1:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 10:28:18.151   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-05 10:28:18.149    13    13 W kworker/1:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 10:28:18.170  3735  3863 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
10-05 10:28:18.171  3509  3509 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
10-05 10:28:18.169    13    13 W kworker/1:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 10:28:18.173  3509  3509 D AndroidRuntime: Shutting down VM
--------- beginning of crash
10-05 10:28:18.174  3509  3509 E AndroidRuntime: FATAL EXCEPTION: main
10-05 10:28:18.174  3509  3509 E AndroidRuntime: Process: com.google.process.gapps, PID: 3509
10-05 10:28:18.174  3509  3509 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-05 10:28:18.174  3509  3509 E AndroidRuntime: 	... 8 more
,10-05 10:28:18.185   930  3790 I ActivityManager: Start proc 5977:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,10-05 10:28:18.186  3735  3863 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-05 10:28:18.186  3735  3863 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3735
10-05 10:28:18.186  3735  3863 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:28:18.186  3735  3863 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-05 10:28:18.193   930  5986 E DropBoxManagerService: Can't write: system_app_crash
10-05 10:28:18.193   930  5986 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 10:28:18.193   930  5986 E DropBoxManagerService: 	... 5 more
,10-05 10:28:18.194   930  5987 E DropBoxManagerService: Can't write: system_app_crash
10-05 10:28:18.194   930  5987 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 10:28:18.194   930  5987 E DropBoxManagerService: 	... 5 more
10-05 10:28:18.194   930  3789 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 10:28:18.199  3509  3509 I Process : Sending signal. PID: 3509 SIG: 9
10-05 10:28:18.200  3735  3863 I Process : Sending signal. PID: 3735 SIG: 9
,10-05 10:28:18.212  3321  5971 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-05 10:28:18.222  3321  5971 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
10-05 10:28:18.222  3321  5971 E AndroidRuntime: Process: android.process.acore, PID: 3321
10-05 10:28:18.222  3321  5971 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:28:18.222  3321  5971 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-05 10:28:18.226   930  2900 D WifiService: Client connection lost with reason: 4
,10-05 10:28:18.228   930  5992 E DropBoxManagerService: Can't write: system_app_crash
10-05 10:28:18.228   930  5992 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 10:28:18.228   930  5992 E DropBoxManagerService: 	... 5 more
,10-05 10:28:18.229  3321  5971 I Process : Sending signal. PID: 3321 SIG: 9
,10-05 10:28:18.232   930  3789 I ActivityManager: Process com.google.process.gapps (pid 3509) has died
10-05 10:28:18.232   930  3789 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
10-05 10:28:18.232   930  3789 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
10-05 10:28:18.233   930  3789 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
10-05 10:28:18.233   930  3789 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 30999ms
,10-05 10:28:18.254   930  3123 I ActivityManager: Start proc 5994:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,10-05 10:28:18.295   930   940 I ActivityManager: Process android.process.acore (pid 3321) has died
,10-05 10:28:18.296   930   940 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-05 10:28:18.306   930  2864 W InputDispatcher: channel 'ee11ea2 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-05 10:28:18.306   930  3789 D GraphicsStats: Buffer count: 1
10-05 10:28:18.306   930  3709 I WindowState: WIN DEATH: Window{ee11ea2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
10-05 10:28:18.306   930  2864 E InputDispatcher: channel 'ee11ea2 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
10-05 10:28:18.306   930  3709 W InputDispatcher: Attempted to unregister already unregistered input channel 'ee11ea2 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-05 10:28:18.311   930  3860 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3735) has died
,10-05 10:28:18.312   930  3860 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-05 10:28:18.317   930  3860 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-05 10:28:18.336   930   943 I ActivityManager: Start proc 6007:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 10:28:18.380  6007  6007 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:28:18.380  6007  6007 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-05 10:28:18.381  6007  6007 D AndroidRuntime: Shutting down VM
,10-05 10:28:18.387  6007  6007 E AndroidRuntime: FATAL EXCEPTION: main
10-05 10:28:18.387  6007  6007 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6007
10-05 10:28:18.387  6007  6007 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-05 10:28:18.387  6007  6007 E AndroidRuntime: 	... 10 more
,10-05 10:28:18.389   930   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-05 10:28:18.390   930  6020 E DropBoxManagerService: Can't write: system_app_crash
10-05 10:28:18.390   930  6020 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 10:28:18.390   930  6020 E DropBoxManagerService: 	... 5 more
,10-05 10:28:18.390  6007  6007 I Process : Sending signal. PID: 6007 SIG: 9
,10-05 10:28:18.400   930  3860 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6007) has died
,10-05 10:28:18.402   930  3860 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-05 10:28:18.417   930   943 I ActivityManager: Start proc 6021:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 10:28:18.468  6021  6021 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:28:18.468  6021  6021 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-05 10:28:18.468  6021  6021 D AndroidRuntime: Shutting down VM
,10-05 10:28:18.475  6021  6021 E AndroidRuntime: FATAL EXCEPTION: main
10-05 10:28:18.475  6021  6021 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6021
10-05 10:28:18.475  6021  6021 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-05 10:28:18.475  6021  6021 E AndroidRuntime: 	... 10 more
10-05 10:28:18.478   930   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-05 10:28:18.479   930  6033 E DropBoxManagerService: Can't write: system_app_crash
10-05 10:28:18.479   930  6033 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 10:28:18.479   930  6033 E DropBoxManagerService: 	... 5 more
10-05 10:28:18.479  6021  6021 I Process : Sending signal. PID: 6021 SIG: 9
,10-05 10:28:18.495   930  3079 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6021) has died
10-05 10:28:18.497   930  3079 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-05 10:28:18.512   930   943 I ActivityManager: Start proc 6034:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-05 10:28:18.547   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
