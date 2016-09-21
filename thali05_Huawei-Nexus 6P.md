#### Test 85960304e9d96a8_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-21 07:07:08.197   930  5267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=184905, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-21 07:07:08.896  5514  5514 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 07:07:08.901  5514  5514 D AndroidRuntime: CheckJNI is OFF
09-21 07:07:08.933  5514  5514 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 07:07:08.981  5514  5514 I Radio-JNI: register_android_hardware_Radio DONE
09-21 07:07:08.996  5514  5514 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-21 07:07:09.013   930  3478 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-21 07:07:09.059   930  3478 I ActivityManager: Start proc 5523:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-21 07:07:09.073  5514  5514 D AndroidRuntime: Shutting down VM
,09-21 07:07:09.405   930  3784 I WindowManager: Screenshot max retries 4 of Token{e561af ActivityRecord{119d58e u0 com.test.thalitest/.MainActivity t2}} appWin=Window{f0866 u0 Starting com.test.thalitest} drawState=4
,09-21 07:07:09.507  5523  5523 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-21 07:07:09.545  5523  5523 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-21 07:07:09.571  5523  5523 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 6259-6279)
09-21 07:07:09.572  5523  5523 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-21 07:07:09.593  5523  5523 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f983dcd}
,09-21 07:07:09.594  5523  5523 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 07:07:09.594  5523  5523 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-21 07:07:09.600  5523  5523 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-21 07:07:09.601  5523  5523 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-21 07:07:09.637  5523  5523 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-21 07:07:09.650  5523  5523 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-21 07:07:09.650  5523  5523 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 07:07:09.650  5523  5523 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-21 07:07:09.650  5523  5523 I Adreno  : Build Date                       : 12/06/15
09-21 07:07:09.650  5523  5523 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-21 07:07:09.650  5523  5523 I Adreno  : Local Branch                     : mybranch17112971
09-21 07:07:09.650  5523  5523 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-21 07:07:09.650  5523  5523 I Adreno  : Remote Branch                    : NONE
09-21 07:07:09.650  5523  5523 I Adreno  : Reconstruct Branch               : NOTHING
,09-21 07:07:09.709   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16cbe3e:true
,09-21 07:07:09.744   953   953 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[13790]" dev="sockfs" ino=13790 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 07:07:09.744   953   953 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[13790]" dev="sockfs" ino=13790 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 07:07:09.757  5523  5523 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 07:07:09.766  5523  5523 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-21 07:07:09.794   405   405 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32178]" dev="sockfs" ino=32178 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 07:07:09.794   405   405 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32178]" dev="sockfs" ino=32178 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 07:07:09.797  5523  5560 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 07:07:09.800  3588  3588 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[13802]" dev="sockfs" ino=13802 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 07:07:09.800  3588  3588 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[13802]" dev="sockfs" ino=13802 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 07:07:09.804  5523  5547 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-21 07:07:09.829  5523  5560 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 07:07:09.907   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +498ms (total +879ms)
,09-21 07:07:09.930  5523  5523 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5523
,09-21 07:07:10.037  5523  5523 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 07:07:10.331  5523  5563 D jxcore_app_log: JniHelper::setJavaVM(0xf52fc000), pthread_self() = -586675920
,09-21 07:07:10.355  5523  5563 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 07:07:10.355  5523  5563 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 07:07:10.355  5523  5563 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 07:07:10.355  5523  5563 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 07:07:10.355  5523  5563 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-21 07:07:10.356  5523  5563 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@500ea9a added. We now have 1 listener(s)
,09-21 07:07:10.366  5523  5563 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-21 07:07:10.368  5523  5563 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 07:07:10.369  5523  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:10.370  5523  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-21 07:07:10.379  5523  5563 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a251ec1 added. We now have 1 listener(s)
09-21 07:07:10.379  5523  5563 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 07:07:10.386   930  3050 D WifiService: New client listening to asynchronous messages
,09-21 07:07:10.387  5523  5563 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 07:07:10.387  5523  5563 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 07:07:10.387  5523  5563 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-21 07:07:10.388  5523  5563 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 07:07:10.388  5523  5563 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-21 07:07:10.394  5523  5563 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:10.395  5523  5563 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-21 07:07:10.407  5523  5563 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-21 07:07:10.408  5523  5563 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:10.408  5523  5563 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:10.408  5523  5563 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:10.408  5523  5563 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:10.408  5523  5563 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:10.408  5523  5563 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:10.408  5523  5563 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 07:07:10.408  5523  5563 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 07:07:10.408  5523  5563 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 07:07:10.408  5523  5563 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 07:07:10.409  5523  5563 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 07:07:10.417  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:10.420  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:10.754  5523  5523 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 07:07:11.064  5523  5532 I art     : Background sticky concurrent mark sweep GC freed 76612(7MB) AllocSpace objects, 18(1604KB) LOS objects, 25% free, 24MB/32MB, paused 1.359ms total 192.345ms
,09-21 07:07:11.492  5523  5569 W jxcore-log: Initializing JXcore engine
09-21 07:07:11.492  5523  5569 W jxcore-log: JXcore engine is ready
,09-21 07:07:11.557  5569  5569 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12525 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-21 07:07:11.557  5569  5569 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13361]" dev="sockfs" ino=13361 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-21 07:07:11.557  5569  5569 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 07:07:11.557  5569  5569 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32143]" dev="sockfs" ino=32143 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-21 07:07:11.567  5523  5569 W jxcore-log: Starting JXcore engine
,09-21 07:07:11.626  5523  5569 W jxcore-log: Platform android
09-21 07:07:11.626  5523  5569 W jxcore-log: 
,09-21 07:07:11.626  5523  5569 W jxcore-log: Process ARCH arm
09-21 07:07:11.626  5523  5569 W jxcore-log: 
,09-21 07:07:11.723  5523  5569 I jxcore-log: JXcore Cordova bridge is ready!
09-21 07:07:11.723  5523  5569 I jxcore-log: 
,09-21 07:07:11.723  5523  5569 W jxcore-log: JXcore engine is started
,09-21 07:07:11.736  5523  5563 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 07:07:11.741  5523  5523 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 07:07:13.330   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 07:07:14.331   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 07:07:15.332   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 07:07:16.332   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 07:07:16.664   930  3051 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-21 07:07:17.333   570   570 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 07:07:18.206  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-21 07:07:18.206  5523  5569 I jxcore-log: 
,09-21 07:07:18.208  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-21 07:07:18.208  5523  5569 I jxcore-log: 
,09-21 07:07:18.212  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:18.212  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.212  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.212  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.212  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:18.212  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.212  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 07:07:18.212  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 07:07:18.214  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 07:07:18.216  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-21 07:07:18.216  5523  5569 I jxcore-log: 
,09-21 07:07:18.217  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-21 07:07:18.217  5523  5569 I jxcore-log: 
,09-21 07:07:18.334   570   570 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-21 07:07:18.554  5523  5569 D executeNativeTests: Running unit tests
,09-21 07:07:18.591  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 07:07:18.591  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e added. We now have 2 listener(s)
09-21 07:07:18.591  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 07:07:18.591  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-21 07:07:18.591  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:18.591  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:18.592  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df added. We now have 2 listener(s)
,09-21 07:07:18.592  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:18.592  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 07:07:18.593  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:18.596  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:18.596  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.596  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.596  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.596  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:18.596  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.596  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 07:07:18.596  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 07:07:18.596  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.597  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 07:07:18.598  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 07:07:18.598  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 07:07:18.598  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 07:07:18.599  5523  5569 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-21 07:07:18.599  5523  5569 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-21 07:07:18.599  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 07:07:18.599  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 07:07:18.599  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 07:07:18.599  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.599  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.599  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.599  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.599  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 07:07:18.599  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:18.599  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:18.600  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e removed from the list
09-21 07:07:18.600  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-21 07:07:18.600  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df removed from the list
,09-21 07:07:18.610  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:18.619  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.619  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.619  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 07:07:18.620  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.620  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.620  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-21 07:07:18.620  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.620  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-21 07:07:18.620  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.621  5523  5569 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-21 07:07:18.622  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 07:07:18.622  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.622  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.622  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.622  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.622  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.622  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.622  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.622  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
,09-21 07:07:18.622  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.622  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.622  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.622  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.622  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 07:07:18.623  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.623  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.623  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.623  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-21 07:07:18.625  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 07:07:18.627  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 07:07:18.628  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 07:07:18.628  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.628  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.628  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.628  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.628  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.628  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.628  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.628  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.628  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.628  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.628  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.628  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.628  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.628  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.629  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.629  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.629  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.629  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.629  5523  5569 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 07:07:18.630  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:18.632  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:18.632  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.632  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.632  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.632  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:18.632  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.632  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 07:07:18.632  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 07:07:18.633  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.633  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 07:07:18.633  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 07:07:18.633  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 07:07:18.633  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 07:07:18.633  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:18.633  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 07:07:18.635  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.637  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.637  5523  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 07:07:18.637  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 07:07:18.641  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 07:07:18.642  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 07:07:18.642  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 07:07:18.643  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-21 07:07:18.644  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-21 07:07:18.644  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 07:07:18.644  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 07:07:18.644  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 07:07:18.645  5523  5569 D BluetoothAdapter: STATE_ON
09-21 07:07:18.647  4560  4572 D BtGatt.GattService: registerClient() - UUID=a6d6e933-7a60-4e9c-8b40-764f787a8568
09-21 07:07:18.648  4560  4622 D BtGatt.GattService: onClientRegistered() - UUID=a6d6e933-7a60-4e9c-8b40-764f787a8568, clientIf=5
09-21 07:07:18.650  5523  5533 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 07:07:18.652  4560  4782 D BtGatt.GattService: start scan with filters
09-21 07:07:18.657  4560  4636 D BtGatt.ScanManager: handling starting scan
09-21 07:07:18.658  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 07:07:18.658  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 07:07:18.658  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 07:07:18.658  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 07:07:18.659  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:18.659  4560  4636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:18.659  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 07:07:18.659  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:18.660  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 07:07:18.661  5523  5569 I io.jxcore.node.ConnectionHelper: start: OK
09-21 07:07:18.662  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.662  5523  5569 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 07:07:18.662  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.662  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 07:07:18.662  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.662  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 07:07:18.662  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 07:07:18.662  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 07:07:18.663  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 07:07:18.663  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 07:07:18.663  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 07:07:18.663  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 07:07:18.663  5523  5569 D BluetoothAdapter: STATE_ON
09-21 07:07:18.664  4560  4572 D BtGatt.GattService: stopScan() - queue size =1
09-21 07:07:18.664  4560  4782 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 07:07:18.665  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 07:07:18.665  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 07:07:18.665  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 07:07:18.665  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 07:07:18.665  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 07:07:18.666  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:18.667  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 07:07:18.667  4560  4622 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 07:07:18.667  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.667  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 07:07:18.667  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 07:07:18.667  4560  4636 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 07:07:18.668  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:18.672  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.672  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:18.672  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.672  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:18.672  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:18.672  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:18.672  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.672  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.673  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.673  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.673  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.673  5523  5569 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 07:07:18.674  4560  4622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 07:07:18.674  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.675  4560  4636 D BtGatt.ScanManager: Starting BLE batch scan
09-21 07:07:18.675  4560  4636 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 07:07:18.675  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:18.679  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:18.679  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.679  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.679  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.679  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:18.679  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.679  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 07:07:18.679  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 07:07:18.682  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.682  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 07:07:18.682  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 07:07:18.682  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 07:07:18.682  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 07:07:18.682  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:18.683  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 07:07:18.683  4560  4622 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 07:07:18.683  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.685  5523  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 07:07:18.686  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 07:07:18.687  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.689  4560  4622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 07:07:18.689  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.691  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 07:07:18.691  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.691  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 07:07:18.691  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 07:07:18.695  4560  4622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 07:07:18.695  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.695  4560  4636 D BtGatt.ScanManager: stopping BLe Batch
09-21 07:07:18.697  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 07:07:18.697  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 07:07:18.697  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 07:07:18.698  5523  5569 D BluetoothAdapter: STATE_ON
09-21 07:07:18.699  4560  4782 D BtGatt.GattService: registerClient() - UUID=cb9bc52d-e141-4fe6-9ffe-a3fc11d1e78c
09-21 07:07:18.700  4560  4622 D BtGatt.GattService: onClientRegistered() - UUID=cb9bc52d-e141-4fe6-9ffe-a3fc11d1e78c, clientIf=5
09-21 07:07:18.700  5523  5534 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 07:07:18.701  4560  4572 D BtGatt.GattService: start scan with filters
09-21 07:07:18.702  4560  4622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 07:07:18.702  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.702  4560  4636 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 07:07:18.703  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 07:07:18.703  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 07:07:18.703  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State ,changed from [NOT_STARTED] to [SCANNING]
09-21 07:07:18.703  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 07:07:18.705  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:18.705  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 07:07:18.706  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:18.706  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 07:07:18.707  4560  4622 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 07:07:18.707  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.708  5523  5569 I io.jxcore.node.ConnectionHelper: start: OK
09-21 07:07:18.709  4560  4636 D BtGatt.ScanManager: handling starting scan
09-21 07:07:18.710  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 07:07:18.710  5523  5569 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 07:07:18.710  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.710  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 07:07:18.710  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.710  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 07:07:18.711  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 07:07:18.711  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 07:07:18.711  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-21 07:07:18.711  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 07:07:18.711  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 07:07:18.711  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 07:07:18.711  5523  5569 D BluetoothAdapter: STATE_ON
,09-21 07:07:18.712  4560  4572 D BtGatt.GattService: stopScan() - queue size =1
09-21 07:07:18.713  4560  4782 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 07:07:18.713  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 07:07:18.713  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 07:07:18.713  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 07:07:18.714  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 07:07:18.714  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-21 07:07:18.715  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:18.715  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 07:07:18.715  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 07:07:18.715  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 07:07:18.715  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:18.716  4560  4622 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 07:07:18.716  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:18.716  4560  4636 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-21 07:07:18.717  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:18.717  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.717  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.717  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-21 07:07:18.717  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:18.717  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:18.717  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.717  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.717  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.717  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
,09-21 07:07:18.717  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.718  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.718  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.719  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.719  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.719  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.719  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
,09-21 07:07:18.720  5523  5569 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 07:07:18.721  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:18.721  4560  4622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 07:07:18.721  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.722  4560  4636 D BtGatt.ScanManager: Starting BLE batch scan
09-21 07:07:18.722  4560  4636 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-21 07:07:18.725  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:18.725  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.725  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.725  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.725  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:18.725  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.725  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 07:07:18.725  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 07:07:18.728  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 07:07:18.728  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 07:07:18.728  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-21 07:07:18.728  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 07:07:18.728  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 07:07:18.728  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:18.728  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 07:07:18.731  4560  4622 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 07:07:18.731  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.731  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.731  5523  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 07:07:18.732  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 07:07:18.733  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:18.735  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 07:07:18.736  4560  4622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 07:07:18.736  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.736  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 07:07:18.736  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 07:07:18.741  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-21 07:07:18.741  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 07:07:18.741  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 07:07:18.742  5523  5569 D BluetoothAdapter: STATE_ON
09-21 07:07:18.742  4560  4622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 07:07:18.742  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:18.742  4560  4636 D BtGatt.ScanManager: stopping BLe Batch
09-21 07:07:18.744  4560  4575 D BtGatt.GattService: registerClient() - UUID=865da523-f2bf-49af-b21a-1cbe0fe2294c
,09-21 07:07:18.744  4560  4622 D BtGatt.GattService: onClientRegistered() - UUID=865da523-f2bf-49af-b21a-1cbe0fe2294c, clientIf=5
,09-21 07:07:18.744  5523  5533 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 07:07:18.745  4560  4572 D BtGatt.GattService: start scan with filters
09-21 07:07:18.747  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 07:07:18.748  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 07:07:18.748  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 07:07:18.748  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 07:07:18.748  4560  4622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 07:07:18.748  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:18.748  4560  4636 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-21 07:07:18.749  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:18.750  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 07:07:18.750  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 07:07:18.751  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 07:07:18.753  5523  5569 I io.jxcore.node.ConnectionHelper: start: OK
09-21 07:07:18.753  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 07:07:18.753  5523  5569 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 07:07:18.753  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.753  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 07:07:18.753  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.753  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 07:07:18.753  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 07:07:18.753  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 07:07:18.753  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 07:07:18.753  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-21 07:07:18.754  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 07:07:18.754  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 07:07:18.754  4560  4622 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 07:07:18.754  5523  5569 D BluetoothAdapter: STATE_ON
09-21 07:07:18.754  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.755  4560  4782 D BtGatt.GattService: stopScan() - queue size =0
09-21 07:07:18.755  4560  4575 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 07:07:18.756  4560  4636 D BtGatt.ScanManager: handling starting scan
,09-21 07:07:18.756  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 07:07:18.756  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 07:07:18.756  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-21 07:07:18.756  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 07:07:18.756  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 07:07:18.757  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:18.758  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 07:07:18.758  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 07:07:18.758  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 07:07:18.761  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:18.762  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-21 07:07:18.762  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:18.762  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.762  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:18.762  5523  5569 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 07:07:18.762  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.762  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.762  4560  4622 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 07:07:18.762  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.762  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.762  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.762  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:18.762  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.762  4560  4636 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 07:07:18.762  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.763  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.763  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.763  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.763  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.763  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.764  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.764  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.764  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.764  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.765  5523  5569 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-21 07:07:18.765  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.766  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.766  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-21 07:07:18.766  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.766  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.766  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.766  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.766  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.766  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.766  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.766  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.766  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.766  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.766  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.767  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.767  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.767  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-21 07:07:18.767  4560  4622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 07:07:18.767  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.767  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.767  4560  4636 D BtGatt.ScanManager: Starting BLE batch scan
09-21 07:07:18.767  4560  4636 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 07:07:18.768  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-21 07:07:18.768  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.769  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.769  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.769  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.769  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.769  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.769  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
,09-21 07:07:18.769  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.769  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.769  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.769  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.769  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.769  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.769  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.770  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.770  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.770  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.771  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.771  5523  5569 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-21 07:07:18.771  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.771  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.772  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.772  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.772  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.772  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.772  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.772  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.772  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.772  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.772  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.772  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 07:07:18.772  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.772  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.774  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.774  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.774  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.774  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.774  5523  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-21 07:07:18.775  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.775  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.775  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.775  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.775  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.775  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.775  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.775  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.775  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.775  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.775  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.775  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.775  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.775  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 07:07:18.776  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.776  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.776  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.777  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.777  4560  4622 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-21 07:07:18.777  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.777  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 07:07:18.777  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 07:07:18.777  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 07:07:18.777  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 07:07:18.777  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 07:07:18.778  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 07:07:18.778  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.778  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.778  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.778  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.778  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.778  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.778  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
,09-21 07:07:18.778  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.778  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.778  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.778  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.778  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.778  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.778  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.780  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.780  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.781  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.781  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
,09-21 07:07:18.784  4560  4622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 07:07:18.784  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:18.784  5523  5569 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-21 07:07:18.784  5523  5569 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-21 07:07:18.784  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-21 07:07:18.786  5523  5569 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-21 07:07:18.787  5523  5569 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-21 07:07:18.787  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-21 07:07:18.788  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-21 07:07:18.788  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 07:07:18.788  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 07:07:18.788  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 07:07:18.788  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-21 07:07:18.788  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-21 07:07:18.788  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 07:07:18.788  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 07:07:18.788  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 07:07:18.788  5523  5569 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-21 07:07:18.788  5523  5569 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-21 07:07:18.788  5523  5569 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-21 07:07:18.788  5523  5569 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 07:07:18.789  5523  5569 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-21 07:07:18.789  5523  5569 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-21 07:07:18.789  5523  5569 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-21 07:07:18.789  5523  5569 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-21 07:07:18.789  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-21 07:07:18.790  4560  4622 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 07:07:18.790  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.790  4560  4636 D BtGatt.ScanManager: stopping BLe Batch
09-21 07:07:18.792  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-21 07:07:18.793  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-21 07:07:18.793  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-21 07:07:18.794  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-21 07:07:18.794  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-21 07:07:18.794  5523  5569 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-21 07:07:18.794  5523  5569 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 07:07:18.794  5523  5569 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-21 07:07:18.794  5523  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-21 07:07:18.795  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.795  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.795  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.795  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.795  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.795  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.795  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-21 07:07:18.795  4560  4622 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 07:07:18.796  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.796  5523  5570 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 07:07:18.796  4560  4636 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 07:07:18.797  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.797  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.797  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.797  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.797  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.797  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.797  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.797  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.797  4790  4790 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28265]" dev="sockfs" ino=28265 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 07:07:18.797  4790  4790 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28265]" dev="sockfs" ino=28265 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 07:07:18.799  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.799  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.799  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.799  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.799  5523  5571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-21 07:07:18.7,99  5523  5571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-21 07:07:18.800  4560  4780 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
09-21 07:07:18.800  5523  5571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-21 07:07:18.800  5523  5569 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-21 07:07:18.800  5523  5570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-21 07:07:18.800  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.801  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.801  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.801  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.801  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.801  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.801  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.801  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.801  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.801  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.801  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.801  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.801  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.802  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.803  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.803  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.803  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.803  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.804  5523  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-21 07:07:18.804  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.804  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.804  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this ,operation, skipping...
09-21 07:07:18.804  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.804  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.804  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.804  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.805  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.805  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.805  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.805  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.805  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.805  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.805  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.806  4560  4622 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 07:07:18.806  4560  4622 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:18.806  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.806  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.806  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.806  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.807  5523  5569 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-21 07:07:18.807  5523  5569 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-21 07:07:18.807  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-21 07:07:18.807  5523  5569 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-21 07:07:18.807  5523  5569 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-21 07:07:18.808  5523  5569 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-21 07:07:18.808  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-21 07:07:18.808  5523  5569 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-21 07:07:18.808  5523  5569 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-21 07:07:18.808  5523  5569 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-21 07:07:18.808  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-21 07:07:18.808  5523  5569 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-21 07:07:18.808  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.808  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.809  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.809  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.809  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.809  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.809  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.809  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.809  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.809  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.809  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.809  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.809  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.809  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.811  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.811  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.811  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.811  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.811  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.812  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.812  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.812  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.812  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.812  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.812  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.812  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.812  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.812  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.812  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.812  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.813  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.813  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.813  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.813  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.813  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.813  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.813  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.813  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.813  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.813  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.814  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.814  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.814  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.814  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.814  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.814  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.814  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.815  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.815  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.815  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.815  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.816  5523  5569 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-21 07:07:18.817  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:18.817  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-21 07:07:18.818  5523  5569 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-21 07:07:18.818  5523  5569 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-21 07:07:18.818  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-21 07:07:18.818  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 07:07:18.818  5523  5523 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-21 07:07:18.819  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.819  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-21 07:07:18.819  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-21 07:07:18.819  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-21 07:07:18.819  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.819  5523  5569 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-21 07:07:18.819  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.819  5523  5523 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-21 07:07:18.819  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.819  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 07:07:18.819  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 07:07:18.819  5523  5572 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 07:07:18.819  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 07:07:18.820  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.820  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.817  4790  4790 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32939]" dev="sockfs" ino=32939 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 07:07:18.820  4790  4790 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32939]" dev="sockfs" ino=32939 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 07:07:18.821  5523  5572 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-21 07:07:18.822  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:18.822  5523  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-21 07:07:18.822  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.822  5523  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-21 07:07:18.822  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.822  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:18.822  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.822  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:18.822  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.822  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:18.822  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.822  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.822  5523  5523 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-21 07:07:18.822  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.822  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.822  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.822  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.822  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.823  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.823  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.823  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.823  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.824  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.824  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.824  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.824  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.825  5523  5569 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-21 07:07:18.825  5523  5569 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-21 07:07:18.825  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 07:07:18.825  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 07:07:18.825  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.825  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.825  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.826  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.826  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.826  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.826  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.826  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.826  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.826  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.826  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.826  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.826  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.826  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.827  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.827  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.827  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.827  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.830  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.830  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.830  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.830  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.830  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.830  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.830  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.831  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.831  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.831  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.831  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.831  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.831  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.831  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.832  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.832  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.832  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.832  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.833  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:18.833  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:18.833  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:18.833  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:18.833  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.833  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.833  5523  5569 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aadd07e not in the list
09-21 07:07:18.833  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.833  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.833  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:18.833  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.833  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.833  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:18.833  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:18.834  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:18.834  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:18.834  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:18.835  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc59df not in the list
09-21 07:07:18.835  5523  5569 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-21 07:07:18.835  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-21 07:07:18.835  5523  5569 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-21 07:07:18.836  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-21 07:07:18.836  5523  5569 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-21 07:07:18.836  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-21 07:07:18.837  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-21 07:07:18.837  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-21 07:07:18.837  5523  5569 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-21 07:07:18.837  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-21 07:07:18.837  5523  5569 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-21 07:07:18.837  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-21 07:07:18.837  5523  5569 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-21 07:07:18.837  5523  5569 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-21 07:07:18.838  5523  5569 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-21 07:07:18.838  5523  5569 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-21 07:07:18.838  5523  5569 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-21 07:07:18.838  5523  5569 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-21 07:07:18.838  5523  5569 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-21 07:07:18.838  5523  5569 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-21 07:07:18.839  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:18.839  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc97ba9 added. We now have 2 listener(s)
09-21 07:07:18.839  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:18.840  5523  5569 D BluetoothAdapter: enable(): BT is already enabled..!
09-21 07:07:18.840   930  3588 D WifiService: setWifiEnabled: true pid=5523, uid=10077
09-21 07:07:18.840   930  3588 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 07:07:18.841  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:18.841  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2d552e added. We now have 3 listener(s)
09-21 07:07:18.841  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:18.844  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:18.844  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d578cf added. We now have 4 listener(s)
09-21 07:07:18.844  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:18.845  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:18.845  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8cdb25c added. We now have 5 listener(s)
09-21 07:07:18.845  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:18.847   930  3478 D WifiService: setWifiEnabled: false pid=5523, uid=10077
09-21 07:07:18.847   930  3478 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-21 07:07:18.849   930  3049 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-21 07:07:18.849   930  3049 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-21 07:07:18.849   930  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-21 07:07:18.849   930  3049 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-21 07:07:18.852  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:18.852  4560  4617 D BluetoothAdapterState: Current state: ON, message: 23
09-21 07:07:18.852  4560  4617 D BluetoothAdapterProperties: Setting state to 13
09-21 07:07:18.852  4560  4617 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-21 07:07:18.852  4560  4617 D BluetoothAdapterProperties: onBluetoothDisable()
09-21 07:07:18.854  4560  4617 I BluetoothAdapterState: Entering PendingCommandState
09-21 07:07:18.854  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.855  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:18.855  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.855  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.855  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.855  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:18.855  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.855  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 07:07:18.855  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 07:07:18.855  4560  4560 D BluetoothMapService: onReceive
09-21 07:07:18.855  4560  4560 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-21 07:07:18.855  4560  4560 D BluetoothMapService: STATE_TURNING_OFF
09-21 07:07:18.855  4560  4560 D BluetoothMapService: MAP Service closeService in
09-21 07:07:18.855  4560  4560 D BluetoothMapMasInstance0: MAP Service shutdown
09-21 07:07:18.855  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.855  4560  4560 D ObexServerSockets0: shutdown(block = true)
09-21 07:07:18.855  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.856  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 07:07:18.856  4560  4560 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 07:07:18.856  4560  4560 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 07:07:18.856  4560  4792 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-21 07:07:18.856  4560  4793 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-21 07:07:18.857  4560  4780 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-21 07:07:18.858   509   922 D CommandListener: Clearing all IP addresses on wlan0
09-21 07:07:18.858   930  5268 D DhcpClient: Clearing IP address
09-21 07:07:18.860  4560  4560 I BtOppRfcommListener: stopping Accept Thread
09-21 07:07:18.860  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.860  4560  5208 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-21 07:07:18.860  4560  5208 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-21 07:07:18.862  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.864  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.864  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:18.864  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.864  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.864  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.864  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:18.864  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.864  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 07:07:18.864  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 07:07:18.865  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.865  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 07:07:18.865   509   922 D CommandListener: Setting iface cfg
09-21 07:07:18.866  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.867  3684  5329 V NativeCrypto: Read error: ssl=0x7fa300e400: I/O error during system call, Connection timed out
09-21 07:07:18.868  3684  5329 V NativeCrypto: SSL shutdown failed: ssl=0x7fa300e400: I/O error during system call, Broken pipe
09-21 07:07:18.870   930  3225 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-21 07:07:18.870   930  5266 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-21 07:07:18.872   930  5266 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-21 07:07:18.872   930  3051 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-21 07:07:18.873   930  3051 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-21 07:07:18.874   930  3051 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-21 07:07:18.883   930   943 I ActivityManager: Start proc 5575:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-21 07:07:18.884  4560  4622 D BluetoothAdapterProperties: Scan Mode:20
09-21 07:07:18.884  4560  4617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-21 07:07:18.885   930  3051 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-21 07:07:18.885   930  3051 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-21 07:07:18.892  4560  4560 D HeadsetService: Received stop request...Stopping profile...
09-21 07:07:18.892  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.892  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:18.892  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.892  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.892  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.892  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:18.892  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:18.892  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:18.892  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 07:07:18.892   567   567 E Parcel  : Reading a NULL string not supported here.
,09-21 07:07:18.893  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.893  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:18.893   930   930 D RttService: SCAN_AVAILABLE : 1
09-21 07:07:18.893   930  3156 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-21 07:07:18.895  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.895  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:18.895  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.895  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.895  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.895  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:18.895  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:18.895  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:18.895  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 07:07:18.896  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 07:07:18.896  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:18.897   930  3051 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-21 07:07:18.898   930   930 D BluetoothHeadset: Proxy object disconnected
09-21 07:07:18.899  3587  3610 D BluetoothHeadset: Proxy object disconnected
09-21 07:07:18.899   930  3049 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-21 07:07:18.900  3552  3697 W QCNEJ   : |CORE| network lost: 100
09-21 07:07:18.900  4560  4560 D A2dpService: Received stop request...Stopping profile...
09-21 07:07:18.900  3552  3697 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-21 07:07:18.903  4560  4785 D A2dpStateMachine: Exit Disconnected: -1
09-21 07:07:18.903   930  5269 D DhcpClient: Receive thread stopped
09-21 07:07:18.903   930   930 D BluetoothHeadset: Proxy object disconnected
09-21 07:07:18.903  3190  3807 D BluetoothHeadset: Proxy object disconnected
09-21 07:07:18.903   930   930 D BluetoothHeadset: Proxy object disconnected
,09-21 07:07:18.906   930   930 D BluetoothA2dp: Proxy object disconnected
09-21 07:07:18.907  4560  4560 D HidService: Received stop request...Stopping profile...
09-21 07:07:18.907  4560  4560 D HidService: Stopping Bluetooth HidService
09-21 07:07:18.908  4560  4560 D HealthService: Received stop request...Stopping profile...
09-21 07:07:18.909  3190  3190 D HeadsetProfile: Bluetooth service disconnected
09-21 07:07:18.909  3190  3190 D BluetoothA2dp: Proxy object disconnected
09-21 07:07:18.909  3190  3190 D BluetoothInputDevice: Proxy object disconnected
09-21 07:07:18.909  3190  3190 D HidProfile: Bluetooth service disconnected
09-21 07:07:18.909  4560  4560 D PanService: Received stop request...Stopping profile...
,09-21 07:07:18.910   930  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-21 07:07:18.914  4560  4560 D BluetoothMapService: Received stop request...Stopping profile...
09-21 07:07:18.914  4560  4560 D BluetoothMapService: stop()
,09-21 07:07:18.914  4560  4560 D BluetoothMapAppObserver: deinitObservers()
09-21 07:07:18.914  4560  4560 D BluetoothMapAppObserver: removeReceiver()
09-21 07:07:18.916  4560  4560 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:18.916  4560  4560 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:18.916  4560  4560 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:18.917  4560  4560 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 07:07:18.917  4560  4560 D SapService: Received stop request...Stopping profile...
,09-21 07:07:18.917  4560  4560 V SapService: stop()
09-21 07:07:18.920  4560  4560 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-21 07:07:18.920  4560  4560 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-21 07:07:18.921  4560  4560 V BluetoothAdapterState: isTurningOff()=true
,09-21 07:07:18.921  4560  4560 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:18.921  4560  4560 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:18.921  4560  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:18.921  4560  4560 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:18.921  4560  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:18.921  4560  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:18.921  4560  4622 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-21 07:07:18.922  4560  4622 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-21 07:07:18.922  4560  4622 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-21 07:07:18.922  4560  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:18.922  4560  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:18.922  4560  4560 V BluetoothAdapterState: isTurningOff()=true
,09-21 07:07:18.922  4560  4560 V BluetoothAdapterState: isTurningOn()=false
,09-21 07:07:18.922  4560  4773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 07:07:18.922  4560  4560 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 07:07:18.922  4560  4773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-21 07:07:18.922  4560  4560 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:18.922  4560  4773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 07:07:18.923  4560  4773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 07:07:18.923  4560  4560 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-21 07:07:18.923  4560  4560 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-21 07:07:18.923  4560  4622 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-21 07:07:18.923  4560  4560 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:18.923  4560  4560 V BluetoothAdapterState: isTurningOn()=false
,09-21 07:07:18.923  4560  4560 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:18.923  4560  4560 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:18.923  4560  4560 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-21 07:07:18.923  4560  4622 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-21 07:07:18.924  4560  4560 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-21 07:07:18.924  4560  4560 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:18.924  4560  4560 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:18.924  4560  4560 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:18.924  4560  4560 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:18.924  4560  4560 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-21 07:07:18.925  4560  4560 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-21 07:07:18.926  4560  4560 D BluetoothMapService: MAP Service closeService in
,09-21 07:07:18.926  4560  4560 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:18.926  4560  4560 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:18.926  4560  4560 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:18.926  4560  4560 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:18.927  4560  4560 D BluetoothMapService: cleanup()
09-21 07:07:18.927  4560  4560 D BluetoothMapService: MAP Service closeService in
09-21 07:07:18.927  4560  4560 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:18.927  4560  4560 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:18.928  4560  4560 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 07:07:18.928  4560  4560 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:18.928  4560  4617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-21 07:07:18.928  4560  4617 D BluetoothAdapterProperties: Setting state to 15
09-21 07:07:18.928  4560  4617 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-21 07:07:18.928   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 07:07:18.929  3587  3848 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:18.929  3190  3208 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-21 07:07:18.929  3190  3190 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-21 07:07:18.929  3190  3190 D PanProfile: Bluetooth service disconnected
09-21 07:07:18.929  3190  3190 D BluetoothMap: Proxy object disconnected
09-21 07:07:18.929  3190  3190 D MapProfile: Bluetooth service disconnected
,09-21 07:07:18.930   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-21 07:07:18.930  3190  3202 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:18.930  4560  4617 I BluetoothAdapterState: Entering BleOnState
09-21 07:07:18.931  3190  3807 D BluetoothPan: onBluetoothStateChange on: false
09-21 07:07:18.931   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:18.931   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:18.931  3190  3208 D BluetoothPbap: onBluetoothStateChange: up=false
09-21 07:07:18.932  3190  3202 D BluetoothMap: onBluetoothStateChange: up=false
09-21 07:07:18.933  3190  3807 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 07:07:18.934   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:18.934  4560  4617 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-21 07:07:18.935  4560  4617 D BluetoothAdapterProperties: Setting state to 16
,09-21 07:07:18.935  4560  4617 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-21 07:07:18.935  4560  4617 D BluetoothAdapterProperties: onBleDisable
09-21 07:07:18.936  4560  4617 I BluetoothAdapterState: Entering PendingCommandState
09-21 07:07:18.936  4560  4618 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-21 07:07:18.937  4560  4622 D BluetoothAdapterProperties: Scan Mode:20
09-21 07:07:18.937  5575  5575 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-21 07:07:18.937  4560  4773 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-21 07:07:18.937  4560  4773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:18.939  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.939  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:18.939  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.939  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.939  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.939  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:18.939  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:18.939  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:18.939  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:18.942  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.942  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:18.942  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.942  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.942  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:18.942  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:18.942  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:18.942  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:18.942  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:18.944  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.946  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.948   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-21 07:07:18.948   509   922 D CommandListener: Clearing all IP addresses on wlan0
,09-21 07:07:18.951   930  3051 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-21 07:07:18.951   930  3051 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-21 07:07:18.952   509   922 D TetherController: Setting IP forward enable = 0
09-21 07:07:18.954   930  3049 D DhcpClient: doQuit
09-21 07:07:18.954   930  3049 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 07:07:18.954   930   947 D Tethering: MasterInitialState.processMessage what=3
09-21 07:07:18.955  3721  3721 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-21 07:07:18.955   930  5268 D DhcpClient: onQuitting
,09-21 07:07:18.959  4325  4325 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d110789 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-21 07:07:18.961  4899  4899 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-21 07:07:18.961  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.961  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:18.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:18.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:18.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:18.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:18.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:18.962  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.962  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:18.964  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:18.964  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:18.964  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:18.964  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:18.964  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:18.964  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:18.964  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:18.964  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:18.964  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:18.963  4973  4988 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-21 07:07:18.965  4973  4988 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-21 07:07:18.965  4973  4988 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-21 07:07:18.965  4973  4988 E SarControlService: no key has been found,reset the power
09-21 07:07:18.965  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 07:07:18.965  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:18.965  4973  5012 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-21 07:07:18.965  4973  5012 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-21 07:07:18.965  4973  5012 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-21 07:07:18.966  5002  5002 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-21 07:07:18.966  5002  5002 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-21 07:07:18.967  4973  5012 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-21 07:07:18.967  4973  5012 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-21 07:07:18.967  4973  5012 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-21 07:07:18.967  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:18.969  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:18.969  5002  5002 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-21 07:07:18.969  5002  5002 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-21 07:07:18.972  5002  5016 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@eb24cf7 HexData = [00000000ea03000000000000ffffffff]
09-21 07:07:18.972  5002  5016 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-21 07:07:18.972  5002  5016 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-21 07:07:18.973  5002  5002 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-21 07:07:18.973  4973  4984 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-21 07:07:18.973  3721  3721 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-21 07:07:18.976  5002  5016 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@eb24cf7 HexData = [00000000eb03000000000000ffffffff]
09-21 07:07:18.976  5002  5016 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-21 07:07:18.976  5002  5016 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-21 07:07:18.977  5002  5002 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-21 07:07:18.977  4973  4985 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-21 07:07:18.979  3721  3721 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-21 07:07:18.981   509   915 W SocketClient: write error (Broken pipe)
,09-21 07:07:18.981   509   915 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-21 07:07:18.981   509   915 W SocketListener: Error sending broadcast (Broken pipe)
,09-21 07:07:18.983  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-21 07:07:18.990   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7b68b26:true
,09-21 07:07:18.991  3684  3684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 07:07:19.004   509   922 E Netd    : netlink response contains error (No such file or directory)
09-21 07:07:19.005   509   922 D TetherController: Setting IP forward enable = 0
,09-21 07:07:19.005   930  3051 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-21 07:07:19.007   930  3278 I ActivityManager: Start proc 5605:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-21 07:07:19.010  3721  3721 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-21 07:07:19.025  5575  5575 D LocalBluetoothProfileManager: Adding local MAP profile
,09-21 07:07:19.027  3721  3721 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-21 07:07:19.033  5575  5575 D BluetoothMap: Create BluetoothMap proxy object
,09-21 07:07:19.044  5575  5575 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-21 07:07:19.053  5605  5605 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-21 07:07:19.064  5575  5575 D DockEventReceiver: finishStartingService: stopping service
,09-21 07:07:19.068   930  3785 I ActivityManager: Killing 4947:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-21 07:07:19.130  4372  4372 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-21 07:07:19.130   930  3049 D wifi    : In wifi stop Hal
09-21 07:07:19.130   930  3049 D wifi    : halHandle = 0x7f911238c0, mVM = 0x7facecd140, mCls = 0x100b32
09-21 07:07:19.130   930  3718 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-21 07:07:19.130   930  3718 D WifiHAL : Got a signal to exit!!!
09-21 07:07:19.130   930  3718 I WifiHAL : Exit wifi_event_loop
,09-21 07:07:19.131   930  3049 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-21 07:07:19.131   930  3049 E WifiHAL : Event processing terminated
09-21 07:07:19.131   930  3049 D wifi    : In wifi cleaned up handler
,09-21 07:07:19.131   930  3049 I WifiHAL : Internal cleanup completed
09-21 07:07:19.132  3710  4122 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 07:07:19.134  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:19.135  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:19.147  4560  4622 I bt_hci  : shut_down
,09-21 07:07:19.149  4560  4641 D bt_hwcfg: hw_epilog_process
,09-21 07:07:19.150  4560  4641 I bt_vendor: low_power_mode_cb
,09-21 07:07:19.152  4560  4641 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-21 07:07:19.152  4560  4641 I bt_vendor: epilog_cb
09-21 07:07:19.152  4560  4641 I bt_hci  : epilog_finished_callback
,09-21 07:07:19.153   930  3718 D wifi    : set interface wlan0 flags (DOWN)
09-21 07:07:19.154   930  3049 D WifiNative-HAL: HAL event thread stopped successfully
,09-21 07:07:19.156  4560  4622 I bt_hci_h4: hal_close
09-21 07:07:19.156  4560  4622 I bt_userial_vendor: device fd = 54 close
,09-21 07:07:19.252  5605  5605 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.File.exists(File.java:361)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-21 07:07:19.252  5605  5605 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 07:07:19.252  5605  5605 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 07:07:19.252  5605  5605 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.e.b(PG:170)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 07:07:19.252  5605  5605 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.k.d(PG:583)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.e.b(PG:170)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 07:07:19.252  5605  5605 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.io.File.exists(File.java:361)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 07:07:19.252  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 07:07:19.253  5605  5605 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at java.io.File.exists(File.java:361)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 07:07:19.253  5605  5605 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 07:07:19.253  5605  5605 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 07:07:19.266  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 07:07:19.267  4560  4618 D bt_stack_manager: event_shut_down_stack finished.
09-21 07:07:19.267  4560  4617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-21 07:07:19.269  4560  4560 D BtGatt.DebugUtils: handleDebugAction() action=null
09-21 07:07:19.270  4560  4560 D BtGatt.GattService: Received stop request...Stopping profile...
09-21 07:07:19.270  4560  4560 D BtGatt.GattService: stop()
09-21 07:07:19.270  4560  4560 D BtGatt.AdvertiseManager: advertise clients cleared
09-21 07:07:19.270  4560  4617 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-21 07:07:19.272  4560  4560 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:19.272  4560  4560 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:19.272  4560  4560 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:19.272  4560  4560 V BluetoothAdapterState: isBleTurningOff()=true
09-21 07:07:19.273  4560  4617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-21 07:07:19.273  4560  4617 D BluetoothAdapterProperties: Setting state to 10
09-21 07:07:19.273  4560  4617 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-21 07:07:19.273  4560  4617 I BluetoothAdapterState: Entering OffState
09-21 07:07:19.274  5575  5575 D DockEventReceiver: finishStartingService: stopping service
09-21 07:07:19.274   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-21 07:07:19.274  3684  3684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 07:07:19.276   930  3605 I ActivityManager: Killing 4325:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-21 07:07:19.323  5523  5523 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 07:07:19.356   930   947 D Tethering: InitialState.processMessage what=4
,09-21 07:07:19.359   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-21 07:07:19.358  4560  4560 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-21 07:07:19.359  4560  4560 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-21 07:07:19.360  4560  4560 I BluetoothServiceJni: cleanupNative: return from cleanup
09-21 07:07:19.360  4560  4618 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-21 07:07:19.371  3993  3993 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-21 07:07:19.376  3993  3993 D SystemUpdateService: onCreate
09-21 07:07:19.376  4560  4618 D bt_stack_manager: event_clean_up_stack finished.
,09-21 07:07:19.379  3993  3993 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-21 07:07:19.391  4560  4560 I art     : System.exit called, status: 0
,09-21 07:07:19.391  4560  4560 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-21 07:07:19.399  3993  3993 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-21 07:07:19.401  3993  5294 I iu.UploadsManager: num queued entries: 0
09-21 07:07:19.401  3993  5294 I iu.UploadsManager: num updated entries: 0
09-21 07:07:19.402  3993  5294 I iu.SyncManager: NEXT; no task
,09-21 07:07:19.412  3993  3993 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-21 07:07:19.414  3993  3993 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-21 07:07:19.416  5297  5297 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-21 07:07:19.421  5297  5297 D SprintDMHelper: simOperator: 
09-21 07:07:19.421  5297  5297 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-21 07:07:19.433  4372  5642 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-21 07:07:19.438  3993  5640 I SystemUpdateService: active receiver: enabled
,09-21 07:07:19.450   930  3785 I ActivityManager: Start proc 5643:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-21 07:07:19.451   930  3588 I ActivityManager: Process com.android.bluetooth (pid 4560) has died
,09-21 07:07:19.454  3993  5640 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-21 07:07:19.467  3993  5640 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,09-21 07:07:19.471  3993  5640 I SystemUpdateService: now status is 0 (complete)
,09-21 07:07:19.471  3993  5640 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-21 07:07:19.471  3993  5640 I SystemUpdateService: file has been verified
09-21 07:07:19.472  3993  5640 I SystemUpdateService: OTA package size = 21989297
,09-21 07:07:19.485  5643  5643 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-21 07:07:19.496  3993  5640 I SystemUpdateService: showing system update notification
,09-21 07:07:19.513  3993  3993 D SystemUpdateService: onDestroy
,09-21 07:07:19.515   930  3784 I ActivityManager: Killing 4644:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-21 07:07:19.619  5605  5633 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-21 07:07:19.631   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c1b796b:true
,09-21 07:07:21.857   930  3641 D WifiService: setWifiEnabled: true pid=5523, uid=10077
,09-21 07:07:21.857   930  3641 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 07:07:21.867   509   922 D SoftapController: Softap fwReload - Ok
,09-21 07:07:21.872   509   922 D CommandListener: Setting iface cfg
,09-21 07:07:21.872   509   922 D CommandListener: Trying to bring down wlan0
,09-21 07:07:21.876   509   922 D CommandListener: Clearing all IP addresses on wlan0
,09-21 07:07:21.880   930  3049 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 07:07:22.485   930  3049 D wifi    : set interface wlan0 flags (UP)
,09-21 07:07:22.489   930  3049 I WifiHAL : Initializing wifi
,09-21 07:07:22.489   930  3049 I WifiHAL : Creating socket
09-21 07:07:22.495   930  3049 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-21 07:07:22.495   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-21 07:07:22.495   930  3049 D wifi    : Did set static halHandle = 0x7f911238c0
,09-21 07:07:22.495   930  3049 D wifi    : halHandle = 0x7f911238c0, mVM = 0x7facecd140, mCls = 0x1017ea
09-21 07:07:22.495   930  3049 D wifi    : array field set
09-21 07:07:22.496   930  3049 I WifiNative-HAL: interface[0] = wlan0
09-21 07:07:22.498   930  5660 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547894737088
,09-21 07:07:22.498   930  5660 D wifi    : waitForHalEvents called, vm = 0x7facecd140, obj = 0x1017ea, env = 0x7f92caa480
,09-21 07:07:22.565  5661  5661 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-21 07:07:22.587  5661  5661 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 07:07:22.599   930  3049 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-21 07:07:22.606  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:22.611  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:22.636  5661  5661 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 07:07:22.636  5661  5661 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-21 07:07:22.651   930  3049 D WifiConfigStore: Loading config and enabling all networks 
,09-21 07:07:22.652  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:22.652  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:22.652  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:22.652  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:22.652  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:22.652  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:22.652  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:22.652  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:22.652  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:22.652  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:22.652  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:22.653  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:22.653  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:22.653  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:22.653  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:22.653  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:22.653  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:22.653  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:22.653  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:22.653  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:22.654  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:22.654  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 07:07:22.661   930  3049 D WifiConfigStore: loaded 0 passpoint configs
,09-21 07:07:22.661   930  3049 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-21 07:07:22.662   930  3049 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-21 07:07:22.662   930  3049 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-21 07:07:22.663   930  3049 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-21 07:07:22.664   930  3049 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-21 07:07:22.664   930  3049 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-21 07:07:22.664   930  3049 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-21 07:07:22.667   930  3049 D WifiNative-HAL: Setting external_sim to 1
,09-21 07:07:22.667  4372  4372 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-21 07:07:22.668   930  3049 D wifi    : setting dfs flag to true, 0x7f92fdf6e0
,09-21 07:07:22.668   930  3049 D WifiStateMachine: Setting OUI to DA-A1-19
09-21 07:07:22.668   930  3049 D wifi    : setting scan oui 0x7f92fdf6e0
09-21 07:07:22.668   930  3049 D WifiHAL : Sending mac address OUI
,09-21 07:07:22.672   930  3049 E native  : do suspend false
,09-21 07:07:22.679   930  3049 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-21 07:07:22.679   930   930 D RttService: SCAN_AVAILABLE : 3
09-21 07:07:22.680   509   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-21 07:07:22.680   930  3156 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-21 07:07:22.681   509   922 D CommandListener: Setting iface cfg
,09-21 07:07:22.685   930  3048 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-21 07:07:22.685   930  3048 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-21 07:07:22.694   930  3048 D WifiNative-HAL: p2pGetDeviceAddress
,09-21 07:07:22.694   930  3048 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-21 07:07:22.699   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=199408 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-21 07:07:24.865   930  3511 D WifiService: setWifiEnabled: false pid=5523, uid=10077
09-21 07:07:24.865   930  3511 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 07:07:24.872   930   930 D RttService: SCAN_AVAILABLE : 1
,09-21 07:07:24.872   930  3156 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-21 07:07:24.885   930  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-21 07:07:24.885   509   922 D CommandListener: Clearing all IP addresses on wlan0
,09-21 07:07:24.893   930  3049 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 07:07:24.895  5661  5661 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-21 07:07:24.901  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:24.901  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:24.901  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:24.901  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:24.901  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:24.901  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:24.901  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:24.901  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:24.901  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:24.901  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:24.901  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 07:07:24.903  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:24.904  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:24.904  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:24.904  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:24.904  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:24.904  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:24.904  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:24.904  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:24.904  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:24.904  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:24.904  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 07:07:24.910  5661  5661 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-21 07:07:24.916  5661  5661 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-21 07:07:24.918  5661  5661 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-21 07:07:25.022   930  3049 D wifi    : In wifi stop Hal
,09-21 07:07:25.022   930  3049 D wifi    : halHandle = 0x7f911238c0, mVM = 0x7facecd140, mCls = 0x1017ea
,09-21 07:07:25.023   930  5660 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-21 07:07:25.023   930  5660 D WifiHAL : Got a signal to exit!!!
09-21 07:07:25.023   930  5660 I WifiHAL : Exit wifi_event_loop
09-21 07:07:25.024   930  3049 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-21 07:07:25.024  4372  4372 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 07:07:25.025   930  3049 E WifiHAL : Event processing terminated
09-21 07:07:25.026   930  3049 D wifi    : In wifi cleaned up handler
09-21 07:07:25.026   930  3049 I WifiHAL : Internal cleanup completed
09-21 07:07:25.032  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:25.033  3710  4122 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 07:07:25.034  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:25.050   930  5660 D wifi    : set interface wlan0 flags (DOWN)
,09-21 07:07:25.050   930  3049 D WifiNative-HAL: HAL event thread stopped successfully
,09-21 07:07:25.256   930   947 D Tethering: InitialState.processMessage what=4
,09-21 07:07:25.262   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-21 07:07:27.908   930   947 I ActivityManager: Start proc 5665:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-21 07:07:28.006  5665  5665 D AdapterServiceConfig: Adding HeadsetService
,09-21 07:07:28.006  5665  5665 D AdapterServiceConfig: Adding A2dpService
09-21 07:07:28.006  5665  5665 D AdapterServiceConfig: Adding HidService
09-21 07:07:28.007  5665  5665 D AdapterServiceConfig: Adding HealthService
09-21 07:07:28.007  5665  5665 D AdapterServiceConfig: Adding PanService
09-21 07:07:28.007  5665  5665 D AdapterServiceConfig: Adding GattService
,09-21 07:07:28.007  5665  5665 D AdapterServiceConfig: Adding BluetoothMapService
09-21 07:07:28.007  5665  5665 D AdapterServiceConfig: Adding SapService
,09-21 07:07:28.021   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@463a7f8:true
,09-21 07:07:28.022  5665  5665 D BluetoothAdapterState: make() - Creating AdapterState
,09-21 07:07:28.025  5665  5665 I bt_bluedroid: init
09-21 07:07:28.026  5665  5677 I BluetoothAdapterState: Entering OffState
09-21 07:07:28.029  5665  5678 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-21 07:07:28.029  5665  5678 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-21 07:07:28.029  5665  5678 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-21 07:07:28.030  5665  5678 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-21 07:07:28.030  5665  5665 I bt_bluedroid: get_profile_interface socket
09-21 07:07:28.032  5665  5665 I bt_bluedroid: get_profile_interface sdp
09-21 07:07:28.032  5665  5681 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-21 07:07:28.033  5665  5681 D BluetoothAdapterProperties: Name is: Nexus 6P
09-21 07:07:28.038  5665  5676 I bt_bluedroid: config_hci_snoop_log
09-21 07:07:28.039   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-21 07:07:28.043  5665  5677 D BluetoothAdapterState: Current state: OFF, message: 0
09-21 07:07:28.043  5665  5677 D BluetoothAdapterProperties: Setting state to 14
09-21 07:07:28.043  5665  5677 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-21 07:07:28.045  5665  5677 D BluetoothBondStateMachine: make
09-21 07:07:28.047  5665  5682 I BluetoothBondStateMachine: StableState(): Entering Off State
09-21 07:07:28.049  5665  5677 I BluetoothAdapterState: Entering PendingCommandState
09-21 07:07:28.050  5665  5665 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-21 07:07:28.052  5665  5665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:28.053  5665  5665 D BtGatt.DebugUtils: handleDebugAction() action=null
09-21 07:07:28.054  5665  5665 D BtGatt.GattService: Received start request. Starting profile...
09-21 07:07:28.054  5665  5665 D BtGatt.GattService: start()
09-21 07:07:28.054  5665  5665 I bt_bluedroid: get_profile_interface gatt
09-21 07:07:28.055  5665  5665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:28.055  5665  5665 D BtGatt.AdvertiseManager: advertise manager created
09-21 07:07:28.061  5665  5665 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:28.061  5665  5665 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:28.061  5665  5665 V BluetoothAdapterState: isBleTurningOn()=true
09-21 07:07:28.061  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:28.062  5665  5677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-21 07:07:28.063  5665  5677 I bt_bluedroid: bt_bluedroid
09-21 07:07:28.063  5665  5678 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-21 07:07:28.063  5665  5678 I bt_hci  : start_up
09-21 07:07:28.069  5665  5678 I bt_vendor: alloc value 0xf3fbd871
09-21 07:07:28.069  5665  5678 I bt_vendor: init
09-21 07:07:28.069  5665  5678 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-21 07:07:28.069  5665  5678 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-21 07:07:28.181  5665  5678 D bt_hci  : start_up starting async portion
,09-21 07:07:28.182  5665  5685 I bt_hci  : event_finish_startup
09-21 07:07:28.182  5665  5685 I bt_hci_h4: hal_open
09-21 07:07:28.182  5665  5685 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-21 07:07:28.185  5665  5685 I bt_userial_vendor: device fd = 54 open
,09-21 07:07:28.180  5686  5686 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 07:07:28.199  5665  5685 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 07:07:28.202  5665  5685 D bt_hwcfg: Chipset BCM4358A3
,09-21 07:07:28.202  5665  5685 D bt_hwcfg: Target name = [BCM4358A3]
09-21 07:07:28.202  5665  5685 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-21 07:07:28.606  5665  5685 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-21 07:07:28.606  5665  5685 D bt_hwcfg: Settlement delay -- 100 ms
09-21 07:07:28.606  5665  5685 I bt_hwcfg: Setting fw settlement delay to 100 
,09-21 07:07:28.742  5665  5685 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 07:07:28.742  5665  5685 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-21 07:07:28.743  5665  5685 I bt_hwcfg: vendor lib fwcfg completed
09-21 07:07:28.744  5665  5685 I bt_vendor: firmware callback
09-21 07:07:28.744  5665  5685 I bt_hci  : firmware_config_callback
,09-21 07:07:28.754  5665  5688 I bt_btu  : btu_task pending for preload complete event
09-21 07:07:28.754  5665  5688 I bt_btu_task: Bluetooth chip preload is complete
,09-21 07:07:28.755  5665  5688 I bt_btu  : btu_task received preload complete event
,09-21 07:07:28.760  5665  5688 I         : BTE_InitTraceLevels -- TRC_HCI
,09-21 07:07:28.760  5665  5688 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-21 07:07:28.760  5665  5688 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_AVDT
09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_AVRC
09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_A2D
,09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_BNEP
09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_BTM
09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_GAP
09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_PAN
09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_SDP
09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_GATT
09-21 07:07:28.761  5665  5688 I         : BTE_InitTraceLevels -- TRC_SMP
09-21 07:07:28.762  5665  5688 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-21 07:07:28.762  5665  5688 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-21 07:07:28.845  5665  5688 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f3b549
09-21 07:07:28.845  5665  5688 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f3b549 
,09-21 07:07:28.864  5665  5681 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-21 07:07:28.866  5665  5681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-21 07:07:28.866  5665  5681 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-21 07:07:28.868  5665  5681 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 07:07:28.870  5665  5681 D BluetoothAdapterProperties: Scan Mode:20
09-21 07:07:28.870  5665  5681 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 07:07:28.870  5665  5681 D bt_hci  : do_postload posting postload work item
09-21 07:07:28.870  5665  5685 I bt_hci  : event_postload
,09-21 07:07:28.870  5665  5685 I bt_vendor: sco_config_cb
,09-21 07:07:28.870  5665  5685 I bt_hci  : sco_config_callback postload finished.
09-21 07:07:28.873  5665  5681 D bt_bte_conf: Device ID record 1 : primary
,09-21 07:07:28.873  5665  5681 D bt_bte_conf:   vendorId            = 000f
09-21 07:07:28.873  5665  5681 D bt_bte_conf:   vendorIdSource      = 0001
09-21 07:07:28.873  5665  5681 D bt_bte_conf:   product             = 1200
09-21 07:07:28.873  5665  5681 D bt_bte_conf:   version             = 1436
,09-21 07:07:28.873  5665  5681 D bt_bte_conf:   clientExecutableURL = 
09-21 07:07:28.873  5665  5681 D bt_bte_conf:   serviceDescription  = 
,09-21 07:07:28.873  5665  5681 D bt_bte_conf:   documentationURL    = 
09-21 07:07:28.874  5665  5681 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-21 07:07:28.874  5665  5678 D bt_stack_manager: event_start_up_stack finished
,09-21 07:07:28.874  5665  5677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-21 07:07:28.875  5665  5677 D BluetoothAdapterProperties: Setting state to 15
09-21 07:07:28.875  5665  5677 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-21 07:07:28.876  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:28.876  5665  5677 I BluetoothAdapterState: Entering BleOnState
09-21 07:07:28.879  5665  5685 I bt_vendor: low_power_mode_cb
09-21 07:07:28.880  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:28.882  5665  5677 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-21 07:07:28.883  5665  5677 D BluetoothAdapterProperties: Setting state to 11
09-21 07:07:28.883  5665  5677 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-21 07:07:28.889  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:28.891  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:28.892  5665  5665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:28.893  5665  5665 D HeadsetService: Received start request. Starting profile...
,09-21 07:07:28.895  5665  5665 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-21 07:07:28.896  5665  5665 D HeadsetStateMachine: make
,09-21 07:07:28.905  5665  5677 I BluetoothAdapterState: Entering PendingCommandState
,09-21 07:07:28.908  5665  5665 D HeadsetStateMachine: max_hf_connections = 1
09-21 07:07:28.909  5665  5665 I bt_bluedroid: get_profile_interface handsfree
,09-21 07:07:28.909  5665  5681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-21 07:07:28.909  5665  5681 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-21 07:07:28.912  5665  5665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
,09-21 07:07:28.913  5665  5665 D A2dpService: Received start request. Starting profile...
09-21 07:07:28.913  5665  5665 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-21 07:07:28.914  5665  5665 I bt_bluedroid: get_profile_interface avrcp
,09-21 07:07:28.919  5665  5665 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-21 07:07:28.919  5665  5665 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-21 07:07:28.919  5665  5665 D A2dpStateMachine: make
,09-21 07:07:28.920  5665  5665 I bt_bluedroid: get_profile_interface a2dp
09-21 07:07:28.921  5665  5681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-21 07:07:28.923  5665  5698 D A2dpStateMachine: Enter Disconnected: -2
,09-21 07:07:28.923  5665  5665 I BluetoothHidServiceJni: classInitNative: succeeds
09-21 07:07:28.924  5665  5665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
,09-21 07:07:28.925  5665  5665 D HidService: Received start request. Starting profile...
,09-21 07:07:28.925  5665  5665 I bt_bluedroid: get_profile_interface hidhost
09-21 07:07:28.925  5665  5665 D HidService: setHidService(): set to: null
09-21 07:07:28.925  5665  5681 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f1c56d
,09-21 07:07:28.926  5665  5681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-21 07:07:28.926  5575  5575 D BluetoothInputDevice: Proxy object connected
09-21 07:07:28.926  5575  5575 D HidProfile: Bluetooth service connected
09-21 07:07:28.926  5665  5665 I BluetoothHealthServiceJni: classInitNative: succeeds
09-21 07:07:28.927  5665  5665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:28.928  5665  5665 D HealthService: Received start request. Starting profile...
,09-21 07:07:28.928  3684  3684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 07:07:28.929  5665  5665 I bt_bluedroid: get_profile_interface health
09-21 07:07:28.930  5665  5665 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-21 07:07:28.931  5665  5665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
,09-21 07:07:28.932  5575  5575 D BluetoothPan: BluetoothPAN Proxy object connected
09-21 07:07:28.933  5575  5575 D PanProfile: Bluetooth service connected
,09-21 07:07:28.933  5665  5665 D PanService: Received start request. Starting profile...
09-21 07:07:28.933  5665  5665 D BluetoothPanServiceJni: initializeNative(L110): pan
09-21 07:07:28.933  5665  5665 I bt_bluedroid: get_profile_interface pan
09-21 07:07:28.934  5665  5681 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-21 07:07:28.936  5665  5665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
,09-21 07:07:28.937  5575  5575 D BluetoothMap: Proxy object connected
09-21 07:07:28.937  5665  5665 D BluetoothMapService: Received start request. Starting profile...
09-21 07:07:28.937  5665  5665 D BluetoothMapService: start()
09-21 07:07:28.938  5575  5575 D MapProfile: Bluetooth service connected
09-21 07:07:28.939  5575  5575 D BluetoothMap: getConnectedDevices()
09-21 07:07:28.939  5575  5575 D BluetoothMap: Bluetooth is Not enabled
,09-21 07:07:28.940  5665  5665 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-21 07:07:28.941  5665  5665 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-21 07:07:28.941  5665  5665 D BluetoothMapAppObserver: createReceiver()
09-21 07:07:28.942  5665  5665 D BluetoothMapAppObserver: initObservers()
,09-21 07:07:28.942  5665  5665 D BluetoothMapAppObserver: getEnabledAccountItems()
09-21 07:07:28.947  5665  5665 V SapService: SapBinder()
09-21 07:07:28.947  5665  5665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
,09-21 07:07:28.948  5665  5665 D SapService: Received start request. Starting profile...
,09-21 07:07:28.948  5665  5665 V SapService: start()
09-21 07:07:28.950  5665  5665 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:28.950  5665  5665 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:28.950  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:28.950  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:28.950  5665  5665 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:28.950  5665  5665 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:28.950  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:28.950  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:28.951  5665  5696 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-21 07:07:28.951  5665  5665 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:28.951  5665  5665 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:28.951  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:28.951  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:28.951  5665  5665 V BluetoothAdapterState: isTurningOff()=false
,09-21 07:07:28.951  5665  5665 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:28.952  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:28.953  5665  5665 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:28.953  5665  5665 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:28.953  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:28.953  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 07:07:28.954  5665  5677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-21 07:07:28.954  5665  5677 D BluetoothAdapterProperties: ScanMode =  20
09-21 07:07:28.954  5665  5677 D BluetoothAdapterProperties: State =  11
09-21 07:07:28.954  5665  5677 D BluetoothAdapterProperties: Setting state to 12
09-21 07:07:28.954  5665  5677 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-21 07:07:28.955   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-21 07:07:28.955  5665  5677 I BluetoothAdapterState: Entering OnState
,09-21 07:07:28.955  5665  5681 D BluetoothAdapterProperties: Scan Mode:21
09-21 07:07:28.955  5665  5681 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 07:07:28.956  3587  3615 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 07:07:28.957  3190  3807 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-21 07:07:28.957   930   930 D BluetoothA2dp: Proxy object connected
09-21 07:07:28.958  3190  3190 D BluetoothInputDevice: Proxy object connected
09-21 07:07:28.958  3190  3190 D HidProfile: Bluetooth service connected
09-21 07:07:28.958  5575  5585 D BluetoothMap: onBluetoothStateChange: up=true
,09-21 07:07:28.959  5575  5587 D BluetoothPan: onBluetoothStateChange on: true
,09-21 07:07:28.959  3190  3208 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-21 07:07:28.960  3190  3807 D BluetoothPan: onBluetoothStateChange on: true
09-21 07:07:28.961  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:28.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:28.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:28.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:28.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:28.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:28.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:28.961  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:28.962   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 07:07:28.962  3190  3190 D BluetoothPan: BluetoothPAN Proxy object connected
09-21 07:07:28.962  3190  3190 D PanProfile: Bluetooth service connected
09-21 07:07:28.962   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 07:07:28.962  3190  3208 D BluetoothPbap: onBluetoothStateChange: up=true
09-21 07:07:28.962  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:28.963  5575  5585 D BluetoothPbap: onBluetoothStateChange: up=true
,09-21 07:07:28.965  3190  3202 D BluetoothMap: onBluetoothStateChange: up=true
09-21 07:07:28.965  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:28.965  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:28.965  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:28.965  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:28.965  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:28.965  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:28.965  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:28.965  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:28.966  3190  3190 D BluetoothMap: Proxy object connected
09-21 07:07:28.966  3190  3208 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 07:07:28.966  3190  3190 D MapProfile: Bluetooth service connected
09-21 07:07:28.966  3190  3190 D BluetoothMap: getConnectedDevices()
09-21 07:07:28.967  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:28.968  5665  5665 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-21 07:07:28.968  5575  5587 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-21 07:07:28.968   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 07:07:28.968  3190  3190 D BluetoothA2dp: Proxy object connected
09-21 07:07:28.968  5665  5665 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-21 07:07:28.969   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
09-21 07:07:28.971  5665  5665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 07:07:28.972  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:28.973  5575  5575 D LocalBluetoothProfileManager: Adding local A2DP profile
09-21 07:07:28.974  5665  5665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 07:07:28.975  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:28.976  5665  5665 D ObexServerSockets: Succeed to create listening sockets 
09-21 07:07:28.976  5665  5665 D ObexServerSockets0: startAccept()
09-21 07:07:28.976  5665  5665 D ObexServerSockets0: prepareForNewConnect()
09-21 07:07:28.978  5665  5665 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-21 07:07:28.978  5665  5665 D BluetoothSdpJni: SDP Create record success - handle: 0
09-21 07:07:28.979  5575  5575 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-21 07:07:28.979  5665  5665 D BluetoothMapService: onReceive
09-21 07:07:28.979  5665  5705 D ObexServerSockets0: Accepting socket connection...
09-21 07:07:28.979  5665  5665 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-21 07:07:28.979  5665  5665 D BluetoothMapService: STATE_ON
09-21 07:07:28.980  5665  5706 D ObexServerSockets0: Accepting socket connection...
09-21 07:07:28.982  5665  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 07:07:28.983  5665  5707 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-21 07:07:28.983  5665  5707 D BluetoothSdpJni: SDP Create record success - handle: 1
09-21 07:07:28.986  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 07:07:28.988  5575  5575 D BluetoothA2dp: Proxy object connected
09-21 07:07:28.993  3684  3684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 07:07:28.994  5575  5575 D DockEventReceiver: finishStartingService: stopping service
09-21 07:07:29.000  3190  3190 D BluetoothPbap: Proxy object connected
09-21 07:07:29.000  3190  3190 D PbapServerProfile: Bluetooth service connected
09-21 07:07:29.000  5575  5575 D BluetoothPbap: Proxy object connected
09-21 07:07:29.001  5575  5575 D PbapServerProfile: Bluetooth service connected
09-21 07:07:29.007  5665  5665 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-21 07:07:29.008  5665  5665 D ObexServerSockets0: prepareForNewConnect()
09-21 07:07:29.010  5665  5711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 07:07:29.023  5665  5715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 07:07:29.025  5665  5715 I BtOppRfcommListener: Accept thread started.
,09-21 07:07:29.057   930   930 D BluetoothHeadset: Proxy object connected
,09-21 07:07:29.058  3587  3854 D BluetoothHeadset: Proxy object connected
09-21 07:07:29.058   930   930 D BluetoothHeadset: Proxy object connected
,09-21 07:07:29.058  3190  3208 D BluetoothHeadset: Proxy object connected
09-21 07:07:29.059  3190  3190 D HeadsetProfile: Bluetooth service connected
09-21 07:07:29.059   930   930 D BluetoothHeadset: Proxy object connected
09-21 07:07:29.060  3190  3202 D BluetoothHeadset: Proxy object connected
09-21 07:07:29.061  3190  3190 D HeadsetProfile: Bluetooth service connected
,09-21 07:07:29.061   930   947 D BluetoothHeadset: Proxy object connected
09-21 07:07:29.061   930   947 D BluetoothHeadset: Proxy object connected
,09-21 07:07:29.069   930   947 D BluetoothHeadset: Proxy object connected
,09-21 07:07:29.082  5575  5587 D BluetoothHeadset: Proxy object connected
,09-21 07:07:29.083  5575  5575 D HeadsetProfile: Bluetooth service connected
,09-21 07:07:30.883  5665  5677 D BluetoothAdapterState: Current state: ON, message: 23
,09-21 07:07:30.883  5665  5677 D BluetoothAdapterProperties: Setting state to 13
,09-21 07:07:30.883  5665  5677 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-21 07:07:30.885  5665  5677 D BluetoothAdapterProperties: onBluetoothDisable()
09-21 07:07:30.886  5665  5677 I BluetoothAdapterState: Entering PendingCommandState
09-21 07:07:30.889  5665  5665 D BluetoothMapService: onReceive
09-21 07:07:30.889  5665  5665 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-21 07:07:30.890  5665  5665 D BluetoothMapService: STATE_TURNING_OFF
,09-21 07:07:30.890  5665  5665 D BluetoothMapService: MAP Service closeService in
09-21 07:07:30.891  5665  5665 D BluetoothMapMasInstance0: MAP Service shutdown
09-21 07:07:30.891  5665  5665 D ObexServerSockets0: shutdown(block = true)
09-21 07:07:30.893  5665  5665 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 07:07:30.893  5665  5665 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 07:07:30.893  5665  5706 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-21 07:07:30.895  5665  5705 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-21 07:07:30.895  5665  5692 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-21 07:07:30.895  5665  5681 D BluetoothAdapterProperties: Scan Mode:20
09-21 07:07:30.895  5665  5677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-21 07:07:30.901  5665  5665 I BtOppRfcommListener: stopping Accept Thread
09-21 07:07:30.901  5665  5715 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-21 07:07:30.902  5665  5715 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-21 07:07:30.902  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:30.902  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:30.902  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:30.902  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:30.902  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:30.902  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:30.902  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:30.902  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:30.902  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:30.903  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:30.903  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:30.903  5665  5665 D HeadsetService: Received stop request...Stopping profile...
09-21 07:07:30.904  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 07:07:30.906   930   930 D BluetoothHeadset: Proxy object disconnected
09-21 07:07:30.906  3587  3848 D BluetoothHeadset: Proxy object disconnected
09-21 07:07:30.906   930   930 D BluetoothHeadset: Proxy object disconnected
09-21 07:07:30.907  5665  5665 D A2dpService: Received stop request...Stopping profile...
09-21 07:07:30.907  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:30.907  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:30.907  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:30.907  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:30.907  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:30.907  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 07:07:30.907  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:30.907  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:30.907  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 07:07:30.907  5665  5698 D A2dpStateMachine: Exit Disconnected: -1
09-21 07:07:30.909  5523  5523 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 07:07:30.909  5575  5585 D BluetoothHeadset: Proxy object disconnected
09-21 07:07:30.909  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 07:07:30.909  3190  3208 D BluetoothHeadset: Proxy object disconnected
,09-21 07:07:30.910   930   930 D BluetoothHeadset: Proxy object disconnected
09-21 07:07:30.910   930   930 D BluetoothA2dp: Proxy object disconnected
09-21 07:07:30.911  5665  5665 D HidService: Received stop request...Stopping profile...
09-21 07:07:30.911  5665  5665 D HidService: Stopping Bluetooth HidService
09-21 07:07:30.913  5665  5665 D HealthService: Received stop request...Stopping profile...
09-21 07:07:30.914  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:30.915  5665  5665 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:30.915  5665  5665 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:30.915  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:30.915  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:30.916  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:30.917  5665  5665 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-21 07:07:30.917  5665  5665 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-21 07:07:30.917  5665  5681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-21 07:07:30.917  5665  5688 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:30.917  5665  5688 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:30.917  5665  5665 V BluetoothAdapterState: isTurningOff()=true
,09-21 07:07:30.917  5665  5688 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-21 07:07:30.917  5665  5665 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:30.917  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:30.917  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:30.919  5665  5681 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-21 07:07:30.918  5665  5665 D PanService: Received stop request...Stopping profile...
09-21 07:07:30.923  5665  5665 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:30.923  5665  5665 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:30.923  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 07:07:30.923  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 07:07:30.923  5665  5681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-21 07:07:30.923  5665  5688 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:30.923  5665  5688 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:30.923  5665  5688 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 07:07:30.923  5665  5688 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 07:07:30.923  5575  5575 D DockEventReceiver: finishStartingService: stopping service
09-21 07:07:30.923  5665  5688 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 07:07:30.923  5665  5688 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 07:07:30.924  5575  5575 D HeadsetProfile: Bluetooth service disconnected
09-21 07:07:30.925  5575  5575 D BluetoothA2dp: Proxy object disconnected
09-21 07:07:30.925  5575  5575 D BluetoothInputDevice: Proxy object disconnected
09-21 07:07:30.926  5575  5575 D HidProfile: Bluetooth service disconnected
09-21 07:07:30.926  5575  5575 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-21 07:07:30.926  5575  5575 D PanProfile: Bluetooth service disconnected
09-21 07:07:30.926  5665  5665 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-21 07:07:30.926  5665  5665 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-21 07:07:30.926  5665  5681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-21 07:07:30.927  5665  5665 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:30.927  5665  5665 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:30.927  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:30.927  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:30.928  3684  3684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 07:07:30.928  5665  5665 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-21 07:07:30.928  5665  5681 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-21 07:07:30.929  5665  5665 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-21 07:07:30.929  3190  3190 D BluetoothA2dp: Proxy object disconnected
09-21 07:07:30.929  3190  3190 D HeadsetProfile: Bluetooth service disconnected
09-21 07:07:30.929  3190  3190 D BluetoothInputDevice: Proxy object disconnected
09-21 07:07:30.929  3190  3190 D HidProfile: Bluetooth service disconnected
09-21 07:07:30.930  3190  3190 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-21 07:07:30.930  3190  3190 D PanProfile: Bluetooth service disconnected
09-21 07:07:30.931  5665  5665 D BluetoothMapService: Received stop request...Stopping profile...
09-21 07:07:30.931  5665  5665 D BluetoothMapService: stop()
09-21 07:07:30.932  5665  5665 D BluetoothMapAppObserver: deinitObservers()
09-21 07:07:30.932  5665  5665 D BluetoothMapAppObserver: removeReceiver()
09-21 07:07:30.933  3190  3190 D BluetoothMap: Proxy object disconnected
09-21 07:07:30.933  3190  3190 D MapProfile: Bluetooth service disconnected
,09-21 07:07:30.933  5575  5575 D BluetoothMap: Proxy object disconnected
09-21 07:07:30.933  5575  5575 D MapProfile: Bluetooth service disconnected
09-21 07:07:30.935  5665  5665 D SapService: Received stop request...Stopping profile...
09-21 07:07:30.935  5665  5665 V SapService: stop()
09-21 07:07:30.936  5665  5665 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:30.936  5665  5665 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:30.936  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:30.936  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:30.936  5665  5665 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-21 07:07:30.936  5665  5665 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-21 07:07:30.938  3190  3190 D BluetoothPbap: Proxy object disconnected
09-21 07:07:30.938  3190  3190 D PbapServerProfile: Bluetooth service disconnected
,09-21 07:07:30.939  5665  5665 D BluetoothMapService: MAP Service closeService in
09-21 07:07:30.939  5665  5665 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:30.939  5665  5665 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:30.939  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 07:07:30.939  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:30.939  5665  5665 D BluetoothMapService: cleanup()
09-21 07:07:30.939  5665  5665 D BluetoothMapService: MAP Service closeService in
09-21 07:07:30.939  5665  5665 V BluetoothAdapterState: isTurningOff()=true
09-21 07:07:30.939  5665  5665 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:30.939  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:30.940  5665  5665 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:30.940  5665  5677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-21 07:07:30.940  5665  5677 D BluetoothAdapterProperties: Setting state to 15
09-21 07:07:30.940  5665  5677 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-21 07:07:30.940   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 07:07:30.941  5665  5677 I BluetoothAdapterState: Entering BleOnState
,09-21 07:07:30.941  5575  5718 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 07:07:30.942  5575  5587 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:30.942  3587  3610 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:30.942  3190  3202 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-21 07:07:30.943  5575  5585 D BluetoothMap: onBluetoothStateChange: up=false
,09-21 07:07:30.943  5575  5718 D BluetoothPan: onBluetoothStateChange on: false
09-21 07:07:30.944  3190  3807 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:30.944  3190  3208 D BluetoothPan: onBluetoothStateChange on: false
09-21 07:07:30.945   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:30.945   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 07:07:30.945  3190  3202 D BluetoothPbap: onBluetoothStateChange: up=false
09-21 07:07:30.945  5575  5587 D BluetoothPbap: onBluetoothStateChange: up=false
09-21 07:07:30.947  3190  3807 D BluetoothMap: onBluetoothStateChange: up=false
09-21 07:07:30.949  3190  3202 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 07:07:30.950  5575  5585 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-21 07:07:30.950   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-21 07:07:30.951  5665  5677 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-21 07:07:30.951  5665  5677 D BluetoothAdapterProperties: Setting state to 16
09-21 07:07:30.951  5665  5677 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-21 07:07:30.951  5575  5575 D BluetoothPbap: Proxy object disconnected
09-21 07:07:30.951  5575  5575 D PbapServerProfile: Bluetooth service disconnected
09-21 07:07:30.953  5665  5677 D BluetoothAdapterProperties: onBleDisable
09-21 07:07:30.953  5665  5678 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-21 07:07:30.953  5665  5677 I BluetoothAdapterState: Entering PendingCommandState
09-21 07:07:30.953  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:30.953  5665  5681 D BluetoothAdapterProperties: Scan Mode:20
09-21 07:07:30.955  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 07:07:30.955  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:30.955  5665  5688 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-21 07:07:30.955  5665  5688 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 07:07:30.956  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:30.957  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:30.960  3684  3684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 07:07:30.964  5575  5575 D DockEventReceiver: finishStartingService: stopping service
,09-21 07:07:31.160  5665  5681 I bt_hci  : shut_down
,09-21 07:07:31.164  5665  5685 D bt_hwcfg: hw_epilog_process
,09-21 07:07:31.164  5665  5685 I bt_vendor: low_power_mode_cb
,09-21 07:07:31.166  5665  5685 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-21 07:07:31.167  5665  5685 I bt_vendor: epilog_cb
09-21 07:07:31.167  5665  5685 I bt_hci  : epilog_finished_callback
,09-21 07:07:31.168  5665  5681 I bt_hci_h4: hal_close
09-21 07:07:31.169  5665  5681 I bt_userial_vendor: device fd = 54 close
,09-21 07:07:31.286  5665  5678 D bt_stack_manager: event_shut_down_stack finished.
,09-21 07:07:31.287  5665  5677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-21 07:07:31.291  5665  5677 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-21 07:07:31.291  5665  5665 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-21 07:07:31.292  5665  5665 D BtGatt.GattService: Received stop request...Stopping profile...
,09-21 07:07:31.292  5665  5665 D BtGatt.GattService: stop()
09-21 07:07:31.293  5665  5665 D BtGatt.AdvertiseManager: advertise clients cleared
,09-21 07:07:31.296  5665  5665 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:31.297  5665  5665 V BluetoothAdapterState: isTurningOn()=false
,09-21 07:07:31.297  5665  5665 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 07:07:31.297  5665  5665 V BluetoothAdapterState: isBleTurningOff()=true
09-21 07:07:31.297  5665  5677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-21 07:07:31.297  5665  5677 D BluetoothAdapterProperties: Setting state to 10
,09-21 07:07:31.298  5665  5677 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-21 07:07:31.299  5665  5677 I BluetoothAdapterState: Entering OffState
09-21 07:07:31.299   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-21 07:07:31.313  5665  5665 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-21 07:07:31.313  5665  5665 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-21 07:07:31.314  5665  5665 I BluetoothServiceJni: cleanupNative: return from cleanup
09-21 07:07:31.317  5665  5678 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-21 07:07:31.324  5665  5665 I art     : System.exit called, status: 0
,09-21 07:07:31.324  5665  5665 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-21 07:07:31.356   930  3784 I ActivityManager: Process com.android.bluetooth (pid 5665) has died
,09-21 07:07:33.882  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
,09-21 07:07:33.882  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 07:07:36.889  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:36.889  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bd963a added. We now have 6 listener(s)
,09-21 07:07:36.890  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 07:07:36.894  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:36.894  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@65ad2eb added. We now have 7 listener(s)
,09-21 07:07:36.894  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 07:07:36.896  5523  5569 I System.out: IsBluetoothEnabled
,09-21 07:07:36.903  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:36.925   930   947 I ActivityManager: Start proc 5724:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-21 07:07:37.007  5724  5724 D AdapterServiceConfig: Adding HeadsetService
,09-21 07:07:37.008  5724  5724 D AdapterServiceConfig: Adding A2dpService
09-21 07:07:37.008  5724  5724 D AdapterServiceConfig: Adding HidService
09-21 07:07:37.008  5724  5724 D AdapterServiceConfig: Adding HealthService
09-21 07:07:37.008  5724  5724 D AdapterServiceConfig: Adding PanService
09-21 07:07:37.008  5724  5724 D AdapterServiceConfig: Adding GattService
09-21 07:07:37.008  5724  5724 D AdapterServiceConfig: Adding BluetoothMapService
,09-21 07:07:37.009  5724  5724 D AdapterServiceConfig: Adding SapService
,09-21 07:07:37.019   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4dbaa91:true
,09-21 07:07:37.019  5724  5724 D BluetoothAdapterState: make() - Creating AdapterState
,09-21 07:07:37.022  5724  5724 I bt_bluedroid: init
,09-21 07:07:37.022  5724  5736 I BluetoothAdapterState: Entering OffState
,09-21 07:07:37.024  5724  5737 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-21 07:07:37.024  5724  5737 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-21 07:07:37.024  5724  5737 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-21 07:07:37.024  5724  5737 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-21 07:07:37.025  5724  5724 I bt_bluedroid: get_profile_interface socket
,09-21 07:07:37.026  5724  5740 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-21 07:07:37.027  5724  5724 I bt_bluedroid: get_profile_interface sdp
,09-21 07:07:37.028  5724  5740 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 07:07:37.032  5724  5735 I bt_bluedroid: config_hci_snoop_log
,09-21 07:07:37.033   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-21 07:07:37.038  5724  5736 D BluetoothAdapterState: Current state: OFF, message: 0
,09-21 07:07:37.038  5724  5736 D BluetoothAdapterProperties: Setting state to 14
09-21 07:07:37.038  5724  5736 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-21 07:07:37.040  5724  5736 D BluetoothBondStateMachine: make
,09-21 07:07:37.041  5724  5741 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-21 07:07:37.044  5724  5736 I BluetoothAdapterState: Entering PendingCommandState
,09-21 07:07:37.045  5724  5724 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-21 07:07:37.047  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:37.048  5724  5724 D BtGatt.DebugUtils: handleDebugAction() action=null
09-21 07:07:37.049  5724  5724 D BtGatt.GattService: Received start request. Starting profile...
09-21 07:07:37.049  5724  5724 D BtGatt.GattService: start()
09-21 07:07:37.049  5724  5724 I bt_bluedroid: get_profile_interface gatt
09-21 07:07:37.050  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:37.050  5724  5724 D BtGatt.AdvertiseManager: advertise manager created
,09-21 07:07:37.055  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:37.055  5724  5724 V BluetoothAdapterState: isTurningOn()=false
09-21 07:07:37.055  5724  5724 V BluetoothAdapterState: isBleTurningOn()=true
09-21 07:07:37.055  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:37.055  5724  5736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-21 07:07:37.056  5724  5736 I bt_bluedroid: bt_bluedroid
,09-21 07:07:37.057  5724  5737 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-21 07:07:37.057  5724  5737 I bt_hci  : start_up
,09-21 07:07:37.062  5724  5737 I bt_vendor: alloc value 0xf3fbd871
,09-21 07:07:37.062  5724  5737 I bt_vendor: init
09-21 07:07:37.062  5724  5737 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-21 07:07:37.063  5724  5737 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-21 07:07:37.174  5724  5737 D bt_hci  : start_up starting async portion
,09-21 07:07:37.174  5724  5744 I bt_hci  : event_finish_startup
09-21 07:07:37.174  5724  5744 I bt_hci_h4: hal_open
09-21 07:07:37.174  5724  5744 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-21 07:07:37.176  5724  5744 I bt_userial_vendor: device fd = 54 open
,09-21 07:07:37.174  5745  5745 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 07:07:37.190  5724  5744 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 07:07:37.193  5724  5744 D bt_hwcfg: Chipset BCM4358A3
,09-21 07:07:37.193  5724  5744 D bt_hwcfg: Target name = [BCM4358A3]
,09-21 07:07:37.193  5724  5744 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-21 07:07:37.589  5724  5744 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-21 07:07:37.589  5724  5744 D bt_hwcfg: Settlement delay -- 100 ms
,09-21 07:07:37.589  5724  5744 I bt_hwcfg: Setting fw settlement delay to 100 
,09-21 07:07:37.723  5724  5744 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-21 07:07:37.724  5724  5744 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-21 07:07:37.725  5724  5744 I bt_hwcfg: vendor lib fwcfg completed
09-21 07:07:37.725  5724  5744 I bt_vendor: firmware callback
09-21 07:07:37.725  5724  5744 I bt_hci  : firmware_config_callback
,09-21 07:07:37.733  5724  5747 I bt_btu  : btu_task pending for preload complete event
09-21 07:07:37.734  5724  5747 I bt_btu_task: Bluetooth chip preload is complete
,09-21 07:07:37.734  5724  5747 I bt_btu  : btu_task received preload complete event
,09-21 07:07:37.742  5724  5747 I         : BTE_InitTraceLevels -- TRC_HCI
,09-21 07:07:37.742  5724  5747 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-21 07:07:37.742  5724  5747 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-21 07:07:37.742  5724  5747 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-21 07:07:37.743  5724  5747 I         : BTE_InitTraceLevels -- TRC_AVRC
09-21 07:07:37.743  5724  5747 I         : BTE_InitTraceLevels -- TRC_A2D
09-21 07:07:37.743  5724  5747 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-21 07:07:37.743  5724  5747 I         : BTE_InitTraceLevels -- TRC_BTM
09-21 07:07:37.743  5724  5747 I         : BTE_InitTraceLevels -- TRC_GAP
09-21 07:07:37.743  5724  5747 I         : BTE_InitTraceLevels -- TRC_PAN
09-21 07:07:37.743  5724  5747 I         : BTE_InitTraceLevels -- TRC_SDP
,09-21 07:07:37.743  5724  5747 I         : BTE_InitTraceLevels -- TRC_GATT
09-21 07:07:37.744  5724  5747 I         : BTE_InitTraceLevels -- TRC_SMP
09-21 07:07:37.744  5724  5747 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-21 07:07:37.744  5724  5747 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-21 07:07:37.830  5724  5747 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f3b549
,09-21 07:07:37.830  5724  5747 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f3b549 
,09-21 07:07:37.843  5724  5740 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-21 07:07:37.844  5724  5740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-21 07:07:37.845  5724  5740 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-21 07:07:37.847  5724  5740 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 07:07:37.851  5724  5740 D BluetoothAdapterProperties: Scan Mode:20
09-21 07:07:37.851  5724  5740 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 07:07:37.852  5724  5740 D bt_hci  : do_postload posting postload work item
09-21 07:07:37.852  5724  5744 I bt_hci  : event_postload
09-21 07:07:37.852  5724  5744 I bt_vendor: sco_config_cb
09-21 07:07:37.852  5724  5744 I bt_hci  : sco_config_callback postload finished.
09-21 07:07:37.856  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:37.859  5724  5740 D bt_bte_conf: Device ID record 1 : primary
,09-21 07:07:37.859  5724  5744 I bt_vendor: low_power_mode_cb
09-21 07:07:37.859  5724  5740 D bt_bte_conf:   vendorId            = 000f
09-21 07:07:37.859  5724  5740 D bt_bte_conf:   vendorIdSource      = 0001
09-21 07:07:37.859  5724  5740 D bt_bte_conf:   product             = 1200
09-21 07:07:37.859  5724  5740 D bt_bte_conf:   version             = 1436
09-21 07:07:37.859  5724  5740 D bt_bte_conf:   clientExecutableURL = 
,09-21 07:07:37.860  5724  5740 D bt_bte_conf:   serviceDescription  = 
09-21 07:07:37.860  5724  5740 D bt_bte_conf:   documentationURL    = 
09-21 07:07:37.860  5724  5740 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-21 07:07:37.860  5724  5737 D bt_stack_manager: event_start_up_stack finished
09-21 07:07:37.861  5724  5736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-21 07:07:37.861  5724  5736 D BluetoothAdapterProperties: Setting state to 15
09-21 07:07:37.861  5724  5736 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-21 07:07:37.863  5724  5736 I BluetoothAdapterState: Entering BleOnState
,09-21 07:07:37.869  5724  5736 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-21 07:07:37.869  5724  5736 D BluetoothAdapterProperties: Setting state to 11
,09-21 07:07:37.869  5724  5736 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-21 07:07:37.878  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
,09-21 07:07:37.879  5724  5724 D HeadsetService: Received start request. Starting profile...
09-21 07:07:37.879  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:37.885  5724  5724 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-21 07:07:37.885  5724  5724 D HeadsetStateMachine: make
,09-21 07:07:37.890  5724  5736 I BluetoothAdapterState: Entering PendingCommandState
,09-21 07:07:37.896  5724  5724 D HeadsetStateMachine: max_hf_connections = 1
,09-21 07:07:37.896  5724  5724 I bt_bluedroid: get_profile_interface handsfree
09-21 07:07:37.897  5724  5740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-21 07:07:37.897  5724  5740 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-21 07:07:37.900  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
,09-21 07:07:37.901  5724  5724 D A2dpService: Received start request. Starting profile...
,09-21 07:07:37.902  5724  5724 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-21 07:07:37.902  5724  5724 I bt_bluedroid: get_profile_interface avrcp
,09-21 07:07:37.907  5724  5724 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-21 07:07:37.908  5724  5724 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-21 07:07:37.908  5724  5724 D A2dpStateMachine: make
,09-21 07:07:37.909  5724  5724 I bt_bluedroid: get_profile_interface a2dp
09-21 07:07:37.909  5724  5740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-21 07:07:37.910  5724  5756 D A2dpStateMachine: Enter Disconnected: -2
09-21 07:07:37.911  5724  5724 I BluetoothHidServiceJni: classInitNative: succeeds
09-21 07:07:37.912  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
,09-21 07:07:37.912  5724  5724 D HidService: Received start request. Starting profile...
09-21 07:07:37.912  5724  5724 I bt_bluedroid: get_profile_interface hidhost
09-21 07:07:37.912  5724  5724 D HidService: setHidService(): set to: null
09-21 07:07:37.912  5724  5740 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f1c56d
09-21 07:07:37.913  5724  5740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-21 07:07:37.914  5724  5724 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-21 07:07:37.915  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:37.915  5724  5724 D HealthService: Received start request. Starting profile...
09-21 07:07:37.916  3684  3684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 07:07:37.917  5724  5724 I bt_bluedroid: get_profile_interface health
09-21 07:07:37.917  5724  5724 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-21 07:07:37.918  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:37.919  5724  5724 D PanService: Received start request. Starting profile...
,09-21 07:07:37.919  5724  5724 D BluetoothPanServiceJni: initializeNative(L110): pan
09-21 07:07:37.919  5724  5724 I bt_bluedroid: get_profile_interface pan
09-21 07:07:37.920  5724  5740 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-21 07:07:37.921  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:37.922  5724  5724 D BluetoothMapService: Received start request. Starting profile...
09-21 07:07:37.922  5724  5724 D BluetoothMapService: start()
,09-21 07:07:37.925  5724  5724 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-21 07:07:37.925  5724  5724 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-21 07:07:37.926  5724  5724 D BluetoothMapAppObserver: createReceiver()
,09-21 07:07:37.927  5724  5724 D BluetoothMapAppObserver: initObservers()
,09-21 07:07:37.927  5724  5724 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-21 07:07:37.933  5724  5724 V SapService: SapBinder()
,09-21 07:07:37.934  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
09-21 07:07:37.934  5724  5724 D SapService: Received start request. Starting profile...
,09-21 07:07:37.934  5724  5724 V SapService: start()
,09-21 07:07:37.938  5724  5724 V BluetoothAdapterState: isTurningOff()=false
,09-21 07:07:37.938  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:37.938  5724  5754 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-21 07:07:37.938  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:37.938  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:37.938  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:37.938  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:37.938  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:37.938  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 07:07:37.939  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:37.939  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:37.939  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:37.939  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:37.939  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:37.939  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:37.939  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:37.939  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 07:07:37.940  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:37.940  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:37.940  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:37.940  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:37.940  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:37.940  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:37.940  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 07:07:37.940  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-21 07:07:37.941  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-21 07:07:37.941  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-21 07:07:37.941  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-21 07:07:37.941  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 07:07:37.942  5724  5736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-21 07:07:37.942  5724  5736 D BluetoothAdapterProperties: ScanMode =  20
09-21 07:07:37.942  5724  5736 D BluetoothAdapterProperties: State =  11
09-21 07:07:37.943  5724  5740 D BluetoothAdapterProperties: Scan Mode:21
09-21 07:07:37.943  5724  5736 D BluetoothAdapterProperties: Setting state to 12
09-21 07:07:37.943  5724  5736 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-21 07:07:37.944   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-21 07:07:37.945  5724  5736 I BluetoothAdapterState: Entering OnState
09-21 07:07:37.945  5575  5718 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 07:07:37.945  5724  5740 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 07:07:37.945   930   930 D BluetoothA2dp: Proxy object connected
,09-21 07:07:37.947  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:37.947  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:37.947  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:37.947  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:37.947  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:37.947  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:37.947  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:37.947  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:37.948  5575  5585 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-21 07:07:37.949  3587  3615 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 07:07:37.949  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:37.949  3190  3202 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-21 07:07:37.951  5575  5587 D BluetoothMap: onBluetoothStateChange: up=true
,09-21 07:07:37.952  3190  3190 D BluetoothInputDevice: Proxy object connected
,09-21 07:07:37.952  3190  3190 D HidProfile: Bluetooth service connected
09-21 07:07:37.953  5724  5724 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-21 07:07:37.953  5724  5724 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-21 07:07:37.953  5575  5718 D BluetoothPan: onBluetoothStateChange on: true
,09-21 07:07:37.954  5724  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 07:07:37.955  5575  5575 D BluetoothA2dp: Proxy object connected
,09-21 07:07:37.956  3190  3208 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 07:07:37.956  5724  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 07:07:37.956  3190  3202 D BluetoothPan: onBluetoothStateChange on: true
09-21 07:07:37.957  5724  5724 D ObexServerSockets: Succeed to create listening sockets 
09-21 07:07:37.957  5724  5724 D ObexServerSockets0: startAccept()
,09-21 07:07:37.957  5724  5724 D ObexServerSockets0: prepareForNewConnect()
09-21 07:07:37.958   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 07:07:37.958   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 07:07:37.958  3190  3807 D BluetoothPbap: onBluetoothStateChange: up=true
09-21 07:07:37.959  5724  5724 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-21 07:07:37.959  5724  5724 D BluetoothSdpJni: SDP Create record success - handle: 0
09-21 07:07:37.960  5724  5762 D ObexServerSockets0: Accepting socket connection...
09-21 07:07:37.960  5724  5763 D ObexServerSockets0: Accepting socket connection...
09-21 07:07:37.960  5575  5585 D BluetoothPbap: onBluetoothStateChange: up=true
09-21 07:07:37.961  3190  3190 D BluetoothPan: BluetoothPAN Proxy object connected
,09-21 07:07:37.961  3190  3190 D PanProfile: Bluetooth service connected
09-21 07:07:37.962  3190  3202 D BluetoothMap: onBluetoothStateChange: up=true
09-21 07:07:37.964  3190  3190 D BluetoothMap: Proxy object connected
09-21 07:07:37.964  3190  3208 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 07:07:37.964  3190  3190 D MapProfile: Bluetooth service connected
09-21 07:07:37.964  3190  3190 D BluetoothMap: getConnectedDevices()
09-21 07:07:37.966  5575  5718 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-21 07:07:37.967  3190  3190 D BluetoothA2dp: Proxy object connected
09-21 07:07:37.967   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 07:07:37.969  5724  5724 D BluetoothMapService: onReceive
09-21 07:07:37.969  5724  5724 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-21 07:07:37.969  5724  5724 D BluetoothMapService: STATE_ON
09-21 07:07:37.970   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
09-21 07:07:37.971  5575  5575 D BluetoothMap: Proxy object connected
09-21 07:07:37.971  5575  5575 D MapProfile: Bluetooth service connected
09-21 07:07:37.971  5575  5575 D BluetoothMap: getConnectedDevices()
09-21 07:07:37.971  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:37.972  5724  5764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 07:07:37.973  5724  5764 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-21 07:07:37.973  5575  5575 D BluetoothPan: BluetoothPAN Proxy object connected
,09-21 07:07:37.973  5575  5575 D PanProfile: Bluetooth service connected
09-21 07:07:37.973  5575  5575 D BluetoothInputDevice: Proxy object connected
09-21 07:07:37.974  5724  5764 D BluetoothSdpJni: SDP Create record success - handle: 1
09-21 07:07:37.974  5575  5575 D HidProfile: Bluetooth service connected
,09-21 07:07:37.979  5575  5575 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-21 07:07:37.986  5575  5575 D DockEventReceiver: finishStartingService: stopping service
,09-21 07:07:37.987  3684  3684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 07:07:37.991  5575  5575 D BluetoothPbap: Proxy object connected
09-21 07:07:37.992  5575  5575 D PbapServerProfile: Bluetooth service connected
09-21 07:07:37.992  5724  5724 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-21 07:07:37.992  5724  5724 D ObexServerSockets0: prepareForNewConnect()
,09-21 07:07:37.993  3190  3190 D BluetoothPbap: Proxy object connected
09-21 07:07:37.993  3190  3190 D PbapServerProfile: Bluetooth service connected
,09-21 07:07:38.000  5724  5769 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 07:07:38.012  5724  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 07:07:38.013  5724  5773 I BtOppRfcommListener: Accept thread started.
,09-21 07:07:38.050   930   930 D BluetoothHeadset: Proxy object connected
,09-21 07:07:38.050  3587  3854 D BluetoothHeadset: Proxy object connected
09-21 07:07:38.050   930   930 D BluetoothHeadset: Proxy object connected
09-21 07:07:38.051  5575  5585 D BluetoothHeadset: Proxy object connected
,09-21 07:07:38.051  3190  3202 D BluetoothHeadset: Proxy object connected
,09-21 07:07:38.052  3190  3190 D HeadsetProfile: Bluetooth service connected
09-21 07:07:38.052   930   930 D BluetoothHeadset: Proxy object connected
09-21 07:07:38.052  5575  5575 D HeadsetProfile: Bluetooth service connected
,09-21 07:07:38.056  3190  3208 D BluetoothHeadset: Proxy object connected
,09-21 07:07:38.056  3190  3190 D HeadsetProfile: Bluetooth service connected
,09-21 07:07:38.059   930   947 D BluetoothHeadset: Proxy object connected
,09-21 07:07:38.059   930   947 D BluetoothHeadset: Proxy object connected
,09-21 07:07:38.068   930   947 D BluetoothHeadset: Proxy object connected
,09-21 07:07:38.912  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:38.912  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:38.912  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:38.912  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 07:07:38.912  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:38.912  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:38.912  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:38.912  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:38.914  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 07:07:38.916  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 07:07:38.916  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db19848 added. We now have 8 listener(s)
09-21 07:07:38.916  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 07:07:38.920   930  3478 D WifiService: setWifiEnabled: false pid=5523, uid=10077
,09-21 07:07:38.920   930  3478 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 07:07:38.926  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:38.926   930  3225 D WifiService: setWifiEnabled: true pid=5523, uid=10077
,09-21 07:07:38.926   930  3225 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 07:07:38.932   509   922 D SoftapController: Softap fwReload - Ok
,09-21 07:07:38.935   509   922 D CommandListener: Setting iface cfg
,09-21 07:07:38.935   509   922 D CommandListener: Trying to bring down wlan0
,09-21 07:07:38.936   509   922 D CommandListener: Clearing all IP addresses on wlan0
,09-21 07:07:38.940   930  3049 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 07:07:39.538   930  3049 D wifi    : set interface wlan0 flags (UP)
09-21 07:07:39.543   930  3049 I WifiHAL : Initializing wifi
09-21 07:07:39.543   930  3049 I WifiHAL : Creating socket
09-21 07:07:39.547   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-21 07:07:39.553   930  3049 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-21 07:07:39.554   930  3049 D wifi    : Did set static halHandle = 0x7f911238c0
09-21 07:07:39.554   930  3049 D wifi    : halHandle = 0x7f911238c0, mVM = 0x7facecd140, mCls = 0x20182e
09-21 07:07:39.554   930  3049 D wifi    : array field set
09-21 07:07:39.554   930  3049 I WifiNative-HAL: interface[0] = wlan0
09-21 07:07:39.556   930  5778 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547894737088
09-21 07:07:39.556   930  5778 D wifi    : waitForHalEvents called, vm = 0x7facecd140, obj = 0x20182e, env = 0x7f92cab980
,09-21 07:07:39.601  5779  5779 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-21 07:07:39.622  5779  5779 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 07:07:39.633  5779  5779 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 07:07:39.634  5779  5779 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-21 07:07:39.657   930  3049 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-21 07:07:39.667   930  3049 D WifiConfigStore: Loading config and enabling all networks 
09-21 07:07:39.671  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:39.671  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:39.671  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:39.671  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:39.671  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:39.671  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:39.671  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:39.671  5523  5523 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:39.674  5523  5523 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:39.675  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:39.678   930  3049 D WifiConfigStore: loaded 0 passpoint configs
09-21 07:07:39.678   930  3049 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-21 07:07:39.679   930  3049 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-21 07:07:39.679   930  3049 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-21 07:07:39.681   930  3049 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-21 07:07:39.681   930  3049 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-21 07:07:39.681   930  3049 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-21 07:07:39.681   930  3049 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-21 07:07:39.685   930  3049 D WifiNative-HAL: Setting external_sim to 1
09-21 07:07:39.685  4372  4372 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-21 07:07:39.685   930  3049 D wifi    : setting dfs flag to true, 0x7f91825f80
,09-21 07:07:39.686   930  3049 D WifiStateMachine: Setting OUI to DA-A1-19
09-21 07:07:39.686   930  3049 D wifi    : setting scan oui 0x7f91825f80
09-21 07:07:39.686   930  3049 D WifiHAL : Sending mac address OUI
,09-21 07:07:39.690   930  3049 E native  : do suspend false
,09-21 07:07:39.697   930  3049 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-21 07:07:39.697   509   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-21 07:07:39.697   930   930 D RttService: SCAN_AVAILABLE : 3
09-21 07:07:39.698   930  3156 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-21 07:07:39.698   509   922 D CommandListener: Setting iface cfg
,09-21 07:07:39.703   930  3048 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-21 07:07:39.703   930  3048 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-21 07:07:39.711   930  3048 D WifiNative-HAL: p2pGetDeviceAddress
,09-21 07:07:39.716   930  3048 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-21 07:07:39.716   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=216424 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-21 07:07:39.944  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 07:07:39.944  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:39.944  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:39.944  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:39.944  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:39.944  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:39.944  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:39.944  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:39.950  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 07:07:39.959  5523  5569 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-21 07:07:39.960  5523  5569 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-21 07:07:39.967  5523  5569 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@570d00b Bundle[{}]
,09-21 07:07:39.968  5523  5569 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 07:07:39.968  5523  5569 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-21 07:07:39.970  5523  5569 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-21 07:07:39.971  5523  5569 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-21 07:07:39.972  5523  5569 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-21 07:07:39.975  5523  5569 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-21 07:07:39.981  5523  5569 I System.out: Running OutgoingSocketThread
,09-21 07:07:39.984  5523  5781 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 152)
,09-21 07:07:39.986  5523  5781 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45609
,09-21 07:07:39.986  5523  5781 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-21 07:07:40.985  5523  5569 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 153)
,09-21 07:07:40.986  5523  5569 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 153)
09-21 07:07:40.991  5523  5569 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
09-21 07:07:40.994  5523  5569 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-21 07:07:40.994  5523  5569 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 159)
,09-21 07:07:41.002  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 07:07:41.003  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3f6e1 added. We now have 2 listener(s)
,09-21 07:07:41.005  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 07:07:41.006  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.006  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.006  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:41.006  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dedc06 added. We now have 9 listener(s)
09-21 07:07:41.006  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:41.008  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 07:07:41.013  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 07:07:41.018  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:41.018  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:41.018  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:41.018  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:41.018  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:41.018  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:41.018  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:41.018  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:41.022  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 07:07:41.022  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 07:07:41.023  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 07:07:41.023  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6bf0f4 added. We now have 3 listener(s)
,09-21 07:07:41.026  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:41.027  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:41.029  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 07:07:41.029  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.029  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.029  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 07:07:41.030  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@118201d added. We now have 10 listener(s)
09-21 07:07:41.030  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:41.030  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:41.030  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:41.030  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:41.030  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-21 07:07:41.030  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.030  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:41.030  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:41.030  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3f6e1 removed from the list
09-21 07:07:41.031  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.031  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dedc06 removed from the list
09-21 07:07:41.031  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:41.031  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.032  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 07:07:41.032  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.034  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.034  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:41.035  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.035  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dedc06 not in the list
,09-21 07:07:41.035  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.035  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 07:07:41.037  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-21 07:07:41.037  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.037  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.037  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@118201d removed from the list
09-21 07:07:41.037  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:41.037  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.037  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.037  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:41.037  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6bf0f4 removed from the list
09-21 07:07:41.039  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 07:07:41.039  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47cb292 added. We now have 2 listener(s)
,09-21 07:07:41.040  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 07:07:41.041  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.041  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.041  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:41.041  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66cb463 added. We now have 9 listener(s)
09-21 07:07:41.041  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:41.042  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 07:07:41.047  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:41.050  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:41.050  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:41.050  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:41.050  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:41.050  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:41.050  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:41.050  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:41.050  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:41.052  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:41.052  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 07:07:41.053  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 07:07:41.053  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79ba119 added. We now have 3 listener(s)
,09-21 07:07:41.055  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 07:07:41.055  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:41.055  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.055  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.056  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:41.056  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaf65de added. We now have 10 listener(s)
09-21 07:07:41.056  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:41.056  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 07:07:41.056  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-21 07:07:41.056  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 07:07:41.056  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:41.056  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 07:07:41.058  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:41.059  5523  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 07:07:41.059  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 07:07:41.063  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 07:07:41.063  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-21 07:07:41.064  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 07:07:41.067  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-21 07:07:41.067  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 07:07:41.067  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 07:07:41.067  5523  5569 D BluetoothAdapter: STATE_ON
,09-21 07:07:41.070  5724  5761 D BtGatt.GattService: registerClient() - UUID=01802018-86d3-4d0f-9214-34899c481f61
,09-21 07:07:41.071  5724  5740 D BtGatt.GattService: onClientRegistered() - UUID=01802018-86d3-4d0f-9214-34899c481f61, clientIf=5
09-21 07:07:41.072  5523  5534 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-21 07:07:41.073  5724  5752 D BtGatt.GattService: start scan with filters
,09-21 07:07:41.076  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 07:07:41.076  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 07:07:41.076  5724  5743 D BtGatt.ScanManager: handling starting scan
,09-21 07:07:41.076  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 07:07:41.076  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 07:07:41.078  5724  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3210efc
,09-21 07:07:41.078  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:41.079  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 07:07:41.079  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:41.080  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 07:07:41.082  5523  5569 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 07:07:41.083  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:41.083  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 07:07:41.083  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.083  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 07:07:41.083  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-21 07:07:41.083  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 07:07:41.083  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 07:07:41.083  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 07:07:41.083  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 07:07:41.083  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 07:07:41.084  5523  5569 D BluetoothAdapter: STATE_ON
09-21 07:07:41.084  5724  5740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 07:07:41.084  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.085  5724  5761 D BtGatt.GattService: stopScan() - queue size =1
,09-21 07:07:41.085  5724  5743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-21 07:07:41.085  5724  5752 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 07:07:41.086  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-21 07:07:41.086  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-21 07:07:41.086  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 07:07:41.086  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-21 07:07:41.086  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 07:07:41.088  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:41.088  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 07:07:41.088  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 07:07:41.088  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 07:07:41.089  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:41.090  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:41.090  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:41.090  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:41.092  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 07:07:41.092  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.092  5724  5743 D BtGatt.ScanManager: Starting BLE batch scan
09-21 07:07:41.092  5724  5743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 07:07:41.093  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:41.093  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:41.093  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:41.093  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:41.093  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.093  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:41.093  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-21 07:07:41.094  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47cb292 removed from the list
09-21 07:07:41.094  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.094  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66cb463 removed from the list
09-21 07:07:41.094  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:41.094  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.095  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 07:07:41.095  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 07:07:41.096  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.096  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:41.096  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.096  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66cb463 not in the list
09-21 07:07:41.096  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 07:07:41.096  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 07:07:41.097  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-21 07:07:41.097  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.098  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.098  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaf65de removed from the list
09-21 07:07:41.098  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:41.098  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.098  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.098  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:41.098  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79ba119 removed from the list
09-21 07:07:41.099  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 07:07:41.099  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c801ea added. We now have 2 listener(s)
09-21 07:07:41.100  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 07:07:41.101  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.101  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.101  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:41.101  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ba4cdb added. We now have 9 listener(s)
09-21 07:07:41.101  5724  5740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 07:07:41.101  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:41.101  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.102  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 07:07:41.104  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 07:07:41.106  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-21 07:07:41.106  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.108  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:41.108  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:41.108  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:41.108  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:41.108  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:41.108  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:41.108  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:41.108  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:41.110  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:41.110  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 07:07:41.110  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 07:07:41.110  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3175a51 added. We now have 3 listener(s)
09-21 07:07:41.111  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:41.111  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 07:07:41.111  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.111  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.111  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:41.112  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1c52b6 added. We now have 10 listener(s)
09-21 07:07:41.112  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:41.112  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 07:07:41.112  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 07:07:41.112  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.112  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 07:07:41.112  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 07:07:41.112  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 07:07:41.112  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 07:07:41.112  5724  5743 D BtGatt.ScanManager: stopping BLe Batch
09-21 07:07:41.112  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:41.112  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 07:07:41.117  5523  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 07:07:41.117  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 07:07:41.118  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 07:07:41.118  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.118  5724  5743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-21 07:07:41.120  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 07:07:41.121  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 07:07:41.121  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 07:07:41.124  5724  5740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-21 07:07:41.124  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.126  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 07:07:41.126  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 07:07:41.126  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-21 07:07:41.127  5523  5569 D BluetoothAdapter: STATE_ON
,09-21 07:07:41.130  5724  5761 D BtGatt.GattService: registerClient() - UUID=f0d3c514-6e42-410c-b4bb-dc1ef13e3771
,09-21 07:07:41.130  5724  5740 D BtGatt.GattService: onClientRegistered() - UUID=f0d3c514-6e42-410c-b4bb-dc1ef13e3771, clientIf=5
09-21 07:07:41.130  5523  5534 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-21 07:07:41.131  5724  5734 D BtGatt.GattService: start scan with filters
,09-21 07:07:41.132  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-21 07:07:41.132  5724  5743 D BtGatt.ScanManager: handling starting scan
09-21 07:07:41.132  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-21 07:07:41.133  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-21 07:07:41.133  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 07:07:41.135  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:41.135  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 07:07:41.135  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:41.136  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 07:07:41.137  5724  5740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 07:07:41.137  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.137  5724  5743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 07:07:41.139  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-21 07:07:41.139  5523  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-21 07:07:41.139  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:41.139  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:41.139  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:41.139  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:41.139  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.139  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 07:07:41.139  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:41.139  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c801ea removed from the list
09-21 07:07:41.139  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.139  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ba4cdb removed from the list
09-21 07:07:41.139  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
,09-21 07:07:41.139  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:41.140  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.140  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-21 07:07:41.140  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.140  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 07:07:41.141  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.141  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:41.141  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.141  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ba4cdb not in the list
09-21 07:07:41.141  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 07:07:41.141  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 07:07:41.141  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 07:07:41.141  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-21 07:07:41.141  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 07:07:41.142  5523  5569 D BluetoothAdapter: STATE_ON
09-21 07:07:41.142  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 07:07:41.142  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.142  5724  5743 D BtGatt.ScanManager: Starting BLE batch scan
09-21 07:07:41.142  5724  5743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 07:07:41.142  5724  5734 D BtGatt.GattService: stopScan() - queue size =1
,09-21 07:07:41.143  5724  5752 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-21 07:07:41.143  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 07:07:41.143  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 07:07:41.143  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 07:07:41.143  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 07:07:41.143  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 07:07:41.144  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:41.144  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-21 07:07:41.144  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 07:07:41.144  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 07:07:41.145  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.146  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:41.146  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.146  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.146  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:41.146  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1c52b6 removed from the list
,09-21 07:07:41.146  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:41.146  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:41.146  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.146  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:41.146  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.146  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:41.146  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3175a51 removed from the list
09-21 07:07:41.146  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 07:07:41.147  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392e442 added. We now have 2 listener(s)
09-21 07:07:41.148  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 07:07:41.148  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.148  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.148  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 07:07:41.148  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4237c53 added. We now have 9 listener(s)
09-21 07:07:41.148  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:41.148  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 07:07:41.150  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:41.151  5724  5740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 07:07:41.151  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.154  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:41.154  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:41.154  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:41.154  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:41.154  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:41.154  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:41.154  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:41.154  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:41.156  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-21 07:07:41.156  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.157  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 07:07:41.157  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 07:07:41.157  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 07:07:41.157  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba0289 added. We now have 3 listener(s)
09-21 07:07:41.159  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:41.159  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 07:07:41.159  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.159  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.160  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:41.160  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ef028e added. We now have 10 listener(s)
09-21 07:07:41.160  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:41.160  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:41.160  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 07:07:41.160  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 07:07:41.160  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 07:07:41.160  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 07:07:41.160  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 07:07:41.161  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 07:07:41.161  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.161  5724  5743 D BtGatt.ScanManager: stopping BLe Batch
,09-21 07:07:41.163  5523  5569 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 07:07:41.163  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 07:07:41.165  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 07:07:41.166  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 07:07:41.166  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.166  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 07:07:41.166  5724  5743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 07:07:41.166  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 07:07:41.168  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 07:07:41.168  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 07:07:41.168  5523  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 07:07:41.169  5523  5569 D BluetoothAdapter: STATE_ON
,09-21 07:07:41.170  5724  5740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 07:07:41.170  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.171  5724  5761 D BtGatt.GattService: registerClient() - UUID=10e1fab8-9c74-4b5f-8891-a55fa5a2d8cd
09-21 07:07:41.172  5724  5740 D BtGatt.GattService: onClientRegistered() - UUID=10e1fab8-9c74-4b5f-8891-a55fa5a2d8cd, clientIf=5
09-21 07:07:41.172  5523  5622 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-21 07:07:41.173  5724  5752 D BtGatt.GattService: start scan with filters
,09-21 07:07:41.174  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 07:07:41.174  5724  5743 D BtGatt.ScanManager: handling starting scan
09-21 07:07:41.174  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 07:07:41.174  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-21 07:07:41.175  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 07:07:41.177  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 07:07:41.177  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 07:07:41.177  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 07:07:41.178  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 07:07:41.179  5724  5740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 07:07:41.179  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.179  5724  5743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 07:07:41.182  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 07:07:41.182  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:41.182  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:41.182  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:41.182  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.182  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 07:07:41.182  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:41.182  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392e442 removed from the list
09-21 07:07:41.182  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.182  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4237c53 removed from the list
09-21 07:07:41.182  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:41.182  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:41.183  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.183  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-21 07:07:41.183  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.183  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:41.184  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.184  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:41.184  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 07:07:41.184  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.184  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.184  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4237c53 not in the list
09-21 07:07:41.184  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 07:07:41.184  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 07:07:41.184  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 07:07:41.184  5724  5743 D BtGatt.ScanManager: Starting BLE batch scan
09-21 07:07:41.184  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 07:07:41.184  5724  5743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 07:07:41.184  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 07:07:41.185  5523  5569 D BluetoothAdapter: STATE_ON
09-21 07:07:41.185  5724  5753 D BtGatt.GattService: stopScan() - queue size =1
09-21 07:07:41.186  5724  5735 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 07:07:41.186  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 07:07:41.186  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 07:07:41.186  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 07:07:41.186  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 07:07:41.186  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-21 07:07:41.187  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:41.187  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 07:07:41.187  5523  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 07:07:41.187  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 07:07:41.188  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.188  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:41.188  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.189  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-21 07:07:41.189  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:41.189  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ef028e removed from the list
09-21 07:07:41.189  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:41.189  5523  5523 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 07:07:41.189  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.189  5523  5523 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 07:07:41.189  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.189  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:41.189  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba0289 removed from the list
09-21 07:07:41.189  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 07:07:41.189  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dcb99a added. We now have 2 listener(s)
,09-21 07:07:41.190  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 07:07:41.190  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.191  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.191  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:41.191  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa422cb added. We now have 9 listener(s)
09-21 07:07:41.191  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 07:07:41.191  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 07:07:41.193  5724  5740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 07:07:41.193  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.194  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 07:07:41.197  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-21 07:07:41.198  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.198  5523  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 07:07:41.198  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 07:07:41.198  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 07:07:41.198  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 07:07:41.198  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 07:07:41.198  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 07:07:41.198  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 07:07:41.198  5523  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 07:07:41.200  5523  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 07:07:41.200  5523  5569 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 07:07:41.200  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 07:07:41.200  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59279c1 added. We now have 3 listener(s)
09-21 07:07:41.201  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:41.201  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 07:07:41.201  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 07:07:41.202  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 07:07:41.202  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 07:07:41.202  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbcd566 added. We now have 10 listener(s)
09-21 07:07:41.202  5523  5569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 07:07:41.202  5523  5569 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 07:07:41.202  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:41.202  5523  5569 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 07:07:41.202  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:41.202  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.202  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 07:07:41.202  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:41.202  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dcb99a removed from the list
09-21 07:07:41.202  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.202  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa422cb removed from the list
09-21 07:07:41.202  5523  5523 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 07:07:41.202  5523  5569 D io.jxcore.node.ConnectivityMonitor: stop
09-21 07:07:41.202  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.203  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.203  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.203  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 07:07:41.203  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.203  5724  5743 D BtGatt.ScanManager: stopping BLe Batch
09-21 07:07:41.204  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.204  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:41.204  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.204  5523  5569 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa422cb not in the list
09-21 07:07:41.204  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.204  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 07:07:41.205  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 07:07:41.205  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 07:07:41.205  5523  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 07:07:41.205  5523  5569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbcd566 removed from the list
09-21 07:07:41.205  5523  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 07:07:41.205  5523  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 07:07:41.205  5523  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 07:07:41.205  5523  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 07:07:41.205  5523  5569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59279c1 removed from the list
,09-21 07:07:41.206  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-21 07:07:41.206  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-21 07:07:41.206  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-21 07:07:41.206  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 07:07:41.206  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-21 07:07:41.206  5523  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 07:07:41.208  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 07:07:41.208  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 07:07:41.208  5724  5743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-21 07:07:41.211  5523  5782 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name)
,09-21 07:07:41.211  5523  5782 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: My test thread name)
09-21 07:07:41.211  5523  5782 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-21 07:07:41.213  5724  5740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-21 07:07:41.213  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 07:07:41.214  5523  5783 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name)
,09-21 07:07:41.215  5523  5783 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name)
09-21 07:07:41.215  5523  5783 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-21 07:07:41.216  5523  5569 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-21 07:07:41.216  5523  5569 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-21 07:07:41.216  5523  5569 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-21 07:07:41.216  5523  5569 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-21 07:07:41.216  5523  5569 D com.test.thalitest.ThaliTestRunner: Total duration: 22627 ms
09-21 07:07:41.218  5523  5569 I jxcore-log: *Native tests were executed*
09-21 07:07:41.218  5523  5569 I jxcore-log: 
09-21 07:07:41.218  5523  5569 I jxcore-log: Total number of executed tests:  80
09-21 07:07:41.218  5523  5569 I jxcore-log: 
09-21 07:07:41.218  5523  5569 I jxcore-log: Number of passed tests:  80
09-21 07:07:41.218  5523  5569 I jxcore-log: 
09-21 07:07:41.218  5523  5569 I jxcore-log: Number of failed tests:  0
09-21 07:07:41.218  5523  5569 I jxcore-log: 
09-21 07:07:41.218  5523  5569 I jxcore-log: Number of ignored tests:  0
09-21 07:07:41.218  5523  5569 I jxcore-log: 
09-21 07:07:41.219  5523  5569 I jxcore-log: Total duration:  22627
09-21 07:07:41.219  5523  5569 I jxcore-log: 
09-21 07:07:41.219  5523  5569 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-21 07:07:41.219  5523  5569 I jxcore-log: 
,09-21 07:07:41.222  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 07:07:41.222  5523  5569 I jxcore-log: 
09-21 07:07:41.224  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 07:07:41.224  5523  5569 I jxcore-log: 
09-21 07:07:41.225  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 07:07:41.225  5523  5569 I jxcore-log: 
09-21 07:07:41.226  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 07:07:41.226  5523  5569 I jxcore-log: 
09-21 07:07:41.227  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 07:07:41.227  5523  5569 I jxcore-log: 
09-21 07:07:41.229  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 07:07:41.229  5523  5569 I jxcore-log: 
09-21 07:07:41.229  5523  5523 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-21 07:07:41.232  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 07:07:41.232  5523  5569 I jxcore-log: 
09-21 07:07:41.234  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.234  5523  5569 I jxcore-log: 
09-21 07:07:41.235  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.235  5523  5569 I jxcore-log: 
09-21 07:07:41.235  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.235  5523  5569 I jxcore-log: 
09-21 07:07:41.236  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.236  5523  5569 I jxcore-log: 
09-21 07:07:41.237  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 07:07:41.237  5523  5569 I jxcore-log: 
09-21 07:07:41.238  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.238  5523  5569 I jxcore-log: 
09-21 07:07:41.239  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.239  5523  5569 I jxcore-log: 
09-21 07:07:41.239  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.239  5523  5569 I jxcore-log: 
09-21 07:07:41.240  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.240  5523  5569 I jxcore-log: 
,09-21 07:07:41.241  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.241  5523  5569 I jxcore-log: 
09-21 07:07:41.242  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.242  5523  5569 I jxcore-log: 
09-21 07:07:41.242  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.242  5523  5569 I jxcore-log: 
09-21 07:07:41.243  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.243  5523  5569 I jxcore-log: 
09-21 07:07:41.243  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.243  5523  5569 I jxcore-log: 
09-21 07:07:41.244  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 07:07:41.244  5523  5569 I jxcore-log: 
09-21 07:07:41.245  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.245  5523  5569 I jxcore-log: 
09-21 07:07:41.245  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.245  5523  5569 I jxcore-log: 
09-21 07:07:41.246  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.246  5523  5569 I jxcore-log: 
09-21 07:07:41.247  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.247  5523  5569 I jxcore-log: 
,09-21 07:07:41.247  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.247  5523  5569 I jxcore-log: 
09-21 07:07:41.248  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.248  5523  5569 I jxcore-log: 
09-21 07:07:41.249  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 07:07:41.249  5523  5569 I jxcore-log: 
,09-21 07:07:41.590  5523  5523 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 07:07:41.594  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 07:07:41.594  5523  5569 I jxcore-log: 
,09-21 07:07:41.647  5523  5523 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 07:07:41.650  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 07:07:41.650  5523  5569 I jxcore-log: 
,09-21 07:07:41.689  5523  5523 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 07:07:41.692  5523  5569 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 07:07:41.692  5523  5569 I jxcore-log: 
,09-21 07:07:41.733  5784  5784 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-21 07:07:41.739  5784  5784 D AndroidRuntime: CheckJNI is OFF
,09-21 07:07:41.768  5784  5784 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-21 07:07:41.803  5784  5784 I Radio-JNI: register_android_hardware_Radio DONE
,09-21 07:07:41.821  5784  5784 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-21 07:07:41.831   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-21 07:07:41.832   930   943 I ActivityManager: Killing 5523:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-21 07:07:41.906   930   941 I WindowState: WIN DEATH: Window{4c3f225 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-21 07:07:41.906   930  3511 D GraphicsStats: Buffer count: 2
,09-21 07:07:41.907   930  3050 D WifiService: Client connection lost with reason: 4
,09-21 07:07:41.978   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-21 07:07:41.978   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-21 07:07:41.979   930   943 E ActivityManager: Failure starting process com.test.thalitest
09-21 07:07:41.979   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-21 07:07:41.979   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:41.979   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:41.979   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 07:07:41.979   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-21 07:07:41.979   930   943 I ActivityManager:   Force finishing activity ActivityRecord{119d58e u0 com.test.thalitest/.MainActivity t2}
,09-21 07:07:41.981   930   954 I art     : Starting a blocking GC Explicit
,09-21 07:07:41.988   930  3225 W ActivityManager: Spurious death for ProcessRecord{d5f1b4a 0:com.test.thalitest/u0a77}, curProc for 5523: null
,09-21 07:07:41.992   930   948 W WindowManager: Attempted to add application window with unknown token Token{e561af ActivityRecord{119d58e u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-21 07:07:41.993   930   948 W WindowManager: Token{e561af ActivityRecord{119d58e u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{e561af ActivityRecord{119d58e u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-21 07:07:41.993   930   948 W WindowManager: view not successfully added to wm, removing view
09-21 07:07:41.993   930   948 W WindowManager: Exception when adding starting window
09-21 07:07:41.993   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{bb3e96d V.E...... R.....ID 0,0-0,0} not attached to window manager
09-21 07:07:41.993   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-21 07:07:41.993   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-21 07:07:41.993   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-21 07:07:41.993   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-21 07:07:41.993   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-21 07:07:41.993   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:41.993   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:41.993   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 07:07:41.993   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-21 07:07:42.064   930   954 I art     : Explicit concurrent mark sweep GC freed 25528(1647KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 28MB/43MB, paused 1.509ms total 82.465ms
,09-21 07:07:42.082   930   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-21 07:07:42.085  5784  5784 I art     : System.exit called, status: 0
,09-21 07:07:42.086  5784  5784 I AndroidRuntime: VM exiting with result code 0.
,09-21 07:07:42.089   930   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-21 07:07:42.097   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-21 07:07:42.100  3479  3479 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-21 07:07:42.101  5724  5724 D BluetoothMapAppObserver: onReceive
09-21 07:07:42.101  5724  5724 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-21 07:07:42.101  3710  4050 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-21 07:07:42.106   930  3015 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-21 07:07:42.154  3492  5798 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-21 07:07:42.156  3587  3587 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-21 07:07:42.160   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-21 07:07:42.155  3479  5795 I Keyboard.Facilitator.DecoderInitializer: run()
,09-21 07:07:42.171  3479  5795 I Decoder : createOrResetDecoder
,09-21 07:07:42.182  3684  3684 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-21 07:07:42.183  3684  3684 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-21 07:07:42.199  3993  5801 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-21 07:07:42.199  3993  5801 D AccountUtils: Clearing selected account for com.test.thalitest
,09-21 07:07:42.204    29    29 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 07:07:42.210    29    29 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 07:07:42.220    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 07:07:42.227  3684  3684 I ConfigService: onCreate
,09-21 07:07:42.228  3492  3509 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj3507F89ED) - 
,09-21 07:07:42.229  3684  5804 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-21 07:07:42.229  3684  5804 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-21 07:07:42.230  3684  5804 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-21 07:07:42.232  3684  5804 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-21 07:07:42.245  3479  5795 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-21 07:07:42.272  3993  5801 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-21 07:07:42.308  3993  5801 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:42.308  3993  5801 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:42.308  3993  5801 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 07:07:42.309  3993  5801 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,--------- beginning of crash
09-21 07:07:42.314  3492  3509 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-21 07:07:42.314  3492  3509 E AndroidRuntime: Process: android.process.acore, PID: 3492
09-21 07:07:42.314  3492  3509 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-21 07:07:42.314  3492  3509 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-21 07:07:42.332  3993  3993 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-21 07:07:42.332  3993  3993 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-21 07:07:42.348  3993  3993 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-21 07:07:42.348  3993  3993 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-21 07:07:42.368  4899  5810 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-21 07:07:42.375   930  3784 I ActivityManager: Start proc 5813:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,09-21 07:07:42.409  4899  5810 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-21 07:07:42.412  3492  3509 I Process : Sending signal. PID: 3492 SIG: 9
,09-21 07:07:42.415  3993  5809 W BaseAppContext: Using Auth Proxy for data requests.
,09-21 07:07:42.426  3993  5809 W BaseAppContext: Using Auth Proxy for data requests.
,09-21 07:07:42.443  3993  5820 I GMPM-SVC: App measurement is starting up
,09-21 07:07:42.446  3993  5820 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-21 07:07:42.447  3993  5820 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-21 07:07:42.451   930  3278 I ActivityManager: Start proc 5822:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-21 07:07:42.460  3993  3993 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-21 07:07:42.604   381   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
