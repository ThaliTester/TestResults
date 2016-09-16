#### Test 852025185ed7d1b_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of system
09-16 08:28:31.669   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-16 08:28:32.899  5414  5414 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 08:28:32.905  5414  5414 D AndroidRuntime: CheckJNI is OFF
09-16 08:28:32.937  5414  5414 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 08:28:32.973  5414  5414 I Radio-JNI: register_android_hardware_Radio DONE
09-16 08:28:32.989  5414  5414 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-16 08:28:32.992   927  3410 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-16 08:28:33.032   927  3410 I ActivityManager: Start proc 5423:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-16 08:28:33.037  5414  5414 D AndroidRuntime: Shutting down VM
,09-16 08:28:33.375   927  3489 I WindowManager: Screenshot max retries 4 of Token{b58d0df ActivityRecord{165c37e u0 com.test.thalitest/.MainActivity t4}} appWin=Window{64cc456 u0 Starting com.test.thalitest} drawState=2
,09-16 08:28:33.440  5423  5423 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-16 08:28:33.475  5423  5423 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-16 08:28:33.498  5423  5423 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 7583-7602)
,09-16 08:28:33.498  5423  5423 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-16 08:28:33.520  5423  5423 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d84404b}
,09-16 08:28:33.520  5423  5423 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-16 08:28:33.520  5423  5423 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-16 08:28:33.526  5423  5423 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-16 08:28:33.527  5423  5423 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-16 08:28:33.562  5423  5423 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-16 08:28:33.582  5423  5423 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-16 08:28:33.582  5423  5423 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 08:28:33.582  5423  5423 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-16 08:28:33.582  5423  5423 I Adreno  : Build Date                       : 12/06/15
09-16 08:28:33.582  5423  5423 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-16 08:28:33.582  5423  5423 I Adreno  : Local Branch                     : mybranch17112971
09-16 08:28:33.582  5423  5423 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-16 08:28:33.582  5423  5423 I Adreno  : Remote Branch                    : NONE
09-16 08:28:33.582  5423  5423 I Adreno  : Reconstruct Branch               : NOTHING
,09-16 08:28:33.623   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@269b865:true
,09-16 08:28:33.653   702   702 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32972]" dev="sockfs" ino=32972 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 08:28:33.653   702   702 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32972]" dev="sockfs" ino=32972 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 08:28:33.667  5423  5423 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-16 08:28:33.675  5423  5423 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-16 08:28:33.693   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[28172]" dev="sockfs" ino=28172 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 08:28:33.699  5423  5460 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-16 08:28:33.693   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[28172]" dev="sockfs" ino=28172 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 08:28:33.696  3089  3089 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32983]" dev="sockfs" ino=32983 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-16 08:28:33.696  3089  3089 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32983]" dev="sockfs" ino=32983 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-16 08:28:33.705  5423  5447 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-16 08:28:33.725  5423  5460 I OpenGLRenderer: Initialized EGL, version 1.4
,09-16 08:28:33.789   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +411ms (total +781ms)
,09-16 08:28:33.827  5423  5423 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5423
,09-16 08:28:33.881  5423  5423 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-16 08:28:33.989  5423  5462 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -561252048
,09-16 08:28:33.994  5423  5462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 08:28:33.994  5423  5462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 08:28:33.994  5423  5462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 08:28:33.994  5423  5462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 08:28:33.994  5423  5462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-16 08:28:33.994  5423  5462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@daa4300 added. We now have 1 listener(s)
,09-16 08:28:33.996  5423  5462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-16 08:28:33.997  5423  5462 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:28:33.997  5423  5462 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 08:28:33.997  5423  5462 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-16 08:28:33.999  5423  5462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9986df added. We now have 1 listener(s)
09-16 08:28:33.999  5423  5462 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:28:34.003   927  2911 D WifiService: New client listening to asynchronous messages
,09-16 08:28:34.003  5423  5462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 08:28:34.003  5423  5462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 08:28:34.003  5423  5462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 08:28:34.003  5423  5462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 08:28:34.003  5423  5462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-16 08:28:34.008  5423  5462 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:28:34.008  5423  5462 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-16 08:28:34.012  5423  5462 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-16 08:28:34.012  5423  5462 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:28:34.012  5423  5462 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:28:34.012  5423  5462 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:28:34.012  5423  5462 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:28:34.012  5423  5462 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:28:34.012  5423  5462 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:28:34.012  5423  5462 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:28:34.012  5423  5462 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:28:34.012  5423  5462 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-16 08:28:34.012  5423  5462 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:28:34.013  5423  5462 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 08:28:34.016  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:28:34.018  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:28:34.031  5423  5423 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-16 08:28:34.313  5423  5469 W jxcore-log: Initializing JXcore engine
09-16 08:28:34.313  5423  5469 W jxcore-log: JXcore engine is ready
,09-16 08:28:34.333  5469  5469 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11005 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-16 08:28:34.333  5469  5469 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12608]" dev="sockfs" ino=12608 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-16 08:28:34.333  5469  5469 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4965 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 08:28:34.333  5469  5469 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[28149]" dev="sockfs" ino=28149 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-16 08:28:34.343  5423  5469 W jxcore-log: Starting JXcore engine
,09-16 08:28:34.391  5423  5469 W jxcore-log: Platform android
09-16 08:28:34.391  5423  5469 W jxcore-log: 
,09-16 08:28:34.391  5423  5469 W jxcore-log: Process ARCH arm
09-16 08:28:34.391  5423  5469 W jxcore-log: 
,09-16 08:28:34.489  5423  5469 I jxcore-log: JXcore Cordova bridge is ready!
09-16 08:28:34.489  5423  5469 I jxcore-log: 
,09-16 08:28:34.489  5423  5469 W jxcore-log: JXcore engine is started
,09-16 08:28:34.496  5423  5462 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 08:28:34.502  5423  5423 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 08:28:34.686   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 08:28:37.287   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:28:39.616   927  5101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=343720, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-16 08:28:40.452   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:41.453   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:42.454   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:43.456   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:44.280  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 08:28:44.280  5423  5469 I jxcore-log: 
,09-16 08:28:44.283  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 08:28:44.283  5423  5469 I jxcore-log: 
,09-16 08:28:44.288  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:28:44.288  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:28:44.288  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:28:44.288  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:28:44.288  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:28:44.288  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:28:44.288  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:28:44.288  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:28:44.290  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:28:44.291  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 08:28:44.291  5423  5469 I jxcore-log: 
,09-16 08:28:44.292  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 08:28:44.292  5423  5469 I jxcore-log: 
,09-16 08:28:44.457   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:44.536  5423  5469 I jxcore-log: Running unit tests
09-16 08:28:44.536  5423  5469 I jxcore-log: 
,09-16 08:28:44.537  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 08:28:44.537  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd54db9 added. We now have 2 listener(s)
09-16 08:28:44.538  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:28:44.538  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 08:28:44.538  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 08:28:44.538  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:28:44.538  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196a5fe added. We now have 2 listener(s)
09-16 08:28:44.538  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 08:28:44.539  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 08:28:44.541  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:28:44.544  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:28:44.544  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:28:44.544  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:28:44.544  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:28:44.544  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:28:44.544  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:28:44.544  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:28:44.544  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 08:28:44.545  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:28:44.545  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:28:44.545  5423  5469 D executeNativeTests: Running unit tests
,09-16 08:28:44.552  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:28:44.559  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:28:44.582  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 08:28:44.582  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc added. We now have 3 listener(s)
09-16 08:28:44.583  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 08:28:44.583  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 08:28:44.583  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 08:28:44.583  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:28:44.583  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 added. We now have 3 listener(s)
09-16 08:28:44.583  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 08:28:44.583  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 08:28:44.585  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:28:44.587  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:28:44.587  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:28:44.587  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:28:44.587  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:28:44.587  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:28:44.587  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:28:44.587  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:28:44.587  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:28:44.588  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:28:44.588  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:28:44.589  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-16 08:28:44.589  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 08:28:44.589  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-16 08:28:44.589  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 08:28:44.590  5423  5469 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-16 08:28:44.590  5423  5469 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-16 08:28:44.590  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 08:28:44.590  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 08:28:44.590  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 08:28:44.590  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
,09-16 08:28:44.590  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:28:44.591  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:28:44.591  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:28:44.591  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:28:44.591  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:44.591  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:28:44.592  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-16 08:28:44.592  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc removed from the list
09-16 08:28:44.592  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:28:44.592  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 removed from the list
09-16 08:28:44.593  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:28:44.600  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:28:44.600  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:28:44.600  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:28:44.601  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:44.601  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:28:44.601  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:28:44.601  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:28:44.601  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:28:44.601  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:28:44.602  5423  5469 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-16 08:28:44.602  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:28:44.602  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:28:44.603  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:28:44.603  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:28:44.603  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:28:44.603  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:28:44.603  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:28:44.603  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:28:44.603  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:28:44.603  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:28:44.603  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:44.603  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:28:44.603  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:44.603  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:28:44.603  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:28:44.603  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:28:44.604  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:28:44.604  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 08:28:44.606  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 08:28:44.607  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:28:44.607  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:28:44.607  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:28:44.607  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:28:44.607  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:44.607  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:28:44.607  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:28:44.607  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 08:28:44.607  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:28:44.607  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:28:44.607  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:44.607  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:28:44.607  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:44.607  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:28:44.608  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:28:44.608  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 08:28:44.608  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:28:44.608  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:28:44.608  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 08:28:44.609  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:28:44.611  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:28:44.611  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:28:44.611  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:28:44.611  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:28:44.611  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:28:44.611  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:28:44.611  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:28:44.611  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 08:28:44.612  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 08:28:44.612  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:28:44.612  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:28:44.612  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 08:28:44.612  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 08:28:44.612  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:28:44.612  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 08:28:44.614  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:28:44.615  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:28:44.616  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 08:28:44.616  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 08:28:44.618  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 08:28:44.619  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:28:44.619  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 08:28:44.620  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-16 08:28:44.622  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persi,stent storage
09-16 08:28:44.622  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 08:28:44.622  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 08:28:44.622  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 08:28:44.623  5423  5469 D BluetoothAdapter: STATE_ON
09-16 08:28:44.627  4389  4612 D BtGatt.GattService: registerClient() - UUID=3ad7fa78-84c7-417e-9c5b-27dbf92d674f
09-16 08:28:44.628  4389  4471 D BtGatt.GattService: onClientRegistered() - UUID=3ad7fa78-84c7-417e-9c5b-27dbf92d674f, clientIf=5
09-16 08:28:44.629  5423  5434 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 08:28:44.630  4389  4402 D BtGatt.GattService: start scan with filters
09-16 08:28:44.634  4389  4479 D BtGatt.ScanManager: handling starting scan
09-16 08:28:44.634  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 08:28:44.634  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 08:28:44.635  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 08:28:44.635  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 08:28:44.636  4389  4479 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:28:44.636  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:28:44.636  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 08:28:44.636  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:28:44.636  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 08:28:44.637  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
09-16 08:28:44.644  4389  4471 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 08:28:44.644  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:44.644  4389  4479 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 08:28:44.650  4389  4471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 08:28:44.650  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:44.651  4389  4479 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:28:44.651  4389  4479 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 08:28:44.661  4389  4471 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 08:28:44.661  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:28:44.667  4389  4471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 08:28:44.667  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:28:45.138  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 08:28:45.138  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:28:45.138  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:28:45.457   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:28:46.767   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 08:28:49.641  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:28:49.642  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 08:28:49.642  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 08:28:49.642  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:28:49.642  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 08:28:49.642  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:28:49.642  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 08:28:49.642  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 08:28:49.642  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-16 08:28:49.643  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 08:28:49.648  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 08:28:49.649  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:28:49.650  4389  4612 D BtGatt.GattService: stopScan() - queue size =1
,09-16 08:28:49.651  4389  4402 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 08:28:49.653  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 08:28:49.653  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 08:28:49.653  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 08:28:49.653  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 08:28:49.653  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 08:28:49.655  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 08:28:49.655  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 08:28:49.655  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 08:28:49.656  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 08:28:49.656  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 08:28:49.659  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:28:49.659  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:28:49.659  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:49.659  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 08:28:49.659  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:28:49.659  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:28:49.660  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:28:49.660  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:28:49.660  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
,09-16 08:28:49.660  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:28:49.660  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:28:49.660  4389  4389 D BtGatt.ScanManager: awakened up at time 353764
09-16 08:28:49.668  4389  4471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 08:28:49.668  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:49.669  4389  4479 D BtGatt.ScanManager: stopping BLe Batch
,09-16 08:28:49.679  4389  4471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 08:28:49.679  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:49.680  4389  4479 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:28:49.703  4389  4471 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-16 08:28:49.703  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:49.704  4389  4471 D BtGatt.GattService: current time is 353807846431
09-16 08:28:49.704  4389  4471 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -81, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 08:28:49.706  4389  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 08:28:49.707  4389  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 08:28:49.708  4389  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-16 08:28:49.709  4389  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-16 08:28:49.797   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 08:28:49.801   927  2912 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-16 08:28:50.161  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:28:50.459   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:51.460   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:52.462   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:52.829   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-16 08:28:52.832   927  2912 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-16 08:28:53.463   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:54.465   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:28:54.662  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 08:28:54.668  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:28:54.681  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:28:54.681  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:28:54.681  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:28:54.681  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:28:54.681  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:28:54.681  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:28:54.681  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:28:54.681  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:28:54.685  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:28:54.686  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:28:54.686  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:28:54.686  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 08:28:54.687  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-16 08:28:54.687  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:28:54.687  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 08:28:54.692  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:28:54.695  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 08:28:54.695  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 08:28:54.699  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:28:54.705  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 08:28:54.706  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:28:54.706  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 08:28:54.712  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 08:28:54.712  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 08:28:54.712  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 08:28:54.713  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:28:54.718  4389  4612 D BtGatt.GattService: registerClient() - UUID=ce54a077-8dec-4d56-b202-ee3f4fe4fc46
,09-16 08:28:54.719  4389  4471 D BtGatt.GattService: onClientRegistered() - UUID=ce54a077-8dec-4d56-b202-ee3f4fe4fc46, clientIf=5
,09-16 08:28:54.720  5423  5433 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 08:28:54.720  4389  4402 D BtGatt.GattService: start scan with filters
,09-16 08:28:54.724  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 08:28:54.724  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-16 08:28:54.724  4389  4479 D BtGatt.ScanManager: handling starting scan
09-16 08:28:54.724  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 08:28:54.724  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 08:28:54.728  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:28:54.728  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 08:28:54.728  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:28:54.730  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 08:28:54.734  4389  4471 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-16 08:28:54.734  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
09-16 08:28:54.734  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:54.735  4389  4479 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 08:28:54.738  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:28:54.738  5423  5469 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 08:28:54.738  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 08:28:54.738  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 08:28:54.738  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:54.738  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 08:28:54.738  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:28:54.738  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 08:28:54.738  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 08:28:54.738  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 08:28:54.739  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 08:28:54.739  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 08:28:54.740  5423  5469 D BluetoothAdapter: STATE_ON
09-16 08:28:54.741  4389  4612 D BtGatt.GattService: stopScan() - queue size =1
09-16 08:28:54.741  4389  4402 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 08:28:54.742  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 08:28:54.742  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 08:28:54.742  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 08:28:54.742  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 08:28:54.742  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 08:28:54.743  4389  4471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 08:28:54.743  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:54.743  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:28:54.743  4389  4479 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:28:54.744  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 08:28:54.744  4389  4479 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-16 08:28:54.744  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 08:28:54.744  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 08:28:54.744  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:28:54.746  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:28:54.746  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:28:54.746  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:28:54.746  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:28:54.746  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:28:54.746  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:28:54.746  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:28:54.746  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:28:54.746  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:28:54.746  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:28:54.746  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:28:54.747  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:54.747  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:28:54.748  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 08:28:54.748  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:28:54.748  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:28:54.748  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
,09-16 08:28:54.749  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 08:28:54.751  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:28:54.757  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:28:54.757  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:28:54.757  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:28:54.757  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:28:54.757  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:28:54.757  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:28:54.757  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:28:54.757  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:28:54.758  4389  4471 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 08:28:54.758  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:54.759  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 08:28:54.760  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:28:54.760  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:28:54.760  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 08:28:54.760  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 08:28:54.760  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:28:54.760  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 08:28:54.764  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:28:54.764  4389  4471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 08:28:54.764  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 08:28:54.764  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 08:28:54.764  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:28:54.768  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:28:54.769  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 08:28:54.770  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 08:28:54.770  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 08:28:54.773  4389  4471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 08:28:54.773  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:54.773  4389  4479 D BtGatt.ScanManager: stopping BLe Batch
,09-16 08:28:54.776  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 08:28:54.777  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 08:28:54.777  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 08:28:54.777  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:28:54.779  4389  4471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 08:28:54.779  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:54.779  4389  4479 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:28:54.781  4389  4404 D BtGatt.GattService: registerClient() - UUID=ce75a1db-08e2-4028-b84e-80c707004d51
,09-16 08:28:54.783  4389  4471 D BtGatt.GattService: onClientRegistered() - UUID=ce75a1db-08e2-4028-b84e-80c707004d51, clientIf=5
,09-16 08:28:54.784  5423  5433 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 08:28:54.784  4389  4402 D BtGatt.GattService: start scan with filters
09-16 08:28:54.785  4389  4471 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:28:54.785  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:28:54.787  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 08:28:54.787  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 08:28:54.787  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 08:28:54.787  4389  4479 D BtGatt.ScanManager: handling starting scan
09-16 08:28:54.787  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 08:28:54.790  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:28:54.790  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 08:28:54.790  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:28:54.791  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 08:28:54.793  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 08:28:54.793  4389  4471 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 08:28:54.794  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:54.794  4389  4479 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 08:28:54.799  4389  4471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 08:28:54.799  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:54.799  4389  4479 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:28:54.799  4389  4479 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 08:28:54.808  4389  4471 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 08:28:54.808  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:28:54.814  4389  4471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 08:28:54.814  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:28:55.291  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 08:28:55.292  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:28:55.292  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:28:55.466   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:28:55.851   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 08:28:55.856   927  2912 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-16 08:28:58.864   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 08:28:58.873   927  2912 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-16 08:28:59.794  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:28:59.794  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 08:28:59.794  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 08:28:59.795  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:28:59.795  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 08:28:59.795  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-16 08:28:59.795  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 08:28:59.795  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 08:28:59.795  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-16 08:28:59.796  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 08:28:59.796  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 08:28:59.798  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:28:59.801  4389  4404 D BtGatt.GattService: stopScan() - queue size =1
09-16 08:28:59.804  4389  4612 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 08:28:59.804  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 08:28:59.805  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 08:28:59.805  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 08:28:59.805  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 08:28:59.805  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-16 08:28:59.808  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 08:28:59.809  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 08:28:59.809  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 08:28:59.809  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 08:28:59.809  4389  4389 D BtGatt.ScanManager: awakened up at time 363913
09-16 08:28:59.811  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 08:28:59.815  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:28:59.815  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:28:59.815  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:28:59.817  4389  4471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 08:28:59.818  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:59.818  4389  4479 D BtGatt.ScanManager: stopping BLe Batch
,09-16 08:28:59.825  4389  4471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 08:28:59.825  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:59.825  4389  4479 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:28:59.843  4389  4471 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-16 08:28:59.843  4389  4471 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:28:59.843  4389  4471 D BtGatt.GattService: current time is 363947223175
09-16 08:28:59.843  4389  4471 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -92, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -78, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -86, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-16 08:28:59.844  4389  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 08:28:59.844  4389  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 08:28:59.844  4389  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 08:28:59.844  4389  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 08:28:59.844  4389  4471 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-16 08:29:00.316  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:29:00.316  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:00.317  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:29:04.816  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:29:04.816  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:29:04.817  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:29:04.817  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:04.817  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.817  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:29:04.817  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.818  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 08:29:04.818  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.818  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.818  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:04.820  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.820  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.825  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 08:29:04.825  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.825  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.826  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.828  5423  5469 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-16 08:29:04.831  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:29:04.832  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:04.832  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:29:04.834  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 08:29:04.834  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.834  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.834  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.835  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.835  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.835  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.835  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.835  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.835  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.835  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:04.836  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:04.837  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.837  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.837  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.838  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 08:29:04.838  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:04.838  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:04.838  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:04.838  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 08:29:04.838  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.839  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.839  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.839  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.839  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.839  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.839  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.839  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.839  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.839  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:04.841  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:04.841  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.841  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.841  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.842  5423  5469 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-16 08:29:04.842  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:04.842  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:04.842  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:04.842  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 08:29:04.842  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.842  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.842  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.843  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.843  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.843  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.843  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.843  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.843  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.843  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:04.844  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:04.844  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.844  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.845  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.845  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-16 08:29:04.846  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:04.846  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:04.846  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:04.846  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:04.846  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:29:04.846  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.846  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.846  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.846  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.846  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.847  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.847  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.847  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.847  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:04.848  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:04.848  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.848  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.849  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.850  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 08:29:04.850  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 08:29:04.850  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 08:29:04.850  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 08:29:04.850  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 08:29:04.850  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-16 08:29:04.850  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 08:29:04.850  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 08:29:04.850  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 08:29:04.851  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:04.851  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:04.851  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:04.851  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:04.851  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.851  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.851  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.851  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 08:29:04.851  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.851  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.851  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.851  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.851  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.852  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:04.853  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:04.853  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.853  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.853  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.854  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 08:29:04.854  5423  5469 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 08:29:04.855  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-16 08:29:04.858  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 08:29:04.858  5423  5469 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-16 08:29:04.858  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 08:29:04.858  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 08:29:04.858  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 08:29:04.858  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 08:29:04.858  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 08:29:04.858  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 08:29:04.859  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 08:29:04.860  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
09-16 08:29:04.860  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 08:29:04.860  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 08:29:04.860  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 08:29:04.860  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 08:29:04.860  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 08:29:04.860  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-16 08:29:04.860  5423  5469 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 08:29:04.860  5423  5469 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-16 08:29:04.860  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 08:29:04.860  5423  5469 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 08:29:04.861  5423  5469 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-16 08:29:04.861  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 08:29:04.861  5423  5469 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 08:29:04.861  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-16 08:29:04.864  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-16 08:29:04.865  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 08:29:04.865  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 08:29:04.866  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-16 08:29:04.866  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-16 08:29:04.866  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-16 08:29:04.866  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 08:29:04.866  5423  5469 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-16 08:29:04.867  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:04.868  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:04.868  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:04.868  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:04.868  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.868  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.868  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-16 08:29:04.868  5423  5471 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-16 08:29:04.869  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.869  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.869  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.869  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.869  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.869  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.869  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.869  5423  5472 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-16 08:29:04.869  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.871  5423  5471 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 08:29:04.871  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:04.871  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.871  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.871  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.870  4402  4402 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28196]" dev="sockfs" ino=28196 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:29:04.872  5423  5469 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-16 08:29:04.873  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:04.873  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:04.873  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:04.873  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:04.873  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.873  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.873  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.873  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.873  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.873  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.873  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.873  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.870  4402  4402 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28196]" dev="sockfs" ino=28196 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:29:04.873  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.873  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.875  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:04.875  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.875  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.875  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.876  5423  5469 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-16 08:29:04.876  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:04.877  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:04.877  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:04.877  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:04.877  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.877  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.877  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.877  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.877  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.877  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.877  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.877  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.877  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.877  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.878  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:04.878  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.878  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.878  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.879  5423  5469 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-16 08:29:04.880  5423  5469 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-16 08:29:04.880  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 08:29:04.880  5423  5469 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-16 08:29:04.880  5423  5469 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 08:29:04.880  5423  5469 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-16 08:29:04.880  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 08:29:04.880  5423  5469 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-16 08:29:04.880  5423  5469 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 08:29:04.880  5423  5469 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 08:29:04.880  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 08:29:04.880  5423  5469 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-16 08:29:04.880  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:04.880  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:04.880  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:04.881  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:04.881  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.881  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.881  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.881  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.881  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.881  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.881  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.881  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.881  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.881  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.882  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:04.882  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:04.882  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.882  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.883  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:04.883  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.883  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:04.883  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:04.883  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:04.883  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:04.884  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:04.884  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:04.884  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:05.467   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:06.469   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:07.470   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:08.471   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:09.472   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:09.884  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 08:29:09.885  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:09.885  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 08:29:09.885  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.885  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.886  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
,09-16 08:29:09.886  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:29:09.886  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:09.886  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:29:09.887  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:09.887  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.887  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.887  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
,09-16 08:29:09.887  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.887  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:09.887  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:09.888  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.888  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.888  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.888  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.891  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:09.892  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 08:29:09.892  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.892  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
,09-16 08:29:09.898  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 08:29:09.899  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:29:09.901  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-16 08:29:09.903  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-16 08:29:09.903  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 08:29:09.904  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 08:29:09.904  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:29:09.904  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-16 08:29:09.904  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:09.905  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 08:29:09.905  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 08:29:09.905  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 08:29:09.905  5423  5473 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 08:29:09.905  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.905  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-16 08:29:09.905  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:09.905  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.905  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 08:29:09.905  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 08:29:09.905  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 08:29:09.905  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 08:29:09.905  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.905  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.907  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:29:09.907  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:09.907  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:29:09.907  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:29:09.907  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:09.907  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 08:29:09.907  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:09.907  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:09.907  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:09.907  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.907  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.907  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:09.908  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.908  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:09.908  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:09.908  5423  5473 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 08:29:09.908  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.908  5423  5473 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-16 08:29:09.908  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.908  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.908  5423  5473 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 08:29:09.908  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.908  5423  5423 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 08:29:09.909  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:09.903  4612  4612 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29444]" dev="sockfs" ino=29444 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:29:09.910  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:09.910  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.903  4612  4612 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29444]" dev="sockfs" ino=29444 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:29:09.910  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:09.911  5423  5469 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-16 08:29:09.911  5423  5469 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-16 08:29:09.912  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 08:29:09.912  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 08:29:09.912  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 08:29:09.912  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:29:09.912  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:09.912  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:09.912  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:09.912  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.912  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.912  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:09.913  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.913  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:09.913  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:09.913  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.913  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.913  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.913  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:09.915  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 08:29:09.915  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:09.915  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.915  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
,09-16 08:29:09.921  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:29:09.921  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:09.921  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:09.921  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:09.922  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.922  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.922  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:09.922  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.922  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:09.922  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:09.922  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.922  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.922  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.922  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:09.925  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:09.925  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:09.925  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.925  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
,09-16 08:29:09.926  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:29:09.926  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:29:09.926  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:29:09.927  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:29:09.927  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.927  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.927  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943a3dc not in the list
09-16 08:29:09.927  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.927  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:09.927  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:09.927  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.927  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:09.927  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:09.927  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:09.928  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:29:09.928  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:29:09.928  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:09.929  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e1fce5 not in the list
09-16 08:29:09.930  5423  5469 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-16 08:29:09.930  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 08:29:09.930  5423  5469 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-16 08:29:09.930  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 08:29:09.930  5423  5469 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-16 08:29:09.930  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 08:29:09.932  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 08:29:09.932  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-16 08:29:09.932  5423  5469 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-16 08:29:09.932  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 08:29:09.932  5423  5469 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-16 08:29:09.932  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 08:29:09.932  5423  5469 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-16 08:29:09.932  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-16 08:29:09.933  5423  5469 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-16 08:29:09.933  5423  5469 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-16 08:29:09.934  5423  5469 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-16 08:29:09.934  5423  5469 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-16 08:29:09.934  5423  5469 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-16 08:29:09.934  5423  5469 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-16 08:29:09.937  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:29:09.937  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a5db3f added. We now have 3 listener(s)
09-16 08:29:09.937  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:29:09.939  5423  5469 D BluetoothAdapter: enable(): BT is already enabled..!
,09-16 08:29:09.940   927   937 D WifiService: setWifiEnabled: true pid=5423, uid=10077
09-16 08:29:09.940   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 08:29:09.999  4389  4594 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-16 08:29:10.000  4389  4610 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-16 08:29:10.000  5423  5471 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,09-16 08:29:10.408  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:29:10.472   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:29:14.404   927  5101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=378507, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:29:14.946  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 08:29:14.946  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c25bc0c added. We now have 4 listener(s)
,09-16 08:29:14.946  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:29:14.960  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:14.961  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c25bc0c removed from the list
09-16 08:29:14.961  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:14.961  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:14.961  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:14.964  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 08:29:14.965  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a4e955 added. We now have 4 listener(s)
09-16 08:29:14.965  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:29:14.967  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:14.967  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a4e955 removed from the list
,09-16 08:29:14.967  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 08:29:14.968  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:14.968  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:14.969  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:29:14.969  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a0d6f6a added. We now have 4 listener(s)
09-16 08:29:14.970  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 08:29:14.972   927  3493 D WifiService: setWifiEnabled: false pid=5423, uid=10077
09-16 08:29:14.972   927  3493 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-16 08:29:14.975   927  2910 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-16 08:29:14.976   927  2910 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-16 08:29:14.976   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 08:29:14.976   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 08:29:14.982  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:29:14.984  4389  4462 D BluetoothAdapterState: Current state: ON, message: 23
,09-16 08:29:14.984  4389  4462 D BluetoothAdapterProperties: Setting state to 13
09-16 08:29:14.984  4389  4462 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 08:29:14.986  4389  4462 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 08:29:14.988  4389  4462 I BluetoothAdapterState: Entering PendingCommandState
,09-16 08:29:14.989  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:14.989  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:29:14.989  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:14.989  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:14.989  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:14.989  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:14.989  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:29:14.989  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:29:14.989  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 08:29:14.990  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:14.991  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 08:29:14.991  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 08:29:14.993  4389  4389 D BluetoothMapService: onReceive
09-16 08:29:14.993  4389  4389 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 08:29:14.993  4389  4389 D BluetoothMapService: STATE_TURNING_OFF
09-16 08:29:14.993  4389  4471 D BluetoothAdapterProperties: Scan Mode:20
09-16 08:29:14.993  4389  4389 D BluetoothMapService: MAP Service closeService in
09-16 08:29:14.993  4389  4389 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 08:29:14.993  4389  4389 D ObexServerSockets0: shutdown(block = true)
09-16 08:29:14.994  4389  4389 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 08:29:14.994  4389  4389 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 08:29:14.994  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:14.995  4389  4648 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 08:29:14.995  4389  4647 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-16 08:29:14.995  4389  4610 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-16 08:29:14.995   927  5102 D DhcpClient: Clearing IP address
09-16 08:29:14.996   506   926 D CommandListener: Clearing all IP addresses on wlan0
09-16 08:29:14.996  4389  4389 I BtOppRfcommListener: stopping Accept Thread
09-16 08:29:14.997  4389  5056 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 08:29:14.997  4389  5056 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-16 08:29:14.998  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:15.000  4389  4462 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-16 08:29:15.003  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.003  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:15.003  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:15.003  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:15.003  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:15.003  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:15.003  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:29:15.003  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:29:15.003  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 08:29:15.003   506   926 D CommandListener: Setting iface cfg
09-16 08:29:15.004  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.004  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 08:29:15.007  3528  5155 V NativeCrypto: Read error: ssl=0x7f7e647000: I/O error during system call, Connection timed out
09-16 08:29:15.007   927  5103 D DhcpClient: Receive thread stopped
09-16 08:29:15.008  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:15.009  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:15.009  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:15.009  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:15.009  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:15.009  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:15.009  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:29:15.009  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:29:15.009  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 08:29:15.009  3528  5155 V NativeCrypto: SSL shutdown failed: ssl=0x7f7e647000: I/O error during system call, Broken pipe
09-16 08:29:15.009  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.009  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 08:29:15.011   927  3482 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-16 08:29:15.011   927  5100 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-16 08:29:15.012   927   940 I ActivityManager: Start proc 5477:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-16 08:29:15.013  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:15.013   927  5100 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-16 08:29:15.014   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-16 08:29:15.014   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-16 08:29:15.016   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-16 08:29:15.017  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:15.020  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:15.021  4389  4389 D HeadsetService: Received stop request...Stopping profile...
09-16 08:29:15.022   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:15.023   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:15.023   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:15.023  3064  3681 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:15.023  4389  4389 D A2dpService: Received stop request...Stopping profile...
09-16 08:29:15.024  3470  3484 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:15.024  4389  4627 D A2dpStateMachine: Exit Disconnected: -1
09-16 08:29:15.025  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:15.026   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-16 08:29:15.027   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-16 08:29:15.027   532   532 E Parcel  : Reading a NULL string not supported here.
09-16 08:29:15.028  4389  4389 D HidService: Received stop request...Stopping profile...
09-16 08:29:15.028  4389  4389 D HidService: Stopping Bluetooth HidService
09-16 08:29:15.028   927   927 D BluetoothA2dp: Proxy object disconnected
09-16 08:29:15.029  3064  3064 D HeadsetProfile: Bluetooth service disconnected
09-16 08:29:15.030  3064  3064 D BluetoothA2dp: Proxy object disconnected
09-16 08:29:15.030  4389  4389 D HealthService: Received stop request...Stopping profile...
09-16 08:29:15.030  3064  3064 D BluetoothInputDevice: Proxy object disconnected
09-16 08:29:15.030  3064  3064 D HidProfile: Bluetooth service disconnected
09-16 08:29:15.031   927   927 D RttService: SCAN_AVAILABLE : 1
,09-16 08:29:15.031   927  3018 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 08:29:15.032  4389  4389 D PanService: Received stop request...Stopping profile...
09-16 08:29:15.034  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-16 08:29:15.034  3064  3064 D PanProfile: Bluetooth service disconnected
09-16 08:29:15.034   927  2912 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-16 08:29:15.034  4389  4389 D BluetoothMapService: Received stop request...Stopping profile...
09-16 08:29:15.035  4389  4389 D BluetoothMapService: stop()
09-16 08:29:15.035  4389  4389 D BluetoothMapAppObserver: deinitObservers()
09-16 08:29:15.035  4389  4389 D BluetoothMapAppObserver: removeReceiver()
09-16 08:29:15.036  3413  3535 W QCNEJ   : |CORE| network lost: 100
09-16 08:29:15.037  3413  3535 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-16 08:29:15.038  4389  4389 D SapService: Received stop request...Stopping profile...
,09-16 08:29:15.039  4389  4389 V SapService: stop()
09-16 08:29:15.038  3064  3064 D BluetoothMap: Proxy object disconnected
09-16 08:29:15.039  3064  3064 D MapProfile: Bluetooth service disconnected
09-16 08:29:15.041  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:15.041  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:15.041  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:15.041  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:15.043  4389  4389 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 08:29:15.044  4389  4471 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 08:29:15.044  4389  4594 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 08:29:15.044  4389  4594 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 08:29:15.044  4389  4594 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 08:29:15.044  4389  4471 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-16 08:29:15.044  4389  4389 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 08:29:15.044  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:15.044  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:15.044  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:15.044  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:15.045  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:15.046  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:15.046  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:15.046  4389  4471 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 08:29:15.046  4389  4594 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-16 08:29:15.046  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:15.046  4389  4594 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 08:29:15.046  4389  4594 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 08:29:15.046  4389  4389 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 08:29:15.046  4389  4594 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 08:29:15.046  4389  4594 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 08:29:15.046  4389  4389 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 08:29:15.046  4389  4594 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 08:29:15.046  4389  4471 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 08:29:15.046  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:15.046  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:15.046  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:15.046  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:15.046  4389  4389 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 08:29:15.047  4389  4471 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-16 08:29:15.047  4389  4389 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 08:29:15.047  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:15.047  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:15.047  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 08:29:15.047  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:15.047  4389  4389 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 08:29:15.048  4389  4389 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 08:29:15.048  4389  4389 D BluetoothMapService: MAP Service closeService in
09-16 08:29:15.048  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:15.048  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:15.048  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 08:29:15.049  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:15.049  4389  4389 D BluetoothMapService: cleanup()
09-16 08:29:15.049  4389  4389 D BluetoothMapService: MAP Service closeService in
09-16 08:29:15.049  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:15.049  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:15.049  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:15.049  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:15.049  4389  4462 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-16 08:29:15.050  4389  4462 D BluetoothAdapterProperties: Setting state to 15
09-16 08:29:15.050  4389  4462 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 08:29:15.050  4389  4462 I BluetoothAdapterState: Entering BleOnState
09-16 08:29:15.050   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:15.050  3064  3080 D BluetoothPan: onBluetoothStateChange on: false
09-16 08:29:15.051   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:15.051  3064  3386 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 08:29:15.052  3064  3681 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 08:29:15.052   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:15.052  3064  3082 D BluetoothMap: onBluetoothStateChange: up=false
,09-16 08:29:15.053  3064  3080 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 08:29:15.054  3470  3484 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:15.054  3064  3386 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:15.054   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 08:29:15.054  4389  4462 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 08:29:15.054  4389  4462 D BluetoothAdapterProperties: Setting state to 16
09-16 08:29:15.055  4389  4462 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 08:29:15.055  4389  4462 D BluetoothAdapterProperties: onBleDisable
09-16 08:29:15.056  4389  4462 I BluetoothAdapterState: Entering PendingCommandState
09-16 08:29:15.056  4389  4463 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-16 08:29:15.058  4389  4594 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 08:29:15.058  4389  4594 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-16 08:29:15.058  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.058  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:15.058  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:15.058  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:15.058  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:15.058  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:15.058  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:15.058  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:15.058  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:15.059  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.059  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:15.060  4389  4471 D BluetoothAdapterProperties: Scan Mode:20
,09-16 08:29:15.068   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 08:29:15.071   927  2910 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 08:29:15.071   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 08:29:15.073  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:15.073  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:15.073  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:15.073  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:15.073  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:15.073  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:15.073  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:15.073  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:15.073  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 08:29:15.074  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:15.074  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:15.077  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.077  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:15.077  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:15.077  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:15.077  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:15.077  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:15.077  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:15.077  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:15.077  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:15.078  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.078  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:15.079  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:15.081  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:15.082  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:15.089  5477  5477 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-16 08:29:15.092   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 08:29:15.093   506   926 D CommandListener: Clearing all IP addresses on wlan0
,09-16 08:29:15.093   927  2912 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-16 08:29:15.094   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 08:29:15.095   927  2910 D DhcpClient: doQuit
09-16 08:29:15.096   927  2910 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 08:29:15.096   927   944 D Tethering: MasterInitialState.processMessage what=3
09-16 08:29:15.097  3565  3565 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-16 08:29:15.097   927  5102 D DhcpClient: onQuitting
,09-16 08:29:15.101  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:15.102  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:15.102  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:15.102  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:15.102  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:15.102  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:15.102  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:15.102  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:15.102  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:15.103  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.103  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 08:29:15.106  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.106  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:15.106  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:15.106  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:15.106  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:15.106  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:15.106  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:15.106  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:15.106  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 08:29:15.107  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:15.107  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:15.107  4810  4825 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 08:29:15.108  4810  4825 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 08:29:15.108  4810  4825 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-16 08:29:15.108  4810  4825 E SarControlService: no key has been found,reset the power
09-16 08:29:15.108  4810  4849 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 08:29:15.109  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.109  4810  4849 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 08:29:15.109  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:15.109  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:15.109  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:15.109  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:15.109  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:15.109  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:15.109  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:15.109  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 08:29:15.110  4810  4849 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 08:29:15.110  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:15.110  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:15.110  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 08:29:15.111  4839  4839 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 08:29:15.112  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:15.112  4810  4849 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 08:29:15.113  4810  4849 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 08:29:15.113  4810  4849 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 08:29:15.113  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:15.114  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 08:29:15.114  4839  4839 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 08:29:15.114  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:15.117  3565  3565 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-16 08:29:15.118  4839  4853 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e5bbfc5 HexData = [00000000ea03000000000000ffffffff]
09-16 08:29:15.118  4839  4853 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 08:29:15.118  4839  4853 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-16 08:29:15.118  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 08:29:15.118  4810  4822 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-16 08:29:15.119  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 08:29:15.121  4839  4853 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e5bbfc5 HexData = [00000000eb03000000000000ffffffff]
09-16 08:29:15.121  4839  4853 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-16 08:29:15.121  4839  4853 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-16 08:29:15.122  3565  3565 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-16 08:29:15.122  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 08:29:15.122  4810  4821 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-16 08:29:15.127   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@614c26d:true
,09-16 08:29:15.128  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 08:29:15.141   927  3493 I ActivityManager: Start proc 5498:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-16 08:29:15.151   506   926 E Netd    : netlink response contains error (No such file or directory)
,09-16 08:29:15.152   927  2912 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-16 08:29:15.148  3565  3565 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 08:29:15.155  5477  5477 D LocalBluetoothProfileManager: Adding local MAP profile
,09-16 08:29:15.158  5477  5477 D BluetoothMap: Create BluetoothMap proxy object
,09-16 08:29:15.163  3565  3565 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 08:29:15.168  5477  5477 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-16 08:29:15.183  5477  5477 D DockEventReceiver: finishStartingService: stopping service
,09-16 08:29:15.186  5498  5498 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-16 08:29:15.195   927   938 I ActivityManager: Killing 5142:com.android.chrome/u0a39 (adj 15): empty #17
,09-16 08:29:15.264  4389  4471 I bt_hci  : shut_down
,09-16 08:29:15.265   927  2910 D wifi    : In wifi stop Hal
,09-16 08:29:15.265   927  2910 D wifi    : halHandle = 0x7f7d55b040, mVM = 0x7f99b8d140, mCls = 0x100b8e
09-16 08:29:15.265   927  3559 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 08:29:15.265   927  3559 D WifiHAL : Got a signal to exit!!!
,09-16 08:29:15.265   927  3559 I WifiHAL : Exit wifi_event_loop
09-16 08:29:15.266  4235  4235 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 08:29:15.267   927  2910 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-16 08:29:15.267   927  2910 E WifiHAL : Event processing terminated
09-16 08:29:15.267   927  2910 D wifi    : In wifi cleaned up handler
09-16 08:29:15.267   927  2910 I WifiHAL : Internal cleanup completed
09-16 08:29:15.267  4389  4480 D bt_hwcfg: hw_epilog_process
09-16 08:29:15.267  3551  3978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 08:29:15.268  4389  4480 I bt_vendor: low_power_mode_cb
09-16 08:29:15.269  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:15.271  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:15.271  4389  4480 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-16 08:29:15.271  4389  4480 I bt_vendor: epilog_cb
09-16 08:29:15.271  4389  4480 I bt_hci  : epilog_finished_callback
09-16 08:29:15.272  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:15.273  4389  4471 I bt_hci_h4: hal_close
09-16 08:29:15.273  4389  4471 I bt_userial_vendor: device fd = 54 close
,09-16 08:29:15.290   927  3559 D wifi    : set interface wlan0 flags (DOWN)
,09-16 08:29:15.290   927  2910 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 08:29:15.351   506   926 E Netd    : netlink response contains error (No such file or directory)
,09-16 08:29:15.380  4389  4463 D bt_stack_manager: event_shut_down_stack finished.
,09-16 08:29:15.380  4389  4462 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-16 08:29:15.381  4389  4462 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-16 08:29:15.381  4389  4389 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 08:29:15.382  4389  4389 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 08:29:15.382  4389  4389 D BtGatt.GattService: stop()
09-16 08:29:15.382  4389  4389 D BtGatt.AdvertiseManager: advertise clients cleared
,09-16 08:29:15.383  4389  4389 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:15.383  4389  4389 V BluetoothAdapterState: isTurningOn()=false
,09-16 08:29:15.383  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 08:29:15.383  4389  4389 V BluetoothAdapterState: isBleTurningOff()=true
09-16 08:29:15.383  4389  4462 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-16 08:29:15.384  4389  4462 D BluetoothAdapterProperties: Setting state to 10
09-16 08:29:15.384  4389  4462 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 08:29:15.384  4389  4462 I BluetoothAdapterState: Entering OffState
,09-16 08:29:15.385   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-16 08:29:15.390  4389  4389 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-16 08:29:15.390  4389  4389 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 08:29:15.391  4389  4389 I BluetoothServiceJni: cleanupNative: return from cleanup
09-16 08:29:15.392  4389  4463 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 08:29:15.399  4389  4389 I art     : System.exit called, status: 0
,09-16 08:29:15.400  4389  4389 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 08:29:15.418  5498  5498 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:29:15.418  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-16 08:29:15.419  5498  5498 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:29:15.419  5498  5498 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:29:15.419  5498  5498 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:29:15.419  5498  5498 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.k.d(PG:583)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:29:15.419  5498  5498 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:29:15.419  5498  5498 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:29:15.419  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:29:15.429  5498  5498 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 08:29:15.429  5498  5498 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:29:15.429  5498  5498 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:29:15.434  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 08:29:15.436   927  3482 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-16 08:29:15.437   927  3482 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-16 08:29:15.437   927  3482 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-16 08:29:15.437   927  3482 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-16 08:29:15.437   927  3482 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-16 08:29:15.437   927  3482 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-16 08:29:15.437   927  3482 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-16 08:29:15.437   927  3482 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-16 08:29:15.437   927  3482 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-16 08:29:15.437   927  3482 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-16 08:29:15.437   927  3482 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-16 08:29:15.437   927  3482 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-16 08:29:15.437   927  3482 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-16 08:29:15.459   927  3482 I ActivityManager: Start proc 5537:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-16 08:29:15.460   927  3367 W ActivityManager: Spurious death for ProcessRecord{2d4b4ce 5537:com.android.bluetooth/1002}, curProc for 4389: null
09-16 08:29:15.463  5477  5477 D DockEventReceiver: finishStartingService: stopping service
09-16 08:29:15.465   927  3089 I ActivityManager: Killing 5159:com.google.android.apps.photos/u0a62 (adj 15): empty #17
09-16 08:29:15.492   927   944 D Tethering: InitialState.processMessage what=4
,09-16 08:29:15.502   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 08:29:15.550  5537  5537 D AdapterServiceConfig: Adding HeadsetService
09-16 08:29:15.551  5537  5537 D AdapterServiceConfig: Adding A2dpService
09-16 08:29:15.551  5537  5537 D AdapterServiceConfig: Adding HidService
09-16 08:29:15.551  5537  5537 D AdapterServiceConfig: Adding HealthService
09-16 08:29:15.551  5537  5537 D AdapterServiceConfig: Adding PanService
09-16 08:29:15.551  5537  5537 D AdapterServiceConfig: Adding GattService
09-16 08:29:15.551  5537  5537 D AdapterServiceConfig: Adding BluetoothMapService
09-16 08:29:15.551  5537  5537 D AdapterServiceConfig: Adding SapService
,09-16 08:29:15.553   927  3726 I ActivityManager: Killing 5213:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-16 08:29:15.591  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 08:29:15.608  3850  3850 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-16 08:29:15.617  3850  3850 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 08:29:15.619  3850  3850 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-16 08:29:15.612  3850  5126 I iu.UploadsManager: num queued entries: 0
09-16 08:29:15.620  3850  5126 I iu.UploadsManager: num updated entries: 0
09-16 08:29:15.620  3850  5126 I iu.SyncManager: NEXT; no task
,09-16 08:29:15.630   927  3089 I ActivityManager: Start proc 5550:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-16 08:29:15.667  5550  5550 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-16 08:29:15.670  5550  5550 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 08:29:15.675  5550  5550 D SprintDMHelper: simOperator: 
,09-16 08:29:15.675  5550  5550 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 08:29:15.687   927  3482 I ActivityManager: Start proc 5562:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-16 08:29:15.688   927  3482 I ActivityManager: Killing 3352:android.process.acore/u0a2 (adj 15): empty #17
,09-16 08:29:15.785  4235  5576 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 08:29:15.793   927  3367 I ActivityManager: Start proc 5577:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-16 08:29:15.795   927  3367 I ActivityManager: Killing 5233:com.google.android.partnersetup/u0a18 (adj 15): empty #17
,09-16 08:29:15.820  5498  5518 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-16 08:29:15.846  5577  5577 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-16 08:29:15.862   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6fe6338:true
,09-16 08:29:16.036   927  3482 I ActivityManager: Killing 5250:com.android.musicfx/u0a21 (adj 15): empty #17
,09-16 08:29:16.072   927  3367 I ActivityManager: Start proc 5591:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-16 08:29:16.102  5591  5591 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-16 08:29:16.109   927  3089 I ActivityManager: Killing 5018:com.google.android.gms.wearable/u0a12 (adj 15): empty #17
,09-16 08:29:19.993   927  3091 D WifiService: setWifiEnabled: true pid=5423, uid=10077
09-16 08:29:19.994   927  3091 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 08:29:20.006   506   926 D SoftapController: Softap fwReload - Ok
,09-16 08:29:20.012   506   926 D CommandListener: Setting iface cfg
,09-16 08:29:20.012   506   926 D CommandListener: Trying to bring down wlan0
09-16 08:29:20.013   506   926 D CommandListener: Clearing all IP addresses on wlan0
,09-16 08:29:20.015   927  2910 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 08:29:20.586   927  2910 D wifi    : set interface wlan0 flags (UP)
09-16 08:29:20.590   927  2910 I WifiHAL : Initializing wifi
09-16 08:29:20.590   927  2910 I WifiHAL : Creating socket
,09-16 08:29:20.596   927  2910 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-16 08:29:20.596   927  2910 D wifi    : Did set static halHandle = 0x7f7d55b040
09-16 08:29:20.596   927  2910 D wifi    : halHandle = 0x7f7d55b040, mVM = 0x7f99b8d140, mCls = 0x1017ae
09-16 08:29:20.597   927  2910 D wifi    : array field set
09-16 08:29:20.597   927  2910 I WifiNative-HAL: interface[0] = wlan0
09-16 08:29:20.599   927  5610 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547563614272
09-16 08:29:20.600   927  5610 D wifi    : waitForHalEvents called, vm = 0x7f99b8d140, obj = 0x1017ae, env = 0x7f79a789c0
09-16 08:29:20.605   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 08:29:20.611   927  2910 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 08:29:20.615  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:20.617  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:20.619  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:20.672  5611  5611 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 08:29:20.686  5611  5611 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 08:29:20.715  5611  5611 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 08:29:20.715  5611  5611 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 08:29:20.730   927  2910 D WifiConfigStore: Loading config and enabling all networks 
,09-16 08:29:20.731  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:20.731  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:20.731  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:20.731  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:20.731  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:20.731  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:20.731  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:20.731  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:20.731  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:20.731  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:20.731  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:20.732  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:20.732  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:20.732  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:20.732  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:20.732  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:20.732  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:20.732  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:20.732  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:20.732  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:20.733  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:20.733  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 08:29:20.734  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:20.735  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:20.735  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:20.735  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:20.735  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:20.735  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:20.735  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:20.735  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:20.735  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 08:29:20.735  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:20.735  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 08:29:20.743   927  2910 D WifiConfigStore: loaded 0 passpoint configs
,09-16 08:29:20.744   927  2910 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 08:29:20.744   927  2910 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 08:29:20.745   927  2910 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 08:29:20.746   927  2910 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-16 08:29:20.747   927  2910 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 08:29:20.747   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-16 08:29:20.747   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 08:29:20.751   927  2910 D WifiNative-HAL: Setting external_sim to 1
,09-16 08:29:20.751  4235  4235 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 08:29:20.751   927  2910 D wifi    : setting dfs flag to true, 0x7f7e392180
,09-16 08:29:20.752   927  2910 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 08:29:20.752   927  2910 D wifi    : setting scan oui 0x7f7e392180
09-16 08:29:20.752   927  2910 D WifiHAL : Sending mac address OUI
09-16 08:29:20.755   927  2910 E native  : do suspend false
,09-16 08:29:20.762   927  2910 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-16 08:29:20.763   927   927 D RttService: SCAN_AVAILABLE : 3
09-16 08:29:20.763   506   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-16 08:29:20.763   927  3018 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-16 08:29:20.763   506   926 D CommandListener: Setting iface cfg
,09-16 08:29:20.768   927  2909 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-16 08:29:20.768   927  2909 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 08:29:20.778   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=384882 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=11 mControllerEnergyUsed=41 }
,09-16 08:29:20.779   927  2909 D WifiNative-HAL: p2pGetDeviceAddress
,09-16 08:29:20.779   927  2909 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 08:29:23.962  5611  5611 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 08:29:23.970  5611  5611 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 08:29:23.976  5611  5611 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 08:29:23.982  5611  5611 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 08:29:24.005   927  2910 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-16 08:29:24.006   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-16 08:29:24.006   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 08:29:24.018   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 08:29:24.051   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 08:29:24.054  5611  5611 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-16 08:29:24.475  5611  5611 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-16 08:29:24.509  5611  5611 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-16 08:29:24.509  5611  5611 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-16 08:29:24.517   927  2910 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 08:29:24.517   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 08:29:24.517   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-16 08:29:24.534   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 08:29:24.545   506   926 D CommandListener: Setting iface cfg
,09-16 08:29:24.550   927  2910 D WifiStateMachine: Start Dhcp Watchdog 2
,09-16 08:29:24.555   927  5628 D DhcpClient: Receive thread started
,09-16 08:29:24.559   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 08:29:24.559   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-16 08:29:24.559   927  2912 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-16 08:29:24.639   927  2910 E native  : do suspend false
,09-16 08:29:24.652   927  5627 D DhcpClient: Broadcasting DHCPDISCOVER
,09-16 08:29:24.664   927  5628 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172452, domain null
,09-16 08:29:24.664   927  5627 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172452 seconds
09-16 08:29:24.666   927  5627 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-16 08:29:24.678   927  5628 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-16 08:29:24.679   927  5627 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-16 08:29:24.682   506   926 D CommandListener: Setting iface cfg
,09-16 08:29:24.686   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-16 08:29:24.691   927  5627 D DhcpClient: Scheduling renewal in 86399s
,09-16 08:29:24.699   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-16 08:29:24.700   927  2910 D WifiConfigStore: No blacklist allowed without epno enabled
,09-16 08:29:24.701   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-16 08:29:24.705   927  2912 D ConnectivityService: Adding iface wlan0 to network 101
,09-16 08:29:24.715   927  2910 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-16 08:29:24.755   927  2912 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-16 08:29:24.756   927  2912 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-16 08:29:24.761   927  2912 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-16 08:29:24.763   927  2912 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-16 08:29:24.766   927  2912 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-16 08:29:24.772   927  2912 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 08:29:24.776   927  2912 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-16 08:29:24.777   927  2912 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-16 08:29:24.777   927  2912 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-16 08:29:24.777   927  2912 D ConnectivityService:    accepting network in place of null
09-16 08:29:24.777   927  2910 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-16 08:29:24.777   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 08:29:24.777   927  2912 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 08:29:24.790   927  5626 D NetlinkSocketObserver: NeighborEvent{elapsedMs=388894, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:29:24.802   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 08:29:24.822   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 08:29:24.826   927  2912 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-16 08:29:24.826  3413  3535 W QCNEJ   : |CORE| network available: 101
,09-16 08:29:24.826   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-16 08:29:24.827   927  2912 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-16 08:29:24.827  3413  3535 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-16 08:29:24.828   927   944 D Tethering: MasterInitialState.processMessage what=3
09-16 08:29:24.829  3413  3535 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-16 08:29:24.829  3413  3535 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-16 08:29:24.832  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:24.833  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:24.833  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:24.833  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:24.833  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:24.833  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:24.833  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:29:24.833  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:29:24.833  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 08:29:24.833  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:24.833  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:29:24.838  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:24.838  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:24.838  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:24.838  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:24.838  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:24.838  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:24.838  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:29:24.838  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:29:24.838  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 08:29:24.838  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:24.838  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:29:24.840  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:24.840  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:24.840  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:24.840  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:24.840  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:24.840  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:24.840  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:29:24.840  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:29:24.840  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 08:29:24.840  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:24.840  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:29:24.845  4810  4825 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 08:29:24.845  4810  4825 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 08:29:24.845  4810  4825 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-16 08:29:24.845  4810  4825 E SarControlService: no key has been found,reset the power
09-16 08:29:24.845  4810  4849 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 08:29:24.845  4810  4849 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-16 08:29:24.846  4810  4849 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 08:29:24.846  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 08:29:24.846  4839  4839 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 08:29:24.847  4810  4849 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 08:29:24.847  4810  4849 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 08:29:24.847  4810  4849 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 08:29:24.848  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 08:29:24.848  4839  4839 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-16 08:29:24.853  4839  4853 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e5bbfc5 HexData = [00000000ec03000000000000ffffffff]
,09-16 08:29:24.854  4839  4853 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 08:29:24.854  4839  4853 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-16 08:29:24.855  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 08:29:24.855  4810  4822 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 08:29:24.856  4839  4853 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e5bbfc5 HexData = [00000000ed03000000000000ffffffff]
09-16 08:29:24.856  4839  4853 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 08:29:24.856  4839  4853 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-16 08:29:24.857  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 08:29:24.857  4810  4821 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 08:29:24.860  3850  3850 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-16 08:29:24.868  3850  5126 I iu.UploadsManager: num queued entries: 0
,09-16 08:29:24.868  3850  5126 I iu.UploadsManager: num updated entries: 0
09-16 08:29:24.868  3850  5126 I iu.SyncManager: NEXT; no task
,09-16 08:29:24.870  3850  3850 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 08:29:24.871  3850  3850 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 08:29:24.874  5550  5550 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 08:29:24.877  5550  5550 D SprintDMHelper: simOperator: 
09-16 08:29:24.877  5550  5550 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-16 08:29:24.877   927  5623 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-16 08:29:24.932   927  5623 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 12:29:24 GMT], X-Android-Received-Millis=[1474028964931], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474028964900]}
,09-16 08:29:24.932   927  2912 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 08:29:24.933   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-16 08:29:24.933   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-16 08:29:24.934   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-16 08:29:24.987  4235  5641 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-16 08:29:25.003   927  3367 D WifiService: setWifiEnabled: false pid=5423, uid=10077
09-16 08:29:25.003   927  3367 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 08:29:25.005   927  2910 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-16 08:29:25.005   927  2910 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-16 08:29:25.006   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 08:29:25.006   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 08:29:25.013   927  5627 D DhcpClient: Clearing IP address
09-16 08:29:25.013   506   926 D CommandListener: Clearing all IP addresses on wlan0
,09-16 08:29:25.015   506   926 D CommandListener: Setting iface cfg
,09-16 08:29:25.018  3528  5647 V NativeCrypto: Read error: ssl=0x7f8fccb680: I/O error during system call, Connection timed out
09-16 08:29:25.019  3528  5647 V NativeCrypto: SSL shutdown failed: ssl=0x7f8fccb680: I/O error during system call, Broken pipe
,09-16 08:29:25.021   927  5628 D DhcpClient: Receive thread stopped
,09-16 08:29:25.027   927   937 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,09-16 08:29:25.028   927  5623 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
09-16 08:29:25.028   927  5623 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-16 08:29:25.029   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-16 08:29:25.029   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-16 08:29:25.033   927  2912 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-16 08:29:25.033   927   927 D RttService: SCAN_AVAILABLE : 1
09-16 08:29:25.034   927  3018 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 08:29:25.034   532   532 E Parcel  : Reading a NULL string not supported here.
09-16 08:29:25.035  3413  3535 W QCNEJ   : |CORE| network lost: 101
09-16 08:29:25.035  3413  3535 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-16 08:29:25.039   927  5623 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-16 08:29:25.045   927  2910 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-16 08:29:25.049   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 08:29:25.062   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 08:29:25.082   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 08:29:25.082   927  2912 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-16 08:29:25.082   506   926 D CommandListener: Clearing all IP addresses on wlan0
09-16 08:29:25.082   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 08:29:25.084   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-16 08:29:25.085   927  2910 D DhcpClient: doQuit
,09-16 08:29:25.085   927  2910 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 08:29:25.085   927  5627 D DhcpClient: onQuitting
09-16 08:29:25.086  5611  5611 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-16 08:29:25.087  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:25.087  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:25.087  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:25.087  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:25.087  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:25.087  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:25.087  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:25.087  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:25.087  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:25.087  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:25.088  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:25.088  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:25.088  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:25.088  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:25.088  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:25.088  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:25.088  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:25.088  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:25.088  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:25.088  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:25.088  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 08:29:25.089  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:25.090  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:25.091  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:25.091  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:25.091  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:25.091  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:25.091  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:25.091  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:25.091  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:25.091  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:25.091  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:25.091  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:25.092  4810  4825 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 08:29:25.092  4810  4825 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 08:29:25.092  4810  4825 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-16 08:29:25.093  4810  4825 E SarControlService: no key has been found,reset the power
09-16 08:29:25.093  4810  4849 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 08:29:25.093  4810  4849 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 08:29:25.093  4810  4849 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-16 08:29:25.094  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:25.094  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:25.094  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:25.094  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:25.094  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:25.094  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:25.094  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:25.094  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:25.094  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:25.094  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:25.094  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:25.095  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:25.095  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:25.095  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:25.095  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:25.095  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:25.095  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:25.095  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:25.095  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:25.095  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:25.095  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:25.095  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 08:29:25.095  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:25.095  4839  4839 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 08:29:25.097  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:25.097  4810  4849 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 08:29:25.099  4810  4849 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 08:29:25.099  4810  4849 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 08:29:25.100  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 08:29:25.100  4839  4839 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 08:29:25.102  4839  4853 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e5bbfc5 HexData = [00000000ee03000000000000ffffffff]
09-16 08:29:25.102  4839  4853 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 08:29:25.102  4839  4853 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-16 08:29:25.102  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 08:29:25.102  4810  4821 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 08:29:25.103  4839  4853 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e5bbfc5 HexData = [00000000ef03000000000000ffffffff]
09-16 08:29:25.103  4839  4853 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 08:29:25.103  4839  4853 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-16 08:29:25.104  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 08:29:25.105  4810  4822 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-16 08:29:25.105  3850  3850 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-16 08:29:25.111  3850  5126 I iu.UploadsManager: num queued entries: 0
,09-16 08:29:25.112  3850  5126 I iu.UploadsManager: num updated entries: 0
09-16 08:29:25.112  3850  5126 I iu.SyncManager: NEXT; no task
,09-16 08:29:25.114  3850  3850 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 08:29:25.114  5611  5611 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-16 08:29:25.115  3850  3850 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 08:29:25.118  5550  5550 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-16 08:29:25.119  5611  5611 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-16 08:29:25.122  5550  5550 D SprintDMHelper: simOperator: 
09-16 08:29:25.122  5550  5550 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 08:29:25.135  4235  5661 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 08:29:25.145   506   926 E Netd    : netlink response contains error (No such file or directory)
09-16 08:29:25.146   927  2912 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 08:29:25.159  5611  5611 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 08:29:25.170  5611  5611 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 08:29:25.272   927  2910 D wifi    : In wifi stop Hal
,09-16 08:29:25.272   927  2910 D wifi    : halHandle = 0x7f7d55b040, mVM = 0x7f99b8d140, mCls = 0x1017ae
,09-16 08:29:25.272   927  5610 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 08:29:25.272   927  5610 D WifiHAL : Got a signal to exit!!!
09-16 08:29:25.272   927  5610 I WifiHAL : Exit wifi_event_loop
09-16 08:29:25.273  4235  4235 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 08:29:25.274  3551  3978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 08:29:25.275  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:25.275   927  2910 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-16 08:29:25.276   927  2910 E WifiHAL : Event processing terminated
09-16 08:29:25.276   927  2910 D wifi    : In wifi cleaned up handler
09-16 08:29:25.276   927  2910 I WifiHAL : Internal cleanup completed
09-16 08:29:25.277  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:25.280  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:25.301   927  5610 D wifi    : set interface wlan0 flags (DOWN)
,09-16 08:29:25.301   927  2910 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 08:29:25.362   506   926 E Netd    : netlink response contains error (No such file or directory)
,09-16 08:29:25.473   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:25.507   927   944 D Tethering: InitialState.processMessage what=4
,09-16 08:29:25.514   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 08:29:25.827   927  2912 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-16 08:29:26.474   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:27.475   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:28.476   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:29.477   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:30.038   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@96faba4:true
,09-16 08:29:30.039  5537  5537 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 08:29:30.044  5537  5537 I bt_bluedroid: init
,09-16 08:29:30.045  5537  5671 I BluetoothAdapterState: Entering OffState
,09-16 08:29:30.049  5537  5672 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 08:29:30.049  5537  5672 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 08:29:30.049  5537  5672 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 08:29:30.049  5537  5672 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-16 08:29:30.050  5537  5537 I bt_bluedroid: get_profile_interface socket
,09-16 08:29:30.054  5537  5537 I bt_bluedroid: get_profile_interface sdp
,09-16 08:29:30.054  5537  5675 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 08:29:30.058  5537  5675 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 08:29:30.063  5537  5548 I bt_bluedroid: config_hci_snoop_log
,09-16 08:29:30.065   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-16 08:29:30.071  5537  5671 D BluetoothAdapterState: Current state: OFF, message: 0
09-16 08:29:30.071  5537  5671 D BluetoothAdapterProperties: Setting state to 14
,09-16 08:29:30.072  5537  5671 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-16 08:29:30.074  5537  5671 D BluetoothBondStateMachine: make
,09-16 08:29:30.078  5537  5676 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 08:29:30.082  5537  5671 I BluetoothAdapterState: Entering PendingCommandState
,09-16 08:29:30.084  5537  5537 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 08:29:30.089  5537  5537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
,09-16 08:29:30.090  5537  5537 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 08:29:30.091  5537  5537 D BtGatt.GattService: Received start request. Starting profile...
,09-16 08:29:30.091  5537  5537 D BtGatt.GattService: start()
,09-16 08:29:30.091  5537  5537 I bt_bluedroid: get_profile_interface gatt
09-16 08:29:30.093  5537  5537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:30.093  5537  5537 D BtGatt.AdvertiseManager: advertise manager created
,09-16 08:29:30.101  5537  5537 V BluetoothAdapterState: isTurningOff()=false
,09-16 08:29:30.101  5537  5537 V BluetoothAdapterState: isTurningOn()=false
,09-16 08:29:30.101  5537  5537 V BluetoothAdapterState: isBleTurningOn()=true
09-16 08:29:30.101  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:30.102  5537  5671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-16 08:29:30.103  5537  5671 I bt_bluedroid: bt_bluedroid
,09-16 08:29:30.104  5537  5672 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 08:29:30.104  5537  5672 I bt_hci  : start_up
,09-16 08:29:30.112  5537  5672 I bt_vendor: alloc value 0xf4178871
,09-16 08:29:30.112  5537  5672 I bt_vendor: init
09-16 08:29:30.112  5537  5672 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 08:29:30.112  5537  5672 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 08:29:30.226  5537  5672 D bt_hci  : start_up starting async portion
,09-16 08:29:30.227  5537  5679 I bt_hci  : event_finish_startup
,09-16 08:29:30.229  5537  5679 I bt_hci_h4: hal_open
09-16 08:29:30.230  5537  5679 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-16 08:29:30.226  5680  5680 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 08:29:30.233  5537  5679 I bt_userial_vendor: device fd = 54 open
,09-16 08:29:30.247  5537  5679 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 08:29:30.249  5537  5679 D bt_hwcfg: Chipset BCM4358A3
,09-16 08:29:30.249  5537  5679 D bt_hwcfg: Target name = [BCM4358A3]
09-16 08:29:30.249  5537  5679 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 08:29:30.478   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:29:30.649  5537  5679 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-16 08:29:30.649  5537  5679 D bt_hwcfg: Settlement delay -- 100 ms
,09-16 08:29:30.649  5537  5679 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 08:29:30.783  5537  5679 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 08:29:30.784  5537  5679 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-16 08:29:30.785  5537  5679 I bt_hwcfg: vendor lib fwcfg completed
,09-16 08:29:30.785  5537  5679 I bt_vendor: firmware callback
,09-16 08:29:30.785  5537  5679 I bt_hci  : firmware_config_callback
,09-16 08:29:30.794  5537  5682 I bt_btu  : btu_task pending for preload complete event
,09-16 08:29:30.794  5537  5682 I bt_btu_task: Bluetooth chip preload is complete
09-16 08:29:30.794  5537  5682 I bt_btu  : btu_task received preload complete event
,09-16 08:29:30.802  5537  5682 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 08:29:30.802  5537  5682 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 08:29:30.802  5537  5682 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 08:29:30.802  5537  5682 I         : BTE_InitTraceLevels -- TRC_AVDT
09-16 08:29:30.802  5537  5682 I         : BTE_InitTraceLevels -- TRC_AVRC
09-16 08:29:30.802  5537  5682 I         : BTE_InitTraceLevels -- TRC_A2D
,09-16 08:29:30.803  5537  5682 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 08:29:30.803  5537  5682 I         : BTE_InitTraceLevels -- TRC_BTM
09-16 08:29:30.803  5537  5682 I         : BTE_InitTraceLevels -- TRC_GAP
09-16 08:29:30.803  5537  5682 I         : BTE_InitTraceLevels -- TRC_PAN
,09-16 08:29:30.803  5537  5682 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 08:29:30.803  5537  5682 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 08:29:30.803  5537  5682 I         : BTE_InitTraceLevels -- TRC_SMP
09-16 08:29:30.803  5537  5682 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-16 08:29:30.804  5537  5682 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 08:29:30.889  5537  5682 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40f6549
09-16 08:29:30.889  5537  5682 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40f6549 
,09-16 08:29:30.915  5537  5675 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 08:29:30.916  5537  5675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 08:29:30.917  5537  5675 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 08:29:30.919  5537  5675 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 08:29:30.922  5537  5675 D BluetoothAdapterProperties: Scan Mode:20
09-16 08:29:30.924  5537  5675 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 08:29:30.924  5537  5675 D bt_hci  : do_postload posting postload work item
09-16 08:29:30.924  5537  5679 I bt_hci  : event_postload
09-16 08:29:30.924  5537  5679 I bt_vendor: sco_config_cb
09-16 08:29:30.925  5537  5679 I bt_hci  : sco_config_callback postload finished.
,09-16 08:29:30.929  5537  5675 D bt_bte_conf: Device ID record 1 : primary
,09-16 08:29:30.929  5537  5675 D bt_bte_conf:   vendorId            = 000f
09-16 08:29:30.929  5537  5675 D bt_bte_conf:   vendorIdSource      = 0001
09-16 08:29:30.929  5537  5675 D bt_bte_conf:   product             = 1200
09-16 08:29:30.929  5537  5675 D bt_bte_conf:   version             = 1436
09-16 08:29:30.929  5537  5675 D bt_bte_conf:   clientExecutableURL = 
09-16 08:29:30.929  5537  5675 D bt_bte_conf:   serviceDescription  = 
09-16 08:29:30.929  5537  5675 D bt_bte_conf:   documentationURL    = 
09-16 08:29:30.930  5537  5675 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-16 08:29:30.930  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:30.931  5537  5672 D bt_stack_manager: event_start_up_stack finished
09-16 08:29:30.932  5537  5671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-16 08:29:30.933  5537  5671 D BluetoothAdapterProperties: Setting state to 15
09-16 08:29:30.933  5537  5671 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-16 08:29:30.933  5537  5679 I bt_vendor: low_power_mode_cb
09-16 08:29:30.934  5537  5671 I BluetoothAdapterState: Entering BleOnState
,09-16 08:29:30.937  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:30.938  5537  5671 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-16 08:29:30.938  5537  5671 D BluetoothAdapterProperties: Setting state to 11
09-16 08:29:30.939  5537  5671 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-16 08:29:30.940  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:30.947  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:30.948  5537  5537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
,09-16 08:29:30.949  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:30.950  5537  5537 D HeadsetService: Received start request. Starting profile...
,09-16 08:29:30.952  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:30.953  5537  5537 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-16 08:29:30.953  5537  5537 D HeadsetStateMachine: make
,09-16 08:29:30.961  5537  5671 I BluetoothAdapterState: Entering PendingCommandState
,09-16 08:29:30.965  5537  5537 D HeadsetStateMachine: max_hf_connections = 1
,09-16 08:29:30.966  5537  5537 I bt_bluedroid: get_profile_interface handsfree
09-16 08:29:30.966  5537  5675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 08:29:30.967  5537  5675 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-16 08:29:30.969  5537  5537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
,09-16 08:29:30.969  5537  5537 D A2dpService: Received start request. Starting profile...
09-16 08:29:30.970  5537  5537 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 08:29:30.970  5537  5537 I bt_bluedroid: get_profile_interface avrcp
,09-16 08:29:30.976  5537  5537 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 08:29:30.976  5537  5537 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 08:29:30.976  5537  5537 D A2dpStateMachine: make
,09-16 08:29:30.977  5537  5537 I bt_bluedroid: get_profile_interface a2dp
,09-16 08:29:30.978  5537  5675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-16 08:29:30.979  5537  5690 D A2dpStateMachine: Enter Disconnected: -2
,09-16 08:29:30.979  5537  5537 I BluetoothHidServiceJni: classInitNative: succeeds
,09-16 08:29:30.980  5537  5537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
,09-16 08:29:30.982  5477  5477 D BluetoothInputDevice: Proxy object connected
,09-16 08:29:30.983  5537  5537 D HidService: Received start request. Starting profile...
09-16 08:29:30.983  5537  5537 I bt_bluedroid: get_profile_interface hidhost
09-16 08:29:30.983  5477  5477 D HidProfile: Bluetooth service connected
09-16 08:29:30.983  5537  5537 D HidService: setHidService(): set to: null
09-16 08:29:30.983  5537  5675 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40d756d
09-16 08:29:30.983  5537  5675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-16 08:29:30.984  5537  5537 I BluetoothHealthServiceJni: classInitNative: succeeds
09-16 08:29:30.984  5537  5537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
,09-16 08:29:30.985  5537  5537 D HealthService: Received start request. Starting profile...
,09-16 08:29:30.986  5537  5537 I bt_bluedroid: get_profile_interface health
,09-16 08:29:30.987  5537  5537 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-16 08:29:30.988  5537  5537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
,09-16 08:29:30.989  5477  5477 D BluetoothPan: BluetoothPAN Proxy object connected
,09-16 08:29:30.989  5537  5537 D PanService: Received start request. Starting profile...
09-16 08:29:30.989  5537  5537 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 08:29:30.989  5537  5537 I bt_bluedroid: get_profile_interface pan
09-16 08:29:30.990  5477  5477 D PanProfile: Bluetooth service connected
09-16 08:29:30.990  5537  5675 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-16 08:29:30.992  5537  5537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
,09-16 08:29:30.994  5477  5477 D BluetoothMap: Proxy object connected
,09-16 08:29:30.994  5477  5477 D MapProfile: Bluetooth service connected
09-16 08:29:30.994  5477  5477 D BluetoothMap: getConnectedDevices()
09-16 08:29:30.995  5537  5537 D BluetoothMapService: Received start request. Starting profile...
09-16 08:29:30.995  5537  5537 D BluetoothMapService: start()
,09-16 08:29:30.998  5537  5537 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-16 08:29:30.999  5537  5537 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-16 08:29:30.999  5537  5537 D BluetoothMapAppObserver: createReceiver()
,09-16 08:29:31.001  5537  5537 D BluetoothMapAppObserver: initObservers()
,09-16 08:29:31.001  5537  5537 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 08:29:31.006  5477  5477 D BluetoothMap: Bluetooth is Not enabled
,09-16 08:29:31.008  5537  5537 V SapService: SapBinder()
,09-16 08:29:31.008  5537  5537 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:31.008  5537  5537 D SapService: Received start request. Starting profile...
09-16 08:29:31.008  5537  5537 V SapService: start()
,09-16 08:29:31.012  5537  5537 V BluetoothAdapterState: isTurningOff()=false
,09-16 08:29:31.012  5537  5537 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:31.012  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:31.012  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isTurningOff()=false
,09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:31.013  5537  5688 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isTurningOn()=true
,09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:31.013  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isTurningOff()=false
,09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:31.013  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:31.014  5537  5537 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:31.014  5537  5537 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:31.014  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:31.014  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:31.015  5537  5537 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:31.015  5537  5537 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:31.015  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:31.015  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:31.015  5537  5671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-16 08:29:31.015  5537  5671 D BluetoothAdapterProperties: ScanMode =  20
09-16 08:29:31.015  5537  5671 D BluetoothAdapterProperties: State =  11
09-16 08:29:31.015  5537  5671 D BluetoothAdapterProperties: Setting state to 12
09-16 08:29:31.015  5537  5671 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 08:29:31.016   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:31.016  5537  5671 I BluetoothAdapterState: Entering OnState
09-16 08:29:31.016  3064  3386 D BluetoothPan: onBluetoothStateChange on: true
09-16 08:29:31.018  5537  5675 D BluetoothAdapterProperties: Scan Mode:21
,09-16 08:29:31.018  5537  5675 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-16 08:29:31.021  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 08:29:31.021   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:31.021  3064  3064 D PanProfile: Bluetooth service connected
,09-16 08:29:31.021  3064  3681 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-16 08:29:31.023  3064  3080 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 08:29:31.023  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:31.023  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:31.023  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:31.023  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:31.023  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:29:31.023  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:31.023  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:31.023  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:31.024  3064  3064 D BluetoothA2dp: Proxy object connected
,09-16 08:29:31.025  5477  5490 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 08:29:31.025  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 08:29:31.027   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:31.027  3064  3082 D BluetoothMap: onBluetoothStateChange: up=true
09-16 08:29:31.027  5537  5537 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 08:29:31.028  5537  5537 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 08:29:31.029  3064  3064 D BluetoothMap: Proxy object connected
09-16 08:29:31.029  5477  5489 D BluetoothPan: onBluetoothStateChange on: true
09-16 08:29:31.029  3064  3064 D MapProfile: Bluetooth service connected
,09-16 08:29:31.029  3064  3064 D BluetoothMap: getConnectedDevices()
09-16 08:29:31.029  3064  3386 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 08:29:31.029  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:31.029  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:31.029  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:31.029  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:31.029  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:29:31.029  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:31.029  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:31.029  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:31.030  5537  5537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 08:29:31.031  5477  5490 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 08:29:31.031  5477  5489 D BluetoothMap: onBluetoothStateChange: up=true
09-16 08:29:31.032  3470  3484 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:31.032  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:31.032  5537  5537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 08:29:31.032  3064  3082 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 08:29:31.032  3064  3064 D BluetoothInputDevice: Proxy object connected
09-16 08:29:31.032  3064  3064 D HidProfile: Bluetooth service connected
09-16 08:29:31.033   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 08:29:31.033  5537  5537 D ObexServerSockets: Succeed to create listening sockets 
09-16 08:29:31.033  5537  5537 D ObexServerSockets0: startAccept()
09-16 08:29:31.033  5537  5537 D ObexServerSockets0: prepareForNewConnect()
09-16 08:29:31.033   927   927 D BluetoothA2dp: Proxy object connected
09-16 08:29:31.036  5537  5537 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 08:29:31.036  5537  5537 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 08:29:31.037  5537  5537 D BluetoothMapService: onReceive
09-16 08:29:31.037  5537  5537 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-16 08:29:31.037  5537  5697 D ObexServerSockets0: Accepting socket connection...
09-16 08:29:31.037  5537  5537 D BluetoothMapService: STATE_ON
09-16 08:29:31.038  5537  5698 D ObexServerSockets0: Accepting socket connection...
09-16 08:29:31.038  5477  5477 D LocalBluetoothProfileManager: Adding local A2DP profile
09-16 08:29:31.039  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:31.039  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:31.039  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:31.039  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:31.039  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:29:31.039  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:31.039  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:31.039  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:31.039   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 08:29:31.043  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:31.043  5477  5477 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-16 08:29:31.043  5537  5699 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:29:31.044  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:31.044  5537  5699 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 08:29:31.044  5537  5699 D BluetoothSdpJni: SDP Create record success - handle: 1
09-16 08:29:31.045  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:31.048  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:31.051  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 08:29:31.054  5477  5477 D BluetoothA2dp: Proxy object connected
,09-16 08:29:31.057  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 08:29:31.058  5477  5477 D DockEventReceiver: finishStartingService: stopping service
,09-16 08:29:31.064  5477  5477 D BluetoothPbap: Proxy object connected
,09-16 08:29:31.064  5477  5477 D PbapServerProfile: Bluetooth service connected
09-16 08:29:31.065  5537  5537 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 08:29:31.065  5537  5537 D ObexServerSockets0: prepareForNewConnect()
09-16 08:29:31.065  3064  3064 D BluetoothPbap: Proxy object connected
09-16 08:29:31.065  3064  3064 D PbapServerProfile: Bluetooth service connected
,09-16 08:29:31.073  5537  5703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:29:31.085  5537  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:29:31.086  5537  5707 I BtOppRfcommListener: Accept thread started.
,09-16 08:29:31.118   927   927 D BluetoothHeadset: Proxy object connected
,09-16 08:29:31.118   927   927 D BluetoothHeadset: Proxy object connected
09-16 08:29:31.118   927   927 D BluetoothHeadset: Proxy object connected
09-16 08:29:31.119  3064  3681 D BluetoothHeadset: Proxy object connected
09-16 08:29:31.119  3064  3064 D HeadsetProfile: Bluetooth service connected
,09-16 08:29:31.119  3470  3483 D BluetoothHeadset: Proxy object connected
,09-16 08:29:31.120   927   944 D BluetoothHeadset: Proxy object connected
,09-16 08:29:31.127   927   944 D BluetoothHeadset: Proxy object connected
,09-16 08:29:31.132  3470  3720 D BluetoothHeadset: Proxy object connected
,09-16 08:29:31.133  3064  3080 D BluetoothHeadset: Proxy object connected
09-16 08:29:31.133  3064  3064 D HeadsetProfile: Bluetooth service connected
,09-16 08:29:31.147  5477  5490 D BluetoothHeadset: Proxy object connected
,09-16 08:29:31.148  5477  5477 D HeadsetProfile: Bluetooth service connected
,09-16 08:29:32.783   927  2912 D ConnectivityService: handlePromptUnvalidated 101
,09-16 08:29:35.020  5537  5671 D BluetoothAdapterState: Current state: ON, message: 23
,09-16 08:29:35.021  5537  5671 D BluetoothAdapterProperties: Setting state to 13
,09-16 08:29:35.021  5537  5671 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-16 08:29:35.023  5537  5671 D BluetoothAdapterProperties: onBluetoothDisable()
,09-16 08:29:35.026  5537  5671 I BluetoothAdapterState: Entering PendingCommandState
09-16 08:29:35.029  5537  5537 D BluetoothMapService: onReceive
09-16 08:29:35.030  5537  5537 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 08:29:35.030  5537  5537 D BluetoothMapService: STATE_TURNING_OFF
09-16 08:29:35.030  5537  5537 D BluetoothMapService: MAP Service closeService in
09-16 08:29:35.030  5537  5537 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 08:29:35.031  5537  5537 D ObexServerSockets0: shutdown(block = true)
09-16 08:29:35.034  5537  5537 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 08:29:35.035  5537  5697 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-16 08:29:35.037  5537  5537 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 08:29:35.037  5537  5698 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 08:29:35.037  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:35.038  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:35.038  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:35.038  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:35.038  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:35.038  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:35.038  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:35.038  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:35.038  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:35.038  5537  5675 D BluetoothAdapterProperties: Scan Mode:20
,09-16 08:29:35.039  5537  5684 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-16 08:29:35.040  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:35.040  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:35.042  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 08:29:35.042  5537  5537 I BtOppRfcommListener: stopping Accept Thread
09-16 08:29:35.039  5537  5671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-16 08:29:35.042  5537  5707 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 08:29:35.042  5537  5707 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 08:29:35.044  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:35.044  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:35.044  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:35.044  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:35.044  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:35.044  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:35.044  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:35.044  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:35.044  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 08:29:35.045  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:35.045  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:35.048  5537  5537 D HeadsetService: Received stop request...Stopping profile...
09-16 08:29:35.049  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:35.049  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:35.049  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:35.049  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:35.049  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:35.049  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 08:29:35.049  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:35.049  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:35.049  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:35.050  5423  5423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 08:29:35.050  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:35.051  5477  5477 D DockEventReceiver: finishStartingService: stopping service
09-16 08:29:35.051   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:35.051   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:35.051   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:35.052  5477  5489 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:35.052  3064  3082 D BluetoothHeadset: Proxy object disconnected
,09-16 08:29:35.053  3470  3856 D BluetoothHeadset: Proxy object disconnected
09-16 08:29:35.053  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:35.053  5477  5477 D HeadsetProfile: Bluetooth service disconnected
09-16 08:29:35.055  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:35.056  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:35.057  5537  5537 D A2dpService: Received stop request...Stopping profile...
09-16 08:29:35.057  5537  5690 D A2dpStateMachine: Exit Disconnected: -1
,09-16 08:29:35.058  3064  3064 D HeadsetProfile: Bluetooth service disconnected
09-16 08:29:35.060  3064  3064 D BluetoothA2dp: Proxy object disconnected
09-16 08:29:35.062  5537  5537 D HidService: Received stop request...Stopping profile...
09-16 08:29:35.062  5537  5537 D HidService: Stopping Bluetooth HidService
09-16 08:29:35.063   927   927 D BluetoothA2dp: Proxy object disconnected
09-16 08:29:35.063  5477  5477 D BluetoothA2dp: Proxy object disconnected
,09-16 08:29:35.063  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 08:29:35.064  3064  3064 D BluetoothInputDevice: Proxy object disconnected
09-16 08:29:35.064  3064  3064 D HidProfile: Bluetooth service disconnected
09-16 08:29:35.064  5477  5477 D BluetoothInputDevice: Proxy object disconnected
09-16 08:29:35.064  5477  5477 D HidProfile: Bluetooth service disconnected
09-16 08:29:35.064  5537  5537 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:35.064  5537  5537 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:35.064  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:35.064  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:35.067  5537  5537 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-16 08:29:35.067  5537  5537 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 08:29:35.067  5537  5675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 08:29:35.067  5537  5682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 08:29:35.067  5537  5682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 08:29:35.067  5537  5682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 08:29:35.067  5537  5675 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-16 08:29:35.068  5537  5537 D HealthService: Received stop request...Stopping profile...
,09-16 08:29:35.074  5537  5537 D PanService: Received stop request...Stopping profile...
,09-16 08:29:35.075  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 08:29:35.075  3064  3064 D PanProfile: Bluetooth service disconnected
,09-16 08:29:35.076  5537  5537 D BluetoothMapService: Received stop request...Stopping profile...
,09-16 08:29:35.076  5537  5537 D BluetoothMapService: stop()
09-16 08:29:35.076  5537  5537 D BluetoothMapAppObserver: deinitObservers()
09-16 08:29:35.077  5537  5537 D BluetoothMapAppObserver: removeReceiver()
09-16 08:29:35.077  3064  3064 D BluetoothMap: Proxy object disconnected
09-16 08:29:35.078  3064  3064 D MapProfile: Bluetooth service disconnected
09-16 08:29:35.078  5537  5537 D SapService: Received stop request...Stopping profile...
09-16 08:29:35.078  5537  5537 V SapService: stop()
09-16 08:29:35.079  5537  5537 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:35.079  5537  5537 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:35.079  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:35.079  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:35.080  5477  5477 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 08:29:35.080  5477  5477 D PanProfile: Bluetooth service disconnected
09-16 08:29:35.080  5477  5477 D BluetoothMap: Proxy object disconnected
,09-16 08:29:35.080  5477  5477 D MapProfile: Bluetooth service disconnected
09-16 08:29:35.081  5537  5675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 08:29:35.081  5537  5682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 08:29:35.081  5537  5682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-16 08:29:35.081  5537  5682 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 08:29:35.081  5537  5682 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 08:29:35.081  5537  5682 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 08:29:35.081  5537  5682 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 08:29:35.085  3064  3064 D BluetoothPbap: Proxy object disconnected
09-16 08:29:35.085  5537  5537 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:35.085  3064  3064 D PbapServerProfile: Bluetooth service disconnected
09-16 08:29:35.085  5537  5537 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:35.085  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:35.085  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:35.086  5537  5537 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-16 08:29:35.086  5537  5537 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 08:29:35.086  5537  5675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 08:29:35.086  5537  5537 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:35.086  5537  5537 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:35.086  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:35.087  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:35.087  5537  5537 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 08:29:35.087  5537  5675 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-16 08:29:35.087  5537  5537 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 08:29:35.087  5537  5537 V BluetoothAdapterState: isTurningOff()=true
09-16 08:29:35.087  5537  5537 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:35.087  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:35.088  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:35.088  5537  5537 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 08:29:35.088  5537  5537 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 08:29:35.089  5537  5537 D BluetoothMapService: MAP Service closeService in
09-16 08:29:35.089  5537  5537 V BluetoothAdapterState: isTurningOff()=true
,09-16 08:29:35.089  5537  5537 V BluetoothAdapterState: isTurningOn()=false
,09-16 08:29:35.089  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 08:29:35.089  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:35.089  5537  5537 D BluetoothMapService: cleanup()
09-16 08:29:35.089  5537  5537 D BluetoothMapService: MAP Service closeService in
09-16 08:29:35.089  5537  5537 V BluetoothAdapterState: isTurningOff()=true
,09-16 08:29:35.089  5537  5537 V BluetoothAdapterState: isTurningOn()=false
,09-16 08:29:35.089  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:35.089  5537  5537 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:35.089  5477  5477 D BluetoothPbap: Proxy object disconnected
09-16 08:29:35.090  5477  5477 D PbapServerProfile: Bluetooth service disconnected
09-16 08:29:35.090  5537  5671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-16 08:29:35.090  5537  5671 D BluetoothAdapterProperties: Setting state to 15
09-16 08:29:35.090  5537  5671 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-16 08:29:35.090  5537  5671 I BluetoothAdapterState: Entering BleOnState
09-16 08:29:35.091   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:35.091  5477  5489 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:35.091  3064  3082 D BluetoothPan: onBluetoothStateChange on: false
09-16 08:29:35.092   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:35.092  3064  3386 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 08:29:35.092  3064  3681 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 08:29:35.093  5477  5490 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 08:29:35.093   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:35.093  3064  3080 D BluetoothMap: onBluetoothStateChange: up=false
09-16 08:29:35.094  5477  5489 D BluetoothPan: onBluetoothStateChange on: false
,09-16 08:29:35.094  5477  5490 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 08:29:35.095  3064  3082 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 08:29:35.095  5477  5489 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 08:29:35.096  5477  5490 D BluetoothMap: onBluetoothStateChange: up=false
09-16 08:29:35.097  3470  3484 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:35.097  3064  3386 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 08:29:35.097   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 08:29:35.097  5537  5671 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 08:29:35.097  5537  5671 D BluetoothAdapterProperties: Setting state to 16
09-16 08:29:35.097  5537  5671 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 08:29:35.098  5537  5671 D BluetoothAdapterProperties: onBleDisable
09-16 08:29:35.098  5537  5671 I BluetoothAdapterState: Entering PendingCommandState
,09-16 08:29:35.098  5537  5672 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 08:29:35.100  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:35.100  5537  5682 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 08:29:35.100  5537  5682 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 08:29:35.101  5537  5675 D BluetoothAdapterProperties: Scan Mode:20
09-16 08:29:35.101  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 08:29:35.101  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:35.103  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:35.104  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:35.105  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:35.106  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:35.109  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 08:29:35.112  5477  5477 D DockEventReceiver: finishStartingService: stopping service
,09-16 08:29:35.314  5537  5675 I bt_hci  : shut_down
,09-16 08:29:35.321  5537  5679 D bt_hwcfg: hw_epilog_process
,09-16 08:29:35.322  5537  5679 I bt_vendor: low_power_mode_cb
,09-16 08:29:35.327  5537  5679 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-16 08:29:35.327  5537  5679 I bt_vendor: epilog_cb
09-16 08:29:35.327  5537  5679 I bt_hci  : epilog_finished_callback
,09-16 08:29:35.330  5537  5675 I bt_hci_h4: hal_close
,09-16 08:29:35.331  5537  5675 I bt_userial_vendor: device fd = 54 close
,09-16 08:29:35.441  5537  5672 D bt_stack_manager: event_shut_down_stack finished.
,09-16 08:29:35.442  5537  5671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-16 08:29:35.445  5537  5671 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-16 08:29:35.446  5537  5537 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 08:29:35.447  5537  5537 D BtGatt.GattService: Received stop request...Stopping profile...
,09-16 08:29:35.447  5537  5537 D BtGatt.GattService: stop()
09-16 08:29:35.447  5537  5537 D BtGatt.AdvertiseManager: advertise clients cleared
09-16 08:29:35.450  5537  5537 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:35.450  5537  5537 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:35.450  5537  5537 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 08:29:35.450  5537  5537 V BluetoothAdapterState: isBleTurningOff()=true
09-16 08:29:35.451  5537  5671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-16 08:29:35.451  5537  5671 D BluetoothAdapterProperties: Setting state to 10
09-16 08:29:35.451  5537  5671 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 08:29:35.452  5537  5671 I BluetoothAdapterState: Entering OffState
09-16 08:29:35.453   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-16 08:29:35.466  5537  5537 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-16 08:29:35.466  5537  5537 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 08:29:35.466  5537  5537 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-16 08:29:35.468  5537  5672 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 08:29:35.476  5537  5537 I art     : System.exit called, status: 0
09-16 08:29:35.477  5537  5537 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 08:29:35.506   927   938 I ActivityManager: Process com.android.bluetooth (pid 5537) has died
,09-16 08:29:40.016  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 08:29:40.016  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:40.021  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 08:29:40.021  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a0d6f6a removed from the list
09-16 08:29:40.021  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:29:40.021  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:40.021  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:40.026  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 08:29:40.027  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d788cf8 added. We now have 4 listener(s)
,09-16 08:29:40.028  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:29:40.030  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:40.030  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d788cf8 removed from the list
09-16 08:29:40.030  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 08:29:40.031  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:40.031  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:29:40.032  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:29:40.033  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@717c5d1 added. We now have 4 listener(s)
09-16 08:29:40.033  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:29:45.042  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:45.073   927   944 I ActivityManager: Start proc 5715:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-16 08:29:45.162  5715  5715 D AdapterServiceConfig: Adding HeadsetService
,09-16 08:29:45.162  5715  5715 D AdapterServiceConfig: Adding A2dpService
09-16 08:29:45.162  5715  5715 D AdapterServiceConfig: Adding HidService
09-16 08:29:45.162  5715  5715 D AdapterServiceConfig: Adding HealthService
,09-16 08:29:45.163  5715  5715 D AdapterServiceConfig: Adding PanService
09-16 08:29:45.163  5715  5715 D AdapterServiceConfig: Adding GattService
,09-16 08:29:45.163  5715  5715 D AdapterServiceConfig: Adding BluetoothMapService
,09-16 08:29:45.163  5715  5715 D AdapterServiceConfig: Adding SapService
,09-16 08:29:45.176   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@80b9c64:true
,09-16 08:29:45.177  5715  5715 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 08:29:45.180  5715  5715 I bt_bluedroid: init
,09-16 08:29:45.181  5715  5727 I BluetoothAdapterState: Entering OffState
,09-16 08:29:45.184  5715  5728 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 08:29:45.184  5715  5728 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-16 08:29:45.184  5715  5728 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 08:29:45.185  5715  5728 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-16 08:29:45.186  5715  5715 I bt_bluedroid: get_profile_interface socket
,09-16 08:29:45.187  5715  5731 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 08:29:45.188  5715  5715 I bt_bluedroid: get_profile_interface sdp
09-16 08:29:45.189  5715  5731 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 08:29:45.193  5715  5726 I bt_bluedroid: config_hci_snoop_log
09-16 08:29:45.194   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-16 08:29:45.198  5715  5727 D BluetoothAdapterState: Current state: OFF, message: 0
09-16 08:29:45.198  5715  5727 D BluetoothAdapterProperties: Setting state to 14
09-16 08:29:45.198  5715  5727 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-16 08:29:45.200  5715  5727 D BluetoothBondStateMachine: make
,09-16 08:29:45.202  5715  5732 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 08:29:45.205  5715  5727 I BluetoothAdapterState: Entering PendingCommandState
,09-16 08:29:45.206  5715  5715 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 08:29:45.209  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:45.210  5715  5715 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 08:29:45.210  5715  5715 D BtGatt.GattService: Received start request. Starting profile...
,09-16 08:29:45.210  5715  5715 D BtGatt.GattService: start()
09-16 08:29:45.211  5715  5715 I bt_bluedroid: get_profile_interface gatt
,09-16 08:29:45.212  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:45.212  5715  5715 D BtGatt.AdvertiseManager: advertise manager created
,09-16 08:29:45.218  5715  5715 V BluetoothAdapterState: isTurningOff()=false
,09-16 08:29:45.218  5715  5715 V BluetoothAdapterState: isTurningOn()=false
09-16 08:29:45.218  5715  5715 V BluetoothAdapterState: isBleTurningOn()=true
09-16 08:29:45.218  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:45.218  5715  5727 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-16 08:29:45.220  5715  5727 I bt_bluedroid: bt_bluedroid
09-16 08:29:45.220  5715  5728 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 08:29:45.221  5715  5728 I bt_hci  : start_up
,09-16 08:29:45.227  5715  5728 I bt_vendor: alloc value 0xf41e3871
09-16 08:29:45.227  5715  5728 I bt_vendor: init
,09-16 08:29:45.227  5715  5728 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 08:29:45.227  5715  5728 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 08:29:45.337  5715  5728 D bt_hci  : start_up starting async portion
,09-16 08:29:45.338  5715  5735 I bt_hci  : event_finish_startup
09-16 08:29:45.338  5715  5735 I bt_hci_h4: hal_open
09-16 08:29:45.338  5715  5735 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 08:29:45.340  5736  5736 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 08:29:45.345  5715  5735 I bt_userial_vendor: device fd = 54 open
,09-16 08:29:45.361  5715  5735 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 08:29:45.364  5715  5735 D bt_hwcfg: Chipset BCM4358A3
,09-16 08:29:45.364  5715  5735 D bt_hwcfg: Target name = [BCM4358A3]
09-16 08:29:45.365  5715  5735 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 08:29:45.882  5715  5735 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-16 08:29:45.882  5715  5735 D bt_hwcfg: Settlement delay -- 100 ms
,09-16 08:29:45.882  5715  5735 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 08:29:46.016  5715  5735 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 08:29:46.017  5715  5735 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-16 08:29:46.018  5715  5735 I bt_hwcfg: vendor lib fwcfg completed
,09-16 08:29:46.019  5715  5735 I bt_vendor: firmware callback
09-16 08:29:46.019  5715  5735 I bt_hci  : firmware_config_callback
,09-16 08:29:46.029  5715  5738 I bt_btu  : btu_task pending for preload complete event
09-16 08:29:46.029  5715  5738 I bt_btu_task: Bluetooth chip preload is complete
,09-16 08:29:46.030  5715  5738 I bt_btu  : btu_task received preload complete event
,09-16 08:29:46.037  5715  5738 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 08:29:46.037  5715  5738 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 08:29:46.037  5715  5738 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_AVDT
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_AVRC
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_BTM
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_GAP
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_SMP
09-16 08:29:46.038  5715  5738 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-16 08:29:46.039  5715  5738 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 08:29:46.132  5715  5738 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4161549
,09-16 08:29:46.133  5715  5738 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4161549 
,09-16 08:29:46.156  5715  5731 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 08:29:46.158  5715  5731 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 08:29:46.159  5715  5731 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 08:29:46.161  5715  5731 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 08:29:46.164  5715  5731 D BluetoothAdapterProperties: Scan Mode:20
09-16 08:29:46.164  5715  5731 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 08:29:46.164  5715  5731 D bt_hci  : do_postload posting postload work item
09-16 08:29:46.165  5715  5735 I bt_hci  : event_postload
09-16 08:29:46.165  5715  5735 I bt_vendor: sco_config_cb
09-16 08:29:46.165  5715  5735 I bt_hci  : sco_config_callback postload finished.
,09-16 08:29:46.167  5715  5731 D bt_bte_conf: Device ID record 1 : primary
09-16 08:29:46.168  5715  5731 D bt_bte_conf:   vendorId            = 000f
09-16 08:29:46.168  5715  5731 D bt_bte_conf:   vendorIdSource      = 0001
,09-16 08:29:46.168  5715  5731 D bt_bte_conf:   product             = 1200
09-16 08:29:46.168  5715  5731 D bt_bte_conf:   version             = 1436
09-16 08:29:46.168  5715  5731 D bt_bte_conf:   clientExecutableURL = 
09-16 08:29:46.168  5715  5731 D bt_bte_conf:   serviceDescription  = 
09-16 08:29:46.168  5715  5731 D bt_bte_conf:   documentationURL    = 
09-16 08:29:46.168  5715  5731 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-16 08:29:46.169  5715  5728 D bt_stack_manager: event_start_up_stack finished
09-16 08:29:46.169  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:46.170  5715  5727 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-16 08:29:46.170  5715  5727 D BluetoothAdapterProperties: Setting state to 15
09-16 08:29:46.170  5715  5727 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-16 08:29:46.173  5715  5727 I BluetoothAdapterState: Entering BleOnState
09-16 08:29:46.174  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:46.176  5715  5727 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-16 08:29:46.176  5715  5727 D BluetoothAdapterProperties: Setting state to 11
09-16 08:29:46.176  5715  5727 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-16 08:29:46.177  5715  5735 I bt_vendor: low_power_mode_cb
,09-16 08:29:46.180  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:46.182  5715  5715 D HeadsetService: Received start request. Starting profile...
,09-16 08:29:46.186  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:46.187  5715  5715 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-16 08:29:46.189  5715  5715 D HeadsetStateMachine: make
09-16 08:29:46.190  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:46.198  5715  5727 I BluetoothAdapterState: Entering PendingCommandState
,09-16 08:29:46.202  5715  5715 D HeadsetStateMachine: max_hf_connections = 1
09-16 08:29:46.202  5715  5715 I bt_bluedroid: get_profile_interface handsfree
09-16 08:29:46.202  5715  5731 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 08:29:46.202  5715  5731 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-16 08:29:46.205  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
,09-16 08:29:46.206  5715  5715 D A2dpService: Received start request. Starting profile...
,09-16 08:29:46.207  5715  5715 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 08:29:46.207  5715  5715 I bt_bluedroid: get_profile_interface avrcp
,09-16 08:29:46.213  5715  5715 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 08:29:46.213  5715  5715 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 08:29:46.214  5715  5715 D A2dpStateMachine: make
09-16 08:29:46.215  5715  5715 I bt_bluedroid: get_profile_interface a2dp
,09-16 08:29:46.215  5715  5731 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-16 08:29:46.217  5715  5747 D A2dpStateMachine: Enter Disconnected: -2
,09-16 08:29:46.218  5715  5715 I BluetoothHidServiceJni: classInitNative: succeeds
09-16 08:29:46.219  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:46.219  5715  5715 D HidService: Received start request. Starting profile...
09-16 08:29:46.220  5715  5715 I bt_bluedroid: get_profile_interface hidhost
09-16 08:29:46.220  5715  5715 D HidService: setHidService(): set to: null
09-16 08:29:46.220  5715  5731 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414256d
09-16 08:29:46.220  5715  5731 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-16 08:29:46.222  5715  5715 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-16 08:29:46.223  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 08:29:46.223  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:46.225  5715  5715 D HealthService: Received start request. Starting profile...
,09-16 08:29:46.226  5715  5715 I bt_bluedroid: get_profile_interface health
,09-16 08:29:46.227  5715  5715 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-16 08:29:46.228  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:46.229  5715  5715 D PanService: Received start request. Starting profile...
09-16 08:29:46.229  5715  5715 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 08:29:46.229  5715  5715 I bt_bluedroid: get_profile_interface pan
09-16 08:29:46.230  5715  5731 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-16 08:29:46.232  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:46.232  5715  5715 D BluetoothMapService: Received start request. Starting profile...
09-16 08:29:46.232  5715  5715 D BluetoothMapService: start()
,09-16 08:29:46.235  5715  5715 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-16 08:29:46.236  5715  5715 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-16 08:29:46.236  5715  5715 D BluetoothMapAppObserver: createReceiver()
09-16 08:29:46.237  5715  5715 D BluetoothMapAppObserver: initObservers()
09-16 08:29:46.237  5715  5715 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 08:29:46.243  5715  5715 V SapService: SapBinder()
,09-16 08:29:46.244  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:29:46.245  5715  5715 D SapService: Received start request. Starting profile...
09-16 08:29:46.245  5715  5715 V SapService: start()
,09-16 08:29:46.249  5715  5715 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:46.249  5715  5715 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:46.249  5715  5744 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 08:29:46.249  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:46.249  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:46.249  5715  5715 V BluetoothAdapterState: isTurningOff()=false
,09-16 08:29:46.249  5715  5715 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:46.249  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:46.249  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:46.250  5715  5715 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:46.250  5715  5715 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:46.250  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:46.250  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:46.250  5715  5715 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:46.250  5715  5715 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:46.251  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:46.252  5715  5715 V BluetoothAdapterState: isTurningOff()=false
09-16 08:29:46.252  5715  5715 V BluetoothAdapterState: isTurningOn()=true
09-16 08:29:46.252  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
09-16 08:29:46.252  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 08:29:46.253  5715  5727 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-16 08:29:46.253  5715  5727 D BluetoothAdapterProperties: ScanMode =  20
09-16 08:29:46.253  5715  5727 D BluetoothAdapterProperties: State =  11
09-16 08:29:46.254  5715  5727 D BluetoothAdapterProperties: Setting state to 12
09-16 08:29:46.254  5715  5727 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 08:29:46.254  5715  5727 I BluetoothAdapterState: Entering OnState
09-16 08:29:46.254   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:46.254  5477  5490 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:46.255  5715  5731 D BluetoothAdapterProperties: Scan Mode:21
09-16 08:29:46.255  5715  5731 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 08:29:46.256  3064  3386 D BluetoothPan: onBluetoothStateChange on: true
09-16 08:29:46.258   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:46.258  3064  3082 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-16 08:29:46.258  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 08:29:46.259  3064  3064 D PanProfile: Bluetooth service connected
09-16 08:29:46.260  3064  3386 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 08:29:46.261  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:46.261  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:46.261  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:46.261  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:46.261  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:29:46.261  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:46.261  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:46.261  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:46.261  3064  3064 D BluetoothA2dp: Proxy object connected
09-16 08:29:46.262  5477  5489 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 08:29:46.263  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:46.263  5715  5715 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 08:29:46.264   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:46.264  3064  3080 D BluetoothMap: onBluetoothStateChange: up=true
09-16 08:29:46.264  5715  5715 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-16 08:29:46.265  5715  5715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 08:29:46.265  5477  5490 D BluetoothPan: onBluetoothStateChange on: true
09-16 08:29:46.266  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:46.266  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:46.266  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:46.266  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:46.266  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:29:46.266  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:46.266  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:46.266  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:46.267  5715  5715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 08:29:46.267  5477  5489 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 08:29:46.268  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 08:29:46.269  3064  3082 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 08:29:46.270  5715  5715 D ObexServerSockets: Succeed to create listening sockets 
09-16 08:29:46.270  5715  5715 D ObexServerSockets0: startAccept()
09-16 08:29:46.270  5715  5715 D ObexServerSockets0: prepareForNewConnect()
09-16 08:29:46.271  5477  5490 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 08:29:46.271  5715  5715 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-16 08:29:46.271  5715  5715 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 08:29:46.272  5715  5753 D ObexServerSockets0: Accepting socket connection...
09-16 08:29:46.272  5715  5754 D ObexServerSockets0: Accepting socket connection...
09-16 08:29:46.273  5477  5489 D BluetoothMap: onBluetoothStateChange: up=true
09-16 08:29:46.273  3064  3064 D BluetoothMap: Proxy object connected
09-16 08:29:46.273  3064  3064 D MapProfile: Bluetooth service connected
09-16 08:29:46.273  3064  3064 D BluetoothMap: getConnectedDevices()
09-16 08:29:46.274  3470  3483 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:46.275  3064  3064 D BluetoothInputDevice: Proxy object connected
09-16 08:29:46.275  3064  3064 D HidProfile: Bluetooth service connected
09-16 08:29:46.276  3064  3080 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 08:29:46.276  5477  5477 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 08:29:46.276  5477  5477 D PanProfile: Bluetooth service connected
09-16 08:29:46.276  5477  5477 D BluetoothA2dp: Proxy object connected
,09-16 08:29:46.277   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 08:29:46.277   927   927 D BluetoothA2dp: Proxy object connected
09-16 08:29:46.279  5715  5715 D BluetoothMapService: onReceive
09-16 08:29:46.279  5715  5715 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 08:29:46.279  5715  5715 D BluetoothMapService: STATE_ON
09-16 08:29:46.280   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 08:29:46.280  5477  5477 D BluetoothInputDevice: Proxy object connected
09-16 08:29:46.281  5477  5477 D HidProfile: Bluetooth service connected
09-16 08:29:46.282  5477  5477 D BluetoothMap: Proxy object connected
09-16 08:29:46.282  5477  5477 D MapProfile: Bluetooth service connected
,09-16 08:29:46.282  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:46.282  5477  5477 D BluetoothMap: getConnectedDevices()
09-16 08:29:46.284  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:29:46.285  5715  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 08:29:46.287  5715  5756 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 08:29:46.287  5715  5756 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-16 08:29:46.290  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 08:29:46.296  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 08:29:46.297  5477  5477 D DockEventReceiver: finishStartingService: stopping service
,09-16 08:29:46.303  5477  5477 D BluetoothPbap: Proxy object connected
,09-16 08:29:46.303  5477  5477 D PbapServerProfile: Bluetooth service connected
09-16 08:29:46.303  5715  5715 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 08:29:46.303  5715  5715 D ObexServerSockets0: prepareForNewConnect()
,09-16 08:29:46.307  3064  3064 D BluetoothPbap: Proxy object connected
09-16 08:29:46.307  3064  3064 D PbapServerProfile: Bluetooth service connected
,09-16 08:29:46.310  5715  5760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:29:46.325  5715  5764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:29:46.327  5715  5764 I BtOppRfcommListener: Accept thread started.
,09-16 08:29:46.357   927   944 D BluetoothHeadset: Proxy object connected
,09-16 08:29:46.357   927   927 D BluetoothHeadset: Proxy object connected
09-16 08:29:46.357   927   927 D BluetoothHeadset: Proxy object connected
09-16 08:29:46.357   927   927 D BluetoothHeadset: Proxy object connected
09-16 08:29:46.358  5477  5489 D BluetoothHeadset: Proxy object connected
,09-16 08:29:46.358  3064  3681 D BluetoothHeadset: Proxy object connected
,09-16 08:29:46.359  3064  3064 D HeadsetProfile: Bluetooth service connected
09-16 08:29:46.359  3470  3720 D BluetoothHeadset: Proxy object connected
09-16 08:29:46.361  5477  5477 D HeadsetProfile: Bluetooth service connected
,09-16 08:29:46.364   927   944 D BluetoothHeadset: Proxy object connected
,09-16 08:29:46.375  3470  3856 D BluetoothHeadset: Proxy object connected
09-16 08:29:46.376  3064  3386 D BluetoothHeadset: Proxy object connected
,09-16 08:29:46.376  3064  3064 D HeadsetProfile: Bluetooth service connected
,09-16 08:29:50.059  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:50.059  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:50.059  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:50.059  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 08:29:50.059  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:29:50.059  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:50.059  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:50.059  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 08:29:50.064  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 08:29:50.065  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:29:50.065  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@717c5d1 removed from the list
09-16 08:29:50.065  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 08:29:50.065  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:29:50.065  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:29:50.068  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:29:50.068  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@40b1836 added. We now have 4 listener(s)
09-16 08:29:50.069  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:29:50.074   927  3725 D WifiService: setWifiEnabled: false pid=5423, uid=10077
,09-16 08:29:50.074   927  3725 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 08:29:50.479   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:51.480   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:52.481   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:53.482   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:54.483   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:29:55.084  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:55.085   927  3489 D WifiService: setWifiEnabled: true pid=5423, uid=10077
,09-16 08:29:55.085   927  3489 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 08:29:55.096   506   926 D SoftapController: Softap fwReload - Ok
,09-16 08:29:55.102   506   926 D CommandListener: Setting iface cfg
,09-16 08:29:55.102   506   926 D CommandListener: Trying to bring down wlan0
09-16 08:29:55.104   506   926 D CommandListener: Clearing all IP addresses on wlan0
,09-16 08:29:55.110   927  2910 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 08:29:55.484   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:29:55.783   927  2910 D wifi    : set interface wlan0 flags (UP)
,09-16 08:29:55.784   927  2910 I WifiHAL : Initializing wifi
,09-16 08:29:55.784   927  2910 I WifiHAL : Creating socket
,09-16 08:29:55.790   927  2910 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-16 08:29:55.791   927  2910 D wifi    : Did set static halHandle = 0x7f7d55b040
09-16 08:29:55.791   927  2910 D wifi    : halHandle = 0x7f7d55b040, mVM = 0x7f99b8d140, mCls = 0x200f4a
09-16 08:29:55.791   927  2910 D wifi    : array field set
,09-16 08:29:55.791   927  2910 I WifiNative-HAL: interface[0] = wlan0
,09-16 08:29:55.792   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 08:29:55.794   927  5770 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547563614272
09-16 08:29:55.795   927  5770 D wifi    : waitForHalEvents called, vm = 0x7f99b8d140, obj = 0x200f4a, env = 0x7f79a7a580
,09-16 08:29:55.845  5771  5771 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 08:29:55.867  5771  5771 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 08:29:55.895   927  2910 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 08:29:55.895  5771  5771 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-16 08:29:55.895  5771  5771 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
09-16 08:29:55.899  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:55.901  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:29:55.914   927  2910 D WifiConfigStore: Loading config and enabling all networks 
,09-16 08:29:55.919  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:55.919  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:55.919  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:55.919  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:55.919  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:29:55.919  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:55.919  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:55.919  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 08:29:55.921  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 08:29:55.924  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:29:55.924  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:29:55.924  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:29:55.924  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:29:55.924  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:29:55.924  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 08:29:55.924  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 08:29:55.924  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 08:29:55.926  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 08:29:55.929   927  2910 D WifiConfigStore: loaded 0 passpoint configs
09-16 08:29:55.929   927  2910 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-16 08:29:55.930   927  2910 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 08:29:55.931   927  2910 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 08:29:55.932   927  2910 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-16 08:29:55.932   927  2910 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-16 08:29:55.932   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-16 08:29:55.933   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 08:29:55.935   927  2910 D WifiNative-HAL: Setting external_sim to 1
,09-16 08:29:55.935   927  2910 D wifi    : setting dfs flag to true, 0x7f7dea3060
09-16 08:29:55.936   927  2910 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 08:29:55.936   927  2910 D wifi    : setting scan oui 0x7f7dea3060
09-16 08:29:55.936   927  2910 D WifiHAL : Sending mac address OUI
09-16 08:29:55.936  4235  4235 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 08:29:55.940   927  2910 E native  : do suspend false
,09-16 08:29:55.951   927  2910 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-16 08:29:55.952   927   927 D RttService: SCAN_AVAILABLE : 3
09-16 08:29:55.952   506   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-16 08:29:55.952   927  3018 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 08:29:55.953   506   926 D CommandListener: Setting iface cfg
,09-16 08:29:55.957   927  2909 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
,09-16 08:29:55.957   927  2909 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 08:29:55.967   927  2909 D WifiNative-HAL: p2pGetDeviceAddress
09-16 08:29:55.967   927  2909 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 08:29:55.973   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=420077 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-16 08:29:59.161  5771  5771 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 08:29:59.170  5771  5771 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 08:29:59.175  5771  5771 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 08:29:59.181  5771  5771 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 08:29:59.204   927  2910 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-16 08:29:59.204   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-16 08:29:59.205   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 08:29:59.214   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 08:29:59.243   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 08:29:59.246  5771  5771 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-16 08:29:59.666  5771  5771 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-16 08:29:59.699  5771  5771 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-16 08:29:59.701  5771  5771 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-16 08:29:59.709   927  2910 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 08:29:59.709   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 08:29:59.709   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-16 08:29:59.727   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 08:29:59.740   506   926 D CommandListener: Setting iface cfg
,09-16 08:29:59.746   927  2910 D WifiStateMachine: Start Dhcp Watchdog 3
,09-16 08:29:59.751   927  5785 D DhcpClient: Receive thread started
,09-16 08:29:59.757   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:29:59.757   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-16 08:29:59.757   927  2912 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-16 08:29:59.838   927  2910 E native  : do suspend false
,09-16 08:29:59.852   927  5784 D DhcpClient: Broadcasting DHCPDISCOVER
,09-16 08:29:59.865   927  5785 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-16 08:29:59.865   927  5784 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-16 08:29:59.868   927  5784 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-16 08:29:59.888   927  5785 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-16 08:29:59.888   927  5784 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-16 08:29:59.891   506   926 D CommandListener: Setting iface cfg
,09-16 08:29:59.896   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-16 08:29:59.901   927  5784 D DhcpClient: Scheduling renewal in 86399s
,09-16 08:29:59.911   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-16 08:29:59.912   927  2910 D WifiConfigStore: No blacklist allowed without epno enabled
09-16 08:29:59.913   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-16 08:29:59.918   927  2912 D ConnectivityService: Adding iface wlan0 to network 102
,09-16 08:29:59.926   927  2910 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-16 08:29:59.964   927  2912 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-16 08:29:59.964   927  2912 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-16 08:29:59.966   927  2912 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-16 08:29:59.969   927  2912 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-16 08:29:59.970   927  2912 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-16 08:29:59.977   927  2912 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:29:59.981   927  2912 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-16 08:29:59.981   927  2912 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-16 08:29:59.981   927  2912 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-16 08:29:59.981   927  2910 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-16 08:29:59.981   927  2912 D ConnectivityService:    accepting network in place of null
09-16 08:29:59.981   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 08:29:59.982   927  2912 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 08:29:59.998   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=424101, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:30:00.005   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 08:30:00.031   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 08:30:00.034   927  2912 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-16 08:30:00.035   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 08:30:00.035  3413  3535 W QCNEJ   : |CORE| network available: 102
,09-16 08:30:00.036   927  2912 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-16 08:30:00.037  3413  3535 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-16 08:30:00.038   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-16 08:30:00.038  3413  3535 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-16 08:30:00.039  3413  3535 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-16 08:30:00.046  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:30:00.046  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:00.046  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:00.046  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:00.046  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:00.046  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:00.046  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:00.046  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:00.048  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:30:00.052  4810  4825 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 08:30:00.053  4810  4825 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 08:30:00.053  4810  4825 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-16 08:30:00.053  4810  4825 E SarControlService: no key has been found,reset the power
09-16 08:30:00.053  4810  4849 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 08:30:00.053  4810  4849 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 08:30:00.053  4810  4849 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 08:30:00.054  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 08:30:00.054  4839  4839 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 08:30:00.054  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:30:00.054  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:00.054  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:00.054  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:00.054  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:00.054  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:00.054  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:00.054  5423  5423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 08:30:00.055  4810  4849 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 08:30:00.055  4810  4849 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 08:30:00.055  4810  4849 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 08:30:00.055  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 08:30:00.055  4839  4839 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 08:30:00.057  5423  5423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:30:00.062  4839  4853 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e5bbfc5 HexData = [00000000f003000000000000ffffffff]
09-16 08:30:00.062  4839  4853 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 08:30:00.062  4839  4853 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-16 08:30:00.062  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 08:30:00.063  4810  4821 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-16 08:30:00.067  4839  4853 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e5bbfc5 HexData = [00000000f103000000000000ffffffff]
09-16 08:30:00.067  4839  4853 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 08:30:00.067  4839  4853 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-16 08:30:00.068  4839  4839 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-16 08:30:00.068  4810  4822 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 08:30:00.074  3850  3850 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-16 08:30:00.081   927  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-16 08:30:00.084  3850  3850 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-16 08:30:00.085  3850  3850 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 08:30:00.086  5550  5550 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 08:30:00.091  5550  5550 D SprintDMHelper: simOperator: 
09-16 08:30:00.091  5550  5550 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 08:30:00.101  3850  5126 I iu.UploadsManager: num queued entries: 0
,09-16 08:30:00.104  3850  5126 I iu.UploadsManager: num updated entries: 0
,09-16 08:30:00.106  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 08:30:00.106  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:00.106  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:00.106  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:00.106  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:00.106  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:00.106  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:00.106  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:00.108  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:00.108  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:00.109  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@40b1836 removed from the list
09-16 08:30:00.109  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:30:00.109  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:30:00.109  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:00.113  5423  5800 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-16 08:30:00.113  5423  5800 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-16 08:30:00.126  3850  5126 I iu.SyncManager: NEXT; no task
,09-16 08:30:00.131   927  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 12:30:00 GMT], X-Android-Received-Millis=[1474029000130], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474029000108]}
,09-16 08:30:00.131   927  2912 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 08:30:00.132   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-16 08:30:00.133   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-16 08:30:00.134   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-16 08:30:00.211  4235  5799 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-16 08:30:01.397   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,09-16 08:30:01.412   927  2912 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:30:01.419  3413  3535 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-16 08:30:01.419  3413  3535 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-16 08:30:03.123  5423  5800 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-16 08:30:03.123  5423  5807 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-16 08:30:03.124  5423  5807 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-16 08:30:03.124  5423  5800 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-16 08:30:03.125  5423  5807 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:30:03.125  5423  5800 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:30:03.128  5423  5800 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:30:03.128  5423  5807 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:30:03.129  5423  5800 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-16 08:30:03.132  5423  5810 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: IncomingSocketThread/Sender)
,09-16 08:30:03.132  5423  5807 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-16 08:30:03.135  5423  5809 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: OutgoingSocketThread/Sender)
,09-16 08:30:03.136  5423  5811 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Receiver)
,09-16 08:30:03.138  5423  5812 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver)
,09-16 08:30:03.138  5423  5811 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: OutgoingSocketThread/Receiver)
09-16 08:30:03.138  5423  5811 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-16 08:30:03.138  5423  5811 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-16 08:30:03.139  5423  5812 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver)
09-16 08:30:03.139  5423  5812 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-16 08:30:03.140  5423  5812 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-16 08:30:06.120  5423  5469 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-16 08:30:06.121  5423  5469 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-16 08:30:06.128  5423  5469 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9706979 Bundle[{}]
,09-16 08:30:06.130  5423  5469 I io.jxcore.node.LifeCycleMonitor: start: OK
09-16 08:30:06.130  5423  5469 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-16 08:30:06.131  5423  5469 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-16 08:30:06.132  5423  5469 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-16 08:30:06.132  5423  5469 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-16 08:30:06.133  5423  5469 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-16 08:30:06.139  5423  5469 I System.out: Running OutgoingSocketThread
,09-16 08:30:06.141  5423  5813 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-16 08:30:06.142  5423  5813 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-16 08:30:07.987   927  2912 D ConnectivityService: handlePromptUnvalidated 102
,09-16 08:30:09.152  5423  5813 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-16 08:30:09.152  5423  5813 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-16 08:30:09.153  5423  5813 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 08:30:09.154  5423  5813 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 08:30:09.154  5423  5814 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-16 08:30:09.154  5423  5814 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-16 08:30:09.155  5423  5814 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 08:30:09.155  5423  5813 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-16 08:30:09.159  5423  5814 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:30:09.161  5423  5816 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
,09-16 08:30:09.165  5423  5817 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Receiver)
,09-16 08:30:09.167  5423  5814 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-16 08:30:09.167  5423  5817 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: OutgoingSocketThread/Receiver)
09-16 08:30:09.168  5423  5817 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-16 08:30:09.168  5423  5818 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender)
09-16 08:30:09.168  5423  5817 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-16 08:30:09.171  5423  5819 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
09-16 08:30:09.172  5423  5819 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
09-16 08:30:09.173  5423  5819 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-16 08:30:09.173  5423  5819 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-16 08:30:10.977   927  2910 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 23, 24 -> obsolete
,09-16 08:30:12.151  5423  5469 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-16 08:30:12.153  5423  5469 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-16 08:30:12.153  5423  5469 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-16 08:30:12.159  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 08:30:12.159  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ddf337 added. We now have 3 listener(s)
,09-16 08:30:12.164  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:30:12.164  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 08:30:12.164  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 08:30:12.164  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:30:12.165  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72580a4 added. We now have 4 listener(s)
09-16 08:30:12.165  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 08:30:12.166  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 08:30:12.172  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:12.178  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:30:12.178  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:12.178  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:12.178  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:12.178  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:12.178  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:12.178  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:12.178  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:12.182  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:30:12.182  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:30:12.183  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:30:12.183  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:30:12.183  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:30:12.183  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:30:12.183  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:12.183  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:30:12.183  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 08:30:12.184  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ddf337 removed from the list
,09-16 08:30:12.184  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:12.184  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72580a4 removed from the list
,09-16 08:30:12.186  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:12.190  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:12.191  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 08:30:12.191  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:12.192  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:12.192  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:30:12.194  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:30:12.194  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:30:12.194  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:12.194  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72580a4 not in the list
09-16 08:30:12.194  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:12.194  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:30:12.196  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:30:12.196  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:30:12.196  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:12.196  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72580a4 not in the list
09-16 08:30:12.196  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 08:30:12.196  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:12.196  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:12.196  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ddf337 not in the list
09-16 08:30:12.197  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 08:30:12.197  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16881c2 added. We now have 3 listener(s)
09-16 08:30:12.199  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 08:30:12.199  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 08:30:12.200  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 08:30:12.200  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:30:12.200  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f148bd3 added. We now have 4 listener(s)
09-16 08:30:12.200  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:30:12.201  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 08:30:12.206  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:12.212  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:30:12.212  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:12.212  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:12.212  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:12.212  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:12.212  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:12.212  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:12.212  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:12.215  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:12.215  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:30:12.215  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:30:12.216  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 08:30:12.216  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 08:30:12.216  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:30:12.216  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 08:30:12.219  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:30:12.221  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 08:30:12.221  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 08:30:12.223  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:12.225  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 08:30:12.226  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:30:12.227  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 08:30:12.231  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 08:30:12.231  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-16 08:30:12.231  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 08:30:12.232  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:12.236  5715  5755 D BtGatt.GattService: registerClient() - UUID=3d33e0a9-e0f4-41ba-83c9-e125bdaf8639
,09-16 08:30:12.238  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=3d33e0a9-e0f4-41ba-83c9-e125bdaf8639, clientIf=5
,09-16 08:30:12.239  5423  5434 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 08:30:12.240  5715  5745 D BtGatt.GattService: start scan with filters
,09-16 08:30:12.245  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 08:30:12.245  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 08:30:12.245  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 08:30:12.245  5715  5734 D BtGatt.ScanManager: handling starting scan
09-16 08:30:12.245  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 08:30:12.249  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:30:12.249  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 08:30:12.249  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:30:12.250  5715  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ba1f572
09-16 08:30:12.251  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 08:30:12.254  5423  5469 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 08:30:12.254  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 08:30:12.254  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 08:30:12.254  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:30:12.254  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 08:30:12.254  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:30:12.254  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 08:30:12.254  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 08:30:12.254  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 08:30:12.254  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 08:30:12.255  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 08:30:12.256  5423  5469 D BluetoothAdapter: STATE_ON
09-16 08:30:12.257  5715  5745 D BtGatt.GattService: stopScan() - queue size =1
,09-16 08:30:12.258  5715  5725 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 08:30:12.258  5715  5731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-16 08:30:12.258  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:12.259  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 08:30:12.259  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 08:30:12.259  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 08:30:12.259  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 08:30:12.259  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 08:30:12.259  5715  5734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 08:30:12.261  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:12.261  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 08:30:12.261  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 08:30:12.261  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 08:30:12.262  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 08:30:12.264  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:12.264  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:12.264  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 08:30:12.268  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 08:30:12.268  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:12.268  5715  5734 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:30:12.268  5715  5734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 08:30:12.282  5715  5731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 08:30:12.282  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:12.289  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 08:30:12.289  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:12.297  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 08:30:12.297  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:12.298  5715  5734 D BtGatt.ScanManager: stopping BLe Batch
,09-16 08:30:12.305  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 08:30:12.305  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:12.305  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:30:12.311  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 08:30:12.312  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:12.766  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:30:12.766  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:30:12.791  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:30:15.264  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:30:15.265  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:30:15.265  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:30:15.265  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:30:15.265  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:15.265  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:30:15.266  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 08:30:15.266  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16881c2 removed from the list
09-16 08:30:15.266  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:15.266  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f148bd3 removed from the list
09-16 08:30:15.267  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:30:15.267  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:15.268  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:15.269  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:15.272  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:30:15.272  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:30:15.272  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:15.272  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f148bd3 not in the list
09-16 08:30:15.273  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:15.273  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:30:15.276  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 08:30:15.276  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 08:30:15.276  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 08:30:15.276  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f148bd3 not in the list
09-16 08:30:15.276  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:30:15.277  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:15.277  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:30:15.277  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16881c2 not in the list
09-16 08:30:15.278  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 08:30:15.279  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d96403c added. We now have 3 listener(s)
09-16 08:30:15.283  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 08:30:15.283  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 08:30:15.283  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 08:30:15.283  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:30:15.283  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af3d1c5 added. We now have 4 listener(s)
,09-16 08:30:15.284  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:30:15.285  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 08:30:15.289  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:15.297  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:30:15.297  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:15.297  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:15.297  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:15.297  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:15.297  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:15.297  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:15.297  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:15.300  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:30:15.301  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:30:15.301  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 08:30:15.302  5423  5469 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-16 08:30:15.302  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-16 08:30:15.303  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 08:30:15.304  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 08:30:15.304  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 08:30:15.304  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:15.306  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-16 08:30:15.307  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 08:30:15.307  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 08:30:15.307  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 08:30:15.307  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 08:30:15.307  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:30:15.307  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 08:30:15.305  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:30:15.308  5423  5820 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:30:15.314  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 08:30:15.313  5725  5725 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[28481]" dev="sockfs" ino=28481 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:30:15.314  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 08:30:15.314  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 08:30:15.314  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 08:30:15.318  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 08:30:15.319  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:30:15.319  5423  5820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-16 08:30:15.320  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 08:30:15.313  5725  5725 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[28481]" dev="sockfs" ino=28481 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 08:30:15.324  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-16 08:30:15.325  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:30:15.325  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-16 08:30:15.326  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:15.326  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:15.326  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-16 08:30:15.327  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:15.332  5715  5745 D BtGatt.GattService: registerClient() - UUID=4c9ab58f-a613-429d-b95c-4c2b3c725d68
,09-16 08:30:15.332  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=4c9ab58f-a613-429d-b95c-4c2b3c725d68, clientIf=5
09-16 08:30:15.332  5423  5434 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 08:30:15.334  5715  5733 D BtGatt.AdvertiseManager: message : 0
,09-16 08:30:15.337  5715  5733 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 08:30:15.348  5715  5731 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 08:30:15.354  5715  5731 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 08:30:15.355  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-16 08:30:15.356  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 08:30:15.357  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 08:30:15.359  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 08:30:15.359  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 08:30:15.359  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 08:30:15.359  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 08:30:15.359  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-16 08:30:15.359  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-16 08:30:15.361  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-16 08:30:15.362  5423  5423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-16 08:30:15.362  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 08:30:15.863  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 08:30:15.864  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 08:30:15.864  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:30:18.362  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:30:18.363  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-16 08:30:18.363  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 08:30:18.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-16 08:30:18.364  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-16 08:30:18.364  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 08:30:18.364  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 08:30:18.364  5423  5820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 08:30:18.364  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 08:30:18.364  5423  5820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-16 08:30:18.365  5423  5820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 08:30:18.365  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:30:18.365  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 08:30:18.365  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 08:30:18.365  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 08:30:18.365  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 08:30:18.365  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 08:30:18.368  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:18.368  5423  5469 D BluetoothLeScanner: could not find callback wrapper
09-16 08:30:18.369  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 08:30:18.369  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-16 08:30:18.371  5715  5733 D BtGatt.AdvertiseManager: message : 1
09-16 08:30:18.375  5715  5733 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 08:30:18.387  5715  5731 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-16 08:30:18.388  5715  5731 D BtGatt.GattService: Client app is not null!
09-16 08:30:18.389  5715  5745 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 08:30:18.389  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 08:30:18.390  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-16 08:30:18.390  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-16 08:30:18.390  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-16 08:30:18.390  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-16 08:30:18.392  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:18.392  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 08:30:18.392  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 08:30:18.393  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 08:30:18.395  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:30:18.395  5423  5423 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 08:30:18.395  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:18.395  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:30:18.395  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 08:30:18.396  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d96403c removed from the list
09-16 08:30:18.396  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:18.396  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:18.396  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af3d1c5 removed from the list
09-16 08:30:18.396  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:18.396  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:30:18.396  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:30:18.396  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:18.397  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:18.397  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:18.399  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:30:18.400  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 08:30:18.400  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:18.400  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af3d1c5 not in the list
09-16 08:30:18.400  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:30:18.400  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:18.403  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:30:18.403  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:30:18.403  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:18.403  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af3d1c5 not in the list
09-16 08:30:18.403  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:30:18.403  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:18.403  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:18.403  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d96403c not in the list
,09-16 08:30:18.404  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 08:30:18.404  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7fae6 added. We now have 3 listener(s)
09-16 08:30:18.407  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:30:18.407  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 08:30:18.407  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 08:30:18.407  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 08:30:18.407  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dc1827 added. We now have 4 listener(s)
09-16 08:30:18.407  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 08:30:18.408  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 08:30:18.412  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:18.418  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:30:18.418  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:18.418  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:18.418  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:18.418  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:18.418  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:18.418  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:18.418  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:18.421  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:18.421  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 08:30:18.422  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-16 08:30:18.422  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 08:30:18.422  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 08:30:18.422  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:30:18.422  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 08:30:18.427  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:18.429  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 08:30:18.429  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 08:30:18.431  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:18.435  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 08:30:18.435  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:30:18.435  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 08:30:18.439  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 08:30:18.439  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 08:30:18.439  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 08:30:18.440  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:18.444  5715  5755 D BtGatt.GattService: registerClient() - UUID=acf31274-2d3e-4afc-bcbe-daedc67a844c
09-16 08:30:18.445  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=acf31274-2d3e-4afc-bcbe-daedc67a844c, clientIf=5
,09-16 08:30:18.445  5423  5434 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 08:30:18.445  5715  5745 D BtGatt.GattService: start scan with filters
,09-16 08:30:18.448  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 08:30:18.448  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 08:30:18.448  5715  5734 D BtGatt.ScanManager: handling starting scan
09-16 08:30:18.448  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 08:30:18.448  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 08:30:18.451  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:30:18.451  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 08:30:18.451  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:30:18.453  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 08:30:18.454  5715  5731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 08:30:18.454  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:18.455  5715  5734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 08:30:18.461  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 08:30:18.461  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:18.461  5715  5734 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:30:18.461  5715  5734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 08:30:18.471  5715  5731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 08:30:18.471  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:18.477  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 08:30:18.477  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:18.897  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:30:18.952  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 08:30:18.952  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:30:18.953  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:30:20.488   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:30:20.489   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:30:21.463  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:30:21.463  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:30:21.464  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-16 08:30:21.464  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:30:21.464  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 08:30:21.464  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:30:21.464  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 08:30:21.464  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 08:30:21.465  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 08:30:21.465  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 08:30:21.465  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 08:30:21.467  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:21.469  5715  5726 D BtGatt.GattService: stopScan() - queue size =1
09-16 08:30:21.476  5715  5742 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 08:30:21.478  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 08:30:21.478  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 08:30:21.478  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 08:30:21.478  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 08:30:21.479  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 08:30:21.482  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 08:30:21.482  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 08:30:21.482  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 08:30:21.482  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 08:30:21.483  5715  5715 D BtGatt.ScanManager: awakened up at time 445587
09-16 08:30:21.485  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:30:21.487  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 08:30:21.488  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:21.488  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:21.488  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:21.488  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 08:30:21.488  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 08:30:21.488  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:21.488  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7fae6 removed from the list
,09-16 08:30:21.488  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:21.488  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dc1827 removed from the list
09-16 08:30:21.488  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
09-16 08:30:21.488  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:30:21.490  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:21.490  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:30:21.492  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 08:30:21.492  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 08:30:21.492  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:21.492  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dc1827 not in the list
09-16 08:30:21.492  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:30:21.492  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:21.494  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:30:21.494  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:30:21.494  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:21.494  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dc1827 not in the list
09-16 08:30:21.494  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:30:21.494  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:21.494  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:21.495  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7fae6 not in the list
,09-16 08:30:21.495  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 08:30:21.496  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6e5040 added. We now have 3 listener(s)
09-16 08:30:21.498  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:30:21.498  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 08:30:21.498  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 08:30:21.498  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:30:21.498  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bebdb79 added. We now have 4 listener(s)
09-16 08:30:21.499  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 08:30:21.499  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 08:30:21.505  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:21.511  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:30:21.511  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:21.511  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:21.511  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:21.511  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:21.511  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:21.511  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:21.511  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:21.514  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:30:21.514  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:30:21.514  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:30:21.514  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:30:21.514  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:30:21.514  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:30:21.514  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:30:21.515  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 08:30:21.515  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 08:30:21.515  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6e5040 removed from the list
09-16 08:30:21.515  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:21.515  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bebdb79 removed from the list
,09-16 08:30:21.517  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:21.517  5423  5469 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 08:30:21.517  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:21.518  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:21.518  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:30:21.520  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:30:21.521  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:30:21.521  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:21.521  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bebdb79 not in the list
09-16 08:30:21.521  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:21.521  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 08:30:21.522  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:21.524  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 08:30:21.524  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:30:21.524  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 08:30:21.524  5423  5469 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bebdb79 not in the list
09-16 08:30:21.524  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 08:30:21.524  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 08:30:21.524  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 08:30:21.524  5423  5469 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6e5040 not in the list
09-16 08:30:21.525  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-16 08:30:21.525  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 08:30:21.525  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-16 08:30:21.526  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:30:21.526  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:30:21.526  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:30:21.545  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-16 08:30:21.545  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:21.545  5715  5734 D BtGatt.ScanManager: stopping BLe Batch
,09-16 08:30:21.550  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 08:30:21.550  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:21.550  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:30:21.564  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-16 08:30:21.564  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:21.564  5715  5731 D BtGatt.GattService: current time is 445668033264
09-16 08:30:21.564  5715  5731 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -87, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -81, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 08:30:21.565  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-16 08:30:21.566  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 08:30:21.566  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 08:30:21.566  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 08:30:21.566  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-16 08:30:21.989  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:30:23.538  5423  5821 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,09-16 08:30:25.537  5423  5469 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
,09-16 08:30:25.537  5423  5469 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,09-16 08:30:25.541  5423  5822 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
09-16 08:30:25.542  5423  5822 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
09-16 08:30:25.542  5423  5822 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-16 08:30:25.546  5423  5469 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 08:30:25.552  5423  5823 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-16 08:30:25.552  5423  5823 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
09-16 08:30:25.553  5423  5823 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-16 08:30:25.558  5423  5469 I jxcore-log: Total number of executed tests:  82
09-16 08:30:25.558  5423  5469 I jxcore-log: 
,09-16 08:30:25.559  5423  5469 I jxcore-log: Number of passed tests:  82
09-16 08:30:25.559  5423  5469 I jxcore-log: 
,09-16 08:30:25.559  5423  5469 I jxcore-log: Number of failed tests:  0
09-16 08:30:25.559  5423  5469 I jxcore-log: 
09-16 08:30:25.559  5423  5469 I jxcore-log: Number of ignored tests:  0
09-16 08:30:25.559  5423  5469 I jxcore-log: 
,09-16 08:30:25.559  5423  5469 I jxcore-log: Total duration:  100973
09-16 08:30:25.559  5423  5469 I jxcore-log: 
,09-16 08:30:25.564  5423  5469 I jxcore-log: Unit Test app is loaded
09-16 08:30:25.564  5423  5469 I jxcore-log: 
,09-16 08:30:25.564  5423  5821 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-16 08:30:25.576  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.576  5423  5469 I jxcore-log: 
,09-16 08:30:25.585  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.585  5423  5469 I jxcore-log: 
,09-16 08:30:25.585  5423  5423 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-16 08:30:25.586  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.586  5423  5469 I jxcore-log: 
,09-16 08:30:25.588  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.588  5423  5469 I jxcore-log: 
,09-16 08:30:25.591  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 08:30:25.591  5423  5469 I jxcore-log: 
,09-16 08:30:25.593  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:30:25.593  5423  5469 I jxcore-log: 
,09-16 08:30:25.596  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.596  5423  5469 I jxcore-log: 
,09-16 08:30:25.599  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.599  5423  5469 I jxcore-log: 
,09-16 08:30:25.600  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 08:30:25.600  5423  5469 I jxcore-log: 
,09-16 08:30:25.601  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:30:25.601  5423  5469 I jxcore-log: 
,09-16 08:30:25.602  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:30:25.602  5423  5469 I jxcore-log: 
,09-16 08:30:25.604  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.604  5423  5469 I jxcore-log: 
09-16 08:30:25.604  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.604  5423  5469 I jxcore-log: 
09-16 08:30:25.605  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.605  5423  5469 I jxcore-log: 
09-16 08:30:25.606  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.606  5423  5469 I jxcore-log: 
,09-16 08:30:25.607  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.607  5423  5469 I jxcore-log: 
,09-16 08:30:25.609  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.609  5423  5469 I jxcore-log: 
,09-16 08:30:25.610  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.610  5423  5469 I jxcore-log: 
,09-16 08:30:25.611  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.611  5423  5469 I jxcore-log: 
,09-16 08:30:25.612  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.612  5423  5469 I jxcore-log: 
,09-16 08:30:25.613  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.613  5423  5469 I jxcore-log: 
,09-16 08:30:25.614  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.614  5423  5469 I jxcore-log: 
09-16 08:30:25.615  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.615  5423  5469 I jxcore-log: 
09-16 08:30:25.616  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.616  5423  5469 I jxcore-log: 
,09-16 08:30:25.617  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.617  5423  5469 I jxcore-log: 
09-16 08:30:25.618  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.618  5423  5469 I jxcore-log: 
,09-16 08:30:25.619  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.619  5423  5469 I jxcore-log: 
,09-16 08:30:25.620  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.620  5423  5469 I jxcore-log: 
,09-16 08:30:25.621  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.621  5423  5469 I jxcore-log: 
09-16 08:30:25.622  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.622  5423  5469 I jxcore-log: 
09-16 08:30:25.622  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.622  5423  5469 I jxcore-log: 
09-16 08:30:25.623  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.623  5423  5469 I jxcore-log: 
,09-16 08:30:25.624  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.624  5423  5469 I jxcore-log: 
,09-16 08:30:25.625  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.625  5423  5469 I jxcore-log: 
09-16 08:30:25.626  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.626  5423  5469 I jxcore-log: 
,09-16 08:30:25.627  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.627  5423  5469 I jxcore-log: 
,09-16 08:30:25.628  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.628  5423  5469 I jxcore-log: 
,09-16 08:30:25.628  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.628  5423  5469 I jxcore-log: 
,09-16 08:30:25.630  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.630  5423  5469 I jxcore-log: 
,09-16 08:30:25.630  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 08:30:25.630  5423  5469 I jxcore-log: 
09-16 08:30:25.631  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.631  5423  5469 I jxcore-log: 
09-16 08:30:25.632  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 08:30:25.632  5423  5469 I jxcore-log: 
09-16 08:30:25.632  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.632  5423  5469 I jxcore-log: 
09-16 08:30:25.632  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.632  5423  5469 I jxcore-log: 
,09-16 08:30:25.634  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.634  5423  5469 I jxcore-log: 
,09-16 08:30:25.635  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.635  5423  5469 I jxcore-log: 
,09-16 08:30:25.636  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.636  5423  5469 I jxcore-log: 
,09-16 08:30:25.637  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:30:25.637  5423  5469 I jxcore-log: 
,09-16 08:30:25.638  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.638  5423  5469 I jxcore-log: 
,09-16 08:30:25.638  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 08:30:25.638  5423  5469 I jxcore-log: 
,09-16 08:30:25.639  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.639  5423  5469 I jxcore-log: 
,09-16 08:30:25.640  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:30:25.640  5423  5469 I jxcore-log: 
,09-16 08:30:25.641  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 08:30:25.641  5423  5469 I jxcore-log: 
,09-16 08:30:25.641  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:25.641  5423  5469 I jxcore-log: 
09-16 08:30:25.642  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:30:25.642  5423  5469 I jxcore-log: 
,09-16 08:30:25.648  5423  5469 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-16 08:30:25.648  5423  5469 I jxcore-log:   bluetooth: 'on',
09-16 08:30:25.648  5423  5469 I jxcore-log:   wifi: 'on',
09-16 08:30:25.648  5423  5469 I jxcore-log:   cellular: 'doNotCare',
09-16 08:30:25.648  5423  5469 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-16 08:30:25.648  5423  5469 I jxcore-log: 
,09-16 08:30:25.655  5423  5469 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-16 08:30:25.655  5423  5469 I jxcore-log:   bluetooth: 'on',
09-16 08:30:25.655  5423  5469 I jxcore-log:   wifi: 'on',
09-16 08:30:25.655  5423  5469 I jxcore-log:   cellular: 'doNotCare',
09-16 08:30:25.655  5423  5469 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-16 08:30:25.655  5423  5469 I jxcore-log: 
,09-16 08:30:25.656  5423  5469 I jxcore-log: My device name is: Huawei-Nexus 6P
09-16 08:30:25.656  5423  5469 I jxcore-log: 
,09-16 08:30:25.657  5423  5469 I jxcore-log: WARN testUtils: myNameCallback not set!
09-16 08:30:25.657  5423  5469 I jxcore-log: 
09-16 08:30:25.657  5423  5469 I jxcore-log: Running for WIFI network type
09-16 08:30:25.657  5423  5469 I jxcore-log: 
,09-16 08:30:27.461  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-16 08:30:27.461  5423  5469 I jxcore-log: 
,09-16 08:30:27.764  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-16 08:30:27.764  5423  5469 I jxcore-log: 
,09-16 08:30:27.781  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-16 08:30:27.781  5423  5469 I jxcore-log: 
,09-16 08:30:27.785  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-16 08:30:27.785  5423  5469 I jxcore-log: 
,09-16 08:30:27.790  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-16 08:30:27.790  5423  5469 I jxcore-log: 
,09-16 08:30:27.829  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-16 08:30:27.829  5423  5469 I jxcore-log: 
,09-16 08:30:27.840  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-16 08:30:27.840  5423  5469 I jxcore-log: 
,09-16 08:30:27.843  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-16 08:30:27.843  5423  5469 I jxcore-log: 
,09-16 08:30:28.350  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-16 08:30:28.350  5423  5469 I jxcore-log: 
,09-16 08:30:28.358  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-16 08:30:28.358  5423  5469 I jxcore-log: 
,09-16 08:30:28.364  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-16 08:30:28.364  5423  5469 I jxcore-log: 
,09-16 08:30:28.527  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-16 08:30:28.527  5423  5469 I jxcore-log: 
,09-16 08:30:29.570  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-16 08:30:29.570  5423  5469 I jxcore-log: 
,09-16 08:30:29.604  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-16 08:30:29.604  5423  5469 I jxcore-log: 
,09-16 08:30:29.610  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-16 08:30:29.610  5423  5469 I jxcore-log: 
,09-16 08:30:29.699  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-16 08:30:29.699  5423  5469 I jxcore-log: 
,09-16 08:30:29.714  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-16 08:30:29.714  5423  5469 I jxcore-log: 
,09-16 08:30:29.718  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-16 08:30:29.718  5423  5469 I jxcore-log: 
,09-16 08:30:29.722  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-16 08:30:29.722  5423  5469 I jxcore-log: 
,09-16 08:30:29.732  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-16 08:30:29.732  5423  5469 I jxcore-log: 
,09-16 08:30:29.836  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-16 08:30:29.836  5423  5469 I jxcore-log: 
,09-16 08:30:29.854  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-16 08:30:29.854  5423  5469 I jxcore-log: 
,09-16 08:30:29.878  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-16 08:30:29.878  5423  5469 I jxcore-log: 
,09-16 08:30:29.889  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-16 08:30:29.889  5423  5469 I jxcore-log: 
,09-16 08:30:29.899  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-16 08:30:29.899  5423  5469 I jxcore-log: 
,09-16 08:30:29.922  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-16 08:30:29.922  5423  5469 I jxcore-log: 
,09-16 08:30:29.926  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-16 08:30:29.926  5423  5469 I jxcore-log: 
,09-16 08:30:29.945  5423  5469 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-16 08:30:29.945  5423  5469 I jxcore-log: 
,09-16 08:30:29.954  5423  5469 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-16 08:30:29.955  5423  5469 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-16 08:30:29.955  5423  5469 I jxcore-log: 
,09-16 08:30:29.956  5423  5469 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-16 08:30:29.956  5423  5469 I jxcore-log: 
09-16 08:30:29.956  5423  5469 I jxcore-log: ThaliTape :: Started ThaliTape
09-16 08:30:29.956  5423  5469 I jxcore-log: 
,09-16 08:30:29.959  5423  5469 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-16 08:30:29.959  5423  5469 I jxcore-log: 
,09-16 08:30:30.053  5423  5469 I jxcore-log: ThaliTape :: Connected to the test server
09-16 08:30:30.053  5423  5469 I jxcore-log: 
,09-16 08:30:30.382  5423  5469 I jxcore-log: TAP version 13
09-16 08:30:30.382  5423  5469 I jxcore-log: 
,09-16 08:30:30.386  5423  5469 I jxcore-log: # setup
09-16 08:30:30.386  5423  5469 I jxcore-log: 
,09-16 08:30:31.576  5423  5469 I jxcore-log: # 1. calling createNativeListener directly rejects
09-16 08:30:31.576  5423  5469 I jxcore-log: 
,09-16 08:30:31.644  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:31.644  5423  5469 I jxcore-log: 
,09-16 08:30:31.653  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 42203
09-16 08:30:31.653  5423  5469 I jxcore-log: 
,09-16 08:30:31.665  5423  5469 I jxcore-log: ok 1 Should throw
09-16 08:30:31.665  5423  5469 I jxcore-log: 
,09-16 08:30:31.670  5423  5469 I jxcore-log: # teardown
09-16 08:30:31.670  5423  5469 I jxcore-log: 
,09-16 08:30:31.749  5423  5469 I jxcore-log: # setup
09-16 08:30:31.749  5423  5469 I jxcore-log: 
,09-16 08:30:31.810  5423  5469 I jxcore-log: # 2. emits incomingConnectionState
09-16 08:30:31.810  5423  5469 I jxcore-log: 
,09-16 08:30:31.915  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:31.915  5423  5469 I jxcore-log: 
,09-16 08:30:31.920  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 43094
09-16 08:30:31.920  5423  5469 I jxcore-log: 
,09-16 08:30:31.936  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:31.936  5423  5469 I jxcore-log: 
,09-16 08:30:31.940  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:31.940  5423  5469 I jxcore-log: 
,09-16 08:30:31.956  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:31.956  5423  5469 I jxcore-log: 
,09-16 08:30:31.962  5423  5469 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-16 08:30:31.962  5423  5469 I jxcore-log: 
,09-16 08:30:31.985  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:31.985  5423  5469 I jxcore-log: 
,09-16 08:30:31.986  5423  5469 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-16 08:30:31.986  5423  5469 I jxcore-log: 
,09-16 08:30:31.992  5423  5469 I jxcore-log: # teardown
09-16 08:30:31.992  5423  5469 I jxcore-log: 
,09-16 08:30:32.107  5423  5469 I jxcore-log: # setup
09-16 08:30:32.107  5423  5469 I jxcore-log: 
,09-16 08:30:32.206  5423  5469 I jxcore-log: # 3. emits routerPortConnectionFailed
09-16 08:30:32.206  5423  5469 I jxcore-log: 
,09-16 08:30:32.282  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:32.282  5423  5469 I jxcore-log: 
,09-16 08:30:32.289  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 45826
09-16 08:30:32.289  5423  5469 I jxcore-log: 
,09-16 08:30:32.299  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:32.299  5423  5469 I jxcore-log: 
,09-16 08:30:32.302  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:32.302  5423  5469 I jxcore-log: 
,09-16 08:30:32.304  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:32.304  5423  5469 I jxcore-log: 
,09-16 08:30:32.336  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:32.336  5423  5469 I jxcore-log: 
,09-16 08:30:32.338  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:32.338  5423  5469 I jxcore-log: 
,09-16 08:30:32.344  5423  5469 I jxcore-log: DEBUG createNativeListener: 
09-16 08:30:32.344  5423  5469 I jxcore-log: 
,09-16 08:30:32.345  5423  5469 I jxcore-log: ok 4 tried to connect to right port
09-16 08:30:32.345  5423  5469 I jxcore-log: 
09-16 08:30:32.345  5423  5469 I jxcore-log: ok 5 failed due to refused connection
09-16 08:30:32.345  5423  5469 I jxcore-log: 
09-16 08:30:32.346  5423  5469 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-16 08:30:32.346  5423  5469 I jxcore-log: 
,09-16 08:30:32.348  5423  5469 I jxcore-log: # teardown
09-16 08:30:32.348  5423  5469 I jxcore-log: 
,09-16 08:30:32.351  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:32.351  5423  5469 I jxcore-log: 
,09-16 08:30:32.417  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:32.417  5423  5469 I jxcore-log: 
,09-16 08:30:32.420  5423  5469 I jxcore-log: # setup
09-16 08:30:32.420  5423  5469 I jxcore-log: 
09-16 08:30:32.421  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:32.421  5423  5469 I jxcore-log: 
,09-16 08:30:32.509  5423  5469 I jxcore-log: # 4. native server connections all up
09-16 08:30:32.509  5423  5469 I jxcore-log: 
,09-16 08:30:32.589  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:32.589  5423  5469 I jxcore-log: 
,09-16 08:30:32.618  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 37184
09-16 08:30:32.618  5423  5469 I jxcore-log: 
,09-16 08:30:32.629  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:32.629  5423  5469 I jxcore-log: 
,09-16 08:30:32.631  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:32.631  5423  5469 I jxcore-log: 
,09-16 08:30:32.633  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:32.633  5423  5469 I jxcore-log: 
,09-16 08:30:32.667  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:32.667  5423  5469 I jxcore-log: 
,09-16 08:30:32.672  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:32.672  5423  5469 I jxcore-log: 
,09-16 08:30:32.675  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:32.675  5423  5469 I jxcore-log: 
,09-16 08:30:32.678  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:32.678  5423  5469 I jxcore-log: 
,09-16 08:30:32.705  5423  5469 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-16 08:30:32.705  5423  5469 I jxcore-log: 
,09-16 08:30:32.705  5423  5469 I jxcore-log: ok 8 Send/recvd #1 should be same
09-16 08:30:32.705  5423  5469 I jxcore-log: 
,09-16 08:30:32.709  5423  5469 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-16 08:30:32.709  5423  5469 I jxcore-log: 
,09-16 08:30:32.709  5423  5469 I jxcore-log: ok 10 Send/recvd #2 should be same
09-16 08:30:32.709  5423  5469 I jxcore-log: 
09-16 08:30:32.712  5423  5469 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-16 08:30:32.712  5423  5469 I jxcore-log: 
,09-16 08:30:32.720  5423  5469 I jxcore-log: # teardown
09-16 08:30:32.720  5423  5469 I jxcore-log: 
,09-16 08:30:32.761  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:32.761  5423  5469 I jxcore-log: 
,09-16 08:30:32.763  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:32.763  5423  5469 I jxcore-log: 
,09-16 08:30:32.765  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:32.765  5423  5469 I jxcore-log: 
,09-16 08:30:32.768  5423  5469 I jxcore-log: # setup
09-16 08:30:32.768  5423  5469 I jxcore-log: 
,09-16 08:30:32.769  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:32.769  5423  5469 I jxcore-log: 
,09-16 08:30:32.898  5423  5469 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-16 08:30:32.898  5423  5469 I jxcore-log: 
,09-16 08:30:32.988  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:32.988  5423  5469 I jxcore-log: 
,09-16 08:30:32.994  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 43580
09-16 08:30:32.994  5423  5469 I jxcore-log: 
,09-16 08:30:33.005  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:33.005  5423  5469 I jxcore-log: 
,09-16 08:30:33.007  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:33.007  5423  5469 I jxcore-log: 
,09-16 08:30:33.010  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:33.010  5423  5469 I jxcore-log: 
,09-16 08:30:33.029  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:33.029  5423  5469 I jxcore-log: 
,09-16 08:30:33.033  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:33.033  5423  5469 I jxcore-log: 
,09-16 08:30:33.048  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:33.048  5423  5469 I jxcore-log: 
,09-16 08:30:33.062  5423  5469 I jxcore-log: ok 12 socket shouldn't close until after stream
09-16 08:30:33.062  5423  5469 I jxcore-log: 
,09-16 08:30:33.063  5423  5469 I jxcore-log: ok 13 incoming remains open
09-16 08:30:33.063  5423  5469 I jxcore-log: 
,09-16 08:30:33.066  5423  5469 I jxcore-log: # teardown
09-16 08:30:33.066  5423  5469 I jxcore-log: 
,09-16 08:30:33.218  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:33.218  5423  5469 I jxcore-log: 
,09-16 08:30:33.227  5423  5469 I jxcore-log: # setup
09-16 08:30:33.227  5423  5469 I jxcore-log: 
,09-16 08:30:33.229  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:33.229  5423  5469 I jxcore-log: 
,09-16 08:30:33.340  5423  5469 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-16 08:30:33.340  5423  5469 I jxcore-log: 
,09-16 08:30:33.399  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:33.399  5423  5469 I jxcore-log: 
,09-16 08:30:33.404  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 41796
09-16 08:30:33.404  5423  5469 I jxcore-log: 
,09-16 08:30:33.416  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:33.416  5423  5469 I jxcore-log: 
,09-16 08:30:33.418  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:33.418  5423  5469 I jxcore-log: 
,09-16 08:30:33.421  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:33.421  5423  5469 I jxcore-log: 
,09-16 08:30:33.432  5423  5469 I jxcore-log: ok 14 we should not have gotten an error
09-16 08:30:33.432  5423  5469 I jxcore-log: 
,09-16 08:30:33.445  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:33.445  5423  5469 I jxcore-log: 
,09-16 08:30:33.450  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:33.450  5423  5469 I jxcore-log: 
,09-16 08:30:33.461  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:33.461  5423  5469 I jxcore-log: 
,09-16 08:30:33.464  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:33.464  5423  5469 I jxcore-log: 
,09-16 08:30:33.472  5423  5469 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-16 08:30:33.472  5423  5469 I jxcore-log: 
,09-16 08:30:33.473  5423  5469 I jxcore-log: ok 16 incoming is cleaned up
09-16 08:30:33.473  5423  5469 I jxcore-log: 
,09-16 08:30:33.476  5423  5469 I jxcore-log: # teardown
09-16 08:30:33.476  5423  5469 I jxcore-log: 
,09-16 08:30:33.514  5423  5469 I jxcore-log: # setup
09-16 08:30:33.514  5423  5469 I jxcore-log: 
,09-16 08:30:33.562  5423  5469 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-16 08:30:33.562  5423  5469 I jxcore-log: 
,09-16 08:30:33.634  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:33.634  5423  5469 I jxcore-log: 
,09-16 08:30:33.639  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 38286
09-16 08:30:33.639  5423  5469 I jxcore-log: 
,09-16 08:30:33.649  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:33.649  5423  5469 I jxcore-log: 
,09-16 08:30:33.651  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:33.651  5423  5469 I jxcore-log: 
,09-16 08:30:33.654  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:33.654  5423  5469 I jxcore-log: 
,09-16 08:30:33.671  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:33.671  5423  5469 I jxcore-log: 
,09-16 08:30:33.675  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:33.675  5423  5469 I jxcore-log: 
,09-16 08:30:33.692  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:33.692  5423  5469 I jxcore-log: 
,09-16 08:30:33.708  5423  5469 I jxcore-log: ok 17 stream was closed
09-16 08:30:33.708  5423  5469 I jxcore-log: 
,09-16 08:30:33.708  5423  5469 I jxcore-log: ok 18 incoming should survive
09-16 08:30:33.708  5423  5469 I jxcore-log: 
09-16 08:30:33.708  5423  5469 I jxcore-log: ok 19 mux should have no streams
09-16 08:30:33.708  5423  5469 I jxcore-log: 
,09-16 08:30:33.712  5423  5469 I jxcore-log: # teardown
09-16 08:30:33.712  5423  5469 I jxcore-log: 
,09-16 08:30:33.786  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:33.786  5423  5469 I jxcore-log: 
,09-16 08:30:33.796  5423  5469 I jxcore-log: # setup
09-16 08:30:33.796  5423  5469 I jxcore-log: 
,09-16 08:30:33.798  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:33.798  5423  5469 I jxcore-log: 
,09-16 08:30:33.898  5423  5469 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-16 08:30:33.898  5423  5469 I jxcore-log: 
,09-16 08:30:33.969  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:33.969  5423  5469 I jxcore-log: 
,09-16 08:30:33.977  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 47619
09-16 08:30:33.977  5423  5469 I jxcore-log: 
,09-16 08:30:33.986  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:33.986  5423  5469 I jxcore-log: 
,09-16 08:30:33.988  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:33.988  5423  5469 I jxcore-log: 
,09-16 08:30:33.990  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:33.990  5423  5469 I jxcore-log: 
,09-16 08:30:34.004  5423  5469 I jxcore-log: ok 20 we should not have gotten an error
09-16 08:30:34.004  5423  5469 I jxcore-log: 
,09-16 08:30:34.014  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.014  5423  5469 I jxcore-log: 
,09-16 08:30:34.018  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.018  5423  5469 I jxcore-log: 
,09-16 08:30:34.028  5423  5469 I jxcore-log: ok 21 Buffers are identical
09-16 08:30:34.028  5423  5469 I jxcore-log: 
,09-16 08:30:34.031  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.031  5423  5469 I jxcore-log: 
,09-16 08:30:34.033  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.033  5423  5469 I jxcore-log: 
,09-16 08:30:34.036  5423  5469 I jxcore-log: ok 22 native server is nulled out
09-16 08:30:34.036  5423  5469 I jxcore-log: 
,09-16 08:30:34.037  5423  5469 I jxcore-log: ok 23 native server should be closed
09-16 08:30:34.037  5423  5469 I jxcore-log: 
,09-16 08:30:34.037  5423  5469 I jxcore-log: ok 24 incoming has been removed
09-16 08:30:34.037  5423  5469 I jxcore-log: 
09-16 08:30:34.037  5423  5469 I jxcore-log: ok 25 Incoming should be done
09-16 08:30:34.037  5423  5469 I jxcore-log: 
,09-16 08:30:34.037  5423  5469 I jxcore-log: ok 26 The mux object should be closed
09-16 08:30:34.037  5423  5469 I jxcore-log: 
,09-16 08:30:34.038  5423  5469 I jxcore-log: ok 27 The mux stream should be closed
09-16 08:30:34.038  5423  5469 I jxcore-log: 
09-16 08:30:34.038  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.038  5423  5469 I jxcore-log: 
,09-16 08:30:34.052  5423  5469 I jxcore-log: # teardown
09-16 08:30:34.052  5423  5469 I jxcore-log: 
,09-16 08:30:34.086  5423  5469 I jxcore-log: # setup
09-16 08:30:34.086  5423  5469 I jxcore-log: 
,09-16 08:30:34.164  5423  5469 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-16 08:30:34.164  5423  5469 I jxcore-log: 
,09-16 08:30:34.237  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:34.237  5423  5469 I jxcore-log: 
,09-16 08:30:34.241  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 48958
09-16 08:30:34.241  5423  5469 I jxcore-log: 
,09-16 08:30:34.285  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.285  5423  5469 I jxcore-log: 
,09-16 08:30:34.286  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.286  5423  5469 I jxcore-log: 
,09-16 08:30:34.288  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.288  5423  5469 I jxcore-log: 
,09-16 08:30:34.292  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.292  5423  5469 I jxcore-log: 
09-16 08:30:34.293  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.293  5423  5469 I jxcore-log: 
,09-16 08:30:34.295  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.295  5423  5469 I jxcore-log: 
,09-16 08:30:34.299  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.299  5423  5469 I jxcore-log: 
,09-16 08:30:34.300  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.300  5423  5469 I jxcore-log: 
09-16 08:30:34.301  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.301  5423  5469 I jxcore-log: 
,09-16 08:30:34.306  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.306  5423  5469 I jxcore-log: 
,09-16 08:30:34.307  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.307  5423  5469 I jxcore-log: 
09-16 08:30:34.308  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.308  5423  5469 I jxcore-log: 
,09-16 08:30:34.312  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.312  5423  5469 I jxcore-log: 
,09-16 08:30:34.313  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.313  5423  5469 I jxcore-log: 
,09-16 08:30:34.314  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.314  5423  5469 I jxcore-log: 
,09-16 08:30:34.317  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.317  5423  5469 I jxcore-log: 
,09-16 08:30:34.318  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.318  5423  5469 I jxcore-log: 
09-16 08:30:34.319  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.319  5423  5469 I jxcore-log: 
,09-16 08:30:34.322  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.322  5423  5469 I jxcore-log: 
,09-16 08:30:34.323  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.323  5423  5469 I jxcore-log: 
,09-16 08:30:34.330  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.330  5423  5469 I jxcore-log: 
,09-16 08:30:34.337  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.337  5423  5469 I jxcore-log: 
,09-16 08:30:34.338  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.338  5423  5469 I jxcore-log: 
,09-16 08:30:34.340  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.340  5423  5469 I jxcore-log: 
,09-16 08:30:34.342  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.342  5423  5469 I jxcore-log: 
,09-16 08:30:34.342  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.342  5423  5469 I jxcore-log: 
,09-16 08:30:34.343  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.343  5423  5469 I jxcore-log: 
,09-16 08:30:34.345  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:34.345  5423  5469 I jxcore-log: 
,09-16 08:30:34.346  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:34.346  5423  5469 I jxcore-log: 
,09-16 08:30:34.347  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:34.347  5423  5469 I jxcore-log: 
,09-16 08:30:34.428  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.428  5423  5469 I jxcore-log: 
,09-16 08:30:34.429  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.429  5423  5469 I jxcore-log: 
,09-16 08:30:34.431  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.431  5423  5469 I jxcore-log: 
,09-16 08:30:34.432  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.432  5423  5469 I jxcore-log: 
,09-16 08:30:34.433  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.433  5423  5469 I jxcore-log: 
,09-16 08:30:34.434  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.434  5423  5469 I jxcore-log: 
,09-16 08:30:34.435  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.435  5423  5469 I jxcore-log: 
,09-16 08:30:34.436  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.436  5423  5469 I jxcore-log: 
,09-16 08:30:34.437  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.437  5423  5469 I jxcore-log: 
,09-16 08:30:34.439  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.439  5423  5469 I jxcore-log: 
,09-16 08:30:34.439  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.439  5423  5469 I jxcore-log: 
,09-16 08:30:34.440  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.440  5423  5469 I jxcore-log: 
,09-16 08:30:34.441  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.441  5423  5469 I jxcore-log: 
,09-16 08:30:34.442  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.442  5423  5469 I jxcore-log: 
,09-16 08:30:34.443  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.443  5423  5469 I jxcore-log: 
,09-16 08:30:34.444  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.444  5423  5469 I jxcore-log: 
,09-16 08:30:34.445  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.445  5423  5469 I jxcore-log: 
,09-16 08:30:34.447  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.447  5423  5469 I jxcore-log: 
,09-16 08:30:34.447  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.447  5423  5469 I jxcore-log: 
,09-16 08:30:34.448  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.448  5423  5469 I jxcore-log: 
09-16 08:30:34.449  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.449  5423  5469 I jxcore-log: 
,09-16 08:30:34.450  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.450  5423  5469 I jxcore-log: 
,09-16 08:30:34.450  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.450  5423  5469 I jxcore-log: 
,09-16 08:30:34.454  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.454  5423  5469 I jxcore-log: 
,09-16 08:30:34.455  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.455  5423  5469 I jxcore-log: 
,09-16 08:30:34.457  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.457  5423  5469 I jxcore-log: 
,09-16 08:30:34.457  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.457  5423  5469 I jxcore-log: 
,09-16 08:30:34.458  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.458  5423  5469 I jxcore-log: 
,09-16 08:30:34.459  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.459  5423  5469 I jxcore-log: 
,09-16 08:30:34.460  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.460  5423  5469 I jxcore-log: 
,09-16 08:30:34.461  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.461  5423  5469 I jxcore-log: 
,09-16 08:30:34.461  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.461  5423  5469 I jxcore-log: 
09-16 08:30:34.463  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.463  5423  5469 I jxcore-log: 
,09-16 08:30:34.464  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.464  5423  5469 I jxcore-log: 
,09-16 08:30:34.464  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.464  5423  5469 I jxcore-log: 
,09-16 08:30:34.465  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.465  5423  5469 I jxcore-log: 
09-16 08:30:34.466  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.466  5423  5469 I jxcore-log: 
,09-16 08:30:34.467  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.467  5423  5469 I jxcore-log: 
,09-16 08:30:34.472  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.472  5423  5469 I jxcore-log: 
,09-16 08:30:34.473  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.473  5423  5469 I jxcore-log: 
,09-16 08:30:34.475  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.475  5423  5469 I jxcore-log: 
,09-16 08:30:34.476  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.476  5423  5469 I jxcore-log: 
,09-16 08:30:34.477  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.477  5423  5469 I jxcore-log: 
,09-16 08:30:34.478  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.478  5423  5469 I jxcore-log: 
,09-16 08:30:34.478  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.478  5423  5469 I jxcore-log: 
09-16 08:30:34.479  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.479  5423  5469 I jxcore-log: 
,09-16 08:30:34.480  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.480  5423  5469 I jxcore-log: 
,09-16 08:30:34.480  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.480  5423  5469 I jxcore-log: 
,09-16 08:30:34.481  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.481  5423  5469 I jxcore-log: 
,09-16 08:30:34.482  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.482  5423  5469 I jxcore-log: 
09-16 08:30:34.483  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.483  5423  5469 I jxcore-log: 
,09-16 08:30:34.483  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.483  5423  5469 I jxcore-log: 
,09-16 08:30:34.484  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.484  5423  5469 I jxcore-log: 
,09-16 08:30:34.485  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.485  5423  5469 I jxcore-log: 
09-16 08:30:34.485  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.485  5423  5469 I jxcore-log: 
,09-16 08:30:34.486  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.486  5423  5469 I jxcore-log: 
09-16 08:30:34.487  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.487  5423  5469 I jxcore-log: 
,09-16 08:30:34.487  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.487  5423  5469 I jxcore-log: 
,09-16 08:30:34.488  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.488  5423  5469 I jxcore-log: 
,09-16 08:30:34.489  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.489  5423  5469 I jxcore-log: 
09-16 08:30:34.489  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.489  5423  5469 I jxcore-log: 
,09-16 08:30:34.490  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.490  5423  5469 I jxcore-log: 
,09-16 08:30:34.491  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.491  5423  5469 I jxcore-log: 
,09-16 08:30:34.492  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.492  5423  5469 I jxcore-log: 
,09-16 08:30:34.493  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.493  5423  5469 I jxcore-log: 
,09-16 08:30:34.494  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.494  5423  5469 I jxcore-log: 
,09-16 08:30:34.495  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.495  5423  5469 I jxcore-log: 
09-16 08:30:34.496  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.496  5423  5469 I jxcore-log: 
,09-16 08:30:34.496  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.496  5423  5469 I jxcore-log: 
09-16 08:30:34.497  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.497  5423  5469 I jxcore-log: 
,09-16 08:30:34.497  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.497  5423  5469 I jxcore-log: 
,09-16 08:30:34.498  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.498  5423  5469 I jxcore-log: 
,09-16 08:30:34.499  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.499  5423  5469 I jxcore-log: 
09-16 08:30:34.500  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.500  5423  5469 I jxcore-log: 
,09-16 08:30:34.500  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.500  5423  5469 I jxcore-log: 
,09-16 08:30:34.501  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.501  5423  5469 I jxcore-log: 
09-16 08:30:34.502  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.502  5423  5469 I jxcore-log: 
,09-16 08:30:34.502  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.502  5423  5469 I jxcore-log: 
09-16 08:30:34.503  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:34.503  5423  5469 I jxcore-log: 
,09-16 08:30:34.504  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:34.504  5423  5469 I jxcore-log: 
,09-16 08:30:34.549  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.549  5423  5469 I jxcore-log: 
,09-16 08:30:34.550  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.550  5423  5469 I jxcore-log: 
,09-16 08:30:34.551  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.551  5423  5469 I jxcore-log: 
,09-16 08:30:34.552  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.552  5423  5469 I jxcore-log: 
09-16 08:30:34.552  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.552  5423  5469 I jxcore-log: 
,09-16 08:30:34.553  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.553  5423  5469 I jxcore-log: 
09-16 08:30:34.554  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.554  5423  5469 I jxcore-log: 
,09-16 08:30:34.554  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.554  5423  5469 I jxcore-log: 
,09-16 08:30:34.555  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.555  5423  5469 I jxcore-log: 
,09-16 08:30:34.555  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.555  5423  5469 I jxcore-log: 
09-16 08:30:34.556  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.556  5423  5469 I jxcore-log: 
09-16 08:30:34.558  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.558  5423  5469 I jxcore-log: 
,09-16 08:30:34.558  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.558  5423  5469 I jxcore-log: 
,09-16 08:30:34.559  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.559  5423  5469 I jxcore-log: 
09-16 08:30:34.560  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.560  5423  5469 I jxcore-log: 
,09-16 08:30:34.563  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.563  5423  5469 I jxcore-log: 
,09-16 08:30:34.563  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.563  5423  5469 I jxcore-log: 
09-16 08:30:34.564  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.564  5423  5469 I jxcore-log: 
,09-16 08:30:34.565  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.565  5423  5469 I jxcore-log: 
09-16 08:30:34.565  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.565  5423  5469 I jxcore-log: 
,09-16 08:30:34.566  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.566  5423  5469 I jxcore-log: 
09-16 08:30:34.566  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.566  5423  5469 I jxcore-log: 
,09-16 08:30:34.567  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.567  5423  5469 I jxcore-log: 
09-16 08:30:34.567  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.567  5423  5469 I jxcore-log: 
09-16 08:30:34.568  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.568  5423  5469 I jxcore-log: 
,09-16 08:30:34.569  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.569  5423  5469 I jxcore-log: 
09-16 08:30:34.569  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.569  5423  5469 I jxcore-log: 
,09-16 08:30:34.570  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.570  5423  5469 I jxcore-log: 
09-16 08:30:34.570  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.570  5423  5469 I jxcore-log: 
,09-16 08:30:34.571  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.571  5423  5469 I jxcore-log: 
09-16 08:30:34.571  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.571  5423  5469 I jxcore-log: 
,09-16 08:30:34.572  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.572  5423  5469 I jxcore-log: 
,09-16 08:30:34.572  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.572  5423  5469 I jxcore-log: 
09-16 08:30:34.573  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.573  5423  5469 I jxcore-log: 
09-16 08:30:34.573  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.573  5423  5469 I jxcore-log: 
09-16 08:30:34.574  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.574  5423  5469 I jxcore-log: 
,09-16 08:30:34.574  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.574  5423  5469 I jxcore-log: 
09-16 08:30:34.575  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.575  5423  5469 I jxcore-log: 
,09-16 08:30:34.578  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.578  5423  5469 I jxcore-log: 
,09-16 08:30:34.578  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.578  5423  5469 I jxcore-log: 
09-16 08:30:34.579  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.579  5423  5469 I jxcore-log: 
,09-16 08:30:34.579  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.579  5423  5469 I jxcore-log: 
09-16 08:30:34.580  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.580  5423  5469 I jxcore-log: 
,09-16 08:30:34.580  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.580  5423  5469 I jxcore-log: 
09-16 08:30:34.581  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.581  5423  5469 I jxcore-log: 
,09-16 08:30:34.581  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.581  5423  5469 I jxcore-log: 
09-16 08:30:34.582  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.582  5423  5469 I jxcore-log: 
,09-16 08:30:34.582  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.582  5423  5469 I jxcore-log: 
09-16 08:30:34.583  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:34.583  5423  5469 I jxcore-log: 
09-16 08:30:34.583  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:34.583  5423  5469 I jxcore-log: 
,09-16 08:30:34.585  5423  5469 I jxcore-log: ok 28 native server is nulled out
09-16 08:30:34.585  5423  5469 I jxcore-log: 
,09-16 08:30:34.586  5423  5469 I jxcore-log: ok 29 native server should be closed
09-16 08:30:34.586  5423  5469 I jxcore-log: 
09-16 08:30:34.586  5423  5469 I jxcore-log: ok 30 incoming has been removed
09-16 08:30:34.586  5423  5469 I jxcore-log: 
09-16 08:30:34.586  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.586  5423  5469 I jxcore-log: 
,09-16 08:30:34.587  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.587  5423  5469 I jxcore-log: 
09-16 08:30:34.587  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.587  5423  5469 I jxcore-log: 
09-16 08:30:34.587  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.587  5423  5469 I jxcore-log: 
09-16 08:30:34.588  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.588  5423  5469 I jxcore-log: 
09-16 08:30:34.588  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.588  5423  5469 I jxcore-log: 
09-16 08:30:34.588  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.588  5423  5469 I jxcore-log: 
,09-16 08:30:34.588  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.588  5423  5469 I jxcore-log: 
09-16 08:30:34.588  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.588  5423  5469 I jxcore-log: 
09-16 08:30:34.589  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:34.589  5423  5469 I jxcore-log: 
,09-16 08:30:34.668  5423  5469 I jxcore-log: # teardown
09-16 08:30:34.668  5423  5469 I jxcore-log: 
,09-16 08:30:34.744  5423  5469 I jxcore-log: # setup
09-16 08:30:34.744  5423  5469 I jxcore-log: 
,09-16 08:30:36.454  5423  5469 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-16 08:30:36.454  5423  5469 I jxcore-log: 
,09-16 08:30:37.478  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:37.478  5423  5469 I jxcore-log: 
,09-16 08:30:37.485  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 46349
09-16 08:30:37.485  5423  5469 I jxcore-log: 
,09-16 08:30:37.494  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:37.494  5423  5469 I jxcore-log: 
,09-16 08:30:37.496  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:37.496  5423  5469 I jxcore-log: 
,09-16 08:30:37.498  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:37.498  5423  5469 I jxcore-log: 
,09-16 08:30:37.509  5423  5469 I jxcore-log: ok 31 we should not have gotten an error
09-16 08:30:37.509  5423  5469 I jxcore-log: 
,09-16 08:30:37.517  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:37.517  5423  5469 I jxcore-log: 
,09-16 08:30:37.520  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:37.520  5423  5469 I jxcore-log: 
,09-16 08:30:37.532  5423  5469 I jxcore-log: ok 32 Buffers are identical
09-16 08:30:37.532  5423  5469 I jxcore-log: 
,09-16 08:30:37.533  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:37.533  5423  5469 I jxcore-log: 
,09-16 08:30:37.535  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:37.535  5423  5469 I jxcore-log: 
,09-16 08:30:37.550  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:37.550  5423  5469 I jxcore-log: 
,09-16 08:30:37.551  5423  5469 I jxcore-log: ok 33 server should be fine
09-16 08:30:37.551  5423  5469 I jxcore-log: 
09-16 08:30:37.552  5423  5469 I jxcore-log: ok 34 server should be open
09-16 08:30:37.552  5423  5469 I jxcore-log: 
09-16 08:30:37.552  5423  5469 I jxcore-log: ok 35 incoming has been removed
09-16 08:30:37.552  5423  5469 I jxcore-log: 
09-16 08:30:37.552  5423  5469 I jxcore-log: ok 36 The mux object should be closed
09-16 08:30:37.552  5423  5469 I jxcore-log: 
09-16 08:30:37.552  5423  5469 I jxcore-log: ok 37 The mux stream should be closed
09-16 08:30:37.552  5423  5469 I jxcore-log: 
,09-16 08:30:37.556  5423  5469 I jxcore-log: # teardown
09-16 08:30:37.556  5423  5469 I jxcore-log: 
,09-16 08:30:37.636  5423  5469 I jxcore-log: # setup
09-16 08:30:37.636  5423  5469 I jxcore-log: 
,09-16 08:30:37.695  5423  5469 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-16 08:30:37.695  5423  5469 I jxcore-log: 
,09-16 08:30:37.767  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:37.767  5423  5469 I jxcore-log: 
,09-16 08:30:37.771  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 44626
09-16 08:30:37.771  5423  5469 I jxcore-log: 
,09-16 08:30:37.779  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:30:37.779  5423  5469 I jxcore-log: 
,09-16 08:30:37.780  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:30:37.780  5423  5469 I jxcore-log: 
,09-16 08:30:37.782  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:30:37.782  5423  5469 I jxcore-log: 
,09-16 08:30:37.788  5423  5469 I jxcore-log: ok 38 we should not have gotten an error
09-16 08:30:37.788  5423  5469 I jxcore-log: 
,09-16 08:30:37.794  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:30:37.794  5423  5469 I jxcore-log: 
,09-16 08:30:37.796  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:30:37.796  5423  5469 I jxcore-log: 
,09-16 08:30:37.803  5423  5469 I jxcore-log: ok 39 Buffers are identical
09-16 08:30:37.803  5423  5469 I jxcore-log: 
,09-16 08:30:37.808  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-16 08:30:37.808  5423  5469 I jxcore-log: 
,09-16 08:30:37.811  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:30:37.811  5423  5469 I jxcore-log: 
,09-16 08:30:37.812  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:30:37.812  5423  5469 I jxcore-log: 
,09-16 08:30:37.816  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:30:37.816  5423  5469 I jxcore-log: 
,09-16 08:30:37.816  5423  5469 I jxcore-log: ok 40 server should be fine
09-16 08:30:37.816  5423  5469 I jxcore-log: 
09-16 08:30:37.817  5423  5469 I jxcore-log: ok 41 server should be open
09-16 08:30:37.817  5423  5469 I jxcore-log: 
09-16 08:30:37.817  5423  5469 I jxcore-log: ok 42 incoming has been removed
09-16 08:30:37.817  5423  5469 I jxcore-log: 
09-16 08:30:37.817  5423  5469 I jxcore-log: ok 43 The mux object should be closed
09-16 08:30:37.817  5423  5469 I jxcore-log: 
09-16 08:30:37.817  5423  5469 I jxcore-log: ok 44 The mux stream should be closed
09-16 08:30:37.817  5423  5469 I jxcore-log: 
,09-16 08:30:37.822  5423  5469 I jxcore-log: # teardown
09-16 08:30:37.822  5423  5469 I jxcore-log: 
,09-16 08:30:37.884  5423  5469 I jxcore-log: # setup
09-16 08:30:37.884  5423  5469 I jxcore-log: 
,09-16 08:30:37.931  5423  5469 I jxcore-log: # 12. closeAll can close even when connections open
09-16 08:30:37.931  5423  5469 I jxcore-log: 
,09-16 08:30:38.125  5423  5469 I jxcore-log: ok 45 not possible to connect to the server anymore
09-16 08:30:38.125  5423  5469 I jxcore-log: 
,09-16 08:30:38.131  5423  5469 I jxcore-log: # teardown
09-16 08:30:38.131  5423  5469 I jxcore-log: 
,09-16 08:30:38.173  5423  5469 I jxcore-log: # setup
09-16 08:30:38.173  5423  5469 I jxcore-log: 
,09-16 08:30:38.229  5423  5469 I jxcore-log: # 13. closeAll with promise
09-16 08:30:38.229  5423  5469 I jxcore-log: 
,09-16 08:30:38.409  5423  5469 I jxcore-log: ok 46 not possible to connect to the server anymore
09-16 08:30:38.409  5423  5469 I jxcore-log: 
,09-16 08:30:38.415  5423  5469 I jxcore-log: # teardown
09-16 08:30:38.415  5423  5469 I jxcore-log: 
,09-16 08:30:38.472  5423  5469 I jxcore-log: # setup
09-16 08:30:38.472  5423  5469 I jxcore-log: 
,09-16 08:30:38.517  5423  5469 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
09-16 08:30:38.517  5423  5469 I jxcore-log: 
,09-16 08:30:38.707  5423  5469 I jxcore-log: ok 47 Got the right error
09-16 08:30:38.707  5423  5469 I jxcore-log: 
,09-16 08:30:38.715  5423  5469 I jxcore-log: # teardown
09-16 08:30:38.715  5423  5469 I jxcore-log: 
,09-16 08:30:38.771  5423  5469 I jxcore-log: # setup
09-16 08:30:38.771  5423  5469 I jxcore-log: 
,09-16 08:30:38.849  5423  5469 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-16 08:30:38.849  5423  5469 I jxcore-log: 
,09-16 08:30:39.040  5423  5469 I jxcore-log: # teardown
09-16 08:30:39.040  5423  5469 I jxcore-log: 
,09-16 08:30:39.083  5423  5469 I jxcore-log: # setup
09-16 08:30:39.083  5423  5469 I jxcore-log: 
,09-16 08:30:39.160  5423  5469 I jxcore-log: # 16. onPeerLost calls jxcore
09-16 08:30:39.160  5423  5469 I jxcore-log: 
,09-16 08:30:39.256  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 08:30:39.256  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e31e51f added. We now have 3 listener(s)
,09-16 08:30:39.261  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6",
,09-16 08:30:39.261  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 08:30:39.261  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 08:30:39.262  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:30:39.262  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@408306c added. We now have 4 listener(s)
,09-16 08:30:39.262  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 08:30:39.264  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 08:30:39.271  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:39.280  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:30:39.280  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:39.280  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:39.280  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:39.280  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:39.280  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:39.280  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:39.280  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:39.283  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:39.283  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:30:39.284  5423  5469 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-16 08:30:39.284  5423  5469 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-16 08:30:39.289  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:39.294  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:39.967   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:30:40.490   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:41.287  5423  5469 I jxcore-log: onPeerLost
09-16 08:30:41.287  5423  5469 I jxcore-log: 
,09-16 08:30:41.290  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:41.290  5423  5469 I jxcore-log: 
,09-16 08:30:41.299  5423  5469 I jxcore-log: # teardown
09-16 08:30:41.299  5423  5469 I jxcore-log: 
,09-16 08:30:41.317  5423  5469 I jxcore-log: ok 48 check if callback was fired by onPeerLost
09-16 08:30:41.317  5423  5469 I jxcore-log: 
,09-16 08:30:41.318  5423  5469 I jxcore-log: ok 49 check if peerAvailable is false
09-16 08:30:41.318  5423  5469 I jxcore-log: 
,09-16 08:30:41.399  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 08:30:41.399  5423  5469 I jxcore-log: 
,09-16 08:30:41.402  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 08:30:41.402  5423  5469 I jxcore-log: 
,09-16 08:30:41.413  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:30:41.413  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:41.413  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:41.413  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:41.413  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:41.413  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:41.413  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:41.413  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:41.419  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:30:41.422  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 08:30:41.422  5423  5469 I jxcore-log: 
,09-16 08:30:41.425  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 08:30:41.425  5423  5469 I jxcore-log: 
,09-16 08:30:41.429  5423  5469 I jxcore-log: # setup
09-16 08:30:41.429  5423  5469 I jxcore-log: 
,09-16 08:30:41.432  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:41.432  5423  5469 I jxcore-log: 
,09-16 08:30:41.491   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:41.501  5423  5469 I jxcore-log: # 17. onPeerDiscovered calls jxcore
09-16 08:30:41.501  5423  5469 I jxcore-log: 
,09-16 08:30:41.562  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 08:30:41.563  5423  5469 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b0eaca added. We now have 4 listener(s)
09-16 08:30:41.566  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:30:41.567  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 08:30:41.567  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 08:30:41.567  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 08:30:41.567  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919b43b added. We now have 5 listener(s)
09-16 08:30:41.567  5423  5469 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 08:30:41.569  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 08:30:41.581  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:41.589  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:30:41.589  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:41.589  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:41.589  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:41.589  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:41.589  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:41.589  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:41.589  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:41.592  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:30:41.593  5423  5469 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 08:30:41.593  5423  5469 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-16 08:30:41.599  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:41.603  5423  5423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 08:30:42.492   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:43.493   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:43.597  5423  5469 I jxcore-log: onPeerDiscovered
09-16 08:30:43.597  5423  5469 I jxcore-log: 
,09-16 08:30:43.601  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:43.601  5423  5469 I jxcore-log: 
,09-16 08:30:43.611  5423  5469 I jxcore-log: # teardown
09-16 08:30:43.611  5423  5469 I jxcore-log: 
,09-16 08:30:43.618  5423  5469 I jxcore-log: ok 50 check if callback was fired by onPeerDiscovered
09-16 08:30:43.618  5423  5469 I jxcore-log: 
,09-16 08:30:43.619  5423  5469 I jxcore-log: ok 51 check if peerAvailable is true
09-16 08:30:43.619  5423  5469 I jxcore-log: 
,09-16 08:30:43.707  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 08:30:43.707  5423  5469 I jxcore-log: 
,09-16 08:30:43.711  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 08:30:43.711  5423  5469 I jxcore-log: 
,09-16 08:30:43.723  5423  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 08:30:43.723  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 08:30:43.723  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 08:30:43.723  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 08:30:43.723  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 08:30:43.723  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 08:30:43.723  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 08:30:43.723  5423  5469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 08:30:43.728  5423  5469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 08:30:43.729  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 08:30:43.729  5423  5469 I jxcore-log: 
09-16 08:30:43.731  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 08:30:43.731  5423  5469 I jxcore-log: 
,09-16 08:30:43.734  5423  5469 I jxcore-log: # setup
09-16 08:30:43.734  5423  5469 I jxcore-log: 
,09-16 08:30:43.736  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 08:30:43.736  5423  5469 I jxcore-log: 
,09-16 08:30:43.803  5423  5469 I jxcore-log: # 18. test defaultDirectory
09-16 08:30:43.803  5423  5469 I jxcore-log: 
,09-16 08:30:43.880  5423  5469 I jxcore-log: ok 52 should be equal
09-16 08:30:43.880  5423  5469 I jxcore-log: 
,09-16 08:30:43.885  5423  5469 I jxcore-log: ok 53 should be equal
09-16 08:30:43.885  5423  5469 I jxcore-log: 
,09-16 08:30:43.902  5423  5469 I jxcore-log: ok 54 should be equal
09-16 08:30:43.902  5423  5469 I jxcore-log: 
,09-16 08:30:43.905  5423  5469 I jxcore-log: # teardown
09-16 08:30:43.905  5423  5469 I jxcore-log: 
,09-16 08:30:43.983  5423  5469 I jxcore-log: # setup
09-16 08:30:43.983  5423  5469 I jxcore-log: 
,09-16 08:30:44.042  5423  5469 I jxcore-log: # 19. test defaultAdapter
09-16 08:30:44.042  5423  5469 I jxcore-log: 
,09-16 08:30:44.111  5423  5469 I jxcore-log: ok 55 should be equal
09-16 08:30:44.111  5423  5469 I jxcore-log: 
,09-16 08:30:44.112  5423  5469 I jxcore-log: ok 56 should be equal
09-16 08:30:44.112  5423  5469 I jxcore-log: 
,09-16 08:30:44.114  5423  5469 I jxcore-log: ok 57 should be equal
09-16 08:30:44.114  5423  5469 I jxcore-log: 
09-16 08:30:44.115  5423  5469 I jxcore-log: ok 58 should be equal
09-16 08:30:44.115  5423  5469 I jxcore-log: 
,09-16 08:30:44.120  5423  5469 I jxcore-log: ok 59 should be equal
09-16 08:30:44.120  5423  5469 I jxcore-log: 
,09-16 08:30:44.120  5423  5469 I jxcore-log: ok 60 should be equal
09-16 08:30:44.120  5423  5469 I jxcore-log: 
,09-16 08:30:44.261  5423  5469 I jxcore-log: ok 61 should be equal
09-16 08:30:44.261  5423  5469 I jxcore-log: 
,09-16 08:30:44.261  5423  5469 I jxcore-log: ok 62 should be equal
09-16 08:30:44.261  5423  5469 I jxcore-log: 
09-16 08:30:44.263  5423  5469 I jxcore-log: # teardown
09-16 08:30:44.263  5423  5469 I jxcore-log: 
,09-16 08:30:44.407  5423  5469 I jxcore-log: # setup
09-16 08:30:44.407  5423  5469 I jxcore-log: 
,09-16 08:30:44.494   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:44.522  5423  5469 I jxcore-log: # 20. enqueue and run in order
09-16 08:30:44.522  5423  5469 I jxcore-log: 
,09-16 08:30:44.672  5423  5469 I jxcore-log: ok 63 firstPromise setTimeout
09-16 08:30:44.672  5423  5469 I jxcore-log: 
,09-16 08:30:44.674  5423  5469 I jxcore-log: ok 64 firstPromise result
09-16 08:30:44.674  5423  5469 I jxcore-log: 
09-16 08:30:44.675  5423  5469 I jxcore-log: ok 65 firstPromise testValue
09-16 08:30:44.675  5423  5469 I jxcore-log: 
,09-16 08:30:44.778  5423  5469 I jxcore-log: ok 66 secondPromise setTimeout
09-16 08:30:44.778  5423  5469 I jxcore-log: 
,09-16 08:30:44.781  5423  5469 I jxcore-log: ok 67 secondPromise result
09-16 08:30:44.781  5423  5469 I jxcore-log: 
,09-16 08:30:44.782  5423  5469 I jxcore-log: ok 68 secondPromise testValue
09-16 08:30:44.782  5423  5469 I jxcore-log: 
,09-16 08:30:44.785  5423  5469 I jxcore-log: ok 69 thirdPromise in promise
09-16 08:30:44.785  5423  5469 I jxcore-log: 
,09-16 08:30:44.788  5423  5469 I jxcore-log: ok 70 thirdPromise result
09-16 08:30:44.788  5423  5469 I jxcore-log: 
,09-16 08:30:44.791  5423  5469 I jxcore-log: ok 71 thirdPromise testValue
09-16 08:30:44.791  5423  5469 I jxcore-log: 
,09-16 08:30:44.798  5423  5469 I jxcore-log: # teardown
09-16 08:30:44.798  5423  5469 I jxcore-log: 
,09-16 08:30:44.888  5423  5469 I jxcore-log: # setup
09-16 08:30:44.888  5423  5469 I jxcore-log: 
,09-16 08:30:44.970  5423  5469 I jxcore-log: # 21. enqueueAtTop and run backwards
09-16 08:30:44.970  5423  5469 I jxcore-log: 
,09-16 08:30:45.029  5423  5469 I jxcore-log: ok 72 thirdPromise - first to run
09-16 08:30:45.029  5423  5469 I jxcore-log: 
,09-16 08:30:45.031  5423  5469 I jxcore-log: ok 73 thirdPromise - in resolve
09-16 08:30:45.031  5423  5469 I jxcore-log: 
,09-16 08:30:45.033  5423  5469 I jxcore-log: ok 74 secondPromise - second to run
09-16 08:30:45.033  5423  5469 I jxcore-log: 
,09-16 08:30:45.036  5423  5469 I jxcore-log: ok 75 secondPromise - in catch
09-16 08:30:45.036  5423  5469 I jxcore-log: 
,09-16 08:30:45.039  5423  5469 I jxcore-log: ok 76 firstPromise - third to run
09-16 08:30:45.039  5423  5469 I jxcore-log: 
,09-16 08:30:45.041  5423  5469 I jxcore-log: ok 77 firstPromise - in then
09-16 08:30:45.041  5423  5469 I jxcore-log: 
,09-16 08:30:45.043  5423  5469 I jxcore-log: ok 78 testing promises
09-16 08:30:45.043  5423  5469 I jxcore-log: 
,09-16 08:30:45.048  5423  5469 I jxcore-log: # teardown
09-16 08:30:45.048  5423  5469 I jxcore-log: 
,09-16 08:30:45.095  5423  5469 I jxcore-log: # setup
09-16 08:30:45.095  5423  5469 I jxcore-log: 
,09-16 08:30:45.157  5423  5469 I jxcore-log: # 22. mix enqueue and enqueueAtTop
09-16 08:30:45.157  5423  5469 I jxcore-log: 
,09-16 08:30:45.231  5423  5469 I jxcore-log: ok 79 fourth
09-16 08:30:45.231  5423  5469 I jxcore-log: 
,09-16 08:30:45.233  5423  5469 I jxcore-log: ok 80 fourth
09-16 08:30:45.233  5423  5469 I jxcore-log: 
,09-16 08:30:45.234  5423  5469 I jxcore-log: ok 81 second
09-16 08:30:45.234  5423  5469 I jxcore-log: 
,09-16 08:30:45.236  5423  5469 I jxcore-log: ok 82 secondPromise - in then
09-16 08:30:45.236  5423  5469 I jxcore-log: 
,09-16 08:30:45.339  5423  5469 I jxcore-log: ok 83 first
09-16 08:30:45.339  5423  5469 I jxcore-log: 
,09-16 08:30:45.342  5423  5469 I jxcore-log: ok 84 firstPromise - in catch
09-16 08:30:45.342  5423  5469 I jxcore-log: 
,09-16 08:30:45.343  5423  5469 I jxcore-log: ok 85 third
09-16 08:30:45.343  5423  5469 I jxcore-log: 
,09-16 08:30:45.346  5423  5469 I jxcore-log: ok 86 thirdPromise - in then
09-16 08:30:45.346  5423  5469 I jxcore-log: 
09-16 08:30:45.347  5423  5469 I jxcore-log: ok 87 testingPromises
09-16 08:30:45.347  5423  5469 I jxcore-log: 
,09-16 08:30:45.354  5423  5469 I jxcore-log: # teardown
09-16 08:30:45.354  5423  5469 I jxcore-log: 
,09-16 08:30:45.411  5423  5469 I jxcore-log: # setup
09-16 08:30:45.411  5423  5469 I jxcore-log: 
,09-16 08:30:45.485  5423  5469 I jxcore-log: # 23. queues handled independently
09-16 08:30:45.485  5423  5469 I jxcore-log: 
,09-16 08:30:45.495   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:30:45.708  5423  5469 I jxcore-log: ok 88 all short operations completed before the long resolves
09-16 08:30:45.708  5423  5469 I jxcore-log: 
,09-16 08:30:45.717  5423  5469 I jxcore-log: # teardown
09-16 08:30:45.717  5423  5469 I jxcore-log: 
,09-16 08:30:45.759  5423  5469 I jxcore-log: # setup
09-16 08:30:45.759  5423  5469 I jxcore-log: 
,09-16 08:30:45.823  5423  5469 I jxcore-log: # 24. basic
09-16 08:30:45.823  5423  5469 I jxcore-log: 
,09-16 08:30:45.879  5423  5469 I jxcore-log: ok 89 sane
09-16 08:30:45.879  5423  5469 I jxcore-log: 
,09-16 08:30:45.882  5423  5469 I jxcore-log: # teardown
09-16 08:30:45.882  5423  5469 I jxcore-log: 
,09-16 08:30:45.938  5423  5469 I jxcore-log: # setup
09-16 08:30:45.938  5423  5469 I jxcore-log: 
,09-16 08:30:46.003  5423  5469 I jxcore-log: # 25. another
09-16 08:30:46.003  5423  5469 I jxcore-log: 
,09-16 08:30:46.058  5423  5469 I jxcore-log: ok 90 sane
09-16 08:30:46.058  5423  5469 I jxcore-log: 
,09-16 08:30:46.061  5423  5469 I jxcore-log: # teardown
09-16 08:30:46.061  5423  5469 I jxcore-log: 
,09-16 08:30:46.123  5423  5469 I jxcore-log: # setup
09-16 08:30:46.123  5423  5469 I jxcore-log: 
,09-16 08:30:46.174  5423  5469 I jxcore-log: # 26. can pass data in setup
09-16 08:30:46.174  5423  5469 I jxcore-log: 
,09-16 08:30:46.265  5423  5469 I jxcore-log: [{"uuid":"42fe85da-e8fa-4862-923f-959cc949929b","data":"custom data"},{"uuid":"4a5b688e-fb07-4847-9262-6eb2738ca5a8","data":"custom data"},{"uuid":"738a7884-2e81-4c15-9a5d-16132eea729e","data":"custom data"}]
09-16 08:30:46.265  5423  5469 I jxcore-log: 
,09-16 08:30:46.267  5423  5469 I jxcore-log: ok 91 test participant has uuid
09-16 08:30:46.267  5423  5469 I jxcore-log: 
,09-16 08:30:46.269  5423  5469 I jxcore-log: ok 92 participant data matches
09-16 08:30:46.269  5423  5469 I jxcore-log: 
,09-16 08:30:46.270  5423  5469 I jxcore-log: ok 93 test participant has uuid
09-16 08:30:46.270  5423  5469 I jxcore-log: 
,09-16 08:30:46.271  5423  5469 I jxcore-log: ok 94 participant data matches
09-16 08:30:46.271  5423  5469 I jxcore-log: 
09-16 08:30:46.272  5423  5469 I jxcore-log: ok 95 test participant has uuid
09-16 08:30:46.272  5423  5469 I jxcore-log: 
09-16 08:30:46.273  5423  5469 I jxcore-log: ok 96 participant data matches
09-16 08:30:46.273  5423  5469 I jxcore-log: 
,09-16 08:30:46.274  5423  5469 I jxcore-log: ok 97 own UUID is found from the participants list
09-16 08:30:46.274  5423  5469 I jxcore-log: 
,09-16 08:30:46.278  5423  5469 I jxcore-log: # teardown
09-16 08:30:46.278  5423  5469 I jxcore-log: 
,09-16 08:30:46.334  5423  5469 I jxcore-log: # setup
09-16 08:30:46.334  5423  5469 I jxcore-log: 
,09-16 08:30:46.397  5423  5469 I jxcore-log: # 27. #startListeningForAdvertisements should fail if start not called
09-16 08:30:46.397  5423  5469 I jxcore-log: 
,09-16 08:30:46.472  5423  5469 I jxcore-log: ok 98 specific error should be returned
09-16 08:30:46.472  5423  5469 I jxcore-log: 
,09-16 08:30:46.476  5423  5469 I jxcore-log: # teardown
09-16 08:30:46.476  5423  5469 I jxcore-log: 
,09-16 08:30:46.541  5423  5469 I jxcore-log: ok 99 error should be null
09-16 08:30:46.541  5423  5469 I jxcore-log: 
,09-16 08:30:46.543  5423  5469 I jxcore-log: ok 100 error should be null
09-16 08:30:46.543  5423  5469 I jxcore-log: 
,09-16 08:30:46.547  5423  5469 I jxcore-log: # setup
09-16 08:30:46.547  5423  5469 I jxcore-log: 
,09-16 08:30:46.605  5423  5469 I jxcore-log: # 28. #startUpdateAdvertisingAndListening should fail if start not called
09-16 08:30:46.605  5423  5469 I jxcore-log: 
,09-16 08:30:46.680  5423  5469 I jxcore-log: ok 101 specific error should be returned
09-16 08:30:46.680  5423  5469 I jxcore-log: 
,09-16 08:30:46.683  5423  5469 I jxcore-log: # teardown
09-16 08:30:46.683  5423  5469 I jxcore-log: 
,09-16 08:30:46.726  5423  5469 I jxcore-log: ok 102 error should be null
09-16 08:30:46.726  5423  5469 I jxcore-log: 
,09-16 08:30:46.726  5423  5469 I jxcore-log: ok 103 error should be null
09-16 08:30:46.726  5423  5469 I jxcore-log: 
09-16 08:30:46.728  5423  5469 I jxcore-log: # setup
09-16 08:30:46.728  5423  5469 I jxcore-log: 
,09-16 08:30:46.833  5423  5469 I jxcore-log: # 29. should be able to call #stopListeningForAdvertisements many times
09-16 08:30:46.833  5423  5469 I jxcore-log: 
,09-16 08:30:47.024  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 45886
09-16 08:30:47.024  5423  5469 I jxcore-log: 
,09-16 08:30:47.025  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:47.025  5423  5469 I jxcore-log: 
,09-16 08:30:47.026  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 43489
09-16 08:30:47.026  5423  5469 I jxcore-log: 
,09-16 08:30:47.028  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 08:30:47.028  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 08:30:47.029  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:30:47.029  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:47.032  5423  5469 I jxcore-log: ok 104 error should be null
09-16 08:30:47.032  5423  5469 I jxcore-log: 
,09-16 08:30:47.032  5423  5469 I jxcore-log: ok 105 error should be null
09-16 08:30:47.032  5423  5469 I jxcore-log: 
,09-16 08:30:47.033  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 08:30:47.033  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 08:30:47.033  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-16 08:30:47.033  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:47.035  5423  5469 I jxcore-log: ok 106 error should be null
09-16 08:30:47.035  5423  5469 I jxcore-log: 
,09-16 08:30:47.035  5423  5469 I jxcore-log: ok 107 error should be null
09-16 08:30:47.035  5423  5469 I jxcore-log: 
,09-16 08:30:47.047  5423  5469 I jxcore-log: # teardown
09-16 08:30:47.047  5423  5469 I jxcore-log: 
,09-16 08:30:47.086  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
09-16 08:30:47.086  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:30:47.087  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:30:47.087  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:47.089  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 08:30:47.089  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 08:30:47.089  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:30:47.089  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:47.094  5423  5469 I jxcore-log: ok 108 error should be null
09-16 08:30:47.094  5423  5469 I jxcore-log: 
,09-16 08:30:47.094  5423  5469 I jxcore-log: ok 109 error should be null
09-16 08:30:47.094  5423  5469 I jxcore-log: 
,09-16 08:30:47.099  5423  5469 I jxcore-log: # setup
09-16 08:30:47.099  5423  5469 I jxcore-log: 
,09-16 08:30:47.148  5423  5469 I jxcore-log: # 30. should be able to call #startListeningForAdvertisements many times
09-16 08:30:47.148  5423  5469 I jxcore-log: 
,09-16 08:30:47.243  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 37467
09-16 08:30:47.243  5423  5469 I jxcore-log: 
,09-16 08:30:47.245  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:47.245  5423  5469 I jxcore-log: 
,09-16 08:30:47.250  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 48999
09-16 08:30:47.250  5423  5469 I jxcore-log: 
,09-16 08:30:47.259  5423  5469 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 08:30:47.263  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
09-16 08:30:47.264  5423  5469 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 08:30:47.264  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:30:47.264  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-16 08:30:47.264  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 08:30:47.264  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:30:47.264  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 08:30:47.270  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 08:30:47.270  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 08:30:47.275  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 08:30:47.275  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:30:47.275  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 08:30:47.279  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 08:30:47.279  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 08:30:47.279  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 08:30:47.280  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:47.282  5715  5742 D BtGatt.GattService: registerClient() - UUID=4350693b-7dc3-45cc-8563-6589bd67730b
,09-16 08:30:47.283  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=4350693b-7dc3-45cc-8563-6589bd67730b, clientIf=5
,09-16 08:30:47.283  5423  5434 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 08:30:47.284  5715  5745 D BtGatt.GattService: start scan with filters
09-16 08:30:47.286  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 08:30:47.286  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 08:30:47.286  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 08:30:47.286  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 08:30:47.287  5715  5734 D BtGatt.ScanManager: handling starting scan
,09-16 08:30:47.289  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:30:47.289  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 08:30:47.289  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:30:47.290  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 08:30:47.294  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 08:30:47.294  5715  5731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 08:30:47.295  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:47.295  5715  5734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 08:30:47.302  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 08:30:47.302  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:47.303  5715  5734 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:30:47.303  5715  5734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 08:30:47.314  5715  5731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 08:30:47.314  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:47.320  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 08:30:47.320  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:47.790  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 08:30:47.791  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:30:47.791  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:30:47.798  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 08:30:47.798  5423  5469 I jxcore-log: 
,09-16 08:30:47.803  5423  5469 I jxcore-log: ok 110 error should be null
09-16 08:30:47.803  5423  5469 I jxcore-log: 
,09-16 08:30:47.804  5423  5469 I jxcore-log: ok 111 error should be null
09-16 08:30:47.804  5423  5469 I jxcore-log: 
09-16 08:30:47.809  5423  5469 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 08:30:47.818  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,09-16 08:30:47.818  5423  5469 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 08:30:47.818  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:30:47.818  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:30:47.818  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 08:30:47.822  5423  5469 I jxcore-log: ok 112 error should be null
09-16 08:30:47.822  5423  5469 I jxcore-log: 
,09-16 08:30:47.822  5423  5469 I jxcore-log: ok 113 error should be null
09-16 08:30:47.822  5423  5469 I jxcore-log: 
,09-16 08:30:47.826  5423  5469 I jxcore-log: # teardown
09-16 08:30:47.826  5423  5469 I jxcore-log: 
,09-16 08:30:47.995  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 08:30:47.995  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:30:47.995  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:30:47.995  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 08:30:47.996  5423  5469 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 08:30:47.997  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-16 08:30:47.997  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:30:47.997  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 08:30:47.997  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 08:30:47.997  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 08:30:47.998  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 08:30:47.998  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 08:30:48.003  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:48.006  5715  5726 D BtGatt.GattService: stopScan() - queue size =1
,09-16 08:30:48.009  5715  5742 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 08:30:48.010  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 08:30:48.010  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-16 08:30:48.010  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 08:30:48.010  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-16 08:30:48.011  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 08:30:48.016  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:48.016  5715  5715 D BtGatt.ScanManager: awakened up at time 472119
09-16 08:30:48.016  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 08:30:48.017  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 08:30:48.018  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 08:30:48.019  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 08:30:48.023  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:48.024  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:48.024  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:48.025  5423  5469 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 08:30:48.025  5423  5469 I jxcore-log: 
09-16 08:30:48.027  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 08:30:48.027  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:48.027  5715  5734 D BtGatt.ScanManager: stopping BLe Batch
,09-16 08:30:48.036  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 08:30:48.036  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:48.036  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:30:48.048  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-16 08:30:48.048  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:48.048  5715  5731 D BtGatt.GattService: current time is 472152202889
09-16 08:30:48.048  5715  5731 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -78, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
09-16 08:30:48.048  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-16 08:30:48.049  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-16 08:30:48.049  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-16 08:30:48.049  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-16 08:30:48.525  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:30:48.525  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:30:48.526  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-16 08:30:48.529  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 08:30:48.529  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 08:30:48.529  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:30:48.529  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:48.533  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:30:48.533  5423  5469 I jxcore-log: 
,09-16 08:30:48.545  5423  5469 I jxcore-log: ok 114 error should be null
09-16 08:30:48.545  5423  5469 I jxcore-log: 
,09-16 08:30:48.546  5423  5469 I jxcore-log: ok 115 error should be null
09-16 08:30:48.546  5423  5469 I jxcore-log: 
,09-16 08:30:48.554  5423  5469 I jxcore-log: # setup
09-16 08:30:48.554  5423  5469 I jxcore-log: 
,09-16 08:30:48.675  5423  5469 I jxcore-log: # 31. should be able to call #startUpdateAdvertisingAndListening many times
09-16 08:30:48.675  5423  5469 I jxcore-log: 
,09-16 08:30:48.744  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 48055
09-16 08:30:48.744  5423  5469 I jxcore-log: 
,09-16 08:30:48.747  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:48.747  5423  5469 I jxcore-log: 
,09-16 08:30:48.751  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 39730
09-16 08:30:48.751  5423  5469 I jxcore-log: 
,09-16 08:30:48.770  5423  5469 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 08:30:48.775  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 39730, start advertisements: true
,09-16 08:30:48.775  5423  5469 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 08:30:48.775  5423  5469 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-16 08:30:48.775  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-16 08:30:48.775  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-16 08:30:48.775  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 08:30:48.776  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 08:30:48.776  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:48.779  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 08:30:48.783  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 08:30:48.784  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 08:30:48.784  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 08:30:48.784  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-16 08:30:48.784  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 08:30:48.785  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:30:48.785  5423  5832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:30:48.785  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 08:30:48.786  5755  5755 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32674]" dev="sockfs" ino=32674 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 08:30:48.786  5755  5755 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32674]" dev="sockfs" ino=32674 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:30:48.790  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 08:30:48.790  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 08:30:48.791  5423  5832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-16 08:30:48.795  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 08:30:48.796  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:30:48.796  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 08:30:48.798  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-16 08:30:48.798  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:30:48.798  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-16 08:30:48.799  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:48.799  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:48.799  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-16 08:30:48.800  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:48.805  5715  5745 D BtGatt.GattService: registerClient() - UUID=a370c050-dc77-40eb-9509-ef1e26328d75
,09-16 08:30:48.805  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=a370c050-dc77-40eb-9509-ef1e26328d75, clientIf=5
09-16 08:30:48.805  5423  5434 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 08:30:48.807  5715  5733 D BtGatt.AdvertiseManager: message : 0
,09-16 08:30:48.808  5715  5733 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 08:30:48.819  5715  5731 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 08:30:48.825  5715  5731 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 08:30:48.825  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-16 08:30:48.826  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 08:30:48.827  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 08:30:48.828  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
09-16 08:30:48.828  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-16 08:30:48.828  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 08:30:48.828  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 08:30:48.828  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 08:30:48.829  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-16 08:30:48.829  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-16 08:30:48.830  5423  5469 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 44136
09-16 08:30:48.830  5423  5469 I jxcore-log: 
,09-16 08:30:48.832  5423  5423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-16 08:30:48.832  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 08:30:49.333  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-16 08:30:49.333  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-16 08:30:49.333  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:30:49.343  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 08:30:49.343  5423  5469 I jxcore-log: 
,09-16 08:30:49.346  5423  5469 I jxcore-log: ok 116 error should be null
09-16 08:30:49.346  5423  5469 I jxcore-log: 
09-16 08:30:49.348  5423  5469 I jxcore-log: ok 117 error should be null
09-16 08:30:49.348  5423  5469 I jxcore-log: 
,09-16 08:30:49.359  5423  5469 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 08:30:49.362  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 39730, start advertisements: true
09-16 08:30:49.363  5423  5469 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 08:30:49.363  5423  5469 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-16 08:30:49.363  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,09-16 08:30:49.365  5715  5733 D BtGatt.AdvertiseManager: message : 1
,09-16 08:30:49.371  5715  5733 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 08:30:49.380  5715  5731 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-16 08:30:49.381  5715  5731 D BtGatt.GattService: Client app is not null!
09-16 08:30:49.382  5715  5726 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 08:30:49.382  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 08:30:49.382  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-16 08:30:49.383  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 08:30:49.383  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-16 08:30:49.383  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:30:49.383  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-16 08:30:49.384  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:49.384  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:49.384  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-16 08:30:49.385  5423  5469 D BluetoothAdapter: STATE_ON
09-16 08:30:49.388  5715  5726 D BtGatt.GattService: registerClient() - UUID=f5fa16d7-3562-4868-b11e-bee85e49f90f
,09-16 08:30:49.389  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=f5fa16d7-3562-4868-b11e-bee85e49f90f, clientIf=5
09-16 08:30:49.389  5423  5433 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 08:30:49.390  5715  5733 D BtGatt.AdvertiseManager: message : 0
,09-16 08:30:49.396  5715  5733 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 08:30:49.407  5715  5731 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 08:30:49.414  5715  5731 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 08:30:49.414  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 08:30:49.414  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-16 08:30:49.414  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:30:49.414  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 08:30:49.414  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-16 08:30:49.414  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 08:30:49.415  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 08:30:49.415  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 08:30:49.415  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 08:30:49.422  5423  5469 I jxcore-log: ok 118 error should be null
09-16 08:30:49.422  5423  5469 I jxcore-log: 
,09-16 08:30:49.424  5423  5469 I jxcore-log: ok 119 error should be null
09-16 08:30:49.424  5423  5469 I jxcore-log: 
09-16 08:30:49.427  5423  5469 I jxcore-log: # teardown
09-16 08:30:49.427  5423  5469 I jxcore-log: 
,09-16 08:30:49.661  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 08:30:49.662  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:30:49.662  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-16 08:30:49.662  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 08:30:49.662  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-16 08:30:49.662  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 08:30:49.662  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-16 08:30:49.663  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-16 08:30:49.663  5423  5832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-16 08:30:49.663  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-16 08:30:49.663  5423  5832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-16 08:30:49.663  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:30:49.664  5423  5832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 08:30:49.664  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 08:30:49.664  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 08:30:49.664  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 08:30:49.664  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 08:30:49.664  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 08:30:49.667  5423  5469 D BluetoothAdapter: STATE_ON
09-16 08:30:49.667  5423  5469 D BluetoothLeScanner: could not find callback wrapper
09-16 08:30:49.667  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 08:30:49.667  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-16 08:30:49.670  5715  5733 D BtGatt.AdvertiseManager: message : 1
09-16 08:30:49.671  5715  5733 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 08:30:49.684  5715  5731 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-16 08:30:49.684  5715  5731 D BtGatt.GattService: Client app is not null!
,09-16 08:30:49.686  5715  5742 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 08:30:49.687  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 08:30:49.687  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-16 08:30:49.687  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-16 08:30:49.688  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-16 08:30:49.688  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-16 08:30:49.690  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:49.690  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 08:30:49.690  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 08:30:49.692  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 08:30:49.695  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:30:49.695  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-16 08:30:49.695  5423  5423 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 08:30:49.695  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:49.695  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 08:30:49.695  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:49.697  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 08:30:49.697  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 08:30:49.697  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:30:49.697  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:49.703  5423  5469 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 08:30:49.703  5423  5469 I jxcore-log: 
,09-16 08:30:49.709  5423  5469 I jxcore-log: ok 120 error should be null
09-16 08:30:49.709  5423  5469 I jxcore-log: 
,09-16 08:30:49.709  5423  5469 I jxcore-log: ok 121 error should be null
09-16 08:30:49.709  5423  5469 I jxcore-log: 
,09-16 08:30:49.715  5423  5469 I jxcore-log: # setup
09-16 08:30:49.715  5423  5469 I jxcore-log: 
,09-16 08:30:49.797  5423  5469 I jxcore-log: # 32. should be able to call #stopAdvertisingAndListening many times
09-16 08:30:49.797  5423  5469 I jxcore-log: 
,09-16 08:30:49.885  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 45852
09-16 08:30:49.885  5423  5469 I jxcore-log: 
,09-16 08:30:49.888  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:49.888  5423  5469 I jxcore-log: 
,09-16 08:30:49.892  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 42800
09-16 08:30:49.892  5423  5469 I jxcore-log: 
,09-16 08:30:49.898  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 08:30:49.898  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:30:49.899  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:30:49.899  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:49.903  5423  5469 I jxcore-log: ok 122 error should be null
09-16 08:30:49.903  5423  5469 I jxcore-log: 
,09-16 08:30:49.904  5423  5469 I jxcore-log: ok 123 error should be null
09-16 08:30:49.904  5423  5469 I jxcore-log: 
,09-16 08:30:49.907  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 08:30:49.907  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:30:49.908  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:30:49.908  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:49.912  5423  5469 I jxcore-log: ok 124 error should be null
09-16 08:30:49.912  5423  5469 I jxcore-log: 
,09-16 08:30:49.912  5423  5469 I jxcore-log: ok 125 error should be null
09-16 08:30:49.912  5423  5469 I jxcore-log: 
,09-16 08:30:49.917  5423  5469 I jxcore-log: # teardown
09-16 08:30:49.917  5423  5469 I jxcore-log: 
,09-16 08:30:49.960  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 08:30:49.960  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:30:49.961  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:30:49.961  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:49.963  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 08:30:49.963  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 08:30:49.963  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:30:49.963  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:49.969  5423  5469 I jxcore-log: ok 126 error should be null
09-16 08:30:49.969  5423  5469 I jxcore-log: 
,09-16 08:30:49.970  5423  5469 I jxcore-log: ok 127 error should be null
09-16 08:30:49.970  5423  5469 I jxcore-log: 
,09-16 08:30:49.976  5423  5469 I jxcore-log: # setup
09-16 08:30:49.976  5423  5469 I jxcore-log: 
,09-16 08:30:50.016  5423  5469 I jxcore-log: # 33. #start should fail if called twice in a row
09-16 08:30:50.016  5423  5469 I jxcore-log: 
,09-16 08:30:50.153  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 43898
09-16 08:30:50.153  5423  5469 I jxcore-log: 
,09-16 08:30:50.155  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:50.155  5423  5469 I jxcore-log: 
,09-16 08:30:50.160  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 40744
09-16 08:30:50.160  5423  5469 I jxcore-log: 
,09-16 08:30:50.164  5423  5469 I jxcore-log: ok 128 first call should succeed
09-16 08:30:50.164  5423  5469 I jxcore-log: 
09-16 08:30:50.165  5423  5469 I jxcore-log: ok 129 first call should succeed
09-16 08:30:50.165  5423  5469 I jxcore-log: 
,09-16 08:30:50.170  5423  5469 I jxcore-log: ok 130 specific error should be returned
09-16 08:30:50.170  5423  5469 I jxcore-log: 
,09-16 08:30:50.172  5423  5469 I jxcore-log: # teardown
09-16 08:30:50.172  5423  5469 I jxcore-log: 
,09-16 08:30:50.196  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:30:50.198  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:30:50.198  5423  5469 I jxcore-log: 
,09-16 08:30:50.220  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 08:30:50.220  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:30:50.220  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:30:50.220  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:50.222  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 08:30:50.223  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-16 08:30:50.223  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:30:50.223  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:50.229  5423  5469 I jxcore-log: ok 131 error should be null
09-16 08:30:50.229  5423  5469 I jxcore-log: 
09-16 08:30:50.230  5423  5469 I jxcore-log: ok 132 error should be null
09-16 08:30:50.230  5423  5469 I jxcore-log: 
,09-16 08:30:50.240  5423  5469 I jxcore-log: # setup
09-16 08:30:50.240  5423  5469 I jxcore-log: 
,09-16 08:30:50.295  5423  5469 I jxcore-log: # 34. does not emit duplicate discoveryAdvertisingStateUpdate
09-16 08:30:50.295  5423  5469 I jxcore-log: 
,09-16 08:30:50.365  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 39585
09-16 08:30:50.365  5423  5469 I jxcore-log: 
,09-16 08:30:50.367  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:50.367  5423  5469 I jxcore-log: 
,09-16 08:30:50.372  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 38033
09-16 08:30:50.372  5423  5469 I jxcore-log: 
,09-16 08:30:50.377  5423  5469 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 08:30:50.381  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 39730, start advertisements: false
09-16 08:30:50.381  5423  5469 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 08:30:50.381  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:30:50.381  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 08:30:50.381  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-16 08:30:50.381  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:30:50.381  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 08:30:50.386  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 08:30:50.387  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 08:30:50.392  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 08:30:50.393  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 08:30:50.393  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 08:30:50.398  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 08:30:50.398  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 08:30:50.398  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 08:30:50.399  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:50.403  5715  5726 D BtGatt.GattService: registerClient() - UUID=a644ea7a-924f-49ba-976c-110cd9e8f3a9
,09-16 08:30:50.403  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=a644ea7a-924f-49ba-976c-110cd9e8f3a9, clientIf=5
,09-16 08:30:50.404  5423  5434 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 08:30:50.404  5715  5725 D BtGatt.GattService: start scan with filters
,09-16 08:30:50.408  5715  5734 D BtGatt.ScanManager: handling starting scan
09-16 08:30:50.409  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 08:30:50.409  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 08:30:50.409  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-16 08:30:50.409  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 08:30:50.413  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 08:30:50.413  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 08:30:50.413  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 08:30:50.415  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 08:30:50.415  5715  5731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 08:30:50.415  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:50.415  5715  5734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 08:30:50.418  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 08:30:50.422  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 08:30:50.422  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:50.423  5715  5734 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:30:50.423  5715  5734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 08:30:50.434  5715  5731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 08:30:50.434  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:50.441  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 08:30:50.441  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:50.495   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:50.914  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 08:30:50.915  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:30:50.915  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:30:50.920  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 08:30:50.920  5423  5469 I jxcore-log: 
,09-16 08:30:50.946  5423  5469 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 08:30:50.950  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 38033, start advertisements: true
09-16 08:30:50.950  5423  5469 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 08:30:50.950  5423  5469 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-16 08:30:50.950  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 08:30:50.950  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:30:50.952  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:50.953  5715  5742 D BtGatt.GattService: stopScan() - queue size =1
,09-16 08:30:50.954  5715  5755 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 08:30:50.955  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 08:30:50.955  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 08:30:50.955  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 08:30:50.955  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 08:30:50.955  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 08:30:50.955  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 08:30:50.957  5423  5469 D BluetoothAdapter: STATE_ON
09-16 08:30:50.961  5715  5715 D BtGatt.ScanManager: awakened up at time 475065
09-16 08:30:50.963  5715  5755 D BtGatt.GattService: registerClient() - UUID=0b394cd0-3f5f-491f-8a4d-b98844ffb5fb
,09-16 08:30:50.967  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=0b394cd0-3f5f-491f-8a4d-b98844ffb5fb, clientIf=5
,09-16 08:30:50.968  5423  5433 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 08:30:50.968  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 08:30:50.968  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:50.968  5715  5734 D BtGatt.ScanManager: stopping BLe Batch
09-16 08:30:50.968  5715  5725 D BtGatt.GattService: start scan with filters
09-16 08:30:50.971  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 08:30:50.971  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 08:30:50.971  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-16 08:30:50.971  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 08:30:50.972  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 08:30:50.972  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 08:30:50.972  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-16 08:30:50.973  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 08:30:50.973  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-16 08:30:50.974  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 08:30:50.974  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 08:30:50.974  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 08:30:50.974  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:30:50.974  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 08:30:50.974  5423  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 08:30:50.973  5755  5755 W Binder_5: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32684]" dev="sockfs" ino=32684 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:30:50.973  5755  5755 W Binder_5: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[32684]" dev="sockfs" ino=32684 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:30:50.975  5423  5469 D BluetoothAdapter: STATE_ON
09-16 08:30:50.975  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 08:30:50.975  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:50.975  5715  5745 D BtGatt.GattService: stopScan() - queue size =0
09-16 08:30:50.975  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 08:30:50.976  5715  5742 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 08:30:50.976  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 08:30:50.977  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 08:30:50.977  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 08:30:50.977  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 08:30:50.977  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 08:30:50.978  5423  5834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-16 08:30:50.978  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:50.979  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 08:30:50.982  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:30:50.982  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:50.983  5715  5734 D BtGatt.ScanManager: handling starting scan
09-16 08:30:50.984  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-16 08:30:50.984  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:30:50.984  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-16 08:30:50.985  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:50.985  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:50.985  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-16 08:30:50.986  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:50.989  5715  5726 D BtGatt.GattService: registerClient() - UUID=8c3dcba7-9ecd-4adc-bbbc-0135c60960e4
,09-16 08:30:50.990  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=8c3dcba7-9ecd-4adc-bbbc-0135c60960e4, clientIf=5
,09-16 08:30:50.990  5423  5434 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 08:30:50.992  5715  5731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 08:30:50.992  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:50.993  5715  5733 D BtGatt.AdvertiseManager: message : 0
09-16 08:30:50.993  5715  5734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 08:30:50.996  5715  5733 D BtGatt.AdvertiseManager: starting multi advertising
09-16 08:30:50.998  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 08:30:50.998  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:50.998  5715  5734 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:30:50.998  5715  5734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 08:30:51.008  5715  5731 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 08:30:51.016  5715  5731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 08:30:51.016  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:51.022  5715  5731 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 08:30:51.022  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-16 08:30:51.022  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 08:30:51.023  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 08:30:51.025  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 08:30:51.025  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 08:30:51.025  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:51.025  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 08:30:51.025  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 08:30:51.025  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 08:30:51.025  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-16 08:30:51.025  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-16 08:30:51.026  5423  5469 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 40718
09-16 08:30:51.026  5423  5469 I jxcore-log: 
09-16 08:30:51.027  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 08:30:51.027  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:51.029  5423  5423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-16 08:30:51.029  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 08:30:51.034  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-16 08:30:51.034  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:51.034  5715  5734 D BtGatt.ScanManager: stopping BLe Batch
,09-16 08:30:51.041  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 08:30:51.041  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:51.041  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:30:51.046  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 08:30:51.046  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:51.496   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:51.530  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 08:30:51.530  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-16 08:30:51.530  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:30:51.539  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 08:30:51.539  5423  5469 I jxcore-log: 
,09-16 08:30:51.550  5423  5469 I jxcore-log: ok 133 called only once
09-16 08:30:51.550  5423  5469 I jxcore-log: 
,09-16 08:30:51.551  5423  5469 I jxcore-log: ok 134 discovery state matches
09-16 08:30:51.551  5423  5469 I jxcore-log: 
09-16 08:30:51.552  5423  5469 I jxcore-log: ok 135 advertising state matches
09-16 08:30:51.552  5423  5469 I jxcore-log: 
,09-16 08:30:51.563  5423  5469 I jxcore-log: # teardown
09-16 08:30:51.563  5423  5469 I jxcore-log: 
,09-16 08:30:51.929  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 08:30:51.930  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:30:51.930  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-16 08:30:51.930  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-16 08:30:51.930  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 08:30:51.930  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 08:30:51.931  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-16 08:30:51.931  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-16 08:30:51.931  5423  5834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 08:30:51.931  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-16 08:30:51.931  5423  5834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 08:30:51.931  5423  5834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-16 08:30:51.931  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:30:51.932  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 08:30:51.932  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 08:30:51.932  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 08:30:51.932  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 08:30:51.932  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 08:30:51.935  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:51.935  5423  5469 D BluetoothLeScanner: could not find callback wrapper
09-16 08:30:51.935  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 08:30:51.935  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-16 08:30:51.940  5715  5733 D BtGatt.AdvertiseManager: message : 1
,09-16 08:30:51.942  5715  5733 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 08:30:51.955  5715  5731 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-16 08:30:51.955  5715  5731 D BtGatt.GattService: Client app is not null!
09-16 08:30:51.957  5715  5745 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 08:30:51.957  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 08:30:51.957  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-16 08:30:51.957  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-16 08:30:51.958  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-16 08:30:51.958  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-16 08:30:51.960  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:51.960  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 08:30:51.960  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 08:30:51.961  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 08:30:51.963  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:30:51.964  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-16 08:30:51.964  5423  5423 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 08:30:51.964  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:51.964  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 08:30:51.964  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:51.965  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 08:30:51.965  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-16 08:30:51.965  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:30:51.965  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:30:51.970  5423  5469 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
09-16 08:30:51.970  5423  5469 I jxcore-log: 
,09-16 08:30:51.971  5423  5469 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 08:30:51.971  5423  5469 I jxcore-log: 
,09-16 08:30:51.973  5423  5469 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 08:30:51.973  5423  5469 I jxcore-log: 
,09-16 08:30:51.978  5423  5469 I jxcore-log: ok 136 error should be null
09-16 08:30:51.978  5423  5469 I jxcore-log: 
,09-16 08:30:51.978  5423  5469 I jxcore-log: ok 137 error should be null
09-16 08:30:51.978  5423  5469 I jxcore-log: 
,09-16 08:30:51.984  5423  5469 I jxcore-log: # setup
09-16 08:30:51.984  5423  5469 I jxcore-log: 
,09-16 08:30:52.018  5423  5469 I jxcore-log: # 35. does not send duplicate availability changes
09-16 08:30:52.018  5423  5469 I jxcore-log: 
,09-16 08:30:52.086  5423  5469 I jxcore-log: ok 138 should be called once
09-16 08:30:52.086  5423  5469 I jxcore-log: 
,09-16 08:30:52.088  5423  5469 I jxcore-log: ok 139 should not have been called more than once
09-16 08:30:52.088  5423  5469 I jxcore-log: 
,09-16 08:30:52.091  5423  5469 I jxcore-log: # teardown
09-16 08:30:52.091  5423  5469 I jxcore-log: 
,09-16 08:30:52.170  5423  5469 I jxcore-log: ok 140 error should be null
09-16 08:30:52.170  5423  5469 I jxcore-log: 
,09-16 08:30:52.171  5423  5469 I jxcore-log: ok 141 error should be null
09-16 08:30:52.171  5423  5469 I jxcore-log: 
,09-16 08:30:52.174  5423  5469 I jxcore-log: # setup
09-16 08:30:52.174  5423  5469 I jxcore-log: 
,09-16 08:30:52.238  5423  5469 I jxcore-log: # 36. can get the network status
09-16 08:30:52.238  5423  5469 I jxcore-log: 
,09-16 08:30:52.315  5423  5469 I jxcore-log: ok 142 network status should have certain non-empty properties
09-16 08:30:52.315  5423  5469 I jxcore-log: 
,09-16 08:30:52.318  5423  5469 I jxcore-log: # teardown
09-16 08:30:52.318  5423  5469 I jxcore-log: 
,09-16 08:30:52.385  5423  5469 I jxcore-log: ok 143 error should be null
09-16 08:30:52.385  5423  5469 I jxcore-log: 
,09-16 08:30:52.386  5423  5469 I jxcore-log: ok 144 error should be null
09-16 08:30:52.386  5423  5469 I jxcore-log: 
,09-16 08:30:52.391  5423  5469 I jxcore-log: # setup
09-16 08:30:52.391  5423  5469 I jxcore-log: 
,09-16 08:30:52.439  5423  5469 I jxcore-log: # 37. wifi peer is marked unavailable if announcements stop
09-16 08:30:52.439  5423  5469 I jxcore-log: 
,09-16 08:30:52.465  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:30:52.468  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:30:52.468  5423  5469 I jxcore-log: 
,09-16 08:30:52.497   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:52.529  5423  5469 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
09-16 08:30:52.529  5423  5469 I jxcore-log: 
,09-16 08:30:52.557  5423  5469 I jxcore-log: ok 145 host address should match
09-16 08:30:52.557  5423  5469 I jxcore-log: 
,09-16 08:30:52.558  5423  5469 I jxcore-log: ok 146 port should match
09-16 08:30:52.558  5423  5469 I jxcore-log: 
,09-16 08:30:53.498   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:54.499   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:30:54.526  5423  5469 I jxcore-log: ok 147 host address should be null
09-16 08:30:54.526  5423  5469 I jxcore-log: 
09-16 08:30:54.527  5423  5469 I jxcore-log: ok 148 port should should be null
09-16 08:30:54.527  5423  5469 I jxcore-log: 
,09-16 08:30:54.540  5423  5469 I jxcore-log: # teardown
09-16 08:30:54.540  5423  5469 I jxcore-log: 
,09-16 08:30:54.615  5423  5469 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 08:30:54.615  5423  5469 I jxcore-log: 
,09-16 08:30:54.618  5423  5469 I jxcore-log: ok 149 error should be null
09-16 08:30:54.618  5423  5469 I jxcore-log: 
09-16 08:30:54.619  5423  5469 I jxcore-log: ok 150 error should be null
09-16 08:30:54.619  5423  5469 I jxcore-log: 
,09-16 08:30:54.624  5423  5469 I jxcore-log: # setup
09-16 08:30:54.624  5423  5469 I jxcore-log: 
,09-16 08:30:54.796  5423  5469 I jxcore-log: # 38. Client to server request coordinated
09-16 08:30:54.796  5423  5469 I jxcore-log: 
,09-16 08:30:54.853  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 48969
09-16 08:30:54.853  5423  5469 I jxcore-log: 
,09-16 08:30:54.855  5423  5469 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 08:30:54.855  5423  5469 I jxcore-log: 
09-16 08:30:54.858  5423  5469 I jxcore-log: DEBUG createNativeListener: listening 37819
09-16 08:30:54.858  5423  5469 I jxcore-log: 
,09-16 08:30:54.860  5423  5469 I jxcore-log: ok 151 error should be null
09-16 08:30:54.860  5423  5469 I jxcore-log: 
,09-16 08:30:54.860  5423  5469 I jxcore-log: ok 152 error should be null
09-16 08:30:54.860  5423  5469 I jxcore-log: 
,09-16 08:30:54.927  5423  5469 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 08:30:54.931  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 37819, start advertisements: true
,09-16 08:30:54.931  5423  5469 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 08:30:54.931  5423  5469 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-16 08:30:54.931  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-16 08:30:54.932  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 08:30:54.932  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 08:30:54.932  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 08:30:54.932  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:30:54.933  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-16 08:30:54.933  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 08:30:54.934  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 08:30:54.934  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 08:30:54.934  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 08:30:54.934  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 08:30:54.934  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 08:30:54.934  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 08:30:54.938  5423  5835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:30:54.940  5423  5835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-16 08:30:54.936  5755  5755 W Binder_5: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34130]" dev="sockfs" ino=34130 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:30:54.936  5755  5755 W Binder_5: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34130]" dev="sockfs" ino=34130 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:30:54.941  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 08:30:54.941  5423  5469 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 08:30:54.945  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 08:30:54.947  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:30:54.947  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 08:30:54.948  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-16 08:30:54.948  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 08:30:54.948  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-16 08:30:54.948  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:54.948  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 08:30:54.948  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-16 08:30:54.948  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:54.950  5715  5725 D BtGatt.GattService: registerClient() - UUID=3bc99e22-5a32-4bee-8b04-b8c738fb48b8
,09-16 08:30:54.950  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=3bc99e22-5a32-4bee-8b04-b8c738fb48b8, clientIf=5
09-16 08:30:54.950  5423  5433 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 08:30:54.951  5715  5733 D BtGatt.AdvertiseManager: message : 0
,09-16 08:30:54.952  5715  5733 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 08:30:54.960  5715  5731 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 08:30:54.965  5715  5731 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 08:30:54.966  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-16 08:30:54.966  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 08:30:54.968  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 08:30:54.969  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
09-16 08:30:54.969  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 08:30:54.969  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 08:30:54.969  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 08:30:54.969  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 08:30:54.969  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-16 08:30:54.969  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-16 08:30:54.971  5423  5423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-16 08:30:54.971  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 08:30:54.972  5423  5469 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 46563
09-16 08:30:54.972  5423  5469 I jxcore-log: 
,09-16 08:30:55.472  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 08:30:55.473  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 08:30:55.473  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:30:55.478  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 08:30:55.478  5423  5469 I jxcore-log: 
,09-16 08:30:55.489  5423  5469 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 08:30:55.494  5423  5469 I io.jxcore.node.ConnectionHelper: start: Port number: 37819, start advertisements: false
,09-16 08:30:55.494  5423  5469 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 08:30:55.495  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should affect listening to advertisements only
09-16 08:30:55.495  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 08:30:55.495  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 08:30:55.495  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 08:30:55.495  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-16 08:30:55.497  5715  5733 D BtGatt.AdvertiseManager: message : 1
,09-16 08:30:55.497  5715  5733 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 08:30:55.500   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:30:55.507  5715  5731 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-16 08:30:55.507  5715  5731 D BtGatt.GattService: Client app is not null!
,09-16 08:30:55.508  5715  5742 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 08:30:55.509  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 08:30:55.509  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-16 08:30:55.509  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-16 08:30:55.509  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-16 08:30:55.509  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-16 08:30:55.511  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:55.511  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:30:55.514  5423  5469 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 08:30:55.519  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 08:30:55.519  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 08:30:55.519  5423  5469 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 08:30:55.520  5423  5469 D BluetoothAdapter: STATE_ON
,09-16 08:30:55.524  5715  5726 D BtGatt.GattService: registerClient() - UUID=bfd2d0bf-428d-4d48-a6ce-8ef83717c3d5
,09-16 08:30:55.525  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=bfd2d0bf-428d-4d48-a6ce-8ef83717c3d5, clientIf=5
09-16 08:30:55.525  5423  5433 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 08:30:55.526  5715  5742 D BtGatt.GattService: start scan with filters
,09-16 08:30:55.529  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 08:30:55.529  5715  5734 D BtGatt.ScanManager: handling starting scan
09-16 08:30:55.529  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 08:30:55.529  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 08:30:55.529  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 08:30:55.534  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:30:55.534  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 08:30:55.534  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 08:30:55.535  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 08:30:55.537  5715  5731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 08:30:55.537  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:55.537  5715  5734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 08:30:55.538  5423  5469 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 08:30:55.543  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 08:30:55.544  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:30:55.544  5715  5734 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:30:55.544  5715  5734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 08:30:55.555  5715  5731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 08:30:55.555  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:55.561  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 08:30:55.561  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:30:56.035  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 08:30:56.035  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 08:30:56.036  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:30:56.041  5423  5469 I jxcore-log: INFO testThaliNotification: startListeningForAdvertisements
09-16 08:30:56.041  5423  5469 I jxcore-log: 
,09-16 08:30:56.045  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 08:30:56.045  5423  5469 I jxcore-log: 
,09-16 08:30:56.399  5423  5469 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.137, 192.168.1.137, 59475
09-16 08:30:56.399  5423  5469 I jxcore-log: 
,09-16 08:30:56.600  5423  5469 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.107, 192.168.1.107, 40422
09-16 08:30:56.600  5423  5469 I jxcore-log: 
,09-16 08:31:00.565  5715  5715 D BtGatt.ScanManager: awakened up at time 484669
,09-16 08:31:00.567  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:00.610  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-16 08:31:00.610  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:31:00.610  5715  5731 D BtGatt.GattService: current time is 484714270182
,09-16 08:31:00.611  5715  5731 D BtGatt.GattService: Batch record : [-74, -22, -56, -28, 55, 97, 1, -128, -74, 99, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, -80, 48, 97, 74, 104, 79, 1, -128, -60, 99, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62, 0, 37, -47, 14, -113, 116, -46, 1, -128, -82, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-16 08:31:00.611  5715  5731 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
09-16 08:31:00.612  5715  5731 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62]
09-16 08:31:00.612  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 08:31:00.613  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 08:31:00.614  5715  5731 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 08:31:00.621  5423  5423 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 44:78:3E:94:4A:3E 5], added - the peer count is 1
09-16 08:31:00.622  5423  5423 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 5], added - the peer count is 2
09-16 08:31:00.622  5423  5423 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 5], Bluetooth address: 44:78:3E:94:4A:3E, device name: '', device address: ''
09-16 08:31:00.622  5423  5423 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
,09-16 08:31:00.631  5423  5469 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-16 08:31:00.631  5423  5469 I jxcore-log: 
,09-16 08:31:00.638  5423  5469 I jxcore-log: DEBUG createPeerListener: listening 47189
09-16 08:31:00.638  5423  5469 I jxcore-log: 
,09-16 08:31:00.640  5423  5469 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-16 08:31:00.640  5423  5469 I jxcore-log: 
,09-16 08:31:00.657  5423  5469 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-16 08:31:00.657  5423  5469 I jxcore-log: 
,09-16 08:31:00.666  5423  5469 I jxcore-log: DEBUG createPeerListener: listening 39140
09-16 08:31:00.666  5423  5469 I jxcore-log: 
,09-16 08:31:00.667  5423  5469 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-16 08:31:00.667  5423  5469 I jxcore-log: 
,09-16 08:31:00.685  5423  5469 I jxcore-log: DEBUG createPeerListener: first connection
09-16 08:31:00.685  5423  5469 I jxcore-log: 
,09-16 08:31:00.689  5423  5469 D io.jxcore.node.JXcoreExtension: connect: 44:78:3E:94:4A:3E
,09-16 08:31:00.689  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 44:78:3E:94:4A:3E
09-16 08:31:00.689  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 44:78:3E:94:4A:3E 5]
,09-16 08:31:00.691  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 44:78:3E:94:4A:3E
,09-16 08:31:00.692  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 08:31:00.692  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 08:31:00.692  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 44:78:3E:94:4A:3E
09-16 08:31:00.692  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 44:78:3E:94:4A:3E
09-16 08:31:00.692  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 44:78:3E:94:4A:3E)
09-16 08:31:00.693  5423  5836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 44:78:3E:94:4A:3E (thread ID: 196)
,09-16 08:31:00.694  5423  5469 I jxcore-log: DEBUG createPeerListener: first connection
09-16 08:31:00.694  5423  5469 I jxcore-log: 
,09-16 08:31:00.695  5423  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:31:00.693  5726  5726 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32704]" dev="sockfs" ino=32704 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 08:31:00.693  5726  5726 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32704]" dev="sockfs" ino=32704 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 08:31:00.698  5423  5469 D io.jxcore.node.JXcoreExtension: connect: A8:81:95:E9:5F:6F
09-16 08:31:00.698  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID A8:81:95:E9:5F:6F
09-16 08:31:00.698  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> A8:81:95:E9:5F:6F 5]
,09-16 08:31:00.700  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address A8:81:95:E9:5F:6F
,09-16 08:31:00.700  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 08:31:00.701  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 08:31:00.701  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null A8:81:95:E9:5F:6F
09-16 08:31:00.701  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address A8:81:95:E9:5F:6F
09-16 08:31:00.701  5423  5469 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: A8:81:95:E9:5F:6F)
09-16 08:31:00.701  5423  5837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address A8:81:95:E9:5F:6F (thread ID: 197)
09-16 08:31:00.703  5423  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:31:00.700  5755  5755 W Binder_5: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32709]" dev="sockfs" ino=32709 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:31:00.700  5755  5755 W Binder_5: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32709]" dev="sockfs" ino=32709 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 08:31:01.115  5715  5715 D BtGatt.ScanManager: awakened up at time 485219
,09-16 08:31:01.118  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:01.133  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 08:31:01.134  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:01.915  5715  5715 D BtGatt.ScanManager: awakened up at time 486018
,09-16 08:31:01.917  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:01.945  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:01.945  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:01.949  5715  5738 W bt_btif : bta_dm_acl_change info: 0x10
09-16 08:31:01.950  5715  5731 D bt_btif_dm: remote version info [44:78:3e:94:4a:3e]: 8, f, 6106
09-16 08:31:01.950  5715  5731 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,09-16 08:31:01.990  5715  5738 W bt_sdp  : process_service_search_attr_rsp
,09-16 08:31:02.451  5715  5715 D BtGatt.ScanManager: awakened up at time 486554
,09-16 08:31:02.454  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:02.472  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:02.472  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:02.572  5715  5731 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 1
,09-16 08:31:02.575  5715  5731 I bt_btif_dm: check_cod remote_cod = 0x00001f00 cod = 0x00000580
,09-16 08:31:02.578  5715  5732 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 10 NewState: 11
,09-16 08:31:02.579  5715  5732 I BluetoothBondStateMachine: Entering PendingCommandState State
09-16 08:31:02.579  3064  3311 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 08:31:02.581  5477  5477 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 08:31:02.582  3064  3311 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-16 08:31:02.583  5477  5477 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-16 08:31:02.594  5715  5738 W bt_btif : bta_dm_acl_change info: 0x10
09-16 08:31:02.594  5715  5731 D bt_btif_dm: remote version info [a8:81:95:e9:5f:6f]: 8, f, 6106
,09-16 08:31:02.598  5715  5731 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,09-16 08:31:02.655  5715  5738 W bt_sdp  : process_service_search_attr_rsp
,09-16 08:31:02.658  5715  5731 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 0
,09-16 08:31:02.659  5715  5732 D BluetoothAdapterProperties: Failed to remove device: 44:78:3E:94:4A:3E
,09-16 08:31:02.662  5715  5732 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 11 NewState: 10
,09-16 08:31:02.664  5477  5477 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
,09-16 08:31:02.666  3064  3311 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 08:31:02.669  5477  5477 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-16 08:31:02.671  3064  3311 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-16 08:31:02.676  5715  5732 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@21fb3a6
,09-16 08:31:02.677  5715  5732 D HidService: Saved priority 44:78:3E:94:4A:3E = -1
09-16 08:31:02.679  5715  5732 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 08:31:02.682  5715  5738 W bt_smp  : for SMP over BR max_key_size: 0x10,                        local_i_key: 0x07, local_r_key: 0x07
,09-16 08:31:02.699  5715  5731 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 1
,09-16 08:31:02.701  5715  5732 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 10 NewState: 11
,09-16 08:31:02.701  5715  5732 I BluetoothBondStateMachine: Entering PendingCommandState State
,09-16 08:31:02.701  3064  3311 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 08:31:02.702  5477  5477 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 08:31:02.703  5715  5738 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
09-16 08:31:02.703  3064  3311 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-16 08:31:02.703  5715  5738 W bt_smp  : flag = 0 round = 1
09-16 08:31:02.703  5715  5738 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
09-16 08:31:02.703  5715  5738 W bt_smp  : flag = 0 round = 1
09-16 08:31:02.703  5715  5738 W bt_smp  : smp_send_id_info
,09-16 08:31:02.705  5477  5477 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-16 08:31:02.719  5715  5731 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 0
,09-16 08:31:02.719  5715  5732 D BluetoothAdapterProperties: Failed to remove device: 44:78:3E:94:4A:3E
,09-16 08:31:02.720  5715  5732 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 11 NewState: 10
09-16 08:31:02.721  3064  3311 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
,09-16 08:31:02.721  5477  5477 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-16 08:31:02.722  5715  5732 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@21fb3a6
09-16 08:31:02.723  3064  3311 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-16 08:31:02.725  5715  5732 D HidService: Saved priority 44:78:3E:94:4A:3E = -1
09-16 08:31:02.725  5477  5477 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-16 08:31:02.726  5715  5732 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 08:31:02.975  5715  5738 W bt_btif : new conn_srvc id:26, app_id:1
09-16 08:31:02.975  5715  5738 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
,09-16 08:31:02.975  5715  5738 W bt_btif : bta_dm_pm_ssr:2, lat:1200
,09-16 08:31:02.979  5715  5715 D BtGatt.ScanManager: awakened up at time 487082
09-16 08:31:02.980  5423  5836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> 44:78:3E:94:4A:3E 5] (thread ID: 196)
09-16 08:31:02.980  5423  5836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 196)
09-16 08:31:02.981  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 08:31:02.983  5423  5836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 198)
,09-16 08:31:02.990  5423  5836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 198)
,09-16 08:31:02.990  5423  5836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 196)
09-16 08:31:02.991  5423  5842 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 198)
,09-16 08:31:03.013  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 08:31:03.013  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:03.026  5715  5731 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: A8:81:95:E9:5F:6F newState: 1
,09-16 08:31:03.027  5715  5731 I bt_btif_dm: check_cod remote_cod = 0x00001f00 cod = 0x00000580
,09-16 08:31:03.029  5715  5732 I BluetoothBondStateMachine: Bond State Change Intent:A8:81:95:E9:5F:6F OldState: 10 NewState: 11
09-16 08:31:03.029  5715  5732 I BluetoothBondStateMachine: Entering PendingCommandState State
,09-16 08:31:03.031  5477  5477 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
,09-16 08:31:03.036  5477  5477 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
09-16 08:31:03.037  3064  3311 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
,09-16 08:31:03.042  3064  3311 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 08:31:03.078  5423  5842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 198)
,09-16 08:31:03.080  5423  5842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> 44:78:3E:94:4A:3E]
,09-16 08:31:03.080  5423  5842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> 44:78:3E:94:4A:3E] (thread ID: 196)
09-16 08:31:03.080  5423  5842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> 44:78:3E:94:4A:3E] (thread ID: 196)
09-16 08:31:03.081  5423  5842 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 198)
09-16 08:31:03.081  5423  5423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-16 08:31:03.082  5423  5423 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> 44:78:3E:94:4A:3E]
,09-16 08:31:03.084  5423  5423 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,09-16 08:31:03.085  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 2 -> 0
09-16 08:31:03.085  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 3 -> 1
09-16 08:31:03.085  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 2 -> 0
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-16 08:31:03.086  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
09-16 08:31:03.086  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:31:03.087  5423  5423 D BluetoothAdapter: STATE_ON
,09-16 08:31:03.093  5715  5755 D BtGatt.GattService: stopScan() - queue size =1
,09-16 08:31:03.096  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-16 08:31:03.096  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:03.098  5715  5745 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 08:31:03.099  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 08:31:03.099  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 08:31:03.099  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,09-16 08:31:03.099  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 08:31:03.099  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 08:31:03.099  5423  5423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 08:31:03.100  5715  5734 D BtGatt.ScanManager: stopping BLe Batch
,09-16 08:31:03.102  5423  5423 D BluetoothAdapter: STATE_ON
09-16 08:31:03.103  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 08:31:03.103  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:31:03.103  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 08:31:03.106  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:03.106  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:31:03.107  5715  5755 D BtGatt.GattService: registerClient() - UUID=2bfd8e84-18b2-4284-a92e-770f487aab05
,09-16 08:31:03.107  5715  5731 D BtGatt.GattService: onClientRegistered() - UUID=2bfd8e84-18b2-4284-a92e-770f487aab05, clientIf=5
09-16 08:31:03.108  5423  5433 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 08:31:03.109  5715  5745 D BtGatt.GattService: start scan with filters
,09-16 08:31:03.112  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 08:31:03.112  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-16 08:31:03.112  5715  5734 D BtGatt.ScanManager: handling starting scan
09-16 08:31:03.113  5423  5423 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> 44:78:3E:94:4A:3E], created successfully
09-16 08:31:03.113  5423  5423 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,09-16 08:31:03.113  5423  5843 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 199)
09-16 08:31:03.114  5423  5843 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41651
,09-16 08:31:03.114  5423  5843 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-16 08:31:03.114  5423  5843 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 41651 (peer ID: 44:78:3E:94:4A:3E)
09-16 08:31:03.114  5423  5843 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "44:78:3E:94:4A:3E" removed
09-16 08:31:03.115  5715  5731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 08:31:03.115  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:03.117  5423  5469 I jxcore-log: DEBUG createPeerListener: forward connection
09-16 08:31:03.117  5423  5469 I jxcore-log: 
09-16 08:31:03.118  5715  5734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 08:31:03.119  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 08:31:03.119  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:31:03.119  5715  5734 D BtGatt.ScanManager: Starting BLE batch scan
09-16 08:31:03.120  5715  5734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 08:31:03.121  5423  5843 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 41651
09-16 08:31:03.121  5423  5843 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-16 08:31:03.121  5423  5843 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:31:03.121  5423  5843 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:31:03.122  5423  5844 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: OutgoingSocketThread/Sender)
09-16 08:31:03.123  5423  5843 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 199)
09-16 08:31:03.123  5423  5843 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 199)
,09-16 08:31:03.123  5423  5845 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: OutgoingSocketThread/Receiver)
,09-16 08:31:03.129  5715  5731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 08:31:03.129  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:03.131  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 08:31:03.131  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:03.307  5715  5731 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: A8:81:95:E9:5F:6F newState: 0
,09-16 08:31:03.307  5715  5732 D BluetoothAdapterProperties: Failed to remove device: A8:81:95:E9:5F:6F
,09-16 08:31:03.311  5715  5732 I BluetoothBondStateMachine: Bond State Change Intent:A8:81:95:E9:5F:6F OldState: 11 NewState: 10
09-16 08:31:03.313  3064  3311 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
,09-16 08:31:03.313  5477  5477 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
09-16 08:31:03.317  5715  5732 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@21fb3a6
09-16 08:31:03.317  3064  3311 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 08:31:03.318  5477  5477 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 08:31:03.324  5715  5732 D HidService: Saved priority A8:81:95:E9:5F:6F = -1
,09-16 08:31:03.333  5715  5732 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 08:31:03.394  5715  5738 W bt_smp  : for SMP over BR max_key_size: 0x10,                        local_i_key: 0x07, local_r_key: 0x07
,09-16 08:31:03.469  5715  5731 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: A8:81:95:E9:5F:6F newState: 1
09-16 08:31:03.469  5715  5738 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
,09-16 08:31:03.469  5715  5738 W bt_smp  : flag = 0 round = 1
09-16 08:31:03.470  5715  5738 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
09-16 08:31:03.470  5715  5738 W bt_smp  : flag = 0 round = 1
09-16 08:31:03.470  5715  5738 W bt_smp  : smp_send_id_info
,09-16 08:31:03.472  5715  5732 I BluetoothBondStateMachine: Bond State Change Intent:A8:81:95:E9:5F:6F OldState: 10 NewState: 11
,09-16 08:31:03.472  5715  5732 I BluetoothBondStateMachine: Entering PendingCommandState State
,09-16 08:31:03.474  3064  3311 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
,09-16 08:31:03.478  5477  5477 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
,09-16 08:31:03.480  3064  3311 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 08:31:03.485  5477  5477 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 08:31:03.506  5715  5731 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: A8:81:95:E9:5F:6F newState: 0
,09-16 08:31:03.506  5715  5732 D BluetoothAdapterProperties: Failed to remove device: A8:81:95:E9:5F:6F
,09-16 08:31:03.508  5715  5732 I BluetoothBondStateMachine: Bond State Change Intent:A8:81:95:E9:5F:6F OldState: 11 NewState: 10
,09-16 08:31:03.509  3064  3311 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
,09-16 08:31:03.510  5715  5732 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@21fb3a6
,09-16 08:31:03.511  5715  5732 D HidService: Saved priority A8:81:95:E9:5F:6F = -1
09-16 08:31:03.511  3064  3311 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
09-16 08:31:03.512  5477  5477 W BluetoothEventManager: CachedBluetoothDevice for device A8:81:95:E9:5F:6F not found, calling readPairedDevices().
09-16 08:31:03.513  5715  5732 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 08:31:03.515  5477  5477 E BluetoothEventManager: Got bonding state changed for A8:81:95:E9:5F:6F, but we have no record of that device.
,09-16 08:31:03.628  5715  5738 W bt_btif : new conn_srvc id:26, app_id:1
,09-16 08:31:03.628  5715  5738 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
09-16 08:31:03.628  5715  5738 W bt_btif : bta_dm_pm_ssr:2, lat:1200
09-16 08:31:03.629  5423  5837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> A8:81:95:E9:5F:6F 5] (thread ID: 197)
09-16 08:31:03.629  5423  5837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 197)
,09-16 08:31:03.631  5423  5837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 202)
,09-16 08:31:03.631  5423  5837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 202)
09-16 08:31:03.631  5423  5837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 197)
09-16 08:31:03.632  5423  5849 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 202)
09-16 08:31:03.634  5715  5715 D BtGatt.ScanManager: awakened up at time 487738
09-16 08:31:03.636  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:03.639  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 08:31:03.640  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:03.972  5423  5849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 202)
,09-16 08:31:03.975  5423  5849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> A8:81:95:E9:5F:6F]
,09-16 08:31:03.975  5423  5849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> A8:81:95:E9:5F:6F] (thread ID: 197)
,09-16 08:31:03.975  5423  5849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> A8:81:95:E9:5F:6F] (thread ID: 197)
,09-16 08:31:03.976  5423  5423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> A8:81:95:E9:5F:6F]
09-16 08:31:03.977  5423  5423 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> A8:81:95:E9:5F:6F]
,09-16 08:31:03.978  5423  5423 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> A8:81:95:E9:5F:6F], created successfully
,09-16 08:31:03.978  5423  5849 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 202)
09-16 08:31:03.978  5423  5423 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
09-16 08:31:03.979  5423  5850 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 203)
09-16 08:31:03.981  5423  5850 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42789
09-16 08:31:03.981  5423  5850 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-16 08:31:03.981  5423  5850 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 42789 (peer ID: A8:81:95:E9:5F:6F)
09-16 08:31:03.981  5423  5850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "A8:81:95:E9:5F:6F" removed
,09-16 08:31:03.988  5423  5469 I jxcore-log: DEBUG createPeerListener: forward connection
09-16 08:31:03.988  5423  5469 I jxcore-log: 
,09-16 08:31:03.994  5423  5850 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 42789
,09-16 08:31:03.995  5423  5850 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-16 08:31:03.995  5423  5850 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 08:31:03.996  5423  5850 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:31:03.997  5423  5850 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 203)
09-16 08:31:03.997  5423  5850 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 203)
,09-16 08:31:03.999  5423  5852 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 205, name: OutgoingSocketThread/Receiver)
09-16 08:31:04.000  5423  5851 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 204, name: OutgoingSocketThread/Sender)
,09-16 08:31:04.089  5423  5469 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:AndroidBluetooth, 127.0.0.1, 127.0.0.1, 47189
09-16 08:31:04.089  5423  5469 I jxcore-log: 
,09-16 08:31:04.131  5715  5738 W bt_btif : new conn_srvc id:26, app_id:255
,09-16 08:31:04.131  5715  5738 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
,09-16 08:31:04.131  5715  5738 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
09-16 08:31:04.131  5715  5738 W bt_btif : bta_dm_pm_ssr:2, lat:1200
09-16 08:31:04.132  5423  5835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
09-16 08:31:04.133  5423  5835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 206)
,09-16 08:31:04.133  5423  5835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 08:31:04.134  5423  5853 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 206)
09-16 08:31:04.134  5423  5835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 08:31:04.133  5755  5755 W Binder_5: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[31605]" dev="sockfs" ino=31605 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 08:31:04.137  5423  5835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-16 08:31:04.133  5755  5755 W Binder_5: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[31605]" dev="sockfs" ino=31605 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 08:31:04.142  5715  5715 D BtGatt.ScanManager: awakened up at time 488246
,09-16 08:31:04.143  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:04.144  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:04.144  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:04.648  5715  5715 D BtGatt.ScanManager: awakened up at time 488751
,09-16 08:31:04.650  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:04.652  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 08:31:04.652  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:04.677  5423  5853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 206)
,09-16 08:31:04.679  5423  5853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> 44:78:3E:94:4A:3E]
,09-16 08:31:04.680  5423  5853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 206)
09-16 08:31:04.680  5423  5853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 206
09-16 08:31:04.680  5423  5853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 206)
09-16 08:31:04.680  5423  5853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-16 08:31:04.681  5423  5853 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 206)
,09-16 08:31:04.681  5423  5423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-16 08:31:04.681  5423  5423 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> 44:78:3E:94:4A:3E]
09-16 08:31:04.684  5423  5423 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> 44:78:3E:94:4A:3E], created successfully
,09-16 08:31:04.684  5423  5854 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 207)
09-16 08:31:04.685  5423  5423 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
,09-16 08:31:04.691  5423  5854 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 37819
,09-16 08:31:04.691  5423  5854 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-16 08:31:04.691  5423  5854 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:31:04.692  5423  5854 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 08:31:04.694  5423  5856 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 208, name: IncomingSocketThread/Sender)
09-16 08:31:04.694  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:31:04.694  5423  5469 I jxcore-log: 
09-16 08:31:04.694  5423  5854 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 207)
09-16 08:31:04.694  5423  5854 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 207)
,09-16 08:31:04.698  5423  5857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 209, name: IncomingSocketThread/Receiver)
,09-16 08:31:04.702  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:31:04.702  5423  5469 I jxcore-log: 
,09-16 08:31:04.713  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:31:04.713  5423  5469 I jxcore-log: 
,09-16 08:31:05.041  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:31:05.041  5423  5469 I jxcore-log: 
,09-16 08:31:05.046  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:31:05.046  5423  5469 I jxcore-log: 
,09-16 08:31:05.157  5715  5715 D BtGatt.ScanManager: awakened up at time 489260
,09-16 08:31:05.159  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:05.163  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:05.163  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:05.500   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:05.563  5423  5469 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:AndroidBluetooth, 127.0.0.1, 127.0.0.1, 39140
09-16 08:31:05.563  5423  5469 I jxcore-log: 
,09-16 08:31:05.668  5715  5715 D BtGatt.ScanManager: awakened up at time 489772
,09-16 08:31:05.670  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:05.675  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:05.675  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:05.697  5423  5835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,09-16 08:31:05.697  5423  5835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 210)
09-16 08:31:05.698  5423  5835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-16 08:31:05.698  5423  5858 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 210)
09-16 08:31:05.699  5423  5835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 08:31:05.700  5715  5738 W bt_btif : new conn_srvc id:26, app_id:255
09-16 08:31:05.700  5715  5738 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
,09-16 08:31:05.700  5715  5738 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
09-16 08:31:05.700  5715  5738 W bt_btif : bta_dm_pm_ssr:2, lat:1200
,09-16 08:31:05.696  5755  5755 W Binder_5: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[32735]" dev="sockfs" ino=32735 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 08:31:05.696  5755  5755 W Binder_5: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[32735]" dev="sockfs" ino=32735 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 08:31:05.704  5423  5835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-16 08:31:05.998  5423  5858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 210)
09-16 08:31:06.000  5423  5858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> A8:81:95:E9:5F:6F]
,09-16 08:31:06.001  5423  5858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 210)
,09-16 08:31:06.002  5423  5858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 210
09-16 08:31:06.002  5423  5858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 210)
,09-16 08:31:06.002  5423  5858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> A8:81:95:E9:5F:6F]
,09-16 08:31:06.002  5423  5858 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 210)
,09-16 08:31:06.003  5423  5423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> A8:81:95:E9:5F:6F]
09-16 08:31:06.003  5423  5423 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> A8:81:95:E9:5F:6F]
09-16 08:31:06.005  5423  5423 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> A8:81:95:E9:5F:6F], created successfully
09-16 08:31:06.006  5423  5423 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 4
09-16 08:31:06.007  5423  5859 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 211)
09-16 08:31:06.011  5423  5859 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 37819
09-16 08:31:06.011  5423  5859 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-16 08:31:06.012  5423  5859 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:31:06.013  5423  5859 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 08:31:06.013  5423  5860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 212, name: IncomingSocketThread/Sender)
,09-16 08:31:06.016  5423  5859 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 211)
09-16 08:31:06.016  5423  5859 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 211)
09-16 08:31:06.017  5423  5861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 213, name: IncomingSocketThread/Receiver)
,09-16 08:31:06.039  5423  5469 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 08:31:06.039  5423  5469 I jxcore-log: 
,09-16 08:31:06.040  5423  5469 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 08:31:06.040  5423  5469 I jxcore-log: 
,09-16 08:31:06.041  5423  5469 I jxcore-log: DEBUG createNativeListener: new mux
09-16 08:31:06.041  5423  5469 I jxcore-log: 
,09-16 08:31:06.182  5715  5715 D BtGatt.ScanManager: awakened up at time 490285
,09-16 08:31:06.184  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:06.187  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:06.188  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:06.349  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:31:06.349  5423  5469 I jxcore-log: 
,09-16 08:31:06.356  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:31:06.356  5423  5469 I jxcore-log: 
,09-16 08:31:06.371  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:31:06.371  5423  5469 I jxcore-log: 
,09-16 08:31:06.375  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:31:06.375  5423  5469 I jxcore-log: 
,09-16 08:31:06.380  5423  5469 I jxcore-log: DEBUG createNativeListener: 
09-16 08:31:06.380  5423  5469 I jxcore-log: 
,09-16 08:31:06.381  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:31:06.381  5423  5469 I jxcore-log: 
,09-16 08:31:06.501   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:06.692  5715  5715 D BtGatt.ScanManager: awakened up at time 490796
,09-16 08:31:06.695  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:06.712  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 08:31:06.713  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:06.976  5423  5469 I jxcore-log: DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
09-16 08:31:06.976  5423  5469 I jxcore-log: 
,09-16 08:31:07.041  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:31:07.041  5423  5469 I jxcore-log: 
,09-16 08:31:07.217  5715  5715 D BtGatt.ScanManager: awakened up at time 491320
,09-16 08:31:07.219  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:07.236  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:07.237  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:07.409  5423  5469 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 08:31:07.409  5423  5469 I jxcore-log: 
,09-16 08:31:07.418  5423  5469 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 08:31:07.418  5423  5469 I jxcore-log: 
,09-16 08:31:07.449  5423  5469 I jxcore-log: DEBUG createNativeListener: 
09-16 08:31:07.449  5423  5469 I jxcore-log: 
,09-16 08:31:07.452  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:31:07.452  5423  5469 I jxcore-log: 
,09-16 08:31:07.501   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:07.743  5715  5715 D BtGatt.ScanManager: awakened up at time 491846
09-16 08:31:07.744  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:07.761  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 08:31:07.761  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:07.991  5423  5469 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 08:31:07.991  5423  5469 I jxcore-log: 
,09-16 08:31:08.267  5715  5715 D BtGatt.ScanManager: awakened up at time 492371
,09-16 08:31:08.270  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:08.273  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:08.274  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:08.502   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:09.504   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:09.861  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 08:31:09.862  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-16 08:31:09.862  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-16 08:31:09.862  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
09-16 08:31:09.862  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 08:31:09.863  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 08:31:09.866  5423  5469 D BluetoothAdapter: STATE_ON
09-16 08:31:09.867  5715  5725 D BtGatt.GattService: stopScan() - queue size =1
,09-16 08:31:09.872  5715  5742 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 08:31:09.873  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 08:31:09.873  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 08:31:09.873  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 08:31:09.874  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 08:31:09.874  5423  5469 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 08:31:09.875  5715  5731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 08:31:09.875  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:31:09.875  5715  5734 D BtGatt.ScanManager: stopping BLe Batch
09-16 08:31:09.877  5423  5469 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 08:31:09.878  5423  5423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 08:31:09.879  5715  5731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 08:31:09.879  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 08:31:09.880  5715  5734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 08:31:09.882  5715  5731 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 08:31:09.883  5715  5731 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 08:31:10.379  5423  5423 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 08:31:10.380  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:31:10.380  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 08:31:10.384  5423  5469 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 08:31:10.384  5423  5469 I jxcore-log: 
,09-16 08:31:10.399  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 08:31:10.399  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 08:31:10.399  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 44:78:3E:94:4A:3E]
09-16 08:31:10.399  5423  5469 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 199)
,09-16 08:31:10.400  5423  5469 V io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
09-16 08:31:10.400  5423  5469 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 201
09-16 08:31:10.400  5423  5469 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 201, name: OutgoingSocketThread/Receiver)
09-16 08:31:10.400  5423  5845 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
,09-16 08:31:10.401  5423  5469 V io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
,09-16 08:31:10.401  5423  5469 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 200
09-16 08:31:10.401  5423  5469 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 200, name: OutgoingSocketThread/Sender)
,09-16 08:31:10.401  5423  5469 V io.jxcore.node.OutgoingSocketThread: close: Closing the Bluetooth socket...
09-16 08:31:10.401  5423  5469 V io.jxcore.node.OutgoingSocketThread: close: Closing the localhost socket...
,09-16 08:31:10.401  5423  5844 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: OutgoingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 907 and the total number of bytes written 907
09-16 08:31:10.401  5423  5469 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 199)
09-16 08:31:10.401  5423  5469 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> A8:81:95:E9:5F:6F]
09-16 08:31:10.402  5423  5469 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 203)
,09-16 08:31:10.402  5423  5469 V io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
09-16 08:31:10.402  5423  5469 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 205
09-16 08:31:10.402  5423  5469 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 205, name: OutgoingSocketThread/Receiver)
09-16 08:31:10.402  5423  5469 V io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
09-16 08:31:10.404  5423  5851 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 204, thread name: OutgoingSocketThread/Sender): Socket closed
09-16 08:31:10.404  5423  5852 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 205, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
,09-16 08:31:10.405  5423  5851 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 204, name: OutgoingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 903 and the total number of bytes written 903
09-16 08:31:10.402  5423  5469 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 204
09-16 08:31:10.405  5423  5469 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 204, name: OutgoingSocketThread/Sender)
09-16 08:31:10.406  5423  5469 V io.jxcore.node.OutgoingSocketThread: close: Closing the Bluetooth socket...
09-16 08:31:10.406  5423  5469 V io.jxcore.node.OutgoingSocketThread: close: Closing the localhost socket...
09-16 08:31:10.406  5423  5469 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 203)
09-16 08:31:10.406  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 08:31:10.406  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 08:31:10.407  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 08:31:10.407  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 08:31:10.407  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-16 08:31:10.407  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-16 08:31:10.407  5423  5469 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 08:31:10.408  5423  5469 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 08:31:10.408  5423  5469 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 08:31:10.408  5423  5423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 08:31:10.408  5423  5835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-16 08:31:10.408  5423  5835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 08:31:10.408  5423  5835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 08:31:10.409  5423  5469 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 08:31:10.410  5423  5469 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-16 08:31:10.411  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:31:10.412  5423  5423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:31:10.412  5423  5423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-16 08:31:10.412  5423  5423 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-16 08:31:10.424  5423  5469 I jxcore-log: DEBUG createPeerListener: Recreating listener
09-16 08:31:10.424  5423  5469 I jxcore-log: 
,09-16 08:31:10.425  5423  5469 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-16 08:31:10.425  5423  5469 I jxcore-log: 
,09-16 08:31:10.428  5423  5469 I jxcore-log: DEBUG createPeerListener: listening 39368
09-16 08:31:10.428  5423  5469 I jxcore-log: 
,09-16 08:31:10.429  5423  5469 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-16 08:31:10.429  5423  5469 I jxcore-log: 
,09-16 08:31:10.433  5423  5469 I jxcore-log: DEBUG createPeerListener: Recreating listener
09-16 08:31:10.433  5423  5469 I jxcore-log: 
,09-16 08:31:10.434  5423  5469 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-16 08:31:10.434  5423  5469 I jxcore-log: 
,09-16 08:31:10.436  5423  5469 I jxcore-log: DEBUG createPeerListener: listening 48907
09-16 08:31:10.436  5423  5469 I jxcore-log: 
,09-16 08:31:10.437  5423  5469 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-16 08:31:10.437  5423  5469 I jxcore-log: 
09-16 08:31:10.439  5423  5469 I jxcore-log: ok 153 Peer made successful https requests to all peers
09-16 08:31:10.439  5423  5469 I jxcore-log: 
,09-16 08:31:10.441  5423  5469 I jxcore-log: ok 154 Peer received right amount of https requests
09-16 08:31:10.441  5423  5469 I jxcore-log: 
09-16 08:31:10.441  5423  5469 I jxcore-log: ok 155 HTTPS server received zero PSK Identities. Count:0
09-16 08:31:10.441  5423  5469 I jxcore-log: 
,09-16 08:31:10.448  5423  5469 I jxcore-log: # teardown
09-16 08:31:10.448  5423  5469 I jxcore-log: 
,09-16 08:31:10.476  5715  5738 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,09-16 08:31:10.477  5715  5738 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
,09-16 08:31:10.482  5715  5738 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
09-16 08:31:10.482  5715  5738 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
,09-16 08:31:10.504   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:31:11.180  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from ACTIVE to SNIFF.
,09-16 08:31:11.188  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:31:25.505   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:26.507   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:27.508   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:28.510   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:29.511   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:30.512   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:31:39.701  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-16 08:31:39.701  5423  5469 I jxcore-log: 
,09-16 08:31:39.702  5423  5856 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 208, thread name: IncomingSocketThread/Sender)
09-16 08:31:39.702  5423  5856 I io.jxcore.node.IncomingSocketThread: The sending thread is done
09-16 08:31:39.702  5423  5856 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 208, name: IncomingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
,09-16 08:31:39.709  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:31:39.709  5423  5469 I jxcore-log: 
,09-16 08:31:39.714  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-16 08:31:39.714  5423  5469 I jxcore-log: 
09-16 08:31:39.716  5423  5860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 212, thread name: IncomingSocketThread/Sender)
,09-16 08:31:39.716  5423  5860 I io.jxcore.node.IncomingSocketThread: The sending thread is done
09-16 08:31:39.717  5423  5860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 212, name: IncomingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
,09-16 08:31:39.720  5423  5469 I jxcore-log: DEBUG createNativeListener: mux close
09-16 08:31:39.720  5423  5469 I jxcore-log: 
,09-16 08:31:39.725  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:31:39.725  5423  5469 I jxcore-log: 
,09-16 08:31:39.726  5423  5469 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 08:31:39.726  5423  5469 I jxcore-log: 
,09-16 08:31:39.977   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:31:50.513   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:51.515   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:52.516   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:53.517   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:54.519   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:31:55.520   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:31:59.980   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:32:04.054  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 08:32:04.058  5423  5423 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,09-16 08:32:04.085  5423  5857 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 209, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
,09-16 08:32:04.085  5423  5857 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
09-16 08:32:04.086  5423  5857 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> 44:78:3E:94:4A:3E] disconnected: Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)
,09-16 08:32:04.086  5423  5857 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 207
09-16 08:32:04.086  5423  5857 V io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
09-16 08:32:04.086  5423  5857 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 209
09-16 08:32:04.086  5423  5857 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 209, name: IncomingSocketThread/Receiver)
09-16 08:32:04.087  5423  5857 V io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
09-16 08:32:04.087  5423  5857 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 208
09-16 08:32:04.087  5423  5857 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 208, name: IncomingSocketThread/Sender)
,09-16 08:32:04.087  5423  5857 V io.jxcore.node.IncomingSocketThread: close: Closing the Bluetooth socket...
,09-16 08:32:04.087  5423  5857 V io.jxcore.node.IncomingSocketThread: close: Closing the localhost socket...
09-16 08:32:04.087  5423  5857 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 207)
09-16 08:32:04.087  5423  5857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 08:32:04.087  5423  5857 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 209, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 907 and the total number of bytes written 905
,09-16 08:32:04.101  5715  5738 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
,09-16 08:32:04.113  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:32:04.113  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-16 08:32:04.123  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:32:05.064  5715  5738 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,09-16 08:32:05.064  5715  5738 E bt_btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
09-16 08:32:05.065  5715  5738 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
,09-16 08:32:05.079  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 08:32:05.080  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 08:32:09.126  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from ACTIVE to SNIFF.
,09-16 08:32:09.126  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 08:32:10.045  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-16 08:32:11.082  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:32:11.098  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:32:12.669  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 08:32:12.679  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 08:32:15.093  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from ACTIVE to SNIFF.
,09-16 08:32:17.691  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:32:17.708  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:32:18.018  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 08:32:18.568  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-16 08:32:19.129  5423  5423 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,09-16 08:32:19.129  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 0 -> 2
09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 1 -> 3
,09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 0 -> 2
,09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-16 08:32:19.130  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-16 08:32:19.131  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 08:32:19.131  5423  5423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 08:32:19.131  5423  5423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 08:32:20.521   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:32:20.521   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:32:24.557  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:32:24.587  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:32:24.785   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:32:26.014  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 08:32:26.023  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 08:32:27.815   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:32:32.106  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:32:32.126  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:32:32.482  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 08:32:32.524  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 08:32:34.566  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 08:32:34.568  5423  5861 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 213, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
,09-16 08:32:34.568  5423  5861 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
,09-16 08:32:34.568  5423  5861 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> A8:81:95:E9:5F:6F] disconnected: Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)
09-16 08:32:34.568  5423  5861 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 211
09-16 08:32:34.569  5423  5861 V io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
09-16 08:32:34.569  5423  5861 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 213
,09-16 08:32:34.571  5423  5861 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 213, name: IncomingSocketThread/Receiver)
,09-16 08:32:34.571  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
09-16 08:32:34.571  5423  5861 V io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
09-16 08:32:34.572  5423  5861 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 212
,09-16 08:32:34.572  5423  5861 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 212, name: IncomingSocketThread/Sender)
09-16 08:32:34.572  5423  5861 V io.jxcore.node.IncomingSocketThread: close: Closing the Bluetooth socket...
09-16 08:32:34.572  5423  5861 V io.jxcore.node.IncomingSocketThread: close: Closing the localhost socket...
09-16 08:32:34.572  5423  5861 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 211)
,09-16 08:32:34.573  5423  5861 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-16 08:32:34.573  5423  5861 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 213, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 1025 and the total number of bytes written 1023
,09-16 08:32:34.654  5715  5738 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
09-16 08:32:34.654  5715  5738 E bt_btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
09-16 08:32:34.654  5715  5738 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
,09-16 08:32:36.906   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:32:37.544  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:32:37.562  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:32:38.512  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
09-16 08:32:38.512  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 08:32:39.929   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:32:39.982   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:32:42.966   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:32:44.620  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:32:44.689  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:32:44.950  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 08:32:45.506  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-16 08:32:45.533   534  1489 E QC-QMI  : qmi_client [534] a: failed to locate client data
,09-16 08:32:45.537   518   518 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-16 08:32:45.537   518   518 E QC-QMI  : QMUX qmux_client_id=a not found in qmux client list, unable to remove
09-16 08:32:45.539   534   534 I Atfwd_Daemon: Stop the daemon....
,09-16 08:32:45.658  5864  5864 I libmdmdetect: ESOC framework not supported
,09-16 08:32:45.658  5864  5864 I libmdmdetect: Found internal modem: modem
09-16 08:32:45.660  5864  5864 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-16 08:32:45.656  5864  5864 W ATFWD-daemon: type=1400 audit(0.0:132): avc: denied { read write } for name="diag" dev="tmpfs" ino=10945 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-16 08:32:45.665  5864  5864 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
09-16 08:32:45.665  5864  5864 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-16 08:32:45.666  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:45.990   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:32:46.670  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:47.671  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:48.672  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:49.023   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:32:49.674  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:50.675  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:32:51.499  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:32:51.533  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:32:52.064   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:32:53.432  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-16 08:32:53.931  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-16 08:32:55.676  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:56.677  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:57.678  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:58.680  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:59.681  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:32:59.985   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:33:00.133  5715  5738 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-16 08:33:00.256  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-16 08:33:00.675  5423  5469 I jxcore-log: INFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
09-16 08:33:00.675  5423  5469 I jxcore-log: 
,09-16 08:33:00.682  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:33:00.688  5423  5469 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 08:33:00.688  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 08:33:00.688  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 08:33:00.689  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:33:00.695  5423  5469 I jxcore-log: # setup
09-16 08:33:00.695  5423  5469 I jxcore-log: 
,09-16 08:33:00.698  5423  5469 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 08:33:00.698  5423  5469 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-16 08:33:00.699  5423  5469 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 08:33:00.699  5423  5469 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 08:33:00.907  5423  5469 I jxcore-log: # 39. Test BEACONS_RETRIEVED_AND_PARSED locally
09-16 08:33:00.907  5423  5469 I jxcore-log: 
,09-16 08:33:01.137  5423  5469 I jxcore-log: ok 156 peerIdentifier should be identifier
09-16 08:33:01.137  5423  5469 I jxcore-log: 
09-16 08:33:01.138  5423  5469 I jxcore-log: ok 157 Response should be BEACONS_RETRIEVED_AND_PARSED
09-16 08:33:01.138  5423  5469 I jxcore-log: 
,09-16 08:33:01.139  5423  5469 I jxcore-log: ok 158 good beacon
09-16 08:33:01.139  5423  5469 I jxcore-log: 
09-16 08:33:01.139  5423  5469 I jxcore-log: ok 159 good preAmble
09-16 08:33:01.139  5423  5469 I jxcore-log: 
09-16 08:33:01.139  5423  5469 I jxcore-log: ok 160 public keys match!
09-16 08:33:01.139  5423  5469 I jxcore-log: 
,09-16 08:33:01.142  5423  5469 I jxcore-log: ok 161 must return null after successful call
09-16 08:33:01.142  5423  5469 I jxcore-log: 
09-16 08:33:01.142  5423  5469 I jxcore-log: ok 162 Once start returns the action should be in KILLED state
09-16 08:33:01.142  5423  5469 I jxcore-log: 
,09-16 08:33:01.152  5423  5469 I jxcore-log: # teardown
09-16 08:33:01.152  5423  5469 I jxcore-log: 
,09-16 08:33:01.219  5423  5469 I jxcore-log: # setup
09-16 08:33:01.219  5423  5469 I jxcore-log: 
,09-16 08:33:01.403  5423  5469 I jxcore-log: # 40. Test HTTP_BAD_RESPONSE locally
09-16 08:33:01.403  5423  5469 I jxcore-log: 
,09-16 08:33:01.530  5423  5469 I jxcore-log: ok 163 Response should be HTTP_BAD_RESPONSE
09-16 08:33:01.530  5423  5469 I jxcore-log: 
09-16 08:33:01.532  5423  5469 I jxcore-log: ok 164 must return null after successful call
09-16 08:33:01.532  5423  5469 I jxcore-log: 
,09-16 08:33:01.544  5423  5469 I jxcore-log: # teardown
09-16 08:33:01.544  5423  5469 I jxcore-log: 
,09-16 08:33:01.639  5423  5469 I jxcore-log: # setup
09-16 08:33:01.639  5423  5469 I jxcore-log: 
,09-16 08:33:01.816  5423  5469 I jxcore-log: # 41. Test NETWORK_PROBLEM locally
09-16 08:33:01.816  5423  5469 I jxcore-log: 
,09-16 08:33:02.027  5423  5469 I jxcore-log: ok 165 Response should be NETWORK_PROBLEM
09-16 08:33:02.027  5423  5469 I jxcore-log: 
,09-16 08:33:02.035  5423  5469 I jxcore-log: ok 166 reject reason should be: Could not establish TCP connection
09-16 08:33:02.035  5423  5469 I jxcore-log: 
,09-16 08:33:02.045  5423  5469 I jxcore-log: # teardown
09-16 08:33:02.045  5423  5469 I jxcore-log: 
,09-16 08:33:02.078  5423  5469 I jxcore-log: # setup
09-16 08:33:02.078  5423  5469 I jxcore-log: 
,09-16 08:33:02.284  5423  5469 I jxcore-log: # 42. Call the start two times
09-16 08:33:02.284  5423  5469 I jxcore-log: 
,09-16 08:33:02.343  5423  5469 I jxcore-log: ok 167 Call start once
09-16 08:33:02.343  5423  5469 I jxcore-log: 
,09-16 08:33:02.460  5423  5469 I jxcore-log: ok 168 Response should be BEACONS_RETRIEVED_AND_PARSED
09-16 08:33:02.460  5423  5469 I jxcore-log: 
,09-16 08:33:02.462  5423  5469 I jxcore-log: ok 169 must return null after successful call.
09-16 08:33:02.462  5423  5469 I jxcore-log: 
,09-16 08:33:02.482  5423  5469 I jxcore-log: # teardown
09-16 08:33:02.482  5423  5469 I jxcore-log: 
,09-16 08:33:02.553  5423  5469 I jxcore-log: # setup
09-16 08:33:02.553  5423  5469 I jxcore-log: 
,09-16 08:33:02.794  5423  5469 I jxcore-log: # 43. Call the kill before calling the start
09-16 08:33:02.794  5423  5469 I jxcore-log: 
,09-16 08:33:02.844  5423  5469 I jxcore-log: ok 170 Should be Killed
09-16 08:33:02.844  5423  5469 I jxcore-log: 
,09-16 08:33:02.849  5423  5469 I jxcore-log: ok 171 Start after killed
09-16 08:33:02.849  5423  5469 I jxcore-log: 
,09-16 08:33:02.857  5423  5469 I jxcore-log: # teardown
09-16 08:33:02.857  5423  5469 I jxcore-log: 
,09-16 08:33:02.975  5423  5469 I jxcore-log: # setup
09-16 08:33:02.975  5423  5469 I jxcore-log: 
,09-16 08:33:03.160  5423  5469 I jxcore-log: # 44. Call the kill immediately after the start
09-16 08:33:03.160  5423  5469 I jxcore-log: 
,09-16 08:33:03.204  5423  5469 I jxcore-log: ok 172 Should be KILLED
09-16 08:33:03.204  5423  5469 I jxcore-log: 
,09-16 08:33:03.206  5423  5469 I jxcore-log: ok 173 must return null after successful kill
09-16 08:33:03.206  5423  5469 I jxcore-log: 
,09-16 08:33:03.212  5423  5469 I jxcore-log: # teardown
09-16 08:33:03.212  5423  5469 I jxcore-log: 
,09-16 08:33:03.333  5423  5469 I jxcore-log: # setup
09-16 08:33:03.333  5423  5469 I jxcore-log: 
,09-16 08:33:03.514  5423  5469 I jxcore-log: # 45. Call the kill while waiting a response from the server
09-16 08:33:03.514  5423  5469 I jxcore-log: 
,09-16 08:33:04.412  5715  5738 D bt_btm_pm: btm_pm_proc_mode_change switched from SNIFF to ACTIVE.
,09-16 08:33:04.447  5715  5738 I bt_btm_sec: btm_sec_disconnected clearing pending flag handle:12 reason:19
,09-16 08:33:04.450  5715  5731 E BluetoothRemoteDevices: state12newState1
,09-16 08:33:04.457  5715  5715 D BluetoothMapService: onReceive
,09-16 08:33:04.457  5715  5715 D BluetoothMapService: onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,09-16 08:33:04.476   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@47b6357:true
,09-16 08:33:04.490  4743  4743 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=A8:81:95:E9:5F:6F, alias=null, name=Samsung Galaxy S7 edge, majorDeviceClass=7936, deviceClass=7936]
,09-16 08:33:04.494  4743  4743 I BluetoothClassifier: Bluetooth Device Name: Samsung Galaxy S7 edge
,09-16 08:33:04.571  5715  5738 I bt_btm_sec: btm_sec_disconnected clearing pending flag handle:11 reason:19
,09-16 08:33:04.574  5715  5731 E BluetoothRemoteDevices: state12newState1
,09-16 08:33:04.582  5715  5715 D BluetoothMapService: onReceive
09-16 08:33:04.582  5715  5715 D BluetoothMapService: onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,09-16 08:33:04.603  4743  4743 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:78:3E:94:4A:3E, alias=null, name=Samsung Galaxy S7, majorDeviceClass=7936, deviceClass=7936]
,09-16 08:33:04.605  4743  4743 I BluetoothClassifier: Bluetooth Device Name: Samsung Galaxy S7
,09-16 08:33:05.578  5423  5469 I jxcore-log: ok 174 Should be KILLED
09-16 08:33:05.578  5423  5469 I jxcore-log: 
,09-16 08:33:05.590  5423  5469 I jxcore-log: ok 175 must return null after successful kill
09-16 08:33:05.590  5423  5469 I jxcore-log: 
,09-16 08:33:05.613  5423  5469 I jxcore-log: # teardown
09-16 08:33:05.613  5423  5469 I jxcore-log: 
,09-16 08:33:05.706  5423  5469 I jxcore-log: # setup
09-16 08:33:05.706  5423  5469 I jxcore-log: 
,09-16 08:33:05.970  5423  5469 I jxcore-log: # 46. Test to exceed the max content size locally
09-16 08:33:05.970  5423  5469 I jxcore-log: 
,09-16 08:33:06.159  5423  5469 I jxcore-log: ok 176 HTTP_BAD_RESPONSE should be response when content size is exceeded
09-16 08:33:06.159  5423  5469 I jxcore-log: 
,09-16 08:33:06.170  5423  5469 I jxcore-log: ok 177 must return null after successful call
09-16 08:33:06.170  5423  5469 I jxcore-log: 
,09-16 08:33:06.199  5423  5469 I jxcore-log: # teardown
09-16 08:33:06.199  5423  5469 I jxcore-log: 
,09-16 08:33:06.232  5423  5469 I jxcore-log: # setup
09-16 08:33:06.232  5423  5469 I jxcore-log: 
,09-16 08:33:06.402  5423  5469 I jxcore-log: # 47. Close the server socket while the client is waiting a response from the server. Local test.
09-16 08:33:06.402  5423  5469 I jxcore-log: 
,09-16 08:33:08.464  5423  5469 I jxcore-log: ok 178 Should be NETWORK_PROBLEM caused closing server socket
09-16 08:33:08.464  5423  5469 I jxcore-log: 
,09-16 08:33:08.470  5423  5469 I jxcore-log: ok 179 Should be Could not establish TCP connection
09-16 08:33:08.470  5423  5469 I jxcore-log: 
,09-16 08:33:08.479  5423  5469 I jxcore-log: # teardown
09-16 08:33:08.479  5423  5469 I jxcore-log: 
,09-16 08:33:08.558  5423  5469 I jxcore-log: # setup
09-16 08:33:08.558  5423  5469 I jxcore-log: 
,09-16 08:33:08.744  5423  5469 I jxcore-log: # 48. Close the client socket while the client is waiting a response from the server. Local test.
09-16 08:33:08.744  5423  5469 I jxcore-log: 
,09-16 08:33:10.683  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:10.828  5423  5469 I jxcore-log: ok 180 Should be NETWORK_PROBLEM caused closing client socket
09-16 08:33:10.828  5423  5469 I jxcore-log: 
,09-16 08:33:10.841  5423  5469 I jxcore-log: ok 181 Should be Could not establish TCP connection
09-16 08:33:10.841  5423  5469 I jxcore-log: 
,09-16 08:33:10.863  5423  5469 I jxcore-log: # teardown
09-16 08:33:10.863  5423  5469 I jxcore-log: 
,09-16 08:33:10.944  5423  5469 I jxcore-log: # setup
09-16 08:33:10.944  5423  5469 I jxcore-log: 
,09-16 08:33:11.004  5423  5469 I jxcore-log: # 49. #generatePreambleAndBeacons bad args
09-16 08:33:11.004  5423  5469 I jxcore-log: 
,09-16 08:33:11.091  5423  5469 I jxcore-log: ok 182 publicKeysToNotify cannot be null
09-16 08:33:11.091  5423  5469 I jxcore-log: 
,09-16 08:33:11.097  5423  5469 I jxcore-log: ok 183 ecdh for local device cannot be null
09-16 08:33:11.097  5423  5469 I jxcore-log: 
,09-16 08:33:11.100  5423  5469 I jxcore-log: ok 184 milliseconds cannot be less than 0
09-16 08:33:11.100  5423  5469 I jxcore-log: 
,09-16 08:33:11.104  5423  5469 I jxcore-log: ok 185 milliseconds cannot be 0
09-16 08:33:11.104  5423  5469 I jxcore-log: 
,09-16 08:33:11.107  5423  5469 I jxcore-log: ok 186 milliseconds cannot be greater than one_day
09-16 08:33:11.107  5423  5469 I jxcore-log: 
,09-16 08:33:11.111  5423  5469 I jxcore-log: # teardown
09-16 08:33:11.111  5423  5469 I jxcore-log: 
,09-16 08:33:11.154  5423  5469 I jxcore-log: # setup
09-16 08:33:11.154  5423  5469 I jxcore-log: 
,09-16 08:33:11.215  5423  5469 I jxcore-log: # 50. #generatePreambleAndBeacons empty keys to notify
09-16 08:33:11.215  5423  5469 I jxcore-log: 
,09-16 08:33:11.305  5423  5469 I jxcore-log: ok 187 should be equal
09-16 08:33:11.305  5423  5469 I jxcore-log: 
,09-16 08:33:11.309  5423  5469 I jxcore-log: # teardown
09-16 08:33:11.309  5423  5469 I jxcore-log: 
,09-16 08:33:11.353  5423  5469 I jxcore-log: # setup
09-16 08:33:11.353  5423  5469 I jxcore-log: 
,09-16 08:33:11.421  5423  5469 I jxcore-log: # 51. #generatePreambleAndBeacons multiple keys to notify
09-16 08:33:11.421  5423  5469 I jxcore-log: 
,09-16 08:33:11.599  5423  5469 I jxcore-log: ok 188 should be equal
09-16 08:33:11.599  5423  5469 I jxcore-log: 
,09-16 08:33:11.600  5423  5469 I jxcore-log: ok 189 should be equal
09-16 08:33:11.600  5423  5469 I jxcore-log: 
09-16 08:33:11.600  5423  5469 I jxcore-log: ok 190 (unnamed assert)
09-16 08:33:11.600  5423  5469 I jxcore-log: 
09-16 08:33:11.601  5423  5469 I jxcore-log: ok 191 should be equal
09-16 08:33:11.601  5423  5469 I jxcore-log: 
,09-16 08:33:11.602  5423  5469 I jxcore-log: # teardown
09-16 08:33:11.602  5423  5469 I jxcore-log: 
,09-16 08:33:11.640  5423  5469 I jxcore-log: # setup
09-16 08:33:11.640  5423  5469 I jxcore-log: 
,09-16 08:33:11.684  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:11.713  5423  5469 I jxcore-log: # 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
09-16 08:33:11.713  5423  5469 I jxcore-log: 
,09-16 08:33:11.801  5423  5469 I jxcore-log: ok 192 should throw
09-16 08:33:11.801  5423  5469 I jxcore-log: 
,09-16 08:33:11.805  5423  5469 I jxcore-log: # teardown
09-16 08:33:11.805  5423  5469 I jxcore-log: 
,09-16 08:33:11.845  5423  5469 I jxcore-log: # setup
09-16 08:33:11.845  5423  5469 I jxcore-log: 
,09-16 08:33:11.896  5423  5469 I jxcore-log: # 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble
09-16 08:33:11.896  5423  5469 I jxcore-log: 
,09-16 08:33:11.963  5423  5469 I jxcore-log: ok 193 Preamble expiration must be a 64 bit integer
09-16 08:33:11.963  5423  5469 I jxcore-log: 
,09-16 08:33:11.966  5423  5469 I jxcore-log: # teardown
09-16 08:33:11.966  5423  5469 I jxcore-log: 
,09-16 08:33:12.023  5423  5469 I jxcore-log: # setup
09-16 08:33:12.023  5423  5469 I jxcore-log: 
,09-16 08:33:12.103  5423  5469 I jxcore-log: # 54. #parseBeacons expiration out of range lower
09-16 08:33:12.103  5423  5469 I jxcore-log: 
,09-16 08:33:12.242  5423  5469 I jxcore-log: ok 194 Expiration out of range
09-16 08:33:12.242  5423  5469 I jxcore-log: 
,09-16 08:33:12.245  5423  5469 I jxcore-log: # teardown
09-16 08:33:12.245  5423  5469 I jxcore-log: 
,09-16 08:33:12.306  5423  5469 I jxcore-log: # setup
09-16 08:33:12.306  5423  5469 I jxcore-log: 
,09-16 08:33:12.356  5423  5469 I jxcore-log: # 55. #parseBeacons expiration out of range lower
09-16 08:33:12.356  5423  5469 I jxcore-log: 
,09-16 08:33:12.478  5423  5469 I jxcore-log: ok 195 Expiration out of range
09-16 08:33:12.478  5423  5469 I jxcore-log: 
,09-16 08:33:12.482  5423  5469 I jxcore-log: # teardown
09-16 08:33:12.482  5423  5469 I jxcore-log: 
,09-16 08:33:12.555  5423  5469 I jxcore-log: # setup
09-16 08:33:12.555  5423  5469 I jxcore-log: 
,09-16 08:33:12.635  5423  5469 I jxcore-log: # 56. #parseBeacons no beacons returns null
09-16 08:33:12.635  5423  5469 I jxcore-log: 
,09-16 08:33:12.685  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:12.689  5423  5469 I jxcore-log: ok 196 should be equal
09-16 08:33:12.689  5423  5469 I jxcore-log: 
09-16 08:33:12.691  5423  5469 I jxcore-log: # teardown
09-16 08:33:12.691  5423  5469 I jxcore-log: 
,09-16 08:33:12.744  5423  5469 I jxcore-log: # setup
09-16 08:33:12.744  5423  5469 I jxcore-log: 
,09-16 08:33:12.807  5423  5469 I jxcore-log: # 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
09-16 08:33:12.807  5423  5469 I jxcore-log: 
,09-16 08:33:12.887  5423  5469 I jxcore-log: ok 197 Malformed encrypted beacon key ID
09-16 08:33:12.887  5423  5469 I jxcore-log: 
,09-16 08:33:12.891  5423  5469 I jxcore-log: # teardown
09-16 08:33:12.891  5423  5469 I jxcore-log: 
,09-16 08:33:12.938  5423  5469 I jxcore-log: # setup
09-16 08:33:12.938  5423  5469 I jxcore-log: 
,09-16 08:33:12.987  5423  5469 I jxcore-log: # 58. #parseBeacons addressBookCallback fails decrypt
09-16 08:33:12.987  5423  5469 I jxcore-log: 
,09-16 08:33:13.185  5423  5469 I jxcore-log: ok 198 should be equal
09-16 08:33:13.185  5423  5469 I jxcore-log: 
,09-16 08:33:13.187  5423  5469 I jxcore-log: # teardown
09-16 08:33:13.187  5423  5469 I jxcore-log: 
,09-16 08:33:13.235  5423  5469 I jxcore-log: # setup
09-16 08:33:13.235  5423  5469 I jxcore-log: 
,09-16 08:33:13.320  5423  5469 I jxcore-log: # 59. #parseBeacons addressBookCallback returns no matches
09-16 08:33:13.320  5423  5469 I jxcore-log: 
,09-16 08:33:13.509  5423  5469 I jxcore-log: ok 199 should be equal
09-16 08:33:13.509  5423  5469 I jxcore-log: 
,09-16 08:33:13.510  5423  5469 I jxcore-log: ok 200 should be equal
09-16 08:33:13.510  5423  5469 I jxcore-log: 
09-16 08:33:13.511  5423  5469 I jxcore-log: # teardown
09-16 08:33:13.511  5423  5469 I jxcore-log: 
,09-16 08:33:13.574  5423  5469 I jxcore-log: # setup
09-16 08:33:13.574  5423  5469 I jxcore-log: 
,09-16 08:33:13.634  5423  5469 I jxcore-log: # 60. #parseBeacons addressBookCallback returns spurious match
09-16 08:33:13.634  5423  5469 I jxcore-log: 
,09-16 08:33:13.686  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:13.843  5423  5469 I jxcore-log: ok 201 should be equal
09-16 08:33:13.843  5423  5469 I jxcore-log: 
,09-16 08:33:13.844  5423  5469 I jxcore-log: ok 202 should be equal
09-16 08:33:13.844  5423  5469 I jxcore-log: 
,09-16 08:33:13.845  5423  5469 I jxcore-log: # teardown
09-16 08:33:13.845  5423  5469 I jxcore-log: 
,09-16 08:33:13.931  5423  5469 I jxcore-log: # setup
09-16 08:33:13.931  5423  5469 I jxcore-log: 
,09-16 08:33:14.006  5423  5469 I jxcore-log: # 61. #parseBeacons addressBookCallback returns public key
09-16 08:33:14.006  5423  5469 I jxcore-log: 
,09-16 08:33:14.187  5423  5469 I jxcore-log: ok 203 right number of calls to address book
09-16 08:33:14.187  5423  5469 I jxcore-log: 
,09-16 08:33:14.187  5423  5469 I jxcore-log: ok 204 good preAmble
09-16 08:33:14.187  5423  5469 I jxcore-log: 
09-16 08:33:14.187  5423  5469 I jxcore-log: ok 205 good unencryptedKeyId
09-16 08:33:14.187  5423  5469 I jxcore-log: 
09-16 08:33:14.188  5423  5469 I jxcore-log: ok 206 good beacon
09-16 08:33:14.188  5423  5469 I jxcore-log: 
09-16 08:33:14.189  5423  5469 I jxcore-log: # teardown
09-16 08:33:14.189  5423  5469 I jxcore-log: 
,09-16 08:33:14.238  5423  5469 I jxcore-log: # setup
09-16 08:33:14.238  5423  5469 I jxcore-log: 
,09-16 08:33:14.286  5423  5469 I jxcore-log: # 62. validate generatePskIdentityField
09-16 08:33:14.286  5423  5469 I jxcore-log: 
,09-16 08:33:14.370  5423  5469 I jxcore-log: ok 207 decoded buffers match
09-16 08:33:14.370  5423  5469 I jxcore-log: 
,09-16 08:33:14.374  5423  5469 I jxcore-log: # teardown
09-16 08:33:14.374  5423  5469 I jxcore-log: 
,09-16 08:33:14.438  5423  5469 I jxcore-log: # setup
09-16 08:33:14.438  5423  5469 I jxcore-log: 
,09-16 08:33:14.498  5423  5469 I jxcore-log: # 63. validate generatePskSecret
09-16 08:33:14.498  5423  5469 I jxcore-log: 
,09-16 08:33:14.639  5423  5469 I jxcore-log: ok 208 secrets match
09-16 08:33:14.639  5423  5469 I jxcore-log: 
,09-16 08:33:14.641  5423  5469 I jxcore-log: # teardown
09-16 08:33:14.641  5423  5469 I jxcore-log: 
,09-16 08:33:14.681  5423  5469 I jxcore-log: # setup
09-16 08:33:14.681  5423  5469 I jxcore-log: 
,09-16 08:33:14.687  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:14.754  5423  5469 I jxcore-log: # 64. validate generatePskSecrets
09-16 08:33:14.754  5423  5469 I jxcore-log: 
,09-16 08:33:14.971  5423  5469 I jxcore-log: ok 209 Matching numbers
09-16 08:33:14.971  5423  5469 I jxcore-log: 
,09-16 08:33:14.978  5423  5469 I jxcore-log: ok 210 We have an entry!
09-16 08:33:14.978  5423  5469 I jxcore-log: 
09-16 08:33:14.978  5423  5469 I jxcore-log: ok 211 keys match
09-16 08:33:14.978  5423  5469 I jxcore-log: 
,09-16 08:33:14.978  5423  5469 I jxcore-log: ok 212 secrets match
09-16 08:33:14.978  5423  5469 I jxcore-log: 
,09-16 08:33:14.983  5423  5469 I jxcore-log: ok 213 We have an entry!
09-16 08:33:14.983  5423  5469 I jxcore-log: 
,09-16 08:33:14.984  5423  5469 I jxcore-log: ok 214 keys match
09-16 08:33:14.984  5423  5469 I jxcore-log: 
09-16 08:33:14.984  5423  5469 I jxcore-log: ok 215 secrets match
09-16 08:33:14.984  5423  5469 I jxcore-log: 
,09-16 08:33:14.989  5423  5469 I jxcore-log: ok 216 We have an entry!
09-16 08:33:14.989  5423  5469 I jxcore-log: 
,09-16 08:33:14.989  5423  5469 I jxcore-log: ok 217 keys match
09-16 08:33:14.989  5423  5469 I jxcore-log: 
09-16 08:33:14.989  5423  5469 I jxcore-log: ok 218 secrets match
09-16 08:33:14.989  5423  5469 I jxcore-log: 
,09-16 08:33:14.991  5423  5469 I jxcore-log: # teardown
09-16 08:33:14.991  5423  5469 I jxcore-log: 
,09-16 08:33:15.024  5423  5469 I jxcore-log: # setup
09-16 08:33:15.024  5423  5469 I jxcore-log: 
,09-16 08:33:15.112  5423  5469 I jxcore-log: # 65. validate generateBeaconStreamAndSecrets
09-16 08:33:15.112  5423  5469 I jxcore-log: 
,09-16 08:33:15.301  5423  5469 I jxcore-log: ok 219 Streams have same length
09-16 08:33:15.301  5423  5469 I jxcore-log: 
,09-16 08:33:15.309  5423  5469 I jxcore-log: ok 220 matching size
09-16 08:33:15.309  5423  5469 I jxcore-log: 
,09-16 08:33:15.309  5423  5469 I jxcore-log: ok 221 keys match
09-16 08:33:15.309  5423  5469 I jxcore-log: 
09-16 08:33:15.310  5423  5469 I jxcore-log: ok 222 secrets match
09-16 08:33:15.310  5423  5469 I jxcore-log: 
,09-16 08:33:15.311  5423  5469 I jxcore-log: # teardown
09-16 08:33:15.311  5423  5469 I jxcore-log: 
,09-16 08:33:15.352  5423  5469 I jxcore-log: # setup
09-16 08:33:15.352  5423  5469 I jxcore-log: 
,09-16 08:33:15.545  5423  5469 I jxcore-log: # 66. Add two Peers.
09-16 08:33:15.545  5423  5469 I jxcore-log: 
,09-16 08:33:15.619  5423  5469 I jxcore-log: ok 223 should be equal
09-16 08:33:15.619  5423  5469 I jxcore-log: 
,09-16 08:33:15.623  5423  5469 I jxcore-log: ok 224 should be equal
09-16 08:33:15.623  5423  5469 I jxcore-log: 
,09-16 08:33:15.624  5423  5469 I jxcore-log: ok 225 should be equal
09-16 08:33:15.624  5423  5469 I jxcore-log: 
,09-16 08:33:15.625  5423  5469 I jxcore-log: ok 226 should be equal
09-16 08:33:15.625  5423  5469 I jxcore-log: 
,09-16 08:33:15.630  5423  5469 I jxcore-log: ok 227 should be equal
09-16 08:33:15.630  5423  5469 I jxcore-log: 
,09-16 08:33:15.634  5423  5469 I jxcore-log: # teardown
09-16 08:33:15.634  5423  5469 I jxcore-log: 
,09-16 08:33:15.688  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:33:15.696  5423  5469 I jxcore-log: # setup
09-16 08:33:15.696  5423  5469 I jxcore-log: 
,09-16 08:33:15.847  5423  5469 I jxcore-log: # 67. TCP_NATIVE peer loses DNS
09-16 08:33:15.847  5423  5469 I jxcore-log: 
,09-16 08:33:15.886  5423  5469 I jxcore-log: ok 228 should be equal
09-16 08:33:15.886  5423  5469 I jxcore-log: 
,09-16 08:33:15.888  5423  5469 I jxcore-log: ok 229 should be equal
09-16 08:33:15.888  5423  5469 I jxcore-log: 
09-16 08:33:15.890  5423  5469 I jxcore-log: # teardown
09-16 08:33:15.890  5423  5469 I jxcore-log: 
,09-16 08:33:15.945  5423  5469 I jxcore-log: # setup
09-16 08:33:15.945  5423  5469 I jxcore-log: 
,09-16 08:33:16.141  5423  5469 I jxcore-log: # 68. Received beacons with no values for us
09-16 08:33:16.141  5423  5469 I jxcore-log: 
,09-16 08:33:16.337  5423  5469 I jxcore-log: ok 230 entry exists
09-16 08:33:16.337  5423  5469 I jxcore-log: 
,09-16 08:33:16.337  5423  5469 I jxcore-log: ok 231 entry is resolved
09-16 08:33:16.337  5423  5469 I jxcore-log: 
,09-16 08:33:16.349  5423  5469 I jxcore-log: # teardown
09-16 08:33:16.349  5423  5469 I jxcore-log: 
,09-16 08:33:16.381  5423  5469 I jxcore-log: # setup
09-16 08:33:16.381  5423  5469 I jxcore-log: 
,09-16 08:33:16.561  5423  5469 I jxcore-log: # 69. Resolves an action locally
09-16 08:33:16.561  5423  5469 I jxcore-log: 
,09-16 08:33:16.793  5423  5469 I jxcore-log: ok 232 Host address must match
09-16 08:33:16.793  5423  5469 I jxcore-log: 
,09-16 08:33:16.794  5423  5469 I jxcore-log: ok 233 suggestedTCPTimeout must match
09-16 08:33:16.794  5423  5469 I jxcore-log: 
,09-16 08:33:16.794  5423  5469 I jxcore-log: ok 234 connectionType must match
09-16 08:33:16.794  5423  5469 I jxcore-log: 
,09-16 08:33:16.795  5423  5469 I jxcore-log: ok 235 portNumber must match
09-16 08:33:16.795  5423  5469 I jxcore-log: 
,09-16 08:33:16.804  5423  5469 I jxcore-log: # teardown
09-16 08:33:16.804  5423  5469 I jxcore-log: 
,09-16 08:33:16.845  5423  5469 I jxcore-log: # setup
09-16 08:33:16.845  5423  5469 I jxcore-log: 
,09-16 08:33:17.016  5423  5469 I jxcore-log: # 70. Resolves an action locally using ThaliPeerPoolDefault
09-16 08:33:17.016  5423  5469 I jxcore-log: 
,09-16 08:33:17.185  5423  5469 I jxcore-log: ok 236 Host address must match
09-16 08:33:17.185  5423  5469 I jxcore-log: 
,09-16 08:33:17.185  5423  5469 I jxcore-log: ok 237 suggestedTCPTimeout must match
09-16 08:33:17.185  5423  5469 I jxcore-log: 
09-16 08:33:17.186  5423  5469 I jxcore-log: ok 238 connectionType must match
09-16 08:33:17.186  5423  5469 I jxcore-log: 
09-16 08:33:17.187  5423  5469 I jxcore-log: ok 239 portNumber must match
09-16 08:33:17.187  5423  5469 I jxcore-log: 
,09-16 08:33:17.192  5423  5469 I jxcore-log: # teardown
09-16 08:33:17.192  5423  5469 I jxcore-log: 
,09-16 08:33:17.320  5423  5469 I jxcore-log: # setup
09-16 08:33:17.320  5423  5469 I jxcore-log: 
,09-16 08:33:17.487  5423  5469 I jxcore-log: # 71. Action fails because of a bad hostname.
09-16 08:33:17.487  5423  5469 I jxcore-log: 
,09-16 08:33:27.188  5423  5469 I jxcore-log: ok 240 should be equal
09-16 08:33:27.188  5423  5469 I jxcore-log: 
,09-16 08:33:27.190  5423  5469 I jxcore-log: ok 241 should be equal
09-16 08:33:27.190  5423  5469 I jxcore-log: 
09-16 08:33:27.191  5423  5469 I jxcore-log: ok 242 should be equal
09-16 08:33:27.191  5423  5469 I jxcore-log: 
,09-16 08:33:27.199  5423  5469 I jxcore-log: # teardown
09-16 08:33:27.199  5423  5469 I jxcore-log: 
,09-16 08:33:27.667  5423  5469 I jxcore-log: # setup
09-16 08:33:27.667  5423  5469 I jxcore-log: 
,09-16 08:33:27.818  5423  5469 I jxcore-log: # 72. hostaddress is removed when the action is running. 
09-16 08:33:27.818  5423  5469 I jxcore-log: 
,09-16 08:33:29.914  5423  5469 I jxcore-log: ok 243 should be equal
09-16 08:33:29.914  5423  5469 I jxcore-log: 
,09-16 08:33:29.940  5423  5469 I jxcore-log: # teardown
09-16 08:33:29.940  5423  5469 I jxcore-log: 
,09-16 08:33:30.029  5423  5469 I jxcore-log: # setup
09-16 08:33:30.029  5423  5469 I jxcore-log: 
,09-16 08:33:30.182  5423  5469 I jxcore-log: # 73. Client to server request locally
09-16 08:33:30.182  5423  5469 I jxcore-log: 
,09-16 08:33:30.352  5423  5469 I jxcore-log: ok 244 secrets are equal
09-16 08:33:30.352  5423  5469 I jxcore-log: 
,09-16 08:33:30.353  5423  5469 I jxcore-log: ok 245 Public key matches with the server key
09-16 08:33:30.353  5423  5469 I jxcore-log: 
,09-16 08:33:30.353  5423  5469 I jxcore-log: ok 246 Host address must match
09-16 08:33:30.353  5423  5469 I jxcore-log: 
,09-16 08:33:30.353  5423  5469 I jxcore-log: ok 247 suggestedTCPTimeout must match
09-16 08:33:30.353  5423  5469 I jxcore-log: 
09-16 08:33:30.353  5423  5469 I jxcore-log: ok 248 connectionType must match
09-16 08:33:30.353  5423  5469 I jxcore-log: 
09-16 08:33:30.354  5423  5469 I jxcore-log: ok 249 portNumber must match
09-16 08:33:30.354  5423  5469 I jxcore-log: 
,09-16 08:33:30.359  5423  5469 I jxcore-log: # teardown
09-16 08:33:30.359  5423  5469 I jxcore-log: 
,09-16 08:33:30.401  5423  5469 I jxcore-log: # setup
09-16 08:33:30.401  5423  5469 I jxcore-log: 
,09-16 08:33:30.532  5423  5469 I jxcore-log: # 74. Test ThaliPskMapCache clean and expiration
09-16 08:33:30.532  5423  5469 I jxcore-log: 
,09-16 08:33:30.580  5423  5469 I jxcore-log: ok 250 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
09-16 08:33:30.580  5423  5469 I jxcore-log: 
,09-16 08:33:30.580  5423  5469 I jxcore-log: ok 251 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
09-16 08:33:30.580  5423  5469 I jxcore-log: 
,09-16 08:33:30.689  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:31.582  5423  5469 I jxcore-log: ok 252 All entries should be expired after 1 second
09-16 08:33:31.582  5423  5469 I jxcore-log: 
,09-16 08:33:31.591  5423  5469 I jxcore-log: # teardown
09-16 08:33:31.591  5423  5469 I jxcore-log: 
,09-16 08:33:31.655  5423  5469 I jxcore-log: # setup
09-16 08:33:31.655  5423  5469 I jxcore-log: 
,09-16 08:33:31.691  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:31.762  5423  5469 I jxcore-log: # 75. Test ThaliPskMapCache getSecret and getPublic
09-16 08:33:31.762  5423  5469 I jxcore-log: 
,09-16 08:33:31.877  5423  5469 I jxcore-log: ok 253 All keys need to be available in the cache
09-16 08:33:31.877  5423  5469 I jxcore-log: 
,09-16 08:33:32.692  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:32.879  5423  5469 I jxcore-log: ok 254 All entries should be expired after 1 second
09-16 08:33:32.879  5423  5469 I jxcore-log: 
,09-16 08:33:32.890  5423  5469 I jxcore-log: # teardown
09-16 08:33:32.890  5423  5469 I jxcore-log: 
,09-16 08:33:33.033  5423  5469 I jxcore-log: # setup
09-16 08:33:33.033  5423  5469 I jxcore-log: 
,09-16 08:33:33.195  5423  5469 I jxcore-log: # 76. Test ThaliPskMapCache multiple entries
09-16 08:33:33.195  5423  5469 I jxcore-log: 
,09-16 08:33:33.693  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:34.560  5423  5469 I jxcore-log: ok 255 Size of the cache should be 2
09-16 08:33:34.560  5423  5469 I jxcore-log: 
,09-16 08:33:34.564  5423  5469 I jxcore-log: ok 256 Cache doesn't contain dictionary1
09-16 08:33:34.564  5423  5469 I jxcore-log: 
,09-16 08:33:34.695  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:35.695  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:33:35.778  5423  5469 I jxcore-log: ok 257 Size of the cache should be 1
09-16 08:33:35.778  5423  5469 I jxcore-log: 
09-16 08:33:35.783  5423  5469 I jxcore-log: ok 258 Cache doesn't contain beaconStreamAndSecretDictionary2
09-16 08:33:35.783  5423  5469 I jxcore-log: 
,09-16 08:33:35.792  5423  5469 I jxcore-log: # teardown
09-16 08:33:35.792  5423  5469 I jxcore-log: 
,09-16 08:33:35.889  5423  5469 I jxcore-log: # setup
09-16 08:33:35.889  5423  5469 I jxcore-log: 
,09-16 08:33:35.999  5423  5469 I jxcore-log: # 77. Start and stop ThaliNotificationServer
09-16 08:33:35.999  5423  5469 I jxcore-log: 
,09-16 08:33:36.131  5423  5469 I jxcore-log: ok 259 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
09-16 08:33:36.131  5423  5469 I jxcore-log: 
,09-16 08:33:36.132  5423  5469 I jxcore-log: ok 260 ThaliMobile.StopAdvertisingAndListeningshould be called once
09-16 08:33:36.132  5423  5469 I jxcore-log: 
,09-16 08:33:36.133  5423  5469 I jxcore-log: # teardown
09-16 08:33:36.133  5423  5469 I jxcore-log: 
,09-16 08:33:36.234  5423  5469 I jxcore-log: # setup
09-16 08:33:36.234  5423  5469 I jxcore-log: 
,09-16 08:33:36.349  5423  5469 I jxcore-log: # 78. Pass an empty array to ThaliNotificationServer.start
09-16 08:33:36.349  5423  5469 I jxcore-log: 
,09-16 08:33:36.439  5423  5469 I jxcore-log: ok 261 StartUpdateAdvertisingAndListening should not be called
09-16 08:33:36.439  5423  5469 I jxcore-log: 
,09-16 08:33:36.465  5423  5469 I jxcore-log: ok 262 ThaliMobile.StopAdvertisingAndListening should be called once
09-16 08:33:36.465  5423  5469 I jxcore-log: 
,09-16 08:33:36.518  5423  5469 I jxcore-log: ok 263 no error
09-16 08:33:36.518  5423  5469 I jxcore-log: 
,09-16 08:33:36.518  5423  5469 I jxcore-log: ok 264 should be 204
09-16 08:33:36.518  5423  5469 I jxcore-log: 
,09-16 08:33:36.523  5423  5469 I jxcore-log: # teardown
09-16 08:33:36.523  5423  5469 I jxcore-log: 
,09-16 08:33:36.574  5423  5469 I jxcore-log: # setup
09-16 08:33:36.574  5423  5469 I jxcore-log: 
,09-16 08:33:36.719  5423  5469 I jxcore-log: # 79. Pass a string to ThaliNotificationServer.start
09-16 08:33:36.719  5423  5469 I jxcore-log: 
,09-16 08:33:36.777  5423  5469 I jxcore-log: ok 265 StartUpdateAdvertisingAndListening should not be called
09-16 08:33:36.777  5423  5469 I jxcore-log: 
,09-16 08:33:36.779  5423  5469 I jxcore-log: # teardown
09-16 08:33:36.779  5423  5469 I jxcore-log: 
,09-16 08:33:36.875  5423  5469 I jxcore-log: # setup
09-16 08:33:36.875  5423  5469 I jxcore-log: 
,09-16 08:33:37.172  5423  5469 I jxcore-log: # 80. Pass an empty parameter to ThaliNotificationServer.start
09-16 08:33:37.172  5423  5469 I jxcore-log: 
,09-16 08:33:37.218  5423  5469 I jxcore-log: ok 266 StartUpdateAdvertisingAndListening should not be called
09-16 08:33:37.218  5423  5469 I jxcore-log: 
,09-16 08:33:37.220  5423  5469 I jxcore-log: # teardown
09-16 08:33:37.220  5423  5469 I jxcore-log: 
,09-16 08:33:37.341  5423  5469 I jxcore-log: # setup
09-16 08:33:37.341  5423  5469 I jxcore-log: 
,09-16 08:33:37.437  5423  5469 I jxcore-log: # 81. Make an HTTP request to /NotificationBeacons
09-16 08:33:37.437  5423  5469 I jxcore-log: 
,09-16 08:33:37.641  5423  5469 I jxcore-log: ok 267 no error
09-16 08:33:37.641  5423  5469 I jxcore-log: 
,09-16 08:33:37.641  5423  5469 I jxcore-log: ok 268 should be 200
09-16 08:33:37.641  5423  5469 I jxcore-log: 
09-16 08:33:37.641  5423  5469 I jxcore-log: ok 269 should be equal
09-16 08:33:37.641  5423  5469 I jxcore-log: 
09-16 08:33:37.641  5423  5469 I jxcore-log: ok 270 should be equal
09-16 08:33:37.641  5423  5469 I jxcore-log: 
,09-16 08:33:37.659  5423  5469 I jxcore-log: ok 271 (unnamed assert)
09-16 08:33:37.659  5423  5469 I jxcore-log: 
,09-16 08:33:37.677  5423  5469 I jxcore-log: ok 272 no error
09-16 08:33:37.677  5423  5469 I jxcore-log: 
,09-16 08:33:37.677  5423  5469 I jxcore-log: ok 273 should be 204
09-16 08:33:37.677  5423  5469 I jxcore-log: 
,09-16 08:33:37.681  5423  5469 I jxcore-log: # teardown
09-16 08:33:37.681  5423  5469 I jxcore-log: 
,09-16 08:33:37.717  5423  5469 I jxcore-log: # setup
09-16 08:33:37.717  5423  5469 I jxcore-log: 
,09-16 08:33:37.847  5423  5469 I jxcore-log: # 82. Make an HTTP request to /NotificationBeacons (no keys)
09-16 08:33:37.847  5423  5469 I jxcore-log: 
,09-16 08:33:37.972  5423  5469 I jxcore-log: ok 274 error should be null
09-16 08:33:37.972  5423  5469 I jxcore-log: 
,09-16 08:33:37.973  5423  5469 I jxcore-log: ok 275 should be 204
09-16 08:33:37.973  5423  5469 I jxcore-log: 
,09-16 08:33:37.978  5423  5469 I jxcore-log: # teardown
09-16 08:33:37.978  5423  5469 I jxcore-log: 
,09-16 08:33:38.024  5423  5469 I jxcore-log: # setup
09-16 08:33:38.024  5423  5469 I jxcore-log: 
,09-16 08:33:38.147  5423  5469 I jxcore-log: # 83. Make an HTTP request to /NotificationBeaconsbefore calling start
09-16 08:33:38.147  5423  5469 I jxcore-log: 
,09-16 08:33:38.225  5423  5469 I jxcore-log: ok 276 should be 404
09-16 08:33:38.225  5423  5469 I jxcore-log: 
,09-16 08:33:38.229  5423  5469 I jxcore-log: # teardown
09-16 08:33:38.229  5423  5469 I jxcore-log: 
,09-16 08:33:38.292  5423  5469 I jxcore-log: # setup
09-16 08:33:38.292  5423  5469 I jxcore-log: 
,09-16 08:33:38.337  5423  5469 I jxcore-log: # 84. #testThaliPeerAction - test getters
09-16 08:33:38.337  5423  5469 I jxcore-log: 
,09-16 08:33:38.416  5423  5469 I jxcore-log: ok 277 getPeerIdentifier
09-16 08:33:38.416  5423  5469 I jxcore-log: 
,09-16 08:33:38.417  5423  5469 I jxcore-log: ok 278 getConnectionType
09-16 08:33:38.417  5423  5469 I jxcore-log: 
09-16 08:33:38.419  5423  5469 I jxcore-log: ok 279 getActionType
09-16 08:33:38.419  5423  5469 I jxcore-log: 
,09-16 08:33:38.420  5423  5469 I jxcore-log: ok 280 getActionState
09-16 08:33:38.420  5423  5469 I jxcore-log: 
09-16 08:33:38.421  5423  5469 I jxcore-log: ok 281 getPskIdentity
09-16 08:33:38.421  5423  5469 I jxcore-log: 
,09-16 08:33:38.423  5423  5469 I jxcore-log: ok 282 getPskKey
09-16 08:33:38.423  5423  5469 I jxcore-log: 
,09-16 08:33:38.427  5423  5469 I jxcore-log: # teardown
09-16 08:33:38.427  5423  5469 I jxcore-log: 
,09-16 08:33:38.476  5423  5469 I jxcore-log: # setup
09-16 08:33:38.476  5423  5469 I jxcore-log: 
,09-16 08:33:38.536  5423  5469 I jxcore-log: # 85. #testThaliPeerAction - start and kill
09-16 08:33:38.536  5423  5469 I jxcore-log: 
,09-16 08:33:38.587  5423  5469 I jxcore-log: ok 283 initial state
09-16 08:33:38.587  5423  5469 I jxcore-log: 
,09-16 08:33:38.590  5423  5469 I jxcore-log: ok 284 after start
09-16 08:33:38.590  5423  5469 I jxcore-log: 
,09-16 08:33:38.591  5423  5469 I jxcore-log: ok 285 after kill
09-16 08:33:38.591  5423  5469 I jxcore-log: 
,09-16 08:33:38.595  5423  5469 I jxcore-log: # teardown
09-16 08:33:38.595  5423  5469 I jxcore-log: 
,09-16 08:33:38.645  5423  5469 I jxcore-log: # setup
09-16 08:33:38.645  5423  5469 I jxcore-log: 
,09-16 08:33:38.705  5423  5469 I jxcore-log: # 86. #testThaliPeerAction - double start
09-16 08:33:38.705  5423  5469 I jxcore-log: 
,09-16 08:33:38.761  5423  5469 I jxcore-log: ok 286 should be equal
09-16 08:33:38.761  5423  5469 I jxcore-log: 
,09-16 08:33:38.765  5423  5469 I jxcore-log: # teardown
09-16 08:33:38.765  5423  5469 I jxcore-log: 
,09-16 08:33:38.810  5423  5469 I jxcore-log: # setup
09-16 08:33:38.810  5423  5469 I jxcore-log: 
,09-16 08:33:38.858  5423  5469 I jxcore-log: # 87. #testThaliPeerAction - start after kill
09-16 08:33:38.858  5423  5469 I jxcore-log: 
,09-16 08:33:38.929  5423  5469 I jxcore-log: ok 287 clean kill
09-16 08:33:38.929  5423  5469 I jxcore-log: 
,09-16 08:33:38.933  5423  5469 I jxcore-log: ok 288 should be equal
09-16 08:33:38.933  5423  5469 I jxcore-log: 
09-16 08:33:38.936  5423  5469 I jxcore-log: # teardown
09-16 08:33:38.936  5423  5469 I jxcore-log: 
,09-16 08:33:38.980  5423  5469 I jxcore-log: # setup
09-16 08:33:38.980  5423  5469 I jxcore-log: 
,09-16 08:33:39.057  5423  5469 I jxcore-log: # 88. #testThaliPeerAction - make sure ids are unique
09-16 08:33:39.057  5423  5469 I jxcore-log: 
,09-16 08:33:39.117  5423  5469 I jxcore-log: ok 289 should not be equal
09-16 08:33:39.117  5423  5469 I jxcore-log: 
,09-16 08:33:39.121  5423  5469 I jxcore-log: # teardown
09-16 08:33:39.121  5423  5469 I jxcore-log: 
,09-16 08:33:39.183  5423  5469 I jxcore-log: # setup
09-16 08:33:39.183  5423  5469 I jxcore-log: 
,09-16 08:33:39.237  5423  5469 I jxcore-log: # 89. Test PeerConnectionInformation basics
09-16 08:33:39.237  5423  5469 I jxcore-log: 
,09-16 08:33:39.286  5423  5469 I jxcore-log: ok 290 connection type works
09-16 08:33:39.286  5423  5469 I jxcore-log: 
,09-16 08:33:39.287  5423  5469 I jxcore-log: ok 291 getHostAddress works
09-16 08:33:39.287  5423  5469 I jxcore-log: 
09-16 08:33:39.288  5423  5469 I jxcore-log: ok 292 getPortNumber works
09-16 08:33:39.288  5423  5469 I jxcore-log: 
09-16 08:33:39.288  5423  5469 I jxcore-log: ok 293 getSuggestedTCPTimeout works
09-16 08:33:39.288  5423  5469 I jxcore-log: 
,09-16 08:33:39.291  5423  5469 I jxcore-log: # teardown
09-16 08:33:39.291  5423  5469 I jxcore-log: 
,09-16 08:33:39.346  5423  5469 I jxcore-log: # setup
09-16 08:33:39.346  5423  5469 I jxcore-log: 
,09-16 08:33:39.418  5423  5469 I jxcore-log: # 90. Test PeerDictionary basic functionality
09-16 08:33:39.418  5423  5469 I jxcore-log: 
,09-16 08:33:39.517  5423  5469 I jxcore-log: ok 294 Entry counter must be 1
09-16 08:33:39.517  5423  5469 I jxcore-log: 
,09-16 08:33:39.518  5423  5469 I jxcore-log: ok 295 Size must be 1
09-16 08:33:39.518  5423  5469 I jxcore-log: 
09-16 08:33:39.518  5423  5469 I jxcore-log: ok 296 Entry counter must be 2
09-16 08:33:39.518  5423  5469 I jxcore-log: 
09-16 08:33:39.518  5423  5469 I jxcore-log: ok 297 Size must be 2
09-16 08:33:39.518  5423  5469 I jxcore-log: 
09-16 08:33:39.519  5423  5469 I jxcore-log: ok 298 Entry2 should not be found
09-16 08:33:39.519  5423  5469 I jxcore-log: 
,09-16 08:33:39.520  5423  5469 I jxcore-log: ok 299 Size must be 1
09-16 08:33:39.520  5423  5469 I jxcore-log: 
,09-16 08:33:39.520  5423  5469 I jxcore-log: ok 300 Size must be 0
09-16 08:33:39.520  5423  5469 I jxcore-log: 
,09-16 08:33:39.524  5423  5469 I jxcore-log: # teardown
09-16 08:33:39.524  5423  5469 I jxcore-log: 
,09-16 08:33:39.560  5423  5469 I jxcore-log: # setup
09-16 08:33:39.560  5423  5469 I jxcore-log: 
,09-16 08:33:39.617  5423  5469 I jxcore-log: # 91. Test PeerDictionary with multiple entries.
09-16 08:33:39.617  5423  5469 I jxcore-log: 
,09-16 08:33:39.989   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:33:40.230  5423  5469 I jxcore-log: ok 301 Size must be100
09-16 08:33:40.230  5423  5469 I jxcore-log: 
,09-16 08:33:40.233  5423  5469 I jxcore-log: ok 302 Entries between 20 and MAXSIZE + 20 should exist
09-16 08:33:40.233  5423  5469 I jxcore-log: 
,09-16 08:33:40.745  5423  5469 I jxcore-log: ok 303 WAITING state entry should not be removed
09-16 08:33:40.745  5423  5469 I jxcore-log: 
,09-16 08:33:40.747  5423  5469 I jxcore-log: # teardown
09-16 08:33:40.747  5423  5469 I jxcore-log: 
,09-16 08:33:40.778  5423  5469 I jxcore-log: # setup
09-16 08:33:40.778  5423  5469 I jxcore-log: 
,09-16 08:33:41.897  5423  5469 I jxcore-log: # 92. RESOLVED entries are removed before WAITING state entry.
09-16 08:33:41.897  5423  5469 I jxcore-log: 
,09-16 08:33:42.505  5423  5469 I jxcore-log: ok 304 Entries between 6 and MAXSIZE + 4 should exist
09-16 08:33:42.505  5423  5469 I jxcore-log: 
,09-16 08:33:42.505  5423  5469 I jxcore-log: ok 305 Size should be MAXSIZE
09-16 08:33:42.505  5423  5469 I jxcore-log: 
09-16 08:33:42.505  5423  5469 I jxcore-log: ok 306 Size should be MAXSIZE+6
09-16 08:33:42.505  5423  5469 I jxcore-log: 
,09-16 08:33:42.507  5423  5469 I jxcore-log: # teardown
09-16 08:33:42.507  5423  5469 I jxcore-log: 
,09-16 08:33:42.548  5423  5469 I jxcore-log: # setup
09-16 08:33:42.548  5423  5469 I jxcore-log: 
,09-16 08:33:42.627  5423  5469 I jxcore-log: # 93. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
09-16 08:33:42.627  5423  5469 I jxcore-log: 
,09-16 08:33:43.217  5423  5469 I jxcore-log: ok 307 WAITING state entry should not be removed
09-16 08:33:43.217  5423  5469 I jxcore-log: 
,09-16 08:33:43.218  5423  5469 I jxcore-log: ok 308 Waiting entries between 6 and MAXSIZE + 4 should exist
09-16 08:33:43.218  5423  5469 I jxcore-log: 
09-16 08:33:43.218  5423  5469 I jxcore-log: ok 309 Size should be MAXSIZE
09-16 08:33:43.218  5423  5469 I jxcore-log: 
09-16 08:33:43.218  5423  5469 I jxcore-log: ok 310 entryCounter should be MAXSIZE+6
09-16 08:33:43.218  5423  5469 I jxcore-log: 
,09-16 08:33:43.220  5423  5469 I jxcore-log: # teardown
09-16 08:33:43.220  5423  5469 I jxcore-log: 
,09-16 08:33:43.282  5423  5469 I jxcore-log: # setup
09-16 08:33:43.282  5423  5469 I jxcore-log: 
,09-16 08:33:43.348  5423  5469 I jxcore-log: # 94. When CONTROLLED_BY_POOL entry is removed and kill is called.
09-16 08:33:43.348  5423  5469 I jxcore-log: 
,09-16 08:33:43.931  5423  5469 I jxcore-log: ok 311 Kill should be called once
09-16 08:33:43.931  5423  5469 I jxcore-log: 
,09-16 08:33:43.931  5423  5469 I jxcore-log: ok 312 Size should be 100
09-16 08:33:43.931  5423  5469 I jxcore-log: 
,09-16 08:33:43.936  5423  5469 I jxcore-log: # teardown
09-16 08:33:43.936  5423  5469 I jxcore-log: 
,09-16 08:33:43.976  5423  5469 I jxcore-log: # setup
09-16 08:33:43.976  5423  5469 I jxcore-log: 
,09-16 08:33:44.051  5423  5469 I jxcore-log: # 95. #ThaliPeerPoolInterface - make sure that start verifies queue length
09-16 08:33:44.051  5423  5469 I jxcore-log: 
,09-16 08:33:44.116  5423  5469 I jxcore-log: ok 313 good start
09-16 08:33:44.116  5423  5469 I jxcore-log: 
,09-16 08:33:44.118  5423  5469 I jxcore-log: ok 314 good enqueue
09-16 08:33:44.118  5423  5469 I jxcore-log: 
,09-16 08:33:44.128  5423  5469 I jxcore-log: ok 315 queue is not empty
09-16 08:33:44.128  5423  5469 I jxcore-log: 
,09-16 08:33:44.135  5423  5469 I jxcore-log: # teardown
09-16 08:33:44.135  5423  5469 I jxcore-log: 
,09-16 08:33:44.198  5423  5469 I jxcore-log: # setup
09-16 08:33:44.198  5423  5469 I jxcore-log: 
,09-16 08:33:44.241  5423  5469 I jxcore-log: # 96. #ThaliPeerPoolInterface - bad enqueues
09-16 08:33:44.241  5423  5469 I jxcore-log: 
,09-16 08:33:44.294  5423  5469 I jxcore-log: ok 316 null arg
09-16 08:33:44.294  5423  5469 I jxcore-log: 
,09-16 08:33:44.298  5423  5469 I jxcore-log: ok 317 wrong arg type
09-16 08:33:44.298  5423  5469 I jxcore-log: 
,09-16 08:33:44.302  5423  5469 I jxcore-log: ok 318 wrong arg type
09-16 08:33:44.302  5423  5469 I jxcore-log: 
,09-16 08:33:44.307  5423  5469 I jxcore-log: # teardown
09-16 08:33:44.307  5423  5469 I jxcore-log: 
,09-16 08:33:44.360  5423  5469 I jxcore-log: # setup
09-16 08:33:44.360  5423  5469 I jxcore-log: 
,09-16 08:33:44.414  5423  5469 I jxcore-log: # 97. #ThaliPeerPoolInterface - do not allow same object type
09-16 08:33:44.414  5423  5469 I jxcore-log: 
,09-16 08:33:44.475  5423  5469 I jxcore-log: ok 319 good enqueue
09-16 08:33:44.475  5423  5469 I jxcore-log: 
,09-16 08:33:44.480  5423  5469 I jxcore-log: ok 320 already enqueued
09-16 08:33:44.480  5423  5469 I jxcore-log: 
,09-16 08:33:44.494  5423  5469 I jxcore-log: # teardown
09-16 08:33:44.494  5423  5469 I jxcore-log: 
,09-16 08:33:44.561  5423  5469 I jxcore-log: # setup
09-16 08:33:44.561  5423  5469 I jxcore-log: 
,09-16 08:33:44.616  5423  5469 I jxcore-log: # 98. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
09-16 08:33:44.616  5423  5469 I jxcore-log: 
,09-16 08:33:44.681  5423  5469 I jxcore-log: ok 321 good enqueue
09-16 08:33:44.681  5423  5469 I jxcore-log: 
,09-16 08:33:44.683  5423  5469 I jxcore-log: ok 322 2nd good enqueue
09-16 08:33:44.683  5423  5469 I jxcore-log: 
,09-16 08:33:44.684  5423  5469 I jxcore-log: ok 323 we are in the pool
09-16 08:33:44.684  5423  5469 I jxcore-log: 
,09-16 08:33:44.689  5423  5469 I jxcore-log: ok 324 We are out of the pool
09-16 08:33:44.689  5423  5469 I jxcore-log: 
,09-16 08:33:44.690  5423  5469 I jxcore-log: ok 325 Action was killed
09-16 08:33:44.690  5423  5469 I jxcore-log: 
09-16 08:33:44.691  5423  5469 I jxcore-log: ok 326 The original kill was called too
09-16 08:33:44.691  5423  5469 I jxcore-log: 
,09-16 08:33:44.692  5423  5469 I jxcore-log: ok 327 second item is still in queue
09-16 08:33:44.692  5423  5469 I jxcore-log: 
,09-16 08:33:44.696  5423  5469 I jxcore-log: # teardown
09-16 08:33:44.696  5423  5469 I jxcore-log: 
,09-16 08:33:44.739  5423  5469 I jxcore-log: # setup
09-16 08:33:44.739  5423  5469 I jxcore-log: 
,09-16 08:33:44.797  5423  5469 I jxcore-log: # 99. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
09-16 08:33:44.797  5423  5469 I jxcore-log: 
,09-16 08:33:44.856  5423  5469 I jxcore-log: ok 328 good enqueue
09-16 08:33:44.856  5423  5469 I jxcore-log: 
,09-16 08:33:44.860  5423  5469 I jxcore-log: ok 329 first kill
09-16 08:33:44.860  5423  5469 I jxcore-log: 
,09-16 08:33:44.861  5423  5469 I jxcore-log: ok 330 second NOOP kill
09-16 08:33:44.861  5423  5469 I jxcore-log: 
,09-16 08:33:44.865  5423  5469 I jxcore-log: # teardown
09-16 08:33:44.865  5423  5469 I jxcore-log: 
,09-16 08:33:44.914  5423  5469 I jxcore-log: # setup
09-16 08:33:44.914  5423  5469 I jxcore-log: 
,09-16 08:33:44.966  5423  5469 I jxcore-log: # 100. #ThaliPeerPoolInterface - make sure that stop removes all actions
09-16 08:33:44.966  5423  5469 I jxcore-log: 
,09-16 08:33:45.014  5423  5469 I jxcore-log: ok 331 1st good enqueue
09-16 08:33:45.014  5423  5469 I jxcore-log: 
,09-16 08:33:45.016  5423  5469 I jxcore-log: ok 332 2nd good enqueue
09-16 08:33:45.016  5423  5469 I jxcore-log: 
,09-16 08:33:45.018  5423  5469 I jxcore-log: ok 333 1st action is in the pool
09-16 08:33:45.018  5423  5469 I jxcore-log: 
,09-16 08:33:45.019  5423  5469 I jxcore-log: ok 334 2nd action is in the pool
09-16 08:33:45.019  5423  5469 I jxcore-log: 
,09-16 08:33:45.024  5423  5469 I jxcore-log: ok 335 1st action is out of the pool
09-16 08:33:45.024  5423  5469 I jxcore-log: 
,09-16 08:33:45.025  5423  5469 I jxcore-log: ok 336 2st action is out of the pool
09-16 08:33:45.025  5423  5469 I jxcore-log: 
,09-16 08:33:45.026  5423  5469 I jxcore-log: ok 337 pool is empty
09-16 08:33:45.026  5423  5469 I jxcore-log: 
,09-16 08:33:45.031  5423  5469 I jxcore-log: # teardown
09-16 08:33:45.031  5423  5469 I jxcore-log: 
,09-16 08:33:45.085  5423  5469 I jxcore-log: # setup
09-16 08:33:45.085  5423  5469 I jxcore-log: 
,09-16 08:33:55.697  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:56.698  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:57.699  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:58.701  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:33:59.702  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:00.703  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:34:19.992   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:34:25.704  5864  5864 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:34:25.704  5864  5864 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:34:30.705  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:31.707  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:32.708  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:33.710  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:34.711  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:35.712  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:34:39.995   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:34:40.714  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:41.715  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:42.717  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:43.718  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:44.720  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:45.721  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:34:53.016   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:34:55.722  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:56.052   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:34:56.723  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:57.724  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:58.726  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:59.083   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:34:59.727  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:34:59.997   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:35:00.728  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:35:02.102   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:35:15.730  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:16.731  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:17.732  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:18.733  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:19.734  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:19.998   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:35:20.735  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:35:40.001   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:35:40.736  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:41.738  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:42.740  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:43.741  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:44.743  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:35:45.743  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:36:10.744  5864  5864 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:36:10.745  5864  5864 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:36:17.783   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:36:20.005   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:36:20.746  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:20.798   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:36:21.747  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:22.749  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:23.750  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:24.751  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:25.752  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:36:30.754  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:31.755  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:32.757  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:33.759  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:34.760  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:35.760  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:36:40.007   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:36:45.762  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:46.764  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:47.765  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:48.767  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:49.768  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:36:50.769  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:36:54.121   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:36:57.152   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:37:00.010   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:37:00.165   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:37:03.197   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:37:05.771  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:06.772  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:07.774  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:08.775  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:09.777  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:10.777  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:37:20.013   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:37:30.779  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:31.780  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:32.782  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:33.470   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:37:33.783  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:34.785  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:37:35.785  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:37:36.500   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:37:40.014   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:38:00.018   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:38:00.786  5864  5864 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:38:00.787  5864  5864 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:38:09.801   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:38:12.834   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:38:15.788  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:16.789  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:17.791  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:18.792  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:19.794  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:20.019   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:38:20.794  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:38:21.932   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:38:24.961   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:38:25.796  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:26.797  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:27.799  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:28.801  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:29.802  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:30.803  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:38:31.020   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:38:34.051   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:38:40.805  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:41.806  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:42.808  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:43.122   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:38:43.809  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:44.810  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:38:45.810  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:38:49.179   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:38:55.242   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:38:58.275   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:39:00.023   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:39:00.812  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:01.813  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:02.814  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:03.816  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:04.817  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:05.818  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:39:20.025   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:39:25.819  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:26.820  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:27.821  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:28.823  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:29.824  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:39:30.825  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:39:37.640   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:39:40.028   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:39:43.705   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:39:46.743   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:39:49.777   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:39:55.826  5864  5864 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:39:55.826  5864  5864 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:40:00.028   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:40:07.961   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:40:10.992   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:40:15.827  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:16.829  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:17.045   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:40:17.830  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:18.831  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:19.833  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:20.031   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:40:20.834  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:40:25.836  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:26.125   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:40:26.837  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:27.839  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:28.840  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:29.842  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:30.843  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:40:40.034   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:40:40.844  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:41.846  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:42.847  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:43.849  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:44.850  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:40:45.851  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:40:50.351   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:40:53.387   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:41:00.034   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:41:00.853  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:01.854  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:02.855  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:03.857  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:04.858  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:05.858  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:41:11.558   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:41:17.615   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:41:20.038   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:41:25.860  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:26.695   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:41:26.861  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:27.863  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:28.864  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:29.725   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:41:29.865  5864  5864 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:41:30.866  5864  5864 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:41:40.038   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:41:41.839   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:41:44.871   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:41:55.867  5864  5864 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:41:55.867  5864  5864 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:42:00.038   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:42:06.075   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:42:09.111   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:42:20.041   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:42:20.878  5864  5866 E QC-QMI  : qmi_client [5864] 1d: failed to locate client data
,09-16 08:42:20.882   518   518 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-16 08:42:20.883   518   518 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-16 08:42:20.886  5864  5864 I Atfwd_Daemon: Stop the daemon....
,09-16 08:42:20.913  5889  5889 W ATFWD-daemon: type=1400 audit(0.0:133): avc: denied { read write } for name="diag" dev="tmpfs" ino=10945 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-16 08:42:20.918  5889  5889 I libmdmdetect: ESOC framework not supported
09-16 08:42:20.918  5889  5889 I libmdmdetect: Found internal modem: modem
09-16 08:42:20.918  5889  5889 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-16 08:42:20.923  5889  5889 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-16 08:42:20.923  5889  5889 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-16 08:42:20.924  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:21.927  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:22.929  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:23.930  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:24.931  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:25.932  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:42:27.266   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:42:28.670   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1172773, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:42:30.297   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:42:30.933  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:31.934  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:32.936  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:33.937  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:34.938  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:35.939  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:42:36.353   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:42:39.384   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:42:41.351   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1185454, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:42:42.408   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:42:45.941  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:46.942  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:47.944  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:48.474   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:42:48.945  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:49.947  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:42:50.947  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:42:53.710   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1197814, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:42:54.526   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:00.045   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:43:00.581   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:05.949  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:06.404   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1210507, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:43:06.639   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:06.950  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:07.951  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:08.952  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:09.675   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:09.954  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:10.955  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:43:15.477   927   939 I UsageStatsService: User[0] Flushing usage stats to disk
,09-16 08:43:15.734   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:18.767   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:18.777   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1222880, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:43:20.047   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:43:30.956  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:31.457   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1235560, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:43:31.958  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:32.959  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:33.960  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:34.961  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:43:35.961  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:43:36.932   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102],
,09-16 08:43:39.964   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:40.048   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:43:42.997   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:43.817   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1247920, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:43:46.033   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:49.070   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:43:56.497   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1260600, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:44:00.050   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:44:00.963  5889  5889 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:44:00.963  5889  5889 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:44:04.215   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:44:05.964  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:06.965  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:07.967  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:08.857   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1272960, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:44:08.968  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:09.969  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:10.970  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:44:15.972  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:16.973  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:17.974  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:18.976  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:19.358   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:44:19.977  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:20.051   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:44:20.978  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:44:21.537   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1285640, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:44:22.395   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:44:28.457   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:44:30.979  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:31.487   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:44:31.980  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:32.981  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:33.950   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1298053, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:44:33.983  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:34.984  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:35.984  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:44:40.054   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:44:40.575   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:44:43.601   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:44:46.630   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1310733, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:44:50.986  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:51.988  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:52.989  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:53.991  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:54.992  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:44:55.993  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:44:58.990   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1323094, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:45:00.056   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:45:10.850   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:45:11.671   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1335774, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:45:13.885   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:45:15.995  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:45:16.996  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:45:17.998  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:45:18.999  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:45:19.945   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:45:20.027  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:45:20.056   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:45:21.028  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:45:22.984   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:45:24.031   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1348134, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:45:36.711   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1360814, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:45:40.058   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:45:46.029  5889  5889 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:45:46.029  5889  5889 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:45:49.070   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1373173, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:45:56.030  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:45:56.298   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:45:57.032  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:45:58.033  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:45:59.035  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:00.036  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:00.058   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:46:01.037  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:46:01.751   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1385854, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:46:02.359   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:46:06.038  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:07.040  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:08.041  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:09.043  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:10.044  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:11.045  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:46:14.111   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1398214, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:46:20.062   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:46:21.046  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:22.048  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:23.049  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:24.050  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:25.052  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:26.053  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:46:26.791   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1410894, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:46:39.151   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1423254, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:46:40.065   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:46:41.054  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:42.055  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:43.056  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:44.057  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:45.059  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:46:46.059  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:46:47.770   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:46:50.802   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:46:51.830   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1435934, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:47:00.065   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:47:04.217   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1448320, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:47:06.061  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:07.062  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:08.064  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:09.065  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:10.066  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:11.067  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:47:16.884   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1460987, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:47:20.068   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:47:22.910   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1467013, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:47:36.068  5889  5889 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:47:36.068  5889  5889 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:47:40.069   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:47:41.923   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1486027, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:47:47.950   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1492054, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:47:51.070  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:52.071  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:53.073  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:54.074  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:55.076  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:47:56.077  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:48:00.071   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:48:01.078  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:02.080  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:03.081  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:04.083  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:05.084  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:06.085  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:48:06.977   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1511080, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:48:12.991   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1517094, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:48:16.087  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:17.088  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:18.090  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:19.091  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:20.074   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:48:20.093  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:21.094  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:48:24.681   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:48:27.719   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:48:32.044   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1536147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:48:36.095  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:37.097  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:38.084   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1542187, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:48:38.098  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:39.100  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:40.101  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:48:41.102  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:48:57.110   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1561213, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:49:00.076   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:49:01.104  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:02.105  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:03.106  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:03.150   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1567253, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:49:04.107  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:05.108  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:06.109  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:49:20.078   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:49:22.164   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1586267, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-16 08:49:31.110  5889  5889 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:49:31.110  5889  5889 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:49:33.203   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1597307, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:49:40.082   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:49:47.204   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1611307, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-16 08:49:51.111  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:52.113  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:53.114  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:54.115  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:55.116  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:49:56.117  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 08:49:58.244   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1622347, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:50:00.083   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:50:01.119  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:02.120  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:03.122  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:04.123  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:05.124  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:06.125  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 08:50:07.589   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:50:10.623   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:50:12.230   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1636334, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:50:16.127  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:17.128  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:18.130  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:18.257   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1642360, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:50:19.131  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:20.084   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:50:20.132  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:21.133  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 08:50:36.135  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:37.136  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:37.284   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1661387, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:50:38.137  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:39.139  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:40.086   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:50:40.140  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:50:41.141  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 08:50:43.310   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1667413, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:50:46.954   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:50:49.983   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:51:00.088   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:51:01.142  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:51:02.114   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:51:02.143  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:51:02.323   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1686427, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:51:03.144  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:51:04.145  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:51:05.137   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:51:05.146  5889  5889 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:51:06.147  5889  5889 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 08:51:08.350   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1692454, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:51:20.092   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:51:26.317   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:51:27.377   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1711480, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:51:29.350   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 08:51:31.148  5889  5889 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 08:51:31.148  5889  5889 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 08:51:33.391   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1717494, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:51:40.095   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:51:52.417   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1736520, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 08:51:56.159  5889  5891 E QC-QMI  : qmi_client [5889] 1e: failed to locate client data
,09-16 08:51:56.160   518   518 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-16 08:51:56.161   518   518 E QC-QMI  : QMUX qmux_client_id=1e not found in qmux client list, unable to remove
,09-16 08:51:56.165  5889  5889 I Atfwd_Daemon: Stop the daemon....
,09-16 08:51:56.211  5902  5902 I libmdmdetect: ESOC framework not supported
,09-16 08:51:56.211  5902  5902 I libmdmdetect: Found internal modem: modem
09-16 08:51:56.212  5902  5902 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-16 08:51:56.206  5902  5902 W ATFWD-daemon: type=1400 audit(0.0:134): avc: denied { read write } for name="diag" dev="tmpfs" ino=10945 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-16 08:51:56.221  5902  5902 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-16 08:51:56.221  5902  5902 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
09-16 08:51:56.222  5902  5902 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:51:57.224  5902  5902 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:51:58.225  5902  5902 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:51:58.457   927  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1742560, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 08:51:59.226  5902  5902 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:52:00.096   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 08:52:00.228  5902  5902 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 08:52:01.228  5902  5902 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,TIME-OUT KILL (timeout was 1400000ms),09-16 08:52:03.977  5906  5906 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 08:52:03.982  5906  5906 D AndroidRuntime: CheckJNI is OFF
09-16 08:52:04.006  5906  5906 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 08:52:04.037  5906  5906 I Radio-JNI: register_android_hardware_Radio DONE
09-16 08:52:04.052  5906  5906 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-16 08:52:04.060   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-16 08:52:04.061   927   940 I ActivityManager: Killing 5423:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
09-16 08:52:04.108   927  2875 W InputDispatcher: channel 'a5284d5 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-16 08:52:04.108   927  2875 E InputDispatcher: channel 'a5284d5 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
09-16 08:52:04.113   927  3367 I WindowState: WIN DEATH: Window{a5284d5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-16 08:52:04.113   927  3089 D GraphicsStats: Buffer count: 2
09-16 08:52:04.113   927  3367 W InputDispatcher: Attempted to unregister already unregistered input channel 'a5284d5 com.test.thalitest/com.test.thalitest.MainActivity (server)'
09-16 08:52:04.114   927  2911 D WifiService: Client connection lost with reason: 4
09-16 08:52:04.205   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-16 08:52:04.206   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-16 08:52:04.207   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-16 08:52:04.207   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-16 08:52:04.207   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:52:04.207   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:52:04.207   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 08:52:04.207   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 08:52:04.207   927   940 I ActivityManager:   Force finishing activity ActivityRecord{165c37e u0 com.test.thalitest/.MainActivity t4}
09-16 08:52:04.210   927   950 I art     : Starting a blocking GC Explicit
09-16 08:52:04.218   927  3410 W ActivityManager: Spurious death for ProcessRecord{d17fe44 0:com.test.thalitest/u0a77}, curProc for 5423: null
09-16 08:52:04.222   927   945 W WindowManager: Attempted to add application window with unknown token Token{b58d0df ActivityRecord{165c37e u0 com.test.thalitest/.MainActivity t4 f}}.  Aborting.
09-16 08:52:04.223   927   945 W WindowManager: Token{b58d0df ActivityRecord{165c37e u0 com.test.thalitest/.MainActivity t4 f}} already running, starting window not displayed. Unable to add window -- token Token{b58d0df ActivityRecord{165c37e u0 com.test.thalitest/.MainActivity t4 f}} is not valid; is your activity running?
09-16 08:52:04.223   927   945 W WindowManager: view not successfully added to wm, removing view
09-16 08:52:04.223   927   945 W WindowManager: Exception when adding starting window
09-16 08:52:04.223   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{7a9664f V.E...... R.....ID 0,0-0,0} not attached to window manager
09-16 08:52:04.223   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-16 08:52:04.223   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-16 08:52:04.223   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-16 08:52:04.223   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-16 08:52:04.223   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-16 08:52:04.223   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:52:04.223   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:52:04.223   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 08:52:04.223   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 08:52:04.322   927   950 I art     : Explicit concurrent mark sweep GC freed 134827(9MB) AllocSpace objects, 83(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.665ms total 111.769ms
09-16 08:52:04.342   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-16 08:52:04.345  5906  5906 I art     : System.exit called, status: 0
09-16 08:52:04.345  5906  5906 I AndroidRuntime: VM exiting with result code 0.
09-16 08:52:04.361   927   950 I ActivityManager: Start proc 5920:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-16 08:52:04.361   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-16 08:52:04.369   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-16 08:52:04.372  5715  5715 D BluetoothMapAppObserver: onReceive
09-16 08:52:04.372  5715  5715 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-16 08:52:04.376  3551  3894 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-16 08:52:04.376  3336  3336 I Keyboard.Facilitator: resetDictionaries() : en_US
09-16 08:52:04.382   927  2876 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-16 08:52:04.386   927   940 I ActivityManager: Start proc 5933:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-16 08:52:04.401  3336  5931 I Keyboard.Facilitator.DecoderInitializer: run()
09-16 08:52:04.413  3470  3470 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-16 08:52:04.412  3336  5931 I Decoder : createOrResetDecoder
09-16 08:52:04.432   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-16 08:52:04.430    28    28 W kworker/1:1: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 08:52:04.440    28    28 W kworker/1:1: type=1400 audit(0.0:136): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 08:52:04.453    28    28 W kworker/1:1: type=1400 audit(0.0:137): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 08:52:04.463  3487  3629 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-16 08:52:04.479   927  3726 I ActivityManager: Start proc 5948:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-16 08:52:04.480  3487  3629 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-16 08:52:04.480  3487  3629 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3487
09-16 08:52:04.480  3487  3629 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:52:04.480  3487  3629 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 08:52:04.485   927  3091 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 08:52:04.486  3528  3528 I ConfigService: onCreate
09-16 08:52:04.487   927  5953 E DropBoxManagerService: Can't write: system_app_crash
09-16 08:52:04.487   927  5953 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 08:52:04.487   927  5953 E DropBoxManagerService: 	... 5 more
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-16 08:52:04.490  3528  5954 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-16 08:52:04.490  3528  5954 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-16 08:52:04.491  3487  3629 I Process : Sending signal. PID: 3487 SIG: 9
09-16 08:52:04.492  3528  5954 W SQLiteOpenHelper: Opened config.db in read-only mode
09-16 08:52:04.504  3336  5931 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-16 08:52:04.520  5933  5933 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
09-16 08:52:04.647   927  2875 W InputDispatcher: channel '19ffb42 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-16 08:52:04.647   927  2875 E InputDispatcher: channel '19ffb42 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-16 08:52:04.647   927  3725 I WindowState: WIN DEATH: Window{19ffb42 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-16 08:52:04.647   927   937 D GraphicsStats: Buffer count: 1
09-16 08:52:04.647   927  3725 W InputDispatcher: Attempted to unregister already unregistered input channel '19ffb42 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-16 08:52:04.653   927  3499 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3487) has died
09-16 08:52:04.654   927  3499 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-16 08:52:04.655   927  3499 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-16 08:52:04.670   927   940 I ActivityManager: Start proc 5968:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 08:52:04.705  5933  5933 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
09-16 08:52:04.715  5933  5981 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:52:04.718  5968  5968 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:52:04.719  5968  5968 D AndroidRuntime: Shutting down VM
09-16 08:52:04.724   927  3482 I ActivityManager: Start proc 5982:com.android.musicfx/u0a21 for broadcast com.android.musicfx/.Compatibility$Receiver
09-16 08:52:04.729  5968  5968 E AndroidRuntime: FATAL EXCEPTION: main
09-16 08:52:04.729  5968  5968 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5968
09-16 08:52:04.729  5968  5968 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 08:52:04.729  5968  5968 E AndroidRuntime: 	... 10 more
09-16 08:52:04.732   927   937 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 08:52:04.733  5968  5968 I Process : Sending signal. PID: 5968 SIG: 9
09-16 08:52:04.737   927  5994 E DropBoxManagerService: Can't write: system_app_crash
09-16 08:52:04.737   927  5994 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 08:52:04.737   927  5994 E DropBoxManagerService: 	... 5 more
09-16 08:52:04.755   927  3089 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5968) has died
09-16 08:52:04.756   927  3089 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-16 08:52:04.770   927   940 I ActivityManager: Start proc 5995:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:52:04.814  5995  5995 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:52:04.814  5995  5995 D AndroidRuntime: Shutting down VM
09-16 08:52:04.825  5995  5995 E AndroidRuntime: FATAL EXCEPTION: main
09-16 08:52:04.825  5995  5995 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5995
09-16 08:52:04.825  5995  5995 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 08:52:04.825  5995  5995 E AndroidRuntime: 	... 10 more
09-16 08:52:04.825   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
