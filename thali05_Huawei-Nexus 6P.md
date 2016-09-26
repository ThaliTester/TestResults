#### Test 86743101e849c33_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-26 12:19:25.958  3842  4927 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
09-26 12:19:26.050  3842  4927 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
09-26 12:19:26.064  3842  3842 I ConfigFetchService: fetch service done; releasing wakelock
09-26 12:19:26.065  3842  3842 I ConfigFetchService: stopping self
09-26 12:19:26.100  5539  5583 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
09-26 12:19:26.151  5539  5583 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
09-26 12:19:26.181  5539  5583 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-26 12:19:26.242   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
09-26 12:19:26.489   551   551 I ServiceManager: Waiting for service AtCmdFwd...
09-26 12:19:27.491   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:28.121  5596  5596 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-26 12:19:28.127  5596  5596 D AndroidRuntime: CheckJNI is OFF
09-26 12:19:28.153  5596  5596 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-26 12:19:28.183  5596  5596 I Radio-JNI: register_android_hardware_Radio DONE
09-26 12:19:28.198  5596  5596 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-26 12:19:28.206   928  3837 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-26 12:19:28.252   928  3837 I ActivityManager: Start proc 5605:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-26 12:19:28.262  5596  5596 D AndroidRuntime: Shutting down VM
,09-26 12:19:28.491   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:19:28.589   928  3929 I WindowManager: Screenshot max retries 4 of Token{19eea2e ActivityRecord{6044a9 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{23adfe1 u0 Starting com.test.thalitest} drawState=2
,09-26 12:19:28.668  5605  5605 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-26 12:19:28.704  5605  5605 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-26 12:19:28.789  5605  5605 I LibraryLoader: Time to load native libraries: 78 ms (timestamps 3191-3269)
,09-26 12:19:28.789  5605  5605 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-26 12:19:28.838  5605  5605 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cd1d33f}
,09-26 12:19:28.839  5605  5605 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-26 12:19:28.840  5605  5605 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-26 12:19:28.848  5605  5605 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-26 12:19:28.851  5605  5605 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-26 12:19:28.894  5605  5605 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-26 12:19:28.919  5605  5605 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-26 12:19:28.919  5605  5605 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-26 12:19:28.919  5605  5605 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-26 12:19:28.919  5605  5605 I Adreno  : Build Date                       : 12/06/15
09-26 12:19:28.919  5605  5605 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-26 12:19:28.919  5605  5605 I Adreno  : Local Branch                     : mybranch17112971
09-26 12:19:28.919  5605  5605 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-26 12:19:28.919  5605  5605 I Adreno  : Remote Branch                    : NONE
09-26 12:19:28.919  5605  5605 I Adreno  : Reconstruct Branch               : NOTHING
,09-26 12:19:28.974   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f6aa19:true
,09-26 12:19:29.011  2923  2923 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32905]" dev="sockfs" ino=32905 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 12:19:29.011  2923  2923 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32905]" dev="sockfs" ino=32905 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 12:19:29.025  5605  5605 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-26 12:19:29.034  5605  5605 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-26 12:19:29.057   402   402 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32346]" dev="sockfs" ino=32346 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 12:19:29.057   402   402 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32346]" dev="sockfs" ino=32346 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-26 12:19:29.060  5605  5643 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-26 12:19:29.061  3838  3838 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14103]" dev="sockfs" ino=14103 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-26 12:19:29.061  3838  3838 W Binder_B: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14103]" dev="sockfs" ino=14103 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-26 12:19:29.066  5605  5630 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-26 12:19:29.095  5605  5643 I OpenGLRenderer: Initialized EGL, version 1.4
,09-26 12:19:29.193   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +603ms (total +967ms)
,09-26 12:19:29.217  5605  5605 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5605
,09-26 12:19:29.303  5605  5605 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-26 12:19:29.420  5605  5646 D jxcore_app_log: JniHelper::setJavaVM(0xf50fc000), pthread_self() = -566490832
,09-26 12:19:29.423  5605  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-26 12:19:29.423  5605  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-26 12:19:29.423  5605  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-26 12:19:29.423  5605  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-26 12:19:29.423  5605  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-26 12:19:29.424  5605  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3a0964 added. We now have 1 listener(s)
,09-26 12:19:29.426  5605  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-26 12:19:29.426  5605  5646 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 12:19:29.427  5605  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-26 12:19:29.427  5605  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-26 12:19:29.429  5605  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c63b93 added. We now have 1 listener(s)
09-26 12:19:29.429  5605  5646 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:19:29.434   928  2955 D WifiService: New client listening to asynchronous messages
09-26 12:19:29.434  5605  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 12:19:29.434  5605  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-26 12:19:29.435  5605  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-26 12:19:29.435  5605  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-26 12:19:29.435  5605  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-26 12:19:29.442  5605  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:29.443  5605  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-26 12:19:29.449  5605  5646 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-26 12:19:29.449  5605  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:19:29.449  5605  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:19:29.449  5605  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:19:29.449  5605  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:19:29.449  5605  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:19:29.449  5605  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:19:29.449  5605  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:19:29.449  5605  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:19:29.449  5605  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-26 12:19:29.449  5605  5646 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:19:29.449  5605  5646 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-26 12:19:29.452  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:29.454  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:29.466  5605  5605 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-26 12:19:29.744  5605  5652 W jxcore-log: Initializing JXcore engine
,09-26 12:19:29.744  5605  5652 W jxcore-log: JXcore engine is ready
,09-26 12:19:29.764  5652  5652 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11668 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-26 12:19:29.767  5652  5652 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16406]" dev="sockfs" ino=16406 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-26 12:19:29.767  5652  5652 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-26 12:19:29.767  5652  5652 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32312]" dev="sockfs" ino=32312 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-26 12:19:29.774  5605  5652 W jxcore-log: Starting JXcore engine
,09-26 12:19:29.822  5605  5652 W jxcore-log: Platform android
09-26 12:19:29.822  5605  5652 W jxcore-log: 
,09-26 12:19:29.822  5605  5652 W jxcore-log: Process ARCH arm
09-26 12:19:29.822  5605  5652 W jxcore-log: 
,09-26 12:19:29.913  5605  5652 I jxcore-log: JXcore Cordova bridge is ready!
09-26 12:19:29.913  5605  5652 I jxcore-log: 
,09-26 12:19:29.914  5605  5652 W jxcore-log: JXcore engine is started
,09-26 12:19:29.925  5605  5646 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-26 12:19:29.930  5605  5605 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-26 12:19:31.076  3562  3562 I ConfigService: onDestroy
,09-26 12:19:33.495   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:34.496   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:35.497   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:36.498   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:37.498   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:38.499   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:19:39.427  5605  5652 I jxcore-log: 2016-09-26 16:19:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-26 12:19:39.427  5605  5652 I jxcore-log: 
,09-26 12:19:39.429  5605  5652 I jxcore-log: 2016-09-26 16:19:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-26 12:19:39.429  5605  5652 I jxcore-log: 
,09-26 12:19:39.433  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:19:39.433  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:19:39.433  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:19:39.433  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:19:39.433  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:19:39.433  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:19:39.433  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:19:39.433  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:19:39.435  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 12:19:39.437  5605  5652 I jxcore-log: 2016-09-26 16:19:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-26 12:19:39.437  5605  5652 I jxcore-log: 
09-26 12:19:39.439  5605  5652 I jxcore-log: 2016-09-26 16:19:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-26 12:19:39.439  5605  5652 I jxcore-log: 
,09-26 12:19:39.553  4828  4858 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-26 12:19:39.554  4828  4828 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,09-26 12:19:39.667  5605  5652 I jxcore-log: 2016-09-26 16:19:39 - DEBUG UnitTest_app: 'Running unit tests'
09-26 12:19:39.667  5605  5652 I jxcore-log: 
,09-26 12:19:39.667  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 12:19:39.668  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83ed37 added. We now have 2 listener(s)
09-26 12:19:39.668  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 12:19:39.668  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 12:19:39.668  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 12:19:39.669  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:19:39.669  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fcf2a4 added. We now have 2 listener(s)
09-26 12:19:39.669  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:19:39.669  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 12:19:39.671  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:19:39.674  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:19:39.674  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:19:39.674  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:19:39.674  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:19:39.674  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:19:39.674  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:19:39.674  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:19:39.674  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:19:39.675  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:19:39.675  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:19:39.676  5605  5652 D executeNativeTests: Running unit tests
,09-26 12:19:39.681  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:39.687  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:39.711  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 12:19:39.711  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 added. We now have 3 listener(s)
,09-26 12:19:39.711  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 12:19:39.712  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 12:19:39.712  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 12:19:39.712  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:19:39.712  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 added. We now have 3 listener(s)
,09-26 12:19:39.712  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:19:39.712  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 12:19:39.714  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:39.716  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:19:39.716  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:19:39.716  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:19:39.716  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:19:39.716  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:19:39.716  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:19:39.716  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:19:39.716  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:19:39.717  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 12:19:39.717  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:19:39.718  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 12:19:39.718  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-26 12:19:39.718  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 12:19:39.718  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 12:19:39.719  5605  5652 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-26 12:19:39.719  5605  5652 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-26 12:19:39.719  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-26 12:19:39.719  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 12:19:39.719  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-26 12:19:39.719  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 12:19:39.719  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:39.720  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 12:19:39.720  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:39.720  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:39.720  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:39.720  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:19:39.720  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 12:19:39.720  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 removed from the list
09-26 12:19:39.721  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:39.721  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 removed from the list
,09-26 12:19:39.724  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:39.730  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:39.731  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:39.731  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:39.731  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:39.731  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:39.732  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:39.732  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:39.732  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 12:19:39.732  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:39.733  5605  5652 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-26 12:19:39.733  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:39.733  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:39.733  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:39.733  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:39.733  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:39.733  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:39.734  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:39.734  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 12:19:39.734  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:39.734  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:39.734  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:39.734  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:39.734  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:39.734  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:39.734  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:39.734  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:39.734  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:39.734  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
,09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-26 12:19:39.737  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-26 12:19:39.738  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-26 12:19:39.738  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-26 12:19:39.738  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-26 12:19:39.738  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-26 12:19:39.738  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:39.738  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:39.738  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:39.738  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:39.738  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:39.738  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:39.738  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
,09-26 12:19:39.738  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:39.738  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:39.738  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:39.738  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:39.738  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:39.738  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:39.738  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:19:39.739  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:39.739  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:39.739  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:39.739  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:39.739  5605  5652 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-26 12:19:39.740  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:19:39.742  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:19:39.742  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:19:39.742  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:19:39.742  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:19:39.742  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:19:39.742  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:19:39.742  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:19:39.742  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:19:39.743  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:19:39.743  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:19:39.744  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-26 12:19:39.744  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 12:19:39.744  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 12:19:39.744  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:19:39.744  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 12:19:39.747  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:39.748  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:19:39.748  5605  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:19:39.748  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 12:19:39.750  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 12:19:39.751  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 12:19:39.751  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 12:19:39.752  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-26 12:19:39.753  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-26 12:19:39.753  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-26 12:19:39.754  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 12:19:39.754  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-26 12:19:39.754  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:39.756  4578  4591 D BtGatt.GattService: registerClient() - UUID=86766762-af44-414d-8a5b-5d8e4616d043
09-26 12:19:39.757  4578  4667 D BtGatt.GattService: onClientRegistered() - UUID=86766762-af44-414d-8a5b-5d8e4616d043, clientIf=5
09-26 12:19:39.757  5605  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-26 12:19:39.758  4578  4592 D BtGatt.GattService: start scan with filters
,09-26 12:19:39.763  4578  4672 D BtGatt.ScanManager: handling starting scan
09-26 12:19:39.763  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 12:19:39.763  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 12:19:39.763  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 12:19:39.763  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 12:19:39.765  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 12:19:39.765  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 12:19:39.765  4578  4672 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
09-26 12:19:39.765  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 12:19:39.765  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 12:19:39.766  5605  5652 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 12:19:39.772  4578  4667 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 12:19:39.772  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:19:39.773  4578  4672 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 12:19:39.778  4578  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 12:19:39.778  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:39.779  4578  4672 D BtGatt.ScanManager: Starting BLE batch scan
09-26 12:19:39.779  4578  4672 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 12:19:39.789  4578  4667 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 12:19:39.789  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:19:39.794  4578  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 12:19:39.794  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:19:39.867   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 12:19:40.267  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-26 12:19:40.267  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-26 12:19:40.267  5605  5605 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 12:19:42.894   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 12:19:44.771  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 12:19:44.771  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:44.771  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 12:19:44.771  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:44.771  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 12:19:44.771  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-26 12:19:44.771  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 12:19:44.771  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 12:19:44.771  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-26 12:19:44.772  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-26 12:19:44.773  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 12:19:44.774  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:19:44.774  4578  4592 D BtGatt.GattService: stopScan() - queue size =1
,09-26 12:19:44.776  4578  4811 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 12:19:44.777  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 12:19:44.778  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 12:19:44.778  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 12:19:44.778  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-26 12:19:44.778  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 12:19:44.781  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 12:19:44.782  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:44.782  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 12:19:44.783  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:19:44.784  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:19:44.784  4578  4578 D BtGatt.ScanManager: awakened up at time 139265
09-26 12:19:44.786  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:44.786  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:44.786  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 12:19:44.786  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:19:44.787  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:44.787  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:44.787  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:44.787  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:44.787  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 12:19:44.787  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:19:44.787  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 12:19:44.792  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 12:19:44.792  5605  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 12:19:44.793  4578  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 12:19:44.794  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:19:44.794  4578  4672 D BtGatt.ScanManager: stopping BLe Batch
09-26 12:19:44.799  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 12:19:44.803  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 12:19:44.803  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 12:19:44.803  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:19:44.804  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:44.806  4578  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 12:19:44.806  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:44.806  4578  4672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 12:19:44.807  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 12:19:44.807  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:44.807  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:19:44.811  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:19:44.811  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:19:44.812  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:44.815  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 12:19:44.826  4578  4667 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-26 12:19:44.826  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:19:44.826  4578  4667 D BtGatt.GattService: current time is 139307355799
,09-26 12:19:44.827  4578  4667 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -74, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -76, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -79, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -91, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -72, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-26 12:19:44.828  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-26 12:19:44.829  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-26 12:19:44.829  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 12:19:44.830  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-26 12:19:44.830  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-26 12:19:44.830  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-26 12:19:45.317  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 12:19:46.242   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:19:46.530   928  5365 D NetlinkSocketObserver: NeighborEvent{elapsedMs=141010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:19:48.501   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:49.502   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:49.790  5605  5652 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-26 12:19:49.795  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:19:49.807  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:19:49.807  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:19:49.807  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:19:49.807  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:19:49.807  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:19:49.807  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:19:49.807  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:19:49.807  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:19:49.812  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 12:19:49.813  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:19:49.813  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 12:19:49.813  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-26 12:19:49.813  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-26 12:19:49.813  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:49.814  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 12:19:49.816  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:49.818  5605  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 12:19:49.820  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:49.823  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 12:19:49.823  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-26 12:19:49.823  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 12:19:49.824  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:19:49.827  4578  4592 D BtGatt.GattService: registerClient() - UUID=c9fc047b-c240-4ba7-a4cf-ee01ac8ad4aa
09-26 12:19:49.828  4578  4667 D BtGatt.GattService: onClientRegistered() - UUID=c9fc047b-c240-4ba7-a4cf-ee01ac8ad4aa, clientIf=5
,09-26 12:19:49.828  5605  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-26 12:19:49.828  4578  4811 D BtGatt.GattService: start scan with filters
09-26 12:19:49.831  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 12:19:49.832  4578  4672 D BtGatt.ScanManager: handling starting scan
09-26 12:19:49.832  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 12:19:49.832  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 12:19:49.832  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 12:19:49.835  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 12:19:49.836  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 12:19:49.836  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 12:19:49.837  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 12:19:49.839  4578  4667 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 12:19:49.839  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:49.840  4578  4672 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-26 12:19:49.840  5605  5652 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 12:19:49.843  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:49.843  5605  5652 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-26 12:19:49.843  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:49.843  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 12:19:49.843  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:49.843  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 12:19:49.844  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 12:19:49.844  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 12:19:49.844  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-26 12:19:49.844  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 12:19:49.844  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 12:19:49.844  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-26 12:19:49.845  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:49.846  4578  4824 D BtGatt.GattService: stopScan() - queue size =1
09-26 12:19:49.847  4578  4592 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 12:19:49.847  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:49.847  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 12:19:49.847  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 12:19:49.847  4578  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 12:19:49.847  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:49.847  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 12:19:49.847  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 12:19:49.847  4578  4672 D BtGatt.ScanManager: Starting BLE batch scan
09-26 12:19:49.847  4578  4672 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-26 12:19:49.848  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 12:19:49.849  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:49.849  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 12:19:49.849  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:19:49.849  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:19:49.850  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 12:19:49.850  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:19:49.850  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:49.850  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:19:49.850  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:49.850  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 12:19:49.851  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:49.851  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:49.851  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:49.851  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:49.851  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:19:49.853  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 12:19:49.853  5605  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 12:19:49.857  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 12:19:49.857  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 12:19:49.858  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 12:19:49.858  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 12:19:49.859  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:19:49.859  4578  4667 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 12:19:49.859  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:49.861  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:19:49.861  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:49.862  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:49.862  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 12:19:49.863  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:49.863  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:49.863  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:49.863  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:49.863  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:49.864  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:49.864  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:19:49.864  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:49.864  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:19:49.864  5605  5652 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-26 12:19:49.866  4578  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 12:19:49.866  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:49.867  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:19:49.867  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:19:49.867  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:19:49.869  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 12:19:49.871  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 12:19:49.873  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:19:49.873  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:19:49.873  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:19:49.873  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:19:49.873  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:19:49.873  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:19:49.873  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:19:49.873  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:19:49.874  4578  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 12:19:49.874  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:49.874  4578  4672 D BtGatt.ScanManager: stopping BLe Batch
,09-26 12:19:49.874  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 12:19:49.875  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:19:49.875  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 12:19:49.875  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 12:19:49.875  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 12:19:49.875  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:49.875  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:19:49.877  5605  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 12:19:49.879  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:49.880  4578  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 12:19:49.881  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:49.881  4578  4672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 12:19:49.882  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:19:49.884  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 12:19:49.884  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 12:19:49.884  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-26 12:19:49.885  4578  4667 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-26 12:19:49.885  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:49.885  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:49.887  4578  4592 D BtGatt.GattService: registerClient() - UUID=489be954-a512-47a7-85b0-154e628caf1a
09-26 12:19:49.887  4578  4667 D BtGatt.GattService: onClientRegistered() - UUID=489be954-a512-47a7-85b0-154e628caf1a, clientIf=5
,09-26 12:19:49.887  5605  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 12:19:49.888  4578  4591 D BtGatt.GattService: start scan with filters
,09-26 12:19:49.890  4578  4672 D BtGatt.ScanManager: handling starting scan
,09-26 12:19:49.890  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 12:19:49.890  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-26 12:19:49.890  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 12:19:49.891  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 12:19:49.893  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 12:19:49.893  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 12:19:49.893  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 12:19:49.894  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-26 12:19:49.895  4578  4667 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 12:19:49.895  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:49.895  4578  4672 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-26 12:19:49.896  5605  5652 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 12:19:49.900  4578  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-26 12:19:49.900  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:49.900  4578  4672 D BtGatt.ScanManager: Starting BLE batch scan
09-26 12:19:49.901  4578  4672 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 12:19:49.908  4578  4667 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 12:19:49.909  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:19:49.913  4578  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-26 12:19:49.913  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:19:50.210   928  3835 I ActivityManager: Killing 5047:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,09-26 12:19:50.394  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-26 12:19:50.394  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 12:19:50.394  5605  5605 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 12:19:50.503   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:51.504   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:51.971   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 12:19:51.974   928  2960 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 54
,09-26 12:19:52.505   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:19:53.505   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:19:54.897  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 12:19:54.897  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:54.897  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 12:19:54.897  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:54.898  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 12:19:54.898  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 12:19:54.898  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 12:19:54.898  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 12:19:54.898  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 12:19:54.898  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 12:19:54.899  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 12:19:54.901  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:19:54.902  4578  4591 D BtGatt.GattService: stopScan() - queue size =1
,09-26 12:19:54.904  4578  4824 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 12:19:54.905  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:54.905  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 12:19:54.906  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 12:19:54.906  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 12:19:54.906  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 12:19:54.910  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 12:19:54.910  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:54.910  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 12:19:54.910  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:19:54.912  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:19:54.913  4578  4578 D BtGatt.ScanManager: awakened up at time 149394
09-26 12:19:54.914  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:19:54.914  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:54.914  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 12:19:54.919  4578  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 12:19:54.919  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:19:54.919  5605  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 12:19:54.919  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:54.920  4578  4672 D BtGatt.ScanManager: stopping BLe Batch
,09-26 12:19:54.924  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 12:19:54.925  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 12:19:54.926  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 12:19:54.926  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:19:54.926  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:19:54.927  4578  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 12:19:54.927  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:19:54.927  4578  4672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 12:19:54.929  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 12:19:54.929  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:19:54.930  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 12:19:54.933  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:19:54.933  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 12:19:54.934  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 12:19:54.937  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 12:19:54.943  4578  4667 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-26 12:19:54.943  4578  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:19:54.943  4578  4667 D BtGatt.GattService: current time is 149424365506
,09-26 12:19:54.943  4578  4667 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -78, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -72, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -74, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -76, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-26 12:19:54.944  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 12:19:54.944  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-26 12:19:54.944  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-26 12:19:54.945  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-26 12:19:54.945  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-26 12:19:54.945  4578  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-26 12:19:54.990   928  2960 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-26 12:19:55.438  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 12:19:55.439  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 12:19:55.439  5605  5605 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 12:19:58.012   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 12:19:58.019   928  2960 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-26 12:19:59.915  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 12:19:59.916  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 12:19:59.916  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 12:19:59.916  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 12:19:59.916  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.917  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:19:59.917  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:59.917  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.917  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.917  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:59.917  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.919  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.919  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.924  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:59.924  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:59.924  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 12:19:59.926  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:59.927  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:59.927  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:59.927  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.927  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.928  5605  5652 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-26 12:19:59.930  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:59.930  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:59.931  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:59.931  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:59.931  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.931  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:19:59.931  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:59.931  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.932  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.932  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:59.932  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:19:59.932  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.934  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.934  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:19:59.936  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:59.936  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:59.936  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:59.937  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:19:59.938  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:59.938  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:59.938  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.938  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
,09-26 12:19:59.940  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-26 12:19:59.940  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:59.940  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 12:19:59.940  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:59.940  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:59.940  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:19:59.940  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.941  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:59.941  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 12:19:59.941  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.941  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:59.941  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:19:59.941  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.941  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.941  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.943  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 12:19:59.943  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:59.943  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:59.945  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:59.945  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:59.945  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:59.945  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.945  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.946  5605  5652 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-26 12:19:59.947  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:59.947  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:59.947  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:59.947  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:59.947  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.947  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.947  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:59.947  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.948  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.948  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:59.948  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.948  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.948  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.948  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:19:59.950  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:59.950  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:59.950  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:59.951  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:59.951  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:59.951  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:59.951  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.951  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.953  5605  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-26 12:19:59.953  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:59.953  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:59.953  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:59.953  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:59.953  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.953  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.954  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:59.954  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.954  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.954  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:59.954  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.954  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.954  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.954  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.956  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:59.956  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:59.956  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:59.957  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:59.957  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:59.957  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:59.957  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.957  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.959  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 12:19:59.959  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 12:19:59.959  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 12:19:59.959  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-26 12:19:59.959  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 12:19:59.960  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 12:19:59.960  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 12:19:59.960  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 12:19:59.960  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 12:19:59.960  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:59.960  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:59.960  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:59.960  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:59.960  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.960  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.961  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:59.961  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.961  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.961  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:59.961  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.961  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.961  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.961  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.963  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:59.963  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:59.963  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:59.964  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:59.964  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:59.964  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:59.964  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.965  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.966  5605  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 12:19:59.966  5605  5652 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-26 12:19:59.966  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-26 12:19:59.971  5605  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 12:19:59.971  5605  5652 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-26 12:19:59.972  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-26 12:19:59.972  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-26 12:19:59.972  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-26 12:19:59.972  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-26 12:19:59.972  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-26 12:19:59.972  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-26 12:19:59.972  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-26 12:19:59.972  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-26 12:19:59.973  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-26 12:19:59.974  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-26 12:19:59.975  5605  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-26 12:19:59.975  5605  5652 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 12:19:59.975  5605  5652 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-26 12:19:59.976  5605  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 12:19:59.976  5605  5652 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 12:19:59.976  5605  5652 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-26 12:19:59.976  5605  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 12:19:59.976  5605  5652 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 12:19:59.976  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-26 12:19:59.980  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-26 12:19:59.981  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-26 12:19:59.982  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-26 12:19:59.983  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-26 12:19:59.983  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-26 12:19:59.983  5605  5652 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-26 12:19:59.983  5605  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 12:19:59.984  5605  5652 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-26 12:19:59.984  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-26 12:19:59.985  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:59.985  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:59.985  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:59.986  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:59.986  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.986  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.986  5605  5653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 12:19:59.986  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-26 12:19:59.987  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:59.987  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.988  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.988  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:59.988  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.988  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.988  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.988  5605  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-26 12:19:59.988  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.988  5605  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-26 12:19:59.988  5605  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-26 12:19:59.989  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:59.989  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-26 12:19:59.989  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:59.989  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:59.984  4591  4591 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31022]" dev="sockfs" ino=31022 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 12:19:59.984  4591  4591 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31022]" dev="sockfs" ino=31022 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 12:19:59.990  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:59.990  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:59.990  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:59.990  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.990  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.991  5605  5652 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-26 12:19:59.992  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:59.992  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:59.992  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:59.993  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:59.993  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.993  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.993  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:59.993  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.993  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.993  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:59.993  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.993  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.993  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.993  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.994  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:59.994  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:59.994  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:59.995  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:59.995  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:59.995  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:59.995  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.995  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.996  5605  5652 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-26 12:19:59.996  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:19:59.996  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:19:59.996  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:19:59.996  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:19:59.997  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.997  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.997  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:19:59.997  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.997  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:19:59.997  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:19:59.997  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.997  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.997  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:19:59.997  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:19:59.998  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:19:59.998  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:19:59.998  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:19:59.999  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:19:59.999  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:19:59.999  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:19:59.999  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:19:59.999  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:00.000  5605  5652 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-26 12:20:00.000  5605  5652 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-26 12:20:00.000  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 12:20:00.000  5605  5652 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-26 12:20:00.000  5605  5652 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-26 12:20:00.000  5605  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-26 12:20:00.000  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 12:20:00.000  5605  5652 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-26 12:20:00.000  5605  5652 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-26 12:20:00.001  5605  5652 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-26 12:20:00.001  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 12:20:00.001  5605  5652 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-26 12:20:00.001  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:20:00.001  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:20:00.001  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:20:00.001  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:20:00.001  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:00.001  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:00.001  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:20:00.001  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:00.001  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:00.001  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:00.001  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:00.001  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:00.001  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:00.001  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:00.006  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:20:00.006  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:20:00.006  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:20:00.007  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:20:00.007  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:20:00.007  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:20:00.007  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:00.007  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:00.008  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:20:00.008  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:00.008  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:00.008  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:20:00.008  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:00.008  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:00.009  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:00.009  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:00.009  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:20:04.071   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 12:20:04.706  3562  5656 I VacuumService: Vacuum at: now=1474906804706 tag=VacuumService
,09-26 12:20:04.732  3562  5659 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,09-26 12:20:04.765  3562  5657 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-26 12:20:04.768  3562  5657 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-26 12:20:04.813  3562  5657 W Uploader:  no longer exists, so no auth token.
,09-26 12:20:04.819  3562  5659 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-26 12:20:05.010  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 12:20:05.010  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
,09-26 12:20:05.010  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 12:20:05.010  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.010  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:20:05.011  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
,09-26 12:20:05.011  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:20:05.011  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:20:05.011  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 12:20:05.011  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:20:05.011  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.012  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:05.012  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
,09-26 12:20:05.012  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.012  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:05.012  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:05.012  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.012  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:20:05.013  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.013  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:05.016  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:20:05.016  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 12:20:05.016  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 12:20:05.019  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:20:05.019  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:20:05.019  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:20:05.019  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.019  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:05.024  5605  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-26 12:20:05.025  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:20:05.028  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-26 12:20:05.030  5605  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-26 12:20:05.031  5605  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-26 12:20:05.032  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-26 12:20:05.032  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 12:20:05.032  5605  5605 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-26 12:20:05.033  5605  5663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 12:20:05.033  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:20:05.033  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-26 12:20:05.033  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-26 12:20:05.033  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-26 12:20:05.033  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:05.033  5605  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-26 12:20:05.033  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:20:05.033  5605  5605 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-26 12:20:05.033  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.034  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 12:20:05.034  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 12:20:05.034  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 12:20:05.034  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-26 12:20:05.031  4591  4591 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32406]" dev="sockfs" ino=32406 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 12:20:05.031  4591  4591 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32406]" dev="sockfs" ino=32406 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 12:20:05.035  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:20:05.035  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:20:05.035  5605  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-26 12:20:05.035  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:20:05.035  5605  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-26 12:20:05.036  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:20:05.036  5605  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-26 12:20:05.036  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 12:20:05.036  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:20:05.036  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:05.038  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 12:20:05.038  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:20:05.038  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:05.038  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:20:05.038  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:20:05.038  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:20:05.039  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:20:05.039  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:20:05.039  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:20:05.039  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.039  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:20:05.039  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:20:05.040  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.040  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:05.040  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:05.040  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.040  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 12:20:05.042  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:20:05.042  5605  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 12:20:05.047  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 12:20:05.048  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 12:20:05.048  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 12:20:05.048  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:20:05.049  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:20:05.051  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:20:05.052  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:20:05.053  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:20:05.053  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:20:05.053  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 12:20:05.054  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:20:05.054  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:20:05.054  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:20:05.054  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.054  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:05.054  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:20:05.054  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:20:05.054  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:20:05.056  5605  5652 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-26 12:20:05.056  5605  5652 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-26 12:20:05.056  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-26 12:20:05.056  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 12:20:05.056  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 12:20:05.057  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:20:05.057  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:20:05.057  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 12:20:05.057  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:20:05.057  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.057  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:20:05.057  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:20:05.057  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.057  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:05.057  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:05.057  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.057  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 12:20:05.059  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:20:05.059  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:20:05.061  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:20:05.065  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.065  5605  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-26 12:20:05.065  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:20:05.065  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 12:20:05.066  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:20:05.066  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:20:05.066  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:20:05.067  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:20:05.067  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:20:05.067  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:20:05.067  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.067  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
,09-26 12:20:05.072  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 12:20:05.073  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:20:05.073  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:20:05.073  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:20:05.073  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.073  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:05.073  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
,09-26 12:20:05.073  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.073  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:05.073  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:05.073  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:20:05.073  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:20:05.073  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.073  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:05.075  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:20:05.075  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:20:05.075  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:20:05.076  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:20:05.076  5605  5652 D BluetoothLeScanner: could not find callback wrapper
,09-26 12:20:05.076  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:20:05.076  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.076  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
,09-26 12:20:05.078  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 12:20:05.078  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:20:05.078  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:20:05.078  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:20:05.078  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.078  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:05.078  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4f2172 not in the list
09-26 12:20:05.078  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.078  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:05.078  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 12:20:05.078  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.078  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:05.078  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:05.078  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:05.080  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:20:05.080  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:20:05.080  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 12:20:05.081  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:20:05.081  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:20:05.081  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 12:20:05.081  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:05.081  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e29c3 not in the list
09-26 12:20:05.082  5605  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-26 12:20:05.082  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 12:20:05.082  5605  5652 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-26 12:20:05.082  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 12:20:05.082  5605  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-26 12:20:05.082  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-26 12:20:05.084  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-26 12:20:05.084  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-26 12:20:05.085  5605  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-26 12:20:05.085  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-26 12:20:05.085  5605  5652 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-26 12:20:05.085  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-26 12:20:05.085  5605  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-26 12:20:05.085  5605  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-26 12:20:05.086  5605  5652 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-26 12:20:05.086  5605  5652 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-26 12:20:05.086  5605  5652 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-26 12:20:05.086  5605  5652 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-26 12:20:05.087  5605  5652 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-26 12:20:05.087  5605  5652 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-26 12:20:05.089  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:20:05.089  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a86221 added. We now have 3 listener(s)
,09-26 12:20:05.089  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 12:20:05.091  5605  5652 D BluetoothAdapter: enable(): BT is already enabled..!
,09-26 12:20:05.091   928   939 D WifiService: setWifiEnabled: true pid=5605, uid=10077
09-26 12:20:05.092   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 12:20:05.116  4578  4779 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-26 12:20:05.116  4578  4803 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-26 12:20:05.464  3562  5668 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-26 12:20:05.534  3562  5657 W Uploader:  no longer exists, so no auth token.
,09-26 12:20:05.544  3562  5669 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-26 12:20:05.566  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 12:20:05.634  3562  5668 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-26 12:20:07.094   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 12:20:08.506   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:09.507   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:09.837   928  5365 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 12:20:10.097  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 12:20:10.098  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1e0646 added. We now have 4 listener(s)
,09-26 12:20:10.098  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 12:20:10.114  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 12:20:10.114  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1e0646 removed from the list
09-26 12:20:10.114  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:10.114  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:20:10.115  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:10.116  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 12:20:10.117  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d63007 added. We now have 4 listener(s)
09-26 12:20:10.117  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 12:20:10.120  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 12:20:10.120  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d63007 removed from the list
09-26 12:20:10.120  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:10.120  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:20:10.120  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:10.122  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:20:10.122  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3ec534 added. We now have 4 listener(s)
,09-26 12:20:10.122  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:20:10.126   928  3393 D WifiService: setWifiEnabled: false pid=5605, uid=10077
09-26 12:20:10.126   928  3393 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 12:20:10.133   928  2947 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-26 12:20:10.133   928  2947 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-26 12:20:10.134   928  2947 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 12:20:10.134   928  2947 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 12:20:10.136  4578  4663 D BluetoothAdapterState: Current state: ON, message: 23
,09-26 12:20:10.137  4578  4663 D BluetoothAdapterProperties: Setting state to 13
09-26 12:20:10.137  4578  4663 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-26 12:20:10.137  4578  4663 D BluetoothAdapterProperties: onBluetoothDisable()
09-26 12:20:10.138  4578  4663 I BluetoothAdapterState: Entering PendingCommandState
09-26 12:20:10.139  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:20:10.142  4578  4667 D BluetoothAdapterProperties: Scan Mode:20
,09-26 12:20:10.144  4578  4663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-26 12:20:10.146  4578  4578 D HeadsetService: Received stop request...Stopping profile...
,09-26 12:20:10.150   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-26 12:20:10.152  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.152  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:20:10.152  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.152  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.152  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:10.152  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.152  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:10.152  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:20:10.152  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:20:10.153  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.153  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:10.153   928  5366 D DhcpClient: Clearing IP address
09-26 12:20:10.153  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 12:20:10.154   507   922 D CommandListener: Setting iface cfg
09-26 12:20:10.156   928  5367 D DhcpClient: Receive thread stopped
,09-26 12:20:10.159  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 12:20:10.159  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.159  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.159  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.159  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:10.159  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.159  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.159  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:20:10.159  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:20:10.159  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 12:20:10.160  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 12:20:10.161  3562  5422 V NativeCrypto: Read error: ssl=0x7fab1d7580: I/O error during system call, Connection timed out
,09-26 12:20:10.163  3562  5422 V NativeCrypto: SSL shutdown failed: ssl=0x7fab1d7580: I/O error during system call, Broken pipe
09-26 12:20:10.164   928   941 I ActivityManager: Start proc 5673:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-26 12:20:10.164  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:10.165   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-26 12:20:10.165   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-26 12:20:10.167   928   928 D BluetoothHeadset: Proxy object disconnected
09-26 12:20:10.168  3762  4215 D BluetoothHeadset: Proxy object disconnected
,09-26 12:20:10.168  4578  4578 D BluetoothMapService: onReceive
09-26 12:20:10.168   928   928 D BluetoothHeadset: Proxy object disconnected
09-26 12:20:10.168   928   928 D BluetoothHeadset: Proxy object disconnected
09-26 12:20:10.168  4578  4578 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 12:20:10.169  3117  3962 D BluetoothHeadset: Proxy object disconnected
09-26 12:20:10.169  4578  4578 D BluetoothMapService: STATE_TURNING_OFF
09-26 12:20:10.169  3117  3117 D HeadsetProfile: Bluetooth service disconnected
09-26 12:20:10.169  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.169  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.169  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.169  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.169  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:10.169  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.169  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.169  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:20:10.169  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:20:10.169  4578  4578 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:10.169  4578  4578 V BluetoothAdapterState: isTurningOn()=false
,09-26 12:20:10.169  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:10.169  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:10.170  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.170  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:10.173   928   928 D RttService: SCAN_AVAILABLE : 1
09-26 12:20:10.173  4578  4578 D A2dpService: Received stop request...Stopping profile...
09-26 12:20:10.174   928  3055 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-26 12:20:10.174   547   547 E Parcel  : Reading a NULL string not supported here.
09-26 12:20:10.174  4578  4819 D A2dpStateMachine: Exit Disconnected: -1
09-26 12:20:10.174  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.174  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.174  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.174  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.174  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:10.174  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.174  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.174  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:10.174  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:20:10.175  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.175  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:10.175   928  2960 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-26 12:20:10.177  3117  3117 D BluetoothA2dp: Proxy object disconnected
09-26 12:20:10.177   928   928 D BluetoothA2dp: Proxy object disconnected
,09-26 12:20:10.177  4578  4578 D HidService: Received stop request...Stopping profile...
09-26 12:20:10.177  4578  4578 D HidService: Stopping Bluetooth HidService
09-26 12:20:10.178  3715  3878 W QCNEJ   : |CORE| network lost: 100
09-26 12:20:10.178   928  2947 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-26 12:20:10.178  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.178  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.178  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.178  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.178  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:10.178  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.178  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.178  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:10.178  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:20:10.178  3715  3878 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-26 12:20:10.178  3117  3117 D BluetoothInputDevice: Proxy object disconnected
09-26 12:20:10.178  3117  3117 D HidProfile: Bluetooth service disconnected
09-26 12:20:10.180  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.180  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.180  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.180  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.180  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:10.180  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.180  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.180  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:10.180  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:10.180   928  2947 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 12:20:10.180  4578  4578 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-26 12:20:10.180  4578  4578 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-26 12:20:10.180  4578  4667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-26 12:20:10.181  4578  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-26 12:20:10.181  4578  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 12:20:10.181  4578  4578 D BluetoothMapService: MAP Service closeService in
09-26 12:20:10.181  4578  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 12:20:10.181  4578  4578 D BluetoothMapMasInstance0: MAP Service shutdown
09-26 12:20:10.181  4578  4578 D ObexServerSockets0: shutdown(block = true)
09-26 12:20:10.181  4578  4667 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-26 12:20:10.181  4578  4578 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 12:20:10.181  4578  4578 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 12:20:10.181  4578  4826 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-26 12:20:10.181  4578  4803 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-26 12:20:10.182  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.182  4578  4827 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-26 12:20:10.182  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.182  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.182  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.182  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:10.182  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.182  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.182  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:10.182  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 12:20:10.183  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.183  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.183  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.183  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.183  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:10.183  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.183  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.183  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:10.183  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:10.184  4578  4578 I BtOppRfcommListener: stopping Accept Thread
09-26 12:20:10.184  4578  5280 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-26 12:20:10.185  4578  5280 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-26 12:20:10.186  4578  4578 D HealthService: Received stop request...Stopping profile...
09-26 12:20:10.187  4578  4578 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:10.187  4578  4578 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:10.187  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:10.187  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:10.188  4578  4578 D PanService: Received stop request...Stopping profile...
09-26 12:20:10.189  4578  4578 D BluetoothMapService: Received stop request...Stopping profile...
,09-26 12:20:10.189  4578  4578 D BluetoothMapService: stop()
,09-26 12:20:10.190  4578  4578 D BluetoothMapAppObserver: deinitObservers()
09-26 12:20:10.190  4578  4578 D BluetoothMapAppObserver: removeReceiver()
09-26 12:20:10.193  4578  4578 D SapService: Received stop request...Stopping profile...
09-26 12:20:10.193  4578  4578 V SapService: stop()
09-26 12:20:10.196  4578  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 12:20:10.196  4578  4667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-26 12:20:10.197  4578  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 12:20:10.197  4578  4779 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 12:20:10.197  4578  4779 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 12:20:10.197  4578  4779 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 12:20:10.197  4578  4779 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-26 12:20:10.197  4578  4578 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:10.197  4578  4578 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:10.197  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:10.197  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:10.197  4578  4578 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-26 12:20:10.197  4578  4578 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-26 12:20:10.198  3117  3117 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 12:20:10.198  3117  3117 D PanProfile: Bluetooth service disconnected
09-26 12:20:10.198  3117  3117 D BluetoothMap: Proxy object disconnected
09-26 12:20:10.198  3117  3117 D MapProfile: Bluetooth service disconnected
09-26 12:20:10.198  4578  4578 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:10.199  4578  4578 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:10.199  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:10.199  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:10.199  4578  4578 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-26 12:20:10.199  4578  4667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 12:20:10.200  4578  4667 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-26 12:20:10.200  4578  4578 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-26 12:20:10.200  4578  4578 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:10.200  4578  4578 V BluetoothAdapterState: isTurningOn()=false
,09-26 12:20:10.200  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:10.200  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:10.201  4578  4578 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-26 12:20:10.201  4578  4578 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-26 12:20:10.202  4578  4578 D BluetoothMapService: MAP Service closeService in
09-26 12:20:10.202  4578  4578 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:10.202  4578  4578 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:10.202  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:10.202  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:10.202  4578  4578 D BluetoothMapService: cleanup()
09-26 12:20:10.202  4578  4578 D BluetoothMapService: MAP Service closeService in
09-26 12:20:10.202  4578  4578 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:10.203  4578  4578 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:10.203  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:10.203  4578  4578 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:10.203  4578  4663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-26 12:20:10.203  4578  4663 D BluetoothAdapterProperties: Setting state to 15
09-26 12:20:10.203  4578  4663 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-26 12:20:10.203  4578  4663 I BluetoothAdapterState: Entering BleOnState
09-26 12:20:10.204  3117  3962 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-26 12:20:10.205  3117  3129 D BluetoothMap: onBluetoothStateChange: up=false
09-26 12:20:10.205  3117  3128 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 12:20:10.206  3117  3962 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-26 12:20:10.206   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-26 12:20:10.207   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:10.207  3762  3997 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:10.207   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:10.207  3117  3129 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:10.207   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:10.207  3117  3128 D BluetoothPan: onBluetoothStateChange on: false
09-26 12:20:10.208  4578  4663 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-26 12:20:10.208  4578  4663 D BluetoothAdapterProperties: Setting state to 16
09-26 12:20:10.208  4578  4663 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-26 12:20:10.209  4578  4663 D BluetoothAdapterProperties: onBleDisable
09-26 12:20:10.209  4578  4663 I BluetoothAdapterState: Entering PendingCommandState
09-26 12:20:10.209  4578  4664 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-26 12:20:10.210  4578  4667 D BluetoothAdapterProperties: Scan Mode:20
09-26 12:20:10.210  4578  4779 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-26 12:20:10.210  4578  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 12:20:10.211  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:10.213  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:10.214  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:10.215  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:10.217  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:10.218  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:10.222   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 12:20:10.237  5673  5673 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-26 12:20:10.245   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 12:20:10.246   928  2960 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-26 12:20:10.246   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 12:20:10.246   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-26 12:20:10.246   507   922 D TetherController: Setting IP forward enable = 0
09-26 12:20:10.249  5266  5266 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@bf9641b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-26 12:20:10.250  5673  5673 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-26 12:20:10.250   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-26 12:20:10.253  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:10.255  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:10.256  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:10.259  5035  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 12:20:10.259  5035  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-26 12:20:10.259  5035  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,09-26 12:20:10.259  5035  5059 E SarControlService: no key has been found,reset the power
09-26 12:20:10.259  5035  5072 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 12:20:10.260  5035  5072 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 12:20:10.260  5035  5072 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 12:20:10.260  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 12:20:10.260  5060  5060 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-26 12:20:10.262  5035  5072 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 12:20:10.262  5035  5072 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 12:20:10.262  5035  5072 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 12:20:10.263  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 12:20:10.263  5060  5060 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 12:20:10.265  5060  5074 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c955499 HexData = [00000000ea03000000000000ffffffff]
09-26 12:20:10.265  5060  5074 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 12:20:10.265  5060  5074 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,09-26 12:20:10.265  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 12:20:10.265  5035  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 12:20:10.266  5060  5074 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c955499 HexData = [00000000eb03000000000000ffffffff]
09-26 12:20:10.266  5060  5074 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 12:20:10.266  5060  5074 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-26 12:20:10.267  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 12:20:10.267  5035  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 12:20:10.272   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6c59afe:true
09-26 12:20:10.274  3562  3562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 12:20:10.285   928  3787 I ActivityManager: Start proc 5702:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-26 12:20:10.292   507   922 E Netd    : netlink response contains error (No such file or directory)
,09-26 12:20:10.293   507   922 D TetherController: Setting IP forward enable = 0
,09-26 12:20:10.295   928  2960 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-26 12:20:10.295   928  2947 D DhcpClient: doQuit
,09-26 12:20:10.296   928  2947 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-26 12:20:10.296   928  5366 D DhcpClient: onQuitting
09-26 12:20:10.297  3437  3437 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-26 12:20:10.301  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 12:20:10.300  5673  5673 D LocalBluetoothProfileManager: Adding local MAP profile
,09-26 12:20:10.302  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.302  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.302  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.302  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:10.302  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.302  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.302  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:10.302  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 12:20:10.303  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.303  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:10.305  5673  5673 D BluetoothMap: Create BluetoothMap proxy object
09-26 12:20:10.306  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.306  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.306  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.306  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.306  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:10.306  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.306  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.306  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:10.306  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:10.306  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.306  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:10.308  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.308  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:10.308  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:10.308  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:10.308  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:10.308  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:10.308  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:10.308  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:10.308  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 12:20:10.308  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:10.308  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:10.314  5673  5673 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-26 12:20:10.320  3437  3437 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-26 12:20:10.326  3437  3437 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-26 12:20:10.330  5673  5673 D DockEventReceiver: finishStartingService: stopping service
,09-26 12:20:10.334  5702  5702 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-26 12:20:10.336   928  3843 I ActivityManager: Killing 4975:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-26 12:20:10.359  3437  3437 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-26 12:20:10.370  3437  3437 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-26 12:20:10.414  4578  4667 I bt_hci  : shut_down
,09-26 12:20:10.417  4578  4673 D bt_hwcfg: hw_epilog_process
,09-26 12:20:10.417  4578  4673 I bt_vendor: low_power_mode_cb
,09-26 12:20:10.420  4578  4673 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-26 12:20:10.420  4578  4673 I bt_vendor: epilog_cb
09-26 12:20:10.420  4578  4673 I bt_hci  : epilog_finished_callback
09-26 12:20:10.421  4578  4667 I bt_hci_h4: hal_close
09-26 12:20:10.422  4578  4667 I bt_userial_vendor: device fd = 54 close
,09-26 12:20:10.472   928  2947 D wifi    : In wifi stop Hal
09-26 12:20:10.472   928  2947 D wifi    : halHandle = 0x7f8eae7540, mVM = 0x7fab14d140, mCls = 0x100a06
,09-26 12:20:10.473  5010  5010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 12:20:10.473   928  3436 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-26 12:20:10.473   928  3436 D WifiHAL : Got a signal to exit!!!
09-26 12:20:10.473   928  3436 I WifiHAL : Exit wifi_event_loop
09-26 12:20:10.474   928  2947 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-26 12:20:10.474   928  2947 E WifiHAL : Event processing terminated
09-26 12:20:10.474   928  2947 D wifi    : In wifi cleaned up handler
09-26 12:20:10.474   928  2947 I WifiHAL : Internal cleanup completed
09-26 12:20:10.474  4055  4210 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 12:20:10.476  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:10.478  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:10.480  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:10.495   928  3436 D wifi    : set interface wlan0 flags (DOWN)
,09-26 12:20:10.496   928  2947 D WifiNative-HAL: HAL event thread stopped successfully
,09-26 12:20:10.508   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:10.509  5702  5702 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 12:20:10.509  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-26 12:20:10.514  5702  5702 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-26 12:20:10.514  5702  5702 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 12:20:10.514  5702  5702 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-26 12:20:10.514  5,702  5702 D StrictMode: 	at com.google.r.e.b(PG:170)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 12:20:10.514  5702  5702 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.k.d(PG:583)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:170)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 12,:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 12:20:10.514  5702  5702 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 12:20:10.514  5702  5702 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 12:20:10.514  5702  5702 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 12:20:10.514  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 12:20:10.519  5673  5673 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 12:20:10.524  5673  5673 D DockEventReceiver: finishStartingService: stopping service
09-26 12:20:10.525  3562  3562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 12:20:10.527   928  3929 I ActivityManager: Killing 5396:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-26 12:20:10.560  4578  4664 D bt_stack_manager: event_shut_down_stack finished.
09-26 12:20:10.561  3842  3842 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 12:20:10.561  4578  4663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-26 12:20:10.562  4578  4663 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-26 12:20:10.562  4578  4578 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 12:20:10.563  4578  4578 D BtGatt.GattService: Received stop request...Stopping profile...
09-26 12:20:10.563  4578  4578 D BtGatt.GattService: stop()
09-26 12:20:10.563  4578  4578 D BtGatt.AdvertiseManager: advertise clients cleared
09-26 12:20:10.564  4578  4578 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:10.564  4578  4578 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:10.564  4578  4578 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:10.564  3842  3842 D SystemUpdateService: onCreate
09-26 12:20:10.564  4578  4578 V BluetoothAdapterState: isBleTurningOff()=true
09-26 12:20:10.564  4578  4663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-26 12:20:10.564  4578  4663 D BluetoothAdapterProperties: Setting state to 10
09-26 12:20:10.564  4578  4663 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-26 12:20:10.565  4578  4663 I BluetoothAdapterState: Entering OffState
09-26 12:20:10.565   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-26 12:20:10.570  4578  4578 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-26 12:20:10.570  4578  4578 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-26 12:20:10.571  4578  4578 I BluetoothServiceJni: cleanupNative: return from cleanup
09-26 12:20:10.572  4578  4664 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-26 12:20:10.575  3842  3842 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-26 12:20:10.579  4578  4578 I art     : System.exit called, status: 0
09-26 12:20:10.579  4578  4578 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-26 12:20:10.584  3842  3842 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-26 12:20:10.585  3842  5394 I iu.UploadsManager: num queued entries: 0
09-26 12:20:10.586  3842  5394 I iu.UploadsManager: num updated entries: 0
09-26 12:20:10.586  3842  5394 I iu.SyncManager: NEXT; no task
,09-26 12:20:10.591  3842  3842 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 12:20:10.592  3842  3842 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 12:20:10.601  3842  5736 I SystemUpdateService: active receiver: enabled
,09-26 12:20:10.604   928  3393 I ActivityManager: Start proc 5738:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-26 12:20:10.626   928  3393 I ActivityManager: Process com.android.bluetooth (pid 4578) has died
,09-26 12:20:10.634  3842  5736 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 12:20:10.646  5738  5738 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-26 12:20:10.649  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-26 12:20:10.660  3842  5736 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-26 12:20:10.661  3842  5736 I SystemUpdateService: now status is 0 (complete)
09-26 12:20:10.661  3842  5736 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 12:20:10.661  3842  5736 I SystemUpdateService: file has been verified
09-26 12:20:10.661  3842  5736 I SystemUpdateService: OTA package size = 21989297
,09-26 12:20:10.664  5738  5738 D SprintDMHelper: simOperator: 
,09-26 12:20:10.665  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 12:20:10.689  5010  5751 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-26 12:20:10.689   928  3393 I ActivityManager: Start proc 5752:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-26 12:20:10.699  3842  5736 I SystemUpdateService: showing system update notification
,09-26 12:20:10.699   928   945 D Tethering: InitialState.processMessage what=4
,09-26 12:20:10.703   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-26 12:20:10.730  5752  5752 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-26 12:20:10.739   928  3787 I ActivityManager: Killing 5266:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-26 12:20:10.773  3842  3842 D SystemUpdateService: onDestroy
,09-26 12:20:10.778   928  3393 I ActivityManager: Killing 4677:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-26 12:20:10.880  5702  5723 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-26 12:20:10.896   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@76d8ee0:true
,09-26 12:20:11.509   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:12.510   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:13.510   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:20:15.157   928   939 D WifiService: setWifiEnabled: true pid=5605, uid=10077
,09-26 12:20:15.157   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 12:20:15.166   507   922 D SoftapController: Softap fwReload - Ok
,09-26 12:20:15.170   507   922 D CommandListener: Setting iface cfg
,09-26 12:20:15.171   507   922 D CommandListener: Trying to bring down wlan0
,09-26 12:20:15.173   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-26 12:20:15.178   928  2947 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-26 12:20:15.736   928  2947 D wifi    : set interface wlan0 flags (UP)
,09-26 12:20:15.741   928  2947 I WifiHAL : Initializing wifi
09-26 12:20:15.741   928  2947 I WifiHAL : Creating socket
09-26 12:20:15.743   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-26 12:20:15.745   928  2947 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-26 12:20:15.746   928  2947 D wifi    : Did set static halHandle = 0x7f8eae7540
09-26 12:20:15.746   928  2947 D wifi    : halHandle = 0x7f8eae7540, mVM = 0x7fab14d140, mCls = 0x1946
09-26 12:20:15.746   928  2947 D wifi    : array field set
09-26 12:20:15.746   928  2947 I WifiNative-HAL: interface[0] = wlan0
09-26 12:20:15.749   928  5769 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547854644544
09-26 12:20:15.750   928  5769 D wifi    : waitForHalEvents called, vm = 0x7fab14d140, obj = 0x1946, env = 0x7f8effb740
,09-26 12:20:15.800  5770  5770 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-26 12:20:15.817  5770  5770 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 12:20:15.823  5770  5770 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 12:20:15.823  5770  5770 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-26 12:20:15.849   928  2947 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-26 12:20:15.855  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:15.857  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:15.859  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:15.864   928  2947 D WifiConfigStore: Loading config and enabling all networks 
,09-26 12:20:15.866  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 12:20:15.866  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:15.866  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:15.866  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:15.866  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:15.866  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:15.866  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:15.866  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:15.866  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:15.866  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:15.866  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 12:20:15.867  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:15.867  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:15.867  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:15.867  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:15.867  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:15.867  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:15.867  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:15.867  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:15.867  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:15.867  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:15.867  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 12:20:15.868  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:15.868  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:15.868  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:15.868  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:15.868  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:15.868  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:15.868  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:15.868  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:15.868  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:15.868  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:15.868  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 12:20:15.873   928  2947 D WifiConfigStore: loaded 0 passpoint configs
09-26 12:20:15.873   928  2947 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-26 12:20:15.874   928  2947 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-26 12:20:15.875   928  2947 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-26 12:20:15.876   928  2947 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-26 12:20:15.876   928  2947 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-26 12:20:15.876   928  2947 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-26 12:20:15.876   928  2947 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-26 12:20:15.879   928  2947 D WifiNative-HAL: Setting external_sim to 1
,09-26 12:20:15.880  5010  5010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 12:20:15.880   928  2947 D wifi    : setting dfs flag to true, 0x7f9287f800
09-26 12:20:15.880   928  2947 D WifiStateMachine: Setting OUI to DA-A1-19
09-26 12:20:15.881   928  2947 D wifi    : setting scan oui 0x7f9287f800
09-26 12:20:15.881   928  2947 D WifiHAL : Sending mac address OUI
,09-26 12:20:15.884   928  2947 E native  : do suspend false
,09-26 12:20:15.891   928   928 D RttService: SCAN_AVAILABLE : 3
,09-26 12:20:15.891   928  2947 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-26 12:20:15.891   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-26 12:20:15.891   928  3055 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-26 12:20:15.892   507   922 D CommandListener: Setting iface cfg
,09-26 12:20:15.896   928  2932 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-26 12:20:15.896   928  2932 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-26 12:20:15.905   928  2932 D WifiNative-HAL: p2pGetDeviceAddress
,09-26 12:20:15.905   928  2932 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-26 12:20:15.910   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=170391 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-26 12:20:19.070  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 12:20:19.075  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 12:20:19.080  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 12:20:19.084  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 12:20:19.131   928  2947 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-26 12:20:19.132   928  2947 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-26 12:20:19.133   928  2947 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 12:20:19.144   928  2947 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-26 12:20:19.179   928  2947 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-26 12:20:19.182  5770  5770 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-26 12:20:19.603  5770  5770 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-26 12:20:19.642  5770  5770 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-26 12:20:19.642  5770  5770 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-26 12:20:19.651   928  2947 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 12:20:19.651   928  2947 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-26 12:20:19.652   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-26 12:20:19.669   928  2947 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 12:20:19.684   507   922 D CommandListener: Setting iface cfg
,09-26 12:20:19.690   928  2947 D WifiStateMachine: Start Dhcp Watchdog 2
,09-26 12:20:19.696   928  5776 D DhcpClient: Receive thread started
,09-26 12:20:19.701   928  2947 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-26 12:20:19.701   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-26 12:20:19.701   928  2960 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-26 12:20:19.781   928  2947 E native  : do suspend false
,09-26 12:20:19.795   928  5775 D DhcpClient: Broadcasting DHCPDISCOVER
,09-26 12:20:19.842   928  5776 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172666, domain null
,09-26 12:20:19.842   928  5775 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172666 seconds
,09-26 12:20:19.844   928  5775 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-26 12:20:19.856   928  5776 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-26 12:20:19.857   928  5775 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-26 12:20:19.860   507   922 D CommandListener: Setting iface cfg
09-26 12:20:19.863   928  2947 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-26 12:20:19.868   928  5775 D DhcpClient: Scheduling renewal in 86399s
,09-26 12:20:19.880   928  2947 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-26 12:20:19.881   928  2947 D WifiConfigStore: No blacklist allowed without epno enabled
,09-26 12:20:19.882   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-26 12:20:19.893   928  2960 D ConnectivityService: Adding iface wlan0 to network 101
09-26 12:20:19.892   928  2947 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-26 12:20:19.940   928  2960 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-26 12:20:19.942   928  2960 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-26 12:20:19.944   928  2960 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-26 12:20:19.945   928  2960 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-26 12:20:19.947   928  2960 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-26 12:20:19.954   928  2960 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-26 12:20:19.958   928  2960 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-26 12:20:19.958   928  2960 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-26 12:20:19.958   928  2960 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-26 12:20:19.958   928  2947 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-26 12:20:19.958   928  2960 D ConnectivityService:    accepting network in place of null
09-26 12:20:19.958   928  2947 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 12:20:19.960   928  2960 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 12:20:19.977   928  5774 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174458, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 12:20:19.980   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 12:20:20.001   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 12:20:20.004   928  2960 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-26 12:20:20.004  3715  3878 W QCNEJ   : |CORE| network available: 101
09-26 12:20:20.004   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 12:20:20.005   928  2960 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-26 12:20:20.006   928   945 D Tethering: MasterInitialState.processMessage what=3
09-26 12:20:20.008  3715  3878 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-26 12:20:20.011  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.011  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:20.011  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:20.011  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:20.011  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:20.011  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:20.011  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:20.011  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:20:20.011  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:20:20.011  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.011  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:20.012  3715  3878 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-26 12:20:20.013  3715  3878 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-26 12:20:20.013  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.014  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:20.014  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:20.014  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:20.014  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:20.014  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:20.014  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:20.014  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:20:20.014  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:20:20.014  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.014  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:20.016  5035  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 12:20:20.017  5035  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 12:20:20.018  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.018  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:20.018  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:20.018  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:20.018  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:20.018  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:20.018  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:20.018  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:20:20.018  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:20:20.018  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.018  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:20.018  5035  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-26 12:20:20.018  5035  5059 E SarControlService: no key has been found,reset the power
09-26 12:20:20.019  5035  5072 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 12:20:20.019  5035  5072 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 12:20:20.019  5035  5072 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 12:20:20.020  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 12:20:20.020  5060  5060 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 12:20:20.021  5035  5072 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 12:20:20.021  5035  5072 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 12:20:20.021  5035  5072 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 12:20:20.022  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 12:20:20.022  5060  5060 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 12:20:20.026  3842  3842 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 12:20:20.027  5060  5074 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c955499 HexData = [00000000ec03000000000000ffffffff]
09-26 12:20:20.027  5060  5074 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 12:20:20.027  5060  5074 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-26 12:20:20.030  5060  5074 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c955499 HexData = [00000000ed03000000000000ffffffff]
09-26 12:20:20.030  5060  5074 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 12:20:20.030  5060  5074 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-26 12:20:20.030  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 12:20:20.031  5035  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 12:20:20.031  3842  3842 D SystemUpdateService: onCreate
09-26 12:20:20.032  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 12:20:20.032  5035  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 12:20:20.034  3842  3842 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-26 12:20:20.047  3842  3842 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-26 12:20:20.047   928  5773 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-26 12:20:20.053  3842  5394 I iu.UploadsManager: num queued entries: 0
09-26 12:20:20.053  3842  5394 I iu.UploadsManager: num updated entries: 0
09-26 12:20:20.053  3842  5394 I iu.SyncManager: NEXT; no task
09-26 12:20:20.056  3842  5786 I SystemUpdateService: active receiver: enabled
09-26 12:20:20.057  3842  3842 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-26 12:20:20.059  3842  3842 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-26 12:20:20.061  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-26 12:20:20.064  5738  5738 D SprintDMHelper: simOperator: 
09-26 12:20:20.064  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-26 12:20:20.087  3842  5786 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 12:20:20.098  3842  5786 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-26 12:20:20.099  3842  5786 I SystemUpdateService: now status is 0 (complete)
09-26 12:20:20.099  3842  5786 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 12:20:20.099  3842  5786 I SystemUpdateService: file has been verified
09-26 12:20:20.099  3842  5786 I SystemUpdateService: OTA package size = 21989297
,09-26 12:20:20.103   928  5773 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 26 Sep 2016 16:20:20 GMT], X-Android-Received-Millis=[1474906820102], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474906820077]}
,09-26 12:20:20.103   928  2960 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-26 12:20:20.104   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-26 12:20:20.104   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-26 12:20:20.104  3842  5786 I SystemUpdateService: showing system update notification
09-26 12:20:20.105   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-26 12:20:20.113  3842  3842 D SystemUpdateService: onDestroy
,09-26 12:20:20.164   928  3857 D WifiService: setWifiEnabled: false pid=5605, uid=10077
09-26 12:20:20.164   928  3857 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 12:20:20.165   928  2947 D WifiStateMachine: WifiStateMachine: Leaving Connected state,
09-26 12:20:20.166   928  2947 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-26 12:20:20.166   928  2947 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 12:20:20.166   928  2947 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 12:20:20.174   928  5775 D DhcpClient: Clearing IP address
,09-26 12:20:20.174   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-26 12:20:20.176   507   922 D CommandListener: Setting iface cfg
09-26 12:20:20.177  5010  5791 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-26 12:20:20.179   928  5776 D DhcpClient: Receive thread stopped
,09-26 12:20:20.184  3562  5797 V NativeCrypto: Read error: ssl=0x7f8fe82000: I/O error during system call, Connection timed out
,09-26 12:20:20.185  3562  5797 V NativeCrypto: SSL shutdown failed: ssl=0x7f8fe82000: I/O error during system call, Broken pipe
,09-26 12:20:20.186   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-26 12:20:20.186   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-26 12:20:20.191   928  2960 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-26 12:20:20.191   547   547 E Parcel  : Reading a NULL string not supported here.
09-26 12:20:20.192  3715  3878 W QCNEJ   : |CORE| network lost: 101
09-26 12:20:20.193   928   928 D RttService: SCAN_AVAILABLE : 1
09-26 12:20:20.194   928  3055 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-26 12:20:20.194  3715  3878 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-26 12:20:20.195   928  2947 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-26 12:20:20.199   928  2947 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-26 12:20:20.217   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 12:20:20.238   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-26 12:20:20.238   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-26 12:20:20.239   928  2960 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-26 12:20:20.239   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-26 12:20:20.241   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-26 12:20:20.244  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.244  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:20.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:20.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:20.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:20.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:20.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:20.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:20.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:20.244  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.244  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 12:20:20.245  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.245  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:20.245  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:20.245  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:20.245  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:20.245  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:20.245  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:20.245  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:20.245  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:20.245  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.245  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 12:20:20.245   928  2947 D DhcpClient: doQuit
09-26 12:20:20.246   928  2947 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-26 12:20:20.246   928  5775 D DhcpClient: onQuitting
09-26 12:20:20.246  5770  5770 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-26 12:20:20.247  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.247  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:20.247  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:20.247  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:20.247  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:20.247  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:20.247  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:20.247  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:20.247  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:20.247  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.247  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:20.250  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.250  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:20.250  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:20.250  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:20.250  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:20.250  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:20.250  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:20.250  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:20.250  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:20.250  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.251  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:20.252  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.252  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:20.252  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:20.252  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:20.252  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:20.252  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:20.252  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:20.252  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:20.252  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:20.252  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.252  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:20.253  3842  3842 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 12:20:20.253  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.253  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:20.253  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:20.253  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:20.253  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:20.253  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:20.253  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:20.253  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:20.253  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:20.253  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:20.253  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:20.255  5035  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 12:20:20.255  5035  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 12:20:20.255  5035  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-26 12:20:20.255  5035  5059 E SarControlService: no key has been found,reset the power
09-26 12:20:20.255  5035  5072 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 12:20:20.255  5035  5072 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 12:20:20.255  5035  5072 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 12:20:20.256  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 12:20:20.256  5060  5060 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 12:20:20.257  5035  5072 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 12:20:20.257  5035  5072 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 12:20:20.257  5035  5072 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 12:20:20.258  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 12:20:20.258  5060  5060 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 12:20:20.261  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-26 12:20:20.261  3842  3842 D SystemUpdateService: onCreate
09-26 12:20:20.263  5060  5074 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c955499 HexData = [00000000ee03000000000000ffffffff]
09-26 12:20:20.263  5060  5074 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 12:20:20.263  5060  5074 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-26 12:20:20.263  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 12:20:20.263  5035  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 12:20:20.265  5770  5770 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-26 12:20:20.266  5060  5074 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c955499 HexData = [00000000ef03000000000000ffffffff]
09-26 12:20:20.266  5060  5074 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 12:20:20.266  5060  5074 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-26 12:20:20.267  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 12:20:20.267  5035  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 12:20:20.268  3842  3842 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-26 12:20:20.272  3842  5807 I SystemUpdateService: active receiver: enabled
09-26 12:20:20.278  3842  3842 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-26 12:20:20.283  3842  5394 I iu.UploadsManager: num queued entries: 0
09-26 12:20:20.283  3842  5394 I iu.UploadsManager: num updated entries: 0
09-26 12:20:20.284  3842  5394 I iu.SyncManager: NEXT; no task
09-26 12:20:20.286  3842  3842 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-26 12:20:20.287  3842  3842 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-26 12:20:20.289  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-26 12:20:20.292  5770  5770 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-26 12:20:20.292  5738  5738 D SprintDMHelper: simOperator: 
09-26 12:20:20.293  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-26 12:20:20.294   507   922 E Netd    : netlink response contains error (No such file or directory)
09-26 12:20:20.294  3842  5807 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-26 12:20:20.295   928  2960 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-26 12:20:20.303  5770  5770 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-26 12:20:20.304  5010  5811 I Babel   : connection state changed from CONNECTED to DISCONNECTED
09-26 12:20:20.304  3842  5807 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-26 12:20:20.305  3842  5807 I SystemUpdateService: now status is 0 (complete)
09-26 12:20:20.305  3842  5807 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 12:20:20.305  3842  5807 I SystemUpdateService: file has been verified
09-26 12:20:20.305  3842  5807 I SystemUpdateService: OTA package size = 21989297
09-26 12:20:20.319  3842  5807 I SystemUpdateService: showing system update notification
,09-26 12:20:20.329  3842  3842 D SystemUpdateService: onDestroy
,09-26 12:20:20.405   928  2947 D wifi    : In wifi stop Hal
09-26 12:20:20.406   928  2947 D wifi    : halHandle = 0x7f8eae7540, mVM = 0x7fab14d140, mCls = 0x1946
,09-26 12:20:20.407  5010  5010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 12:20:20.408   928  5769 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-26 12:20:20.408   928  5769 D WifiHAL : Got a signal to exit!!!
09-26 12:20:20.408   928  5769 I WifiHAL : Exit wifi_event_loop
09-26 12:20:20.408  4055  4210 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 12:20:20.408  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:20.409   928  2947 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-26 12:20:20.409   928  2947 E WifiHAL : Event processing terminated
09-26 12:20:20.409   928  2947 D wifi    : In wifi cleaned up handler
09-26 12:20:20.409   928  2947 I WifiHAL : Internal cleanup completed
09-26 12:20:20.410  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:20.410  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:20.434   928  5769 D wifi    : set interface wlan0 flags (DOWN)
,09-26 12:20:20.434   928  2947 D WifiNative-HAL: HAL event thread stopped successfully
,09-26 12:20:20.640   928   945 D Tethering: InitialState.processMessage what=4
,09-26 12:20:20.647   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-26 12:20:21.005   928  2960 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-26 12:20:25.202   928   945 I ActivityManager: Start proc 5813:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-26 12:20:25.299  5813  5813 D AdapterServiceConfig: Adding HeadsetService
,09-26 12:20:25.299  5813  5813 D AdapterServiceConfig: Adding A2dpService
09-26 12:20:25.299  5813  5813 D AdapterServiceConfig: Adding HidService
09-26 12:20:25.300  5813  5813 D AdapterServiceConfig: Adding HealthService
09-26 12:20:25.300  5813  5813 D AdapterServiceConfig: Adding PanService
09-26 12:20:25.300  5813  5813 D AdapterServiceConfig: Adding GattService
09-26 12:20:25.300  5813  5813 D AdapterServiceConfig: Adding BluetoothMapService
09-26 12:20:25.300  5813  5813 D AdapterServiceConfig: Adding SapService
,09-26 12:20:25.314   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8f81ff7:true
,09-26 12:20:25.314  5813  5813 D BluetoothAdapterState: make() - Creating AdapterState
,09-26 12:20:25.318  5813  5813 I bt_bluedroid: init
,09-26 12:20:25.318  5813  5825 I BluetoothAdapterState: Entering OffState
,09-26 12:20:25.321  5813  5826 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-26 12:20:25.321  5813  5826 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-26 12:20:25.321  5813  5826 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-26 12:20:25.321  5813  5826 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-26 12:20:25.322  5813  5813 I bt_bluedroid: get_profile_interface socket
,09-26 12:20:25.324  5813  5829 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 12:20:25.324  5813  5813 I bt_bluedroid: get_profile_interface sdp
09-26 12:20:25.325  5813  5829 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 12:20:25.329  5813  5824 I bt_bluedroid: config_hci_snoop_log
09-26 12:20:25.330   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-26 12:20:25.334  5813  5825 D BluetoothAdapterState: Current state: OFF, message: 0
09-26 12:20:25.334  5813  5825 D BluetoothAdapterProperties: Setting state to 14
09-26 12:20:25.334  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-26 12:20:25.336  5813  5825 D BluetoothBondStateMachine: make
,09-26 12:20:25.337  5813  5830 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-26 12:20:25.340  5813  5825 I BluetoothAdapterState: Entering PendingCommandState
,09-26 12:20:25.341  5813  5813 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-26 12:20:25.343  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:25.344  5813  5813 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 12:20:25.344  5813  5813 D BtGatt.GattService: Received start request. Starting profile...
,09-26 12:20:25.345  5813  5813 D BtGatt.GattService: start()
09-26 12:20:25.345  5813  5813 I bt_bluedroid: get_profile_interface gatt
,09-26 12:20:25.346  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
09-26 12:20:25.346  5813  5813 D BtGatt.AdvertiseManager: advertise manager created
,09-26 12:20:25.352  5813  5813 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:25.352  5813  5813 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:25.352  5813  5813 V BluetoothAdapterState: isBleTurningOn()=true
09-26 12:20:25.352  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:25.352  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-26 12:20:25.353  5813  5825 I bt_bluedroid: bt_bluedroid
09-26 12:20:25.353  5813  5826 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-26 12:20:25.354  5813  5826 I bt_hci  : start_up
,09-26 12:20:25.358  5813  5826 I bt_vendor: alloc value 0xf3da3871
,09-26 12:20:25.359  5813  5826 I bt_vendor: init
09-26 12:20:25.359  5813  5826 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-26 12:20:25.359  5813  5826 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-26 12:20:25.469  5813  5826 D bt_hci  : start_up starting async portion
,09-26 12:20:25.470  5813  5833 I bt_hci  : event_finish_startup
09-26 12:20:25.470  5813  5833 I bt_hci_h4: hal_open
09-26 12:20:25.470  5813  5833 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-26 12:20:25.467  5834  5834 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-26 12:20:25.473  5813  5833 I bt_userial_vendor: device fd = 54 open
,09-26 12:20:25.487  5813  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 12:20:25.490  5813  5833 D bt_hwcfg: Chipset BCM4358A3
,09-26 12:20:25.490  5813  5833 D bt_hwcfg: Target name = [BCM4358A3]
09-26 12:20:25.490  5813  5833 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-26 12:20:25.875  5813  5833 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-26 12:20:25.876  5813  5833 D bt_hwcfg: Settlement delay -- 100 ms
09-26 12:20:25.876  5813  5833 I bt_hwcfg: Setting fw settlement delay to 100 
,09-26 12:20:26.010  5813  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-26 12:20:26.010  5813  5833 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-26 12:20:26.012  5813  5833 I bt_hwcfg: vendor lib fwcfg completed
09-26 12:20:26.012  5813  5833 I bt_vendor: firmware callback
09-26 12:20:26.012  5813  5833 I bt_hci  : firmware_config_callback
,09-26 12:20:26.021  5813  5836 I bt_btu  : btu_task pending for preload complete event
,09-26 12:20:26.021  5813  5836 I bt_btu_task: Bluetooth chip preload is complete
,09-26 12:20:26.021  5813  5836 I bt_btu  : btu_task received preload complete event
,09-26 12:20:26.028  5813  5836 I         : BTE_InitTraceLevels -- TRC_HCI
,09-26 12:20:26.028  5813  5836 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-26 12:20:26.028  5813  5836 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-26 12:20:26.029  5813  5836 I         : BTE_InitTraceLevels -- TRC_AVDT
09-26 12:20:26.029  5813  5836 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-26 12:20:26.029  5813  5836 I         : BTE_InitTraceLevels -- TRC_A2D
09-26 12:20:26.030  5813  5836 I         : BTE_InitTraceLevels -- TRC_BNEP
09-26 12:20:26.030  5813  5836 I         : BTE_InitTraceLevels -- TRC_BTM
09-26 12:20:26.030  5813  5836 I         : BTE_InitTraceLevels -- TRC_GAP
,09-26 12:20:26.030  5813  5836 I         : BTE_InitTraceLevels -- TRC_PAN
09-26 12:20:26.030  5813  5836 I         : BTE_InitTraceLevels -- TRC_SDP
09-26 12:20:26.030  5813  5836 I         : BTE_InitTraceLevels -- TRC_GATT
09-26 12:20:26.030  5813  5836 I         : BTE_InitTraceLevels -- TRC_SMP
09-26 12:20:26.031  5813  5836 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-26 12:20:26.031  5813  5836 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-26 12:20:26.113  5813  5836 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d21549
,09-26 12:20:26.113  5813  5836 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d21549 
,09-26 12:20:26.130  5813  5829 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-26 12:20:26.131  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-26 12:20:26.132  5813  5829 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 12:20:26.135  5813  5829 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 12:20:26.138  5813  5829 D BluetoothAdapterProperties: Scan Mode:20
,09-26 12:20:26.138  5813  5829 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-26 12:20:26.139  5813  5829 D bt_hci  : do_postload posting postload work item
,09-26 12:20:26.139  5813  5833 I bt_hci  : event_postload
,09-26 12:20:26.139  5813  5833 I bt_vendor: sco_config_cb
09-26 12:20:26.139  5813  5833 I bt_hci  : sco_config_callback postload finished.
09-26 12:20:26.144  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:26.147  5813  5833 I bt_vendor: low_power_mode_cb
09-26 12:20:26.147  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:26.151  5813  5829 D bt_bte_conf: Device ID record 1 : primary
09-26 12:20:26.151  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:26.151  5813  5829 D bt_bte_conf:   vendorId            = 000f
09-26 12:20:26.151  5813  5829 D bt_bte_conf:   vendorIdSource      = 0001
09-26 12:20:26.151  5813  5829 D bt_bte_conf:   product             = 1200
09-26 12:20:26.151  5813  5829 D bt_bte_conf:   version             = 1436
09-26 12:20:26.151  5813  5829 D bt_bte_conf:   clientExecutableURL = 
09-26 12:20:26.152  5813  5829 D bt_bte_conf:   serviceDescription  = 
,09-26 12:20:26.152  5813  5829 D bt_bte_conf:   documentationURL    = 
09-26 12:20:26.152  5813  5829 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-26 12:20:26.152  5813  5826 D bt_stack_manager: event_start_up_stack finished
09-26 12:20:26.153  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-26 12:20:26.153  5813  5825 D BluetoothAdapterProperties: Setting state to 15
09-26 12:20:26.153  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-26 12:20:26.154  5813  5825 I BluetoothAdapterState: Entering BleOnState
,09-26 12:20:26.157  5813  5825 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-26 12:20:26.157  5813  5825 D BluetoothAdapterProperties: Setting state to 11
09-26 12:20:26.157  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-26 12:20:26.163  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:26.164  5813  5813 D HeadsetService: Received start request. Starting profile...
09-26 12:20:26.166  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:26.167  5813  5813 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-26 12:20:26.167  5813  5813 D HeadsetStateMachine: make
09-26 12:20:26.168  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:26.170  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:26.180  5813  5813 D HeadsetStateMachine: max_hf_connections = 1
,09-26 12:20:26.180  5813  5813 I bt_bluedroid: get_profile_interface handsfree
09-26 12:20:26.180  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-26 12:20:26.180  5813  5829 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-26 12:20:26.181  5813  5825 I BluetoothAdapterState: Entering PendingCommandState
,09-26 12:20:26.184  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:26.185  5813  5813 D A2dpService: Received start request. Starting profile...
,09-26 12:20:26.185  3562  3562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 12:20:26.186  5813  5813 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-26 12:20:26.186  5813  5813 I bt_bluedroid: get_profile_interface avrcp
,09-26 12:20:26.192  5813  5813 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-26 12:20:26.192  5813  5813 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-26 12:20:26.192  5813  5813 D A2dpStateMachine: make
09-26 12:20:26.193  5813  5813 I bt_bluedroid: get_profile_interface a2dp
09-26 12:20:26.193  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-26 12:20:26.195  5813  5844 D A2dpStateMachine: Enter Disconnected: -2
09-26 12:20:26.195  5813  5813 I BluetoothHidServiceJni: classInitNative: succeeds
09-26 12:20:26.196  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:26.197  5673  5673 D BluetoothInputDevice: Proxy object connected
,09-26 12:20:26.198  5673  5673 D HidProfile: Bluetooth service connected
,09-26 12:20:26.199  5813  5813 D HidService: Received start request. Starting profile...
,09-26 12:20:26.199  5813  5813 I bt_bluedroid: get_profile_interface hidhost
09-26 12:20:26.199  5813  5813 D HidService: setHidService(): set to: null
09-26 12:20:26.199  5813  5829 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d0256d
09-26 12:20:26.200  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-26 12:20:26.200  5813  5813 I BluetoothHealthServiceJni: classInitNative: succeeds
09-26 12:20:26.201  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
09-26 12:20:26.201  5813  5813 D HealthService: Received start request. Starting profile...
09-26 12:20:26.203  5813  5813 I bt_bluedroid: get_profile_interface health
,09-26 12:20:26.205  5813  5813 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-26 12:20:26.205  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
09-26 12:20:26.207  5673  5673 D BluetoothPan: BluetoothPAN Proxy object connected
,09-26 12:20:26.207  5813  5813 D PanService: Received start request. Starting profile...
09-26 12:20:26.207  5813  5813 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-26 12:20:26.207  5673  5673 D PanProfile: Bluetooth service connected
09-26 12:20:26.207  5813  5813 I bt_bluedroid: get_profile_interface pan
09-26 12:20:26.208  5813  5829 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-26 12:20:26.210  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:26.211  5813  5813 D BluetoothMapService: Received start request. Starting profile...
09-26 12:20:26.211  5813  5813 D BluetoothMapService: start()
09-26 12:20:26.211  5673  5673 D BluetoothMap: Proxy object connected
09-26 12:20:26.212  5673  5673 D MapProfile: Bluetooth service connected
09-26 12:20:26.212  5673  5673 D BluetoothMap: getConnectedDevices()
09-26 12:20:26.213  5673  5673 D BluetoothMap: Bluetooth is Not enabled
,09-26 12:20:26.214  5813  5813 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-26 12:20:26.215  5813  5813 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-26 12:20:26.215  5813  5813 D BluetoothMapAppObserver: createReceiver()
,09-26 12:20:26.217  5813  5813 D BluetoothMapAppObserver: initObservers()
,09-26 12:20:26.217  5813  5813 D BluetoothMapAppObserver: getEnabledAccountItems()
09-26 12:20:26.224  5813  5813 V SapService: SapBinder()
09-26 12:20:26.224  5813  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:26.224  5813  5813 D SapService: Received start request. Starting profile...
09-26 12:20:26.224  5813  5813 V SapService: start()
,09-26 12:20:26.226  5813  5813 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:26.226  5813  5813 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:26.226  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:26.226  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 12:20:26.226  5813  5842 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:26.227  5813  5813 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isTurningOff()=false
,09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:26.228  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:26.229  5813  5813 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:26.229  5813  5813 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:26.229  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:26.229  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:26.229  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-26 12:20:26.229  5813  5825 D BluetoothAdapterProperties: ScanMode =  20
09-26 12:20:26.230  5813  5825 D BluetoothAdapterProperties: State =  11
,09-26 12:20:26.230  5813  5825 D BluetoothAdapterProperties: Setting state to 12
09-26 12:20:26.230  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-26 12:20:26.230  3117  3128 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 12:20:26.232  5813  5825 I BluetoothAdapterState: Entering OnState
09-26 12:20:26.233  5813  5829 D BluetoothAdapterProperties: Scan Mode:21
09-26 12:20:26.233  5813  5829 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 12:20:26.233  3117  3129 D BluetoothMap: onBluetoothStateChange: up=true
09-26 12:20:26.234  3117  3117 D BluetoothA2dp: Proxy object connected
09-26 12:20:26.236  3117  5799 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 12:20:26.237  3117  3117 D BluetoothMap: Proxy object connected
09-26 12:20:26.237  3117  3117 D MapProfile: Bluetooth service connected
09-26 12:20:26.237  3117  3117 D BluetoothMap: getConnectedDevices()
,09-26 12:20:26.238  5673  5688 D BluetoothMap: onBluetoothStateChange: up=true
,09-26 12:20:26.238  3117  3128 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 12:20:26.239  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:26.239  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:26.239  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:26.239  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:26.239  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:26.239  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:26.239  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:26.239  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 12:20:26.240   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 12:20:26.240  3117  3117 D BluetoothInputDevice: Proxy object connected
09-26 12:20:26.240  3117  3117 D HidProfile: Bluetooth service connected
09-26 12:20:26.240   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 12:20:26.241   928   928 D BluetoothA2dp: Proxy object connected
,09-26 12:20:26.241  5673  5687 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 12:20:26.241  3762  3786 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 12:20:26.241  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:26.242  5673  5688 D BluetoothPan: onBluetoothStateChange on: true
09-26 12:20:26.242   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 12:20:26.242  5673  5687 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 12:20:26.243  5813  5813 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 12:20:26.243  3117  3129 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 12:20:26.244  5813  5813 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-26 12:20:26.244   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 12:20:26.244  3117  5799 D BluetoothPan: onBluetoothStateChange on: true
09-26 12:20:26.244  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:26.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:26.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:26.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:26.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:26.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:26.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:26.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:26.245  5813  5813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 12:20:26.245  3117  3117 D BluetoothPan: BluetoothPAN Proxy object connected
,09-26 12:20:26.246  3117  3117 D PanProfile: Bluetooth service connected
09-26 12:20:26.246  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:26.246   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-26 12:20:26.250  5813  5813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 12:20:26.251  5673  5673 D LocalBluetoothProfileManager: Adding local A2DP profile
09-26 12:20:26.251  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:26.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:26.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:26.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:26.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:26.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:26.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:26.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:26.251  5813  5813 D ObexServerSockets: Succeed to create listening sockets 
09-26 12:20:26.251  5813  5813 D ObexServerSockets0: startAccept()
09-26 12:20:26.252  5813  5813 D ObexServerSockets0: prepareForNewConnect()
,09-26 12:20:26.254  5813  5813 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-26 12:20:26.254  5813  5813 D BluetoothSdpJni: SDP Create record success - handle: 0
09-26 12:20:26.254  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:26.254  5813  5813 D BluetoothMapService: onReceive
09-26 12:20:26.254  5813  5813 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 12:20:26.254  5813  5813 D BluetoothMapService: STATE_ON
09-26 12:20:26.255  5673  5673 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-26 12:20:26.256  5813  5853 D ObexServerSockets0: Accepting socket connection...
09-26 12:20:26.256  5813  5852 D ObexServerSockets0: Accepting socket connection...
,09-26 12:20:26.258  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:26.259  5813  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 12:20:26.260  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:26.260  5813  5854 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-26 12:20:26.260  5813  5854 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-26 12:20:26.261  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:26.263  5673  5673 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-26 12:20:26.265  5673  5673 D BluetoothA2dp: Proxy object connected
,09-26 12:20:26.269  3562  3562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 12:20:26.274  5673  5673 D DockEventReceiver: finishStartingService: stopping service
,09-26 12:20:26.276  5673  5673 D BluetoothPbap: Proxy object connected
09-26 12:20:26.277  5673  5673 D PbapServerProfile: Bluetooth service connected
09-26 12:20:26.277  3117  3117 D BluetoothPbap: Proxy object connected
09-26 12:20:26.277  3117  3117 D PbapServerProfile: Bluetooth service connected
,09-26 12:20:26.282  5813  5813 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 12:20:26.282  5813  5813 D ObexServerSockets0: prepareForNewConnect()
,09-26 12:20:26.284  5813  5858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 12:20:26.299  5813  5862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 12:20:26.300  5813  5862 I BtOppRfcommListener: Accept thread started.
,09-26 12:20:26.342   928   928 D BluetoothHeadset: Proxy object connected
,09-26 12:20:26.343  3762  3997 D BluetoothHeadset: Proxy object connected
,09-26 12:20:26.343   928   928 D BluetoothHeadset: Proxy object connected
,09-26 12:20:26.343   928   928 D BluetoothHeadset: Proxy object connected
09-26 12:20:26.343  3117  5799 D BluetoothHeadset: Proxy object connected
09-26 12:20:26.343  3117  3117 D HeadsetProfile: Bluetooth service connected
09-26 12:20:26.344  3117  3128 D BluetoothHeadset: Proxy object connected
09-26 12:20:26.344   928   945 D BluetoothHeadset: Proxy object connected
09-26 12:20:26.345  3117  3117 D HeadsetProfile: Bluetooth service connected
,09-26 12:20:26.360  5673  5687 D BluetoothHeadset: Proxy object connected
,09-26 12:20:26.361  5673  5673 D HeadsetProfile: Bluetooth service connected
,09-26 12:20:27.965   928  2960 D ConnectivityService: handlePromptUnvalidated 101
,09-26 12:20:30.176  5813  5825 D BluetoothAdapterState: Current state: ON, message: 23
,09-26 12:20:30.177  5813  5825 D BluetoothAdapterProperties: Setting state to 13
09-26 12:20:30.177  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-26 12:20:30.178  5813  5825 D BluetoothAdapterProperties: onBluetoothDisable()
,09-26 12:20:30.181  5813  5825 I BluetoothAdapterState: Entering PendingCommandState
,09-26 12:20:30.185  5813  5813 D BluetoothMapService: onReceive
,09-26 12:20:30.188  5813  5813 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-26 12:20:30.188  5813  5813 D BluetoothMapService: STATE_TURNING_OFF
,09-26 12:20:30.189  5813  5813 D BluetoothMapService: MAP Service closeService in
09-26 12:20:30.190  5813  5813 D BluetoothMapMasInstance0: MAP Service shutdown
09-26 12:20:30.190  5813  5813 D ObexServerSockets0: shutdown(block = true)
09-26 12:20:30.191  5813  5813 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-26 12:20:30.191  5813  5829 D BluetoothAdapterProperties: Scan Mode:20
09-26 12:20:30.191  5813  5813 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 12:20:30.191  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-26 12:20:30.191  5813  5838 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-26 12:20:30.191  5813  5853 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-26 12:20:30.192  5813  5852 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-26 12:20:30.193  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:30.194  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:30.194  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:30.194  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:30.194  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:30.194  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:30.194  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:30.194  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:30.194  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:30.194  5813  5813 I BtOppRfcommListener: stopping Accept Thread
09-26 12:20:30.194  5673  5673 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 12:20:30.195  5813  5862 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-26 12:20:30.195  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:30.195  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:30.196  5813  5862 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-26 12:20:30.199  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:30.199  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:30.199  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:30.199  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:30.199  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:30.199  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:30.199  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:30.199  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:30.199  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:30.201  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advert,isement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:30.201  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:30.203  5673  5673 D DockEventReceiver: finishStartingService: stopping service
09-26 12:20:30.207  5813  5813 D HeadsetService: Received stop request...Stopping profile...
,09-26 12:20:30.207  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:30.207  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:30.207  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:30.207  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:30.207  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:30.207  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 12:20:30.207  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:30.207  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:30.207  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:30.209   928   928 D BluetoothHeadset: Proxy object disconnected
09-26 12:20:30.211  3762  4215 D BluetoothHeadset: Proxy object disconnected
09-26 12:20:30.211  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 12:20:30.211  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:30.213  5673  5687 D BluetoothHeadset: Proxy object disconnected
09-26 12:20:30.213   928   928 D BluetoothHeadset: Proxy object disconnected
,09-26 12:20:30.213   928   928 D BluetoothHeadset: Proxy object disconnected
09-26 12:20:30.214  3117  3128 D BluetoothHeadset: Proxy object disconnected
09-26 12:20:30.214  5813  5813 D A2dpService: Received stop request...Stopping profile...
09-26 12:20:30.215  5673  5673 D HeadsetProfile: Bluetooth service disconnected
,09-26 12:20:30.215  5813  5844 D A2dpStateMachine: Exit Disconnected: -1
09-26 12:20:30.215  3562  3562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 12:20:30.216   928   928 D BluetoothA2dp: Proxy object disconnected
09-26 12:20:30.216  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:30.217  5813  5813 D HidService: Received stop request...Stopping profile...
09-26 12:20:30.217  5813  5813 D HidService: Stopping Bluetooth HidService
09-26 12:20:30.218  5673  5673 D BluetoothA2dp: Proxy object disconnected
,09-26 12:20:30.219  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:30.220  5673  5673 D BluetoothInputDevice: Proxy object disconnected
09-26 12:20:30.220  5673  5673 D HidProfile: Bluetooth service disconnected
09-26 12:20:30.221  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:30.222  5813  5813 D HealthService: Received stop request...Stopping profile...
,09-26 12:20:30.223  3117  3117 D HeadsetProfile: Bluetooth service disconnected
09-26 12:20:30.223  5813  5813 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:30.224  5813  5813 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:30.224  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:30.224  3117  3117 D BluetoothA2dp: Proxy object disconnected
09-26 12:20:30.224  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:30.224  3117  3117 D BluetoothInputDevice: Proxy object disconnected
,09-26 12:20:30.224  3117  3117 D HidProfile: Bluetooth service disconnected
,09-26 12:20:30.226  5813  5813 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-26 12:20:30.226  5813  5813 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-26 12:20:30.226  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-26 12:20:30.226  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 12:20:30.226  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-26 12:20:30.226  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 12:20:30.226  5813  5829 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-26 12:20:30.226  5813  5813 D PanService: Received stop request...Stopping profile...
,09-26 12:20:30.230  5813  5813 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:30.230  5813  5813 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:30.230  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:30.230  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:30.230  3117  3117 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 12:20:30.230  3117  3117 D PanProfile: Bluetooth service disconnected
09-26 12:20:30.231  3117  3117 D BluetoothPbap: Proxy object disconnected
09-26 12:20:30.231  3117  3117 D PbapServerProfile: Bluetooth service disconnected
09-26 12:20:30.231  5673  5673 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 12:20:30.231  5673  5673 D PanProfile: Bluetooth service disconnected
09-26 12:20:30.231  5673  5673 D BluetoothPbap: Proxy object disconnected
,09-26 12:20:30.231  5673  5673 D PbapServerProfile: Bluetooth service disconnected
09-26 12:20:30.231  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 12:20:30.231  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 12:20:30.232  5813  5836 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 12:20:30.233  5813  5813 D BluetoothMapService: Received stop request...Stopping profile...
09-26 12:20:30.233  5813  5836 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 12:20:30.233  5813  5813 D BluetoothMapService: stop()
09-26 12:20:30.233  5813  5836 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 12:20:30.233  5813  5836 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-26 12:20:30.233  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-26 12:20:30.236  5813  5813 D BluetoothMapAppObserver: deinitObservers()
,09-26 12:20:30.236  5813  5813 D BluetoothMapAppObserver: removeReceiver()
09-26 12:20:30.237  3117  3117 D BluetoothMap: Proxy object disconnected
09-26 12:20:30.237  3117  3117 D MapProfile: Bluetooth service disconnected
09-26 12:20:30.237  5813  5813 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:30.237  5813  5813 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:30.237  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:30.238  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:30.238  5813  5813 D SapService: Received stop request...Stopping profile...
09-26 12:20:30.238  5813  5813 V SapService: stop()
09-26 12:20:30.238  5673  5673 D BluetoothMap: Proxy object disconnected
09-26 12:20:30.239  5673  5673 D MapProfile: Bluetooth service disconnected
,09-26 12:20:30.243  5813  5813 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-26 12:20:30.243  5813  5813 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-26 12:20:30.243  5813  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 12:20:30.243  5813  5813 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:30.243  5813  5813 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:30.243  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:30.243  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 12:20:30.243  5813  5813 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-26 12:20:30.243  5813  5829 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-26 12:20:30.244  5813  5813 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-26 12:20:30.244  5813  5813 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:30.244  5813  5813 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:30.244  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 12:20:30.244  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:30.244  5813  5813 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-26 12:20:30.244  5813  5813 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-26 12:20:30.249  5813  5813 D BluetoothMapService: MAP Service closeService in
09-26 12:20:30.249  5813  5813 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:30.249  5813  5813 V BluetoothAdapterState: isTurningOn()=false
,09-26 12:20:30.249  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:30.249  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:30.250  5813  5813 D BluetoothMapService: cleanup()
09-26 12:20:30.250  5813  5813 D BluetoothMapService: MAP Service closeService in
09-26 12:20:30.250  5813  5813 V BluetoothAdapterState: isTurningOff()=true
09-26 12:20:30.250  5813  5813 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:30.250  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:30.250  5813  5813 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 12:20:30.251  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-26 12:20:30.251  5813  5825 D BluetoothAdapterProperties: Setting state to 15
,09-26 12:20:30.251  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-26 12:20:30.252  5813  5825 I BluetoothAdapterState: Entering BleOnState
09-26 12:20:30.252  3117  5799 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 12:20:30.256  3117  3128 D BluetoothMap: onBluetoothStateChange: up=false
09-26 12:20:30.257  3117  3962 D BluetoothPbap: onBluetoothStateChange: up=false
,09-26 12:20:30.257  5673  5688 D BluetoothMap: onBluetoothStateChange: up=false
,09-26 12:20:30.258  5673  5687 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-26 12:20:30.258  3117  3129 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-26 12:20:30.259   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 12:20:30.259   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:30.259  5673  5688 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-26 12:20:30.260  3762  3785 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:30.260  5673  5687 D BluetoothPan: onBluetoothStateChange on: false
09-26 12:20:30.260  5673  5688 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-26 12:20:30.261   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:30.261  5673  5687 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 12:20:30.262  3117  5799 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:30.262   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 12:20:30.262  3117  3128 D BluetoothPan: onBluetoothStateChange on: false
09-26 12:20:30.263  5813  5825 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-26 12:20:30.263  5813  5825 D BluetoothAdapterProperties: Setting state to 16
09-26 12:20:30.263  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-26 12:20:30.264  5813  5825 D BluetoothAdapterProperties: onBleDisable
09-26 12:20:30.264  5813  5825 I BluetoothAdapterState: Entering PendingCommandState
09-26 12:20:30.265  5813  5826 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-26 12:20:30.266  5813  5836 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-26 12:20:30.266  5813  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-26 12:20:30.266  5813  5829 D BluetoothAdapterProperties: Scan Mode:20
09-26 12:20:30.267  5673  5673 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 12:20:30.267  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:30.271  5673  5673 D DockEventReceiver: finishStartingService: stopping service
09-26 12:20:30.271  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:30.272  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:30.273  3562  3562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 12:20:30.273  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:30.275  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:30.277  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:30.490  5813  5829 I bt_hci  : shut_down
,09-26 12:20:30.496  5813  5833 D bt_hwcfg: hw_epilog_process
,09-26 12:20:30.497  5813  5833 I bt_vendor: low_power_mode_cb
,09-26 12:20:30.500  5813  5833 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-26 12:20:30.501  5813  5833 I bt_vendor: epilog_cb
,09-26 12:20:30.501  5813  5833 I bt_hci  : epilog_finished_callback
,09-26 12:20:30.506  5813  5829 I bt_hci_h4: hal_close
,09-26 12:20:30.507  5813  5829 I bt_userial_vendor: device fd = 54 close
,09-26 12:20:30.627  5813  5826 D bt_stack_manager: event_shut_down_stack finished.
,09-26 12:20:30.627  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-26 12:20:30.632  5813  5825 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-26 12:20:30.632  5813  5813 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 12:20:30.633  5813  5813 D BtGatt.GattService: Received stop request...Stopping profile...
09-26 12:20:30.633  5813  5813 D BtGatt.GattService: stop()
09-26 12:20:30.633  5813  5813 D BtGatt.AdvertiseManager: advertise clients cleared
,09-26 12:20:30.638  5813  5813 V BluetoothAdapterState: isTurningOff()=false
,09-26 12:20:30.638  5813  5813 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:30.638  5813  5813 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:30.639  5813  5813 V BluetoothAdapterState: isBleTurningOff()=true
09-26 12:20:30.639  5813  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-26 12:20:30.640  5813  5825 D BluetoothAdapterProperties: Setting state to 10
09-26 12:20:30.640  5813  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-26 12:20:30.641  5813  5825 I BluetoothAdapterState: Entering OffState
,09-26 12:20:30.642   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-26 12:20:30.660  5813  5813 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-26 12:20:30.660  5813  5813 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-26 12:20:30.661  5813  5826 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-26 12:20:30.665  5813  5813 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-26 12:20:30.671  5813  5813 I art     : System.exit called, status: 0
09-26 12:20:30.671  5813  5813 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-26 12:20:30.709   928   939 I ActivityManager: Process com.android.bluetooth (pid 5813) has died
,09-26 12:20:33.511   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:34.513   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:35.174  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 12:20:35.175  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:35.180  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:35.180  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3ec534 removed from the list
09-26 12:20:35.181  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:35.181  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:20:35.181  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:35.183  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:20:35.183  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12440d2 added. We now have 4 listener(s)
09-26 12:20:35.183  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:20:35.186  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:35.187  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12440d2 removed from the list
09-26 12:20:35.187  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:35.187  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:20:35.187  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:35.189  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:20:35.189  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c9bc5a3 added. We now have 4 listener(s)
09-26 12:20:35.189  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 12:20:35.514   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:36.515   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:37.517   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:20:38.542   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:20:40.201  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:40.232   928   945 I ActivityManager: Start proc 5870:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-26 12:20:40.322  5870  5870 D AdapterServiceConfig: Adding HeadsetService
,09-26 12:20:40.322  5870  5870 D AdapterServiceConfig: Adding A2dpService
09-26 12:20:40.322  5870  5870 D AdapterServiceConfig: Adding HidService
09-26 12:20:40.323  5870  5870 D AdapterServiceConfig: Adding HealthService
09-26 12:20:40.323  5870  5870 D AdapterServiceConfig: Adding PanService
09-26 12:20:40.323  5870  5870 D AdapterServiceConfig: Adding GattService
09-26 12:20:40.323  5870  5870 D AdapterServiceConfig: Adding BluetoothMapService
,09-26 12:20:40.323  5870  5870 D AdapterServiceConfig: Adding SapService
,09-26 12:20:40.335   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@789bf24:true
,09-26 12:20:40.335  5870  5870 D BluetoothAdapterState: make() - Creating AdapterState
,09-26 12:20:40.338  5870  5870 I bt_bluedroid: init
,09-26 12:20:40.339  5870  5882 I BluetoothAdapterState: Entering OffState
,09-26 12:20:40.341  5870  5883 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-26 12:20:40.341  5870  5883 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-26 12:20:40.341  5870  5883 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-26 12:20:40.341  5870  5883 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-26 12:20:40.342  5870  5870 I bt_bluedroid: get_profile_interface socket
,09-26 12:20:40.344  5870  5886 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-26 12:20:40.344  5870  5870 I bt_bluedroid: get_profile_interface sdp
,09-26 12:20:40.346  5870  5886 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 12:20:40.350  5870  5881 I bt_bluedroid: config_hci_snoop_log
09-26 12:20:40.351   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-26 12:20:40.356  5870  5882 D BluetoothAdapterState: Current state: OFF, message: 0
09-26 12:20:40.356  5870  5882 D BluetoothAdapterProperties: Setting state to 14
09-26 12:20:40.356  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-26 12:20:40.358  5870  5882 D BluetoothBondStateMachine: make
,09-26 12:20:40.360  5870  5887 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-26 12:20:40.363  5870  5882 I BluetoothAdapterState: Entering PendingCommandState
,09-26 12:20:40.364  5870  5870 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-26 12:20:40.367  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:40.368  5870  5870 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-26 12:20:40.368  5870  5870 D BtGatt.GattService: Received start request. Starting profile...
,09-26 12:20:40.368  5870  5870 D BtGatt.GattService: start()
09-26 12:20:40.369  5870  5870 I bt_bluedroid: get_profile_interface gatt
09-26 12:20:40.370  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
09-26 12:20:40.370  5870  5870 D BtGatt.AdvertiseManager: advertise manager created
,09-26 12:20:40.377  5870  5870 V BluetoothAdapterState: isTurningOff()=false
,09-26 12:20:40.377  5870  5870 V BluetoothAdapterState: isTurningOn()=false
09-26 12:20:40.377  5870  5870 V BluetoothAdapterState: isBleTurningOn()=true
09-26 12:20:40.377  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:40.377  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-26 12:20:40.379  5870  5882 I bt_bluedroid: bt_bluedroid
09-26 12:20:40.379  5870  5883 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-26 12:20:40.379  5870  5883 I bt_hci  : start_up
,09-26 12:20:40.385  5870  5883 I bt_vendor: alloc value 0xf3da3871
,09-26 12:20:40.385  5870  5883 I bt_vendor: init
09-26 12:20:40.385  5870  5883 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-26 12:20:40.385  5870  5883 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-26 12:20:40.496  5870  5883 D bt_hci  : start_up starting async portion
,09-26 12:20:40.497  5870  5890 I bt_hci  : event_finish_startup
09-26 12:20:40.497  5870  5890 I bt_hci_h4: hal_open
09-26 12:20:40.497  5870  5890 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-26 12:20:40.501  5870  5890 I bt_userial_vendor: device fd = 54 open
,09-26 12:20:40.494  5891  5891 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-26 12:20:40.517  5870  5890 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 12:20:40.521  5870  5890 D bt_hwcfg: Chipset BCM4358A3
,09-26 12:20:40.521  5870  5890 D bt_hwcfg: Target name = [BCM4358A3]
,09-26 12:20:40.522  5870  5890 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-26 12:20:41.024  5870  5890 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-26 12:20:41.025  5870  5890 D bt_hwcfg: Settlement delay -- 100 ms
,09-26 12:20:41.025  5870  5890 I bt_hwcfg: Setting fw settlement delay to 100 
,09-26 12:20:41.159  5870  5890 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-26 12:20:41.160  5870  5890 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-26 12:20:41.162  5870  5890 I bt_hwcfg: vendor lib fwcfg completed
09-26 12:20:41.162  5870  5890 I bt_vendor: firmware callback
09-26 12:20:41.162  5870  5890 I bt_hci  : firmware_config_callback
,09-26 12:20:41.171  5870  5893 I bt_btu  : btu_task pending for preload complete event
,09-26 12:20:41.171  5870  5893 I bt_btu_task: Bluetooth chip preload is complete
09-26 12:20:41.172  5870  5893 I bt_btu  : btu_task received preload complete event
,09-26 12:20:41.178  5870  5893 I         : BTE_InitTraceLevels -- TRC_HCI
,09-26 12:20:41.178  5870  5893 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-26 12:20:41.178  5870  5893 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-26 12:20:41.178  5870  5893 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-26 12:20:41.179  5870  5893 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-26 12:20:41.179  5870  5893 I         : BTE_InitTraceLevels -- TRC_A2D
09-26 12:20:41.179  5870  5893 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-26 12:20:41.179  5870  5893 I         : BTE_InitTraceLevels -- TRC_BTM
09-26 12:20:41.179  5870  5893 I         : BTE_InitTraceLevels -- TRC_GAP
09-26 12:20:41.179  5870  5893 I         : BTE_InitTraceLevels -- TRC_PAN
09-26 12:20:41.179  5870  5893 I         : BTE_InitTraceLevels -- TRC_SDP
,09-26 12:20:41.180  5870  5893 I         : BTE_InitTraceLevels -- TRC_GATT
09-26 12:20:41.180  5870  5893 I         : BTE_InitTraceLevels -- TRC_SMP
,09-26 12:20:41.180  5870  5893 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-26 12:20:41.180  5870  5893 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-26 12:20:41.280  5870  5893 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d21549
,09-26 12:20:41.280  5870  5893 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d21549 
,09-26 12:20:41.299  5870  5886 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-26 12:20:41.301  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-26 12:20:41.302  5870  5886 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 12:20:41.304  5870  5886 D BluetoothAdapterProperties: Name is: Nexus 6P
09-26 12:20:41.307  5870  5886 D BluetoothAdapterProperties: Scan Mode:20
09-26 12:20:41.307  5870  5886 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 12:20:41.307  5870  5886 D bt_hci  : do_postload posting postload work item
09-26 12:20:41.307  5870  5890 I bt_hci  : event_postload
09-26 12:20:41.308  5870  5890 I bt_vendor: sco_config_cb
09-26 12:20:41.308  5870  5890 I bt_hci  : sco_config_callback postload finished.
,09-26 12:20:41.314  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:41.316  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:41.317  5870  5886 D bt_bte_conf: Device ID record 1 : primary
,09-26 12:20:41.317  5870  5886 D bt_bte_conf:   vendorId            = 000f
09-26 12:20:41.317  5870  5886 D bt_bte_conf:   vendorIdSource      = 0001
09-26 12:20:41.318  5870  5886 D bt_bte_conf:   product             = 1200
09-26 12:20:41.318  5870  5886 D bt_bte_conf:   version             = 1436
09-26 12:20:41.318  5870  5890 I bt_vendor: low_power_mode_cb
09-26 12:20:41.318  5870  5886 D bt_bte_conf:   clientExecutableURL = 
09-26 12:20:41.318  5870  5886 D bt_bte_conf:   serviceDescription  = 
09-26 12:20:41.318  5870  5886 D bt_bte_conf:   documentationURL    = 
09-26 12:20:41.318  5870  5886 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-26 12:20:41.318  5870  5883 D bt_stack_manager: event_start_up_stack finished
09-26 12:20:41.319  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-26 12:20:41.320  5870  5882 D BluetoothAdapterProperties: Setting state to 15
09-26 12:20:41.320  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-26 12:20:41.321  5870  5882 I BluetoothAdapterState: Entering BleOnState
,09-26 12:20:41.325  5870  5882 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-26 12:20:41.325  5870  5882 D BluetoothAdapterProperties: Setting state to 11
09-26 12:20:41.325  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-26 12:20:41.332  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:41.337  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:41.340  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
09-26 12:20:41.341  5870  5870 D HeadsetService: Received start request. Starting profile...
09-26 12:20:41.344  5870  5870 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-26 12:20:41.344  5870  5870 D HeadsetStateMachine: make
,09-26 12:20:41.352  5870  5882 I BluetoothAdapterState: Entering PendingCommandState
,09-26 12:20:41.355  5870  5870 D HeadsetStateMachine: max_hf_connections = 1
09-26 12:20:41.355  5870  5870 I bt_bluedroid: get_profile_interface handsfree
09-26 12:20:41.356  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-26 12:20:41.356  5870  5886 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-26 12:20:41.360  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
09-26 12:20:41.361  5870  5870 D A2dpService: Received start request. Starting profile...
09-26 12:20:41.362  5870  5870 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-26 12:20:41.362  5870  5870 I bt_bluedroid: get_profile_interface avrcp
,09-26 12:20:41.368  5870  5870 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-26 12:20:41.369  5870  5870 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-26 12:20:41.369  5870  5870 D A2dpStateMachine: make
09-26 12:20:41.371  5870  5870 I bt_bluedroid: get_profile_interface a2dp
,09-26 12:20:41.372  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-26 12:20:41.374  5870  5870 I BluetoothHidServiceJni: classInitNative: succeeds
09-26 12:20:41.375  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
09-26 12:20:41.375  5870  5901 D A2dpStateMachine: Enter Disconnected: -2
09-26 12:20:41.376  3562  3562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 12:20:41.377  5870  5870 D HidService: Received start request. Starting profile...
09-26 12:20:41.377  5870  5870 I bt_bluedroid: get_profile_interface hidhost
09-26 12:20:41.377  5870  5870 D HidService: setHidService(): set to: null
,09-26 12:20:41.377  5870  5886 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d0256d
09-26 12:20:41.377  5870  5886 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-26 12:20:41.378  5870  5870 I BluetoothHealthServiceJni: classInitNative: succeeds
09-26 12:20:41.379  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:41.380  5870  5870 D HealthService: Received start request. Starting profile...
,09-26 12:20:41.381  5870  5870 I bt_bluedroid: get_profile_interface health
,09-26 12:20:41.382  5870  5870 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-26 12:20:41.383  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:41.384  5870  5870 D PanService: Received start request. Starting profile...
,09-26 12:20:41.384  5870  5870 D BluetoothPanServiceJni: initializeNative(L110): pan
09-26 12:20:41.384  5870  5870 I bt_bluedroid: get_profile_interface pan
09-26 12:20:41.384  5870  5886 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-26 12:20:41.387  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:41.388  5870  5870 D BluetoothMapService: Received start request. Starting profile...
,09-26 12:20:41.388  5870  5870 D BluetoothMapService: start()
09-26 12:20:41.391  5870  5870 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-26 12:20:41.392  5870  5870 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-26 12:20:41.392  5870  5870 D BluetoothMapAppObserver: createReceiver()
,09-26 12:20:41.393  5870  5870 D BluetoothMapAppObserver: initObservers()
09-26 12:20:41.393  5870  5870 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-26 12:20:41.400  5870  5870 V SapService: SapBinder()
,09-26 12:20:41.400  5870  5870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
,09-26 12:20:41.401  5870  5870 D SapService: Received start request. Starting profile...
09-26 12:20:41.402  5870  5870 V SapService: start()
,09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isTurningOff()=false
,09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:41.403  5870  5899 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isTurningOn()=true
,09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:41.403  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isTurningOff()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isTurningOff()=false
,09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isTurningOn()=true
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isBleTurningOn()=false
09-26 12:20:41.404  5870  5870 V BluetoothAdapterState: isBleTurningOff()=false
09-26 12:20:41.405  5870  5882 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-26 12:20:41.405  5870  5882 D BluetoothAdapterProperties: ScanMode =  20
09-26 12:20:41.405  5870  5882 D BluetoothAdapterProperties: State =  11
09-26 12:20:41.405  5870  5882 D BluetoothAdapterProperties: Setting state to 12
09-26 12:20:41.405  5870  5882 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-26 12:20:41.406  5870  5882 I BluetoothAdapterState: Entering OnState
09-26 12:20:41.406  3117  3128 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 12:20:41.406  5870  5886 D BluetoothAdapterProperties: Scan Mode:21
,09-26 12:20:41.406  5870  5886 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 12:20:41.408  3117  3962 D BluetoothMap: onBluetoothStateChange: up=true
09-26 12:20:41.409  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:41.409  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:41.409  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:41.409  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:41.409  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:41.409  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:41.409  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:41.409  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:41.409  3117  3117 D BluetoothA2dp: Proxy object connected
09-26 12:20:41.411  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:41.411  3117  5799 D BluetoothPbap: onBluetoothStateChange: up=true
,09-26 12:20:41.413  3117  3117 D BluetoothMap: Proxy object connected
09-26 12:20:41.413  3117  3117 D MapProfile: Bluetooth service connected
09-26 12:20:41.413  3117  3117 D BluetoothMap: getConnectedDevices()
,09-26 12:20:41.414  5673  5687 D BluetoothMap: onBluetoothStateChange: up=true
09-26 12:20:41.414  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:41.414  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:41.414  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:41.414  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:41.414  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:41.414  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:41.414  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:41.414  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:41.415  5673  5688 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-26 12:20:41.416  3117  3129 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-26 12:20:41.416  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 12:20:41.417   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 12:20:41.418  5673  5673 D BluetoothMap: Proxy object connected
09-26 12:20:41.418  5673  5673 D MapProfile: Bluetooth service connected
,09-26 12:20:41.418  5673  5673 D BluetoothMap: getConnectedDevices()
09-26 12:20:41.418  3117  3117 D BluetoothInputDevice: Proxy object connected
09-26 12:20:41.418  3117  3117 D HidProfile: Bluetooth service connected
09-26 12:20:41.418   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-26 12:20:41.418   928   928 D BluetoothA2dp: Proxy object connected
09-26 12:20:41.418  5673  5687 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 12:20:41.419  5870  5870 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 12:20:41.419  5870  5870 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-26 12:20:41.420  3762  3786 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 12:20:41.420  5870  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 12:20:41.421  5673  5688 D BluetoothPan: onBluetoothStateChange on: true
09-26 12:20:41.422  5870  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 12:20:41.422  5673  5687 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 12:20:41.423  5870  5870 D ObexServerSockets: Succeed to create listening sockets 
09-26 12:20:41.424  5870  5870 D ObexServerSockets0: startAccept()
09-26 12:20:41.424  5870  5870 D ObexServerSockets0: prepareForNewConnect()
09-26 12:20:41.424   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 12:20:41.424  5673  5688 D BluetoothPbap: onBluetoothStateChange: up=true
,09-26 12:20:41.426  5870  5870 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-26 12:20:41.426  5870  5870 D BluetoothSdpJni: SDP Create record success - handle: 0
09-26 12:20:41.427  5673  5673 D BluetoothInputDevice: Proxy object connected
09-26 12:20:41.427  5673  5673 D HidProfile: Bluetooth service connected
09-26 12:20:41.428  3117  5799 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 12:20:41.428  5870  5909 D ObexServerSockets0: Accepting socket connection...
09-26 12:20:41.428  5870  5908 D ObexServerSockets0: Accepting socket connection...
09-26 12:20:41.428   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 12:20:41.429  3117  3962 D BluetoothPan: onBluetoothStateChange on: true
09-26 12:20:41.430  3117  3117 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 12:20:41.430  3117  3117 D PanProfile: Bluetooth service connected
,09-26 12:20:41.431   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-26 12:20:41.432  5870  5870 D BluetoothMapService: onReceive
09-26 12:20:41.432  5870  5870 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 12:20:41.432  5870  5870 D BluetoothMapService: STATE_ON
09-26 12:20:41.432  5673  5673 D BluetoothA2dp: Proxy object connected
09-26 12:20:41.434  5870  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 12:20:41.434  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:20:41.435  5870  5910 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-26 12:20:41.435  5870  5910 D BluetoothSdpJni: SDP Create record success - handle: 1
09-26 12:20:41.436  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:41.437  5673  5673 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 12:20:41.437  5673  5673 D PanProfile: Bluetooth service connected
09-26 12:20:41.441  5673  5673 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-26 12:20:41.445  5673  5673 D DockEventReceiver: finishStartingService: stopping service
,09-26 12:20:41.450  3562  3562 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 12:20:41.454  3117  3117 D BluetoothPbap: Proxy object connected
,09-26 12:20:41.454  5673  5673 D BluetoothPbap: Proxy object connected
09-26 12:20:41.454  3117  3117 D PbapServerProfile: Bluetooth service connected
09-26 12:20:41.454  5673  5673 D PbapServerProfile: Bluetooth service connected
09-26 12:20:41.454  5870  5870 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 12:20:41.454  5870  5870 D ObexServerSockets0: prepareForNewConnect()
,09-26 12:20:41.457  5870  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 12:20:41.467  5870  5920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 12:20:41.469  5870  5920 I BtOppRfcommListener: Accept thread started.
,09-26 12:20:41.518   928   928 D BluetoothHeadset: Proxy object connected
09-26 12:20:41.518  3762  3997 D BluetoothHeadset: Proxy object connected
09-26 12:20:41.518   928   945 D BluetoothHeadset: Proxy object connected
,09-26 12:20:41.519  5673  5907 D BluetoothHeadset: Proxy object connected
,09-26 12:20:41.519   928   928 D BluetoothHeadset: Proxy object connected
09-26 12:20:41.519   928   928 D BluetoothHeadset: Proxy object connected
09-26 12:20:41.519  3117  3962 D BluetoothHeadset: Proxy object connected
09-26 12:20:41.519  3117  3117 D HeadsetProfile: Bluetooth service connected
09-26 12:20:41.520  5673  5673 D HeadsetProfile: Bluetooth service connected
09-26 12:20:41.521  3762  4215 D BluetoothHeadset: Proxy object connected
,09-26 12:20:41.523   928   945 D BluetoothHeadset: Proxy object connected
,09-26 12:20:41.529  3117  5799 D BluetoothHeadset: Proxy object connected
,09-26 12:20:41.529  3117  3117 D HeadsetProfile: Bluetooth service connected
09-26 12:20:41.529   928   945 D BluetoothHeadset: Proxy object connected
,09-26 12:20:45.216  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:45.216  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:45.216  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:45.216  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 12:20:45.216  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:45.216  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:45.216  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:45.216  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 12:20:45.221  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 12:20:45.223  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 12:20:45.223  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c9bc5a3 removed from the list
09-26 12:20:45.223  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:45.223  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:45.224  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:20:45.225  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:20:45.225  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39d00a0 added. We now have 4 listener(s)
09-26 12:20:45.225  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:20:45.228   928   939 D WifiService: setWifiEnabled: false pid=5605, uid=10077
09-26 12:20:45.228   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 12:20:50.238  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:50.239   928  3788 D WifiService: setWifiEnabled: true pid=5605, uid=10077
09-26 12:20:50.240   928  3788 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 12:20:50.250   507   922 D SoftapController: Softap fwReload - Ok
,09-26 12:20:50.256   507   922 D CommandListener: Setting iface cfg
,09-26 12:20:50.256   507   922 D CommandListener: Trying to bring down wlan0
,09-26 12:20:50.257   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-26 12:20:50.263   928  2947 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-26 12:20:50.937   928  2947 D wifi    : set interface wlan0 flags (UP)
09-26 12:20:50.938   928  2947 I WifiHAL : Initializing wifi
,09-26 12:20:50.938   928  2947 I WifiHAL : Creating socket
,09-26 12:20:50.945   928  2947 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-26 12:20:50.945   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-26 12:20:50.946   928  2947 D wifi    : Did set static halHandle = 0x7f8eae7540
,09-26 12:20:50.946   928  2947 D wifi    : halHandle = 0x7f8eae7540, mVM = 0x7fab14d140, mCls = 0x167e
,09-26 12:20:50.946   928  2947 D wifi    : array field set
09-26 12:20:50.946   928  2947 I WifiNative-HAL: interface[0] = wlan0
,09-26 12:20:50.949   928  5925 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547854644544
09-26 12:20:50.949   928  5925 D wifi    : waitForHalEvents called, vm = 0x7fab14d140, obj = 0x167e, env = 0x7fa12b7500
,09-26 12:20:51.010  5926  5926 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-26 12:20:51.032  5926  5926 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 12:20:51.054   928  2947 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-26 12:20:51.063  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:51.068  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:20:51.092  5926  5926 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 12:20:51.092  5926  5926 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-26 12:20:51.109   928  2947 D WifiConfigStore: Loading config and enabling all networks 
,09-26 12:20:51.114  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:51.114  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:51.114  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:51.114  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:51.114  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:51.114  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:51.114  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:51.114  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 12:20:51.117  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 12:20:51.121  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:51.121  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:51.121  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:51.121  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:51.121  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:51.121  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 12:20:51.121  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 12:20:51.121  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 12:20:51.121   928  2947 D WifiConfigStore: loaded 0 passpoint configs
09-26 12:20:51.121   928  2947 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-26 12:20:51.122   928  2947 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-26 12:20:51.123   928  2947 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-26 12:20:51.124  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 12:20:51.124   928  2947 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-26 12:20:51.125   928  2947 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-26 12:20:51.125   928  2947 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-26 12:20:51.125   928  2947 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-26 12:20:51.129   928  2947 D WifiNative-HAL: Setting external_sim to 1
,09-26 12:20:51.129  5010  5010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 12:20:51.129   928  2947 D wifi    : setting dfs flag to true, 0x7f90f86b80
09-26 12:20:51.130   928  2947 D WifiStateMachine: Setting OUI to DA-A1-19
09-26 12:20:51.130   928  2947 D wifi    : setting scan oui 0x7f90f86b80
,09-26 12:20:51.130   928  2947 D WifiHAL : Sending mac address OUI
,09-26 12:20:51.134   928  2947 E native  : do suspend false
,09-26 12:20:51.142   928  2947 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-26 12:20:51.143   928   928 D RttService: SCAN_AVAILABLE : 3
09-26 12:20:51.143   928  3055 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-26 12:20:51.147   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-26 12:20:51.149   507   922 D CommandListener: Setting iface cfg
,09-26 12:20:51.156   928  2932 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-26 12:20:51.156   928  2932 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-26 12:20:51.163   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=205643 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-26 12:20:51.164   928  2932 D WifiNative-HAL: p2pGetDeviceAddress
,09-26 12:20:51.164   928  2932 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-26 12:20:54.322  5926  5926 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 12:20:54.347  5926  5926 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 12:20:54.355  5926  5926 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 12:20:54.359  5926  5926 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 12:20:54.393   928  2947 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-26 12:20:54.394   928  2947 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-26 12:20:54.394   928  2947 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 12:20:54.408   928  2947 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-26 12:20:54.436   928  2947 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-26 12:20:54.438  5926  5926 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-26 12:20:54.862  5926  5926 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-26 12:20:54.897  5926  5926 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-26 12:20:54.899  5926  5926 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-26 12:20:54.909   928  2947 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 12:20:54.909   928  2947 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-26 12:20:54.910   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-26 12:20:54.929   928  2947 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 12:20:54.943   507   922 D CommandListener: Setting iface cfg
,09-26 12:20:54.949   928  2947 D WifiStateMachine: Start Dhcp Watchdog 3
,09-26 12:20:54.954   928  5931 D DhcpClient: Receive thread started
,09-26 12:20:54.959   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:20:54.959   928  2947 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-26 12:20:54.960   928  2960 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-26 12:20:55.041   928  2947 E native  : do suspend false
,09-26 12:20:55.052   928  5930 D DhcpClient: Broadcasting DHCPDISCOVER
,09-26 12:20:55.066   928  5931 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-26 12:20:55.067   928  5930 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-26 12:20:55.069   928  5930 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-26 12:20:55.084   928  5931 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-26 12:20:55.085   928  5930 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-26 12:20:55.087   507   922 D CommandListener: Setting iface cfg
09-26 12:20:55.091   928  2947 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-26 12:20:55.095   928  5930 D DhcpClient: Scheduling renewal in 86399s
,09-26 12:20:55.104   928  2947 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-26 12:20:55.105   928  2947 D WifiConfigStore: No blacklist allowed without epno enabled
,09-26 12:20:55.106   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-26 12:20:55.110   928  2960 D ConnectivityService: Adding iface wlan0 to network 102
,09-26 12:20:55.122   928  2947 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-26 12:20:55.161   928  2960 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-26 12:20:55.162   928  2960 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-26 12:20:55.165   928  2960 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-26 12:20:55.169   928  2960 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-26 12:20:55.171   928  2960 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-26 12:20:55.179   928  2960 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:20:55.184   928  2960 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-26 12:20:55.184   928  2960 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-26 12:20:55.184   928  2960 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-26 12:20:55.184   928  2947 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-26 12:20:55.184   928  2960 D ConnectivityService:    accepting network in place of null
09-26 12:20:55.184   928  2947 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 12:20:55.185   928  2960 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 12:20:55.196   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 12:20:55.209   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 12:20:55.230   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 12:20:55.233   928  2960 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-26 12:20:55.233  3715  3878 W QCNEJ   : |CORE| network available: 102
09-26 12:20:55.234   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 12:20:55.235   928  2960 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-26 12:20:55.235  3715  3878 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-26 12:20:55.235   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-26 12:20:55.239  3715  3878 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-26 12:20:55.240  3715  3878 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-26 12:20:55.244  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:55.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:55.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:55.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:55.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:55.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:55.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:20:55.244  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:20:55.247  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 12:20:55.251  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:55.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:55.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:55.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:55.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:55.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:55.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:20:55.251  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:20:55.254  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 12:20:55.254  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:20:55.254  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:20:55.254  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:20:55.254  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:20:55.254  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:55.254  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:20:55.254  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:20:55.255  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:55.256  5035  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 12:20:55.256  5035  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 12:20:55.256  5035  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-26 12:20:55.256  5035  5059 E SarControlService: no key has been found,reset the power
09-26 12:20:55.257  5035  5072 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 12:20:55.257  5035  5072 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 12:20:55.257  5035  5072 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 12:20:55.257  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:20:55.257  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 12:20:55.257  5060  5060 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 12:20:55.257  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:20:55.257  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39d00a0 removed from the list
09-26 12:20:55.257  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:20:55.257  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:20:55.258  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:20:55.258  5035  5072 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 12:20:55.258  5035  5072 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 12:20:55.258  5035  5072 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 12:20:55.260  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 12:20:55.260  5060  5060 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 12:20:55.261  5605  5940 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-26 12:20:55.261  5605  5940 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-26 12:20:55.260  3842  3842 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 12:20:55.264  3842  3842 D SystemUpdateService: onCreate
09-26 12:20:55.266   928  5928 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-26 12:20:55.269  3842  3842 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-26 12:20:55.271  5060  5074 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c955499 HexData = [00000000f003000000000000ffffffff]
09-26 12:20:55.271  5060  5074 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 12:20:55.271  5060  5074 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-26 12:20:55.272  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 12:20:55.272  5035  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 12:20:55.272  5060  5074 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c955499 HexData = [00000000f103000000000000ffffffff]
09-26 12:20:55.272  5060  5074 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 12:20:55.272  5060  5074 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-26 12:20:55.273  5060  5060 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 12:20:55.273  5035  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 12:20:55.280  3842  3842 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-26 12:20:55.287  3842  5394 I iu.UploadsManager: num queued entries: 0
09-26 12:20:55.287  3842  5394 I iu.UploadsManager: num updated entries: 0
09-26 12:20:55.288  3842  5394 I iu.SyncManager: NEXT; no task
09-26 12:20:55.290  3842  3842 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-26 12:20:55.291  3842  3842 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-26 12:20:55.293  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-26 12:20:55.296  5738  5738 D SprintDMHelper: simOperator: 
09-26 12:20:55.296  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 12:20:55.308  3842  5942 I SystemUpdateService: active receiver: enabled
09-26 12:20:55.332  3842  5942 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-26 12:20:55.334  3842  5942 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-26 12:20:55.334  3842  5942 I SystemUpdateService: now status is 0 (complete)
09-26 12:20:55.334  3842  5942 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 12:20:55.334  3842  5942 I SystemUpdateService: file has been verified
09-26 12:20:55.334  3842  5942 I SystemUpdateService: OTA package size = 21989297
09-26 12:20:55.340  3842  5942 I SystemUpdateService: showing system update notification
,09-26 12:20:55.341   928  5928 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 26 Sep 2016 16:20:55 GMT], X-Android-Received-Millis=[1474906855341], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474906855288]}
,09-26 12:20:55.342   928  2960 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-26 12:20:55.342   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-26 12:20:55.342   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-26 12:20:55.343   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-26 12:20:55.352  3842  3842 D SystemUpdateService: onDestroy
,09-26 12:20:55.411  5010  5946 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-26 12:20:57.982   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:20:58.284  5605  5954 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-26 12:20:58.284  5605  5940 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-26 12:20:58.285  5605  5954 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-26 12:20:58.285  5605  5940 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-26 12:20:58.286  5605  5954 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 12:20:58.287  5605  5940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 12:20:58.287  5605  5954 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 12:20:58.288  5605  5940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 12:20:58.289  5605  5954 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-26 12:20:58.289  5605  5940 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-26 12:20:58.294  5605  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Sender)
,09-26 12:20:58.295  5605  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver)
,09-26 12:20:58.296  5605  5959 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver)
09-26 12:20:58.296  5605  5959 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-26 12:20:58.297  5605  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-26 12:20:58.297  5605  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Sender)
09-26 12:20:58.298  5605  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver)
,09-26 12:20:58.298  5605  5958 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver)
,09-26 12:20:58.299  5605  5958 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-26 12:20:58.299  5605  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-26 12:21:01.269  5605  5652 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-26 12:21:01.271  5605  5652 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-26 12:21:01.279  5605  5652 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@499a60d Bundle[{}]
,09-26 12:21:01.280  5605  5652 I io.jxcore.node.LifeCycleMonitor: start: OK
09-26 12:21:01.281  5605  5652 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-26 12:21:01.282  5605  5652 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-26 12:21:01.283  5605  5652 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-26 12:21:01.284  5605  5652 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-26 12:21:01.285  5605  5652 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-26 12:21:01.292  5605  5652 I System.out: Running OutgoingSocketThread
,09-26 12:21:01.295  5605  5960 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-26 12:21:01.295  5605  5960 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-26 12:21:03.189   928  2960 D ConnectivityService: handlePromptUnvalidated 102
,09-26 12:21:03.543   551   551 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:21:03.544   551   551 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:21:04.305  5605  5960 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-26 12:21:04.306  5605  5961 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-26 12:21:04.306  5605  5960 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-26 12:21:04.306  5605  5961 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-26 12:21:04.306  5605  5960 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 12:21:04.306  5605  5961 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 12:21:04.308  5605  5960 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 12:21:04.308  5605  5961 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 12:21:04.311  5605  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender)
,09-26 12:21:04.314  5605  5960 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-26 12:21:04.314  5605  5961 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-26 12:21:04.320  5605  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender)
,09-26 12:21:04.322  5605  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver)
,09-26 12:21:04.324  5605  5965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver)
,09-26 12:21:04.324  5605  5965 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-26 12:21:04.324  5605  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-26 12:21:04.325  5605  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: IncomingSocketThread/Receiver)
,09-26 12:21:04.327  5605  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: IncomingSocketThread/Receiver)
,09-26 12:21:04.327  5605  5966 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-26 12:21:04.327  5605  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-26 12:21:06.166   928  2947 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,09-26 12:21:07.303  5605  5652 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-26 12:21:07.305  5605  5652 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-26 12:21:07.305  5605  5652 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-26 12:21:07.312  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 12:21:07.312  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bca3459 added. We now have 3 listener(s)
,09-26 12:21:07.317  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 12:21:07.317  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 12:21:07.317  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 12:21:07.318  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:21:07.318  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e1981e added. We now have 4 listener(s)
09-26 12:21:07.318  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:21:07.319  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 12:21:07.322  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:21:07.330  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:21:07.330  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:21:07.330  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:21:07.330  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:21:07.330  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:21:07.330  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:21:07.330  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:21:07.330  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:21:07.332  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:21:07.332  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:21:07.333  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:21:07.333  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:21:07.333  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:21:07.333  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:21:07.333  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:07.333  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:21:07.333  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 12:21:07.334  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bca3459 removed from the list
09-26 12:21:07.334  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:07.334  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e1981e removed from the list
,09-26 12:21:07.336  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:21:07.337  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:21:07.337  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:07.338  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:21:07.338  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:07.339  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:21:07.339  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:21:07.339  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:07.339  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e1981e not in the list
09-26 12:21:07.340  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:07.340  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:07.341  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:21:07.341  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:21:07.341  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:07.341  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e1981e not in the list
,09-26 12:21:07.341  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:21:07.341  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:07.341  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:07.341  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:21:07.341  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bca3459 not in the list
09-26 12:21:07.342  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 12:21:07.342  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae186cc added. We now have 3 listener(s)
09-26 12:21:07.343  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 12:21:07.343  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 12:21:07.343  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 12:21:07.344  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 12:21:07.344  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0bd15 added. We now have 4 listener(s)
09-26 12:21:07.344  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:21:07.345  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 12:21:07.348  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:21:07.352  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:21:07.352  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:21:07.352  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:21:07.352  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:21:07.352  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:21:07.352  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:21:07.352  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:21:07.352  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 12:21:07.354  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 12:21:07.354  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:21:07.354  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 12:21:07.354  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 12:21:07.354  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 12:21:07.354  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:07.354  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 12:21:07.357  5605  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 12:21:07.358  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 12:21:07.358  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:21:07.361  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:21:07.361  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 12:21:07.364  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 12:21:07.364  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 12:21:07.368  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 12:21:07.368  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-26 12:21:07.368  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 12:21:07.369  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:21:07.372  5870  5906 D BtGatt.GattService: registerClient() - UUID=3e46e6bc-9551-4dba-b180-1262889b5f05
,09-26 12:21:07.373  5870  5886 D BtGatt.GattService: onClientRegistered() - UUID=3e46e6bc-9551-4dba-b180-1262889b5f05, clientIf=5
,09-26 12:21:07.374  5605  5615 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 12:21:07.375  5870  5898 D BtGatt.GattService: start scan with filters
,09-26 12:21:07.378  5870  5889 D BtGatt.ScanManager: handling starting scan
09-26 12:21:07.378  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-26 12:21:07.378  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 12:21:07.378  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 12:21:07.378  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 12:21:07.380  5870  5889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@74ef036
09-26 12:21:07.380  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 12:21:07.380  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 12:21:07.380  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 12:21:07.381  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 12:21:07.384  5605  5652 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-26 12:21:07.384  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 12:21:07.384  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 12:21:07.384  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:07.384  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 12:21:07.384  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 12:21:07.384  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 12:21:07.384  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 12:21:07.384  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-26 12:21:07.384  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 12:21:07.384  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-26 12:21:07.386  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:21:07.387  5870  5912 D BtGatt.GattService: stopScan() - queue size =1
09-26 12:21:07.387  5870  5886 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 12:21:07.387  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:21:07.388  5870  5889 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-26 12:21:07.388  5870  5906 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 12:21:07.388  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:21:07.388  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 12:21:07.389  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-26 12:21:07.389  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 12:21:07.389  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 12:21:07.390  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 12:21:07.390  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:21:07.390  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 12:21:07.390  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:21:07.391  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 12:21:07.393  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:21:07.393  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:07.393  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 12:21:07.396  5870  5886 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 12:21:07.396  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:21:07.396  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:21:07.396  5605  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 12:21:07.396  5870  5889 D BtGatt.ScanManager: Starting BLE batch scan
09-26 12:21:07.396  5870  5889 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 12:21:07.400  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 12:21:07.400  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 12:21:07.400  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 12:21:07.400  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:21:07.402  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:21:07.404  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 12:21:07.404  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:07.404  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 12:21:07.407  5870  5886 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 12:21:07.408  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:21:07.408  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:21:07.408  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 12:21:07.409  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 12:21:07.411  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 12:21:07.413  5870  5886 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-26 12:21:07.413  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:21:07.420  5870  5886 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-26 12:21:07.420  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:21:07.420  5870  5889 D BtGatt.ScanManager: stopping BLe Batch
,09-26 12:21:07.426  5870  5886 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 12:21:07.426  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:21:07.427  5870  5889 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 12:21:07.432  5870  5886 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-26 12:21:07.432  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:21:07.911  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 12:21:07.912  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 12:21:07.912  5605  5605 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 12:21:10.070   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:21:10.394  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:21:10.394  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:21:10.394  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 12:21:10.395  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:21:10.395  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:10.395  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:21:10.395  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 12:21:10.395  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae186cc removed from the list
,09-26 12:21:10.395  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:10.396  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0bd15 removed from the list
09-26 12:21:10.396  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:21:10.396  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:10.398  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 12:21:10.398  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:10.400  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:21:10.401  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:21:10.401  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:21:10.402  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:21:10.403  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:21:10.403  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:21:10.403  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:10.403  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0bd15 not in the list
,09-26 12:21:10.403  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:10.403  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:10.406  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:21:10.408  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:21:10.408  5605  5652 D BluetoothLeScanner: could not find callback wrapper
,09-26 12:21:10.409  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:21:10.409  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:21:10.409  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:21:10.409  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:10.409  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0bd15 not in the list
,09-26 12:21:10.409  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:21:10.410  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:10.410  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:10.410  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae186cc not in the list
09-26 12:21:10.412  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 12:21:10.412  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55a8282 added. We now have 3 listener(s)
09-26 12:21:10.415  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 12:21:10.416  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-26 12:21:10.416  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 12:21:10.417  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:21:10.417  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd95d93 added. We now have 4 listener(s)
09-26 12:21:10.417  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 12:21:10.418  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 12:21:10.422  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:10.427  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:21:10.427  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:21:10.427  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:21:10.427  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:21:10.427  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:21:10.427  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:21:10.427  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:21:10.427  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:21:10.429  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 12:21:10.434  5880  5880 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[35029]" dev="sockfs" ino=35029 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-26 12:21:10.434  5880  5880 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[35029]" dev="sockfs" ino=35029 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-26 12:21:10.429  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:21:10.430  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-26 12:21:10.431  5605  5652 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-26 12:21:10.431  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-26 12:21:10.431  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-26 12:21:10.431  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-26 12:21:10.432  5605  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-26 12:21:10.432  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:10.434  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-26 12:21:10.434  5605  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-26 12:21:10.434  5605  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-26 12:21:10.434  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-26 12:21:10.435  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:21:10.435  5605  5967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 12:21:10.435  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-26 12:21:10.435  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:10.435  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:21:10.437  5605  5967 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-26 12:21:10.438  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:21:10.438  5605  5605 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-26 12:21:10.442  5605  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 12:21:10.442  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 12:21:10.446  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 12:21:10.446  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 12:21:10.447  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 12:21:10.448  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-26 12:21:10.449  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 12:21:10.449  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-26 12:21:10.450  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-26 12:21:10.450  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-26 12:21:10.450  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-26 12:21:10.451  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:21:10.456  5870  5906 D BtGatt.GattService: registerClient() - UUID=7511fded-f43c-4c7b-8fbf-777192422da7
09-26 12:21:10.456  5870  5886 D BtGatt.GattService: onClientRegistered() - UUID=7511fded-f43c-4c7b-8fbf-777192422da7, clientIf=5
,09-26 12:21:10.457  5605  5615 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-26 12:21:10.460  5870  5888 D BtGatt.AdvertiseManager: message : 0
,09-26 12:21:10.462  5870  5888 D BtGatt.AdvertiseManager: starting multi advertising
,09-26 12:21:10.471  5870  5886 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-26 12:21:10.477  5870  5886 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-26 12:21:10.478  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-26 12:21:10.478  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-26 12:21:10.480  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 12:21:10.481  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-26 12:21:10.481  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-26 12:21:10.481  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-26 12:21:10.481  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-26 12:21:10.481  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-26 12:21:10.481  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-26 12:21:10.483  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-26 12:21:10.484  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-26 12:21:10.484  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-26 12:21:10.985  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-26 12:21:10.985  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-26 12:21:10.985  5605  5605 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 12:21:13.101   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:21:13.484  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:21:13.485  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-26 12:21:13.485  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-26 12:21:13.485  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-26 12:21:13.485  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-26 12:21:13.485  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-26 12:21:13.486  5605  5967 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-26 12:21:13.486  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-26 12:21:13.486  5605  5967 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-26 12:21:13.486  5605  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-26 12:21:13.486  5605  5967 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-26 12:21:13.487  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 12:21:13.487  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-26 12:21:13.487  5605  5605 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-26 12:21:13.487  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 12:21:13.487  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 12:21:13.487  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 12:21:13.489  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:21:13.490  5605  5652 D BluetoothLeScanner: could not find callback wrapper
,09-26 12:21:13.490  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:21:13.490  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-26 12:21:13.492  5870  5888 D BtGatt.AdvertiseManager: message : 1
09-26 12:21:13.493  5870  5888 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-26 12:21:13.506  5870  5886 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-26 12:21:13.507  5870  5886 D BtGatt.GattService: Client app is not null!
09-26 12:21:13.508  5870  5911 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 12:21:13.509  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 12:21:13.509  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-26 12:21:13.509  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-26 12:21:13.509  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-26 12:21:13.510  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-26 12:21:13.513  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 12:21:13.513  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 12:21:13.513  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:21:13.514  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:21:13.515  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 12:21:13.516  5605  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-26 12:21:13.516  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:13.516  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:21:13.516  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 12:21:13.516  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:21:13.516  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55a8282 removed from the list
,09-26 12:21:13.516  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:13.516  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:13.516  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:21:13.516  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd95d93 removed from the list
09-26 12:21:13.516  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:21:13.516  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:21:13.522  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:21:13.522  5605  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 12:21:13.528  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 12:21:13.529  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 12:21:13.530  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 12:21:13.530  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 12:21:13.531  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:21:13.535  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:13.535  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:21:13.537  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 12:21:13.537  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:21:13.537  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:21:13.538  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:21:13.538  5605  5652 D BluetoothLeScanner: could not find callback wrapper
,09-26 12:21:13.538  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:21:13.539  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:13.539  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:21:13.539  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd95d93 not in the list
,09-26 12:21:13.539  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:13.539  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 12:21:13.544  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 12:21:13.544  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:21:13.544   551   551 I ServiceManager: Waiting for service AtCmdFwd...
09-26 12:21:13.545  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:13.548  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:13.548  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 12:21:13.548  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:13.549  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 12:21:13.551  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:21:13.551  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:21:13.551  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:21:13.551  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:21:13.551  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:21:13.551  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 12:21:13.551  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd95d93 not in the list
09-26 12:21:13.551  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:21:13.551  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:13.551  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:13.552  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55a8282 not in the list
,09-26 12:21:13.552  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 12:21:13.553  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6e0ae8 added. We now have 3 listener(s)
09-26 12:21:13.555  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 12:21:13.555  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 12:21:13.555  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 12:21:13.555  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:21:13.555  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39d8501 added. We now have 4 listener(s)
09-26 12:21:13.555  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:21:13.556  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 12:21:13.560  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:21:13.567  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:21:13.567  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:21:13.567  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:21:13.567  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:21:13.567  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:21:13.567  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:21:13.567  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:21:13.567  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:21:13.568  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 12:21:13.569  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:21:13.569  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-26 12:21:13.569  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 12:21:13.569  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 12:21:13.569  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:13.569  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:21:13.573  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:21:13.575  5605  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:21:13.575  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 12:21:13.576  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 12:21:13.580  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 12:21:13.581  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 12:21:13.581  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 12:21:13.584  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-26 12:21:13.585  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 12:21:13.585  5605  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 12:21:13.585  5605  5652 D BluetoothAdapter: STATE_ON
,09-26 12:21:13.588  5870  5912 D BtGatt.GattService: registerClient() - UUID=844b05dc-d01a-4376-95f2-a9f829a2fc53
,09-26 12:21:13.588  5870  5886 D BtGatt.GattService: onClientRegistered() - UUID=844b05dc-d01a-4376-95f2-a9f829a2fc53, clientIf=5
09-26 12:21:13.589  5605  5717 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-26 12:21:13.589  5870  5911 D BtGatt.GattService: start scan with filters
,09-26 12:21:13.592  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-26 12:21:13.592  5870  5889 D BtGatt.ScanManager: handling starting scan
09-26 12:21:13.592  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 12:21:13.592  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 12:21:13.593  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 12:21:13.596  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 12:21:13.596  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 12:21:13.596  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 12:21:13.597  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-26 12:21:13.600  5870  5886 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 12:21:13.600  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:21:13.600  5870  5889 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 12:21:13.607  5870  5886 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-26 12:21:13.607  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:21:13.607  5870  5889 D BtGatt.ScanManager: Starting BLE batch scan
09-26 12:21:13.607  5870  5889 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 12:21:13.617  5870  5886 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-26 12:21:13.618  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:21:13.623  5870  5886 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-26 12:21:13.624  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:21:14.048  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 12:21:14.097  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-26 12:21:14.097  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 12:21:14.098  5605  5605 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 12:21:14.545   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:15.546   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:16.150   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=230630, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:21:16.547   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:16.608  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:21:16.608  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 12:21:16.608  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 12:21:16.608  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:16.609  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 12:21:16.609  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 12:21:16.609  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 12:21:16.609  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 12:21:16.609  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 12:21:16.610  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-26 12:21:16.610  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 12:21:16.611  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:21:16.613  5870  5906 D BtGatt.GattService: stopScan() - queue size =1
09-26 12:21:16.616  5870  5880 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 12:21:16.618  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:21:16.619  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 12:21:16.619  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 12:21:16.620  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 12:21:16.620  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-26 12:21:16.623  5870  5870 D BtGatt.ScanManager: awakened up at time 231104
09-26 12:21:16.625  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 12:21:16.625  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:21:16.625  5605  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 12:21:16.625  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 12:21:16.627  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:21:16.631  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:21:16.631  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:21:16.631  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:16.632  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:21:16.632  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:16.632  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 12:21:16.632  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:21:16.632  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6e0ae8 removed from the list
09-26 12:21:16.632  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:16.632  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39d8501 removed from the list
09-26 12:21:16.632  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:21:16.632  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 12:21:16.636  5870  5886 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 12:21:16.636  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:21:16.636  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 12:21:16.636  5605  5605 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 12:21:16.637  5870  5889 D BtGatt.ScanManager: stopping BLe Batch
,09-26 12:21:16.642  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 12:21:16.643  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 12:21:16.643  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 12:21:16.644  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:21:16.644  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:16.645  5870  5886 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-26 12:21:16.645  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 12:21:16.645  5870  5889 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-26 12:21:16.646  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:16.646  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:16.647  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:21:16.648  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:21:16.648  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:21:16.648  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:21:16.648  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:21:16.648  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 12:21:16.649  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:16.649  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 12:21:16.649  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39d8501 not in the list
,09-26 12:21:16.649  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 12:21:16.649  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 12:21:16.652  5605  5605 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 12:21:16.652  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 12:21:16.653  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:16.655  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 12:21:16.655  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:16.655  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:21:16.660  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 12:21:16.660  5605  5652 D BluetoothAdapter: STATE_ON
09-26 12:21:16.661  5605  5652 D BluetoothLeScanner: could not find callback wrapper
09-26 12:21:16.661  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 12:21:16.661  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:21:16.661  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 12:21:16.661  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:16.661  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39d8501 not in the list
09-26 12:21:16.661  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:21:16.661  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:16.661  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:16.661  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6e0ae8 not in the list
09-26 12:21:16.663  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 12:21:16.663  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1f7d7e added. We now have 3 listener(s)
09-26 12:21:16.664  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 12:21:16.665  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 12:21:16.665  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 12:21:16.665  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 12:21:16.665  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21902df added. We now have 4 listener(s)
09-26 12:21:16.665  5605  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 12:21:16.665  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 12:21:16.666  5870  5886 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-26 12:21:16.666  5870  5886 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 12:21:16.667  5870  5886 D BtGatt.GattService: current time is 231147791613
09-26 12:21:16.667  5870  5886 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -71, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -72, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
09-26 12:21:16.668  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-26 12:21:16.669  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 12:21:16.669  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-26 12:21:16.669  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 12:21:16.670  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-26 12:21:16.670  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-26 12:21:16.670  5870  5886 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-26 12:21:16.673  5605  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 12:21:16.673  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 12:21:16.673  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 12:21:16.673  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 12:21:16.673  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 12:21:16.673  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 12:21:16.673  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 12:21:16.673  5605  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 12:21:16.674  5605  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 12:21:16.674  5605  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 12:21:16.675  5605  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 12:21:16.675  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 12:21:16.675  5605  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 12:21:16.675  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:21:16.675  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:16.675  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 12:21:16.675  5605  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 12:21:16.675  5605  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1f7d7e removed from the list
09-26 12:21:16.675  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:16.675  5605  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21902df removed from the list
09-26 12:21:16.677  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 12:21:16.679  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No releva,nt state changes
09-26 12:21:16.680  5605  5652 D io.jxcore.node.ConnectivityMonitor: stop
09-26 12:21:16.680  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 12:21:16.680  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:16.680  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:16.681  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 12:21:16.681  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:21:16.681  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 12:21:16.681  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21902df not in the list
09-26 12:21:16.681  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:16.682  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:16.682  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 12:21:16.683  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 12:21:16.683  5605  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 12:21:16.683  5605  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21902df not in the list
09-26 12:21:16.683  5605  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 12:21:16.683  5605  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 12:21:16.683  5605  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 12:21:16.683  5605  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1f7d7e not in the list
09-26 12:21:16.684  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-26 12:21:16.684  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-26 12:21:16.684  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-26 12:21:16.684  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 12:21:16.684  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-26 12:21:16.684  5605  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-26 12:21:17.156  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 12:21:17.548   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:18.549   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:21:18.695  5605  5968 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-26 12:21:20.694  5605  5652 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 191
,09-26 12:21:20.695  5605  5652 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 191, name: My test thread name)
,09-26 12:21:20.700  5605  5969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name)
,09-26 12:21:20.700  5605  5969 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name)
09-26 12:21:20.700  5605  5969 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-26 12:21:20.704  5605  5652 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 12:21:20.710  5605  5970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name)
,09-26 12:21:20.711  5605  5970 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
09-26 12:21:20.711  5605  5970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-26 12:21:20.721  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
09-26 12:21:20.721  5605  5652 I jxcore-log: 
,09-26 12:21:20.723  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-26 12:21:20.723  5605  5652 I jxcore-log: 
,09-26 12:21:20.725  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG UnitTest_app: 'Number of failed tests:  0'
09-26 12:21:20.725  5605  5652 I jxcore-log: 
,09-26 12:21:20.726  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-26 12:21:20.726  5605  5652 I jxcore-log: 
,09-26 12:21:20.729  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG UnitTest_app: 'Total duration:  101003'
09-26 12:21:20.729  5605  5652 I jxcore-log: 
,09-26 12:21:20.739  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-26 12:21:20.739  5605  5652 I jxcore-log: 
,09-26 12:21:20.749  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.749  5605  5652 I jxcore-log: 
,09-26 12:21:20.752  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.752  5605  5652 I jxcore-log: 
,09-26 12:21:20.754  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.754  5605  5652 I jxcore-log: 
,09-26 12:21:20.755  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.755  5605  5652 I jxcore-log: 
,09-26 12:21:20.757  5605  5605 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-26 12:21:20.757  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 12:21:20.757  5605  5652 I jxcore-log: 
,09-26 12:21:20.759  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 12:21:20.759  5605  5652 I jxcore-log: 
,09-26 12:21:20.760  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.760  5605  5652 I jxcore-log: 
09-26 12:21:20.761  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.761  5605  5652 I jxcore-log: 
09-26 12:21:20.761  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 12:21:20.761  5605  5652 I jxcore-log: 
09-26 12:21:20.762  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 12:21:20.762  5605  5652 I jxcore-log: 
09-26 12:21:20.763  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 12:21:20.763  5605  5652 I jxcore-log: 
,09-26 12:21:20.763  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.763  5605  5652 I jxcore-log: 
09-26 12:21:20.764  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.764  5605  5652 I jxcore-log: 
09-26 12:21:20.764  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.764  5605  5652 I jxcore-log: 
09-26 12:21:20.765  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.765  5605  5652 I jxcore-log: 
,09-26 12:21:20.767  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.767  5605  5652 I jxcore-log: 
09-26 12:21:20.768  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.768  5605  5652 I jxcore-log: 
,09-26 12:21:20.769  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.769  5605  5652 I jxcore-log: 
09-26 12:21:20.771  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.771  5605  5652 I jxcore-log: 
09-26 12:21:20.772  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.772  5605  5652 I jxcore-log: 
,09-26 12:21:20.772  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.772  5605  5652 I jxcore-log: 
09-26 12:21:20.773  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.773  5605  5652 I jxcore-log: 
09-26 12:21:20.773  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.773  5605  5652 I jxcore-log: 
,09-26 12:21:20.777  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.777  5605  5652 I jxcore-log: 
09-26 12:21:20.778  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.778  5605  5652 I jxcore-log: 
,09-26 12:21:20.779  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.779  5605  5652 I jxcore-log: 
,09-26 12:21:20.780  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.780  5605  5652 I jxcore-log: 
09-26 12:21:20.781  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.781  5605  5652 I jxcore-log: 
09-26 12:21:20.782  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.782  5605  5652 I jxcore-log: 
09-26 12:21:20.782  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.782  5605  5652 I jxcore-log: 
09-26 12:21:20.783  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.783  5605  5652 I jxcore-log: 
09-26 12:21:20.783  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.783  5605  5652 I jxcore-log: 
09-26 12:21:20.784  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.784  5605  5652 I jxcore-log: 
09-26 12:21:20.784  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.784  5605  5652 I jxcore-log: 
09-26 12:21:20.785  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.785  5605  5652 I jxcore-log: 
09-26 12:21:20.785  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.785  5605  5652 I jxcore-log: 
,09-26 12:21:20.786  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.786  5605  5652 I jxcore-log: 
,09-26 12:21:20.787  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.787  5605  5652 I jxcore-log: 
09-26 12:21:20.788  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 12:21:20.788  5605  5652 I jxcore-log: 
,09-26 12:21:20.790  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.790  5605  5652 I jxcore-log: 
,09-26 12:21:20.791  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-26 12:21:20.791  5605  5652 I jxcore-log: 
,09-26 12:21:20.792  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.792  5605  5652 I jxcore-log: 
,09-26 12:21:20.792  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.792  5605  5652 I jxcore-log: 
,09-26 12:21:20.793  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.793  5605  5652 I jxcore-log: 
09-26 12:21:20.794  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.794  5605  5652 I jxcore-log: 
,09-26 12:21:20.795  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.795  5605  5652 I jxcore-log: 
,09-26 12:21:20.796  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 12:21:20.796  5605  5652 I jxcore-log: 
09-26 12:21:20.796  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.796  5605  5652 I jxcore-log: 
,09-26 12:21:20.797  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-26 12:21:20.797  5605  5652 I jxcore-log: 
,09-26 12:21:20.798  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.798  5605  5652 I jxcore-log: 
09-26 12:21:20.798  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 12:21:20.798  5605  5652 I jxcore-log: 
,09-26 12:21:20.799  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 12:21:20.799  5605  5652 I jxcore-log: 
09-26 12:21:20.800  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 12:21:20.800  5605  5652 I jxcore-log: 
,09-26 12:21:20.801  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 12:21:20.801  5605  5652 I jxcore-log: 
,09-26 12:21:20.804  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-26 12:21:20.804  5605  5652 I jxcore-log: 
,09-26 12:21:20.805  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - WARN testUtils: 'myNameCallback not set!'
09-26 12:21:20.805  5605  5652 I jxcore-log: 
,09-26 12:21:20.806  5605  5652 I jxcore-log: 2016-09-26 16:21:20 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-26 12:21:20.806  5605  5652 I jxcore-log: 
,09-26 12:21:20.841  5605  5968 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-26 12:21:22.814  5605  5652 I jxcore-log: 2016-09-26 16:21:22 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-26 12:21:22.814  5605  5652 I jxcore-log: 
,09-26 12:21:23.132  5605  5652 I jxcore-log: 2016-09-26 16:21:23 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-26 12:21:23.132  5605  5652 I jxcore-log: 
,09-26 12:21:23.147  5605  5652 I jxcore-log: 2016-09-26 16:21:23 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-26 12:21:23.147  5605  5652 I jxcore-log: 
,09-26 12:21:23.550   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:24.242  5605  5652 I jxcore-log: 2016-09-26 16:21:24 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-26 12:21:24.242  5605  5652 I jxcore-log: 
,09-26 12:21:24.388  5605  5652 I jxcore-log: 2016-09-26 16:21:24 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-26 12:21:24.388  5605  5652 I jxcore-log: 
,09-26 12:21:24.394  5605  5652 I jxcore-log: 2016-09-26 16:21:24 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-26 12:21:24.394  5605  5652 I jxcore-log: 
,09-26 12:21:24.398  5605  5652 I jxcore-log: 2016-09-26 16:21:24 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-26 12:21:24.398  5605  5652 I jxcore-log: 
,09-26 12:21:24.551   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:24.922  5605  5652 I jxcore-log: 2016-09-26 16:21:24 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-26 12:21:24.922  5605  5652 I jxcore-log: 
,09-26 12:21:24.971  5605  5652 I jxcore-log: 2016-09-26 16:21:24 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-26 12:21:24.971  5605  5652 I jxcore-log: 
,09-26 12:21:24.984  5605  5652 I jxcore-log: 2016-09-26 16:21:24 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-26 12:21:24.984  5605  5652 I jxcore-log: 
,09-26 12:21:24.995  5605  5652 I jxcore-log: 2016-09-26 16:21:24 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-26 12:21:24.995  5605  5652 I jxcore-log: 
,09-26 12:21:25.249  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-26 12:21:25.249  5605  5652 I jxcore-log: 
,09-26 12:21:25.368  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-26 12:21:25.368  5605  5652 I jxcore-log: 
,09-26 12:21:25.552   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:25.576  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-26 12:21:25.576  5605  5652 I jxcore-log: 
,09-26 12:21:25.585  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-26 12:21:25.585  5605  5652 I jxcore-log: 
,09-26 12:21:25.591  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-26 12:21:25.591  5605  5652 I jxcore-log: 
,09-26 12:21:25.597  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-26 12:21:25.597  5605  5652 I jxcore-log: 
,09-26 12:21:25.624  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-26 12:21:25.624  5605  5652 I jxcore-log: 
,09-26 12:21:25.658  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-26 12:21:25.658  5605  5652 I jxcore-log: 
,09-26 12:21:25.665  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-26 12:21:25.665  5605  5652 I jxcore-log: 
,09-26 12:21:25.671  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-26 12:21:25.671  5605  5652 I jxcore-log: 
,09-26 12:21:25.686  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-26 12:21:25.686  5605  5652 I jxcore-log: 
,09-26 12:21:25.690  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-26 12:21:25.690  5605  5652 I jxcore-log: 
,09-26 12:21:25.696  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-26 12:21:25.696  5605  5652 I jxcore-log: 
,09-26 12:21:25.709  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-26 12:21:25.709  5605  5652 I jxcore-log: 
,09-26 12:21:25.730  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-26 12:21:25.730  5605  5652 I jxcore-log: 
,09-26 12:21:25.739  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-26 12:21:25.739  5605  5652 I jxcore-log: 
,09-26 12:21:25.750  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-26 12:21:25.750  5605  5652 I jxcore-log: 
,09-26 12:21:25.759  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-26 12:21:25.759  5605  5652 I jxcore-log: 
,09-26 12:21:25.770  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-26 12:21:25.770  5605  5652 I jxcore-log: 
,09-26 12:21:25.780  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-26 12:21:25.780  5605  5652 I jxcore-log: 
,09-26 12:21:25.785  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-26 12:21:25.785  5605  5652 I jxcore-log: 
,09-26 12:21:25.804  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js'
09-26 12:21:25.804  5605  5652 I jxcore-log: 
,09-26 12:21:25.812  5605  5652 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-26 12:21:25.813  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - INFO testUtils: 'BLE multiple advertisement supported'
09-26 12:21:25.813  5605  5652 I jxcore-log: 
,09-26 12:21:25.929  5605  5652 I jxcore-log: 2016-09-26 16:21:25 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:25.929  5605  5652 I jxcore-log: 
,09-26 12:21:26.293  5605  5652 I jxcore-log: 2016-09-26 16:21:26 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:26.293  5605  5652 I jxcore-log: 
,09-26 12:21:26.303  5605  5652 I jxcore-log: 2016-09-26 16:21:26 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:26.303  5605  5652 I jxcore-log: 
,09-26 12:21:26.553   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:26.632  5605  5652 I jxcore-log: 2016-09-26 16:21:26 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:26.632  5605  5652 I jxcore-log: 
,09-26 12:21:26.644  5605  5652 I jxcore-log: 2016-09-26 16:21:26 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:26.644  5605  5652 I jxcore-log: 
,09-26 12:21:27.244  5605  5652 I jxcore-log: 2016-09-26 16:21:27 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:27.244  5605  5652 I jxcore-log: 
,09-26 12:21:27.256  5605  5652 I jxcore-log: 2016-09-26 16:21:27 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:27.256  5605  5652 I jxcore-log: 
,09-26 12:21:27.554   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:28.299  5605  5652 I jxcore-log: 2016-09-26 16:21:28 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:28.299  5605  5652 I jxcore-log: 
,09-26 12:21:28.310  5605  5652 I jxcore-log: 2016-09-26 16:21:28 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:28.310  5605  5652 I jxcore-log: 
,09-26 12:21:28.554   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:21:29.360  5605  5652 I jxcore-log: 2016-09-26 16:21:29 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:29.360  5605  5652 I jxcore-log: 
,09-26 12:21:29.367  5605  5652 I jxcore-log: 2016-09-26 16:21:29 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:29.367  5605  5652 I jxcore-log: 
,09-26 12:21:30.419  5605  5652 I jxcore-log: 2016-09-26 16:21:30 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:30.419  5605  5652 I jxcore-log: 
,09-26 12:21:30.426  5605  5652 I jxcore-log: 2016-09-26 16:21:30 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:30.426  5605  5652 I jxcore-log: 
,09-26 12:21:30.876   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=245357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 12:21:31.485  5605  5652 I jxcore-log: 2016-09-26 16:21:31 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:31.485  5605  5652 I jxcore-log: 
,09-26 12:21:31.494  5605  5652 I jxcore-log: 2016-09-26 16:21:31 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:31.494  5605  5652 I jxcore-log: 
,09-26 12:21:32.529  5605  5652 I jxcore-log: 2016-09-26 16:21:32 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:32.529  5605  5652 I jxcore-log: 
09-26 12:21:32.535  5605  5652 I jxcore-log: 2016-09-26 16:21:32 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:32.535  5605  5652 I jxcore-log: 
,09-26 12:21:33.583  5605  5652 I jxcore-log: 2016-09-26 16:21:33 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:33.583  5605  5652 I jxcore-log: 
,09-26 12:21:33.591  5605  5652 I jxcore-log: 2016-09-26 16:21:33 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:33.591  5605  5652 I jxcore-log: 
,09-26 12:21:34.700  5605  5652 I jxcore-log: 2016-09-26 16:21:34 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:34.700  5605  5652 I jxcore-log: 
,09-26 12:21:34.713  5605  5652 I jxcore-log: 2016-09-26 16:21:34 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:34.713  5605  5652 I jxcore-log: 
,09-26 12:21:35.165   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:21:35.771  5605  5652 I jxcore-log: 2016-09-26 16:21:35 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:35.771  5605  5652 I jxcore-log: 
,09-26 12:21:35.779  5605  5652 I jxcore-log: 2016-09-26 16:21:35 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:35.779  5605  5652 I jxcore-log: 
,09-26 12:21:36.811  5605  5652 I jxcore-log: 2016-09-26 16:21:36 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:36.811  5605  5652 I jxcore-log: 
,09-26 12:21:36.818  5605  5652 I jxcore-log: 2016-09-26 16:21:36 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:36.818  5605  5652 I jxcore-log: 
,09-26 12:21:37.854  5605  5652 I jxcore-log: 2016-09-26 16:21:37 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:37.854  5605  5652 I jxcore-log: 
,09-26 12:21:37.861  5605  5652 I jxcore-log: 2016-09-26 16:21:37 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:37.861  5605  5652 I jxcore-log: 
,09-26 12:21:38.556   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:38.899  5605  5652 I jxcore-log: 2016-09-26 16:21:38 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:38.899  5605  5652 I jxcore-log: 
09-26 12:21:38.907  5605  5652 I jxcore-log: 2016-09-26 16:21:38 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:38.907  5605  5652 I jxcore-log: 
,09-26 12:21:39.557   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:39.941  5605  5652 I jxcore-log: 2016-09-26 16:21:39 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 12:21:39.941  5605  5652 I jxcore-log: 
,09-26 12:21:39.949  5605  5652 I jxcore-log: 2016-09-26 16:21:39 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 12:21:39.949  5605  5652 I jxcore-log: 
,09-26 12:21:40.559   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:41.561   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:42.562   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:43.562   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:21:45.970  5605  5652 I jxcore-log: 2016-09-26 16:21:45 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:45.970  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:45.970  5605  5652 I jxcore-log: ''
09-26 12:21:45.970  5605  5652 I jxcore-log: 
,09-26 12:21:45.985  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:45.985  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:45.985  5605  5652 W jxcore-log:  color: red
09-26 12:21:45.985  5605  5652 W jxcore-log: 
,09-26 12:21:46.357  5605  5652 I jxcore-log: 2016-09-26 16:21:46 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:46.357  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:46.357  5605  5652 I jxcore-log: ''
09-26 12:21:46.357  5605  5652 I jxcore-log: 
,09-26 12:21:46.369  5605  5652 I jxcore-log: 2016-09-26 16:21:46 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:46.369  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:46.369  5605  5652 I jxcore-log: ''
09-26 12:21:46.369  5605  5652 I jxcore-log: 
,09-26 12:21:46.380  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:46.380  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:46.380  5605  5652 W jxcore-log:  color: red
09-26 12:21:46.380  5605  5652 W jxcore-log: 
,09-26 12:21:46.380  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:46.380  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:46.380  5605  5652 W jxcore-log:  color: red
09-26 12:21:46.380  5605  5652 W jxcore-log: 
,09-26 12:21:46.666  5605  5652 I jxcore-log: 2016-09-26 16:21:46 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:46.666  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:46.666  5605  5652 I jxcore-log: ''
09-26 12:21:46.666  5605  5652 I jxcore-log: 
,09-26 12:21:46.677  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:46.677  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:46.677  5605  5652 W jxcore-log:  color: red
09-26 12:21:46.677  5605  5652 W jxcore-log: 
,09-26 12:21:46.689  5605  5652 I jxcore-log: 2016-09-26 16:21:46 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:46.689  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:46.689  5605  5652 I jxcore-log: ''
09-26 12:21:46.689  5605  5652 I jxcore-log: 
,09-26 12:21:46.697  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:46.697  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:46.697  5605  5652 W jxcore-log:  color: red
09-26 12:21:46.697  5605  5652 W jxcore-log: 
,09-26 12:21:47.281  5605  5652 I jxcore-log: 2016-09-26 16:21:47 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:47.281  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:47.281  5605  5652 I jxcore-log: ''
09-26 12:21:47.281  5605  5652 I jxcore-log: 
,09-26 12:21:47.292  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:47.292  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:47.292  5605  5652 W jxcore-log:  color: red
09-26 12:21:47.292  5605  5652 W jxcore-log: 
,09-26 12:21:47.298  5605  5652 I jxcore-log: 2016-09-26 16:21:47 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:47.298  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:47.298  5605  5652 I jxcore-log: ''
09-26 12:21:47.298  5605  5652 I jxcore-log: 
,09-26 12:21:47.303  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:47.303  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:47.303  5605  5652 W jxcore-log:  color: red
09-26 12:21:47.303  5605  5652 W jxcore-log: 
,09-26 12:21:48.333  5605  5652 I jxcore-log: 2016-09-26 16:21:48 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:48.333  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:48.333  5605  5652 I jxcore-log: ''
09-26 12:21:48.333  5605  5652 I jxcore-log: 
09-26 12:21:48.338  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:48.338  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:48.338  5605  5652 W jxcore-log:  color: red
09-26 12:21:48.338  5605  5652 W jxcore-log: 
,09-26 12:21:48.358  5605  5652 I jxcore-log: 2016-09-26 16:21:48 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:48.358  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:48.358  5605  5652 I jxcore-log: ''
09-26 12:21:48.358  5605  5652 I jxcore-log: 
,09-26 12:21:48.365  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:48.365  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:48.365  5605  5652 W jxcore-log:  color: red
09-26 12:21:48.365  5605  5652 W jxcore-log: 
,09-26 12:21:49.391  5605  5652 I jxcore-log: 2016-09-26 16:21:49 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:49.391  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:49.391  5605  5652 I jxcore-log: ''
09-26 12:21:49.391  5605  5652 I jxcore-log: 
,09-26 12:21:49.400  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:49.400  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:49.400  5605  5652 W jxcore-log:  color: red
09-26 12:21:49.400  5605  5652 W jxcore-log: 
,09-26 12:21:49.414  5605  5652 I jxcore-log: 2016-09-26 16:21:49 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:49.414  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:49.414  5605  5652 I jxcore-log: ''
09-26 12:21:49.414  5605  5652 I jxcore-log: 
,09-26 12:21:49.424  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:49.424  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:49.424  5605  5652 W jxcore-log:  color: red
09-26 12:21:49.424  5605  5652 W jxcore-log: 
,09-26 12:21:50.439  5605  5652 I jxcore-log: 2016-09-26 16:21:50 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:50.439  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:50.439  5605  5652 I jxcore-log: ''
09-26 12:21:50.439  5605  5652 I jxcore-log: 
,09-26 12:21:50.451  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:50.451  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:50.451  5605  5652 W jxcore-log:  color: red
09-26 12:21:50.451  5605  5652 W jxcore-log: 
,09-26 12:21:50.464  5605  5652 I jxcore-log: 2016-09-26 16:21:50 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:50.464  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:50.464  5605  5652 I jxcore-log: ''
09-26 12:21:50.464  5605  5652 I jxcore-log: 
,09-26 12:21:50.468  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:50.468  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:50.468  5605  5652 W jxcore-log:  color: red
09-26 12:21:50.468  5605  5652 W jxcore-log: 
,09-26 12:21:51.383   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=265864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:21:51.502  5605  5652 I jxcore-log: 2016-09-26 16:21:51 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:51.502  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:51.502  5605  5652 I jxcore-log: ''
09-26 12:21:51.502  5605  5652 I jxcore-log: 
,09-26 12:21:51.508  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:51.508  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:51.508  5605  5652 W jxcore-log:  color: red
09-26 12:21:51.508  5605  5652 W jxcore-log: 
,09-26 12:21:51.533  5605  5652 I jxcore-log: 2016-09-26 16:21:51 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:51.533  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:51.533  5605  5652 I jxcore-log: ''
09-26 12:21:51.533  5605  5652 I jxcore-log: 
,09-26 12:21:51.538  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:51.538  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:51.538  5605  5652 W jxcore-log:  color: red
09-26 12:21:51.538  5605  5652 W jxcore-log: 
,09-26 12:21:52.555  5605  5652 I jxcore-log: 2016-09-26 16:21:52 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:52.555  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:52.555  5605  5652 I jxcore-log: ''
09-26 12:21:52.555  5605  5652 I jxcore-log: 
,09-26 12:21:52.562  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:52.562  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:52.562  5605  5652 W jxcore-log:  color: red
09-26 12:21:52.562  5605  5652 W jxcore-log: 
,09-26 12:21:52.578  5605  5652 I jxcore-log: 2016-09-26 16:21:52 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:52.578  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:52.578  5605  5652 I jxcore-log: ''
09-26 12:21:52.578  5605  5652 I jxcore-log: 
,09-26 12:21:52.585  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:52.585  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:52.585  5605  5652 W jxcore-log:  color: red
09-26 12:21:52.585  5605  5652 W jxcore-log: 
,09-26 12:21:53.603  5605  5652 I jxcore-log: 2016-09-26 16:21:53 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:53.603  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:53.603  5605  5652 I jxcore-log: ''
09-26 12:21:53.603  5605  5652 I jxcore-log: 
,09-26 12:21:53.610  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:53.610  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:53.610  5605  5652 W jxcore-log:  color: red
09-26 12:21:53.610  5605  5652 W jxcore-log: 
,09-26 12:21:53.668  5605  5652 I jxcore-log: 2016-09-26 16:21:53 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:53.668  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:53.668  5605  5652 I jxcore-log: ''
09-26 12:21:53.668  5605  5652 I jxcore-log: 
,09-26 12:21:53.673  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:53.673  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:53.673  5605  5652 W jxcore-log:  color: red
09-26 12:21:53.673  5605  5652 W jxcore-log: 
,09-26 12:21:54.721  5605  5652 I jxcore-log: 2016-09-26 16:21:54 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:54.721  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:54.721  5605  5652 I jxcore-log: ''
09-26 12:21:54.721  5605  5652 I jxcore-log: 
,09-26 12:21:54.725  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:54.725  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:54.725  5605  5652 W jxcore-log:  color: red
09-26 12:21:54.725  5605  5652 W jxcore-log: 
,09-26 12:21:54.751  5605  5652 I jxcore-log: 2016-09-26 16:21:54 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:54.751  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:54.751  5605  5652 I jxcore-log: ''
09-26 12:21:54.751  5605  5652 I jxcore-log: 
,09-26 12:21:54.753  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:54.753  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:54.753  5605  5652 W jxcore-log:  color: red
09-26 12:21:54.753  5605  5652 W jxcore-log: 
,09-26 12:21:55.788  5605  5652 I jxcore-log: 2016-09-26 16:21:55 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:55.788  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:55.788  5605  5652 I jxcore-log: ''
09-26 12:21:55.788  5605  5652 I jxcore-log: 
,09-26 12:21:55.793  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:55.793  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:55.793  5605  5652 W jxcore-log:  color: red
09-26 12:21:55.793  5605  5652 W jxcore-log: 
,09-26 12:21:55.818  5605  5652 I jxcore-log: 2016-09-26 16:21:55 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:55.818  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:55.818  5605  5652 I jxcore-log: ''
09-26 12:21:55.818  5605  5652 I jxcore-log: 
,09-26 12:21:55.822  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:55.822  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:55.822  5605  5652 W jxcore-log:  color: red
09-26 12:21:55.822  5605  5652 W jxcore-log: 
,09-26 12:21:56.828  5605  5652 I jxcore-log: 2016-09-26 16:21:56 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:56.828  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:56.828  5605  5652 I jxcore-log: ''
09-26 12:21:56.828  5605  5652 I jxcore-log: 
,09-26 12:21:56.840  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:56.840  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:56.840  5605  5652 W jxcore-log:  color: red
09-26 12:21:56.840  5605  5652 W jxcore-log: 
,09-26 12:21:56.849  5605  5652 I jxcore-log: 2016-09-26 16:21:56 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:56.849  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:56.849  5605  5652 I jxcore-log: ''
09-26 12:21:56.849  5605  5652 I jxcore-log: 
,09-26 12:21:56.852  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:56.852  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:56.852  5605  5652 W jxcore-log:  color: red
09-26 12:21:56.852  5605  5652 W jxcore-log: 
,09-26 12:21:57.871  5605  5652 I jxcore-log: 2016-09-26 16:21:57 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:57.871  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:57.871  5605  5652 I jxcore-log: ''
09-26 12:21:57.871  5605  5652 I jxcore-log: 
,09-26 12:21:57.875  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:57.875  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:57.875  5605  5652 W jxcore-log:  color: red
09-26 12:21:57.875  5605  5652 W jxcore-log: 
,09-26 12:21:57.898  5605  5652 I jxcore-log: 2016-09-26 16:21:57 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:57.898  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:57.898  5605  5652 I jxcore-log: ''
09-26 12:21:57.898  5605  5652 I jxcore-log: 
,09-26 12:21:57.903  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:57.903  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:57.903  5605  5652 W jxcore-log:  color: red
09-26 12:21:57.903  5605  5652 W jxcore-log: 
,09-26 12:21:58.564   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:58.914  5605  5652 I jxcore-log: 2016-09-26 16:21:58 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:58.914  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:58.914  5605  5652 I jxcore-log: ''
09-26 12:21:58.914  5605  5652 I jxcore-log: 
,09-26 12:21:58.919  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:58.919  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:58.919  5605  5652 W jxcore-log:  color: red
09-26 12:21:58.919  5605  5652 W jxcore-log: 
,09-26 12:21:58.941  5605  5652 I jxcore-log: 2016-09-26 16:21:58 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:58.941  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:58.941  5605  5652 I jxcore-log: ''
09-26 12:21:58.941  5605  5652 I jxcore-log: 
,09-26 12:21:58.946  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:58.946  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:58.946  5605  5652 W jxcore-log:  color: red
09-26 12:21:58.946  5605  5652 W jxcore-log: 
,09-26 12:21:59.565   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:21:59.961  5605  5652 I jxcore-log: 2016-09-26 16:21:59 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:59.961  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:59.961  5605  5652 I jxcore-log: ''
09-26 12:21:59.961  5605  5652 I jxcore-log: 
09-26 12:21:59.965  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:59.965  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:59.965  5605  5652 W jxcore-log:  color: red
09-26 12:21:59.965  5605  5652 W jxcore-log: 
,09-26 12:21:59.975  5605  5652 I jxcore-log: 2016-09-26 16:21:59 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:59.975  5605  5652 I jxcore-log: $9@timers.js:120:1
09-26 12:21:59.975  5605  5652 I jxcore-log: ''
09-26 12:21:59.975  5605  5652 I jxcore-log: 
,09-26 12:21:59.980  5605  5652 W jxcore-log: %cUnhandled rejection emit@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:244:16
09-26 12:21:59.980  5605  5652 W jxcore-log: $9@timers.js:120:1
09-26 12:21:59.980  5605  5652 W jxcore-log:  color: red
09-26 12:21:59.980  5605  5652 W jxcore-log: 
,09-26 12:22:00.566   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:22:01.522   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:22:01.567   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:22:02.568   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:22:03.569   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:22:04.551   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:22:11.518   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=285998, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 12:22:15.172   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:22:23.571   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:22:24.573   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:22:25.575   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:22:26.576   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:22:27.578   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:22:28.579   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:22:31.820   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:22:32.024   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:22:34.856   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:22:35.173   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:22:53.580   551   551 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:22:53.580   551   551 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:23:02.095   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:23:05.133   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:23:08.581   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:09.582   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:10.584   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:11.586   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:12.587   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:13.588   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:23:14.220   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:23:15.177   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:23:18.589   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:19.591   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:20.274   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:23:20.592   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:21.594   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:22.598   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:23.599   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:23:31.171   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=365651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 12:23:33.600   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:34.601   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:35.180   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:23:35.603   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:36.604   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:37.605   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:38.606   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:23:51.650   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=386131, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:23:53.607   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:54.608   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:55.183   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:23:55.610   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:56.611   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:57.612   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:23:58.613   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:24:05.679   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:24:10.811   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 12:24:11.746   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:24:18.615   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:24:19.616   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:24:20.617   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:24:21.619   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:24:22.621   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:24:23.622   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:24:26.879   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:24:29.911   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:24:31.278   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=425758, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:24:35.187   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:24:48.623   551   551 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:24:48.623   551   551 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:24:55.190   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:25:00.397   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=454877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 12:25:08.625   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:09.626   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:10.628   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:11.629   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:12.630   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:13.631   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:25:15.193   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:25:18.633   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:19.635   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:20.636   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:20.877   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=475358, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:25:21.638   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:22.640   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:23.641   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:25:30.446   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:25:33.478   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:25:33.643   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:34.644   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:35.197   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:25:35.645   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:36.646   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:37.648   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:38.649   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:25:42.566   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:25:45.601   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:25:53.650   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:54.652   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:55.197   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:25:55.654   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:56.655   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:57.657   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:25:58.658   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:26:00.357   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=514837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 12:26:09.835   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:26:12.869   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:26:18.659   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:26:19.661   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:26:20.663   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:26:20.824   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=535304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:26:21.664   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:26:22.666   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:26:23.667   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:26:29.038   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=543518, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 12:26:35.202   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:26:48.668   551   551 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:26:48.668   551   551 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:26:49.517   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=563997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:26:55.204   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:26:55.263   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:26:57.731   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=572211, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-26 12:26:58.291   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:01.318   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:04.353   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:10.415   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:13.446   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:13.760   551   961 E QC-QMI  : qmi_client [551] 1: failed to locate client data
,09-26 12:27:13.761   519   519 E QC-QMI  : qmuxd: RX on fd=14 returned error=0 errno[2:No such file or directory]
09-26 12:27:13.761   519   519 E QC-QMI  : QMUX qmux_client_id=1 not found in qmux client list, unable to remove
,09-26 12:27:13.767   551   551 I Atfwd_Daemon: Stop the daemon....
,09-26 12:27:13.800  5980  5980 I libmdmdetect: ESOC framework not supported
,09-26 12:27:13.801  5980  5980 I libmdmdetect: Found internal modem: modem
09-26 12:27:13.802  5980  5980 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-26 12:27:13.797  5980  5980 W ATFWD-daemon: type=1400 audit(0.0:118): avc: denied { read write } for name="diag" dev="tmpfs" ino=11608 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-26 12:27:13.808  5980  5980 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-26 12:27:13.808  5980  5980 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-26 12:27:13.811  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:14.815  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:15.206   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:27:15.816  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:16.818  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:17.819  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:18.211   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=592691, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:27:18.819  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:27:19.512   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:22.549   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:23.820  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:24.822  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:25.824  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:26.825  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:27.826  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:28.826  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:27:35.207   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:27:38.827  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:39.828  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:40.730   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:40.829  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:41.830  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:42.831  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:43.832  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:27:46.797   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:52.866   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:55.211   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:27:55.902   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:27:58.834  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:27:59.835  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:00.836  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:01.838  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:02.839  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:03.840  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:28:08.028   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:28:11.048   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:28:15.214   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:28:17.117   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:28:23.179   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:28:23.841  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:24.842  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:25.843  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:26.204   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:28:26.844  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:27.846  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:28.847  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:28:29.244   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:28:35.217   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:28:41.353   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:28:44.394   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:28:53.848  5980  5980 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-26 12:28:53.848  5980  5980 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:28:58.850  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:28:59.851  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:00.853  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:01.854  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:02.565   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:29:02.856  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:03.857  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:29:05.601   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:29:08.622   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:29:08.858  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:09.860  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:10.861  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:11.654   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:29:11.863  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:12.864  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:13.865  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:29:15.224   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:29:23.866  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:24.867  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:25.868  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:26.869  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:27.871  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:28.871  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:29:29.850   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:29:32.881   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:29:35.224   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:29:43.872  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:44.873  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:45.874  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:46.876  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:47.877  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:29:48.877  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:29:55.225   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:30:08.879  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:09.880  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:10.881  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:11.883  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:12.884  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:13.885  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:30:15.228   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:30:21.325   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:30:24.362   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:30:35.231   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:30:38.885  5980  5980 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:30:38.886  5980  5980 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:30:48.584   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:30:48.887  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:49.889  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:50.891  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:51.612   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:30:51.892  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:52.894  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:53.895  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:30:55.233   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:30:58.896  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:30:59.898  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:00.900  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:01.901  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:02.902  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:03.903  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:31:13.904  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:14.906  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:15.237   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:31:15.848   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:31:15.907  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:16.908  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:17.910  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:18.887   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:31:18.911  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:31:33.912  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:34.914  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:35.240   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:31:35.915  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:36.917  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:37.918  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:38.919  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:31:46.143   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:31:49.165   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:31:52.198   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:31:55.238   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:31:55.244   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:31:58.921  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:31:59.923  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:00.925  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:01.926  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:02.928  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:03.929  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:32:07.352   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:32:10.383   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:32:15.247   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:32:28.930  5980  5980 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:32:28.930  5980  5980 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:32:35.248   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:32:43.932  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:44.933  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:45.935  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:46.737   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:32:46.937  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:47.939  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:48.940  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:32:49.769   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:32:53.941  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:54.943  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:55.945  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:56.947  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:57.948  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:32:58.949  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:33:04.907   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:33:07.939   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:33:08.950  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:09.952  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:10.953  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:11.955  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:12.957  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:13.958  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:33:15.256   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:33:23.095   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:33:26.120   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:33:28.959  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:29.960  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:30.962  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:31.963  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:32.965  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:33.966  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:33:35.257   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:33:41.279   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:33:44.314   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:33:53.967  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:54.968  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:55.260   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:33:55.970  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:56.430   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:33:56.971  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:57.973  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:33:58.975  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:34:02.488   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:34:11.576   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:34:15.261   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:34:17.640   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:34:23.976  5980  5980 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:34:23.976  5980  5980 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:34:29.768   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:34:35.265   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:34:35.823   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:34:43.977  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:44.903   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:34:44.978  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:45.980  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:46.981  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:47.983  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:48.984  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:34:50.972   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:34:53.985  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:54.987  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:55.267   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:34:55.988  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:56.991  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:57.992  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:34:58.993  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:35:03.075   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:35:06.104   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:35:08.994  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:09.997  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:10.998  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:12.000  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:13.001  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:14.002  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:35:15.268   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:35:18.205   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:35:21.231   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:35:24.263   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:35:27.286   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:35:29.004  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:30.005  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:31.007  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:32.008  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:33.010  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:34.011  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:35:35.270   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:35:36.374   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:35:41.322  5870  5885 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,09-26 12:35:42.437   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:35:51.518   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:35:54.012  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:55.014  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:55.272   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:35:56.015  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:57.017  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:58.018  5980  5980 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:35:59.018  5980  5980 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:36:00.611   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:36:09.710   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:36:12.738   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:36:15.276   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:36:24.019  5980  5980 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:36:24.019  5980  5980 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:36:35.278   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:36:40.005   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:36:46.066   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:36:49.031  5980  5982 E QC-QMI  : qmi_client [5980] 1d: failed to locate client data
,09-26 12:36:49.033   519   519 E QC-QMI  : qmuxd: RX on fd=14 returned error=0 errno[2:No such file or directory]
09-26 12:36:49.033   519   519 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-26 12:36:49.037  5980  5980 I Atfwd_Daemon: Stop the daemon....
,09-26 12:36:49.081  5994  5994 W ATFWD-daemon: type=1400 audit(0.0:119): avc: denied { read write } for name="diag" dev="tmpfs" ino=11608 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-26 12:36:49.084  5994  5994 I libmdmdetect: ESOC framework not supported
,09-26 12:36:49.085  5994  5994 I libmdmdetect: Found internal modem: modem
,09-26 12:36:49.086  5994  5994 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-26 12:36:49.096  5994  5994 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-26 12:36:49.096  5994  5994 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-26 12:36:49.097  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:36:50.102  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:36:51.104  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:36:52.105  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:36:53.106  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:36:54.107  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:36:55.279   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:36:59.108  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:00.110  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:01.112  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:01.209   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:02.113  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:03.114  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:04.116  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:37:04.239   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:13.330   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:14.117  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:15.118  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:15.283   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:37:16.120  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:16.363   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:17.121  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:18.123  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:19.124  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:37:19.392   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:22.423   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:28.481   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:34.125  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:35.127  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:35.284   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:37:36.128  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:37.130  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:38.131  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:37:39.132  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:37:40.603   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:44.787   928   940 I UsageStatsService: User[0] Flushing usage stats to disk
,09-26 12:37:46.665   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:52.731   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:37:55.287   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:37:59.134  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:00.134  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:01.136  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:02.137  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:03.138  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:04.139  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:38:04.858   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:38:10.914   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:38:15.289   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:38:20.006   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:38:26.062   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:38:29.140  5994  5994 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:38:29.141  5994  5994 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:38:34.142  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:35.143  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:35.289   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:38:36.144  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:37.146  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:38.147  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:38.180   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:38:39.148  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:38:44.150  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:44.211   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:38:45.152  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:46.154  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:47.155  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:48.157  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:49.157  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:38:53.294   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:38:59.159  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:38:59.338   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:00.160  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:01.161  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:02.162  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:03.163  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:04.164  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:39:05.395   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:08.425   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:11.459   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:14.489   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:15.294   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:39:17.523   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:19.167  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:20.168  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:20.555   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:21.170  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:22.171  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:23.173  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:24.174  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:39:26.624   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:32.688   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:35.297   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:39:41.757   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:44.175  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:44.799   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:45.176  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:46.178  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:47.180  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:47.837   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:48.181  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:39:49.181  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:39:50.866   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:39:55.299   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:39:59.964   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:40:14.182  5994  5994 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:40:14.183  5994  5994 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:40:15.300   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:40:21.156   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:40:24.184  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:25.185  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:26.187  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:27.188  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:27.224   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:40:28.190  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:29.191  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:40:30.258   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:40:33.770  3842  6003 I EventLogService: Aggregate from 1474906233675 (log), 1474906233675 (data)
,09-26 12:40:34.194  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:35.196  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:35.301   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:40:36.197  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:37.199  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:38.201  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:38.731   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1393211, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 12:40:39.201  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:40:42.810   928  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1397290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 12:40:45.401   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:40:48.440   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:40:49.203  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:50.204  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:51.206  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:51.468   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:40:52.207  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:53.209  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:40:54.210  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:40:54.504   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:40:55.303   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:41:09.211  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:09.646   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:41:10.213  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:11.215  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:12.217  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:12.671   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:41:13.218  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:14.219  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 12:41:15.306   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:41:18.711   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:41:34.220  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:35.221  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:35.309   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:41:36.223  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:36.878   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:41:37.224  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:38.225  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:41:39.226  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 12:41:55.310   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:42:04.226  5994  5994 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 12:42:04.227  5994  5994 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 12:42:07.145   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:42:15.313   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:42:16.249   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:42:19.228  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:20.230  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:21.231  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:22.232  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:23.234  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:24.234  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 12:42:29.236  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:30.237  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:31.238  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:31.402   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:42:32.240  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:33.241  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:34.242  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 12:42:34.434   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:42:35.314   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 12:42:37.467   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:42:40.509   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:42:43.540   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:42:44.244  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:45.245  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:46.246  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:46.568   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:42:47.248  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:48.249  5994  5994 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 12:42:49.250  5994  5994 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 12:42:49.602   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 12:42:55.319   928  2947 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,TIME-OUT KILL (timeout was 1400000ms)
```
