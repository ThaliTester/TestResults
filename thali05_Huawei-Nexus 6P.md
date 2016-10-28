#### Test 914377094e53433_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-28 15:45:01.027  5545  5590 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
10-28 15:45:01.049  3882  3882 I ConfigFetchService: fetch service done; releasing wakelock
10-28 15:45:01.050  3882  3882 I ConfigFetchService: stopping self
10-28 15:45:01.068  3882  4861 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
10-28 15:45:01.138  3882  4861 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
10-28 15:45:01.161  5545  5590 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
10-28 15:45:01.189  5545  5590 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
10-28 15:45:02.763   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:03.618  5602  5602 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-28 15:45:03.624  5602  5602 D AndroidRuntime: CheckJNI is OFF
10-28 15:45:03.653  5602  5602 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-28 15:45:03.689  5602  5602 I Radio-JNI: register_android_hardware_Radio DONE
10-28 15:45:03.706  5602  5602 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-28 15:45:03.712   930   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-28 15:45:03.763   930   940 I ActivityManager: Start proc 5611:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-28 15:45:03.764   535   535 I ServiceManager: Waiting for service AtCmdFwd...
10-28 15:45:03.769  5602  5602 D AndroidRuntime: Shutting down VM
,10-28 15:45:04.113   930  3179 I WindowManager: Screenshot max retries 4 of Token{5e8b1e9 ActivityRecord{bf7ba70 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{6246788 u0 Starting com.test.thalitest} drawState=4
,10-28 15:45:04.190  5611  5611 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-28 15:45:04.213  5611  5611 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-28 15:45:04.281  5611  5611 I LibraryLoader: Time to load native libraries: 64 ms (timestamps 4941-5005)
,10-28 15:45:04.281  5611  5611 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-28 15:45:04.310  5611  5611 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a7711d9}
,10-28 15:45:04.311  5611  5611 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-28 15:45:04.311  5611  5611 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-28 15:45:04.316  5611  5611 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-28 15:45:04.317  5611  5611 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-28 15:45:04.362  5611  5611 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-28 15:45:04.372  5611  5611 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-28 15:45:04.372  5611  5611 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-28 15:45:04.372  5611  5611 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-28 15:45:04.372  5611  5611 I Adreno  : Build Date                       : 12/06/15
10-28 15:45:04.372  5611  5611 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-28 15:45:04.372  5611  5611 I Adreno  : Local Branch                     : mybranch17112971
10-28 15:45:04.372  5611  5611 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-28 15:45:04.372  5611  5611 I Adreno  : Remote Branch                    : NONE
10-28 15:45:04.372  5611  5611 I Adreno  : Reconstruct Branch               : NOTHING
,10-28 15:45:04.403   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bec83ff:true
,10-28 15:45:04.435   402   402 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22462]" dev="sockfs" ino=22462 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 15:45:04.435   402   402 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22462]" dev="sockfs" ino=22462 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 15:45:04.446  5611  5611 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-28 15:45:04.454  5611  5611 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-28 15:45:04.475   404   404 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32812]" dev="sockfs" ino=32812 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 15:45:04.475   404   404 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32812]" dev="sockfs" ino=32812 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-28 15:45:04.478  5611  5648 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-28 15:45:04.479   941   941 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22466]" dev="sockfs" ino=22466 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-28 15:45:04.479   941   941 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[22466]" dev="sockfs" ino=22466 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-28 15:45:04.484  5611  5635 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-28 15:45:04.516  5611  5648 I OpenGLRenderer: Initialized EGL, version 1.4
,10-28 15:45:04.589   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +473ms (total +852ms)
,10-28 15:45:04.613  5611  5611 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5611
,10-28 15:45:04.701  5611  5611 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-28 15:45:04.765   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:04.847  5611  5651 D jxcore_app_log: JniHelper::setJavaVM(0xf523c000), pthread_self() = -604243664
,10-28 15:45:04.851  5611  5651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-28 15:45:04.851  5611  5651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-28 15:45:04.851  5611  5651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-28 15:45:04.851  5611  5651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-28 15:45:04.851  5611  5651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-28 15:45:04.851  5611  5651 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5f36 added. We now have 1 listener(s)
,10-28 15:45:04.853  5611  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-28 15:45:04.854  5611  5651 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-28 15:45:04.854  5611  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:45:04.855  5611  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-28 15:45:04.857  5611  5651 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7210d added. We now have 1 listener(s)
10-28 15:45:04.857  5611  5651 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 15:45:04.860   930  3013 D WifiService: New client listening to asynchronous messages
,10-28 15:45:04.861  5611  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 15:45:04.861  5611  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-28 15:45:04.861  5611  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
10-28 15:45:04.861  5611  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-28 15:45:04.861  5611  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-28 15:45:04.861  5611  5651 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-28 15:45:04.861  5611  5651 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,10-28 15:45:04.863  5611  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:45:04.863  5611  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-28 15:45:04.867  5611  5651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-28 15:45:04.867  5611  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:45:04.867  5611  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:04.867  5611  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:04.867  5611  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:04.867  5611  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:45:04.867  5611  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:04.867  5611  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:04.867  5611  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:45:04.867  5611  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,10-28 15:45:04.867  5611  5651 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-28 15:45:04.868  5611  5651 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-28 15:45:04.870  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:04.872  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:04.885  5611  5611 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-28 15:45:05.148  5611  5620 I art     : Background sticky concurrent mark sweep GC freed 86967(8MB) AllocSpace objects, 17(1096KB) LOS objects, 20% free, 25MB/32MB, paused 2.239ms total 108.110ms
,10-28 15:45:05.423  5611  5620 I art     : Background partial concurrent mark sweep GC freed 59114(6MB) AllocSpace objects, 3(2MB) LOS objects, 36% free, 28MB/44MB, paused 1.590ms total 128.572ms
,10-28 15:45:05.479  5611  5657 W jxcore-log: Initializing JXcore engine
,10-28 15:45:05.479  5611  5657 W jxcore-log: JXcore engine is ready
,10-28 15:45:05.502  5657  5657 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=13038 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-28 15:45:05.502  5657  5657 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14545]" dev="sockfs" ino=14545 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-28 15:45:05.502  5657  5657 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-28 15:45:05.502  5657  5657 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30661]" dev="sockfs" ino=30661 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-28 15:45:05.512  5611  5657 W jxcore-log: Starting JXcore engine
,10-28 15:45:05.561  5611  5657 W jxcore-log: Platform android
10-28 15:45:05.561  5611  5657 W jxcore-log: 
10-28 15:45:05.561  5611  5657 W jxcore-log: Process ARCH arm
10-28 15:45:05.561  5611  5657 W jxcore-log: 
,10-28 15:45:05.745  5611  5657 I jxcore-log: JXcore Cordova bridge is ready!
10-28 15:45:05.745  5611  5657 I jxcore-log: 
,10-28 15:45:05.745  5611  5657 W jxcore-log: JXcore engine is started
,10-28 15:45:05.756  5611  5651 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-28 15:45:05.761  5611  5611 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-28 15:45:05.766   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:06.059  3571  3571 I ConfigService: onDestroy
,10-28 15:45:06.766   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:07.767   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-28 15:45:15.091  3571  5659 I VacuumService: Vacuum at: now=1477683915091 tag=VacuumService
,10-28 15:45:15.117  3571  5662 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-28 15:45:15.140  4776  4818 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-28 15:45:15.142  4776  4776 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-28 15:45:15.150  3571  5660 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-28 15:45:15.152  3571  5660 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-28 15:45:15.180  3571  5660 W Uploader:  no longer exists, so no auth token.
,10-28 15:45:15.186  3571  5662 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 15:45:15.364  5611  5657 I jxcore-log: 2016-10-28 19:45:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-28 15:45:15.364  5611  5657 I jxcore-log: 
,10-28 15:45:15.366  5611  5657 I jxcore-log: 2016-10-28 19:45:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-28 15:45:15.366  5611  5657 I jxcore-log: 
,10-28 15:45:15.370  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:45:15.370  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:15.370  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:15.370  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:15.370  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:45:15.370  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:15.370  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:15.370  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:45:15.371  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 15:45:15.372  5611  5657 I jxcore-log: 2016-10-28 19:45:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-28 15:45:15.372  5611  5657 I jxcore-log: 
,10-28 15:45:15.373  5611  5657 I jxcore-log: 2016-10-28 19:45:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-28 15:45:15.373  5611  5657 I jxcore-log: 
,10-28 15:45:15.506  3571  5664 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 15:45:15.583  3571  5662 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 15:45:15.601  5611  5657 I jxcore-log: 2016-10-28 19:45:15 - DEBUG UnitTest_app: 'Running unit tests'
10-28 15:45:15.601  5611  5657 I jxcore-log: 
,10-28 15:45:15.601  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:45:15.601  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ddd454 added. We now have 2 listener(s)
10-28 15:45:15.602  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 15:45:15.602  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:45:15.602  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:45:15.602  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-28 15:45:15.602  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2ffd added. We now have 2 listener(s)
10-28 15:45:15.602  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 15:45:15.603  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-28 15:45:15.604  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:45:15.606  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:45:15.606  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:15.606  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:15.606  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:15.606  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:45:15.606  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:15.606  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:15.606  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:45:15.607  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 15:45:15.607  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-28 15:45:15.608  5611  5657 D executeNativeTests: Running unit tests
10-28 15:45:15.610  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:15.613  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:15.645  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-28 15:45:15.645  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 added. We now have 3 listener(s)
10-28 15:45:15.646  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 15:45:15.646  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:45:15.646  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:45:15.646  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:45:15.646  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 added. We now have 3 listener(s)
10-28 15:45:15.646  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:45:15.646  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 15:45:15.648  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:45:15.650  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:45:15.650  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:15.650  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:15.650  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:15.650  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:45:15.650  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:15.650  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:15.650  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:45:15.651  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:15.651  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-28 15:45:15.652  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-28 15:45:15.652  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 15:45:15.652  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 15:45:15.652  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 15:45:15.653  5611  5657 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,10-28 15:45:15.653  5611  5657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-28 15:45:15.653  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-28 15:45:15.653  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-28 15:45:15.653  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 15:45:15.653  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 15:45:15.654  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:15.654  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:15.654  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:15.654  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:15.654  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:45:15.654  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:45:15.654  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:15.654  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:45:15.654  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 removed from the list
10-28 15:45:15.654  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:15.654  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 removed from the list
10-28 15:45:15.656  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:15.661  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:15.661  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:15.661  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:15.661  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:15.661  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:15.661  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.662  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.662  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:15.662  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.662  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:15.662  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:15.662  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:15.662  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:15.663  5611  5657 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-28 15:45:15.663  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:15.663  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:15.663  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-28 15:45:15.663  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:15.663  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:15.663  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:15.663  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:15.663  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
,10-28 15:45:15.664  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:15.664  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:15.664  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:15.664  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:15.664  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:15.664  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:15.664  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:15.664  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.664  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.664  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.664  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.664  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:15.664  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:15.664  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:15.664  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:15.667  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-28 15:45:15.667  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-28 15:45:15.667  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-28 15:45:15.668  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-28 15:45:15.668  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:15.668  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:15.668  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:15.668  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:15.669  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:15.669  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:15.669  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:15.669  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:15.669  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:15.669  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:15.669  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:15.669  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:15.669  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:15.669  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:15.669  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:15.669  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.669  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.669  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.669  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.669  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:15.669  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:15.670  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:15.670  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:15.670  5611  5657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-28 15:45:15.671  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:45:15.672  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:45:15.672  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:15.672  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:15.672  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:15.672  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:45:15.672  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:15.672  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:15.672  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:45:15.673  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:15.673  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 15:45:15.673  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:45:15.673  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 15:45:15.673  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 15:45:15.673  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:45:15.674  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 15:45:15.676  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:15.676  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 15:45:15.676  5611  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 15:45:15.676  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 15:45:15.677  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:15.678  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.678  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-28 15:45:15.679  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-28 15:45:15.679  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-28 15:45:15.680  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-28 15:45:15.681  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-28 15:45:15.681  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.681  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 15:45:15.681  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 15:45:15.681  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 15:45:15.681  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-28 15:45:15.681  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.682  5611  5657 D BluetoothAdapter: STATE_ON
10-28 15:45:15.683  4562  4579 D BtGatt.GattService: registerClient() - UUID=2d874355-cead-4eab-83b6-9fd57898239f
10-28 15:45:15.684  4562  4640 D BtGatt.GattService: onClientRegistered() - UUID=2d874355-cead-4eab-83b6-9fd57898239f, clientIf=5
10-28 15:45:15.685  5611  5621 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-28 15:45:15.686  4562  4796 D BtGatt.GattService: start scan with filters
10-28 15:45:15.689  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-28 15:45:15.689  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.689  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 15:45:15.690  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.690  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 15:45:15.690  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 15:45:15.690  4562  4643 D BtGatt.ScanManager: handling starting scan
10-28 15:45:15.690  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:45:15.690  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 15:45:15.690  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 15:45:15.690  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:45:15.690  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 15:45:15.690  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 15:45:15.690  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.690  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-28 15:45:15.692  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.692  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:45:15.692  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.692  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:15.692  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:45:15.692  5611  5657 I io.jxcore.node.ConnectionHelper: start: OK
10-28 15:45:15.693  4562  4643 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:45:15.694  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 15:45:15.694  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:15.694  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:15.695  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:45:15.695  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:45:15.701  4562  4640 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 15:45:15.701  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:15.701  4562  4643 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-28 15:45:15.706  4562  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 15:45:15.706  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:15.707  4562  4643 D BtGatt.ScanManager: Starting BLE batch scan
10-28 15:45:15.707  4562  4643 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-28 15:45:15.717  4562  4640 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 15:45:15.717  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:15.722  4562  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 15:45:15.722  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 15:45:15.788  3571  5664 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 15:45:15.854  3571  5660 W Uploader:  no longer exists, so no auth token.
,10-28 15:45:15.868  3571  5662 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 15:45:15.963  3571  5664 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 15:45:16.196  5611  5611 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-28 15:45:16.197  5611  5611 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:45:16.197  5611  5611 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-28 15:45:16.226  4562  4562 D BtGatt.ScanManager: awakened up at time 156951
,10-28 15:45:16.229  4562  4643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-28 15:45:16.259  4562  4640 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,10-28 15:45:16.260  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:16.260  4562  4640 D BtGatt.GattService: current time is 156984921724
10-28 15:45:16.261  4562  4640 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,10-28 15:45:16.264  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,10-28 15:45:16.266  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,10-28 15:45:16.272  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
,10-28 15:45:19.307   930  3012 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-28 15:45:20.249   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-28 15:45:20.697  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 15:45:20.698  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:20.698  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-28 15:45:20.698  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:20.698  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-28 15:45:20.698  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-28 15:45:20.698  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-28 15:45:20.698  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 15:45:20.698  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-28 15:45:20.698  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 15:45:20.700  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.700  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.700  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:20.700  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 15:45:20.700  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.702  5611  5657 D BluetoothAdapter: STATE_ON
10-28 15:45:20.702  4562  4796 D BtGatt.GattService: stopScan() - queue size =1
10-28 15:45:20.703  4562  4580 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-28 15:45:20.704  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 15:45:20.704  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.704  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 15:45:20.704  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.704  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.704  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:20.705  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.705  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 15:45:20.705  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.705  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.705  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.705  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-28 15:45:20.706  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 15:45:20.706  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:45:20.707  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.708  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.708  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:45:20.708  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.708  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:20.708  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:20.708  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:20.709  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-28 15:45:20.709  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:20.708  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:45:20.709  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:20.709  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:20.709  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:20.709  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:45:20.709  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:20.709  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:20.709  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 15:45:20.709  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:45:20.710  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 15:45:20.710  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 15:45:20.710  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:45:20.710  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 15:45:20.710  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-28 15:45:20.711  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:45:20.711  4562  4562 D BtGatt.ScanManager: awakened up at time 161436
10-28 15:45:20.713  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 15:45:20.714  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:20.714  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:20.714  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:45:20.714  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-28 15:45:20.719  4562  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 15:45:20.719  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:20.719  4562  4643 D BtGatt.ScanManager: stopping BLe Batch
,10-28 15:45:20.725  4562  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-28 15:45:20.725  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:20.726  4562  4643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-28 15:45:20.742  4562  4640 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
10-28 15:45:20.742  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 15:45:20.742  4562  4640 D BtGatt.GattService: current time is 161467274148
10-28 15:45:20.743  4562  4640 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -87, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -79, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
10-28 15:45:20.743  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-28 15:45:20.743  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-28 15:45:20.744  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-28 15:45:20.744  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-28 15:45:20.744  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-28 15:45:20.744  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,10-28 15:45:21.215  5611  5611 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 15:45:22.768   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:23.283   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-28 15:45:23.769   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:24.771   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:25.710  5611  5657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-28 15:45:25.713  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 15:45:25.719  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:45:25.719  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:25.719  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:25.719  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:25.719  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:45:25.719  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:25.719  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:25.719  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:45:25.722  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 15:45:25.723  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 15:45:25.723  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:45:25.723  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 15:45:25.723  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 15:45:25.723  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 15:45:25.723  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 15:45:25.728  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 15:45:25.728  5611  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 15:45:25.728  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 15:45:25.729  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:25.732  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.733  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-28 15:45:25.733  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-28 15:45:25.733  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-28 15:45:25.735  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:25.743  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:25.743  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 15:45:25.743  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 15:45:25.744  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 15:45:25.744  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-28 15:45:25.744  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.745  5611  5657 D BluetoothAdapter: STATE_ON
,10-28 15:45:25.751  4562  4796 D BtGatt.GattService: registerClient() - UUID=3e799d82-b941-4ddd-8a44-81e5b8e26145
,10-28 15:45:25.751  4562  4640 D BtGatt.GattService: onClientRegistered() - UUID=3e799d82-b941-4ddd-8a44-81e5b8e26145, clientIf=5
10-28 15:45:25.752  5611  5622 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-28 15:45:25.753  4562  4580 D BtGatt.GattService: start scan with filters
,10-28 15:45:25.758  4562  4643 D BtGatt.ScanManager: handling starting scan
,10-28 15:45:25.760  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-28 15:45:25.761  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.761  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 15:45:25.761  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.761  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 15:45:25.761  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 15:45:25.761  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,10-28 15:45:25.761  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 15:45:25.761  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 15:45:25.762  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.762  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,10-28 15:45:25.762  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-28 15:45:25.764  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 15:45:25.764  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.768  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.768  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:45:25.768  4562  4640 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 15:45:25.768  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.768  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:25.768  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.769  5611  5657 I io.jxcore.node.ConnectionHelper: start: OK
10-28 15:45:25.769  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.769  4562  4643 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-28 15:45:25.773   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:25.776  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:25.777  5611  5657 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-28 15:45:25.777  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:25.777  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-28 15:45:25.777  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:25.777  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-28 15:45:25.777  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:25.777  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-28 15:45:25.778  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.778  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.778  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.778  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.778  4562  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-28 15:45:25.778  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 15:45:25.778  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:25.779  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:45:25.779  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 15:45:25.779  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 15:45:25.779  4562  4643 D BtGatt.ScanManager: Starting BLE batch scan
10-28 15:45:25.779  4562  4643 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-28 15:45:25.779  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:25.779  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.779  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.779  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 15:45:25.780  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:25.781  5611  5657 D BluetoothAdapter: STATE_ON
10-28 15:45:25.782  4562  4788 D BtGatt.GattService: stopScan() - queue size =1
10-28 15:45:25.783  4562  4580 D BtGatt.GattService: unregisterClient() - clientIf=5
10-28 15:45:25.784  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 15:45:25.784  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.784  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 15:45:25.784  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.785  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.785  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.785  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:25.785  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 15:45:25.785  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.785  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.785  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.786  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 15:45:25.786  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 15:45:25.786  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:45:25.787  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.788  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.788  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:45:25.789  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.789  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.789  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:25.789  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:25.789  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:45:25.789  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:25.790  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:25.790  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:25.790  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:25.790  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:25.790  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:25.790  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:45:25.790  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:45:25.790  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,10-28 15:45:25.790  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.790  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 15:45:25.790  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 15:45:25.790  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.790  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.791  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 15:45:25.791  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.793  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-28 15:45:25.793  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.793  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.793  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.793  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:45:25.793  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:25.793  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:25.793  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:25.795  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.795  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:25.795  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.795  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:25.795  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:25.795  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:25.795  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:25.795  4562  4640 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 15:45:25.795  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:25.796  5611  5657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-28 15:45:25.798  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:45:25.804  4562  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 15:45:25.804  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:25.804  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:45:25.804  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:25.804  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:25.804  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:25.804  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:45:25.804  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:25.804  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:25.804  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:45:25.807  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:25.807  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 15:45:25.807  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:45:25.807  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 15:45:25.807  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 15:45:25.808  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:45:25.808  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-28 15:45:25.811  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:25.812  4562  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 15:45:25.812  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:25.812  4562  4643 D BtGatt.ScanManager: stopping BLe Batch
10-28 15:45:25.812  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 15:45:25.812  5611  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 15:45:25.813  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 15:45:25.814  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:25.816  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.816  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-28 15:45:25.817  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-28 15:45:25.817  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-28 15:45:25.819  4562  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-28 15:45:25.819  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:25.819  4562  4643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-28 15:45:25.821  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.821  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-28 15:45:25.821  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 15:45:25.821  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 15:45:25.821  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-28 15:45:25.821  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.822  5611  5657 D BluetoothAdapter: STATE_ON
10-28 15:45:25.824  4562  4640 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-28 15:45:25.824  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:25.824  4562  4579 D BtGatt.GattService: registerClient() - UUID=95c862cf-7a58-4831-912a-1f1f826a203b
10-28 15:45:25.826  4562  4640 D BtGatt.GattService: onClientRegistered() - UUID=95c862cf-7a58-4831-912a-1f1f826a203b, clientIf=5
,10-28 15:45:25.826  5611  5621 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-28 15:45:25.826  4562  4580 D BtGatt.GattService: start scan with filters
,10-28 15:45:25.830  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-28 15:45:25.830  4562  4643 D BtGatt.ScanManager: handling starting scan
10-28 15:45:25.830  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.830  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 15:45:25.830  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.830  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-28 15:45:25.830  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 15:45:25.830  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.831  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 15:45:25.831  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 15:45:25.831  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.831  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.831  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-28 15:45:25.831  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 15:45:25.831  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.834  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:25.834  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:45:25.834  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.834  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:25.834  5611  5657 I io.jxcore.node.ConnectionHelper: start: OK
10-28 15:45:25.834  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-28 15:45:25.835  4562  4640 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 15:45:25.835  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 15:45:25.836  4562  4643 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-28 15:45:25.837  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-28 15:45:25.837  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.837  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.837  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:45:25.838  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-28 15:45:25.841  4562  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 15:45:25.841  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:25.841  4562  4643 D BtGatt.ScanManager: Starting BLE batch scan
,10-28 15:45:25.841  4562  4643 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-28 15:45:25.851  4562  4640 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 15:45:25.851  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 15:45:25.856  4562  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 15:45:25.856  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 15:45:26.312   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-28 15:45:26.315   930  3014 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-28 15:45:26.339  5611  5611 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-28 15:45:26.339  5611  5611 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:45:26.339  5611  5611 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-28 15:45:26.776   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:27.778   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-28 15:45:29.338   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-28 15:45:29.344   930  3014 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-28 15:45:30.835  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 15:45:30.835  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-28 15:45:30.836  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-28 15:45:30.836  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:45:30.836  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-28 15:45:30.836  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:30.836  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-28 15:45:30.836  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 15:45:30.836  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 15:45:30.837  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-28 15:45:30.837  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.837  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.837  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.838  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 15:45:30.838  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.842  5611  5657 D BluetoothAdapter: STATE_ON
10-28 15:45:30.843  4562  4796 D BtGatt.GattService: stopScan() - queue size =1
,10-28 15:45:30.845  4562  4788 D BtGatt.GattService: unregisterClient() - clientIf=5
10-28 15:45:30.846  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 15:45:30.847  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:30.847  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 15:45:30.847  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.848  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.848  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.849  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.849  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 15:45:30.849  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.849  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.850  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:30.850  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 15:45:30.850  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 15:45:30.851  4562  4562 D BtGatt.ScanManager: awakened up at time 171575
10-28 15:45:30.852  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:45:30.852  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.856  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.856  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:45:30.856  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.856  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:30.856  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:45:30.857  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:45:30.857  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 15:45:30.857  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:45:30.857  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 15:45:30.857  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-28 15:45:30.857  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:45:30.857  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 15:45:30.857  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 15:45:30.858  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:45:30.858   930  3827 I ActivityManager: Killing 5004:com.google.android.apps.maps/u0a58 (adj 15): empty #17
10-28 15:45:30.860  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 15:45:30.860  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:45:30.860  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,10-28 15:45:30.860  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:45:30.860  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-28 15:45:30.888  4562  4640 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 15:45:30.888  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 15:45:30.888  4562  4643 D BtGatt.ScanManager: stopping BLe Batch
,10-28 15:45:30.893  4562  4640 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-28 15:45:30.893  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:45:30.893  4562  4643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-28 15:45:30.908  4562  4640 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
10-28 15:45:30.909  4562  4640 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 15:45:30.909  4562  4640 D BtGatt.GattService: current time is 171633766413
10-28 15:45:30.909  4562  4640 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -88, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -88, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -96, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-28 15:45:30.909  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-28 15:45:30.910  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-28 15:45:30.910  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-28 15:45:30.910  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-28 15:45:30.910  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-28 15:45:30.910  4562  4640 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-28 15:45:31.361  5611  5611 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
10-28 15:45:31.362  5611  5611 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-28 15:45:31.362  5611  5611 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-28 15:45:35.858  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 15:45:35.858  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:35.858  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:35.858  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:35.858  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.859  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:45:35.859  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.859  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:35.859  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.859  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
,10-28 15:45:35.860  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 15:45:35.860  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:35.861  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:45:35.861  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.862  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:35.865  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.865  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.865  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:35.865  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.865  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-28 15:45:35.866  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.866  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.867  5611  5657 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-28 15:45:35.869  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:35.869  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-28 15:45:35.869  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:35.869  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-28 15:45:35.870  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.870  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:35.870  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.870  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
,10-28 15:45:35.870  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.870  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.870  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:35.871  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.871  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:35.871  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.871  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.871  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.876  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:35.876  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.876  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.876  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.876  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:35.876  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.877  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
,10-28 15:45:35.878  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-28 15:45:35.878  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:35.878  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:35.878  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-28 15:45:35.878  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:35.878  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.878  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.878  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.879  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
,10-28 15:45:35.879  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.879  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.879  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:35.879  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.879  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:35.879  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.879  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.879  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.880  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.881  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.881  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:35.881  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.881  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:35.881  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.881  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.882  5611  5657 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-28 15:45:35.882  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:35.882  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:35.882  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:35.882  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:35.882  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.882  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.882  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.883  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:35.883  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.883  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.883  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 15:45:35.883  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.883  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.883  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.883  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.883  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.885  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.885  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:35.885  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.885  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.885  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:35.885  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.885  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
,10-28 15:45:35.886  5611  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-28 15:45:35.886  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:35.886  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-28 15:45:35.886  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:35.886  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:35.886  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.887  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:35.887  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.887  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:35.887  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.887  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.887  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:35.887  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.887  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:35.887  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.887  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.887  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.889  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.889  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.889  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:35.889  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.889  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:35.889  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.889  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.890  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-28 15:45:35.890  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 15:45:35.890  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 15:45:35.891  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-28 15:45:35.891  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 15:45:35.891  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 15:45:35.891  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-28 15:45:35.891  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 15:45:35.891  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-28 15:45:35.891  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:35.891  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:35.891  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:35.891  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:35.891  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.891  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:35.892  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.892  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:35.892  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.892  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.892  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:35.892  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.892  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.892  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.892  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.892  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:35.897  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.897  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.897  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.897  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.897  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:35.897  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.897  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.898  5611  5657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-28 15:45:35.898  5611  5657 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-28 15:45:35.898  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-28 15:45:35.901  5611  5657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-28 15:45:35.901  5611  5657 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-28 15:45:35.901  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-28 15:45:35.901  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-28 15:45:35.901  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-28 15:45:35.901  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,10-28 15:45:35.902  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-28 15:45:35.902  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-28 15:45:35.902  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-28 15:45:35.902  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-28 15:45:35.902  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-28 15:45:35.902  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-28 15:45:35.902  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,10-28 15:45:35.902  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-28 15:45:35.903  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-28 15:45:35.903  5611  5657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-28 15:45:35.904  5611  5657 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-28 15:45:35.904  5611  5657 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-28 15:45:35.904  5611  5657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-28 15:45:35.904  5611  5657 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-28 15:45:35.904  5611  5657 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-28 15:45:35.904  5611  5657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-28 15:45:35.904  5611  5657 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-28 15:45:35.904  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-28 15:45:35.907  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-28 15:45:35.908  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,10-28 15:45:35.908  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-28 15:45:35.909  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-28 15:45:35.909  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-28 15:45:35.909  5611  5657 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-28 15:45:35.909  5611  5657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-28 15:45:35.909  5611  5657 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-28 15:45:35.910  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:35.910  5611  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-28 15:45:35.910  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:35.910  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:35.910  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:35.910  5611  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-28 15:45:35.910  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.910  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.910  5611  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-28 15:45:35.911  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.911  5611  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-28 15:45:35.911  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-28 15:45:35.911  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:35.912  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.912  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.912  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:35.912  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.912  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.912  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.912  5611  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-28 15:45:35.912  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoot,hManager: release: 2 listener(s) left
10-28 15:45:35.912  5611  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
10-28 15:45:35.912  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.913  5611  5669 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-28 15:45:35.913  5611  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 15:45:35.913  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.913  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.913  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.913  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.913  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:35.913  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.914  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.915  4579  4579 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32317]" dev="sockfs" ino=32317 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-28 15:45:35.914  5611  5657 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-28 15:45:35.915  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:35.915  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:35.915  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:35.915  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-28 15:45:35.916  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.916  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.916  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.916  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:35.916  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.916  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
,10-28 15:45:35.916  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:35.916  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.916  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.916  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.916  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.916  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.915  4579  4579 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32317]" dev="sockfs" ino=32317 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-28 15:45:35.919  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.919  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.919  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.919  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.919  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-28 15:45:35.919  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.920  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.920  5611  5657 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-28 15:45:35.921  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:35.921  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:35.921  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:35.921  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:35.921  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.921  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.921  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-28 15:45:35.921  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:35.921  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.921  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.921  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:35.921  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.921  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.921  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.921  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.921  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.923  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:35.923  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.923  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.924  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.924  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:35.924  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.924  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.925  5611  5657 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-28 15:45:35.925  5611  5657 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-28 15:45:35.925  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-28 15:45:35.925  5611  5657 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,10-28 15:45:35.925  5611  5657 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-28 15:45:35.925  5611  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-28 15:45:35.925  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-28 15:45:35.925  5611  5657 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-28 15:45:35.925  5611  5657 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-28 15:45:35.925  5611  5657 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-28 15:45:35.926  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-28 15:45:35.926  5611  5657 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-28 15:45:35.926  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 15:45:35.926  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:35.926  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:35.926  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:35.926  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.926  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.926  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.926  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:35.926  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.926  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.926  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 15:45:35.926  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.927  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.927  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.927  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.927  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.928  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.928  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:35.929  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:35.929  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:35.929  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:35.929  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.929  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
,10-28 15:45:35.930  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-28 15:45:35.930  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.930  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:35.931  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:35.931  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:35.931  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:35.931  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:35.931  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:35.931  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:35.931  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:40.932  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.932  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.932  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:40.932  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.932  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.932  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-28 15:45:40.932  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:40.932  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:40.933  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:40.933  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:40.933  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:40.933  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.933  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.933  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:40.933  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
,10-28 15:45:40.933  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.933  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.933  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:40.933  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.933  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.934  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.934  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.934  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:40.937  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:40.937  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.938  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.938  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:40.938  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:40.938  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.938  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
,10-28 15:45:40.941  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-28 15:45:40.942  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 15:45:40.944  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-28 15:45:40.946  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-28 15:45:40.946  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-28 15:45:40.947  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-28 15:45:40.947  5611  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-28 15:45:40.947  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-28 15:45:40.947  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-28 15:45:40.948  5611  5611 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-28 15:45:40.948  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:40.948  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-28 15:45:40.949  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-28 15:45:40.949  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-28 15:45:40.949  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.949  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-28 15:45:40.950  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-28 15:45:40.950  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:40.950  5611  5611 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-28 15:45:40.950  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.950  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 15:45:40.950  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 15:45:40.950  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 15:45:40.950  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:45:40.951  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.951  5611  5671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 15:45:40.951  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:40.952  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.952  4796  4796 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32324]" dev="sockfs" ino=32324 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-28 15:45:40.953  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-28 15:45:40.953  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.953  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.953  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.953  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:45:40.953  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:40.953  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:45:40.953  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-28 15:45:40.953  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:45:40.953  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:40.953  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:40.953  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.953  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.953  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-28 15:45:40.953  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:40.953  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.953  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.953  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 15:45:40.953  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.954  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.954  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.954  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.954  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.955  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.952  4796  4796 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32324]" dev="sockfs" ino=32324 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-28 15:45:40.955  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.955  5611  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-28 15:45:40.955  5611  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-28 15:45:40.955  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.955  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:40.955  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:40.955  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.955  5611  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-28 15:45:40.955  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.956  5611  5611 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-28 15:45:40.956  5611  5611 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-28 15:45:40.957  5611  5657 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-28 15:45:40.957  5611  5657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-28 15:45:40.957  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-28 15:45:40.957  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 15:45:40.957  5611  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 15:45:40.957  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 15:45:40.957  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:40.957  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:40.958  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:40.958  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.958  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.958  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-28 15:45:40.958  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:40.958  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.958  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.958  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:40.958  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:45:40.958  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.958  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.958  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.958  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.960  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.960  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:40.960  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.960  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:40.960  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:40.960  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.960  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.964  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 15:45:40.964  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-28 15:45:40.964  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-28 15:45:40.965  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:40.965  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.965  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:40.965  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:40.965  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:40.965  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.965  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.965  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:40.965  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:45:40.965  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.965  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.965  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.965  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.966  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.966  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:40.966  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.967  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:40.967  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:40.967  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 15:45:40.967  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.968  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:45:40.968  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:45:40.968  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:45:40.968  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:45:40.968  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:45:40.968  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.968  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:45:40.968  5611  5657 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0a3733 not in the list
10-28 15:45:40.968  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:40.968  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
10-28 15:45:40.968  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:45:40.968  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:45:40.968  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.968  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:40.968  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:40.968  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.970  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.970  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:45:40.970  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:45:40.970  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:45:40.970  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:45:40.970  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 15:45:40.970  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3af0 not in the list
,10-28 15:45:40.972  5611  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-28 15:45:40.973  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-28 15:45:40.973  5611  5657 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-28 15:45:40.973  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-28 15:45:40.973  5611  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-28 15:45:40.973  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-28 15:45:40.975  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-28 15:45:40.975  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-28 15:45:40.975  5611  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-28 15:45:40.975  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-28 15:45:40.976  5611  5657 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-28 15:45:40.976  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-28 15:45:40.976  5611  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-28 15:45:40.976  5611  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-28 15:45:40.976  5611  5657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-28 15:45:40.976  5611  5657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-28 15:45:40.977  5611  5657 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-28 15:45:40.977  5611  5657 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-28 15:45:40.977  5611  5657 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,10-28 15:45:40.977  5611  5657 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-28 15:45:40.977  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:45:40.978  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdf9452 added. We now have 3 listener(s)
10-28 15:45:40.978  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:45:40.980  5611  5657 D BluetoothAdapter: enable(): BT is already enabled..!
10-28 15:45:40.980   930   940 D WifiService: setWifiEnabled: true pid=5611, uid=10077
10-28 15:45:40.980   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 15:45:41.043  4562  4749 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-28 15:45:41.043  5611  5669 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-28 15:45:41.044  5611  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-28 15:45:41.044  5611  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-28 15:45:41.044  4562  4774 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-28 15:45:41.454  5611  5611 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 15:45:45.984  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-28 15:45:45.985  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cf5323 added. We now have 4 listener(s)
10-28 15:45:45.985  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 15:45:45.997  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 15:45:45.997  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cf5323 removed from the list
10-28 15:45:45.997  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 15:45:45.998  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:45:45.998  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:45:45.999  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:45:46.000  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aad4020 added. We now have 4 listener(s)
10-28 15:45:46.000  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 15:45:46.004  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:45:46.004  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aad4020 removed from the list
,10-28 15:45:46.004  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 15:45:46.004  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:45:46.004  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:45:46.006  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:45:46.006  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e0e3dd9 added. We now have 4 listener(s)
10-28 15:45:46.006  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:45:46.008   930  3179 D WifiService: setWifiEnabled: false pid=5611, uid=10077
,10-28 15:45:46.008   930  3179 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 15:45:46.014   930  3012 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-28 15:45:46.015   930  3012 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-28 15:45:46.015   930  3012 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-28 15:45:46.015   930  3012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-28 15:45:46.019  4562  4636 D BluetoothAdapterState: Current state: ON, message: 23
10-28 15:45:46.019  4562  4636 D BluetoothAdapterProperties: Setting state to 13
10-28 15:45:46.019  4562  4636 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-28 15:45:46.020  4562  4636 D BluetoothAdapterProperties: onBluetoothDisable()
10-28 15:45:46.021  4562  4636 I BluetoothAdapterState: Entering PendingCommandState
10-28 15:45:46.024  4562  4640 D BluetoothAdapterProperties: Scan Mode:20
10-28 15:45:46.025  4562  4636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-28 15:45:46.026  4562  4562 D BluetoothMapService: onReceive
10-28 15:45:46.026  4562  4562 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-28 15:45:46.026  4562  4562 D BluetoothMapService: STATE_TURNING_OFF
10-28 15:45:46.027  4562  4562 D BluetoothMapService: MAP Service closeService in
10-28 15:45:46.027  4562  4562 D BluetoothMapMasInstance0: MAP Service shutdown
10-28 15:45:46.027  4562  4562 D ObexServerSockets0: shutdown(block = true)
10-28 15:45:46.027  4562  4562 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-28 15:45:46.028  4562  4562 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-28 15:45:46.028  4562  4799 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-28 15:45:46.028  4562  4774 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-28 15:45:46.029  4562  4798 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-28 15:45:46.030  4562  4562 I BtOppRfcommListener: stopping Accept Thread
10-28 15:45:46.030  4562  5302 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-28 15:45:46.031  4562  5302 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-28 15:45:46.034  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 15:45:46.034  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:46.034  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.034  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.034  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:46.034  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.034  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:46.034  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:46.034  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:45:46.035   930  5377 D DhcpClient: Clearing IP address
,10-28 15:45:46.035  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.035  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:46.035   507   923 D CommandListener: Clearing all IP addresses on wlan0
,10-28 15:45:46.041  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.041  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:46.041  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.041  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.041  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:46.041  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.041  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:46.041  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:46.041  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:45:46.041   507   923 D CommandListener: Setting iface cfg
10-28 15:45:46.042  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.042  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:46.043   930  5378 D DhcpClient: Receive thread stopped
,10-28 15:45:46.045  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:46.047  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:46.050   930   943 I ActivityManager: Start proc 5675:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-28 15:45:46.050  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:45:46.056  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 15:45:46.056  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:45:46.056  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.056  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.056  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:46.056  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.056  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:46.056  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:46.056  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:45:46.057  3571  5433 V NativeCrypto: Read error: ssl=0x7f68ee0000: I/O error during system call, Connection timed out
10-28 15:45:46.058  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.058  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:46.058  4562  4562 D HeadsetService: Received stop request...Stopping profile...
10-28 15:45:46.058  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 15:45:46.059  3571  5433 V NativeCrypto: SSL shutdown failed: ssl=0x7f68ee0000: I/O error during system call, Broken pipe
10-28 15:45:46.060   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-28 15:45:46.060   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-28 15:45:46.061  3810  3826 D BluetoothHeadset: Proxy object disconnected
10-28 15:45:46.062   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 15:45:46.062   533   533 E Parcel  : Reading a NULL string not supported here.
10-28 15:45:46.062  3127  3967 D BluetoothHeadset: Proxy object disconnected
10-28 15:45:46.062   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 15:45:46.062   930   930 D BluetoothHeadset: Proxy object disconnected
,10-28 15:45:46.063  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.063  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:46.063  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.063  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.063  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:46.063  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.063  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:46.063  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:46.063  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:45:46.063  3127  3127 D HeadsetProfile: Bluetooth service disconnected
,10-28 15:45:46.064  4562  4562 D A2dpService: Received stop request...Stopping profile...
,10-28 15:45:46.063  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.065  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:46.065  4562  4791 D A2dpStateMachine: Exit Disconnected: -1
10-28 15:45:46.067  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:46.068   930   930 D RttService: SCAN_AVAILABLE : 1
10-28 15:45:46.068   930   930 D BluetoothA2dp: Proxy object disconnected
,10-28 15:45:46.068   930  3079 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-28 15:45:46.071   930  3014 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-28 15:45:46.073  4562  4562 D HidService: Received stop request...Stopping profile...
,10-28 15:45:46.073  4562  4562 D HidService: Stopping Bluetooth HidService
10-28 15:45:46.074  3753  3905 W QCNEJ   : |CORE| network lost: 100
10-28 15:45:46.074  4562  4562 D HealthService: Received stop request...Stopping profile...
10-28 15:45:46.074  3753  3905 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-28 15:45:46.075  4562  4562 D PanService: Received stop request...Stopping profile...
10-28 15:45:46.076  4562  4562 D BluetoothMapService: Received stop request...Stopping profile...
10-28 15:45:46.076  4562  4562 D BluetoothMapService: stop()
10-28 15:45:46.077  4562  4562 D BluetoothMapAppObserver: deinitObservers()
10-28 15:45:46.077  4562  4562 D BluetoothMapAppObserver: removeReceiver()
,10-28 15:45:46.078  4562  4562 V BluetoothAdapterState: isTurningOff()=true
10-28 15:45:46.078  4562  4562 V BluetoothAdapterState: isTurningOn()=false
,10-28 15:45:46.078  4562  4562 V BluetoothAdapterState: isBleTurningOn()=false
,10-28 15:45:46.078  4562  4562 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:45:46.078  4562  4562 D SapService: Received stop request...Stopping profile...
10-28 15:45:46.078  4562  4562 V SapService: stop()
10-28 15:45:46.082  3127  3127 D BluetoothA2dp: Proxy object disconnected
10-28 15:45:46.083  3127  3127 D BluetoothInputDevice: Proxy object disconnected
10-28 15:45:46.083  3127  3127 D HidProfile: Bluetooth service disconnected
10-28 15:45:46.083  4562  4562 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-28 15:45:46.083  4562  4562 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-28 15:45:46.083  4562  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:45:46.083  4562  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:45:46.084  4562  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:45:46.084  4562  4640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-28 15:45:46.084  4562  4562 V BluetoothAdapterState: isTurningOff()=true
10-28 15:45:46.084  4562  4562 V BluetoothAdapterState: isTurningOn()=false
10-28 15:45:46.084  4562  4640 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-28 15:45:46.084  4562  4562 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:45:46.084  4562  4562 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:45:46.084  3127  3127 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-28 15:45:46.084  3127  3127 D PanProfile: Bluetooth service disconnected
10-28 15:45:46.084  3127  3127 D BluetoothMap: Proxy object disconnected
10-28 15:45:46.084  3127  3127 D MapProfile: Bluetooth service disconnected
10-28 15:45:46.085   930  3012 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-28 15:45:46.086  4562  4562 V BluetoothAdapterState: isTurningOff()=true
10-28 15:45:46.086  4562  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:45:46.086  4562  4562 V BluetoothAdapterState: isTurningOn()=false
10-28 15:45:46.086  4562  4562 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:45:46.086  4562  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:45:46.086  4562  4562 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:45:46.086  4562  4749 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-28 15:45:46.087  4562  4749 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-28 15:45:46.087  4562  4562 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-28 15:45:46.087  4562  4749 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-28 15:45:46.087  4562  4749 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-28 15:45:46.087  4562  4562 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-28 15:45:46.087  4562  4640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-28 15:45:46.087  4562  4562 V BluetoothAdapterState: isTurningOff()=true
10-28 15:45:46.087  4562  4640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-28 15:45:46.087  4562  4562 V BluetoothAdapterState: isTurningOn()=false
10-28 15:45:46.087  4562  4562 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:45:46.087  4562  4562 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:45:46.087  4562  4562 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-28 15:45:46.087  4562  4562 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-28 15:45:46.087  4562  4640 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-28 15:45:46.088  4562  4562 V BluetoothAdapterState: isTurningOff()=true
10-28 15:45:46.088  4562  4562 V BluetoothAdapterState: isTurningOn()=false
10-28 15:45:46.088  4562  4562 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:45:46.088  4562  4562 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:45:46.088  4562  4562 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-28 15:45:46.088  4562  4562 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-28 15:45:46.091  4562  4562 D BluetoothMapService: MAP Service closeService in
10-28 15:45:46.092  4562  4562 V BluetoothAdapterState: isTurningOff()=true
10-28 15:45:46.092  4562  4562 V BluetoothAdapterState: isTurningOn()=false
10-28 15:45:46.092  4562  4562 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:45:46.092  4562  4562 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:45:46.092  4562  4562 D BluetoothMapService: cleanup()
10-28 15:45:46.093  4562  4562 D BluetoothMapService: MAP Service closeService in
10-28 15:45:46.093  4562  4562 V BluetoothAdapterState: isTurningOff()=true
10-28 15:45:46.093  4562  4562 V BluetoothAdapterState: isTurningOn()=false
10-28 15:45:46.093  4562  4562 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:45:46.093  4562  4562 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:45:46.093  4562  4636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-28 15:45:46.094  4562  4636 D BluetoothAdapterProperties: Setting state to 15
10-28 15:45:46.094  4562  4636 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-28 15:45:46.094  4562  4636 I BluetoothAdapterState: Entering BleOnState
10-28 15:45:46.094   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 15:45:46.095  3127  3967 D BluetoothMap: onBluetoothStateChange: up=false
10-28 15:45:46.095   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 15:45:46.095   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 15:45:46.095  3127  3144 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 15:45:46.096  3127  3143 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 15:45:46.096  3127  3967 D BluetoothPan: onBluetoothStateChange on: false
10-28 15:45:46.097  3127  3144 D BluetoothPbap: onBluetoothStateChange: up=false
10-28 15:45:46.097   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 15:45:46.097  3810  4000 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-28 15:45:46.098  3127  3143 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-28 15:45:46.099  4562  4636 D BluetoothAdapterState: Current state: BLE ON, message: 20
,10-28 15:45:46.099  4562  4636 D BluetoothAdapterProperties: Setting state to 16
,10-28 15:45:46.099  4562  4636 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-28 15:45:46.100  4562  4636 D BluetoothAdapterProperties: onBleDisable
10-28 15:45:46.100  4562  4636 I BluetoothAdapterState: Entering PendingCommandState
10-28 15:45:46.100  4562  4637 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-28 15:45:46.101  4562  4749 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-28 15:45:46.101  4562  4749 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:45:46.102  4562  4640 D BluetoothAdapterProperties: Scan Mode:20
10-28 15:45:46.103  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.104  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:46.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:46.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:46.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:46.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:46.105  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.105   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 15:45:46.105  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:46.110  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.110  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:46.110  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.110  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.110  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:46.110  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.110  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:46.110  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:46.110  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:46.110   930  3012 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-28 15:45:46.111  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.111  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:46.113  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.113  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:46.113  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.113  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.113  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:46.113  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.113  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:46.113  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:46.113  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 15:45:46.115  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:46.116  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:46.118  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:46.118  5675  5675 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-28 15:45:46.128   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 15:45:46.129   507   923 D CommandListener: Clearing all IP addresses on wlan0
10-28 15:45:46.129   507   923 D TetherController: Setting IP forward enable = 0
10-28 15:45:46.130   930  3014 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-28 15:45:46.130   930  3014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-28 15:45:46.131  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-28 15:45:46.132   930   947 D Tethering: MasterInitialState.processMessage what=3
10-28 15:45:46.132   930  3012 D DhcpClient: doQuit
10-28 15:45:46.132   930  3012 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-28 15:45:46.133  5259  5259 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2f2bc55 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-28 15:45:46.133  3473  3473 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-28 15:45:46.134  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:46.134   930  5377 D DhcpClient: onQuitting
,10-28 15:45:46.136  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.136  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:46.136  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.136  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.136  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:45:46.136  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.136  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:46.136  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:46.136  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 15:45:46.137  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.137  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:46.139  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.139  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:46.139  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.139  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.139  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:45:46.139  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.139  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:46.139  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:46.139  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:46.140  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.140  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:46.142  4979  5019 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-28 15:45:46.142  4979  5019 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-28 15:45:46.142  4979  5019 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-28 15:45:46.142  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.142  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:46.142  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:46.142  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:46.142  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:45:46.142  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:46.142  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:46.142  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:46.142  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:46.142  4979  5019 E SarControlService: no key has been found,reset the power
10-28 15:45:46.142  4979  5050 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-28 15:45:46.142  4979  5050 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-28 15:45:46.142  4979  5050 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-28 15:45:46.143  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:46.143  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bl,uetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:46.143  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 15:45:46.143  5033  5033 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-28 15:45:46.144  4979  5050 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-28 15:45:46.144  4979  5050 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-28 15:45:46.144  4979  5050 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-28 15:45:46.144  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:46.145  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 15:45:46.145  5033  5033 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-28 15:45:46.145  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:46.147  5033  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c0f0723 HexData = [00000000ea03000000000000ffffffff]
10-28 15:45:46.147  5033  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 15:45:46.147  5033  5057 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-28 15:45:46.148  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-28 15:45:46.148  4979  4990 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-28 15:45:46.155   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a9920db:true
,10-28 15:45:46.156  5033  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c0f0723 HexData = [00000000eb03000000000000ffffffff]
,10-28 15:45:46.156  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-28 15:45:46.156  5033  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 15:45:46.156  5033  5057 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-28 15:45:46.157  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-28 15:45:46.157  4979  4989 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-28 15:45:46.162  3473  3473 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-28 15:45:46.166  3473  3473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-28 15:45:46.168   507   916 W SocketClient: write error (Broken pipe)
,10-28 15:45:46.168   507   916 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-28 15:45:46.168   507   916 W SocketListener: Error sending broadcast (Broken pipe)
10-28 15:45:46.169   930  3594 I ActivityManager: Start proc 5706:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-28 15:45:46.176   507   923 E Netd    : netlink response contains error (No such file or directory)
,10-28 15:45:46.179   930  3014 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-28 15:45:46.180   507   923 D TetherController: Setting IP forward enable = 0
,10-28 15:45:46.193  5675  5675 D LocalBluetoothProfileManager: Adding local MAP profile
10-28 15:45:46.194  5675  5675 D BluetoothMap: Create BluetoothMap proxy object
,10-28 15:45:46.207  5675  5675 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-28 15:45:46.207  3473  3473 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-28 15:45:46.216  3473  3473 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-28 15:45:46.217  5706  5706 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-28 15:45:46.225  5675  5675 D DockEventReceiver: finishStartingService: stopping service
,10-28 15:45:46.230   930  3827 I ActivityManager: Killing 4916:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-28 15:45:46.310  4562  4640 I bt_hci  : shut_down
,10-28 15:45:46.314  4562  4644 D bt_hwcfg: hw_epilog_process
,10-28 15:45:46.314  4562  4644 I bt_vendor: low_power_mode_cb
,10-28 15:45:46.317  4562  4644 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-28 15:45:46.317  4562  4644 I bt_vendor: epilog_cb
,10-28 15:45:46.317  4562  4644 I bt_hci  : epilog_finished_callback
,10-28 15:45:46.317  4954  4954 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-28 15:45:46.318   930  3012 D wifi    : In wifi stop Hal
10-28 15:45:46.318   930  3012 D wifi    : halHandle = 0x7f6784ee40, mVM = 0x7f83ecd140, mCls = 0x100a06
10-28 15:45:46.318   930  3472 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-28 15:45:46.318   930  3472 D WifiHAL : Got a signal to exit!!!
10-28 15:45:46.318   930  3472 I WifiHAL : Exit wifi_event_loop
10-28 15:45:46.319   930  3012 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-28 15:45:46.319   930  3012 E WifiHAL : Event processing terminated
10-28 15:45:46.320   930  3012 D wifi    : In wifi cleaned up handler
10-28 15:45:46.320   930  3012 I WifiHAL : Internal cleanup completed
10-28 15:45:46.321  4562  4640 I bt_hci_h4: hal_close
10-28 15:45:46.321  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:46.321  4562  4640 I bt_userial_vendor: device fd = 54 close
,10-28 15:45:46.322  4091  4217 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-28 15:45:46.323  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:46.324  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:46.343   930  3472 D wifi    : set interface wlan0 flags (DOWN)
,10-28 15:45:46.344   930  3012 D WifiNative-HAL: HAL event thread stopped successfully
,10-28 15:45:46.427  5706  5706 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.File.exists(File.java:361)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:45:46.427  5706  5706 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:45:46.427  5706  5706 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:45:46.427  5706  5706 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.e.b(PG:170)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:45:46.427  5706  5706 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.k.d(PG:583)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.e.b(PG:170)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:45:46.427  5706  5706 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.io.File.exists(File.java:361)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:45:46.427  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:45:46.428  5706  5706 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at java.io.File.exists(File.java:361)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:45:46.428  5706  5706 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:45:46.428  5706  5706 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:45:46.431  4562  4637 D bt_stack_manager: event_shut_down_stack finished.
10-28 15:45:46.432  4562  4636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-28 15:45:46.434  4562  4636 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-28 15:45:46.434  4562  4562 D BtGatt.DebugUtils: handleDebugAction() action=null
10-28 15:45:46.434  4562  4562 D BtGatt.GattService: Received stop request...Stopping profile...
10-28 15:45:46.434  4562  4562 D BtGatt.GattService: stop()
10-28 15:45:46.434  4562  4562 D BtGatt.AdvertiseManager: advertise clients cleared
10-28 15:45:46.434  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-28 15:45:46.436  4562  4562 V BluetoothAdapterState: isTurningOff()=false
10-28 15:45:46.436  4562  4562 V BluetoothAdapterState: isTurningOn()=false
10-28 15:45:46.436  4562  4562 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:45:46.437  4562  4562 V BluetoothAdapterState: isBleTurningOff()=true
10-28 15:45:46.437  4562  4636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-28 15:45:46.437  4562  4636 D BluetoothAdapterProperties: Setting state to 10
10-28 15:45:46.437  4562  4636 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-28 15:45:46.438   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-28 15:45:46.438  4562  4636 I BluetoothAdapterState: Entering OffState
10-28 15:45:46.440  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-28 15:45:46.447  4562  4562 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-28 15:45:46.447  4562  4562 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-28 15:45:46.449  4562  4562 I BluetoothServiceJni: cleanupNative: return from cleanup
10-28 15:45:46.450  4562  4637 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-28 15:45:46.451  3882  3882 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-28 15:45:46.455  3882  3882 D SystemUpdateService: onCreate
10-28 15:45:46.460  3882  3882 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-28 15:45:46.470  4562  4637 D bt_stack_manager: event_clean_up_stack finished.
10-28 15:45:46.471  3882  3882 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-28 15:45:46.475  3882  5403 I iu.UploadsManager: num queued entries: 0
10-28 15:45:46.480  5675  5675 D DockEventReceiver: finishStartingService: stopping service
10-28 15:45:46.493  4562  4562 I art     : System.exit called, status: 0
10-28 15:45:46.493  4562  4562 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-28 15:45:46.504  3882  3882 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-28 15:45:46.506  3882  3882 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-28 15:45:46.508  5406  5406 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-28 15:45:46.511  5406  5406 D SprintDMHelper: simOperator: 
,10-28 15:45:46.512  5406  5406 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-28 15:45:46.522  3882  5403 I iu.UploadsManager: num updated entries: 0
,10-28 15:45:46.523  3882  5740 I SystemUpdateService: active receiver: enabled
,10-28 15:45:46.527  3882  5403 I iu.SyncManager: NEXT; no task
,10-28 15:45:46.530  4954  5742 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-28 15:45:46.532  3882  5740 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-28 15:45:46.534  3882  5740 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-28 15:45:46.534  3882  5740 I SystemUpdateService: now status is 0 (complete)
,10-28 15:45:46.534  3882  5740 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-28 15:45:46.534  3882  5740 I SystemUpdateService: file has been verified
10-28 15:45:46.534  3882  5740 I SystemUpdateService: OTA package size = 21989297
,10-28 15:45:46.537   930  3692 I ActivityManager: Start proc 5743:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-28 15:45:46.540   930  3179 I ActivityManager: Process com.android.bluetooth (pid 4562) has died
,10-28 15:45:46.546   930   947 D Tethering: InitialState.processMessage what=4
,10-28 15:45:46.551   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-28 15:45:46.574  3882  5740 I SystemUpdateService: showing system update notification
,10-28 15:45:46.583  5743  5743 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-28 15:45:46.591   930  3692 I ActivityManager: Killing 5259:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-28 15:45:46.672  3882  3882 D SystemUpdateService: onDestroy
,10-28 15:45:46.678   930  3838 I ActivityManager: Killing 4650:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-28 15:45:46.767  5706  5727 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-28 15:45:46.775   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e7a22ec:true
,10-28 15:45:47.779   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:48.780   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:49.781   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:50.782   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:51.060   930  3407 D WifiService: setWifiEnabled: true pid=5611, uid=10077
,10-28 15:45:51.061   930  3407 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 15:45:51.067   507   923 D SoftapController: Softap fwReload - Ok
,10-28 15:45:51.072   507   923 D CommandListener: Setting iface cfg
,10-28 15:45:51.072   507   923 D CommandListener: Trying to bring down wlan0
10-28 15:45:51.073   507   923 D CommandListener: Clearing all IP addresses on wlan0
,10-28 15:45:51.079   930  3012 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-28 15:45:51.641   930  3012 D wifi    : set interface wlan0 flags (UP)
,10-28 15:45:51.643   930  3012 I WifiHAL : Initializing wifi
,10-28 15:45:51.643   930  3012 I WifiHAL : Creating socket
10-28 15:45:51.644   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-28 15:45:51.647   930  3012 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-28 15:45:51.648   930  3012 D wifi    : Did set static halHandle = 0x7f6784ee40
,10-28 15:45:51.648   930  3012 D wifi    : halHandle = 0x7f6784ee40, mVM = 0x7f83ecd140, mCls = 0x10191e
,10-28 15:45:51.648   930  3012 D wifi    : array field set
10-28 15:45:51.649   930  3012 I WifiNative-HAL: interface[0] = wlan0
10-28 15:45:51.650   930  5761 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547197611584
10-28 15:45:51.650   930  5761 D wifi    : waitForHalEvents called, vm = 0x7f83ecd140, obj = 0x10191e, env = 0x7f68d32dc0
,10-28 15:45:51.727  5762  5762 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-28 15:45:51.739  5762  5762 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-28 15:45:51.751  5762  5762 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-28 15:45:51.751  5762  5762 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-28 15:45:51.754   930  3012 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-28 15:45:51.758  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:45:51.761  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:51.763  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:51.770   930  3012 D WifiConfigStore: Loading config and enabling all networks 
,10-28 15:45:51.772  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:51.772  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:51.772  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:51.772  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:51.772  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:51.772  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:51.772  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:51.772  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:51.772  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:51.772  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:51.772  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:51.774  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 15:45:51.775  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:51.775  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:51.775  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:51.775  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:51.775  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:51.775  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:51.775  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:51.775  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:51.775  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:51.775  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:51.776  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:51.776  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:51.776  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:51.776  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:51.776  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:51.776  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:51.776  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:51.776  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:51.776  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:51.776  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:51.776  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-28 15:45:51.779   930  3012 D WifiConfigStore: loaded 0 passpoint configs
10-28 15:45:51.779   930  3012 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-28 15:45:51.779   930  3012 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-28 15:45:51.780   930  3012 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-28 15:45:51.781   930  3012 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-28 15:45:51.781   930  3012 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-28 15:45:51.781   930  3012 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-28 15:45:51.781   930  3012 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-28 15:45:51.783   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:45:51.784   930  3012 D WifiNative-HAL: Setting external_sim to 1
,10-28 15:45:51.784  4954  4954 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-28 15:45:51.784   930  3012 D wifi    : setting dfs flag to true, 0x7f6887b660
10-28 15:45:51.785   930  3012 D WifiStateMachine: Setting OUI to DA-A1-19
10-28 15:45:51.785   930  3012 D wifi    : setting scan oui 0x7f6887b660
10-28 15:45:51.785   930  3012 D WifiHAL : Sending mac address OUI
,10-28 15:45:51.789   930  3012 E native  : do suspend false
,10-28 15:45:51.797   930  3012 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-28 15:45:51.797   930   930 D RttService: SCAN_AVAILABLE : 3
10-28 15:45:51.797   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-28 15:45:51.797   930  3079 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-28 15:45:51.798   507   923 D CommandListener: Setting iface cfg
,10-28 15:45:51.802   930  3000 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
,10-28 15:45:51.802   930  3000 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-28 15:45:51.810   930  3000 D WifiNative-HAL: p2pGetDeviceAddress
10-28 15:45:51.810   930  3000 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-28 15:45:51.816   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=192540 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-28 15:45:52.783   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-28 15:45:54.867  5762  5762 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-28 15:45:54.872  5762  5762 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-28 15:45:54.879  5762  5762 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-28 15:45:54.930   930  3012 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-28 15:45:54.931   930  3012 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-28 15:45:54.931   930  3012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-28 15:45:54.944   930  3012 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-28 15:45:54.980   930  3012 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-28 15:45:54.983  5762  5762 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-28 15:45:55.401  5762  5762 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-28 15:45:55.435  5762  5762 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-28 15:45:55.437  5762  5762 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-28 15:45:55.446   930  3012 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-28 15:45:55.447   930  3012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-28 15:45:55.447   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-28 15:45:55.463   930  3012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-28 15:45:55.476   507   923 D CommandListener: Setting iface cfg
,10-28 15:45:55.482   930  3012 D WifiStateMachine: Start Dhcp Watchdog 2
,10-28 15:45:55.488   930  5768 D DhcpClient: Receive thread started
,10-28 15:45:55.492   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-28 15:45:55.492   930  3012 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-28 15:45:55.493   930  3014 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-28 15:45:55.573   930  3012 E native  : do suspend false
,10-28 15:45:55.586   930  5767 D DhcpClient: Broadcasting DHCPDISCOVER
,10-28 15:45:55.607   930  5768 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172643, domain null
,10-28 15:45:55.608   930  5767 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172643 seconds
10-28 15:45:55.609   930  5767 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-28 15:45:55.623   930  5768 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-28 15:45:55.623   930  5767 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-28 15:45:55.626   507   923 D CommandListener: Setting iface cfg
,10-28 15:45:55.629   930  3012 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-28 15:45:55.631   930  5767 D DhcpClient: Scheduling renewal in 86399s
,10-28 15:45:55.641   930  3012 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-28 15:45:55.641   930  3012 D WifiConfigStore: No blacklist allowed without epno enabled
,10-28 15:45:55.643   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-28 15:45:55.644   930  3014 D ConnectivityService: Adding iface wlan0 to network 101
,10-28 15:45:55.646   930  3012 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-28 15:45:55.684   930  3014 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-28 15:45:55.684   930  3014 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-28 15:45:55.686   930  3014 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-28 15:45:55.688   930  3014 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-28 15:45:55.690   930  3014 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-28 15:45:55.697   930  3014 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-28 15:45:55.700   930  3014 D ConnectivityService: scheduleUnvalidatedPrompt 101
10-28 15:45:55.701   930  3014 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-28 15:45:55.701   930  3014 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,10-28 15:45:55.701   930  3014 D ConnectivityService:    accepting network in place of null
10-28 15:45:55.701   930  3014 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-28 15:45:55.701   930  3012 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-28 15:45:55.701   930  3012 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-28 15:45:55.714   930  5766 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196438, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-28 15:45:55.722   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 15:45:55.741   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 15:45:55.744   930  3014 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-28 15:45:55.744   930  3014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-28 15:45:55.744  3753  3905 W QCNEJ   : |CORE| network available: 101
,10-28 15:45:55.745   930  3014 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-28 15:45:55.749   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-28 15:45:55.751  3753  3905 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-28 15:45:55.753  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:55.753  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:55.753  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:55.753  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:55.753  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:55.753  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:55.753  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:55.753  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:55.753  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:45:55.753  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:55.753  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:55.753  4979  5019 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-28 15:45:55.754  4979  5019 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-28 15:45:55.754  4979  5019 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-28 15:45:55.754  4979  5019 E SarControlService: no key has been found,reset the power
10-28 15:45:55.754  4979  5050 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-28 15:45:55.754  4979  5050 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-28 15:45:55.754  4979  5050 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-28 15:45:55.754  3753  3905 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-28 15:45:55.754  3753  3905 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-28 15:45:55.755  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 15:45:55.755  5033  5033 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-28 15:45:55.755  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 15:45:55.756  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:55.756  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:55.756  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:55.756  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:55.756  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:55.756  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:55.756  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:55.756  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:45:55.756  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:55.756  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:55.758  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:55.758  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:55.758  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:55.758  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:55.758  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:55.758  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:55.758  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:55.758  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:45:55.758  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:45:55.758  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:55.758  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:45:55.759  4979  5050 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-28 15:45:55.759  4979  5050 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-28 15:45:55.759  4979  5050 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,10-28 15:45:55.762  3882  3882 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-28 15:45:55.763  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-28 15:45:55.766  5033  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c0f0723 HexData = [00000000ec03000000000000ffffffff]
,10-28 15:45:55.766  5033  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 15:45:55.766  5033  5057 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-28 15:45:55.767  5033  5033 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-28 15:45:55.768  3882  3882 D SystemUpdateService: onCreate
,10-28 15:45:55.770  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-28 15:45:55.770  4979  4990 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-28 15:45:55.770  5033  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c0f0723 HexData = [00000000ed03000000000000ffffffff]
,10-28 15:45:55.770  5033  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 15:45:55.771  5033  5057 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-28 15:45:55.771  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-28 15:45:55.771  4979  4989 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-28 15:45:55.774  3882  3882 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-28 15:45:55.781   930  5765 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=74.125.140.113,2a00:1450:400c:c08::64
,10-28 15:45:55.787  3882  3882 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-28 15:45:55.794  3882  5403 I iu.UploadsManager: num queued entries: 0
,10-28 15:45:55.795  3882  5403 I iu.UploadsManager: num updated entries: 0
10-28 15:45:55.795  3882  5403 I iu.SyncManager: NEXT; no task
,10-28 15:45:55.797  3882  3882 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-28 15:45:55.798  3882  3882 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-28 15:45:55.800  5406  5406 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-28 15:45:55.801  3882  5780 I SystemUpdateService: active receiver: enabled
,10-28 15:45:55.804  5406  5406 D SprintDMHelper: simOperator: 
10-28 15:45:55.804  5406  5406 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-28 15:45:55.834  3882  5780 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-28 15:45:55.841  3882  5780 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-28 15:45:55.841  3882  5780 I SystemUpdateService: now status is 0 (complete)
10-28 15:45:55.841  3882  5780 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-28 15:45:55.841  3882  5780 I SystemUpdateService: file has been verified
10-28 15:45:55.841  3882  5780 I SystemUpdateService: OTA package size = 21989297
,10-28 15:45:55.849  3882  5780 I SystemUpdateService: showing system update notification
,10-28 15:45:55.854   930  5765 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 28 Oct 2016 19:45:55 GMT], X-Android-Received-Millis=[1477683955854], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477683955819]}
,10-28 15:45:55.855   930  3014 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-28 15:45:55.855   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-28 15:45:55.855   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-28 15:45:55.856   930  3014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-28 15:45:55.862  3882  3882 D SystemUpdateService: onDestroy
,10-28 15:45:55.928  4954  5784 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-28 15:45:56.065   930   941 D WifiService: setWifiEnabled: false pid=5611, uid=10077
,10-28 15:45:56.065   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 15:45:56.068   930  3012 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-28 15:45:56.068   930  3012 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-28 15:45:56.069   930  3012 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-28 15:45:56.069   930  3012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-28 15:45:56.087   930  5767 D DhcpClient: Clearing IP address
,10-28 15:45:56.088   507   923 D CommandListener: Clearing all IP addresses on wlan0
,10-28 15:45:56.093   507   923 D CommandListener: Setting iface cfg
,10-28 15:45:56.099  3571  5790 V NativeCrypto: Read error: ssl=0x7f68bb9e00: I/O error during system call, Connection timed out
,10-28 15:45:56.101  3571  5790 V NativeCrypto: SSL shutdown failed: ssl=0x7f68bb9e00: I/O error during system call, Broken pipe
,10-28 15:45:56.105   930  3827 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,10-28 15:45:56.106   930  5765 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-28 15:45:56.107   930  5765 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=74.125.140.113,2a00:1450:400c:c08::64
10-28 15:45:56.111   930  5768 D DhcpClient: Receive thread stopped
10-28 15:45:56.113   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-28 15:45:56.113   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-28 15:45:56.116   533   533 E Parcel  : Reading a NULL string not supported here.
10-28 15:45:56.118   930  3014 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-28 15:45:56.120  3753  3905 W QCNEJ   : |CORE| network lost: 101
,10-28 15:45:56.121  3753  3905 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-28 15:45:56.121   930   930 D RttService: SCAN_AVAILABLE : 1
10-28 15:45:56.122   930  3079 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-28 15:45:56.123   930  5765 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400c:c08::64 (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
10-28 15:45:56.124   930  3012 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-28 15:45:56.127   930  3012 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-28 15:45:56.142   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 15:45:56.163   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 15:45:56.163   930  3014 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-28 15:45:56.163   507   923 D CommandListener: Clearing all IP addresses on wlan0
10-28 15:45:56.163   930  3014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-28 15:45:56.165   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-28 15:45:56.168  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:56.168  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:56.168  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:56.168  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:56.168  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:56.168  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:56.168  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:56.168  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:56.168  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:56.168  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:56.168  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:56.169  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 15:45:56.169  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:56.169  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:56.169  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:56.169  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:56.169  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:56.169  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:56.169  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:56.169  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:56.169  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 15:45:56.169  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:56.171   930  3012 D DhcpClient: doQuit
10-28 15:45:56.171   930  3012 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-28 15:45:56.171   930  5767 D DhcpClient: onQuitting
10-28 15:45:56.172  5762  5762 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-28 15:45:56.172  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:56.172  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:56.172  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:56.172  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:56.172  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:45:56.172  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:56.172  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:56.172  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:56.172  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 15:45:56.172  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:56.172  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:56.174  3882  3882 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-28 15:45:56.175  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:56.175  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:56.175  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:56.175  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:56.175  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:45:56.175  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:56.175  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:56.175  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:56.175  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 15:45:56.175  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:56.175  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:56.177  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 15:45:56.177  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:56.177  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:56.177  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:56.177  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:45:56.177  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:56.177  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:56.177  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:56.177  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:45:56.177  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:56.177  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:56.178  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:45:56.178  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:45:56.178  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:45:56.178  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:45:56.178  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:45:56.178  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:45:56.178  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:45:56.178  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:45:56.178  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 15:45:56.178  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 15:45:56.178  4979  5019 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-28 15:45:56.178  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:45:56.178  4979  5019 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-28 15:45:56.179  4979  5019 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-28 15:45:56.179  4979  5019 E SarControlService: no key has been found,reset the power
10-28 15:45:56.179  4979  5050 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-28 15:45:56.179  4979  5050 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-28 15:45:56.179  4979  5050 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-28 15:45:56.180  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 15:45:56.180  5033  5033 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-28 15:45:56.181  4979  5050 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-28 15:45:56.181  4979  5050 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-28 15:45:56.181  4979  5050 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-28 15:45:56.181  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 15:45:56.181  5033  5033 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-28 15:45:56.184  3882  3882 D SystemUpdateService: onCreate
,10-28 15:45:56.186  5033  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c0f0723 HexData = [00000000ee03000000000000ffffffff]
,10-28 15:45:56.186  5033  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-28 15:45:56.186  5033  5057 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-28 15:45:56.187  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-28 15:45:56.187  4979  4989 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-28 15:45:56.187  5033  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c0f0723 HexData = [00000000ef03000000000000ffffffff]
,10-28 15:45:56.187  5033  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 15:45:56.187  5033  5057 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-28 15:45:56.188  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-28 15:45:56.188  4979  4990 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-28 15:45:56.190  3882  3882 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-28 15:45:56.195  5762  5762 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-28 15:45:56.199  3882  3882 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-28 15:45:56.200  5762  5762 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-28 15:45:56.205  3882  5403 I iu.UploadsManager: num queued entries: 0
,10-28 15:45:56.207  3882  5801 I SystemUpdateService: active receiver: enabled
,10-28 15:45:56.209  3882  3882 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-28 15:45:56.211  3882  3882 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-28 15:45:56.213  5406  5406 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-28 15:45:56.217  5406  5406 D SprintDMHelper: simOperator: 
10-28 15:45:56.217  5406  5406 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-28 15:45:56.223   507   923 E Netd    : netlink response contains error (No such file or directory)
,10-28 15:45:56.224   930  3014 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-28 15:45:56.224   930  3014 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-28 15:45:56.229  4954  5806 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-28 15:45:56.232  5762  5762 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-28 15:45:56.236  3882  5403 I iu.UploadsManager: num updated entries: 0
,10-28 15:45:56.244  3882  5403 I iu.SyncManager: NEXT; no task
,10-28 15:45:56.245  3882  5801 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-28 15:45:56.249  5762  5762 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-28 15:45:56.250  3882  5801 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-28 15:45:56.250  3882  5801 I SystemUpdateService: now status is 0 (complete)
10-28 15:45:56.250  3882  5801 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-28 15:45:56.250  3882  5801 I SystemUpdateService: file has been verified
10-28 15:45:56.250  3882  5801 I SystemUpdateService: OTA package size = 21989297
,10-28 15:45:56.256  3882  5801 I SystemUpdateService: showing system update notification
,10-28 15:45:56.265  3882  3882 D SystemUpdateService: onDestroy
,10-28 15:45:56.354   930  3012 D wifi    : In wifi stop Hal
,10-28 15:45:56.354   930  3012 D wifi    : halHandle = 0x7f6784ee40, mVM = 0x7f83ecd140, mCls = 0x10191e
10-28 15:45:56.355  4954  4954 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-28 15:45:56.356   930  5761 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-28 15:45:56.356  4091  4217 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-28 15:45:56.356   930  5761 D WifiHAL : Got a signal to exit!!!
10-28 15:45:56.356   930  5761 I WifiHAL : Exit wifi_event_loop
10-28 15:45:56.357   930  3012 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-28 15:45:56.358   930  3012 E WifiHAL : Event processing terminated
10-28 15:45:56.358   930  3012 D wifi    : In wifi cleaned up handler
10-28 15:45:56.358  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:56.358   930  3012 I WifiHAL : Internal cleanup completed
10-28 15:45:56.360  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:56.361  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:45:56.382   930  5761 D wifi    : set interface wlan0 flags (DOWN)
,10-28 15:45:56.383   930  3012 D WifiNative-HAL: HAL event thread stopped successfully
,10-28 15:45:56.588   930   947 D Tethering: InitialState.processMessage what=4
,10-28 15:45:56.595   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-28 15:45:56.746   930  3014 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-28 15:46:01.106   930   947 I ActivityManager: Start proc 5808:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-28 15:46:01.212  5808  5808 D AdapterServiceConfig: Adding HeadsetService
,10-28 15:46:01.212  5808  5808 D AdapterServiceConfig: Adding A2dpService
10-28 15:46:01.213  5808  5808 D AdapterServiceConfig: Adding HidService
10-28 15:46:01.213  5808  5808 D AdapterServiceConfig: Adding HealthService
10-28 15:46:01.213  5808  5808 D AdapterServiceConfig: Adding PanService
10-28 15:46:01.213  5808  5808 D AdapterServiceConfig: Adding GattService
10-28 15:46:01.213  5808  5808 D AdapterServiceConfig: Adding BluetoothMapService
,10-28 15:46:01.213  5808  5808 D AdapterServiceConfig: Adding SapService
,10-28 15:46:01.227   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ab8bf3:true
,10-28 15:46:01.228  5808  5808 D BluetoothAdapterState: make() - Creating AdapterState
,10-28 15:46:01.231  5808  5808 I bt_bluedroid: init
,10-28 15:46:01.231  5808  5820 I BluetoothAdapterState: Entering OffState
,10-28 15:46:01.233  5808  5821 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-28 15:46:01.233  5808  5821 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-28 15:46:01.233  5808  5821 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-28 15:46:01.233  5808  5821 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-28 15:46:01.234  5808  5808 I bt_bluedroid: get_profile_interface socket
,10-28 15:46:01.235  5808  5824 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-28 15:46:01.236  5808  5808 I bt_bluedroid: get_profile_interface sdp
10-28 15:46:01.237  5808  5824 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-28 15:46:01.240  5808  5819 I bt_bluedroid: config_hci_snoop_log
,10-28 15:46:01.241   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-28 15:46:01.245  5808  5820 D BluetoothAdapterState: Current state: OFF, message: 0
10-28 15:46:01.245  5808  5820 D BluetoothAdapterProperties: Setting state to 14
,10-28 15:46:01.245  5808  5820 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-28 15:46:01.247  5808  5820 D BluetoothBondStateMachine: make
,10-28 15:46:01.248  5808  5825 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-28 15:46:01.251  5808  5820 I BluetoothAdapterState: Entering PendingCommandState
,10-28 15:46:01.252  5808  5808 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
10-28 15:46:01.254  5808  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:01.255  5808  5808 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-28 15:46:01.256  5808  5808 D BtGatt.GattService: Received start request. Starting profile...
10-28 15:46:01.256  5808  5808 D BtGatt.GattService: start()
,10-28 15:46:01.257  5808  5808 I bt_bluedroid: get_profile_interface gatt
10-28 15:46:01.257  5808  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:01.258  5808  5808 D BtGatt.AdvertiseManager: advertise manager created
,10-28 15:46:01.262  5808  5808 V BluetoothAdapterState: isTurningOff()=false
,10-28 15:46:01.262  5808  5808 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:01.262  5808  5808 V BluetoothAdapterState: isBleTurningOn()=true
10-28 15:46:01.262  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
,10-28 15:46:01.263  5808  5820 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-28 15:46:01.264  5808  5820 I bt_bluedroid: bt_bluedroid
,10-28 15:46:01.264  5808  5821 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-28 15:46:01.264  5808  5821 I bt_hci  : start_up
,10-28 15:46:01.269  5808  5821 I bt_vendor: alloc value 0xf3f09871
10-28 15:46:01.270  5808  5821 I bt_vendor: init
10-28 15:46:01.270  5808  5821 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-28 15:46:01.270  5808  5821 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-28 15:46:01.382  5808  5821 D bt_hci  : start_up starting async portion
10-28 15:46:01.383  5808  5828 I bt_hci  : event_finish_startup
,10-28 15:46:01.383  5808  5828 I bt_hci_h4: hal_open
10-28 15:46:01.383  5808  5828 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-28 15:46:01.382  5829  5829 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-28 15:46:01.386  5808  5828 I bt_userial_vendor: device fd = 54 open
,10-28 15:46:01.400  5808  5828 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-28 15:46:01.403  5808  5828 D bt_hwcfg: Chipset BCM4358A3
,10-28 15:46:01.403  5808  5828 D bt_hwcfg: Target name = [BCM4358A3]
10-28 15:46:01.403  5808  5828 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-28 15:46:01.807  5808  5828 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-28 15:46:01.807  5808  5828 D bt_hwcfg: Settlement delay -- 100 ms
,10-28 15:46:01.807  5808  5828 I bt_hwcfg: Setting fw settlement delay to 100 
,10-28 15:46:01.942  5808  5828 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-28 15:46:01.942  5808  5828 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-28 15:46:01.944  5808  5828 I bt_hwcfg: vendor lib fwcfg completed
,10-28 15:46:01.944  5808  5828 I bt_vendor: firmware callback
,10-28 15:46:01.945  5808  5828 I bt_hci  : firmware_config_callback
,10-28 15:46:01.954  5808  5831 I bt_btu  : btu_task pending for preload complete event
,10-28 15:46:01.954  5808  5831 I bt_btu_task: Bluetooth chip preload is complete
,10-28 15:46:01.955  5808  5831 I bt_btu  : btu_task received preload complete event
,10-28 15:46:01.961  5808  5831 I         : BTE_InitTraceLevels -- TRC_HCI
,10-28 15:46:01.961  5808  5831 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-28 15:46:01.961  5808  5831 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-28 15:46:01.962  5808  5831 I         : BTE_InitTraceLevels -- TRC_AVDT
10-28 15:46:01.962  5808  5831 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-28 15:46:01.962  5808  5831 I         : BTE_InitTraceLevels -- TRC_A2D
10-28 15:46:01.962  5808  5831 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-28 15:46:01.962  5808  5831 I         : BTE_InitTraceLevels -- TRC_BTM
10-28 15:46:01.962  5808  5831 I         : BTE_InitTraceLevels -- TRC_GAP
,10-28 15:46:01.962  5808  5831 I         : BTE_InitTraceLevels -- TRC_PAN
10-28 15:46:01.962  5808  5831 I         : BTE_InitTraceLevels -- TRC_SDP
,10-28 15:46:01.963  5808  5831 I         : BTE_InitTraceLevels -- TRC_GATT
,10-28 15:46:01.963  5808  5831 I         : BTE_InitTraceLevels -- TRC_SMP
,10-28 15:46:01.963  5808  5831 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-28 15:46:01.963  5808  5831 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-28 15:46:02.047  5808  5831 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e87549
10-28 15:46:02.047  5808  5831 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e87549 
,10-28 15:46:02.058  5808  5824 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-28 15:46:02.060  5808  5824 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-28 15:46:02.060  5808  5824 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-28 15:46:02.064  5808  5824 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-28 15:46:02.067  5808  5824 D BluetoothAdapterProperties: Scan Mode:20
,10-28 15:46:02.068  5808  5824 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-28 15:46:02.068  5808  5824 D bt_hci  : do_postload posting postload work item
10-28 15:46:02.069  5808  5828 I bt_hci  : event_postload
,10-28 15:46:02.069  5808  5828 I bt_vendor: sco_config_cb
,10-28 15:46:02.069  5808  5828 I bt_hci  : sco_config_callback postload finished.
10-28 15:46:02.072  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:02.074  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:02.076  5808  5824 D bt_bte_conf: Device ID record 1 : primary
10-28 15:46:02.076  5808  5824 D bt_bte_conf:   vendorId            = 000f
10-28 15:46:02.076  5808  5824 D bt_bte_conf:   vendorIdSource      = 0001
10-28 15:46:02.076  5808  5824 D bt_bte_conf:   product             = 1200
10-28 15:46:02.076  5808  5824 D bt_bte_conf:   version             = 1436
10-28 15:46:02.076  5808  5824 D bt_bte_conf:   clientExecutableURL = 
10-28 15:46:02.076  5808  5824 D bt_bte_conf:   serviceDescription  = 
10-28 15:46:02.076  5808  5824 D bt_bte_conf:   documentationURL    = 
10-28 15:46:02.076  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:02.077  5808  5824 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-28 15:46:02.077  5808  5821 D bt_stack_manager: event_start_up_stack finished
10-28 15:46:02.078  5808  5820 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-28 15:46:02.078  5808  5828 I bt_vendor: low_power_mode_cb
10-28 15:46:02.078  5808  5820 D BluetoothAdapterProperties: Setting state to 15
10-28 15:46:02.079  5808  5820 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-28 15:46:02.079  5808  5820 I BluetoothAdapterState: Entering BleOnState
,10-28 15:46:02.085  5808  5820 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-28 15:46:02.085  5808  5820 D BluetoothAdapterProperties: Setting state to 11
10-28 15:46:02.085  5808  5820 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-28 15:46:02.092  5808  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
,10-28 15:46:02.093  5808  5808 D HeadsetService: Received start request. Starting profile...
,10-28 15:46:02.097  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:02.098  5808  5808 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-28 15:46:02.098  5808  5808 D HeadsetStateMachine: make
10-28 15:46:02.101  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:02.103  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:02.108  5808  5808 D HeadsetStateMachine: max_hf_connections = 1
,10-28 15:46:02.108  5808  5808 I bt_bluedroid: get_profile_interface handsfree
10-28 15:46:02.109  5808  5820 I BluetoothAdapterState: Entering PendingCommandState
10-28 15:46:02.109  5808  5824 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-28 15:46:02.112  5808  5824 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-28 15:46:02.113  5808  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
,10-28 15:46:02.113  5808  5808 D A2dpService: Received start request. Starting profile...
10-28 15:46:02.114  5808  5808 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-28 15:46:02.114  5808  5808 I bt_bluedroid: get_profile_interface avrcp
,10-28 15:46:02.121  5808  5808 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-28 15:46:02.121  5808  5808 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-28 15:46:02.121  5808  5808 D A2dpStateMachine: make
,10-28 15:46:02.122  5808  5808 I bt_bluedroid: get_profile_interface a2dp
,10-28 15:46:02.123  5808  5824 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-28 15:46:02.124  5808  5840 D A2dpStateMachine: Enter Disconnected: -2
,10-28 15:46:02.124  5808  5808 I BluetoothHidServiceJni: classInitNative: succeeds
10-28 15:46:02.125  5808  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
,10-28 15:46:02.126  5675  5675 D BluetoothInputDevice: Proxy object connected
,10-28 15:46:02.127  5808  5808 D HidService: Received start request. Starting profile...
10-28 15:46:02.127  5808  5808 I bt_bluedroid: get_profile_interface hidhost
,10-28 15:46:02.127  5808  5808 D HidService: setHidService(): set to: null
10-28 15:46:02.127  5808  5824 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e6856d
10-28 15:46:02.127  5675  5675 D HidProfile: Bluetooth service connected
10-28 15:46:02.127  5808  5824 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-28 15:46:02.129  5808  5808 I BluetoothHealthServiceJni: classInitNative: succeeds
10-28 15:46:02.130  5808  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:02.130  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-28 15:46:02.130  5808  5808 D HealthService: Received start request. Starting profile...
,10-28 15:46:02.132  5808  5808 I bt_bluedroid: get_profile_interface health
,10-28 15:46:02.133  5808  5808 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-28 15:46:02.134  5808  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
,10-28 15:46:02.135  5675  5675 D BluetoothPan: BluetoothPAN Proxy object connected
10-28 15:46:02.136  5675  5675 D PanProfile: Bluetooth service connected
,10-28 15:46:02.136  5808  5808 D PanService: Received start request. Starting profile...
10-28 15:46:02.137  5808  5808 D BluetoothPanServiceJni: initializeNative(L110): pan
,10-28 15:46:02.137  5808  5808 I bt_bluedroid: get_profile_interface pan
10-28 15:46:02.137  5808  5824 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-28 15:46:02.139  5808  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
,10-28 15:46:02.140  5675  5675 D BluetoothMap: Proxy object connected
,10-28 15:46:02.141  5675  5675 D MapProfile: Bluetooth service connected
10-28 15:46:02.141  5675  5675 D BluetoothMap: getConnectedDevices()
10-28 15:46:02.142  5808  5808 D BluetoothMapService: Received start request. Starting profile...
10-28 15:46:02.142  5808  5808 D BluetoothMapService: start()
,10-28 15:46:02.145  5808  5808 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-28 15:46:02.145  5808  5808 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-28 15:46:02.146  5808  5808 D BluetoothMapAppObserver: createReceiver()
,10-28 15:46:02.147  5808  5808 D BluetoothMapAppObserver: initObservers()
,10-28 15:46:02.147  5808  5808 D BluetoothMapAppObserver: getEnabledAccountItems()
10-28 15:46:02.154  5808  5808 V SapService: SapBinder()
10-28 15:46:02.154  5808  5808 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:02.154  5808  5808 D SapService: Received start request. Starting profile...
10-28 15:46:02.154  5808  5808 V SapService: start()
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:02.156  5808  5837 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:02.156  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:02.157  5808  5808 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:02.158  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:02.158  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:02.158  5808  5808 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:02.158  5808  5808 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:02.158  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:02.158  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:02.159  5808  5820 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-28 15:46:02.159  5808  5820 D BluetoothAdapterProperties: ScanMode =  20
10-28 15:46:02.159  5808  5820 D BluetoothAdapterProperties: State =  11
10-28 15:46:02.160  5675  5675 D BluetoothMap: Bluetooth is Not enabled
10-28 15:46:02.160  5808  5824 D BluetoothAdapterProperties: Scan Mode:21
,10-28 15:46:02.161  5808  5820 D BluetoothAdapterProperties: Setting state to 12
10-28 15:46:02.161  5808  5820 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,10-28 15:46:02.161  5808  5824 D BluetoothAdapterProperties: Discoverable Timeout:120
10-28 15:46:02.161  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-28 15:46:02.161  5675  5686 D BluetoothPan: onBluetoothStateChange on: true
10-28 15:46:02.161  5808  5820 I BluetoothAdapterState: Entering OnState
10-28 15:46:02.162  5675  5687 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-28 15:46:02.162   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 15:46:02.162  5675  5686 D BluetoothPbap: onBluetoothStateChange: up=true
10-28 15:46:02.163  3127  3144 D BluetoothMap: onBluetoothStateChange: up=true
,10-28 15:46:02.165  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:02.165  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:02.165  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:02.165  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:46:02.165  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:02.165  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:02.165  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:02.165  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:46:02.165  3127  3127 D BluetoothMap: Proxy object connected
10-28 15:46:02.165  3127  3127 D MapProfile: Bluetooth service connected
10-28 15:46:02.165  5675  5687 D BluetoothMap: onBluetoothStateChange: up=true
10-28 15:46:02.165  3127  3127 D BluetoothMap: getConnectedDevices()
10-28 15:46:02.165   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-28 15:46:02.165   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 15:46:02.166  3127  3143 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 15:46:02.166   930   930 D BluetoothA2dp: Proxy object connected
10-28 15:46:02.167  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:46:02.168  3127  3127 D BluetoothA2dp: Proxy object connected
10-28 15:46:02.168  3127  3967 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 15:46:02.168  3127  3143 D BluetoothPan: onBluetoothStateChange on: true
10-28 15:46:02.170  3127  3127 D BluetoothPan: BluetoothPAN Proxy object connected
10-28 15:46:02.170  3127  3967 D BluetoothPbap: onBluetoothStateChange: up=true
,10-28 15:46:02.170  3127  3127 D PanProfile: Bluetooth service connected
10-28 15:46:02.171  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:02.171  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:02.171  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:02.171  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:46:02.171  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:02.171  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:02.171  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:02.171  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:46:02.172   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 15:46:02.172  3810  4000 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-28 15:46:02.172  5808  5808 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-28 15:46:02.172  3127  3143 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-28 15:46:02.173  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:46:02.173  5808  5808 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-28 15:46:02.174  5808  5808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 15:46:02.174  3127  3127 D BluetoothInputDevice: Proxy object connected
10-28 15:46:02.174  3127  3127 D HidProfile: Bluetooth service connected
10-28 15:46:02.175   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,10-28 15:46:02.178  5675  5675 D LocalBluetoothProfileManager: Adding local A2DP profile
10-28 15:46:02.179  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:02.179  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:02.179  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:02.179  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:46:02.179  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:02.179  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:02.179  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:02.179  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:46:02.179  5808  5808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 15:46:02.181  5808  5808 D ObexServerSockets: Succeed to create listening sockets 
10-28 15:46:02.181  5808  5808 D ObexServerSockets0: startAccept()
10-28 15:46:02.181  5808  5808 D ObexServerSockets0: prepareForNewConnect()
10-28 15:46:02.182  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:46:02.182  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-28 15:46:02.183  5675  5675 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-28 15:46:02.183  5808  5808 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-28 15:46:02.184  5808  5808 D BluetoothSdpJni: SDP Create record success - handle: 0
10-28 15:46:02.184  5808  5848 D ObexServerSockets0: Accepting socket connection...
10-28 15:46:02.184  5808  5808 D BluetoothMapService: onReceive
,10-28 15:46:02.184  5808  5808 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-28 15:46:02.184  5808  5808 D BluetoothMapService: STATE_ON
10-28 15:46:02.186  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:02.186  5808  5849 D ObexServerSockets0: Accepting socket connection...
,10-28 15:46:02.187  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:02.188  5808  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-28 15:46:02.189  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:02.190  5808  5850 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-28 15:46:02.190  5808  5850 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-28 15:46:02.191  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-28 15:46:02.193  5675  5675 D BluetoothA2dp: Proxy object connected
,10-28 15:46:02.197  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-28 15:46:02.206  3127  3127 D BluetoothPbap: Proxy object connected
,10-28 15:46:02.206  3127  3127 D PbapServerProfile: Bluetooth service connected
,10-28 15:46:02.211  5675  5675 D DockEventReceiver: finishStartingService: stopping service
10-28 15:46:02.212  5808  5808 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-28 15:46:02.212  5808  5808 D ObexServerSockets0: prepareForNewConnect()
10-28 15:46:02.212  5675  5675 D BluetoothPbap: Proxy object connected
10-28 15:46:02.213  5808  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 15:46:02.215  5675  5675 D PbapServerProfile: Bluetooth service connected
,10-28 15:46:02.228  5808  5858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-28 15:46:02.230  5808  5858 I BtOppRfcommListener: Accept thread started.
,10-28 15:46:02.263  3810  3826 D BluetoothHeadset: Proxy object connected
,10-28 15:46:02.263   930   930 D BluetoothHeadset: Proxy object connected
10-28 15:46:02.263  3127  3144 D BluetoothHeadset: Proxy object connected
,10-28 15:46:02.264  3127  3127 D HeadsetProfile: Bluetooth service connected
10-28 15:46:02.264   930   930 D BluetoothHeadset: Proxy object connected
10-28 15:46:02.264   930   930 D BluetoothHeadset: Proxy object connected
,10-28 15:46:02.265   930   947 D BluetoothHeadset: Proxy object connected
,10-28 15:46:02.268  3127  3143 D BluetoothHeadset: Proxy object connected
,10-28 15:46:02.269  3127  3127 D HeadsetProfile: Bluetooth service connected
,10-28 15:46:02.272   930   947 D BluetoothHeadset: Proxy object connected
,10-28 15:46:02.272  3810  3825 D BluetoothHeadset: Proxy object connected
,10-28 15:46:02.286  5675  5686 D BluetoothHeadset: Proxy object connected
,10-28 15:46:02.287  5675  5675 D HeadsetProfile: Bluetooth service connected
,10-28 15:46:03.708   930  3014 D ConnectivityService: handlePromptUnvalidated 101
,10-28 15:46:06.087  5808  5820 D BluetoothAdapterState: Current state: ON, message: 23
,10-28 15:46:06.087  5808  5820 D BluetoothAdapterProperties: Setting state to 13
,10-28 15:46:06.087  5808  5820 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-28 15:46:06.089  5808  5820 D BluetoothAdapterProperties: onBluetoothDisable()
10-28 15:46:06.090  5808  5820 I BluetoothAdapterState: Entering PendingCommandState
10-28 15:46:06.094  5808  5808 D BluetoothMapService: onReceive
10-28 15:46:06.094  5808  5808 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-28 15:46:06.094  5808  5808 D BluetoothMapService: STATE_TURNING_OFF
10-28 15:46:06.095  5808  5808 D BluetoothMapService: MAP Service closeService in
10-28 15:46:06.095  5808  5808 D BluetoothMapMasInstance0: MAP Service shutdown
10-28 15:46:06.096  5808  5808 D ObexServerSockets0: shutdown(block = true)
,10-28 15:46:06.096  5808  5848 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-28 15:46:06.101  5808  5824 D BluetoothAdapterProperties: Scan Mode:20
,10-28 15:46:06.103  5808  5820 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-28 15:46:06.104  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:46:06.104  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:06.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:06.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:06.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:46:06.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:46:06.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:06.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:06.104  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:46:06.106  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:46:06.106  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-28 15:46:06.105  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-28 15:46:06.108  5808  5808 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-28 15:46:06.108  5808  5808 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-28 15:46:06.108  5808  5849 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-28 15:46:06.109  5808  5833 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-28 15:46:06.110  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:46:06.111  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:06.111  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:06.111  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:06.111  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:46:06.111  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:46:06.111  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:06.111  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:06.111  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:46:06.111  5808  5808 I BtOppRfcommListener: stopping Accept Thread
10-28 15:46:06.112  5808  5858 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-28 15:46:06.112  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 15:46:06.112  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:46:06.112  5808  5858 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-28 15:46:06.114  5808  5808 D HeadsetService: Received stop request...Stopping profile...
10-28 15:46:06.116  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:46:06.116  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:06.116  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:06.116  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:06.116  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:46:06.116  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 15:46:06.116  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:06.116  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:06.116  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 15:46:06.116  5675  5687 D BluetoothHeadset: Proxy object disconnected
,10-28 15:46:06.116  5611  5611 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 15:46:06.117  3810  4000 D BluetoothHeadset: Proxy object disconnected
10-28 15:46:06.117  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:46:06.117   930   930 D BluetoothHeadset: Proxy object disconnected
,10-28 15:46:06.117  3127  3144 D BluetoothHeadset: Proxy object disconnected
10-28 15:46:06.117   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 15:46:06.117   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 15:46:06.119  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:06.119  5808  5808 D A2dpService: Received stop request...Stopping profile...
10-28 15:46:06.119  5808  5840 D A2dpStateMachine: Exit Disconnected: -1
10-28 15:46:06.120  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:06.120   930   930 D BluetoothA2dp: Proxy object disconnected
,10-28 15:46:06.122  5808  5808 D HidService: Received stop request...Stopping profile...
10-28 15:46:06.122  5808  5808 D HidService: Stopping Bluetooth HidService
10-28 15:46:06.122  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:06.125  5808  5808 D HealthService: Received stop request...Stopping profile...
,10-28 15:46:06.127  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-28 15:46:06.126  5675  5675 D DockEventReceiver: finishStartingService: stopping service
10-28 15:46:06.128  5808  5808 D PanService: Received stop request...Stopping profile...
10-28 15:46:06.128  5675  5675 D HeadsetProfile: Bluetooth service disconnected
10-28 15:46:06.129  5675  5675 D BluetoothA2dp: Proxy object disconnected
,10-28 15:46:06.129  5675  5675 D BluetoothInputDevice: Proxy object disconnected
10-28 15:46:06.129  5675  5675 D HidProfile: Bluetooth service disconnected
10-28 15:46:06.130  5675  5675 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-28 15:46:06.130  5675  5675 D PanProfile: Bluetooth service disconnected
,10-28 15:46:06.131  5808  5808 D BluetoothMapService: Received stop request...Stopping profile...
10-28 15:46:06.131  5808  5808 D BluetoothMapService: stop()
10-28 15:46:06.131  5808  5808 D BluetoothMapAppObserver: deinitObservers()
10-28 15:46:06.131  5808  5808 D BluetoothMapAppObserver: removeReceiver()
10-28 15:46:06.133  5808  5808 V BluetoothAdapterState: isTurningOff()=true
10-28 15:46:06.133  3127  3127 D HeadsetProfile: Bluetooth service disconnected
10-28 15:46:06.133  5808  5808 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:06.133  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
,10-28 15:46:06.133  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:06.133  3127  3127 D BluetoothA2dp: Proxy object disconnected
10-28 15:46:06.133  3127  3127 D BluetoothInputDevice: Proxy object disconnected
10-28 15:46:06.133  3127  3127 D HidProfile: Bluetooth service disconnected
10-28 15:46:06.133  3127  3127 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-28 15:46:06.133  3127  3127 D PanProfile: Bluetooth service disconnected
10-28 15:46:06.133  3127  3127 D BluetoothMap: Proxy object disconnected
10-28 15:46:06.133  3127  3127 D MapProfile: Bluetooth service disconnected
10-28 15:46:06.134  5808  5808 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-28 15:46:06.134  5808  5808 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-28 15:46:06.135  5808  5824 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-28 15:46:06.135  5808  5831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:46:06.135  5808  5831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:46:06.135  5808  5831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:46:06.135  5808  5808 D SapService: Received stop request...Stopping profile...
10-28 15:46:06.135  5808  5808 V SapService: stop()
,10-28 15:46:06.136  5808  5824 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-28 15:46:06.136  5808  5808 V BluetoothAdapterState: isTurningOff()=true
10-28 15:46:06.136  5808  5808 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:06.136  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:06.137  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:06.138  5808  5831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:46:06.138  5808  5808 V BluetoothAdapterState: isTurningOff()=true
10-28 15:46:06.138  5808  5808 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:06.138  5808  5831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:46:06.138  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:06.138  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
,10-28 15:46:06.138  5675  5675 D BluetoothMap: Proxy object disconnected
10-28 15:46:06.138  5675  5675 D MapProfile: Bluetooth service disconnected
10-28 15:46:06.138  5808  5831 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-28 15:46:06.138  5808  5831 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-28 15:46:06.138  5808  5808 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-28 15:46:06.138  5808  5831 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-28 15:46:06.138  5808  5808 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-28 15:46:06.138  5808  5831 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-28 15:46:06.138  5808  5824 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-28 15:46:06.139  5808  5824 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-28 15:46:06.140  3127  3127 D BluetoothPbap: Proxy object disconnected
10-28 15:46:06.140  5675  5675 D BluetoothPbap: Proxy object disconnected
10-28 15:46:06.140  5675  5675 D PbapServerProfile: Bluetooth service disconnected
10-28 15:46:06.140  3127  3127 D PbapServerProfile: Bluetooth service disconnected
10-28 15:46:06.140  5808  5808 V BluetoothAdapterState: isTurningOff()=true
10-28 15:46:06.140  5808  5808 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:06.140  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:06.140  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:06.140  5808  5808 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-28 15:46:06.141  5808  5824 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-28 15:46:06.141  5808  5808 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-28 15:46:06.141  5808  5808 V BluetoothAdapterState: isTurningOff()=true
10-28 15:46:06.141  5808  5808 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:06.141  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:06.141  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:06.142  5808  5808 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-28 15:46:06.142  5808  5808 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-28 15:46:06.144  5808  5808 D BluetoothMapService: MAP Service closeService in
10-28 15:46:06.144  5808  5808 V BluetoothAdapterState: isTurningOff()=true
10-28 15:46:06.144  5808  5808 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:06.144  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
,10-28 15:46:06.144  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:06.145  5808  5808 D BluetoothMapService: cleanup()
10-28 15:46:06.145  5808  5808 D BluetoothMapService: MAP Service closeService in
10-28 15:46:06.145  5808  5808 V BluetoothAdapterState: isTurningOff()=true
10-28 15:46:06.145  5808  5808 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:06.145  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:06.145  5808  5808 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:06.145  5808  5820 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-28 15:46:06.145  5808  5820 D BluetoothAdapterProperties: Setting state to 15
10-28 15:46:06.145  5808  5820 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,10-28 15:46:06.146  5808  5820 I BluetoothAdapterState: Entering BleOnState
10-28 15:46:06.146  5675  5686 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-28 15:46:06.146  5675  5687 D BluetoothPan: onBluetoothStateChange on: false
,10-28 15:46:06.156  5675  5686 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-28 15:46:06.158   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 15:46:06.158  5675  5686 D BluetoothPbap: onBluetoothStateChange: up=false
10-28 15:46:06.159  5675  5686 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 15:46:06.159  3127  3967 D BluetoothMap: onBluetoothStateChange: up=false
,10-28 15:46:06.160  5675  5686 D BluetoothMap: onBluetoothStateChange: up=false
10-28 15:46:06.160   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 15:46:06.160   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 15:46:06.160  3127  3143 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 15:46:06.161  3127  3144 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 15:46:06.161  3127  3967 D BluetoothPan: onBluetoothStateChange on: false
,10-28 15:46:06.161  3127  3143 D BluetoothPbap: onBluetoothStateChange: up=false
10-28 15:46:06.162   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 15:46:06.162  3810  3826 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 15:46:06.166  3127  3144 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-28 15:46:06.167  5808  5820 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-28 15:46:06.167  5808  5820 D BluetoothAdapterProperties: Setting state to 16
10-28 15:46:06.167  5808  5820 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-28 15:46:06.167  5808  5820 D BluetoothAdapterProperties: onBleDisable
10-28 15:46:06.168  5808  5820 I BluetoothAdapterState: Entering PendingCommandState
10-28 15:46:06.168  5808  5821 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-28 15:46:06.169  5808  5831 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-28 15:46:06.169  5808  5831 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 15:46:06.170  5808  5824 D BluetoothAdapterProperties: Scan Mode:20
,10-28 15:46:06.173  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:06.174  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:06.177  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:06.179  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:06.180  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:06.182  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:06.183  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-28 15:46:06.189  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-28 15:46:06.194  5675  5675 D DockEventReceiver: finishStartingService: stopping service
,10-28 15:46:06.380  5808  5824 I bt_hci  : shut_down
,10-28 15:46:06.384  5808  5828 I bt_vendor: low_power_mode_cb
,10-28 15:46:06.385  5808  5828 D bt_hwcfg: hw_epilog_process
,10-28 15:46:06.388  5808  5828 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-28 15:46:06.388  5808  5828 I bt_vendor: epilog_cb
10-28 15:46:06.388  5808  5828 I bt_hci  : epilog_finished_callback
,10-28 15:46:06.390  5808  5824 I bt_hci_h4: hal_close
,10-28 15:46:06.390  5808  5824 I bt_userial_vendor: device fd = 54 close
,10-28 15:46:06.502  5808  5821 D bt_stack_manager: event_shut_down_stack finished.
,10-28 15:46:06.502  5808  5820 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-28 15:46:06.506  5808  5820 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-28 15:46:06.506  5808  5808 D BtGatt.DebugUtils: handleDebugAction() action=null
10-28 15:46:06.507  5808  5808 D BtGatt.GattService: Received stop request...Stopping profile...
10-28 15:46:06.507  5808  5808 D BtGatt.GattService: stop()
,10-28 15:46:06.507  5808  5808 D BtGatt.AdvertiseManager: advertise clients cleared
10-28 15:46:06.510  5808  5808 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:06.510  5808  5808 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:06.510  5808  5808 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:06.510  5808  5808 V BluetoothAdapterState: isBleTurningOff()=true
,10-28 15:46:06.510  5808  5820 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-28 15:46:06.511  5808  5820 D BluetoothAdapterProperties: Setting state to 10
10-28 15:46:06.511  5808  5820 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-28 15:46:06.511  5808  5820 I BluetoothAdapterState: Entering OffState
10-28 15:46:06.512   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-28 15:46:06.523  5808  5808 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-28 15:46:06.523  5808  5808 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-28 15:46:06.523  5808  5808 I BluetoothServiceJni: cleanupNative: return from cleanup
10-28 15:46:06.525  5808  5821 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-28 15:46:06.531  5808  5808 I art     : System.exit called, status: 0
,10-28 15:46:06.532  5808  5808 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-28 15:46:06.561   930  3407 I ActivityManager: Process com.android.bluetooth (pid 5808) has died
,10-28 15:46:11.084  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 15:46:11.084  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:46:11.089  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 15:46:11.089  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e0e3dd9 removed from the list
,10-28 15:46:11.089  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:46:11.089  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 15:46:11.089  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:46:11.092  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-28 15:46:11.092  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e39fe7f added. We now have 4 listener(s)
10-28 15:46:11.092  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:46:11.094  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:11.094  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e39fe7f removed from the list
,10-28 15:46:11.094  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:46:11.094  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:11.094  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:11.096  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-28 15:46:11.096  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f763e4c added. We now have 4 listener(s)
10-28 15:46:11.097  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 15:46:16.107  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:16.139   930   947 I ActivityManager: Start proc 5869:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-28 15:46:16.221  5869  5869 D AdapterServiceConfig: Adding HeadsetService
10-28 15:46:16.221  5869  5869 D AdapterServiceConfig: Adding A2dpService
10-28 15:46:16.221  5869  5869 D AdapterServiceConfig: Adding HidService
10-28 15:46:16.221  5869  5869 D AdapterServiceConfig: Adding HealthService
10-28 15:46:16.222  5869  5869 D AdapterServiceConfig: Adding PanService
10-28 15:46:16.222  5869  5869 D AdapterServiceConfig: Adding GattService
10-28 15:46:16.222  5869  5869 D AdapterServiceConfig: Adding BluetoothMapService
10-28 15:46:16.222  5869  5869 D AdapterServiceConfig: Adding SapService
,10-28 15:46:16.232   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16ead70:true
,10-28 15:46:16.233  5869  5869 D BluetoothAdapterState: make() - Creating AdapterState
,10-28 15:46:16.236  5869  5869 I bt_bluedroid: init
,10-28 15:46:16.237  5869  5881 I BluetoothAdapterState: Entering OffState
,10-28 15:46:16.239  5869  5882 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-28 15:46:16.239  5869  5882 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,10-28 15:46:16.239  5869  5882 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-28 15:46:16.239  5869  5882 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-28 15:46:16.240  5869  5869 I bt_bluedroid: get_profile_interface socket
,10-28 15:46:16.242  5869  5885 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-28 15:46:16.242  5869  5869 I bt_bluedroid: get_profile_interface sdp
10-28 15:46:16.243  5869  5885 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-28 15:46:16.247  5869  5880 I bt_bluedroid: config_hci_snoop_log
,10-28 15:46:16.249   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-28 15:46:16.253  5869  5881 D BluetoothAdapterState: Current state: OFF, message: 0
10-28 15:46:16.253  5869  5881 D BluetoothAdapterProperties: Setting state to 14
10-28 15:46:16.253  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-28 15:46:16.254  5869  5881 D BluetoothBondStateMachine: make
,10-28 15:46:16.256  5869  5886 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-28 15:46:16.258  5869  5881 I BluetoothAdapterState: Entering PendingCommandState
,10-28 15:46:16.260  5869  5869 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
10-28 15:46:16.262  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:16.263  5869  5869 D BtGatt.DebugUtils: handleDebugAction() action=null
10-28 15:46:16.263  5869  5869 D BtGatt.GattService: Received start request. Starting profile...
10-28 15:46:16.263  5869  5869 D BtGatt.GattService: start()
10-28 15:46:16.263  5869  5869 I bt_bluedroid: get_profile_interface gatt
10-28 15:46:16.264  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:16.264  5869  5869 D BtGatt.AdvertiseManager: advertise manager created
,10-28 15:46:16.270  5869  5869 V BluetoothAdapterState: isTurningOff()=false
,10-28 15:46:16.270  5869  5869 V BluetoothAdapterState: isTurningOn()=false
10-28 15:46:16.270  5869  5869 V BluetoothAdapterState: isBleTurningOn()=true
10-28 15:46:16.270  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:16.270  5869  5881 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-28 15:46:16.272  5869  5881 I bt_bluedroid: bt_bluedroid
,10-28 15:46:16.272  5869  5882 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-28 15:46:16.272  5869  5882 I bt_hci  : start_up
,10-28 15:46:16.278  5869  5882 I bt_vendor: alloc value 0xf3f09871
,10-28 15:46:16.278  5869  5882 I bt_vendor: init
10-28 15:46:16.278  5869  5882 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-28 15:46:16.278  5869  5882 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-28 15:46:16.389  5869  5882 D bt_hci  : start_up starting async portion
,10-28 15:46:16.390  5869  5889 I bt_hci  : event_finish_startup
10-28 15:46:16.390  5869  5889 I bt_hci_h4: hal_open
10-28 15:46:16.390  5869  5889 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-28 15:46:16.389  5890  5890 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-28 15:46:16.393  5869  5889 I bt_userial_vendor: device fd = 54 open
,10-28 15:46:16.409  5869  5889 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-28 15:46:16.413  5869  5889 D bt_hwcfg: Chipset BCM4358A3
,10-28 15:46:16.413  5869  5889 D bt_hwcfg: Target name = [BCM4358A3]
10-28 15:46:16.413  5869  5889 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-28 15:46:16.938  5869  5889 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-28 15:46:16.939  5869  5889 D bt_hwcfg: Settlement delay -- 100 ms
,10-28 15:46:16.939  5869  5889 I bt_hwcfg: Setting fw settlement delay to 100 
,10-28 15:46:17.071  5869  5889 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-28 15:46:17.072  5869  5889 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-28 15:46:17.074  5869  5889 I bt_hwcfg: vendor lib fwcfg completed
10-28 15:46:17.075  5869  5889 I bt_vendor: firmware callback
10-28 15:46:17.075  5869  5889 I bt_hci  : firmware_config_callback
,10-28 15:46:17.083  5869  5892 I bt_btu  : btu_task pending for preload complete event
,10-28 15:46:17.084  5869  5892 I bt_btu_task: Bluetooth chip preload is complete
10-28 15:46:17.084  5869  5892 I bt_btu  : btu_task received preload complete event
,10-28 15:46:17.093  5869  5892 I         : BTE_InitTraceLevels -- TRC_HCI
,10-28 15:46:17.093  5869  5892 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-28 15:46:17.093  5869  5892 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-28 15:46:17.093  5869  5892 I         : BTE_InitTraceLevels -- TRC_AVDT
10-28 15:46:17.093  5869  5892 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-28 15:46:17.093  5869  5892 I         : BTE_InitTraceLevels -- TRC_A2D
10-28 15:46:17.093  5869  5892 I         : BTE_InitTraceLevels -- TRC_BNEP
10-28 15:46:17.093  5869  5892 I         : BTE_InitTraceLevels -- TRC_BTM
10-28 15:46:17.094  5869  5892 I         : BTE_InitTraceLevels -- TRC_GAP
,10-28 15:46:17.094  5869  5892 I         : BTE_InitTraceLevels -- TRC_PAN
10-28 15:46:17.094  5869  5892 I         : BTE_InitTraceLevels -- TRC_SDP
10-28 15:46:17.094  5869  5892 I         : BTE_InitTraceLevels -- TRC_GATT
,10-28 15:46:17.094  5869  5892 I         : BTE_InitTraceLevels -- TRC_SMP
10-28 15:46:17.094  5869  5892 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-28 15:46:17.094  5869  5892 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-28 15:46:17.177  5869  5892 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e87549
10-28 15:46:17.178  5869  5892 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e87549 
,10-28 15:46:17.191  5869  5885 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-28 15:46:17.192  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-28 15:46:17.193  5869  5885 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-28 15:46:17.196  5869  5885 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-28 15:46:17.198  5869  5885 D BluetoothAdapterProperties: Scan Mode:20
,10-28 15:46:17.199  5869  5885 D BluetoothAdapterProperties: Discoverable Timeout:120
10-28 15:46:17.199  5869  5885 D bt_hci  : do_postload posting postload work item
10-28 15:46:17.200  5869  5889 I bt_hci  : event_postload
,10-28 15:46:17.200  5869  5889 I bt_vendor: sco_config_cb
10-28 15:46:17.200  5869  5889 I bt_hci  : sco_config_callback postload finished.
10-28 15:46:17.203  5869  5885 D bt_bte_conf: Device ID record 1 : primary
10-28 15:46:17.204  5869  5885 D bt_bte_conf:   vendorId            = 000f
,10-28 15:46:17.204  5869  5885 D bt_bte_conf:   vendorIdSource      = 0001
,10-28 15:46:17.204  5869  5885 D bt_bte_conf:   product             = 1200
10-28 15:46:17.204  5869  5885 D bt_bte_conf:   version             = 1436
10-28 15:46:17.204  5869  5885 D bt_bte_conf:   clientExecutableURL = 
10-28 15:46:17.204  5869  5885 D bt_bte_conf:   serviceDescription  = 
10-28 15:46:17.204  5869  5885 D bt_bte_conf:   documentationURL    = 
10-28 15:46:17.204  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:17.204  5869  5885 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-28 15:46:17.205  5869  5882 D bt_stack_manager: event_start_up_stack finished
10-28 15:46:17.207  5869  5881 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-28 15:46:17.207  5869  5881 D BluetoothAdapterProperties: Setting state to 15
10-28 15:46:17.207  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-28 15:46:17.208  5869  5881 I BluetoothAdapterState: Entering BleOnState
,10-28 15:46:17.209  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:17.209  5869  5889 I bt_vendor: low_power_mode_cb
,10-28 15:46:17.211  5869  5881 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-28 15:46:17.211  5869  5881 D BluetoothAdapterProperties: Setting state to 11
10-28 15:46:17.211  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-28 15:46:17.218  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:17.219  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
,10-28 15:46:17.220  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:17.222  5869  5869 D HeadsetService: Received start request. Starting profile...
10-28 15:46:17.224  5869  5869 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-28 15:46:17.224  5869  5869 D HeadsetStateMachine: make
,10-28 15:46:17.233  5869  5881 I BluetoothAdapterState: Entering PendingCommandState
,10-28 15:46:17.237  5869  5869 D HeadsetStateMachine: max_hf_connections = 1
,10-28 15:46:17.238  5869  5869 I bt_bluedroid: get_profile_interface handsfree
10-28 15:46:17.238  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-28 15:46:17.238  5869  5885 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-28 15:46:17.241  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
,10-28 15:46:17.242  5869  5869 D A2dpService: Received start request. Starting profile...
,10-28 15:46:17.242  5869  5869 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-28 15:46:17.243  5869  5869 I bt_bluedroid: get_profile_interface avrcp
,10-28 15:46:17.249  5869  5869 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-28 15:46:17.249  5869  5869 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-28 15:46:17.249  5869  5869 D A2dpStateMachine: make
10-28 15:46:17.250  5869  5869 I bt_bluedroid: get_profile_interface a2dp
,10-28 15:46:17.251  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-28 15:46:17.253  5869  5900 D A2dpStateMachine: Enter Disconnected: -2
10-28 15:46:17.254  5869  5869 I BluetoothHidServiceJni: classInitNative: succeeds
10-28 15:46:17.255  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:17.256  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-28 15:46:17.256  5869  5869 D HidService: Received start request. Starting profile...
10-28 15:46:17.256  5869  5869 I bt_bluedroid: get_profile_interface hidhost
,10-28 15:46:17.256  5869  5869 D HidService: setHidService(): set to: null
10-28 15:46:17.256  5869  5885 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e6856d
10-28 15:46:17.256  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-28 15:46:17.257  5869  5869 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-28 15:46:17.257  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
,10-28 15:46:17.258  5869  5869 D HealthService: Received start request. Starting profile...
,10-28 15:46:17.260  5869  5869 I bt_bluedroid: get_profile_interface health
,10-28 15:46:17.260  5869  5869 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-28 15:46:17.261  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
,10-28 15:46:17.261  5869  5869 D PanService: Received start request. Starting profile...
,10-28 15:46:17.262  5869  5869 D BluetoothPanServiceJni: initializeNative(L110): pan
10-28 15:46:17.262  5869  5869 I bt_bluedroid: get_profile_interface pan
10-28 15:46:17.262  5869  5885 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-28 15:46:17.264  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:17.265  5869  5869 D BluetoothMapService: Received start request. Starting profile...
10-28 15:46:17.265  5869  5869 D BluetoothMapService: start()
10-28 15:46:17.268  5869  5869 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-28 15:46:17.268  5869  5869 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-28 15:46:17.268  5869  5869 D BluetoothMapAppObserver: createReceiver()
,10-28 15:46:17.270  5869  5869 D BluetoothMapAppObserver: initObservers()
10-28 15:46:17.270  5869  5869 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-28 15:46:17.277  5869  5869 V SapService: SapBinder()
,10-28 15:46:17.278  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:17.278  5869  5869 D SapService: Received start request. Starting profile...
10-28 15:46:17.278  5869  5869 V SapService: start()
,10-28 15:46:17.280  5869  5869 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:17.281  5869  5898 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
,10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:17.281  5869  5869 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:17.282  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
,10-28 15:46:17.283  5869  5869 V BluetoothAdapterState: isTurningOff()=false
10-28 15:46:17.283  5869  5869 V BluetoothAdapterState: isTurningOn()=true
10-28 15:46:17.283  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
10-28 15:46:17.283  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
10-28 15:46:17.283  5869  5881 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-28 15:46:17.283  5869  5881 D BluetoothAdapterProperties: ScanMode =  20
10-28 15:46:17.283  5869  5881 D BluetoothAdapterProperties: State =  11
,10-28 15:46:17.285  5869  5885 D BluetoothAdapterProperties: Scan Mode:21
,10-28 15:46:17.285  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-28 15:46:17.286  5869  5881 D BluetoothAdapterProperties: Setting state to 12
10-28 15:46:17.286  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-28 15:46:17.287  5869  5881 I BluetoothAdapterState: Entering OnState
10-28 15:46:17.287  5675  5864 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 15:46:17.287  5869  5885 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-28 15:46:17.288  5675  5687 D BluetoothPan: onBluetoothStateChange on: true
10-28 15:46:17.290  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:17.290  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:17.290  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:17.290  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:46:17.290  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:17.290  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:17.290  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:17.290  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:46:17.290  5675  5686 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-28 15:46:17.291   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-28 15:46:17.292  5675  5864 D BluetoothPbap: onBluetoothStateChange: up=true
10-28 15:46:17.292  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:46:17.294  5675  5686 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 15:46:17.295  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:17.295  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:17.295  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:17.295  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:46:17.295  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:17.295  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:17.295  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:17.295  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 15:46:17.296  5869  5869 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-28 15:46:17.296  3127  3143 D BluetoothMap: onBluetoothStateChange: up=true
10-28 15:46:17.296  5869  5869 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-28 15:46:17.297  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 15:46:17.298  5675  5687 D BluetoothMap: onBluetoothStateChange: up=true
,10-28 15:46:17.298  5869  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 15:46:17.299   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 15:46:17.300   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 15:46:17.300  5869  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 15:46:17.300  3127  3967 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 15:46:17.301  5869  5869 D ObexServerSockets: Succeed to create listening sockets 
10-28 15:46:17.301  5869  5869 D ObexServerSockets0: startAccept()
10-28 15:46:17.301  5869  5869 D ObexServerSockets0: prepareForNewConnect()
10-28 15:46:17.301  3127  3144 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 15:46:17.302  3127  3143 D BluetoothPan: onBluetoothStateChange on: true
10-28 15:46:17.304  3127  3127 D BluetoothPan: BluetoothPAN Proxy object connected
10-28 15:46:17.304  3127  3144 D BluetoothPbap: onBluetoothStateChange: up=true
10-28 15:46:17.304  3127  3127 D PanProfile: Bluetooth service connected
10-28 15:46:17.304  5869  5869 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-28 15:46:17.304  5869  5869 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-28 15:46:17.304  5675  5675 D BluetoothPan: BluetoothPAN Proxy object connected
,10-28 15:46:17.304  5675  5675 D PanProfile: Bluetooth service connected
10-28 15:46:17.304  5869  5905 D ObexServerSockets0: Accepting socket connection...
10-28 15:46:17.304  5675  5675 D BluetoothInputDevice: Proxy object connected
10-28 15:46:17.305  5869  5906 D ObexServerSockets0: Accepting socket connection...
10-28 15:46:17.305  5675  5675 D HidProfile: Bluetooth service connected
10-28 15:46:17.305   930   930 D BluetoothA2dp: Proxy object connected
10-28 15:46:17.305   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-28 15:46:17.305  3127  3127 D BluetoothA2dp: Proxy object connected
,10-28 15:46:17.305  3810  4000 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-28 15:46:17.306  3127  3143 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-28 15:46:17.307  3127  3127 D BluetoothMap: Proxy object connected
10-28 15:46:17.307  3127  3127 D MapProfile: Bluetooth service connected
10-28 15:46:17.307  3127  3127 D BluetoothMap: getConnectedDevices()
10-28 15:46:17.307  5675  5675 D BluetoothA2dp: Proxy object connected
10-28 15:46:17.308  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-28 15:46:17.309   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-28 15:46:17.309  5869  5869 D BluetoothMapService: onReceive
10-28 15:46:17.309  5869  5869 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-28 15:46:17.309  5869  5869 D BluetoothMapService: STATE_ON
10-28 15:46:17.310  3127  3127 D BluetoothInputDevice: Proxy object connected
,10-28 15:46:17.310  3127  3127 D HidProfile: Bluetooth service connected
10-28 15:46:17.310  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:17.311  5675  5675 D BluetoothMap: Proxy object connected
10-28 15:46:17.311  5675  5675 D MapProfile: Bluetooth service connected
10-28 15:46:17.311  5675  5675 D BluetoothMap: getConnectedDevices()
10-28 15:46:17.311  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:17.314  5869  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 15:46:17.317  5869  5910 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-28 15:46:17.317  5869  5910 D BluetoothSdpJni: SDP Create record success - handle: 1
10-28 15:46:17.318  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-28 15:46:17.323  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-28 15:46:17.324  5675  5675 D DockEventReceiver: finishStartingService: stopping service
,10-28 15:46:17.326  5675  5675 D BluetoothPbap: Proxy object connected
10-28 15:46:17.326  5675  5675 D PbapServerProfile: Bluetooth service connected
10-28 15:46:17.327  3127  3127 D BluetoothPbap: Proxy object connected
10-28 15:46:17.328  3127  3127 D PbapServerProfile: Bluetooth service connected
,10-28 15:46:17.329  5869  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-28 15:46:17.339  5869  5869 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-28 15:46:17.339  5869  5869 D ObexServerSockets0: prepareForNewConnect()
,10-28 15:46:17.341  5869  5918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-28 15:46:17.342  5869  5918 I BtOppRfcommListener: Accept thread started.
,10-28 15:46:17.390  5675  5687 D BluetoothHeadset: Proxy object connected
,10-28 15:46:17.390  3810  3826 D BluetoothHeadset: Proxy object connected
10-28 15:46:17.391   930   930 D BluetoothHeadset: Proxy object connected
10-28 15:46:17.391  3127  3967 D BluetoothHeadset: Proxy object connected
10-28 15:46:17.391  3127  3127 D HeadsetProfile: Bluetooth service connected
,10-28 15:46:17.391   930   930 D BluetoothHeadset: Proxy object connected
10-28 15:46:17.391   930   930 D BluetoothHeadset: Proxy object connected
10-28 15:46:17.392  5675  5675 D HeadsetProfile: Bluetooth service connected
10-28 15:46:17.392   930   947 D BluetoothHeadset: Proxy object connected
,10-28 15:46:17.400   930   947 D BluetoothHeadset: Proxy object connected
,10-28 15:46:17.402  3127  3144 D BluetoothHeadset: Proxy object connected
10-28 15:46:17.402  3127  3127 D HeadsetProfile: Bluetooth service connected
,10-28 15:46:17.406   930   947 D BluetoothHeadset: Proxy object connected
,10-28 15:46:17.406  3810  3825 D BluetoothHeadset: Proxy object connected
,10-28 15:46:17.783   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-28 15:46:17.784   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-28 15:46:21.123  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:21.123  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:21.123  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:21.123  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 15:46:21.123  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:21.123  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:21.123  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:21.123  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 15:46:21.128  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-28 15:46:21.129  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 15:46:21.130  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f763e4c removed from the list
10-28 15:46:21.130  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:46:21.130  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:21.130  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:46:21.133  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:21.134  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@71bde95 added. We now have 4 listener(s)
10-28 15:46:21.134  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:46:21.136   930  3593 D WifiService: setWifiEnabled: false pid=5611, uid=10077
10-28 15:46:21.136   930  3593 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 15:46:26.144  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:26.145   930  3222 D WifiService: setWifiEnabled: true pid=5611, uid=10077
10-28 15:46:26.145   930  3222 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 15:46:26.156   507   923 D SoftapController: Softap fwReload - Ok
10-28 15:46:26.160   507   923 D CommandListener: Setting iface cfg
,10-28 15:46:26.160   507   923 D CommandListener: Trying to bring down wlan0
,10-28 15:46:26.161   507   923 D CommandListener: Clearing all IP addresses on wlan0
,10-28 15:46:26.164   930  3012 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-28 15:46:26.771   930  3012 D wifi    : set interface wlan0 flags (UP)
,10-28 15:46:26.773   930  3012 I WifiHAL : Initializing wifi
10-28 15:46:26.773   930  3012 I WifiHAL : Creating socket
,10-28 15:46:26.782   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-28 15:46:26.783   930  3012 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-28 15:46:26.783   930  3012 D wifi    : Did set static halHandle = 0x7f6784ee40
,10-28 15:46:26.783   930  3012 D wifi    : halHandle = 0x7f6784ee40, mVM = 0x7f83ecd140, mCls = 0x2015c6
,10-28 15:46:26.784   930  3012 D wifi    : array field set
,10-28 15:46:26.784   930  3012 I WifiNative-HAL: interface[0] = wlan0
,10-28 15:46:26.786   930  5923 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547197611584
10-28 15:46:26.786   930  5923 D wifi    : waitForHalEvents called, vm = 0x7f83ecd140, obj = 0x2015c6, env = 0x7f793f7b40
,10-28 15:46:26.843  5924  5924 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-28 15:46:26.863  5924  5924 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-28 15:46:26.872  5924  5924 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-28 15:46:26.872  5924  5924 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-28 15:46:26.888   930  3012 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-28 15:46:26.899   930  3012 D WifiConfigStore: Loading config and enabling all networks 
,10-28 15:46:26.902  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:26.902  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:26.902  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:26.902  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:26.902  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:26.902  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:26.902  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:26.902  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 15:46:26.905  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-28 15:46:26.909  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:26.909  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:26.909  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:26.909  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:26.909  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:26.909  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 15:46:26.909  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 15:46:26.909  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 15:46:26.912  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-28 15:46:26.912   930  3012 D WifiConfigStore: loaded 0 passpoint configs
10-28 15:46:26.912   930  3012 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-28 15:46:26.913   930  3012 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-28 15:46:26.913  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:26.914   930  3012 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-28 15:46:26.915  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:26.915   930  3012 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-28 15:46:26.915   930  3012 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-28 15:46:26.916   930  3012 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-28 15:46:26.916   930  3012 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-28 15:46:26.922   930  3012 D WifiNative-HAL: Setting external_sim to 1
,10-28 15:46:26.922  4954  4954 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-28 15:46:26.922   930  3012 D wifi    : setting dfs flag to true, 0x7f654fadc0
10-28 15:46:26.923   930  3012 D WifiStateMachine: Setting OUI to DA-A1-19
10-28 15:46:26.924   930  3012 D wifi    : setting scan oui 0x7f654fadc0
10-28 15:46:26.924   930  3012 D WifiHAL : Sending mac address OUI
,10-28 15:46:26.927   930  3012 E native  : do suspend false
,10-28 15:46:26.935   930   930 D RttService: SCAN_AVAILABLE : 3
,10-28 15:46:26.935   930  3012 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-28 15:46:26.935   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-28 15:46:26.935   930  3079 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-28 15:46:26.936   507   923 D CommandListener: Setting iface cfg
10-28 15:46:26.940   930  3000 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
10-28 15:46:26.940   930  3000 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-28 15:46:26.948   930  3000 D WifiNative-HAL: p2pGetDeviceAddress
,10-28 15:46:26.952   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=227677 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-28 15:46:26.953   930  3000 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-28 15:46:27.785   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:28.786   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:29.787   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:29.996  5924  5924 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-28 15:46:30.001  5924  5924 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-28 15:46:30.005  5924  5924 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-28 15:46:30.067   930  3012 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-28 15:46:30.068   930  3012 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-28 15:46:30.068   930  3012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-28 15:46:30.079   930  3012 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-28 15:46:30.112   930  3012 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-28 15:46:30.114  5924  5924 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-28 15:46:30.534  5924  5924 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-28 15:46:30.569  5924  5924 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-28 15:46:30.570  5924  5924 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-28 15:46:30.577   930  3012 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-28 15:46:30.578   930  3012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-28 15:46:30.578   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-28 15:46:30.595   930  3012 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-28 15:46:30.607   507   923 D CommandListener: Setting iface cfg
,10-28 15:46:30.613   930  3012 D WifiStateMachine: Start Dhcp Watchdog 3
,10-28 15:46:30.619   930  5929 D DhcpClient: Receive thread started
,10-28 15:46:30.623   930  3012 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-28 15:46:30.623   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-28 15:46:30.623   930  3014 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-28 15:46:30.704   930  3012 E native  : do suspend false
,10-28 15:46:30.719   930  5928 D DhcpClient: Broadcasting DHCPDISCOVER
,10-28 15:46:30.733   930  5929 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-28 15:46:30.733   930  5928 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-28 15:46:30.735   930  5928 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-28 15:46:30.747   930  5929 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-28 15:46:30.748   930  5928 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-28 15:46:30.750   507   923 D CommandListener: Setting iface cfg
,10-28 15:46:30.754   930  3012 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-28 15:46:30.760   930  5928 D DhcpClient: Scheduling renewal in 86399s
,10-28 15:46:30.768   930  3012 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-28 15:46:30.769   930  3012 D WifiConfigStore: No blacklist allowed without epno enabled
10-28 15:46:30.771   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-28 15:46:30.773   930  3014 D ConnectivityService: Adding iface wlan0 to network 102
10-28 15:46:30.778   930  3012 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-28 15:46:30.787   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:30.829   930  3014 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-28 15:46:30.829   930  3014 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-28 15:46:30.832   930  3014 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-28 15:46:30.834   930  3014 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
10-28 15:46:30.836   930  3014 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-28 15:46:30.847   930  3014 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-28 15:46:30.852   930  3014 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-28 15:46:30.853   930  3014 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-28 15:46:30.853   930  3014 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-28 15:46:30.853   930  3012 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-28 15:46:30.853   930  3014 D ConnectivityService:    accepting network in place of null
10-28 15:46:30.853   930  3012 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-28 15:46:30.854   930  3014 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-28 15:46:30.864   930  5927 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231588, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-28 15:46:30.878   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 15:46:30.901   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 15:46:30.904   930  3014 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
10-28 15:46:30.904  3753  3905 W QCNEJ   : |CORE| network available: 102
,10-28 15:46:30.904   930  3014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-28 15:46:30.905   930  3014 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,10-28 15:46:30.905  3753  3905 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-28 15:46:30.910  3753  3905 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-28 15:46:30.910  3753  3905 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-28 15:46:30.912   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-28 15:46:30.914  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:30.914  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:30.914  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:30.914  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:30.914  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:30.914  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:30.914  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:46:30.914  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:46:30.917  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 15:46:30.920  3882  3882 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-28 15:46:30.921  4979  5019 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-28 15:46:30.921  4979  5019 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-28 15:46:30.922  4979  5019 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-28 15:46:30.922  4979  5019 E SarControlService: no key has been found,reset the power
10-28 15:46:30.922  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:30.922  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:30.922  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:30.922  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:30.922  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:30.922  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:30.922  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:46:30.922  5611  5611 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:46:30.922  4979  5050 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-28 15:46:30.922  4979  5050 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,10-28 15:46:30.922  4979  5050 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-28 15:46:30.923  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 15:46:30.923  5033  5033 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-28 15:46:30.924  4979  5050 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-28 15:46:30.924  4979  5050 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-28 15:46:30.924  4979  5050 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-28 15:46:30.925  5611  5611 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:30.926  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 15:46:30.926  5033  5033 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-28 15:46:30.930   930  5926 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=74.125.140.138,2a00:1450:400c:c08::71
,10-28 15:46:30.932  5033  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c0f0723 HexData = [00000000f003000000000000ffffffff]
,10-28 15:46:30.932  5033  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 15:46:30.932  5033  5057 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-28 15:46:30.934  3882  3882 D SystemUpdateService: onCreate
10-28 15:46:30.934  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-28 15:46:30.935  4979  4989 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-28 15:46:30.938  3882  3882 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-28 15:46:30.939  5033  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c0f0723 HexData = [00000000f103000000000000ffffffff]
10-28 15:46:30.939  5033  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 15:46:30.939  5033  5057 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
,10-28 15:46:30.939  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-28 15:46:30.940  4979  4990 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-28 15:46:30.949  3882  3882 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-28 15:46:30.954  3882  5403 I iu.UploadsManager: num queued entries: 0
,10-28 15:46:30.954  3882  5403 I iu.UploadsManager: num updated entries: 0
10-28 15:46:30.954  3882  5403 I iu.SyncManager: NEXT; no task
,10-28 15:46:30.955  3882  5941 I SystemUpdateService: active receiver: enabled
,10-28 15:46:30.959  3882  3882 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-28 15:46:30.960  3882  3882 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-28 15:46:30.961  5406  5406 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-28 15:46:30.965  5406  5406 D SprintDMHelper: simOperator: 
10-28 15:46:30.965  5406  5406 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-28 15:46:30.985  3882  5941 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-28 15:46:30.997  3882  5941 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-28 15:46:30.997  3882  5941 I SystemUpdateService: now status is 0 (complete)
10-28 15:46:30.997  3882  5941 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-28 15:46:30.997  3882  5941 I SystemUpdateService: file has been verified
10-28 15:46:30.997  3882  5941 I SystemUpdateService: OTA package size = 21989297
,10-28 15:46:31.002   930  5926 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 28 Oct 2016 19:46:30 GMT], X-Android-Received-Millis=[1477683991002], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477683990966]}
,10-28 15:46:31.003   930  3014 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-28 15:46:31.003   930  3014 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,10-28 15:46:31.003   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-28 15:46:31.003  3882  5941 I SystemUpdateService: showing system update notification
,10-28 15:46:31.004   930  3014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-28 15:46:31.013  3882  3882 D SystemUpdateService: onDestroy
,10-28 15:46:31.095  4954  5946 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-28 15:46:31.159  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 15:46:31.159  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:31.159  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:31.159  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:31.159  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:31.159  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.159  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:46:31.159  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:46:31.161  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.161  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.161  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@71bde95 removed from the list
,10-28 15:46:31.161  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:46:31.161  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.162  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 15:46:31.166  5611  5657 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-28 15:46:31.166  5611  5657 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-28 15:46:31.168  5611  5657 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ddcb277 Bundle[{}]
10-28 15:46:31.168  5611  5657 I io.jxcore.node.LifeCycleMonitor: start: OK
10-28 15:46:31.168  5611  5657 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-28 15:46:31.168  5611  5657 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-28 15:46:31.169  5611  5657 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-28 15:46:31.169  5611  5657 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-28 15:46:31.171  5611  5657 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-28 15:46:31.178  5611  5657 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,10-28 15:46:31.178  5611  5657 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-28 15:46:31.178  5611  5657 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,10-28 15:46:31.180  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-28 15:46:31.181  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed5baa added. We now have 3 listener(s)
,10-28 15:46:31.182  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-28 15:46:31.182  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:46:31.182  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:46:31.183  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.183  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67a039b added. We now have 4 listener(s)
10-28 15:46:31.183  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 15:46:31.183  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-28 15:46:31.186  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 15:46:31.191  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:46:31.191  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:31.191  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:31.191  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:31.191  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:31.191  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.191  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:46:31.191  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:46:31.193  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 15:46:31.194  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 15:46:31.194  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:46:31.194  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28cf11 added. We now have 4 listener(s)
,10-28 15:46:31.196  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-28 15:46:31.196  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:46:31.196  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-28 15:46:31.196  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:31.196  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.196  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89d8876 added. We now have 5 listener(s)
10-28 15:46:31.196  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:46:31.196  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 15:46:31.197  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:46:31.197  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:46:31.197  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:46:31.197  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.197  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:46:31.197  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-28 15:46:31.197  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:46:31.197  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed5baa removed from the list
10-28 15:46:31.197  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.197  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67a039b removed from the list
10-28 15:46:31.200  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:31.200  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 15:46:31.200  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.201  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.201  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.201  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.203  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.203  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.203  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.203  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-28 15:46:31.204  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:46:31.204  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.204  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67a039b not in the list
10-28 15:46:31.204  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.204  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.204  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.205  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.206  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.206  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.206  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-28 15:46:31.206  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:46:31.206  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.207  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89d8876 removed from the list
10-28 15:46:31.207  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:46:31.207  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.207  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.207  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-28 15:46:31.207  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:46:31.207  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28cf11 removed from the list
10-28 15:46:31.207  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:46:31.207  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@beb3e77 added. We now have 3 listener(s)
10-28 15:46:31.210  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 15:46:31.210  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:46:31.210  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-28 15:46:31.210  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.210  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73c0ae4 added. We now have 4 listener(s)
10-28 15:46:31.210  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:46:31.211  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 15:46:31.214  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:46:31.217  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:46:31.217  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:31.217  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:31.217  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:31.217  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:31.217  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.217  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:46:31.217  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:46:31.218  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.218  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-28 15:46:31.218  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:46:31.218  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@651b602 added. We now have 4 listener(s)
10-28 15:46:31.220  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 15:46:31.220  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:46:31.220  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:46:31.220  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.220  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcb4b13 added. We now have 5 listener(s)
10-28 15:46:31.220  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 15:46:31.220  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:46:31.220  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 15:46:31.220  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:31.220  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 15:46:31.220  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:46:31.221  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 15:46:31.223  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:31.224  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 15:46:31.224  5611  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 15:46:31.224  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 15:46:31.228  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.228  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-28 15:46:31.228  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-28 15:46:31.228  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-28 15:46:31.231  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.231  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 15:46:31.231  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 15:46:31.231  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 15:46:31.231  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-28 15:46:31.231  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.231  5611  5657 D BluetoothAdapter: STATE_ON
,10-28 15:46:31.234  5869  5908 D BtGatt.GattService: registerClient() - UUID=9b2fbac4-85f8-4714-ad70-7ae1e200531e
,10-28 15:46:31.234  5869  5885 D BtGatt.GattService: onClientRegistered() - UUID=9b2fbac4-85f8-4714-ad70-7ae1e200531e, clientIf=5
,10-28 15:46:31.235  5611  5622 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-28 15:46:31.235  5869  5909 D BtGatt.GattService: start scan with filters
,10-28 15:46:31.238  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-28 15:46:31.238  5869  5888 D BtGatt.ScanManager: handling starting scan
10-28 15:46:31.238  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.238  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 15:46:31.238  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.238  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 15:46:31.238  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 15:46:31.238  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.238  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 15:46:31.238  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 15:46:31.238  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-28 15:46:31.238  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.238  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-28 15:46:31.239  5869  5888 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b71738
10-28 15:46:31.239  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 15:46:31.239  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.242  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.242  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:46:31.242  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.242  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.242  5611  5657 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-28 15:46:31.242  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.242  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-28 15:46:31.242  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-28 15:46:31.242  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.242  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-28 15:46:31.243  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:46:31.243  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-28 15:46:31.244  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.245  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.245  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.245  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.245  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 15:46:31.245  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-28 15:46:31.245  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:46:31.245  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 15:46:31.245  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.245  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.245  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.245  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 15:46:31.245  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.246  5869  5885 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 15:46:31.246  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.246  5611  5657 D BluetoothAdapter: STATE_ON
10-28 15:46:31.246  5869  5888 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-28 15:46:31.247  5869  5908 D BtGatt.GattService: stopScan() - queue size =1
10-28 15:46:31.248  5869  5909 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-28 15:46:31.248  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-28 15:46:31.248  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.248  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 15:46:31.248  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.249  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.249  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.249  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.249  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 15:46:31.249  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.249  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.249  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.249  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 15:46:31.249  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-28 15:46:31.250  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-28 15:46:31.250  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.251  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 15:46:31.252  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.252  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.252  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:46:31.252  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.252  5869  5888 D BtGatt.ScanManager: Starting BLE batch scan
10-28 15:46:31.252  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.252  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:46:31.252  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:46:31.252  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,10-28 15:46:31.252  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.252  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 15:46:31.252  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 15:46:31.252  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.253  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.253  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 15:46:31.253  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.252  5869  5888 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-28 15:46:31.255  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 15:46:31.255  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:46:31.255  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:46:31.255  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:46:31.255  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.255  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:46:31.255  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:46:31.255  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:46:31.255  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@beb3e77 removed from the list
10-28 15:46:31.255  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.255  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73c0ae4 removed from the list
10-28 15:46:31.255  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 15:46:31.255  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.256  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.256  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.256  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.259  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-28 15:46:31.259  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.259  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.259  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.259  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:46:31.260  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.260  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.260  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.260  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:46:31.260  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-28 15:46:31.260  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.260  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73c0ae4 not in the list
10-28 15:46:31.260  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.260  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.260  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.261  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.261  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.261  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.261  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:46:31.261  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:46:31.261  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.261  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcb4b13 removed from the list
10-28 15:46:31.261  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-28 15:46:31.261  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.261  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.261  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:46:31.261  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:46:31.262  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@651b602 removed from the list
10-28 15:46:31.262  5869  5885 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 15:46:31.262  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.262  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:46:31.262  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@795856f added. We now have 3 listener(s)
,10-28 15:46:31.263  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-28 15:46:31.263  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:46:31.263  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:46:31.264  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.264  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2bd27c added. We now have 4 listener(s)
10-28 15:46:31.264  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:46:31.264  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 15:46:31.266  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:46:31.267  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 15:46:31.267  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 15:46:31.269  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:46:31.269  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:31.269  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:31.269  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:31.269  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:31.269  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.269  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:46:31.269  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 15:46:31.271  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.271  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 15:46:31.271  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:46:31.271  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ec035a added. We now have 4 listener(s)
10-28 15:46:31.272  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 15:46:31.272  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:46:31.272  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:46:31.273  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.273  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71f098b added. We now have 5 listener(s)
10-28 15:46:31.273  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 15:46:31.273  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:46:31.273  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 15:46:31.273  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.273  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:31.273  5869  5888 D BtGatt.ScanManager: stopping BLe Batch
10-28 15:46:31.273  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:46:31.273  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 15:46:31.273  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 15:46:31.273  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:46:31.274  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 15:46:31.276  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 15:46:31.277  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-28 15:46:31.277  5611  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 15:46:31.277  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 15:46:31.279  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-28 15:46:31.279  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.279  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-28 15:46:31.281  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.281  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-28 15:46:31.281  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-28 15:46:31.282  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-28 15:46:31.284  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-28 15:46:31.284  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.285  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.285  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 15:46:31.285  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 15:46:31.285  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 15:46:31.285  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-28 15:46:31.285  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.285  5611  5657 D BluetoothAdapter: STATE_ON
,10-28 15:46:31.287  5869  5879 D BtGatt.GattService: registerClient() - UUID=bfcd3aaf-7016-4a5c-bfec-e7ad1767fd3e
10-28 15:46:31.288  5869  5885 D BtGatt.GattService: onClientRegistered() - UUID=bfcd3aaf-7016-4a5c-bfec-e7ad1767fd3e, clientIf=5
,10-28 15:46:31.288  5611  5622 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-28 15:46:31.288  5869  5880 D BtGatt.GattService: start scan with filters
,10-28 15:46:31.290  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-28 15:46:31.290  5869  5888 D BtGatt.ScanManager: handling starting scan
10-28 15:46:31.290  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.290  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 15:46:31.290  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.290  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 15:46:31.290  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 15:46:31.290  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.290  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 15:46:31.291  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 15:46:31.291  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.291  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.291  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-28 15:46:31.291  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 15:46:31.291  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-28 15:46:31.293  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.293  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:46:31.293  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.294  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.294  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.294  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:46:31.294  5611  5657 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-28 15:46:31.294  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:46:31.294  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:46:31.294  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:46:31.294  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:46:31.294  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.294  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-28 15:46:31.294  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:46:31.294  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-28 15:46:31.294  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@795856f removed from the list
10-28 15:46:31.294  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.294  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2bd27c removed from the list
10-28 15:46:31.294  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:46:31.294  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:46:31.295  5869  5885 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 15:46:31.295  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.295  5869  5888 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-28 15:46:31.295  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.295  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-28 15:46:31.295  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.295  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:46:31.296  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.296  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-28 15:46:31.296  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.296  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.296  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.296  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-28 15:46:31.297  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.297  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.297  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.297  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:46:31.297  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:46:31.297  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.297  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2bd27c not in the list
10-28 15:46:31.297  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 15:46:31.297  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 15:46:31.297  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 15:46:31.298  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.298  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.298  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.298  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 15:46:31.298  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.299  5611  5657 D BluetoothAdapter: STATE_ON
,10-28 15:46:31.300  5869  5880 D BtGatt.GattService: stopScan() - queue size =1
,10-28 15:46:31.300  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 15:46:31.300  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.300  5869  5888 D BtGatt.ScanManager: Starting BLE batch scan
10-28 15:46:31.300  5869  5888 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-28 15:46:31.301  5869  5909 D BtGatt.GattService: unregisterClient() - clientIf=5
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.301  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 15:46:31.302  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 15:46:31.302  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.302  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.304  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.304  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:46:31.304  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.304  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.304  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:46:31.305  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:46:31.305  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.305  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:46:31.305  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org,.thaliproject.p2p.btconnectorlib.DiscoveryManager@71f098b removed from the list
10-28 15:46:31.305  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:46:31.305  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:46:31.305  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.305  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.305  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 15:46:31.305  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:46:31.305  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.305  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:46:31.305  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 15:46:31.305  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 15:46:31.305  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ec035a removed from the list
10-28 15:46:31.305  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.305  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.305  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 15:46:31.305  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.306  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:46:31.306  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@872b367 added. We now have 3 listener(s)
10-28 15:46:31.307  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.307  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.307  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.307  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.307  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:46:31.307  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 15:46:31.308  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 ,15:46:31.308  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:46:31.308  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.308  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@429f514 added. We now have 4 listener(s)
10-28 15:46:31.308  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:46:31.308  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 15:46:31.309  5869  5885 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 15:46:31.309  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.311  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:46:31.314  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 15:46:31.314  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.316  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:46:31.316  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:31.316  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:31.316  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:31.316  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:31.316  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.316  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:46:31.316  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:46:31.318  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.318  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 15:46:31.319  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:46:31.319  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@527a3b2 added. We now have 4 listener(s)
10-28 15:46:31.320  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 15:46:31.320  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.320  5869  5888 D BtGatt.ScanManager: stopping BLe Batch
10-28 15:46:31.320  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 15:46:31.320  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:46:31.320  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:31.321  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:46:31.321  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.321  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36d1f03 added. We now have 5 listener(s)
10-28 15:46:31.321  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:46:31.321  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:46:31.321  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 15:46:31.321  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 15:46:31.321  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:46:31.321  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 15:46:31.323  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:31.325  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 15:46:31.325  5611  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 15:46:31.326  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 15:46:31.326  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-28 15:46:31.326  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.326  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-28 15:46:31.330  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.330  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-28 15:46:31.331  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-28 15:46:31.331  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.331  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-28 15:46:31.331  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-28 15:46:31.334  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.334  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 15:46:31.334  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 15:46:31.334  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 15:46:31.334  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-28 15:46:31.334  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.334  5611  5657 D BluetoothAdapter: STATE_ON
10-28 15:46:31.336  5869  5880 D BtGatt.GattService: registerClient() - UUID=019a7274-d7dc-4421-bf2f-5f38c307547c
10-28 15:46:31.336  5869  5885 D BtGatt.GattService: onClientRegistered() - UUID=019a7274-d7dc-4421-bf2f-5f38c307547c, clientIf=5
10-28 15:46:31.336  5611  5621 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-28 15:46:31.337  5869  5879 D BtGatt.GattService: start scan with filters
10-28 15:46:31.338  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-28 15:46:31.338  5869  5888 D BtGatt.ScanManager: handling starting scan
10-28 15:46:31.338  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.338  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 15:46:31.338  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.339  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 15:46:31.339  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 15:46:31.339  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.340  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 15:46:31.340  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 15:46:31.340  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.340  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.340  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-28 15:46:31.340  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 15:46:31.341  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.343  5869  5885 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 15:46:31.343  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.343  5869  5888 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-28 15:46:31.343  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.344  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:46:31.344  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.344  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.344  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.346  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.346  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.346  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.346  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.346  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 15:46:31.346  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:46:31.346  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:46:31.346  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:46:31.346  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:46:31.346  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.347  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-28 15:46:31.347  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:46:31.347  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:46:31.347  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@872b367 removed from the list
,10-28 15:46:31.347  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.347  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@429f514 removed from the list
10-28 15:46:31.347  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:46:31.347  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:46:31.347  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 15:46:31.347  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.347  5869  5888 D BtGatt.ScanManager: Starting BLE batch scan
10-28 15:46:31.347  5869  5888 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-28 15:46:31.347  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.347  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-28 15:46:31.347  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.347  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:46:31.347  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.348  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.348  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.348  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.348  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:46:31.349  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:46:31.349  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.349  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@429f514 not in the list
10-28 15:46:31.349  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 15:46:31.349  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 15:46:31.349  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 15:46:31.349  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.349  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.349  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.349  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 15:46:31.349  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.350  5611  5657 D BluetoothAdapter: STATE_ON
10-28 15:46:31.350  5869  5908 D BtGatt.GattService: stopScan() - queue size =1
10-28 15:46:31.351  5869  5907 D BtGatt.GattService: unregisterClient() - clientIf=5
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.351  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 15:46:31.351  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 15:46:31.352  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.352  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.353  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.353  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:46:31.353  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.353  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.353  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:46:31.353  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:46:31.353  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.353  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:46:31.353  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36d1f03 removed from the list
10-28 15:46:31.353  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 15:46:31.353  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:46:31.353  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.353  5611  5611 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 15:46:31.353  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.353  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.353  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:46:31.353  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 15:46:31.353  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:46:31.353  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 15:46:31.353  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@527a3b2 removed from the list
10-28 15:46:31.353  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.353  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.353  5611  5611 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 15:46:31.354  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.354  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:46:31.354  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@718a85f added. We now have 3 listener(s)
10-28 15:46:31.354  5869  5885 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 15:46:31.355  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.355  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.355  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.355  5611  5611 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.355  5611  5611 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 15:46:31.355  5611  5611 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 15:46:31.355  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 15:46:31.355  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:46:31.355  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:46:31.355  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.356  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@146d2ac added. We now have 4 listener(s)
10-28 15:46:31.357  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:46:31.357  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 15:46:31.359  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 15:46:31.359  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.360  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 15:46:31.363  5611  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 15:46:31.363  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 15:46:31.363  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 15:46:31.363  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 15:46:31.363  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 15:46:31.363  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.363  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 15:46:31.363  5611  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 15:46:31.364  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 15:46:31.364  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.364  5869  5888 D BtGatt.ScanManager: stopping BLe Batch
10-28 15:46:31.365  5611  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 15:46:31.366  5611  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 15:46:31.366  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 15:46:31.366  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7bf70a added. We now have 4 listener(s)
10-28 15:46:31.367  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 15:46:31.367  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 15:46:31.368  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 15:46:31.368  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:31.368  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 15:46:31.368  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec96b7b added. We now have 5 listener(s)
10-28 15:46:31.368  5611  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 15:46:31.368  5611  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 15:46:31.368  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:46:31.368  5611  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 15:46:31.368  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:46:31.368  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.368  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 15:46:31.369  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:46:31.369  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:46:31.369  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@718a85f removed from the list
10-28 15:46:31.369  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.369  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@146d2ac removed from the list
10-28 15:46:31.369  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-28 15:46:31.369  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.369  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-28 15:46:31.370  5611  5611 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 15:46:31.370  5611  5657 D io.jxcore.node.ConnectivityMonitor: stop
10-28 15:46:31.370  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.371  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.371  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.371  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.372  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.372  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.372  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.372  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:46:31.372  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:46:31.373  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.373  5611  5657 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@146d2ac not in the list
10-28 15:46:31.373  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.373  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.373  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.374  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.374  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.374  5611  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-28 15:46:31.374  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 15:46:31.374  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 15:46:31.374  5611  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 15:46:31.375  5611  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec96b7b removed from the list
10-28 15:46:31.375  5611  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 15:46:31.375  5611  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 15:46:31.375  5611  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 15:46:31.375  5611  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 15:46:31.375  5611  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 15:46:31.375  5611  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7bf70a removed from the list
10-28 15:46:31.375  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-28 15:46:31.375  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 15:46:31.376  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-28 15:46:31.377  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-28 15:46:31.377  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-28 15:46:31.377  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:46:31.377  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-28 15:46:31.377  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-28 15:46:31.761  5611  5611 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 15:46:31.788   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:31.808  5611  5611 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 15:46:31.856  5611  5611 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 15:46:32.789   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-28 15:46:33.522  5611  5953 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-28 15:46:33.522  5611  5953 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 15:46:33.644   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-28 15:46:34.325  5611  5953 W !!      : call onHalfStreamCopied
,10-28 15:46:34.325  5611  5953 I testCopyDataAndClose: closing input stream
,10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-28 15:46:35.104  5611  5953 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-28 15:46:37.791   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:38.792   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:38.859   930  3014 D ConnectivityService: handlePromptUnvalidated 102
,10-28 15:46:38.895  5611  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-28 15:46:38.895  5611  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 15:46:39.794   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:40.795   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:40.895  5611  5657 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
10-28 15:46:40.895  5611  5657 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 15:46:40.895  5611  5657 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,10-28 15:46:41.010  5611  5956 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-28 15:46:41.010  5611  5956 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-28 15:46:41.010  5611  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,10-28 15:46:41.031  5611  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-28 15:46:41.031  5611  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 15:46:41.796   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:41.949   930  3012 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,10-28 15:46:42.649  5611  5957 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-28 15:46:42.649  5611  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 15:46:42.649  5611  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-28 15:46:42.649  5611  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 15:46:42.649  5611  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-28 15:46:42.649  5611  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-28 15:46:42.649  5611  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-28 15:46:42.649  5611  5957 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-28 15:46:42.649  5611  5957 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-28 15:46:42.650  5611  5957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-28 15:46:42.650  5611  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-28 15:46:42.797   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-28 15:46:46.401  5611  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-28 15:46:46.401  5611  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 15:46:46.401  5611  5958 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
10-28 15:46:46.401  5611  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-28 15:46:46.401  5611  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-28 15:46:46.401  5611  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-28 15:46:46.402  5611  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-28 15:46:46.402  5611  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-28 15:46:46.402  5611  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-28 15:46:46.402  5611  5958 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-28 15:46:46.402  5611  5958 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-28 15:46:46.402  5611  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-28 15:46:46.402  5611  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-28 15:46:46.404  5611  5657 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-28 15:46:46.407  5611  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-28 15:46:46.407  5611  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-28 15:46:46.408  5611  5959 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
,10-28 15:46:46.408  5611  5959 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-28 15:46:46.408  5611  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-28 15:46:46.408  5611  5959 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-28 15:46:46.409  5611  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-28 15:46:46.409  5611  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-28 15:46:46.412  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-28 15:46:46.412  5611  5657 I jxcore-log: 
10-28 15:46:46.412  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-28 15:46:46.412  5611  5657 I jxcore-log: 
,10-28 15:46:46.413  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-28 15:46:46.413  5611  5657 I jxcore-log: 
10-28 15:46:46.413  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-28 15:46:46.413  5611  5657 I jxcore-log: 
10-28 15:46:46.413  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG UnitTest_app: 'Total duration:  90766'
10-28 15:46:46.413  5611  5657 I jxcore-log: 
10-28 15:46:46.415  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-28 15:46:46.415  5611  5657 I jxcore-log: 
,10-28 15:46:46.418  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.418  5611  5657 I jxcore-log: 
,10-28 15:46:46.419  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.419  5611  5657 I jxcore-log: 
10-28 15:46:46.419  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.419  5611  5657 I jxcore-log: 
10-28 15:46:46.419  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.419  5611  5657 I jxcore-log: 
10-28 15:46:46.420  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-28 15:46:46.420  5611  5657 I jxcore-log: 
10-28 15:46:46.420  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
10-28 15:46:46.420  5611  5657 I jxcore-log: 
,10-28 15:46:46.420  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-28 15:46:46.420  5611  5657 I jxcore-log: 
10-28 15:46:46.421  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 15:46:46.421  5611  5657 I jxcore-log: 
10-28 15:46:46.421  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-28 15:46:46.421  5611  5657 I jxcore-log: 
10-28 15:46:46.421  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.421  5611  5657 I jxcore-log: 
10-28 15:46:46.422  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.422  5611  5657 I jxcore-log: 
10-28 15:46:46.422  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-28 15:46:46.422  5611  5657 I jxcore-log: 
,10-28 15:46:46.422  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
10-28 15:46:46.422  5611  5657 I jxcore-log: 
10-28 15:46:46.422  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-28 15:46:46.422  5611  5657 I jxcore-log: 
10-28 15:46:46.423  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 15:46:46.423  5611  5657 I jxcore-log: 
10-28 15:46:46.423  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-28 15:46:46.423  5611  5657 I jxcore-log: 
10-28 15:46:46.423  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 15:46:46.423  5611  5657 I jxcore-log: 
10-28 15:46:46.423  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-28 15:46:46.423  5611  5657 I jxcore-log: 
10-28 15:46:46.423  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.423  5611  5657 I jxcore-log: 
10-28 15:46:46.424  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.424  5611  5657 I jxcore-log: 
,10-28 15:46:46.424  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.424  5611  5657 I jxcore-log: 
10-28 15:46:46.424  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.424  5611  5657 I jxcore-log: 
10-28 15:46:46.424  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.424  5611  5657 I jxcore-log: 
10-28 15:46:46.425  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.425  5611  5657 I jxcore-log: 
10-28 15:46:46.426  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.426  5611  5657 I jxcore-log: 
10-28 15:46:46.426  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.426  5611  5657 I jxcore-log: 
,10-28 15:46:46.427  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.427  5611  5657 I jxcore-log: 
10-28 15:46:46.427  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.427  5611  5657 I jxcore-log: 
10-28 15:46:46.427  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.427  5611  5657 I jxcore-log: 
10-28 15:46:46.427  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.427  5611  5657 I jxcore-log: 
10-28 15:46:46.428  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.428  5611  5657 I jxcore-log: 
10-28 15:46:46.428  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.428  5611  5657 I jxcore-log: 
10-28 15:46:46.428  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.428  5611  5657 I jxcore-log: 
10-28 15:46:46.428  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.428  5611  5657 I jxcore-log: 
,10-28 15:46:46.429  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.429  5611  5657 I jxcore-log: 
10-28 15:46:46.429  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.429  5611  5657 I jxcore-log: 
10-28 15:46:46.429  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.429  5611  5657 I jxcore-log: 
10-28 15:46:46.429  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.429  5611  5657 I jxcore-log: 
10-28 15:46:46.429  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.429  5611  5657 I jxcore-log: 
10-28 15:46:46.430  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.430  5611  5657 I jxcore-log: 
10-28 15:46:46.430  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.430  5611  5657 I jxcore-log: 
10-28 15:46:46.430  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.430  5611  5657 I jxcore-log: 
10-28 15:46:46.430  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.430  5611  5657 I jxcore-log: 
,10-28 15:46:46.431  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.431  5611  5657 I jxcore-log: 
10-28 15:46:46.431  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.431  5611  5657 I jxcore-log: 
10-28 15:46:46.431  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.431  5611  5657 I jxcore-log: 
10-28 15:46:46.431  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.431  5611  5657 I jxcore-log: 
10-28 15:46:46.431  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 15:46:46.431  5611  5657 I jxcore-log: 
10-28 15:46:46.432  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.432  5611  5657 I jxcore-log: 
,10-28 15:46:46.432  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-28 15:46:46.432  5611  5657 I jxcore-log: 
10-28 15:46:46.432  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.432  5611  5657 I jxcore-log: 
10-28 15:46:46.432  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.432  5611  5657 I jxcore-log: 
10-28 15:46:46.432  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.432  5611  5657 I jxcore-log: 
10-28 15:46:46.433  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.433  5611  5657 I jxcore-log: 
10-28 15:46:46.433  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.433  5611  5657 I jxcore-log: 
10-28 15:46:46.433  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 15:46:46.433  5611  5657 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,10-28 15:46:46.433  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.433  5611  5657 I jxcore-log: 
10-28 15:46:46.434  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.434  5611  5657 I jxcore-log: 
10-28 15:46:46.434  5611  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 15:46:46.434  5611  5657 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-28 15:46:46.434  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 15:46:46.434  5611  5657 I jxcore-log: 
10-28 15:46:46.434  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 15:46:46.434  5611  5657 I jxcore-log: 
10-28 15:46:46.434  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-28 15:46:46.434  5611  5657 I jxcore-log: 
10-28 15:46:46.435  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 15:46:46.435  5611  5657 I jxcore-log: 
10-28 15:46:46.435  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-28 15:46:46.435  5611  5657 I jxcore-log: 
,10-28 15:46:46.435  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 15:46:46.435  5611  5657 I jxcore-log: 
10-28 15:46:46.435  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-28 15:46:46.435  5611  5657 I jxcore-log: 
10-28 15:46:46.437  5611  5611 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-28 15:46:46.441  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-28 15:46:46.441  5611  5657 I jxcore-log: 
,10-28 15:46:46.441  5611  5657 I jxcore-log: 2016-10-28 19:46:46 - WARN testUtils: 'myNameCallback not set!'
10-28 15:46:46.441  5611  5657 I jxcore-log: 
,10-28 15:46:48.492  5611  5657 I jxcore-log: 2016-10-28 19:46:48 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
10-28 15:46:48.492  5611  5657 I jxcore-log: 
,10-28 15:46:48.494  5611  5657 I jxcore-log: 2016-10-28 19:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-28 15:46:48.494  5611  5657 I jxcore-log: 
,10-28 15:46:48.828  5611  5657 I jxcore-log: 2016-10-28 19:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-28 15:46:48.828  5611  5657 I jxcore-log: 
,10-28 15:46:48.840  5611  5657 I jxcore-log: 2016-10-28 19:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-28 15:46:48.840  5611  5657 I jxcore-log: 
,10-28 15:46:49.951  5611  5657 I jxcore-log: 2016-10-28 19:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-28 15:46:49.951  5611  5657 I jxcore-log: 
,10-28 15:46:50.135  5611  5657 I jxcore-log: 2016-10-28 19:46:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-28 15:46:50.135  5611  5657 I jxcore-log: 
,10-28 15:46:50.141  5611  5657 I jxcore-log: 2016-10-28 19:46:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-28 15:46:50.141  5611  5657 I jxcore-log: 
,10-28 15:46:50.145  5611  5657 I jxcore-log: 2016-10-28 19:46:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-28 15:46:50.145  5611  5657 I jxcore-log: 
,10-28 15:46:50.623  5611  5657 I jxcore-log: 2016-10-28 19:46:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-28 15:46:50.623  5611  5657 I jxcore-log: 
,10-28 15:46:50.666  5611  5657 I jxcore-log: 2016-10-28 19:46:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-28 15:46:50.666  5611  5657 I jxcore-log: 
,10-28 15:46:50.680  5611  5657 I jxcore-log: 2016-10-28 19:46:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-28 15:46:50.680  5611  5657 I jxcore-log: 
,10-28 15:46:50.684  5611  5657 I jxcore-log: 2016-10-28 19:46:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-28 15:46:50.684  5611  5657 I jxcore-log: 
,10-28 15:46:50.967  5611  5657 I jxcore-log: 2016-10-28 19:46:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-28 15:46:50.967  5611  5657 I jxcore-log: 
,10-28 15:46:51.093  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-28 15:46:51.093  5611  5657 I jxcore-log: 
,10-28 15:46:51.461  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-28 15:46:51.461  5611  5657 I jxcore-log: 
,10-28 15:46:51.469  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-28 15:46:51.469  5611  5657 I jxcore-log: 
,10-28 15:46:51.473  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-28 15:46:51.473  5611  5657 I jxcore-log: 
,10-28 15:46:51.478  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-28 15:46:51.478  5611  5657 I jxcore-log: 
,10-28 15:46:51.484  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-28 15:46:51.484  5611  5657 I jxcore-log: 
,10-28 15:46:51.511  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-28 15:46:51.511  5611  5657 I jxcore-log: 
,10-28 15:46:51.545  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-28 15:46:51.545  5611  5657 I jxcore-log: 
,10-28 15:46:51.552  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-28 15:46:51.552  5611  5657 I jxcore-log: 
,10-28 15:46:51.558  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-28 15:46:51.558  5611  5657 I jxcore-log: 
,10-28 15:46:51.573  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-28 15:46:51.573  5611  5657 I jxcore-log: 
,10-28 15:46:51.577  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-28 15:46:51.577  5611  5657 I jxcore-log: 
,10-28 15:46:51.583  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-28 15:46:51.583  5611  5657 I jxcore-log: 
,10-28 15:46:51.589  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-28 15:46:51.589  5611  5657 I jxcore-log: 
,10-28 15:46:51.601  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-28 15:46:51.601  5611  5657 I jxcore-log: 
,10-28 15:46:51.607  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-28 15:46:51.607  5611  5657 I jxcore-log: 
,10-28 15:46:51.629  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-28 15:46:51.629  5611  5657 I jxcore-log: 
,10-28 15:46:51.640  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-28 15:46:51.640  5611  5657 I jxcore-log: 
,10-28 15:46:51.652  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-28 15:46:51.652  5611  5657 I jxcore-log: 
,10-28 15:46:51.662  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-28 15:46:51.662  5611  5657 I jxcore-log: 
,10-28 15:46:51.675  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-28 15:46:51.675  5611  5657 I jxcore-log: 
,10-28 15:46:51.686  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-28 15:46:51.686  5611  5657 I jxcore-log: 
,10-28 15:46:51.692  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-28 15:46:51.692  5611  5657 I jxcore-log: 
,10-28 15:46:51.714  5611  5657 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-28 15:46:51.715  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - INFO testUtils: 'BLE multiple advertisement supported'
10-28 15:46:51.715  5611  5657 I jxcore-log: 
,10-28 15:46:51.779   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-28 15:46:51.848  5611  5657 I jxcore-log: 2016-10-28 19:46:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:51.848  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:51.848  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:51.848  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:51.848  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:51.848  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:51.848  5611  5657 I jxcore-log: 
,10-28 15:46:52.028  5611  5657 I jxcore-log: 2016-10-28 19:46:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:52.028  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:52.028  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:52.028  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:52.028  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:52.028  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:52.028  5611  5657 I jxcore-log: 
,10-28 15:46:52.034  5611  5657 I jxcore-log: 2016-10-28 19:46:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:52.034  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:52.034  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:52.034  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:52.034  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:52.034  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:52.034  5611  5657 I jxcore-log: 
,10-28 15:46:52.335  5611  5657 I jxcore-log: 2016-10-28 19:46:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:52.335  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:52.335  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:52.335  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:52.335  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:52.335  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:52.335  5611  5657 I jxcore-log: 
,10-28 15:46:52.338  5611  5657 I jxcore-log: 2016-10-28 19:46:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:52.338  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:52.338  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:52.338  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:52.338  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:52.338  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:52.338  5611  5657 I jxcore-log: 
,10-28 15:46:52.798   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:52.825  5611  5657 I jxcore-log: 2016-10-28 19:46:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:52.825  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:52.825  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:52.825  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:52.825  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:52.825  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:52.825  5611  5657 I jxcore-log: 
,10-28 15:46:52.830  5611  5657 I jxcore-log: 2016-10-28 19:46:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:52.830  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:52.830  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:52.830  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:52.830  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:52.830  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:52.830  5611  5657 I jxcore-log: 
,10-28 15:46:53.799   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:53.814  5611  5657 I jxcore-log: 2016-10-28 19:46:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:53.814  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:53.814  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:53.814  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:53.814  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:53.814  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:53.814  5611  5657 I jxcore-log: 
,10-28 15:46:53.826  5611  5657 I jxcore-log: 2016-10-28 19:46:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:53.826  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:53.826  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:53.826  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:53.826  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:53.826  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:53.826  5611  5657 I jxcore-log: 
,10-28 15:46:54.800   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:54.873  5611  5657 I jxcore-log: 2016-10-28 19:46:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:54.873  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:54.873  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:54.873  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:54.873  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:54.873  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:54.873  5611  5657 I jxcore-log: 
,10-28 15:46:54.877  5611  5657 I jxcore-log: 2016-10-28 19:46:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:54.877  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:54.877  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:54.877  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:54.877  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:54.877  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:54.877  5611  5657 I jxcore-log: 
,10-28 15:46:55.801   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:55.909  5611  5657 I jxcore-log: 2016-10-28 19:46:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:55.909  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:55.909  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:55.909  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:55.909  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:55.909  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:55.909  5611  5657 I jxcore-log: 
,10-28 15:46:55.914  5611  5657 I jxcore-log: 2016-10-28 19:46:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:55.914  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:55.914  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:55.914  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:55.914  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:55.914  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:55.914  5611  5657 I jxcore-log: 
,10-28 15:46:56.802   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 15:46:56.946  5611  5657 I jxcore-log: 2016-10-28 19:46:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:56.946  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:56.946  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:56.946  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:56.946  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:56.946  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:56.946  5611  5657 I jxcore-log: 
,10-28 15:46:56.950  5611  5657 I jxcore-log: 2016-10-28 19:46:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:56.950  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:56.950  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:56.950  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:56.950  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:56.950  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:56.950  5611  5657 I jxcore-log: 
,10-28 15:46:57.803   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-28 15:46:57.821   930  3014 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-28 15:46:57.979  5611  5657 I jxcore-log: 2016-10-28 19:46:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:57.979  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:57.979  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:57.979  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:57.979  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:57.979  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:57.979  5611  5657 I jxcore-log: 
,10-28 15:46:57.984  5611  5657 I jxcore-log: 2016-10-28 19:46:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:57.984  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:57.984  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:57.984  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:57.984  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:57.984  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:57.984  5611  5657 I jxcore-log: 
,10-28 15:46:59.015  5611  5657 I jxcore-log: 2016-10-28 19:46:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:59.015  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:59.015  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:59.015  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:59.015  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:59.015  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:59.015  5611  5657 I jxcore-log: 
,10-28 15:46:59.019  5611  5657 I jxcore-log: 2016-10-28 19:46:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:46:59.019  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:46:59.019  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:46:59.019  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:46:59.019  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:46:59.019  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:46:59.019  5611  5657 I jxcore-log: 
,10-28 15:47:00.094  5611  5657 I jxcore-log: 2016-10-28 19:47:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:00.094  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:00.094  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:00.094  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:00.094  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:00.094  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:00.094  5611  5657 I jxcore-log: 
,10-28 15:47:00.098  5611  5657 I jxcore-log: 2016-10-28 19:47:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:00.098  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:00.098  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:00.098  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:00.098  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:00.098  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:00.098  5611  5657 I jxcore-log: 
,10-28 15:47:01.130  5611  5657 I jxcore-log: 2016-10-28 19:47:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:01.130  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:01.130  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:01.130  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:01.130  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:01.130  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:01.130  5611  5657 I jxcore-log: 
,10-28 15:47:01.137  5611  5657 I jxcore-log: 2016-10-28 19:47:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:01.137  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:01.137  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:01.137  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:01.137  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:01.137  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:01.137  5611  5657 I jxcore-log: 
,10-28 15:47:02.166  5611  5657 I jxcore-log: 2016-10-28 19:47:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:02.166  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:02.166  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:02.166  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:02.166  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:02.166  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:02.166  5611  5657 I jxcore-log: 
,10-28 15:47:02.170  5611  5657 I jxcore-log: 2016-10-28 19:47:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:02.170  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:02.170  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:02.170  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:02.170  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:02.170  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:02.170  5611  5657 I jxcore-log: 
,10-28 15:47:03.201  5611  5657 I jxcore-log: 2016-10-28 19:47:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:03.201  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:03.201  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:03.201  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:03.201  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:03.201  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:03.201  5611  5657 I jxcore-log: 
,10-28 15:47:03.206  5611  5657 I jxcore-log: 2016-10-28 19:47:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:03.206  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:03.206  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:03.206  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:03.206  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:03.206  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:03.206  5611  5657 I jxcore-log: 
,10-28 15:47:04.235  5611  5657 I jxcore-log: 2016-10-28 19:47:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:04.235  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:04.235  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:04.235  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:04.235  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:04.235  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:04.235  5611  5657 I jxcore-log: 
,10-28 15:47:04.241  5611  5657 I jxcore-log: 2016-10-28 19:47:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:04.241  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:04.241  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:04.241  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:04.241  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:04.241  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:04.241  5611  5657 I jxcore-log: 
,10-28 15:47:05.270  5611  5657 I jxcore-log: 2016-10-28 19:47:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 15:47:05.270  5611  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 15:47:05.270  5611  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 15:47:05.270  5611  5657 I jxcore-log: emit@events.js:82:1
10-28 15:47:05.270  5611  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 15:47:05.270  5611  5657 I jxcore-log: emit@events.js:82:1'
10-28 15:47:05.270  5611  5657 I jxcore-log: 
,10-28 15:47:05.281  5611  5657 E jxcore  : Error!: error is undefined
10-28 15:47:05.281  5611  5657 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-28 15:47:05.286  5611  5657 I jxcore-log: 2016-10-28 19:47:05 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-28 15:47:05.286  5611  5657 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
10-28 15:47:05.286  5611  5657 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-28 15:47:05.286  5611  5657 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-28 15:47:05.286  5611  5657 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-28 15:47:05.286  5611  5657 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-28 15:47:05.286  5611  5657 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-28 15:47:05.286  5611  5657 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-28 15:47:05.287  5611  5657 I jxcore-log: 2016-10-28 19:47:05 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-28 15:47:05.287  5611  5657 I jxcore-log: 
,10-28 15:47:05.289  5611  5657 E jxcore-log: TypeError: 
10-28 15:47:05.289  5611  5657 E jxcore-log: error is undefined
10-28 15:47:05.289  5611  5657 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
10-28 15:47:05.290  5611  5657 E jxcore-log: 
,10-28 15:47:05.351   930  2989 W InputDispatcher: channel '7b46aef com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-28 15:47:05.352   930  2989 E InputDispatcher: channel '7b46aef com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
10-28 15:47:05.360   930  3013 D WifiService: Client connection lost with reason: 4
10-28 15:47:05.360   930  3407 D GraphicsStats: Buffer count: 2
10-28 15:47:05.360   930   940 I WindowState: WIN DEATH: Window{7b46aef u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-28 15:47:05.360   930   940 W InputDispatcher: Attempted to unregister already unregistered input channel '7b46aef com.test.thalitest/com.test.thalitest.MainActivity (server)'
10-28 15:47:05.368   527   527 I Zygote  : Process 5611 exited cleanly (139)
10-28 15:47:05.371   930   941 I ActivityManager: Process com.test.thalitest (pid 5611) has died
,10-28 15:47:05.398   930   941 I ActivityManager: Start proc 5962:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-28 15:47:05.731   930  3838 I WindowManager: Screenshot max retries 4 of Token{5e8b1e9 ActivityRecord{bf7ba70 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{70a67aa u0 Starting com.test.thalitest} drawState=4
,10-28 15:47:05.813  5962  5962 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-28 15:47:05.829  5962  5962 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-28 15:47:05.834  5962  5962 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 6557-6558)
,10-28 15:47:05.834  5962  5962 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-28 15:47:05.843  5962  5962 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ea4e420}
10-28 15:47:05.844  5962  5962 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-28 15:47:05.844  5962  5962 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-28 15:47:05.847  5962  5962 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-28 15:47:05.848  5962  5962 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-28 15:47:05.858  5962  5962 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-28 15:47:05.866  5962  5962 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-28 15:47:05.866  5962  5962 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-28 15:47:05.866  5962  5962 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-28 15:47:05.866  5962  5962 I Adreno  : Build Date                       : 12/06/15
10-28 15:47:05.866  5962  5962 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-28 15:47:05.866  5962  5962 I Adreno  : Local Branch                     : mybranch17112971
10-28 15:47:05.866  5962  5962 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-28 15:47:05.866  5962  5962 I Adreno  : Remote Branch                    : NONE
10-28 15:47:05.866  5962  5962 I Adreno  : Reconstruct Branch               : NOTHING
,10-28 15:47:05.899   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8f8e713:true
,10-28 15:47:05.900  5960  5960 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-28 15:47:05.915  5960  5960 D AndroidRuntime: CheckJNI is OFF
,10-28 15:47:05.912   954   954 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[35354]" dev="sockfs" ino=35354 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 15:47:05.912   954   954 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[35354]" dev="sockfs" ino=35354 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 15:47:05.926  5962  5962 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-28 15:47:05.933  5962  5962 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-28 15:47:05.941  5960  5960 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-28 15:47:05.955   953   953 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32631]" dev="sockfs" ino=32631 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 15:47:05.960  5962  6003 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-28 15:47:05.955   953   953 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32631]" dev="sockfs" ino=32631 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 15:47:05.959  3827  3827 W Binder_9: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[15871]" dev="sockfs" ino=15871 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-28 15:47:05.959  3827  3827 W Binder_9: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[15871]" dev="sockfs" ino=15871 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-28 15:47:05.964  5962  5985 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-28 15:47:05.965  5960  5960 I Radio-JNI: register_android_hardware_Radio DONE
,10-28 15:47:05.980  5960  5960 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-28 15:47:05.986   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-28 15:47:05.986   930   943 I ActivityManager: Killing 5962:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-28 15:47:05.995   930  2989 W InputDispatcher: channel '4a294fe com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-28 15:47:05.995   930  2989 E InputDispatcher: channel '4a294fe com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-28 15:47:05.997   930   940 D GraphicsStats: Buffer count: 2
10-28 15:47:05.997   930  3838 I WindowState: WIN DEATH: Window{4a294fe u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-28 15:47:05.997   930  3838 W InputDispatcher: Attempted to unregister already unregistered input channel '4a294fe com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-28 15:47:06.024   930   943 W ActivityManager: Force removing ActivityRecord{bf7ba70 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,10-28 15:47:06.030   930  3827 W ActivityManager: Spurious death for ProcessRecord{ce7feac 0:com.test.thalitest/u0a77}, curProc for 5962: null
,10-28 15:47:06.101   930   955 I art     : Starting a blocking GC Explicit
,10-28 15:47:06.198   930   955 I art     : Explicit concurrent mark sweep GC freed 55050(3MB) AllocSpace objects, 16(568KB) LOS objects, 33% free, 29MB/43MB, paused 1.728ms total 96.344ms
,10-28 15:47:06.222   930   955 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-28 15:47:06.225  5960  5960 I art     : System.exit called, status: 0
,10-28 15:47:06.225  5960  5960 I AndroidRuntime: VM exiting with result code 0.
,10-28 15:47:06.233   930   955 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-28 15:47:06.249  3679  3679 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-28 15:47:06.252  5869  5869 D BluetoothMapAppObserver: onReceive
10-28 15:47:06.252  5869  5869 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-28 15:47:06.253   930  2990 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-28 15:47:06.260  4091  4187 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-28 15:47:06.293  3679  6010 I Keyboard.Facilitator.DecoderInitializer: run()
,10-28 15:47:06.294  3386  6012 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-28 15:47:06.298  3810  3810 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-28 15:47:06.312    17    17 W kworker/2:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-28 15:47:06.313  3571  3571 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
10-28 15:47:06.313  3571  3571 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-28 15:47:06.312    17    17 W kworker/2:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-28 15:47:06.321  3679  6010 I Decoder : createOrResetDecoder
,10-28 15:47:06.321  3828  3937 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-28 15:47:06.322   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-28 15:47:06.325    17    17 W kworker/2:0: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-28 15:47:06.333   930  3179 I ActivityManager: Start proc 6016:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
10-28 15:47:06.334  3828  3937 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-28 15:47:06.334  3828  3937 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3828
10-28 15:47:06.334  3828  3937 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:47:06.334  3828  3937 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-28 15:47:06.338   930  3838 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-28 15:47:06.343   930  6022 E DropBoxManagerService: Can't write: system_app_crash
10-28 15:47:06.343   930  6022 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
10-28 15:47:06.343   930  6022 E DropBoxManagerService: 	... 8 more
,10-28 15:47:06.343  3828  3937 I Process : Sending signal. PID: 3828 SIG: 9
,10-28 15:47:06.346  3882  6028 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-28 15:47:06.346  3882  6028 D AccountUtils: Clearing selected account for com.test.thalitest
,10-28 15:47:06.364  3882  6028 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-28 15:47:06.393  3882  6028 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:47:06.393  3882  6028 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:47:06.393  3882  6028 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-28 15:47:06.394  3882  6028 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,10-28 15:47:06.399  3571  3571 I ConfigService: onCreate
,10-28 15:47:06.401  3571  6034 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-28 15:47:06.401  3571  6034 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-28 15:47:06.401  3571  6034 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,10-28 15:47:06.404  3571  6034 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-28 15:47:06.416  3679  6010 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-28 15:47:06.432  3386  3433 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjB4F04B9E0) - 
,10-28 15:47:06.458  3386  3433 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-28 15:47:06.458  3386  3433 E AndroidRuntime: Process: android.process.acore, PID: 3386
10-28 15:47:06.458  3386  3433 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:47:06.458  3386  3433 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-28 15:47:06.493  3386  3433 I Process : Sending signal. PID: 3386 SIG: 9
,10-28 15:47:06.501  3882  6039 I GMPM-SVC: App measurement is starting up
,10-28 15:47:06.506  3882  6039 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-28 15:47:06.507  3882  6039 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-28 15:47:06.539   930  3179 D GraphicsStats: Buffer count: 1
,10-28 15:47:06.539   930  3594 I WindowState: WIN DEATH: Window{72ca073 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,10-28 15:47:06.545   930  3407 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3828) has died
,10-28 15:47:06.546   930  3407 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-28 15:47:06.547   930  3407 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-28 15:47:06.564   930   943 I ActivityManager: Start proc 6042:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-28 15:47:06.606  6042  6042 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:47:06.606  6042  6042 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-28 15:47:06.607  6042  6042 D AndroidRuntime: Shutting down VM
10-28 15:47:06.612  6042  6042 E AndroidRuntime: FATAL EXCEPTION: main
10-28 15:47:06.612  6042  6042 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6042
10-28 15:47:06.612  6042  6042 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-28 15:47:06.612  6042  6042 E AndroidRuntime: 	... 10 more
10-28 15:47:06.615   930  3594 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-28 15:47:06.615  6042  6042 I Process : Sending signal. PID: 6042 SIG: 9
10-28 15:47:06.626   930  3407 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6042) has died
10-28 15:47:06.628   930  3407 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
10-28 15:47:06.642   930   943 I ActivityManager: Start proc 6056:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-28 15:47:06.687  6056  6056 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:47:06.687  6056  6056 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:47:06.687  6056  6056 D AndroidRuntime: Shutting down VM
,10-28 15:47:06.693  6056  6056 E AndroidRuntime: FATAL EXCEPTION: main
10-28 15:47:06.693  6056  6056 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6056
10-28 15:47:06.693  6056  6056 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-28 15:47:06.693  6056  6056 E AndroidRuntime: 	... 10 more
,10-28 15:47:06.696   930  3222 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-28 15:47:06.697  6056  6056 I Process : Sending signal. PID: 6056 SIG: 9

```
