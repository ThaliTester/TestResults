#### Test 91479574323a717_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-30 17:47:15.574  5368  5411 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
10-30 17:47:15.609  3818  3818 I ConfigFetchService: fetch service done; releasing wakelock
10-30 17:47:15.610  3818  3818 I ConfigFetchService: stopping self
10-30 17:47:15.632  5368  5411 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
10-30 17:47:15.640  3818  4626 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
10-30 17:47:15.710  3818  4626 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
10-30 17:47:15.735  5368  5411 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
--------- beginning of system
10-30 17:47:17.095   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-30 17:47:17.705   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:18.237  5423  5423 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-30 17:47:18.243  5423  5423 D AndroidRuntime: CheckJNI is OFF
10-30 17:47:18.272  5423  5423 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-30 17:47:18.307  5423  5423 I Radio-JNI: register_android_hardware_Radio DONE
10-30 17:47:18.325  5423  5423 D AndroidRuntime: Calling main entry com.android.commands.am.Am
10-30 17:47:18.331   927   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-30 17:47:18.385   927   938 I ActivityManager: Start proc 5432:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-30 17:47:18.393  5423  5423 D AndroidRuntime: Shutting down VM
,10-30 17:47:18.706   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:18.743   927  3656 I WindowManager: Screenshot max retries 4 of Token{11b3503 ActivityRecord{f0851b2 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{104650a u0 Starting com.test.thalitest} drawState=4
,10-30 17:47:18.812  5432  5432 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-30 17:47:18.835  5432  5432 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-30 17:47:18.901  5432  5432 I LibraryLoader: Time to load native libraries: 63 ms (timestamps 4993-5056)
,10-30 17:47:18.901  5432  5432 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-30 17:47:18.926  5432  5432 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bbfe2ff}
,10-30 17:47:18.926  5432  5432 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-30 17:47:18.927  5432  5432 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-30 17:47:18.930  5432  5432 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-30 17:47:18.931  5432  5432 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-30 17:47:18.988  5432  5432 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-30 17:47:19.002  5432  5432 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-30 17:47:19.002  5432  5432 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-30 17:47:19.002  5432  5432 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-30 17:47:19.002  5432  5432 I Adreno  : Build Date                       : 12/06/15
10-30 17:47:19.002  5432  5432 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-30 17:47:19.002  5432  5432 I Adreno  : Local Branch                     : mybranch17112971
10-30 17:47:19.002  5432  5432 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-30 17:47:19.002  5432  5432 I Adreno  : Remote Branch                    : NONE
10-30 17:47:19.002  5432  5432 I Adreno  : Reconstruct Branch               : NOTHING
,10-30 17:47:19.033   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@200ac29:true
,10-30 17:47:19.067  3332  3332 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[14054]" dev="sockfs" ino=14054 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-30 17:47:19.067  3332  3332 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14054]" dev="sockfs" ino=14054 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-30 17:47:19.077  5432  5432 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-30 17:47:19.086  5432  5432 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-30 17:47:19.107  3332  3332 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32854]" dev="sockfs" ino=32854 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-30 17:47:19.110  5432  5469 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-30 17:47:19.107  3332  3332 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32854]" dev="sockfs" ino=32854 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-30 17:47:19.110  3024  3024 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[24265]" dev="sockfs" ino=24265 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-30 17:47:19.110  3024  3024 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[24265]" dev="sockfs" ino=24265 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-30 17:47:19.116  5432  5456 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-30 17:47:19.138  5432  5469 I OpenGLRenderer: Initialized EGL, version 1.4
,10-30 17:47:19.213   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +470ms (total +856ms)
,10-30 17:47:19.250  5432  5432 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5432
,10-30 17:47:19.329  5432  5432 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-30 17:47:19.472  5432  5471 D jxcore_app_log: JniHelper::setJavaVM(0xf4e3c000), pthread_self() = -585369296
,10-30 17:47:19.476  5432  5471 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-30 17:47:19.476  5432  5471 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-30 17:47:19.476  5432  5471 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-30 17:47:19.476  5432  5471 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-30 17:47:19.476  5432  5471 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-30 17:47:19.476  5432  5471 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1c9342 added. We now have 1 listener(s)
,10-30 17:47:19.479  5432  5471 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
10-30 17:47:19.479  5432  5471 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:47:19.480  5432  5471 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:47:19.480  5432  5471 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-30 17:47:19.482  5432  5471 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@596bd89 added. We now have 1 listener(s)
,10-30 17:47:19.482  5432  5471 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-30 17:47:19.487   927  2834 D WifiService: New client listening to asynchronous messages
,10-30 17:47:19.487  5432  5471 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-30 17:47:19.487  5432  5471 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-30 17:47:19.487  5432  5471 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
10-30 17:47:19.487  5432  5471 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-30 17:47:19.487  5432  5471 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,10-30 17:47:19.487  5432  5471 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-30 17:47:19.488  5432  5471 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,10-30 17:47:19.489  5432  5471 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:47:19.489  5432  5471 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-30 17:47:19.493  5432  5471 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-30 17:47:19.493  5432  5471 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:47:19.493  5432  5471 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:47:19.493  5432  5471 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:47:19.493  5432  5471 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:47:19.493  5432  5471 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:47:19.493  5432  5471 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:19.493  5432  5471 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:47:19.493  5432  5471 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:47:19.493  5432  5471 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-30 17:47:19.494  5432  5471 D io.jxcore.node.ConnectivityMonitor: start: OK
10-30 17:47:19.494  5432  5471 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-30 17:47:19.603  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:47:19.610  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:47:19.614  5432  5432 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-30 17:47:19.707   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:19.774  5432  5441 I art     : Background sticky concurrent mark sweep GC freed 86716(8MB) AllocSpace objects, 17(1096KB) LOS objects, 20% free, 25MB/32MB, paused 2.187ms total 109.361ms
,10-30 17:47:20.095  5432  5479 W jxcore-log: Initializing JXcore engine
,10-30 17:47:20.095  5432  5479 W jxcore-log: JXcore engine is ready
,10-30 17:47:20.120  5479  5479 W Thread-58: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12404 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-30 17:47:20.120  5479  5479 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[13541]" dev="sockfs" ino=13541 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-30 17:47:20.120  5479  5479 W Thread-58: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=708 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-30 17:47:20.120  5479  5479 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30993]" dev="sockfs" ino=30993 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-30 17:47:20.128  5432  5479 W jxcore-log: Starting JXcore engine
,10-30 17:47:20.178  5432  5479 W jxcore-log: Platform android
10-30 17:47:20.178  5432  5479 W jxcore-log: 
,10-30 17:47:20.178  5432  5479 W jxcore-log: Process ARCH arm
10-30 17:47:20.178  5432  5479 W jxcore-log: 
,10-30 17:47:20.361  5432  5479 I jxcore-log: JXcore Cordova bridge is ready!
10-30 17:47:20.361  5432  5479 I jxcore-log: 
,10-30 17:47:20.361  5432  5479 W jxcore-log: JXcore engine is started
,10-30 17:47:20.375  5432  5471 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-30 17:47:20.383  5432  5432 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-30 17:47:20.620  3463  3463 I ConfigService: onDestroy
,10-30 17:47:20.708   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:21.709   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:22.709   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-30 17:47:26.169   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-30 17:47:29.131  3463  5481 I VacuumService: Vacuum at: now=1477864049131 tag=VacuumService
,10-30 17:47:29.152  3463  5484 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-30 17:47:29.180  4522  4578 D Finsky  : [176] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-30 17:47:29.183  4522  4522 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-30 17:47:29.189  3463  5482 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-30 17:47:29.191  3463  5482 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-30 17:47:29.222  3463  5482 W Uploader:  no longer exists, so no auth token.
,10-30 17:47:29.227  3463  5484 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-30 17:47:29.749  3463  5490 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-30 17:47:29.816  3463  5482 W Uploader:  no longer exists, so no auth token.
,10-30 17:47:29.827  3463  5492 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-30 17:47:29.929  3463  5490 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-30 17:47:29.974  5432  5479 I jxcore-log: 2016-10-30 21:47:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-30 17:47:29.974  5432  5479 I jxcore-log: 
,10-30 17:47:29.975  5432  5479 I jxcore-log: 2016-10-30 21:47:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-30 17:47:29.975  5432  5479 I jxcore-log: 
,10-30 17:47:29.978  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:47:29.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:47:29.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:47:29.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:47:29.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:47:29.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:29.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:47:29.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-30 17:47:29.979  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-30 17:47:29.980  5432  5479 I jxcore-log: 2016-10-30 21:47:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-30 17:47:29.980  5432  5479 I jxcore-log: 
,10-30 17:47:29.981  5432  5479 I jxcore-log: 2016-10-30 21:47:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-30 17:47:29.981  5432  5479 I jxcore-log: 
,10-30 17:47:30.223  5432  5479 I jxcore-log: 2016-10-30 21:47:30 - DEBUG UnitTest_app: 'Running unit tests'
10-30 17:47:30.223  5432  5479 I jxcore-log: 
,10-30 17:47:30.224  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:47:30.224  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a6a040 added. We now have 2 listener(s)
10-30 17:47:30.225  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-30 17:47:30.225  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:47:30.225  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:47:30.225  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:47:30.225  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b45eb79 added. We now have 2 listener(s)
10-30 17:47:30.225  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:47:30.226  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-30 17:47:30.228  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:47:30.231  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:47:30.231  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:47:30.231  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:47:30.231  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:47:30.231  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:47:30.231  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:30.231  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:47:30.231  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:47:30.232  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:30.232  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
10-30 17:47:30.232  5432  5479 D executeNativeTests: Running unit tests
,10-30 17:47:30.239  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:47:30.245  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:47:30.270  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-30 17:47:30.270  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f added. We now have 3 listener(s)
,10-30 17:47:30.271  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-30 17:47:30.271  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-30 17:47:30.271  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:47:30.271  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-30 17:47:30.271  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c added. We now have 3 listener(s)
10-30 17:47:30.271  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:47:30.271  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-30 17:47:30.273  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-30 17:47:30.276  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:47:30.276  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:47:30.276  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:47:30.276  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:47:30.276  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:47:30.276  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:30.276  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:47:30.276  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:47:30.276  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:30.276  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-30 17:47:30.278  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-30 17:47:30.278  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-30 17:47:30.278  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-30 17:47:30.278  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-30 17:47:30.279  5432  5479 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-30 17:47:30.279  5432  5479 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-30 17:47:30.279  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-30 17:47:30.279  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-30 17:47:30.279  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-30 17:47:30.279  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-30 17:47:30.279  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:30.279  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:30.279  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:30.279  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:30.279  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:30.279  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:47:30.280  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:30.280  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:47:30.280  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f removed from the list
,10-30 17:47:30.280  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:30.280  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c removed from the list
,10-30 17:47:30.281  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:47:30.286  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:47:30.286  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:30.286  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:30.287  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:30.287  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:30.287  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.287  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.287  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.287  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.287  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:30.287  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:30.288  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:47:30.288  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:30.288  5432  5479 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-30 17:47:30.289  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:30.289  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:30.289  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:30.289  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:30.289  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:30.289  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:30.289  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:30.289  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:30.289  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:30.289  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:30.289  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
,10-30 17:47:30.289  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:30.289  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:30.289  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:30.289  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:30.289  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.290  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.290  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.290  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:30.290  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:30.290  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:30.290  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:30.290  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:30.292  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-30 17:47:30.292  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-30 17:47:30.292  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-30 17:47:30.292  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-30 17:47:30.292  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,10-30 17:47:30.292  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-30 17:47:30.292  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-30 17:47:30.293  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-30 17:47:30.293  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:30.293  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:30.293  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:30.293  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-30 17:47:30.293  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:30.293  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:30.293  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-30 17:47:30.293  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:30.294  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:30.294  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:30.294  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
,10-30 17:47:30.294  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:30.294  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:30.294  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:30.294  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:30.294  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.294  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.294  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.294  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.294  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:30.294  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-30 17:47:30.295  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:30.295  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:30.295  5432  5479 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-30 17:47:30.296  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-30 17:47:30.298  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:47:30.298  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:47:30.298  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:47:30.298  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:47:30.298  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:47:30.298  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:30.298  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:47:30.298  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:47:30.299  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:30.299  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
10-30 17:47:30.299  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-30 17:47:30.299  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-30 17:47:30.299  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-30 17:47:30.299  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:47:30.299  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-30 17:47:30.301  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-30 17:47:30.301  5432  5479 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-30 17:47:30.301  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-30 17:47:30.302  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:47:30.303  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.304  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-30 17:47:30.305  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:47:30.305  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-30 17:47:30.306  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-30 17:47:30.307  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-30 17:47:30.308  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-30 17:47:30.308  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.308  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-30 17:47:30.308  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-30 17:47:30.308  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-30 17:47:30.308  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-30 17:47:30.308  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.309  5432  5479 D BluetoothAdapter: STATE_ON
10-30 17:47:30.311  4101  4306 D BtGatt.GattService: registerClient() - UUID=b9aef094-0cf1-41e0-9fa9-9234ffeb64c2
10-30 17:47:30.311  4101  4142 D BtGatt.GattService: onClientRegistered() - UUID=b9aef094-0cf1-41e0-9fa9-9234ffeb64c2, clientIf=5
10-30 17:47:30.312  5432  5442 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-30 17:47:30.315  4101  4115 D BtGatt.GattService: start scan with filters
10-30 17:47:30.321  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-30 17:47:30.321  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.322  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-30 17:47:30.322  4101  4160 D BtGatt.ScanManager: handling starting scan
10-30 17:47:30.322  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.322  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-30 17:47:30.322  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-30 17:47:30.322  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-30 17:47:30.322  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-30 17:47:30.322  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-30 17:47:30.322  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.322  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-30 17:47:30.323  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:47:30.323  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-30 17:47:30.323  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-30 17:47:30.323  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.323  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.323  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:30.323  5432  5479 I io.jxcore.node.ConnectionHelper: start: OK
10-30 17:47:30.323  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-30 17:47:30.325  4101  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:47:30.326  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:47:30.326  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:47:30.326  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:30.326  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:30.326  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:47:30.327  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:47:30.332  4101  4142 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-30 17:47:30.332  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:30.333  4101  4160 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-30 17:47:30.338  4101  4142 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-30 17:47:30.338  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:30.339  4101  4160 D BtGatt.ScanManager: Starting BLE batch scan
10-30 17:47:30.339  4101  4160 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-30 17:47:30.348  4101  4142 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-30 17:47:30.348  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:47:30.353  4101  4142 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-30 17:47:30.353  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:47:30.828  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-30 17:47:30.829  5432  5432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:47:30.829  5432  5432 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-30 17:47:32.211   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-30 17:47:34.285   927  2825 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-30 17:47:35.327  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-30 17:47:35.328  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-30 17:47:35.328  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-30 17:47:35.328  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:47:35.328  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-30 17:47:35.328  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-30 17:47:35.328  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-30 17:47:35.328  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-30 17:47:35.328  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-30 17:47:35.329  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-30 17:47:35.330  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:35.330  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.330  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.330  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-30 17:47:35.330  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.331  5432  5479 D BluetoothAdapter: STATE_ON
10-30 17:47:35.332  4101  4112 D BtGatt.GattService: stopScan() - queue size =1
10-30 17:47:35.333  4101  4296 D BtGatt.GattService: unregisterClient() - clientIf=5
10-30 17:47:35.334  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-30 17:47:35.334  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.334  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-30 17:47:35.334  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.334  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.335  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:35.335  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.335  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-30 17:47:35.335  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:35.335  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.336  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.336  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-30 17:47:35.336  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-30 17:47:35.337  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:47:35.337  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.338  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.338  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:47:35.339  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:35.339  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:35.339  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:35.339  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:35.339  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:47:35.339  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-30 17:47:35.339  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:35.339  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:35.339  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-30 17:47:35.340  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:35.340  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:35.340  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
,10-30 17:47:35.340  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:35.340  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-30 17:47:35.340  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,10-30 17:47:35.340  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-30 17:47:35.340  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-30 17:47:35.341  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:47:35.341  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,10-30 17:47:35.341  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-30 17:47:35.341  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-30 17:47:35.345  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:47:35.345  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:35.345  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,10-30 17:47:35.345  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:47:35.346  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:47:35.346  4101  4101 D BtGatt.ScanManager: awakened up at time 161501
,10-30 17:47:35.350  4101  4142 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-30 17:47:35.350  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:35.351  4101  4160 D BtGatt.ScanManager: stopping BLe Batch
10-30 17:47:35.360  4101  4142 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-30 17:47:35.360  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:35.360  4101  4160 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-30 17:47:35.380  4101  4142 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,10-30 17:47:35.380  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:35.380  4101  4142 D BtGatt.GattService: current time is 161535997230
10-30 17:47:35.381  4101  4142 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -85, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -79, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -88, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-30 17:47:35.382  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-30 17:47:35.383  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-30 17:47:35.383  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-30 17:47:35.383  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-30 17:47:35.847  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-30 17:47:37.711   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:38.712   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:39.713   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:40.341  5432  5479 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-30 17:47:40.344  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-30 17:47:40.350  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:47:40.350  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:47:40.350  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:47:40.350  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:47:40.350  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:47:40.350  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:40.350  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:47:40.350  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-30 17:47:40.353  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:40.353  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
10-30 17:47:40.353  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:47:40.353  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-30 17:47:40.353  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-30 17:47:40.353  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-30 17:47:40.353  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-30 17:47:40.357  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:47:40.361  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:47:40.362  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-30 17:47:40.362  5432  5479 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-30 17:47:40.362  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-30 17:47:40.370  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.371  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-30 17:47:40.372  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-30 17:47:40.373  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-30 17:47:40.380  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.380  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-30 17:47:40.381  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-30 17:47:40.381  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-30 17:47:40.382  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-30 17:47:40.382  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.383  5432  5479 D BluetoothAdapter: STATE_ON
,10-30 17:47:40.388  4101  4304 D BtGatt.GattService: registerClient() - UUID=ef29c514-5022-4a3b-865a-dd08929c7fe0
,10-30 17:47:40.389  4101  4142 D BtGatt.GattService: onClientRegistered() - UUID=ef29c514-5022-4a3b-865a-dd08929c7fe0, clientIf=5
,10-30 17:47:40.390  5432  5443 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-30 17:47:40.390  4101  4112 D BtGatt.GattService: start scan with filters
,10-30 17:47:40.396  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-30 17:47:40.396  4101  4160 D BtGatt.ScanManager: handling starting scan
,10-30 17:47:40.396  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.396  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-30 17:47:40.396  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.397  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-30 17:47:40.397  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-30 17:47:40.397  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.397  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-30 17:47:40.397  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-30 17:47:40.397  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.397  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.397  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-30 17:47:40.400  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-30 17:47:40.401  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.406  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.406  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:47:40.406  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.406  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.406  5432  5479 I io.jxcore.node.ConnectionHelper: start: OK
10-30 17:47:40.406  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.408  4101  4142 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-30 17:47:40.408  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:47:40.409  4101  4160 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-30 17:47:40.411  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:40.411  5432  5479 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-30 17:47:40.411  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-30 17:47:40.411  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-30 17:47:40.411  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.411  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:40.412  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-30 17:47:40.412  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.412  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:40.412  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.412  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-30 17:47:40.412  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,10-30 17:47:40.412  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-30 17:47:40.412  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-30 17:47:40.412  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:47:40.412  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-30 17:47:40.412  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.412  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.412  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.412  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-30 17:47:40.413  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.414  5432  5479 D BluetoothAdapter: STATE_ON
10-30 17:47:40.415  4101  4306 D BtGatt.GattService: stopScan() - queue size =1
10-30 17:47:40.416  4101  4115 D BtGatt.GattService: unregisterClient() - clientIf=5
10-30 17:47:40.416  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-30 17:47:40.416  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.416  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-30 17:47:40.417  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.417  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.417  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.417  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.417  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-30 17:47:40.417  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.417  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.417  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.417  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-30 17:47:40.418  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-30 17:47:40.418  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:47:40.419  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.421  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.421  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:47:40.422  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.422  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.423  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:40.423  4101  4142 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-30 17:47:40.423  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:40.423  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:40.423  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:47:40.423  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:40.423  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:47:40.423  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:40.423  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:40.423  4101  4160 D BtGatt.ScanManager: Starting BLE batch scan
10-30 17:47:40.423  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:47:40.423  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:40.423  4101  4160 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-30 17:47:40.423  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:40.423  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-30 17:47:40.423  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:40.423  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.424  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-30 17:47:40.424  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-30 17:47:40.424  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.424  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:40.424  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.424  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:40.424  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-30 17:47:40.424  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: ,Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.425  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.426  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.426  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.426  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:40.426  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:40.426  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:40.426  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
,10-30 17:47:40.426  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.427  5432  5479 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-30 17:47:40.427  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-30 17:47:40.428  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.428  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.428  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.428  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:47:40.431  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:47:40.436  4101  4142 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-30 17:47:40.436  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:47:40.436  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:47:40.436  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:47:40.436  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:47:40.436  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:47:40.436  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:47:40.436  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:40.436  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:47:40.436  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-30 17:47:40.440  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:47:40.440  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
10-30 17:47:40.440  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:47:40.440  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-30 17:47:40.441  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-30 17:47:40.441  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:47:40.441  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-30 17:47:40.443  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:47:40.443  4101  4142 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-30 17:47:40.443  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:40.445  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-30 17:47:40.445  5432  5479 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-30 17:47:40.445  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-30 17:47:40.446  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:47:40.449  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.449  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-30 17:47:40.450  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-30 17:47:40.451  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-30 17:47:40.451  4101  4142 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-30 17:47:40.452  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:47:40.452  4101  4160 D BtGatt.ScanManager: stopping BLe Batch
,10-30 17:47:40.459  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.459  4101  4142 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-30 17:47:40.459  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-30 17:47:40.459  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:40.459  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-30 17:47:40.459  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-30 17:47:40.459  4101  4160 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-30 17:47:40.459  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-30 17:47:40.459  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.460  5432  5479 D BluetoothAdapter: STATE_ON
,10-30 17:47:40.463  4101  4115 D BtGatt.GattService: registerClient() - UUID=15563daa-3fde-4724-88d8-9d248e0a5010
,10-30 17:47:40.464  4101  4142 D BtGatt.GattService: onClientRegistered() - UUID=15563daa-3fde-4724-88d8-9d248e0a5010, clientIf=5
,10-30 17:47:40.464  5432  5443 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-30 17:47:40.465  4101  4304 D BtGatt.GattService: start scan with filters
10-30 17:47:40.466  4101  4142 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-30 17:47:40.466  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:47:40.468  4101  4160 D BtGatt.ScanManager: handling starting scan
10-30 17:47:40.468  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-30 17:47:40.468  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.468  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-30 17:47:40.469  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.469  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-30 17:47:40.469  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-30 17:47:40.469  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,10-30 17:47:40.469  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-30 17:47:40.469  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-30 17:47:40.469  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.469  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.469  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-30 17:47:40.470  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-30 17:47:40.471  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:40.473  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.474  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:47:40.474  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.474  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:40.474  5432  5479 I io.jxcore.node.ConnectionHelper: start: OK
10-30 17:47:40.474  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-30 17:47:40.477  4101  4142 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-30 17:47:40.477  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:40.478  4101  4160 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-30 17:47:40.478  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.479  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-30 17:47:40.479  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.479  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:47:40.479  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-30 17:47:40.484  4101  4142 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-30 17:47:40.484  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:40.484  4101  4160 D BtGatt.ScanManager: Starting BLE batch scan
,10-30 17:47:40.484  4101  4160 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-30 17:47:40.493  4101  4142 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-30 17:47:40.493  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:47:40.499  4101  4142 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-30 17:47:40.499  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:47:40.715   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:40.980  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-30 17:47:40.981  5432  5432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:47:40.981  5432  5432 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-30 17:47:41.286   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-30 17:47:41.291   927  2839 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-30 17:47:41.716   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:47:42.717   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-30 17:47:44.313   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-30 17:47:44.321   927  2839 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-30 17:47:45.474  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-30 17:47:45.475  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:45.475  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-30 17:47:45.475  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:45.475  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-30 17:47:45.475  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:45.476  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-30 17:47:45.476  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-30 17:47:45.476  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-30 17:47:45.476  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-30 17:47:45.476  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:45.477  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.477  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.477  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-30 17:47:45.477  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.479  5432  5479 D BluetoothAdapter: STATE_ON
,10-30 17:47:45.481  4101  4304 D BtGatt.GattService: stopScan() - queue size =1
10-30 17:47:45.483  4101  4296 D BtGatt.GattService: unregisterClient() - clientIf=5
10-30 17:47:45.484  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-30 17:47:45.484  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.484  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-30 17:47:45.484  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.485  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.485  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.485  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.485  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-30 17:47:45.485  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.486  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.486  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.486  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-30 17:47:45.486  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-30 17:47:45.487  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:47:45.488  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.490  4101  4101 D BtGatt.ScanManager: awakened up at time 171645
10-30 17:47:45.491  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.491  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:47:45.491  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.492  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:45.492  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:47:45.493  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:47:45.493   927  3666 I ActivityManager: Killing 4757:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,10-30 17:47:45.493  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-30 17:47:45.493  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-30 17:47:45.494  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-30 17:47:45.494  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-30 17:47:45.494  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-30 17:47:45.494  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-30 17:47:45.494  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-30 17:47:45.494  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-30 17:47:45.496  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:47:45.496  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:45.496  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:47:45.496  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:47:45.496  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-30 17:47:45.523  4101  4142 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-30 17:47:45.523  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:45.523  4101  4160 D BtGatt.ScanManager: stopping BLe Batch
,10-30 17:47:45.529  4101  4142 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-30 17:47:45.530  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:47:45.530  4101  4160 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-30 17:47:45.544  4101  4142 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-30 17:47:45.544  4101  4142 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:47:45.544  4101  4142 D BtGatt.GattService: current time is 171699855801
10-30 17:47:45.545  4101  4142 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -83, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-30 17:47:45.545  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-30 17:47:45.545  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-30 17:47:45.545  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-30 17:47:45.546  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-30 17:47:45.546  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-30 17:47:45.546  4101  4142 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-30 17:47:45.997  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-30 17:47:45.997  5432  5432 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-30 17:47:45.997  5432  5432 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-30 17:47:47.347   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-30 17:47:48.406   927  5197 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174560, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-30 17:47:50.374   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-30 17:47:50.493  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-30 17:47:50.493  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:50.493  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-30 17:47:50.493  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:50.494  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.494  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:47:50.494  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-30 17:47:50.494  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.494  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.495  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
,10-30 17:47:50.495  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.495  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.496  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.496  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:50.497  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.499  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.499  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.500  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.500  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:50.500  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-30 17:47:50.500  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.500  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.502  5432  5479 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-30 17:47:50.504  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:50.504  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-30 17:47:50.504  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:50.505  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:50.506  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.506  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.506  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-30 17:47:50.507  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.507  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.507  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.507  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.507  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:47:50.507  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.507  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.508  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.508  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:50.511  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.512  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.512  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.512  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:50.513  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:50.513  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:47:50.513  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.517  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-30 17:47:50.517  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:50.517  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:50.518  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-30 17:47:50.518  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:50.518  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.518  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:50.518  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:50.519  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.519  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.519  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
,10-30 17:47:50.519  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.519  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.520  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.520  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.520  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.520  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:50.525  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.525  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.525  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.526  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-30 17:47:50.526  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:50.526  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.526  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
,10-30 17:47:50.528  5432  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-30 17:47:50.529  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-30 17:47:50.529  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:50.529  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:50.529  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:50.530  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.530  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.530  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-30 17:47:50.530  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.530  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.531  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.531  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.531  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.531  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.531  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.531  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:50.532  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:50.535  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:50.535  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.535  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.535  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:50.535  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:50.535  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:47:50.536  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.537  5432  5479 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-30 17:47:50.537  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:50.537  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:50.537  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:50.537  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-30 17:47:50.538  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.538  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.538  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:50.538  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.538  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.538  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.538  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.538  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:47:50.538  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.539  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.539  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.539  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.541  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.542  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.542  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.542  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:50.542  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-30 17:47:50.542  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.542  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
,10-30 17:47:50.544  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-30 17:47:50.545  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-30 17:47:50.545  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-30 17:47:50.545  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-30 17:47:50.545  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-30 17:47:50.545  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-30 17:47:50.545  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-30 17:47:50.545  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-30 17:47:50.546  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-30 17:47:50.546  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:50.546  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:50.546  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:50.546  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-30 17:47:50.546  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.546  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.547  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:50.547  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.547  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.547  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.547  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.547  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.547  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.547  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.547  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.548  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.550  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.550  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:50.550  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.550  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:50.550  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:50.550  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.550  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.552  5432  5479 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-30 17:47:50.552  5432  5479 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-30 17:47:50.552  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-30 17:47:50.557  5432  5479 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-30 17:47:50.558  5432  5479 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,10-30 17:47:50.558  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-30 17:47:50.558  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-30 17:47:50.558  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-30 17:47:50.558  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-30 17:47:50.558  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,10-30 17:47:50.558  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-30 17:47:50.558  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-30 17:47:50.558  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-30 17:47:50.559  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-30 17:47:50.560  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-30 17:47:50.561  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-30 17:47:50.561  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-30 17:47:50.561  5432  5479 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-30 17:47:50.562  5432  5479 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-30 17:47:50.562  5432  5479 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,10-30 17:47:50.562  5432  5479 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-30 17:47:50.562  5432  5479 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-30 17:47:50.562  5432  5479 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,10-30 17:47:50.562  5432  5479 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-30 17:47:50.562  5432  5479 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-30 17:47:50.563  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-30 17:47:50.567  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-30 17:47:50.568  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-30 17:47:50.568  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,10-30 17:47:50.569  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-30 17:47:50.569  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-30 17:47:50.569  5432  5479 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-30 17:47:50.569  5432  5479 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-30 17:47:50.569  5432  5479 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-30 17:47:50.569  5432  5493 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 122)
10-30 17:47:50.569  5432  5493 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-30 17:47:50.570  5432  5493 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-30 17:47:50.570  5432  5493 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-30 17:47:50.570  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:50.570  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:50.570  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:50.570  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:50.571  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.571  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.571  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-30 17:47:50.571  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-30 17:47:50.573  5432  5493 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-30 17:47:50.573  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.573  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.573  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.573  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.573  5432  5493 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-30 17:47:50.573  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.574  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.574  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.574  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.574  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.574  5432  5494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 122
10-30 17:47:50.574  5432  5494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
10-30 17:47:50.574  5432  5494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 122)
10-30 17:47:50.574  5432  5494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 122)
10-30 17:47:50.575  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.575  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.575  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.574  4296  4296 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33083]" dev="sockfs" ino=33083 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-30 17:47:50.574  4296  4296 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33083]" dev="sockfs" ino=33083 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-30 17:47:50.575  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:50.575  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:50.575  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.575  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.576  5432  5479 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-30 17:47:50.576  5432  5493 E org.thaliproject.p2p.btconnectorlib.internal.bluetoo,th.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-30 17:47:50.576  5432  5493 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-30 17:47:50.577  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:50.577  5432  5493 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 122)
10-30 17:47:50.577  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:50.577  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:50.577  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:50.577  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.577  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.577  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:50.577  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.577  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:47:50.577  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.577  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.577  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.577  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.577  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.577  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.577  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.579  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.579  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:50.579  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.579  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:50.579  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:50.579  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.579  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.580  5432  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-30 17:47:50.580  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:50.580  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-30 17:47:50.580  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:50.580  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:50.580  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.580  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.580  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:50.581  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.581  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:47:50.581  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.581  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.581  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.581  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.581  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.581  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.581  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.582  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.582  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:50.582  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.582  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:50.582  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:50.582  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.582  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.583  5432  5479 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-30 17:47:50.583  5432  5479 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,10-30 17:47:50.583  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-30 17:47:50.583  5432  5479 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-30 17:47:50.583  5432  5479 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-30 17:47:50.583  5432  5479 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-30 17:47:50.583  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-30 17:47:50.583  5432  5479 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-30 17:47:50.583  5432  5479 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,10-30 17:47:50.583  5432  5479 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-30 17:47:50.584  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-30 17:47:50.584  5432  5479 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-30 17:47:50.584  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:50.584  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:50.584  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:50.584  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-30 17:47:50.584  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.584  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.584  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:50.584  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.584  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.584  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.584  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.584  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:47:50.584  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.584  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.584  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:50.584  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.586  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.586  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:50.586  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:50.586  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:50.586  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:50.586  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.586  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.586  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:50.586  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:50.586  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:50.587  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:50.587  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:50.587  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:50.587  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:50.587  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:50.587  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:47:50.587  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:55.588  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:47:55.588  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.588  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-30 17:47:55.588  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.589  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:55.589  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:55.589  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
,10-30 17:47:55.589  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:55.589  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-30 17:47:55.590  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:55.590  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-30 17:47:55.590  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.590  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.590  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:55.590  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:55.591  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:47:55.591  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.591  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:55.591  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.591  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.591  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.591  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.592  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.595  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.595  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.596  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.596  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:55.596  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:55.596  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.596  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.600  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-30 17:47:55.601  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-30 17:47:55.603  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-30 17:47:55.605  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-30 17:47:55.605  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-30 17:47:55.605  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-30 17:47:55.606  5432  5495 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-30 17:47:55.606  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-30 17:47:55.606  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-30 17:47:55.606  5432  5432 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-30 17:47:55.607  5432  5495 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-30 17:47:55.608  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:55.608  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-30 17:47:55.608  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-30 17:47:55.609  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-30 17:47:55.609  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.609  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-30 17:47:55.609  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-30 17:47:55.609  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
,10-30 17:47:55.609  5432  5432 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-30 17:47:55.609  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.609  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-30 17:47:55.609  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-30 17:47:55.609  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-30 17:47:55.610  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.610  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.610  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.610  4304  4304 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31054]" dev="sockfs" ino=31054 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-30 17:47:55.610  4304  4304 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31054]" dev="sockfs" ino=31054 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-30 17:47:55.612  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.612  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:47:55.612  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:55.612  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.612  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.612  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:47:55.613  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:47:55.613  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-30 17:47:55.613  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:47:55.613  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:55.613  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:55.613  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:55.613  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:47:55.613  5432  5495 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-30 17:47:55.613  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.613  5432  5495 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-30 17:47:55.613  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-30 17:47:55.613  5432  5495 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-30 17:47:55.614  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:55.614  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.614  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.614  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:55.614  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:47:55.614  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.614  5432  5432 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-30 17:47:55.614  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.614  5432  5432 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:55.614  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:55.614  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.616  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.617  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.617  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:55.617  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:55.617  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:55.617  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.617  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
,10-30 17:47:55.619  5432  5479 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,10-30 17:47:55.619  5432  5479 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-30 17:47:55.620  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-30 17:47:55.620  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-30 17:47:55.620  5432  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-30 17:47:55.620  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-30 17:47:55.620  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:55.620  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-30 17:47:55.620  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:55.621  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.621  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.621  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-30 17:47:55.621  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:55.621  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.621  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.621  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:55.621  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.621  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.622  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:47:55.622  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.622  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:55.625  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:55.625  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.625  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.625  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:55.626  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:55.626  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.626  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.631  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-30 17:47:55.631  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:55.631  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:55.631  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:47:55.631  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.631  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.632  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-30 17:47:55.632  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
10-30 17:47:55.632  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.632  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.632  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
,10-30 17:47:55.632  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.632  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.632  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.632  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:47:55.632  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.633  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.634  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.634  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.634  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:47:55.634  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-30 17:47:55.634  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.634  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.636  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:47:55.636  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:47:55.636  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:47:55.636  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-30 17:47:55.636  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.636  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.637  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:47:55.637  5432  5479 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff8e40f not in the list
,10-30 17:47:55.637  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.637  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.637  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:47:55.637  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:47:55.637  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.637  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:47:55.637  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:47:55.637  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:47:55.639  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.639  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.639  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:47:55.639  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-30 17:47:55.639  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:47:55.639  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:47:55.639  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50fdc9c not in the list
10-30 17:47:55.640  5432  5479 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,10-30 17:47:55.641  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-30 17:47:55.641  5432  5479 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-30 17:47:55.641  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-30 17:47:55.641  5432  5479 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,10-30 17:47:55.641  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-30 17:47:55.643  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-30 17:47:55.644  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-30 17:47:55.644  5432  5479 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-30 17:47:55.644  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-30 17:47:55.644  5432  5479 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-30 17:47:55.645  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-30 17:47:55.645  5432  5479 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,10-30 17:47:55.645  5432  5479 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-30 17:47:55.645  5432  5479 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-30 17:47:55.645  5432  5479 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-30 17:47:55.646  5432  5479 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-30 17:47:55.646  5432  5479 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-30 17:47:55.646  5432  5479 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,10-30 17:47:55.646  5432  5479 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-30 17:47:55.647  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:47:55.648  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee1061e added. We now have 3 listener(s)
10-30 17:47:55.649  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-30 17:47:55.651  5432  5479 D BluetoothAdapter: enable(): BT is already enabled..!
,10-30 17:47:55.651   927  3666 D WifiService: setWifiEnabled: true pid=5432, uid=10077
10-30 17:47:55.651   927  3666 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-30 17:47:55.703  4101  4270 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-30 17:47:55.703  4101  4292 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-30 17:47:56.113  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-30 17:47:59.438   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-30 17:48:00.657  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-30 17:48:00.658  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee0eeff added. We now have 4 listener(s)
,10-30 17:48:00.658  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-30 17:48:00.670  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:48:00.670  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee0eeff removed from the list
10-30 17:48:00.670  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:48:00.670  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:48:00.670  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:00.672  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:00.673  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d1a4cc added. We now have 4 listener(s)
,10-30 17:48:00.673  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-30 17:48:00.677  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:48:00.677  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d1a4cc removed from the list
10-30 17:48:00.678  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:48:00.678  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:00.678  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:48:00.680  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:00.680  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9418315 added. We now have 4 listener(s)
,10-30 17:48:00.680  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:00.684   927  3292 D WifiService: setWifiEnabled: false pid=5432, uid=10077
10-30 17:48:00.685   927  3292 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-30 17:48:00.689   927  2825 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-30 17:48:00.689   927  2825 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-30 17:48:00.689   927  2825 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-30 17:48:00.690   927  2825 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-30 17:48:00.695  4101  4138 D BluetoothAdapterState: Current state: ON, message: 23
10-30 17:48:00.695  4101  4138 D BluetoothAdapterProperties: Setting state to 13
10-30 17:48:00.695  4101  4138 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-30 17:48:00.696  4101  4138 D BluetoothAdapterProperties: onBluetoothDisable()
10-30 17:48:00.697  4101  4138 I BluetoothAdapterState: Entering PendingCommandState
10-30 17:48:00.699  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:48:00.701  4101  4142 D BluetoothAdapterProperties: Scan Mode:20
,10-30 17:48:00.704  4101  4101 D BluetoothMapService: onReceive
,10-30 17:48:00.705  4101  4101 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-30 17:48:00.705  4101  4101 D BluetoothMapService: STATE_TURNING_OFF
10-30 17:48:00.705  4101  4138 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-30 17:48:00.705  4101  4101 D BluetoothMapService: MAP Service closeService in
10-30 17:48:00.705  4101  4101 D BluetoothMapMasInstance0: MAP Service shutdown
10-30 17:48:00.705  4101  4101 D ObexServerSockets0: shutdown(block = true)
10-30 17:48:00.706  4101  4101 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-30 17:48:00.706  4101  4101 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-30 17:48:00.706  4101  4307 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,10-30 17:48:00.707  4101  4308 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-30 17:48:00.707  4101  4292 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-30 17:48:00.707  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.707  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:48:00.707  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.707  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.707  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:00.707  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.707  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:00.707  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:00.707  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:48:00.708  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-30 17:48:00.708  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-30 17:48:00.708  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
10-30 17:48:00.712  4101  4101 I BtOppRfcommListener: stopping Accept Thread
10-30 17:48:00.713  4101  5126 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-30 17:48:00.713  4101  5126 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-30 17:48:00.715  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.716   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-30 17:48:00.718   927  5198 D DhcpClient: Clearing IP address
10-30 17:48:00.718  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.722  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-30 17:48:00.722  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.722  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.722  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.722  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:00.722  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.722  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:00.722  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:00.722  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:48:00.723  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.723  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:00.723   507   921 D CommandListener: Setting iface cfg
,10-30 17:48:00.724   927   940 I ActivityManager: Start proc 5499:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-30 17:48:00.726   927  5199 D DhcpClient: Receive thread stopped
,10-30 17:48:00.727  4101  4101 D HeadsetService: Received stop request...Stopping profile...
10-30 17:48:00.729   927   927 D BluetoothHeadset: Proxy object disconnected
10-30 17:48:00.730  3632  3644 D BluetoothHeadset: Proxy object disconnected
,10-30 17:48:00.731  3463  5254 V NativeCrypto: Read error: ssl=0x7f7a77a180: I/O error during system call, Connection timed out
10-30 17:48:00.731   927   927 D BluetoothHeadset: Proxy object disconnected
10-30 17:48:00.731   927   927 D BluetoothHeadset: Proxy object disconnected
10-30 17:48:00.732  2992  3007 D BluetoothHeadset: Proxy object disconnected
10-30 17:48:00.733  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.733  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.733  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.733  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.733  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:00.733  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.733  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:00.733  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:00.733  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:48:00.733  3463  5254 V NativeCrypto: SSL shutdown failed: ssl=0x7f7a77a180: I/O error during system call, Broken pipe
10-30 17:48:00.734  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.734  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:00.736  4101  4101 D A2dpService: Received stop request...Stopping profile...
10-30 17:48:00.737  4101  4299 D A2dpStateMachine: Exit Disconnected: -1
10-30 17:48:00.737  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.738   927   927 D BluetoothA2dp: Proxy object disconnected
10-30 17:48:00.739  2992  2992 D HeadsetProfile: Bluetooth service disconnected
10-30 17:48:00.739   927  3666 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-30 17:48:00.739   927  2839 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-30 17:48:00.739  2992  2992 D BluetoothA2dp: Proxy object disconnected
,10-30 17:48:00.739   927  5196 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-30 17:48:00.739   927  2839 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-30 17:48:00.740  4101  4101 D HidService: Received stop request...Stopping profile...
10-30 17:48:00.740  4101  4101 D HidService: Stopping Bluetooth HidService
10-30 17:48:00.742   927  5196 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-30 17:48:00.742  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.742  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.742  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.742  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.742  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:00.742  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.742  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:00.742  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:00.742  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:48:00.743  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.743  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:00.744   533   533 E Parcel  : Reading a NULL string not supported here.
10-30 17:48:00.745  4101  4101 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:00.745  4101  4101 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:00.745  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:00.745  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:00.746   927   927 D RttService: SCAN_AVAILABLE : 1
10-30 17:48:00.746  2992  2992 D BluetoothInputDevice: Proxy object disconnected
10-30 17:48:00.746  2992  2992 D HidProfile: Bluetooth service disconnected
10-30 17:48:00.746   927  2932 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-30 17:48:00.746  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.746  4101  4101 D HealthService: Received stop request...Stopping profile...
10-30 17:48:00.746  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.746  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.746  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.746  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:00.746  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.746  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:00.746  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:00.746  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - act,ive network type is Wi-Fi: true
10-30 17:48:00.750  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.750  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:00.751  4101  4101 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-30 17:48:00.751  4101  4101 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-30 17:48:00.751  4101  4142 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-30 17:48:00.751  4101  4270 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:00.752  4101  4270 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:00.752  4101  4270 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:00.752  4101  4142 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-30 17:48:00.752  4101  4101 D PanService: Received stop request...Stopping profile...
10-30 17:48:00.753  4101  4101 D BluetoothMapService: Received stop request...Stopping profile...
10-30 17:48:00.753  4101  4101 D BluetoothMapService: stop()
10-30 17:48:00.753  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.753  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.753  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.753  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.753  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:00.753  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.753  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:00.753  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:00.753  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:48:00.753  4101  4101 D BluetoothMapAppObserver: deinitObservers()
10-30 17:48:00.753  4101  4101 D BluetoothMapAppObserver: removeReceiver()
10-30 17:48:00.754  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.754  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:00.754  4101  4101 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:00.754  4101  4101 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:00.755  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:00.755  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
,10-30 17:48:00.755   927  2839 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-30 17:48:00.756  4101  4142 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-30 17:48:00.757  4101  4270 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-30 17:48:00.757  4101  4270 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:00.757  4101  4270 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-30 17:48:00.757  4101  4270 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-30 17:48:00.757  4101  4270 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-30 17:48:00.757  4101  4270 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-30 17:48:00.757  3602  3736 W QCNEJ   : |CORE| network lost: 100
10-30 17:48:00.758  3602  3736 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-30 17:48:00.758  4101  4101 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:00.758  4101  4101 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:00.758  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:00.758  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:00.759  4101  4101 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-30 17:48:00.759  4101  4101 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-30 17:48:00.759  4101  4142 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-30 17:48:00.759  4101  4101 D SapService: Received stop request...Stopping profile...
10-30 17:48:00.759  4101  4101 V SapService: stop()
10-30 17:48:00.761  4101  4101 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:00.761  4101  4101 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:00.761  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:00.761  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
,10-30 17:48:00.761  4101  4101 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,10-30 17:48:00.761  4101  4142 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-30 17:48:00.762  4101  4101 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-30 17:48:00.762  4101  4101 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:00.762  4101  4101 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:00.762  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:00.762  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:00.762  4101  4101 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-30 17:48:00.762  4101  4101 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-30 17:48:00.766  4101  4101 D BluetoothMapService: MAP Service closeService in
,10-30 17:48:00.767   927  2825 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-30 17:48:00.768  4101  4101 V BluetoothAdapterState: isTurningOff()=true
,10-30 17:48:00.768  4101  4101 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:00.768  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:00.768  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:00.768  4101  4101 D BluetoothMapService: cleanup()
10-30 17:48:00.768  4101  4101 D BluetoothMapService: MAP Service closeService in
10-30 17:48:00.769  4101  4101 V BluetoothAdapterState: isTurningOff()=true
,10-30 17:48:00.769  4101  4101 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:00.769  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:00.769  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
,10-30 17:48:00.769  4101  4138 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-30 17:48:00.769  4101  4138 D BluetoothAdapterProperties: Setting state to 15
10-30 17:48:00.769  4101  4138 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-30 17:48:00.769  4101  4138 I BluetoothAdapterState: Entering BleOnState
10-30 17:48:00.770  3632  3880 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:00.770  2992  3007 D BluetoothMap: onBluetoothStateChange: up=false
10-30 17:48:00.771   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:00.771   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:00.771  2992  3011 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:00.772  2992  3850 D BluetoothA2dp: onBluetoothStateChange: up=false
10-30 17:48:00.772  2992  3007 D BluetoothPbap: onBluetoothStateChange: up=false
10-30 17:48:00.773  2992  3011 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-30 17:48:00.774  2992  3850 D BluetoothPan: onBluetoothStateChange on: false
10-30 17:48:00.774   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-30 17:48:00.775   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:00.775  4101  4138 D BluetoothAdapterState: Current state: BLE ON, message: 20
,10-30 17:48:00.775  4101  4138 D BluetoothAdapterProperties: Setting state to 16
10-30 17:48:00.775  4101  4138 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-30 17:48:00.776  4101  4138 D BluetoothAdapterProperties: onBleDisable
10-30 17:48:00.776  4101  4138 I BluetoothAdapterState: Entering PendingCommandState
10-30 17:48:00.776  4101  4139 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-30 17:48:00.777  4101  4142 D BluetoothAdapterProperties: Scan Mode:20
10-30 17:48:00.777  4101  4270 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-30 17:48:00.777  4101  4270 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:00.780  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.780  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.780  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.780  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.780  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:00.780  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.780  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:00.780  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:00.780  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:00.782   927  2825 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-30 17:48:00.786   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-30 17:48:00.788  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.788  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.788  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.788  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.788  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:00.788  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.788  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:00.788  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:00.788  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:00.792  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.792  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.792  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.792  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.792  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:00.792  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.792  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:00.792  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:00.792  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-30 17:48:00.794  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.797  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.798  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:00.808  5499  5499 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-30 17:48:00.810   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-30 17:48:00.810   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-30 17:48:00.811   507   921 D TetherController: Setting IP forward enable = 0
10-30 17:48:00.812   927  2839 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-30 17:48:00.812   927  2839 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-30 17:48:00.813   927  2825 D DhcpClient: doQuit
10-30 17:48:00.813   927  2825 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-30 17:48:00.813   927  5198 D DhcpClient: onQuitting
10-30 17:48:00.814  3328  3328 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-30 17:48:00.816   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-30 17:48:00.820  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-30 17:48:00.820  3790  3790 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-30 17:48:00.820  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.820  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.820  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.820  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:00.820  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.820  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:00.820  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:00.820  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-30 17:48:00.818  5067  5067 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@82a6fdb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-30 17:48:00.823  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.823  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:00.823  4743  4761 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-30 17:48:00.824  4743  4761 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-30 17:48:00.824  4743  4761 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-30 17:48:00.824  4743  4761 E SarControlService: no key has been found,reset the power
10-30 17:48:00.824  4743  4782 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-30 17:48:00.824  4743  4782 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-30 17:48:00.824  4743  4782 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-30 17:48:00.825  4770  4770 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-30 17:48:00.825  4770  4770 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-30 17:48:00.826  4743  4782 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-30 17:48:00.826  4743  4782 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-30 17:48:00.826  4743  4782 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-30 17:48:00.827  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.827  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.827  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.827  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.827  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:00.827  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.827  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:00.827  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:00.827  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:00.827  4770  4770 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-30 17:48:00.827  4770  4770 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-30 17:48:00.827  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.828  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:00.830  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.830  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:00.830  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:00.830  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:00.830  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:00.830  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:00.830  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:00.830  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:00.830  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:00.830  4770  4784 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88b6e59 HexData = [00000000ea03000000000000ffffffff]
10-30 17:48:00.830  4770  4784 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-30 17:48:00.830  4770  4784 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-30 17:48:00.830  4770  4770 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-30 17:48:00.831  4743  4754 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-30 17:48:00.831  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:00.831  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:00.832  4770  4784 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88b6e59 HexData = [00000000eb03000000000000ffffffff]
10-30 17:48:00.832  4770  4784 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-30 17:48:00.832  4770  4784 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-30 17:48:00.832  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.833  4770  4770 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-30 17:48:00.833  4743  4755 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-30 17:48:00.834  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.836  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.837  3328  3328 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-30 17:48:00.838  5499  5499 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-30 17:48:00.840  3328  3328 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-30 17:48:00.841   507   914 W SocketClient: write error (Broken pipe)
10-30 17:48:00.841   507   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-30 17:48:00.841   507   914 W SocketListener: Error sending broadcast (Broken pipe)
,10-30 17:48:00.845   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d4e1b7a:true
,10-30 17:48:00.847  3463  3463 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-30 17:48:00.860   927  3666 I ActivityManager: Start proc 5530:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-30 17:48:00.863   507   921 E Netd    : netlink response contains error (No such file or directory)
,10-30 17:48:00.864   507   921 D TetherController: Setting IP forward enable = 0
,10-30 17:48:00.865   927  2839 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-30 17:48:00.866  3328  3328 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-30 17:48:00.881  3328  3328 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-30 17:48:00.885  5499  5499 D LocalBluetoothProfileManager: Adding local MAP profile
,10-30 17:48:00.897  5499  5499 D BluetoothMap: Create BluetoothMap proxy object
,10-30 17:48:00.907  5530  5530 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-30 17:48:00.912  5499  5499 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-30 17:48:00.923  5499  5499 D DockEventReceiver: finishStartingService: stopping service
,10-30 17:48:00.934   927  3024 I ActivityManager: Killing 4650:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-30 17:48:00.984  4101  4142 I bt_hci  : shut_down
,10-30 17:48:00.988  4274  4274 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-30 17:48:00.989   927  2825 D wifi    : In wifi stop Hal
10-30 17:48:00.989   927  2825 D wifi    : halHandle = 0x7f66586080, mVM = 0x7f809cd140, mCls = 0x100a12
10-30 17:48:00.989   927  3326 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-30 17:48:00.989   927  3326 D WifiHAL : Got a signal to exit!!!
,10-30 17:48:00.989   927  3326 I WifiHAL : Exit wifi_event_loop
10-30 17:48:00.989  4101  4162 D bt_hwcfg: hw_epilog_process
10-30 17:48:00.989   927  2825 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
,10-30 17:48:00.989  4101  4162 I bt_vendor: low_power_mode_cb
10-30 17:48:00.990   927  2825 E WifiHAL : Event processing terminated
10-30 17:48:00.990   927  2825 D wifi    : In wifi cleaned up handler
10-30 17:48:00.990   927  2825 I WifiHAL : Internal cleanup completed
,10-30 17:48:00.991  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:00.991  3975  4117 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-30 17:48:00.992  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.993  4101  4162 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-30 17:48:00.993  4101  4162 I bt_vendor: epilog_cb
10-30 17:48:00.993  4101  4162 I bt_hci  : epilog_finished_callback
10-30 17:48:00.993  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:00.994  4101  4142 I bt_hci_h4: hal_close
10-30 17:48:00.995  4101  4142 I bt_userial_vendor: device fd = 54 close
,10-30 17:48:01.014   927  3326 D wifi    : set interface wlan0 flags (DOWN)
,10-30 17:48:01.014   927  2825 D WifiNative-HAL: HAL event thread stopped successfully
,10-30 17:48:01.097  5530  5530 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at java.io.File.exists(File.java:361)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-30 17:48:01.097  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-30 17:48:01.101  4101  4139 D bt_stack_manager: event_shut_down_stack finished.
,10-30 17:48:01.105  4101  4138 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-30 17:48:01.106  4101  4138 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-30 17:48:01.107  4101  4101 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-30 17:48:01.107  4101  4101 D BtGatt.GattService: Received stop request...Stopping profile...
,10-30 17:48:01.107  4101  4101 D BtGatt.GattService: stop()
10-30 17:48:01.107  4101  4101 D BtGatt.AdvertiseManager: advertise clients cleared
10-30 17:48:01.109  4101  4101 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:01.109  4101  4101 V BluetoothAdapterState: isTurningOn()=false
,10-30 17:48:01.109  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:01.109  4101  4101 V BluetoothAdapterState: isBleTurningOff()=true
10-30 17:48:01.109  4101  4138 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-30 17:48:01.109  4101  4138 D BluetoothAdapterProperties: Setting state to 10
10-30 17:48:01.109  4101  4138 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-30 17:48:01.109  5530  5530 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-30 17:48:01.109  5530  5530 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-30 17:48:01.109  5530  5530 D Str,ictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-30 17:48:01.109  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-30 17:48:01.110  5530  5530 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-30 17:48:01.110  5530  5530 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.r.e.b(PG:170)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-30 17:48:01.110  5530  5530 D, StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-30 17:48:01.110  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-30 17:48:01.110  4101  4138 I BluetoothAdapterState: Entering OffState
10-30 17:48:01.110   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-30 17:48:01.128  4101  4101 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-30 17:48:01.128  4101  4101 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-30 17:48:01.128  4101  4101 I BluetoothServiceJni: cleanupNative: return from cleanup
10-30 17:48:01.130  4101  4139 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-30 17:48:01.131  5530  5530 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-30 17:48:01.131  5530  5530 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.r.k.d(PG:583)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.r.e.b(PG:170)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-30 17:48:01.131  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-30 17:48:01.132  5530  5530 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at java.io.File.exists(File.java:361)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-30 17:48:01.132  5530  5530 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at java.io.File.exists(File.java:361)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-30 17:48:01.132  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-30 17:48:01.133  5530  5530 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-30 17:48:01.133  5530  5530 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-30 17:48:01.133  5530  5530 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-30 17:48:01.142  5499  5499 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-30 17:48:01.144  4101  4139 D bt_stack_manager: event_clean_up_stack finished.
,10-30 17:48:01.159  4101  4101 I art     : System.exit called, status: 0
10-30 17:48:01.159  4101  4101 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-30 17:48:01.166  5499  5499 D DockEventReceiver: finishStartingService: stopping service
10-30 17:48:01.167   927  3656 I ActivityManager: Killing 5067:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-30 17:48:01.213   927  3026 I ActivityManager: Process com.android.bluetooth (pid 4101) has died
,10-30 17:48:01.215  3463  3463 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-30 17:48:01.217   927   944 D Tethering: InitialState.processMessage what=4
,10-30 17:48:01.229   927   938 I ActivityManager: Start proc 5564:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,10-30 17:48:01.230   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-30 17:48:01.296  5564  5564 D AdapterServiceConfig: Adding HeadsetService
10-30 17:48:01.296  5564  5564 D AdapterServiceConfig: Adding A2dpService
10-30 17:48:01.296  5564  5564 D AdapterServiceConfig: Adding HidService
10-30 17:48:01.296  5564  5564 D AdapterServiceConfig: Adding HealthService
10-30 17:48:01.296  5564  5564 D AdapterServiceConfig: Adding PanService
10-30 17:48:01.296  5564  5564 D AdapterServiceConfig: Adding GattService
10-30 17:48:01.297  5564  5564 D AdapterServiceConfig: Adding BluetoothMapService
10-30 17:48:01.297  5564  5564 D AdapterServiceConfig: Adding SapService
,10-30 17:48:01.300   927   938 I ActivityManager: Killing 5225:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-30 17:48:01.329  3818  3818 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-30 17:48:01.332  3818  3818 D SystemUpdateService: onCreate
,10-30 17:48:01.336  3818  3818 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-30 17:48:01.345  3818  3818 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-30 17:48:01.349  3818  5222 I iu.UploadsManager: num queued entries: 0
,10-30 17:48:01.350  3818  5222 I iu.UploadsManager: num updated entries: 0
10-30 17:48:01.350  3818  5222 I iu.SyncManager: NEXT; no task
,10-30 17:48:01.357  3818  5576 I SystemUpdateService: active receiver: enabled
,10-30 17:48:01.359  3818  3818 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-30 17:48:01.360  3818  3818 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-30 17:48:01.367  3818  5576 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-30 17:48:01.372  3818  5576 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-30 17:48:01.372  3818  5576 I SystemUpdateService: now status is 0 (complete)
10-30 17:48:01.372  3818  5576 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-30 17:48:01.372  3818  5576 I SystemUpdateService: file has been verified
10-30 17:48:01.372  3818  5576 I SystemUpdateService: OTA package size = 21989297
10-30 17:48:01.373   927  3024 I ActivityManager: Start proc 5578:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-30 17:48:01.386  3818  5576 I SystemUpdateService: showing system update notification
,10-30 17:48:01.409  5578  5578 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-30 17:48:01.416  5578  5578 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-30 17:48:01.429  5578  5578 D SprintDMHelper: simOperator: 
,10-30 17:48:01.429  5578  5578 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-30 17:48:01.436  3818  3818 D SystemUpdateService: onDestroy
,10-30 17:48:01.445  4274  5590 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-30 17:48:01.458   927  3026 I ActivityManager: Start proc 5591:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
10-30 17:48:01.461   927   938 I ActivityManager: Killing 4428:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-30 17:48:01.507  5591  5591 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-30 17:48:01.517   927  3279 I ActivityManager: Killing 5309:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-30 17:48:01.553  5530  5554 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-30 17:48:01.567   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4e3b085:true
,10-30 17:48:02.718   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:03.719   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:04.720   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:05.713   927   937 D WifiService: setWifiEnabled: true pid=5432, uid=10077
,10-30 17:48:05.713   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-30 17:48:05.721   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:05.722   507   921 D SoftapController: Softap fwReload - Ok
,10-30 17:48:05.727   507   921 D CommandListener: Setting iface cfg
10-30 17:48:05.728   507   921 D CommandListener: Trying to bring down wlan0
10-30 17:48:05.730   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-30 17:48:05.735   927  2825 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-30 17:48:06.304   927  2825 D wifi    : set interface wlan0 flags (UP)
,10-30 17:48:06.309   927  2825 I WifiHAL : Initializing wifi
10-30 17:48:06.309   927  2825 I WifiHAL : Creating socket
10-30 17:48:06.310   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-30 17:48:06.311   927  2825 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-30 17:48:06.312   927  2825 D wifi    : Did set static halHandle = 0x7f66586080
,10-30 17:48:06.312   927  2825 D wifi    : halHandle = 0x7f66586080, mVM = 0x7f809cd140, mCls = 0x190a
,10-30 17:48:06.312   927  2825 D wifi    : array field set
,10-30 17:48:06.312   927  2825 I WifiNative-HAL: interface[0] = wlan0
10-30 17:48:06.315   927  5608 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547177914496
10-30 17:48:06.315   927  5608 D wifi    : waitForHalEvents called, vm = 0x7f809cd140, obj = 0x190a, env = 0x7f65b3f340
10-30 17:48:06.320   927  2825 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
10-30 17:48:06.323   927  2825 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
10-30 17:48:06.328  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:06.329  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:06.330  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:06.385  5609  5609 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-30 17:48:06.400  5609  5609 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-30 17:48:06.434  5609  5609 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-30 17:48:06.434  5609  5609 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-30 17:48:06.722   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:07.334  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-30 17:48:07.335  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:07.335  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:07.335  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:07.335  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:07.335  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:07.335  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:07.335  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:07.335  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:07.335  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:07.335  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:07.336   927  2825 D WifiConfigStore: Loading config and enabling all networks 
10-30 17:48:07.337  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:07.337  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:07.337  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:07.337  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:07.337  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:07.337  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:07.337  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:07.337  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:07.337  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:07.337  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-30 17:48:07.337  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:07.338  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:07.339  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:07.339  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:07.339  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:07.339  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:07.339  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:07.339  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:07.339  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:07.339  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:07.339  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:07.339  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-30 17:48:07.355   927  2825 D WifiConfigStore: loaded 0 passpoint configs
,10-30 17:48:07.356   927  2825 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-30 17:48:07.357   927  2825 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-30 17:48:07.358   927  2825 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-30 17:48:07.359   927  2825 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-30 17:48:07.360   927  2825 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-30 17:48:07.360   927  2825 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-30 17:48:07.360   927  2825 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-30 17:48:07.364   927  2825 D WifiNative-HAL: Setting external_sim to 1
10-30 17:48:07.364  4274  4274 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-30 17:48:07.364   927  2825 D wifi    : setting dfs flag to true, 0x7f68670b00
10-30 17:48:07.365   927  2825 D WifiStateMachine: Setting OUI to DA-A1-19
10-30 17:48:07.365   927  2825 D wifi    : setting scan oui 0x7f68670b00
10-30 17:48:07.365   927  2825 D WifiHAL : Sending mac address OUI
,10-30 17:48:07.369   927  2825 E native  : do suspend false
,10-30 17:48:07.378   927  2825 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-30 17:48:07.378   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-30 17:48:07.378   927   927 D RttService: SCAN_AVAILABLE : 3
10-30 17:48:07.378   927  2932 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-30 17:48:07.379   507   921 D CommandListener: Setting iface cfg
,10-30 17:48:07.383   927  2812 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
10-30 17:48:07.383   927  2812 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-30 17:48:07.394   927  2812 D WifiNative-HAL: p2pGetDeviceAddress
,10-30 17:48:07.398   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=193554 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-30 17:48:07.399   927  2812 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-30 17:48:07.722   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-30 17:48:10.479  5609  5609 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-30 17:48:10.492  5609  5609 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-30 17:48:10.500  5609  5609 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-30 17:48:10.539   927  2825 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-30 17:48:10.540   927  2825 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-30 17:48:10.540   927  2825 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-30 17:48:10.553   927  2825 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-30 17:48:10.587   927  2825 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-30 17:48:10.589  5609  5609 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-30 17:48:10.720   927  3026 D WifiService: setWifiEnabled: false pid=5432, uid=10077
,10-30 17:48:10.720   927  3026 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-30 17:48:10.726   927   927 D RttService: SCAN_AVAILABLE : 1
10-30 17:48:10.727   927  2932 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-30 17:48:10.743   927  2825 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-30 17:48:10.744   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-30 17:48:10.752   927  2825 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-30 17:48:10.754  5609  5609 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-30 17:48:10.766  5609  5609 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-30 17:48:10.767  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-30 17:48:10.767  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:10.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:10.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:10.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:10.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:10.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:10.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:10.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:10.767  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:10.767  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:10.769  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:10.769  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:10.769  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:10.769  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:10.769  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:10.769  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:10.769  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:10.769  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:10.769  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:10.769  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:10.769  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:10.770  5609  5609 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,10-30 17:48:10.770  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:10.771  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:10.771  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:10.771  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:10.771  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:10.771  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:10.771  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:10.771  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:10.771  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:10.771  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:10.771  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-30 17:48:10.787  5609  5609 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-30 17:48:10.792  5609  5609 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-30 17:48:10.800  4274  4274 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-30 17:48:10.800   927  2825 D wifi    : In wifi stop Hal
10-30 17:48:10.800   927  2825 D wifi    : halHandle = 0x7f66586080, mVM = 0x7f809cd140, mCls = 0x190a
10-30 17:48:10.802   927  5608 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-30 17:48:10.802   927  5608 D WifiHAL : Got a signal to exit!!!
10-30 17:48:10.802   927  5608 I WifiHAL : Exit wifi_event_loop
10-30 17:48:10.803  3975  4117 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-30 17:48:10.803   927  2825 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-30 17:48:10.804   927  2825 E WifiHAL : Event processing terminated
10-30 17:48:10.804   927  2825 D wifi    : In wifi cleaned up handler
,10-30 17:48:10.805   927  2825 I WifiHAL : Internal cleanup completed
10-30 17:48:10.806  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:10.807  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:10.808  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:10.850   927  5608 D wifi    : set interface wlan0 flags (DOWN)
,10-30 17:48:10.850   927  2825 D WifiNative-HAL: HAL event thread stopped successfully
,10-30 17:48:11.057   927   944 D Tethering: InitialState.processMessage what=4
,10-30 17:48:11.063   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-30 17:48:15.759   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dd6b28a:true
,10-30 17:48:15.760  5564  5564 D BluetoothAdapterState: make() - Creating AdapterState
,10-30 17:48:15.766  5564  5564 I bt_bluedroid: init
,10-30 17:48:15.768  5564  5613 I BluetoothAdapterState: Entering OffState
,10-30 17:48:15.773  5564  5614 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-30 17:48:15.773  5564  5614 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-30 17:48:15.774  5564  5614 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-30 17:48:15.774  5564  5614 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-30 17:48:15.775  5564  5564 I bt_bluedroid: get_profile_interface socket
,10-30 17:48:15.780  5564  5617 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-30 17:48:15.780  5564  5564 I bt_bluedroid: get_profile_interface sdp
,10-30 17:48:15.783  5564  5617 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-30 17:48:15.789  5564  5575 I bt_bluedroid: config_hci_snoop_log
,10-30 17:48:15.791   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-30 17:48:15.800  5564  5613 D BluetoothAdapterState: Current state: OFF, message: 0
,10-30 17:48:15.800  5564  5613 D BluetoothAdapterProperties: Setting state to 14
,10-30 17:48:15.801  5564  5613 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-30 17:48:15.804  5564  5613 D BluetoothBondStateMachine: make
,10-30 17:48:15.807  5564  5618 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-30 17:48:15.814  5564  5613 I BluetoothAdapterState: Entering PendingCommandState
,10-30 17:48:15.815  5564  5564 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-30 17:48:15.819  5564  5564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
,10-30 17:48:15.820  5564  5564 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-30 17:48:15.821  5564  5564 D BtGatt.GattService: Received start request. Starting profile...
10-30 17:48:15.821  5564  5564 D BtGatt.GattService: start()
10-30 17:48:15.821  5564  5564 I bt_bluedroid: get_profile_interface gatt
10-30 17:48:15.823  5564  5564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:15.823  5564  5564 D BtGatt.AdvertiseManager: advertise manager created
,10-30 17:48:15.832  5564  5564 V BluetoothAdapterState: isTurningOff()=false
,10-30 17:48:15.833  5564  5564 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:15.833  5564  5564 V BluetoothAdapterState: isBleTurningOn()=true
10-30 17:48:15.833  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:15.834  5564  5613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-30 17:48:15.836  5564  5613 I bt_bluedroid: bt_bluedroid
,10-30 17:48:15.837  5564  5614 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-30 17:48:15.837  5564  5614 I bt_hci  : start_up
,10-30 17:48:15.847  5564  5614 I bt_vendor: alloc value 0xf3a78871
,10-30 17:48:15.848  5564  5614 I bt_vendor: init
10-30 17:48:15.848  5564  5614 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-30 17:48:15.848  5564  5614 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-30 17:48:15.962  5564  5614 D bt_hci  : start_up starting async portion
,10-30 17:48:15.962  5564  5621 I bt_hci  : event_finish_startup
10-30 17:48:15.962  5564  5621 I bt_hci_h4: hal_open
10-30 17:48:15.963  5564  5621 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-30 17:48:15.960  5622  5622 W irq/448-msm_hs_: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-30 17:48:15.966  5564  5621 I bt_userial_vendor: device fd = 54 open
,10-30 17:48:15.983  5564  5621 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-30 17:48:15.987  5564  5621 D bt_hwcfg: Chipset BCM4358A3
,10-30 17:48:15.987  5564  5621 D bt_hwcfg: Target name = [BCM4358A3]
10-30 17:48:15.987  5564  5621 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-30 17:48:16.461  5564  5621 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-30 17:48:16.462  5564  5621 D bt_hwcfg: Settlement delay -- 100 ms
10-30 17:48:16.462  5564  5621 I bt_hwcfg: Setting fw settlement delay to 100 
,10-30 17:48:16.595  5564  5621 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-30 17:48:16.595  5564  5621 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-30 17:48:16.596  5564  5621 I bt_hwcfg: vendor lib fwcfg completed
,10-30 17:48:16.597  5564  5621 I bt_vendor: firmware callback
10-30 17:48:16.597  5564  5621 I bt_hci  : firmware_config_callback
,10-30 17:48:16.606  5564  5624 I bt_btu  : btu_task pending for preload complete event
10-30 17:48:16.606  5564  5624 I bt_btu_task: Bluetooth chip preload is complete
10-30 17:48:16.606  5564  5624 I bt_btu  : btu_task received preload complete event
,10-30 17:48:16.612  5564  5624 I         : BTE_InitTraceLevels -- TRC_HCI
,10-30 17:48:16.612  5564  5624 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-30 17:48:16.612  5564  5624 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-30 17:48:16.612  5564  5624 I         : BTE_InitTraceLevels -- TRC_AVDT
10-30 17:48:16.612  5564  5624 I         : BTE_InitTraceLevels -- TRC_AVRC
10-30 17:48:16.612  5564  5624 I         : BTE_InitTraceLevels -- TRC_A2D
,10-30 17:48:16.612  5564  5624 I         : BTE_InitTraceLevels -- TRC_BNEP
10-30 17:48:16.613  5564  5624 I         : BTE_InitTraceLevels -- TRC_BTM
10-30 17:48:16.613  5564  5624 I         : BTE_InitTraceLevels -- TRC_GAP
10-30 17:48:16.613  5564  5624 I         : BTE_InitTraceLevels -- TRC_PAN
10-30 17:48:16.613  5564  5624 I         : BTE_InitTraceLevels -- TRC_SDP
,10-30 17:48:16.613  5564  5624 I         : BTE_InitTraceLevels -- TRC_GATT
10-30 17:48:16.613  5564  5624 I         : BTE_InitTraceLevels -- TRC_SMP
10-30 17:48:16.613  5564  5624 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-30 17:48:16.613  5564  5624 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-30 17:48:16.697  5564  5624 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf39f6549
10-30 17:48:16.697  5564  5624 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf39f6549 
,10-30 17:48:16.714  5564  5617 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-30 17:48:16.715  5564  5617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-30 17:48:16.716  5564  5617 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6,
,10-30 17:48:16.720  5564  5617 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-30 17:48:16.725  5564  5617 D BluetoothAdapterProperties: Scan Mode:20
,10-30 17:48:16.725  5564  5617 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-30 17:48:16.728  5564  5617 D bt_hci  : do_postload posting postload work item
,10-30 17:48:16.728  5564  5621 I bt_hci  : event_postload
10-30 17:48:16.728  5564  5621 I bt_vendor: sco_config_cb
,10-30 17:48:16.728  5564  5621 I bt_hci  : sco_config_callback postload finished.
,10-30 17:48:16.731  5564  5617 D bt_bte_conf: Device ID record 1 : primary
10-30 17:48:16.731  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:16.731  5564  5617 D bt_bte_conf:   vendorId            = 000f
10-30 17:48:16.731  5564  5617 D bt_bte_conf:   vendorIdSource      = 0001
10-30 17:48:16.731  5564  5617 D bt_bte_conf:   product             = 1200
10-30 17:48:16.731  5564  5617 D bt_bte_conf:   version             = 1436
,10-30 17:48:16.731  5564  5617 D bt_bte_conf:   clientExecutableURL = 
10-30 17:48:16.732  5564  5617 D bt_bte_conf:   serviceDescription  = 
10-30 17:48:16.732  5564  5617 D bt_bte_conf:   documentationURL    = 
,10-30 17:48:16.732  5564  5617 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-30 17:48:16.733  5564  5614 D bt_stack_manager: event_start_up_stack finished
10-30 17:48:16.734  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:16.735  5564  5613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-30 17:48:16.735  5564  5613 D BluetoothAdapterProperties: Setting state to 15
10-30 17:48:16.735  5564  5613 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-30 17:48:16.736  5564  5613 I BluetoothAdapterState: Entering BleOnState
10-30 17:48:16.736  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:16.741  5564  5621 I bt_vendor: low_power_mode_cb
,10-30 17:48:16.741  5564  5613 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-30 17:48:16.741  5564  5613 D BluetoothAdapterProperties: Setting state to 11
10-30 17:48:16.741  5564  5613 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-30 17:48:16.748  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:16.751  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:16.753  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:16.754  5564  5564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
,10-30 17:48:16.757  5564  5564 D HeadsetService: Received start request. Starting profile...
10-30 17:48:16.759  5564  5564 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-30 17:48:16.760  5564  5564 D HeadsetStateMachine: make
,10-30 17:48:16.764  5564  5613 I BluetoothAdapterState: Entering PendingCommandState
,10-30 17:48:16.767  5564  5564 D HeadsetStateMachine: max_hf_connections = 1
,10-30 17:48:16.767  5564  5564 I bt_bluedroid: get_profile_interface handsfree
,10-30 17:48:16.767  5564  5617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-30 17:48:16.768  5564  5617 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
10-30 17:48:16.770  5564  5564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:16.771  5564  5564 D A2dpService: Received start request. Starting profile...
10-30 17:48:16.772  5564  5564 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-30 17:48:16.772  5564  5564 I bt_bluedroid: get_profile_interface avrcp
,10-30 17:48:16.777  5564  5564 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-30 17:48:16.778  5564  5564 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-30 17:48:16.778  5564  5564 D A2dpStateMachine: make
10-30 17:48:16.779  5564  5564 I bt_bluedroid: get_profile_interface a2dp
10-30 17:48:16.779  5564  5617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-30 17:48:16.781  5564  5633 D A2dpStateMachine: Enter Disconnected: -2
,10-30 17:48:16.782  5564  5564 I BluetoothHidServiceJni: classInitNative: succeeds
,10-30 17:48:16.783  5564  5564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:16.784  3463  3463 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-30 17:48:16.785  5564  5564 D HidService: Received start request. Starting profile...
,10-30 17:48:16.785  5564  5564 I bt_bluedroid: get_profile_interface hidhost
10-30 17:48:16.785  5564  5564 D HidService: setHidService(): set to: null
10-30 17:48:16.785  5564  5617 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf39d756d
10-30 17:48:16.786  5564  5617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-30 17:48:16.786  5564  5564 I BluetoothHealthServiceJni: classInitNative: succeeds
10-30 17:48:16.787  5564  5564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
,10-30 17:48:16.787  5499  5499 D BluetoothInputDevice: Proxy object connected
10-30 17:48:16.788  5564  5564 D HealthService: Received start request. Starting profile...
10-30 17:48:16.788  5499  5499 D HidProfile: Bluetooth service connected
,10-30 17:48:16.789  5564  5564 I bt_bluedroid: get_profile_interface health
,10-30 17:48:16.790  5564  5564 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-30 17:48:16.791  5564  5564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
,10-30 17:48:16.792  5499  5499 D BluetoothPan: BluetoothPAN Proxy object connected
,10-30 17:48:16.792  5564  5564 D PanService: Received start request. Starting profile...
10-30 17:48:16.792  5564  5564 D BluetoothPanServiceJni: initializeNative(L110): pan
10-30 17:48:16.792  5564  5564 I bt_bluedroid: get_profile_interface pan
10-30 17:48:16.793  5499  5499 D PanProfile: Bluetooth service connected
10-30 17:48:16.793  5564  5617 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-30 17:48:16.795  5564  5564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
,10-30 17:48:16.797  5499  5499 D BluetoothMap: Proxy object connected
,10-30 17:48:16.797  5499  5499 D MapProfile: Bluetooth service connected
10-30 17:48:16.798  5564  5564 D BluetoothMapService: Received start request. Starting profile...
10-30 17:48:16.798  5564  5564 D BluetoothMapService: start()
10-30 17:48:16.800  5564  5564 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-30 17:48:16.801  5564  5564 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-30 17:48:16.801  5564  5564 D BluetoothMapAppObserver: createReceiver()
10-30 17:48:16.802  5564  5564 D BluetoothMapAppObserver: initObservers()
10-30 17:48:16.803  5564  5564 D BluetoothMapAppObserver: getEnabledAccountItems()
10-30 17:48:16.809  5564  5564 V SapService: SapBinder()
10-30 17:48:16.809  5564  5564 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
,10-30 17:48:16.810  5564  5564 D SapService: Received start request. Starting profile...
10-30 17:48:16.810  5564  5564 V SapService: start()
10-30 17:48:16.798  5499  5499 D BluetoothMap: getConnectedDevices()
10-30 17:48:16.812  5499  5499 D BluetoothMap: Bluetooth is Not enabled
,10-30 17:48:16.813  5564  5564 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:16.813  5564  5564 V BluetoothAdapterState: isTurningOn()=true
,10-30 17:48:16.813  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:16.813  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:16.813  5564  5631 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-30 17:48:16.813  5564  5564 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:16.813  5564  5564 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:16.813  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:16.813  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
,10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:16.814  5564  5564 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isTurningOff()=false
,10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:16.815  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:16.816  5564  5613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-30 17:48:16.816  5564  5613 D BluetoothAdapterProperties: ScanMode =  20
10-30 17:48:16.816  5564  5613 D BluetoothAdapterProperties: State =  11
10-30 17:48:16.816  5564  5613 D BluetoothAdapterProperties: Setting state to 12
10-30 17:48:16.816  5564  5613 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-30 17:48:16.817  5564  5613 I BluetoothAdapterState: Entering OnState
10-30 17:48:16.817  3632  3644 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:16.818  5499  5517 D BluetoothPbap: onBluetoothStateChange: up=true
10-30 17:48:16.820  5564  5617 D BluetoothAdapterProperties: Scan Mode:21
10-30 17:48:16.820  2992  3007 D BluetoothMap: onBluetoothStateChange: up=true
10-30 17:48:16.820  5564  5617 D BluetoothAdapterProperties: Discoverable Timeout:120
10-30 17:48:16.821  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-30 17:48:16.822  2992  2992 D BluetoothMap: Proxy object connected
10-30 17:48:16.822  5499  5513 D BluetoothMap: onBluetoothStateChange: up=true
10-30 17:48:16.822  2992  2992 D MapProfile: Bluetooth service connected
10-30 17:48:16.822  2992  2992 D BluetoothMap: getConnectedDevices()
10-30 17:48:16.823   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:16.823   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:16.823  2992  3011 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-30 17:48:16.823  2992  3007 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-30 17:48:16.825  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:16.825  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:16.825  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:16.825  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:16.825  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:16.825  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:16.825  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:16.825  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:16.825  2992  3850 D BluetoothPbap: onBluetoothStateChange: up=true
10-30 17:48:16.826  2992  2992 D BluetoothA2dp: Proxy object connected
10-30 17:48:16.827  5499  5517 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-30 17:48:16.827  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:16.827  2992  3007 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-30 17:48:16.828  5564  5564 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-30 17:48:16.829  2992  2992 D BluetoothInputDevice: Proxy object connected
10-30 17:48:16.829  5564  5564 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-30 17:48:16.829  2992  2992 D HidProfile: Bluetooth service connected
,10-30 17:48:16.829  5499  5513 D BluetoothPan: onBluetoothStateChange on: true
10-30 17:48:16.829  2992  3850 D BluetoothPan: onBluetoothStateChange on: true
10-30 17:48:16.831  5564  5564 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-30 17:48:16.831  2992  2992 D BluetoothPan: BluetoothPAN Proxy object connected
10-30 17:48:16.831  2992  2992 D PanProfile: Bluetooth service connected
10-30 17:48:16.831   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-30 17:48:16.831  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:16.831  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:16.831  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:16.831  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:16.831  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:16.831  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:16.831  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:16.831  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:16.832   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:16.832   927   927 D BluetoothA2dp: Proxy object connected
,10-30 17:48:16.833  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:16.834  5564  5564 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-30 17:48:16.835   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-30 17:48:16.836  5499  5499 D LocalBluetoothProfileManager: Adding local A2DP profile
10-30 17:48:16.836  5564  5564 D ObexServerSockets: Succeed to create listening sockets 
,10-30 17:48:16.836  5564  5564 D ObexServerSockets0: startAccept()
10-30 17:48:16.836  5564  5564 D ObexServerSockets0: prepareForNewConnect()
10-30 17:48:16.839  5564  5639 D ObexServerSockets0: Accepting socket connection...
10-30 17:48:16.839  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:16.839  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:16.839  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:16.839  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:16.839  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:16.839  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:16.839  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:16.839  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:16.839  5564  5640 D ObexServerSockets0: Accepting socket connection...
,10-30 17:48:16.839  5564  5564 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-30 17:48:16.840  5564  5564 D BluetoothSdpJni: SDP Create record success - handle: 0
10-30 17:48:16.840  5564  5564 D BluetoothMapService: onReceive
10-30 17:48:16.840  5564  5564 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-30 17:48:16.840  5564  5564 D BluetoothMapService: STATE_ON
,10-30 17:48:16.841  5499  5499 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-30 17:48:16.843  5564  5641 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-30 17:48:16.843  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:16.844  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-30 17:48:16.845  5564  5641 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-30 17:48:16.845  5564  5641 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-30 17:48:16.847  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:16.849  5499  5499 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-30 17:48:16.849  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:16.850  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:16.851  5499  5499 D BluetoothA2dp: Proxy object connected
,10-30 17:48:16.855  3463  3463 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-30 17:48:16.859  5499  5499 D DockEventReceiver: finishStartingService: stopping service
,10-30 17:48:16.862  5499  5499 D BluetoothPbap: Proxy object connected
,10-30 17:48:16.862  5499  5499 D PbapServerProfile: Bluetooth service connected
,10-30 17:48:16.864  2992  2992 D BluetoothPbap: Proxy object connected
10-30 17:48:16.864  2992  2992 D PbapServerProfile: Bluetooth service connected
,10-30 17:48:16.868  5564  5564 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-30 17:48:16.868  5564  5564 D ObexServerSockets0: prepareForNewConnect()
10-30 17:48:16.871  5564  5645 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-30 17:48:16.884  5564  5649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-30 17:48:16.886  5564  5649 I BtOppRfcommListener: Accept thread started.
,10-30 17:48:16.919   927   927 D BluetoothHeadset: Proxy object connected
10-30 17:48:16.919  3632  3650 D BluetoothHeadset: Proxy object connected
,10-30 17:48:16.919   927   927 D BluetoothHeadset: Proxy object connected
10-30 17:48:16.919   927   927 D BluetoothHeadset: Proxy object connected
,10-30 17:48:16.920  2992  3850 D BluetoothHeadset: Proxy object connected
10-30 17:48:16.920  2992  2992 D HeadsetProfile: Bluetooth service connected
,10-30 17:48:16.923   927   944 D BluetoothHeadset: Proxy object connected
,10-30 17:48:16.923   927   944 D BluetoothHeadset: Proxy object connected
10-30 17:48:16.923  2992  3011 D BluetoothHeadset: Proxy object connected
10-30 17:48:16.923  2992  2992 D HeadsetProfile: Bluetooth service connected
,10-30 17:48:16.932   927   944 D BluetoothHeadset: Proxy object connected
,10-30 17:48:16.945  5499  5517 D BluetoothHeadset: Proxy object connected
,10-30 17:48:16.946  5499  5499 D HeadsetProfile: Bluetooth service connected
,10-30 17:48:20.739  5564  5613 D BluetoothAdapterState: Current state: ON, message: 23
,10-30 17:48:20.739  5564  5613 D BluetoothAdapterProperties: Setting state to 13
10-30 17:48:20.739  5564  5613 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-30 17:48:20.741  5564  5613 D BluetoothAdapterProperties: onBluetoothDisable()
,10-30 17:48:20.745  5564  5564 D BluetoothMapService: onReceive
10-30 17:48:20.746  5564  5564 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-30 17:48:20.746  5564  5564 D BluetoothMapService: STATE_TURNING_OFF
10-30 17:48:20.746  5564  5564 D BluetoothMapService: MAP Service closeService in
10-30 17:48:20.746  5564  5564 D BluetoothMapMasInstance0: MAP Service shutdown
10-30 17:48:20.746  5564  5564 D ObexServerSockets0: shutdown(block = true)
,10-30 17:48:20.747  5564  5639 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-30 17:48:20.748  5564  5613 I BluetoothAdapterState: Entering PendingCommandState
10-30 17:48:20.750  5564  5564 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-30 17:48:20.751  5564  5640 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-30 17:48:20.751  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-30 17:48:20.751  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:20.751  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:20.751  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:20.751  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:20.751  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:20.751  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:20.751  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:20.751  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:20.752  5564  5626 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-30 17:48:20.751  5564  5564 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-30 17:48:20.753  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:20.753  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-30 17:48:20.755  5564  5564 I BtOppRfcommListener: stopping Accept Thread
10-30 17:48:20.756  5499  5499 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-30 17:48:20.756  5564  5649 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-30 17:48:20.756  5564  5649 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-30 17:48:20.756  5564  5617 D BluetoothAdapterProperties: Scan Mode:20
10-30 17:48:20.757  5564  5613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-30 17:48:20.762  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-30 17:48:20.762  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:20.762  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:20.762  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:20.762  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:20.762  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:20.762  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:20.762  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:20.762  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-30 17:48:20.763  5564  5564 D HeadsetService: Received stop request...Stopping profile...
10-30 17:48:20.764  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:20.764  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:20.765  5499  5513 D BluetoothHeadset: Proxy object disconnected
10-30 17:48:20.766   927   927 D BluetoothHeadset: Proxy object disconnected
10-30 17:48:20.766  3632  3880 D BluetoothHeadset: Proxy object disconnected
10-30 17:48:20.766   927   927 D BluetoothHeadset: Proxy object disconnected
,10-30 17:48:20.767   927   927 D BluetoothHeadset: Proxy object disconnected
10-30 17:48:20.767  2992  3007 D BluetoothHeadset: Proxy object disconnected
10-30 17:48:20.768  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:20.768  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:20.768  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:20.768  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:20.768  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:20.768  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-30 17:48:20.768  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:20.768  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:20.768  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:20.769  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-30 17:48:20.769  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-30 17:48:20.770  3463  3463 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-30 17:48:20.770  5499  5499 D DockEventReceiver: finishStartingService: stopping service
10-30 17:48:20.771  5499  5499 D HeadsetProfile: Bluetooth service disconnected
10-30 17:48:20.773  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:20.774  5564  5564 D A2dpService: Received stop request...Stopping profile...
10-30 17:48:20.774  5564  5633 D A2dpStateMachine: Exit Disconnected: -1
10-30 17:48:20.775  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:20.776   927   927 D BluetoothA2dp: Proxy object disconnected
10-30 17:48:20.777  5499  5499 D BluetoothA2dp: Proxy object disconnected
10-30 17:48:20.777  5564  5564 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:20.777  5564  5564 V BluetoothAdapterState: isTurningOn()=false
,10-30 17:48:20.777  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:20.777  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:20.777  2992  2992 D HeadsetProfile: Bluetooth service disconnected
10-30 17:48:20.778  2992  2992 D BluetoothA2dp: Proxy object disconnected
10-30 17:48:20.778  5564  5564 D HidService: Received stop request...Stopping profile...
10-30 17:48:20.778  5564  5564 D HidService: Stopping Bluetooth HidService
10-30 17:48:20.779  5499  5499 D BluetoothInputDevice: Proxy object disconnected
10-30 17:48:20.779  5499  5499 D HidProfile: Bluetooth service disconnected
10-30 17:48:20.779  2992  2992 D BluetoothInputDevice: Proxy object disconnected
10-30 17:48:20.779  2992  2992 D HidProfile: Bluetooth service disconnected
10-30 17:48:20.780  5564  5564 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-30 17:48:20.780  5564  5564 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-30 17:48:20.781  5564  5624 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:20.781  5564  5624 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:20.781  5564  5624 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:20.781  5564  5617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-30 17:48:20.781  5564  5564 D HealthService: Received stop request...Stopping profile...
,10-30 17:48:20.782  5564  5617 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
10-30 17:48:20.782  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:20.783  5564  5564 D PanService: Received stop request...Stopping profile...
,10-30 17:48:20.784  2992  2992 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-30 17:48:20.784  2992  2992 D PanProfile: Bluetooth service disconnected
10-30 17:48:20.784  5499  5499 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-30 17:48:20.784  5499  5499 D PanProfile: Bluetooth service disconnected
10-30 17:48:20.787  5499  5499 D BluetoothPbap: Proxy object disconnected
10-30 17:48:20.787  5499  5499 D PbapServerProfile: Bluetooth service disconnected
,10-30 17:48:20.788  2992  2992 D BluetoothPbap: Proxy object disconnected
10-30 17:48:20.788  2992  2992 D PbapServerProfile: Bluetooth service disconnected
,10-30 17:48:20.790  5564  5564 D BluetoothMapService: Received stop request...Stopping profile...
,10-30 17:48:20.791  5564  5564 D BluetoothMapService: stop()
10-30 17:48:20.791  5564  5564 D BluetoothMapAppObserver: deinitObservers()
10-30 17:48:20.791  5564  5564 D BluetoothMapAppObserver: removeReceiver()
10-30 17:48:20.792  2992  2992 D BluetoothMap: Proxy object disconnected
10-30 17:48:20.792  2992  2992 D MapProfile: Bluetooth service disconnected
,10-30 17:48:20.793  5564  5564 D SapService: Received stop request...Stopping profile...
,10-30 17:48:20.793  5564  5564 V SapService: stop()
10-30 17:48:20.794  5564  5564 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:20.794  5564  5564 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:20.794  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:20.794  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
,10-30 17:48:20.794  5499  5499 D BluetoothMap: Proxy object disconnected
10-30 17:48:20.795  5499  5499 D MapProfile: Bluetooth service disconnected
10-30 17:48:20.795  5564  5617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-30 17:48:20.795  5564  5564 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:20.795  5564  5624 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:20.795  5564  5564 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:20.795  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:20.795  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:20.795  5564  5624 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:20.795  5564  5624 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-30 17:48:20.795  5564  5564 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-30 17:48:20.795  5564  5624 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-30 17:48:20.796  5564  5564 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-30 17:48:20.796  5564  5617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-30 17:48:20.796  5564  5624 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-30 17:48:20.796  5564  5624 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-30 17:48:20.796  5564  5564 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:20.796  5564  5564 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:20.796  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:20.796  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:20.796  5564  5564 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-30 17:48:20.796  5564  5564 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-30 17:48:20.797  5564  5564 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:20.797  5564  5564 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:20.797  5564  5617 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-30 17:48:20.797  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:20.797  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:20.797  5564  5564 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-30 17:48:20.797  5564  5564 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-30 17:48:20.799  5564  5564 D BluetoothMapService: MAP Service closeService in
,10-30 17:48:20.799  5564  5564 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:20.799  5564  5564 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:20.799  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:20.799  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:20.799  5564  5564 D BluetoothMapService: cleanup()
10-30 17:48:20.799  5564  5564 D BluetoothMapService: MAP Service closeService in
10-30 17:48:20.799  5564  5564 V BluetoothAdapterState: isTurningOff()=true
10-30 17:48:20.799  5564  5564 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:20.799  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:20.799  5564  5564 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:20.800  5564  5613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-30 17:48:20.800  5564  5613 D BluetoothAdapterProperties: Setting state to 15
10-30 17:48:20.800  5564  5613 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-30 17:48:20.800  5564  5613 I BluetoothAdapterState: Entering BleOnState
10-30 17:48:20.800  3632  3644 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-30 17:48:20.802  5499  5517 D BluetoothPbap: onBluetoothStateChange: up=false
,10-30 17:48:20.803  2992  3007 D BluetoothMap: onBluetoothStateChange: up=false
10-30 17:48:20.803  5499  5513 D BluetoothMap: onBluetoothStateChange: up=false
10-30 17:48:20.804  5499  5517 D BluetoothA2dp: onBluetoothStateChange: up=false
10-30 17:48:20.804   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:20.804   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:20.805  2992  3850 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:20.806  2992  3011 D BluetoothA2dp: onBluetoothStateChange: up=false
10-30 17:48:20.806  2992  3007 D BluetoothPbap: onBluetoothStateChange: up=false
10-30 17:48:20.806  5499  5513 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-30 17:48:20.807  2992  3850 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-30 17:48:20.807  5499  5517 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:20.808  5499  5513 D BluetoothPan: onBluetoothStateChange on: false
10-30 17:48:20.808  2992  3011 D BluetoothPan: onBluetoothStateChange on: false
10-30 17:48:20.809   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-30 17:48:20.809   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-30 17:48:20.809  5564  5613 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-30 17:48:20.809  5564  5613 D BluetoothAdapterProperties: Setting state to 16
10-30 17:48:20.809  5564  5613 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-30 17:48:20.810  5564  5613 D BluetoothAdapterProperties: onBleDisable
,10-30 17:48:20.810  5564  5613 I BluetoothAdapterState: Entering PendingCommandState
10-30 17:48:20.810  5564  5614 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-30 17:48:20.812  5564  5624 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-30 17:48:20.812  5564  5617 D BluetoothAdapterProperties: Scan Mode:20
10-30 17:48:20.812  5564  5624 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-30 17:48:20.812  5499  5499 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-30 17:48:20.813  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:20.815  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:20.817  3463  3463 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-30 17:48:20.817  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:20.819  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:20.820  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:20.821  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:20.822  5499  5499 D DockEventReceiver: finishStartingService: stopping service
,10-30 17:48:21.015  5564  5617 I bt_hci  : shut_down
,10-30 17:48:21.020  5564  5621 D bt_hwcfg: hw_epilog_process
,10-30 17:48:21.020  5564  5621 I bt_vendor: low_power_mode_cb
,10-30 17:48:21.023  5564  5621 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-30 17:48:21.023  5564  5621 I bt_vendor: epilog_cb
10-30 17:48:21.023  5564  5621 I bt_hci  : epilog_finished_callback
,10-30 17:48:21.026  5564  5617 I bt_hci_h4: hal_close
,10-30 17:48:21.027  5564  5617 I bt_userial_vendor: device fd = 54 close
,10-30 17:48:21.135  5564  5614 D bt_stack_manager: event_shut_down_stack finished.
,10-30 17:48:21.136  5564  5613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-30 17:48:21.139  5564  5613 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-30 17:48:21.139  5564  5564 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-30 17:48:21.140  5564  5564 D BtGatt.GattService: Received stop request...Stopping profile...
10-30 17:48:21.141  5564  5564 D BtGatt.GattService: stop()
10-30 17:48:21.141  5564  5564 D BtGatt.AdvertiseManager: advertise clients cleared
,10-30 17:48:21.143  5564  5564 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:21.144  5564  5564 V BluetoothAdapterState: isTurningOn()=false
10-30 17:48:21.144  5564  5564 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:21.144  5564  5564 V BluetoothAdapterState: isBleTurningOff()=true
10-30 17:48:21.144  5564  5613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-30 17:48:21.145  5564  5613 D BluetoothAdapterProperties: Setting state to 10
10-30 17:48:21.145  5564  5613 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-30 17:48:21.145  5564  5613 I BluetoothAdapterState: Entering OffState
,10-30 17:48:21.146   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-30 17:48:21.156  5564  5564 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-30 17:48:21.156  5564  5564 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-30 17:48:21.156  5564  5564 I BluetoothServiceJni: cleanupNative: return from cleanup
10-30 17:48:21.158  5564  5614 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-30 17:48:21.164  5564  5564 I art     : System.exit called, status: 0
,10-30 17:48:21.164  5564  5564 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-30 17:48:21.198   927   937 I ActivityManager: Process com.android.bluetooth (pid 5564) has died
,10-30 17:48:25.737  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:48:25.737  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:48:25.742  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:48:25.742  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9418315 removed from the list
,10-30 17:48:25.742  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
,10-30 17:48:25.742  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:48:25.742  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:48:25.745  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:25.745  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5df7c1b added. We now have 4 listener(s)
,10-30 17:48:25.745  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:25.747  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:25.747  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5df7c1b removed from the list
10-30 17:48:25.748  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
,10-30 17:48:25.748  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:25.748  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:48:25.750  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-30 17:48:25.751  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fda41b8 added. We now have 4 listener(s)
10-30 17:48:25.751  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-30 17:48:30.761  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:30.797   927   944 I ActivityManager: Start proc 5657:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-30 17:48:30.883  5657  5657 D AdapterServiceConfig: Adding HeadsetService
,10-30 17:48:30.883  5657  5657 D AdapterServiceConfig: Adding A2dpService
10-30 17:48:30.883  5657  5657 D AdapterServiceConfig: Adding HidService
10-30 17:48:30.883  5657  5657 D AdapterServiceConfig: Adding HealthService
10-30 17:48:30.884  5657  5657 D AdapterServiceConfig: Adding PanService
10-30 17:48:30.884  5657  5657 D AdapterServiceConfig: Adding GattService
10-30 17:48:30.884  5657  5657 D AdapterServiceConfig: Adding BluetoothMapService
,10-30 17:48:30.884  5657  5657 D AdapterServiceConfig: Adding SapService
,10-30 17:48:30.895   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@168e0bb:true
,10-30 17:48:30.895  5657  5657 D BluetoothAdapterState: make() - Creating AdapterState
,10-30 17:48:30.898  5657  5657 I bt_bluedroid: init
10-30 17:48:30.899  5657  5669 I BluetoothAdapterState: Entering OffState
,10-30 17:48:30.901  5657  5670 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-30 17:48:30.901  5657  5670 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-30 17:48:30.901  5657  5670 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-30 17:48:30.901  5657  5670 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-30 17:48:30.902  5657  5657 I bt_bluedroid: get_profile_interface socket
,10-30 17:48:30.904  5657  5673 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-30 17:48:30.905  5657  5657 I bt_bluedroid: get_profile_interface sdp
10-30 17:48:30.906  5657  5673 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-30 17:48:30.910  5657  5668 I bt_bluedroid: config_hci_snoop_log
,10-30 17:48:30.912   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-30 17:48:30.916  5657  5669 D BluetoothAdapterState: Current state: OFF, message: 0
10-30 17:48:30.916  5657  5669 D BluetoothAdapterProperties: Setting state to 14
10-30 17:48:30.916  5657  5669 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-30 17:48:30.918  5657  5669 D BluetoothBondStateMachine: make
,10-30 17:48:30.920  5657  5674 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-30 17:48:30.923  5657  5669 I BluetoothAdapterState: Entering PendingCommandState
,10-30 17:48:30.924  5657  5657 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-30 17:48:30.927  5657  5657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:30.927  5657  5657 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-30 17:48:30.928  5657  5657 D BtGatt.GattService: Received start request. Starting profile...
10-30 17:48:30.928  5657  5657 D BtGatt.GattService: start()
10-30 17:48:30.928  5657  5657 I bt_bluedroid: get_profile_interface gatt
10-30 17:48:30.929  5657  5657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:30.929  5657  5657 D BtGatt.AdvertiseManager: advertise manager created
,10-30 17:48:30.935  5657  5657 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:30.935  5657  5657 V BluetoothAdapterState: isTurningOn()=false
,10-30 17:48:30.935  5657  5657 V BluetoothAdapterState: isBleTurningOn()=true
10-30 17:48:30.935  5657  5657 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:30.936  5657  5669 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-30 17:48:30.937  5657  5669 I bt_bluedroid: bt_bluedroid
10-30 17:48:30.938  5657  5670 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-30 17:48:30.938  5657  5670 I bt_hci  : start_up
,10-30 17:48:30.943  5657  5670 I bt_vendor: alloc value 0xf3af7871
,10-30 17:48:30.943  5657  5670 I bt_vendor: init
10-30 17:48:30.943  5657  5670 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-30 17:48:30.943  5657  5670 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-30 17:48:31.052  5657  5670 D bt_hci  : start_up starting async portion
10-30 17:48:31.053  5657  5677 I bt_hci  : event_finish_startup
,10-30 17:48:31.053  5657  5677 I bt_hci_h4: hal_open
,10-30 17:48:31.053  5657  5677 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-30 17:48:31.054  5678  5678 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-30 17:48:31.058  5657  5677 I bt_userial_vendor: device fd = 54 open
,10-30 17:48:31.074  5657  5677 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-30 17:48:31.078  5657  5677 D bt_hwcfg: Chipset BCM4358A3
,10-30 17:48:31.078  5657  5677 D bt_hwcfg: Target name = [BCM4358A3]
10-30 17:48:31.078  5657  5677 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-30 17:48:31.590  5657  5677 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-30 17:48:31.590  5657  5677 D bt_hwcfg: Settlement delay -- 100 ms
10-30 17:48:31.590  5657  5677 I bt_hwcfg: Setting fw settlement delay to 100 
,10-30 17:48:31.725  5657  5677 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-30 17:48:31.726  5657  5677 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-30 17:48:31.728  5657  5677 I bt_hwcfg: vendor lib fwcfg completed
,10-30 17:48:31.728  5657  5677 I bt_vendor: firmware callback
,10-30 17:48:31.728  5657  5677 I bt_hci  : firmware_config_callback
,10-30 17:48:31.737  5657  5680 I bt_btu  : btu_task pending for preload complete event
10-30 17:48:31.737  5657  5680 I bt_btu_task: Bluetooth chip preload is complete
,10-30 17:48:31.737  5657  5680 I bt_btu  : btu_task received preload complete event
,10-30 17:48:31.744  5657  5680 I         : BTE_InitTraceLevels -- TRC_HCI
10-30 17:48:31.745  5657  5680 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-30 17:48:31.745  5657  5680 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-30 17:48:31.745  5657  5680 I         : BTE_InitTraceLevels -- TRC_AVDT
10-30 17:48:31.745  5657  5680 I         : BTE_InitTraceLevels -- TRC_AVRC
10-30 17:48:31.745  5657  5680 I         : BTE_InitTraceLevels -- TRC_A2D
,10-30 17:48:31.745  5657  5680 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-30 17:48:31.745  5657  5680 I         : BTE_InitTraceLevels -- TRC_BTM
10-30 17:48:31.745  5657  5680 I         : BTE_InitTraceLevels -- TRC_GAP
10-30 17:48:31.746  5657  5680 I         : BTE_InitTraceLevels -- TRC_PAN
,10-30 17:48:31.746  5657  5680 I         : BTE_InitTraceLevels -- TRC_SDP
,10-30 17:48:31.746  5657  5680 I         : BTE_InitTraceLevels -- TRC_GATT
10-30 17:48:31.746  5657  5680 I         : BTE_InitTraceLevels -- TRC_SMP
10-30 17:48:31.746  5657  5680 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-30 17:48:31.746  5657  5680 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-30 17:48:31.842  5657  5680 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a75549
10-30 17:48:31.842  5657  5680 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a75549 
,10-30 17:48:31.869  5657  5673 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-30 17:48:31.872  5657  5673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-30 17:48:31.872  5657  5673 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-30 17:48:31.875  5657  5673 D BluetoothAdapterProperties: Name is: Nexus 6P
10-30 17:48:31.879  5657  5673 D BluetoothAdapterProperties: Scan Mode:20
10-30 17:48:31.879  5657  5673 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-30 17:48:31.879  5657  5673 D bt_hci  : do_postload posting postload work item
10-30 17:48:31.879  5657  5677 I bt_hci  : event_postload
10-30 17:48:31.879  5657  5677 I bt_vendor: sco_config_cb
10-30 17:48:31.880  5657  5677 I bt_hci  : sco_config_callback postload finished.
,10-30 17:48:31.882  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:31.884  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:31.885  5657  5673 D bt_bte_conf: Device ID record 1 : primary
10-30 17:48:31.885  5657  5673 D bt_bte_conf:   vendorId            = 000f
10-30 17:48:31.885  5657  5673 D bt_bte_conf:   vendorIdSource      = 0001
,10-30 17:48:31.885  5657  5673 D bt_bte_conf:   product             = 1200
10-30 17:48:31.885  5657  5673 D bt_bte_conf:   version             = 1436
10-30 17:48:31.885  5657  5673 D bt_bte_conf:   clientExecutableURL = 
10-30 17:48:31.886  5657  5673 D bt_bte_conf:   serviceDescription  = 
,10-30 17:48:31.886  5657  5673 D bt_bte_conf:   documentationURL    = 
10-30 17:48:31.886  5657  5673 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-30 17:48:31.886  5657  5670 D bt_stack_manager: event_start_up_stack finished
10-30 17:48:31.887  5657  5669 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-30 17:48:31.887  5657  5669 D BluetoothAdapterProperties: Setting state to 15
10-30 17:48:31.887  5657  5669 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-30 17:48:31.888  5657  5677 I bt_vendor: low_power_mode_cb
10-30 17:48:31.888  5657  5669 I BluetoothAdapterState: Entering BleOnState
,10-30 17:48:31.893  5657  5669 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-30 17:48:31.893  5657  5669 D BluetoothAdapterProperties: Setting state to 11
10-30 17:48:31.893  5657  5669 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-30 17:48:31.899  5657  5657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:31.900  5657  5657 D HeadsetService: Received start request. Starting profile...
10-30 17:48:31.903  5657  5657 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-30 17:48:31.904  5657  5657 D HeadsetStateMachine: make
,10-30 17:48:31.911  5657  5669 I BluetoothAdapterState: Entering PendingCommandState
,10-30 17:48:31.916  5657  5657 D HeadsetStateMachine: max_hf_connections = 1
10-30 17:48:31.916  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:31.916  5657  5657 I bt_bluedroid: get_profile_interface handsfree
,10-30 17:48:31.917  5657  5673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-30 17:48:31.917  5657  5673 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-30 17:48:31.919  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:31.922  5657  5657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:31.922  5657  5657 D A2dpService: Received start request. Starting profile...
10-30 17:48:31.923  5657  5657 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-30 17:48:31.923  5657  5657 I bt_bluedroid: get_profile_interface avrcp
,10-30 17:48:31.929  5657  5657 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-30 17:48:31.930  5657  5657 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-30 17:48:31.930  5657  5657 D A2dpStateMachine: make
,10-30 17:48:31.931  5657  5657 I bt_bluedroid: get_profile_interface a2dp
10-30 17:48:31.931  5657  5673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-30 17:48:31.933  5657  5657 I BluetoothHidServiceJni: classInitNative: succeeds
10-30 17:48:31.934  5657  5657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:31.935  5657  5688 D A2dpStateMachine: Enter Disconnected: -2
,10-30 17:48:31.935  5657  5657 D HidService: Received start request. Starting profile...
,10-30 17:48:31.936  5657  5657 I bt_bluedroid: get_profile_interface hidhost
10-30 17:48:31.936  5657  5657 D HidService: setHidService(): set to: null
10-30 17:48:31.936  5657  5657 I BluetoothHealthServiceJni: classInitNative: succeeds
10-30 17:48:31.937  5657  5673 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a5656d
10-30 17:48:31.937  5657  5673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-30 17:48:31.937  5657  5657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:31.938  5657  5657 D HealthService: Received start request. Starting profile...
,10-30 17:48:31.939  5657  5657 I bt_bluedroid: get_profile_interface health
,10-30 17:48:31.940  5657  5657 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-30 17:48:31.942  5657  5657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:31.942  5657  5657 D PanService: Received start request. Starting profile...
,10-30 17:48:31.942  5657  5657 D BluetoothPanServiceJni: initializeNative(L110): pan
10-30 17:48:31.943  5657  5657 I bt_bluedroid: get_profile_interface pan
10-30 17:48:31.943  5657  5673 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-30 17:48:31.945  5657  5657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:31.946  5657  5657 D BluetoothMapService: Received start request. Starting profile...
10-30 17:48:31.946  5657  5657 D BluetoothMapService: start()
,10-30 17:48:31.952  5657  5657 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-30 17:48:31.953  5657  5657 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-30 17:48:31.953  5657  5657 D BluetoothMapAppObserver: createReceiver()
,10-30 17:48:31.954  5657  5657 D BluetoothMapAppObserver: initObservers()
,10-30 17:48:31.955  5657  5657 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-30 17:48:31.963  5657  5657 V SapService: SapBinder()
,10-30 17:48:31.963  5657  5657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
10-30 17:48:31.964  5657  5657 D SapService: Received start request. Starting profile...
10-30 17:48:31.964  5657  5657 V SapService: start()
,10-30 17:48:31.967  5657  5657 V BluetoothAdapterState: isTurningOff()=false
,10-30 17:48:31.967  5657  5657 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:31.967  5657  5657 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:31.967  5657  5685 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-30 17:48:31.967  5657  5657 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:31.967  5657  5657 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:31.967  5657  5657 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:31.968  5657  5657 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:31.969  5657  5657 V BluetoothAdapterState: isTurningOff()=false
10-30 17:48:31.969  5657  5657 V BluetoothAdapterState: isTurningOn()=true
10-30 17:48:31.969  5657  5657 V BluetoothAdapterState: isBleTurningOn()=false
10-30 17:48:31.969  5657  5657 V BluetoothAdapterState: isBleTurningOff()=false
10-30 17:48:31.969  5657  5669 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-30 17:48:31.969  5657  5669 D BluetoothAdapterProperties: ScanMode =  20
10-30 17:48:31.969  5657  5669 D BluetoothAdapterProperties: State =  11
10-30 17:48:31.970  3463  3463 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-30 17:48:31.974  5657  5673 D BluetoothAdapterProperties: Scan Mode:21
10-30 17:48:31.975  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-30 17:48:31.975  5657  5673 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-30 17:48:31.976  5657  5669 D BluetoothAdapterProperties: Setting state to 12
10-30 17:48:31.976  5657  5669 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-30 17:48:31.976  5657  5669 I BluetoothAdapterState: Entering OnState
10-30 17:48:31.976  3632  3880 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:31.978  5499  5513 D BluetoothPbap: onBluetoothStateChange: up=true
10-30 17:48:31.979  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:31.979  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:31.979  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:31.979  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:31.979  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:31.979  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:31.979  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:31.979  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:31.979  2992  3011 D BluetoothMap: onBluetoothStateChange: up=true
10-30 17:48:31.980  5657  5657 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-30 17:48:31.981  5499  5517 D BluetoothMap: onBluetoothStateChange: up=true
10-30 17:48:31.981  5657  5657 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-30 17:48:31.981  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:31.983  5657  5657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-30 17:48:31.983  5499  5513 D BluetoothA2dp: onBluetoothStateChange: up=true
10-30 17:48:31.984  5657  5657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-30 17:48:31.984   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:31.985   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:31.985  2992  3850 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:31.985  2992  3007 D BluetoothA2dp: onBluetoothStateChange: up=true
10-30 17:48:31.986  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:31.986  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:31.986  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:31.986  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:31.986  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:31.986  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:31.986  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:31.986  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:31.987  2992  3011 D BluetoothPbap: onBluetoothStateChange: up=true
10-30 17:48:31.987  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:31.989  5499  5517 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-30 17:48:31.990  2992  3850 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-30 17:48:31.992  5657  5657 D ObexServerSockets: Succeed to create listening sockets 
,10-30 17:48:31.992  5657  5657 D ObexServerSockets0: startAccept()
,10-30 17:48:31.992  5499  5513 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:31.992  5657  5657 D ObexServerSockets0: prepareForNewConnect()
10-30 17:48:31.993  5499  5517 D BluetoothPan: onBluetoothStateChange on: true
,10-30 17:48:31.994  2992  3007 D BluetoothPan: onBluetoothStateChange on: true
10-30 17:48:31.994  5657  5657 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-30 17:48:31.995  5657  5657 D BluetoothSdpJni: SDP Create record success - handle: 0
10-30 17:48:31.995  5657  5693 D ObexServerSockets0: Accepting socket connection...
10-30 17:48:31.996  2992  2992 D BluetoothMap: Proxy object connected
10-30 17:48:31.996  2992  2992 D MapProfile: Bluetooth service connected
10-30 17:48:31.996  2992  2992 D BluetoothMap: getConnectedDevices()
10-30 17:48:31.996   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-30 17:48:31.997  5499  5499 D BluetoothMap: Proxy object connected
10-30 17:48:31.997  5499  5499 D MapProfile: Bluetooth service connected
10-30 17:48:31.997  5499  5499 D BluetoothMap: getConnectedDevices()
10-30 17:48:31.997   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-30 17:48:31.997   927   927 D BluetoothA2dp: Proxy object connected
10-30 17:48:31.998  2992  2992 D BluetoothA2dp: Proxy object connected
10-30 17:48:31.999  5657  5694 D ObexServerSockets0: Accepting socket connection...
10-30 17:48:32.000  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-30 17:48:32.001  2992  2992 D BluetoothInputDevice: Proxy object connected
10-30 17:48:32.001  5657  5657 D BluetoothMapService: onReceive
10-30 17:48:32.002  2992  2992 D HidProfile: Bluetooth service connected
10-30 17:48:32.002  5657  5657 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-30 17:48:32.002  5657  5657 D BluetoothMapService: STATE_ON
10-30 17:48:32.002   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-30 17:48:32.003  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:32.004  5499  5499 D BluetoothA2dp: Proxy object connected
10-30 17:48:32.004  2992  2992 D BluetoothPan: BluetoothPAN Proxy object connected
10-30 17:48:32.004  2992  2992 D PanProfile: Bluetooth service connected
10-30 17:48:32.006  5657  5697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-30 17:48:32.006  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:32.008  5657  5697 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-30 17:48:32.008  5657  5697 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-30 17:48:32.011  5499  5499 D BluetoothInputDevice: Proxy object connected
,10-30 17:48:32.011  5499  5499 D HidProfile: Bluetooth service connected
10-30 17:48:32.012  5499  5499 D BluetoothPan: BluetoothPAN Proxy object connected
10-30 17:48:32.013  5499  5499 D PanProfile: Bluetooth service connected
10-30 17:48:32.014  5499  5499 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-30 17:48:32.020  3463  3463 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-30 17:48:32.022  5499  5499 D DockEventReceiver: finishStartingService: stopping service
,10-30 17:48:32.029  5499  5499 D BluetoothPbap: Proxy object connected
10-30 17:48:32.029  2992  2992 D BluetoothPbap: Proxy object connected
10-30 17:48:32.029  5499  5499 D PbapServerProfile: Bluetooth service connected
10-30 17:48:32.029  2992  2992 D PbapServerProfile: Bluetooth service connected
,10-30 17:48:32.030  5657  5657 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-30 17:48:32.030  5657  5657 D ObexServerSockets0: prepareForNewConnect()
,10-30 17:48:32.037  5657  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-30 17:48:32.052  5657  5705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-30 17:48:32.052  5657  5705 I BtOppRfcommListener: Accept thread started.
,10-30 17:48:32.080  5499  5513 D BluetoothHeadset: Proxy object connected
,10-30 17:48:32.080   927   927 D BluetoothHeadset: Proxy object connected
10-30 17:48:32.080  3632  3644 D BluetoothHeadset: Proxy object connected
10-30 17:48:32.081   927   927 D BluetoothHeadset: Proxy object connected
10-30 17:48:32.081   927   927 D BluetoothHeadset: Proxy object connected
,10-30 17:48:32.081  2992  3850 D BluetoothHeadset: Proxy object connected
,10-30 17:48:32.082  2992  2992 D HeadsetProfile: Bluetooth service connected
10-30 17:48:32.083  5499  5499 D HeadsetProfile: Bluetooth service connected
,10-30 17:48:32.085   927   944 D BluetoothHeadset: Proxy object connected
10-30 17:48:32.085   927   944 D BluetoothHeadset: Proxy object connected
10-30 17:48:32.086  2992  3011 D BluetoothHeadset: Proxy object connected
10-30 17:48:32.086  2992  2992 D HeadsetProfile: Bluetooth service connected
,10-30 17:48:32.093  5499  5517 D BluetoothHeadset: Proxy object connected
,10-30 17:48:32.094  5499  5499 D HeadsetProfile: Bluetooth service connected
,10-30 17:48:32.098   927   944 D BluetoothHeadset: Proxy object connected
,10-30 17:48:32.723   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-30 17:48:32.723   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-30 17:48:35.778  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:35.778  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:35.778  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:35.778  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-30 17:48:35.778  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:35.778  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:35.778  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:35.778  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-30 17:48:35.785  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-30 17:48:35.785  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-30 17:48:35.785  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fda41b8 removed from the list
10-30 17:48:35.786  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:48:35.786  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:35.786  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:48:35.790  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-30 17:48:35.790  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c443b91 added. We now have 4 listener(s)
10-30 17:48:35.790  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-30 17:48:35.793   927  3666 D WifiService: setWifiEnabled: false pid=5432, uid=10077
,10-30 17:48:35.794   927  3666 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-30 17:48:40.806  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:40.807   927   938 D WifiService: setWifiEnabled: true pid=5432, uid=10077
,10-30 17:48:40.807   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-30 17:48:40.815   507   921 D SoftapController: Softap fwReload - Ok
,10-30 17:48:40.821   507   921 D CommandListener: Setting iface cfg
,10-30 17:48:40.821   507   921 D CommandListener: Trying to bring down wlan0
,10-30 17:48:40.823   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-30 17:48:40.830   927  2825 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-30 17:48:41.498   927  2825 D wifi    : set interface wlan0 flags (UP)
,10-30 17:48:41.500   927  2825 I WifiHAL : Initializing wifi
,10-30 17:48:41.500   927  2825 I WifiHAL : Creating socket
10-30 17:48:41.505   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-30 17:48:41.506   927  2825 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-30 17:48:41.506   927  2825 D wifi    : Did set static halHandle = 0x7f66586080
10-30 17:48:41.506   927  2825 D wifi    : halHandle = 0x7f66586080, mVM = 0x7f809cd140, mCls = 0x201906
10-30 17:48:41.507   927  2825 D wifi    : array field set
10-30 17:48:41.507   927  2825 I WifiNative-HAL: interface[0] = wlan0
10-30 17:48:41.510   927  5710 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547177914496
,10-30 17:48:41.510   927  5710 D wifi    : waitForHalEvents called, vm = 0x7f809cd140, obj = 0x201906, env = 0x7f65b3f580
,10-30 17:48:41.558  5711  5711 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-30 17:48:41.581  5711  5711 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-30 17:48:41.590  5711  5711 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-30 17:48:41.590  5711  5711 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-30 17:48:41.612   927  2825 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-30 17:48:41.627  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:41.627  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:41.627  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:41.627  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:41.627  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:41.627  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:41.627  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:41.627  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:41.628   927  2825 D WifiConfigStore: Loading config and enabling all networks 
,10-30 17:48:41.631  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-30 17:48:41.635  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:41.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:41.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:41.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:41.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:41.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-30 17:48:41.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-30 17:48:41.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-30 17:48:41.637  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-30 17:48:41.638   927  2825 D WifiConfigStore: loaded 0 passpoint configs
10-30 17:48:41.639   927  2825 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-30 17:48:41.639  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:41.639   927  2825 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-30 17:48:41.640  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:41.640   927  2825 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-30 17:48:41.642   927  2825 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-30 17:48:41.642   927  2825 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-30 17:48:41.642   927  2825 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,10-30 17:48:41.642   927  2825 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-30 17:48:41.647   927  2825 D WifiNative-HAL: Setting external_sim to 1
,10-30 17:48:41.648  4274  4274 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-30 17:48:41.648   927  2825 D wifi    : setting dfs flag to true, 0x7f67d4e280
10-30 17:48:41.649   927  2825 D WifiStateMachine: Setting OUI to DA-A1-19
10-30 17:48:41.649   927  2825 D wifi    : setting scan oui 0x7f67d4e280
10-30 17:48:41.649   927  2825 D WifiHAL : Sending mac address OUI
,10-30 17:48:41.653   927  2825 E native  : do suspend false
,10-30 17:48:41.664   927  2825 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-30 17:48:41.664   927   927 D RttService: SCAN_AVAILABLE : 3
10-30 17:48:41.665   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-30 17:48:41.665   927  2932 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-30 17:48:41.666   507   921 D CommandListener: Setting iface cfg
,10-30 17:48:41.671   927  2812 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '135 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 135 Failed to set address (No such device)'
10-30 17:48:41.671   927  2812 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-30 17:48:41.681   927  2812 D WifiNative-HAL: p2pGetDeviceAddress
10-30 17:48:41.681   927  2812 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-30 17:48:41.687   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=227842 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,10-30 17:48:42.725   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:43.726   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:44.727   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:44.786   927  2825 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-30 17:48:44.787   927  2825 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-30 17:48:44.787   927  2825 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-30 17:48:44.799   927  2825 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-30 17:48:44.829   927  2825 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-30 17:48:44.830  5711  5711 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-30 17:48:45.260  5711  5711 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-30 17:48:45.297  5711  5711 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-30 17:48:45.299  5711  5711 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-30 17:48:45.313   927  2825 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-30 17:48:45.313   927  2825 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-30 17:48:45.313   927  2839 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-30 17:48:45.330   927  2825 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-30 17:48:45.345   507   921 D CommandListener: Setting iface cfg
,10-30 17:48:45.351   927  2825 D WifiStateMachine: Start Dhcp Watchdog 2
,10-30 17:48:45.362   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-30 17:48:45.362   927  2825 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-30 17:48:45.362   927  2839 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-30 17:48:45.366   927  5716 D DhcpClient: Receive thread started
,10-30 17:48:45.446   927  2825 E native  : do suspend false
,10-30 17:48:45.457   927  5715 D DhcpClient: Broadcasting DHCPDISCOVER
,10-30 17:48:45.470   927  5716 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172609, domain null
,10-30 17:48:45.471   927  5715 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172609 seconds
,10-30 17:48:45.472   927  5715 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-30 17:48:45.486   927  5716 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
10-30 17:48:45.487   927  5715 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-30 17:48:45.490   507   921 D CommandListener: Setting iface cfg
,10-30 17:48:45.494   927  2825 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-30 17:48:45.497   927  5715 D DhcpClient: Scheduling renewal in 86399s
,10-30 17:48:45.507   927  2825 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-30 17:48:45.507   927  2825 D WifiConfigStore: No blacklist allowed without epno enabled
10-30 17:48:45.507   927  2839 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-30 17:48:45.509   927  2825 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
10-30 17:48:45.512   927  2839 D ConnectivityService: Adding iface wlan0 to network 101
,10-30 17:48:45.559   927  2839 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-30 17:48:45.559   927  2839 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-30 17:48:45.560   927  2839 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
10-30 17:48:45.561   927  2839 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-30 17:48:45.562   927  2839 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-30 17:48:45.569   927  2839 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-30 17:48:45.573   927  2839 D ConnectivityService: scheduleUnvalidatedPrompt 101
10-30 17:48:45.573   927  2839 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-30 17:48:45.573   927  2839 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-30 17:48:45.573   927  2839 D ConnectivityService:    accepting network in place of null
10-30 17:48:45.573   927  2825 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-30 17:48:45.573   927  2825 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-30 17:48:45.574   927  2839 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-30 17:48:45.584   927  5714 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231739, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-30 17:48:45.594   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-30 17:48:45.616   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-30 17:48:45.619   927  2839 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-30 17:48:45.619   927  2839 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-30 17:48:45.619  3602  3736 W QCNEJ   : |CORE| network available: 101
10-30 17:48:45.620   927  2839 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-30 17:48:45.621   927   944 D Tethering: MasterInitialState.processMessage what=3
10-30 17:48:45.626  3602  3736 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-30 17:48:45.627  3602  3736 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-30 17:48:45.627  3602  3736 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-30 17:48:45.628  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:45.628  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:45.628  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:45.628  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:45.628  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:45.628  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.628  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:45.628  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:48:45.631  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-30 17:48:45.635  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:45.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:45.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:45.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:45.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:45.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:45.635  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-30 17:48:45.637  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-30 17:48:45.638  4743  4761 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-30 17:48:45.638  4743  4761 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-30 17:48:45.638  4743  4761 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-30 17:48:45.638  4743  4761 E SarControlService: no key has been found,reset the power
,10-30 17:48:45.639  4743  4782 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-30 17:48:45.639  4743  4782 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-30 17:48:45.639  4743  4782 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-30 17:48:45.639  4770  4770 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-30 17:48:45.639  4770  4770 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-30 17:48:45.642  3790  3790 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-30 17:48:45.643  4743  4782 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-30 17:48:45.643  4743  4782 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-30 17:48:45.643  4743  4782 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-30 17:48:45.643  4770  4770 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-30 17:48:45.643  4770  4770 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-30 17:48:45.645  3818  3818 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-30 17:48:45.647  4770  4784 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88b6e59 HexData = [00000000ec03000000000000ffffffff]
10-30 17:48:45.647  4770  4784 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-30 17:48:45.647  4770  4784 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,10-30 17:48:45.649  4770  4784 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88b6e59 HexData = [00000000ed03000000000000ffffffff]
10-30 17:48:45.649  4770  4784 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-30 17:48:45.649  4770  4784 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,10-30 17:48:45.650  4770  4770 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-30 17:48:45.650  4743  4754 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-30 17:48:45.651  3818  3818 D SystemUpdateService: onCreate
10-30 17:48:45.652  4770  4770 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-30 17:48:45.653   927  5713 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-30 17:48:45.654  4743  4755 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-30 17:48:45.657  3818  3818 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-30 17:48:45.667  3818  3818 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-30 17:48:45.671  3818  5222 I iu.UploadsManager: num queued entries: 0
,10-30 17:48:45.672  3818  5222 I iu.UploadsManager: num updated entries: 0
10-30 17:48:45.672  3818  5222 I iu.SyncManager: NEXT; no task
,10-30 17:48:45.674  3818  5726 I SystemUpdateService: active receiver: enabled
,10-30 17:48:45.677  3818  3818 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-30 17:48:45.679  3818  3818 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-30 17:48:45.680  5578  5578 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-30 17:48:45.684  5578  5578 D SprintDMHelper: simOperator: 
10-30 17:48:45.684  5578  5578 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-30 17:48:45.698   927  5713 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 30 Oct 2016 21:48:45 GMT], X-Android-Received-Millis=[1477864125697], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477864125675]}
,10-30 17:48:45.699   927  2839 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-30 17:48:45.699   927  2839 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-30 17:48:45.699   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-30 17:48:45.700   927  2839 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-30 17:48:45.705  3818  5726 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-30 17:48:45.722  3818  5726 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-30 17:48:45.722  3818  5726 I SystemUpdateService: now status is 0 (complete)
10-30 17:48:45.722  3818  5726 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-30 17:48:45.722  3818  5726 I SystemUpdateService: file has been verified
10-30 17:48:45.723  3818  5726 I SystemUpdateService: OTA package size = 21989297
,10-30 17:48:45.729  3818  5726 I SystemUpdateService: showing system update notification
,10-30 17:48:45.729   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:45.741  3818  3818 D SystemUpdateService: onDestroy
,10-30 17:48:45.790  4274  5730 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-30 17:48:45.818  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-30 17:48:45.818  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:45.818  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:45.818  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:45.818  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:45.818  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.818  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:45.818  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-30 17:48:45.821  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.821  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.821  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c443b91 removed from the list
10-30 17:48:45.821  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:48:45.821  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.821  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.824  5432  5479 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-30 17:48:45.824  5432  5479 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-30 17:48:45.827  5432  5479 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3fd9482 Bundle[{}]
,10-30 17:48:45.828  5432  5479 I io.jxcore.node.LifeCycleMonitor: start: OK
10-30 17:48:45.828  5432  5479 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-30 17:48:45.828  5432  5479 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-30 17:48:45.828  5432  5479 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-30 17:48:45.829  5432  5479 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-30 17:48:45.829  5432  5479 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-30 17:48:45.835  5432  5479 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,10-30 17:48:45.835  5432  5479 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-30 17:48:45.835  5432  5479 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
10-30 17:48:45.837  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:45.837  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@659baf6 added. We now have 3 listener(s)
,10-30 17:48:45.838  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:48:45.838  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:48:45.838  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:48:45.838  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:45.839  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6fbef7 added. We now have 4 listener(s)
10-30 17:48:45.839  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-30 17:48:45.839  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-30 17:48:45.842  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-30 17:48:45.846  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:48:45.846  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:45.846  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:45.846  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:45.846  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:45.846  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.846  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:45.846  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-30 17:48:45.848  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-30 17:48:45.848  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
10-30 17:48:45.848  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:45.848  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dfffcd added. We now have 4 listener(s)
10-30 17:48:45.850  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:48:45.850  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:48:45.850  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:48:45.851  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:45.851  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bde9082 added. We now have 5 listener(s)
10-30 17:48:45.851  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:45.851  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:48:45.851  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-30 17:48:45.851  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:48:45.851  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:48:45.851  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.851  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:48:45.851  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:45.852  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:48:45.852  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@659baf6 removed from the list
10-30 17:48:45.852  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.852  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6fbef7 removed from the list
,10-30 17:48:45.852  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:45.852  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:48:45.852  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.853  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.853  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.854  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.856  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.856  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.856  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.856  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:48:45.857  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:45.857  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.857  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6fbef7 not in the list
10-30 17:48:45.857  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.857  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.857  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.857  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:45.859  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.859  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.859  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.859  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:45.859  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:48:45.859  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.859  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bde9082 removed from the list
10-30 17:48:45.859  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:48:45.860  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.860  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-30 17:48:45.860  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:45.860  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:48:45.860  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dfffcd removed from the list
10-30 17:48:45.861  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:45.861  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4575393 added. We now have 3 listener(s)
,10-30 17:48:45.862  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:48:45.862  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:48:45.863  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:48:45.863  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:45.863  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b578fd0 added. We now have 4 listener(s)
10-30 17:48:45.863  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-30 17:48:45.864  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-30 17:48:45.867  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-30 17:48:45.871  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:48:45.871  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:45.871  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:45.871  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:45.871  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:45.871  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.871  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:45.871  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-30 17:48:45.873  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-30 17:48:45.874  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
10-30 17:48:45.874  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:45.874  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e932ce added. We now have 4 listener(s)
,10-30 17:48:45.876  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-30 17:48:45.876  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:48:45.876  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:48:45.876  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:45.876  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:45.876  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21995ef added. We now have 5 listener(s)
10-30 17:48:45.876  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:45.876  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:48:45.877  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-30 17:48:45.877  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-30 17:48:45.877  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:48:45.877  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-30 17:48:45.880  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:45.881  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-30 17:48:45.882  5432  5479 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-30 17:48:45.882  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-30 17:48:45.886  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.886  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-30 17:48:45.886  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-30 17:48:45.887  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-30 17:48:45.889  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.889  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-30 17:48:45.889  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-30 17:48:45.889  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-30 17:48:45.889  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-30 17:48:45.889  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.890  5432  5479 D BluetoothAdapter: STATE_ON
,10-30 17:48:45.892  5657  5695 D BtGatt.GattService: registerClient() - UUID=9302c737-6e06-42fd-82b4-a6c4e243242a
10-30 17:48:45.893  5657  5673 D BtGatt.GattService: onClientRegistered() - UUID=9302c737-6e06-42fd-82b4-a6c4e243242a, clientIf=5
,10-30 17:48:45.893  5432  5443 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-30 17:48:45.894  5657  5667 D BtGatt.GattService: start scan with filters
,10-30 17:48:45.896  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-30 17:48:45.897  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.897  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-30 17:48:45.897  5657  5676 D BtGatt.ScanManager: handling starting scan
10-30 17:48:45.897  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.897  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-30 17:48:45.897  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-30 17:48:45.897  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.897  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-30 17:48:45.897  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-30 17:48:45.897  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-30 17:48:45.897  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.897  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-30 17:48:45.898  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-30 17:48:45.898  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.898  5657  5676 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d07ef6
,10-30 17:48:45.900  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.900  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:48:45.900  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.900  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.900  5432  5479 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-30 17:48:45.900  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.900  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-30 17:48:45.900  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-30 17:48:45.900  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.901  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-30 17:48:45.901  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:45.901  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-30 17:48:45.904  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.904  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-30 17:48:45.904  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.904  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.904  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-30 17:48:45.904  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-30 17:48:45.904  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-30 17:48:45.904  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:48:45.905  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.905  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.905  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.905  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-30 17:48:45.905  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.905  5657  5673 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-30 17:48:45.905  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.905  5432  5479 D BluetoothAdapter: STATE_ON
10-30 17:48:45.906  5657  5676 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-30 17:48:45.906  5657  5667 D BtGatt.GattService: stopScan() - queue size =1
10-30 17:48:45.906  5657  5696 D BtGatt.GattService: unregisterClient() - clientIf=5
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.907  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-30 17:48:45.907  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-30 17:48:45.908  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:48:45.908  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.909  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.909  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:48:45.909  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.909  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.909  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:48:45.909  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:48:45.909  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-30 17:48:45.909  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.909  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-30 17:48:45.909  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-30 17:48:45.909  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.909  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.909  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-30 17:48:45.910  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.911  5432  5432 D org.thaliproject.p2p.btconnectorlib.Disco,veryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.911  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.911  5657  5673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-30 17:48:45.911  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.911  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.911  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.911  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:48:45.911  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:48:45.911  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:48:45.911  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:48:45.911  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:48:45.912  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.912  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:48:45.912  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:45.912  5657  5676 D BtGatt.ScanManager: Starting BLE batch scan
10-30 17:48:45.912  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:48:45.912  5657  5676 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-30 17:48:45.912  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4575393 removed from the list
10-30 17:48:45.912  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.912  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b578fd0 removed from the list
10-30 17:48:45.912  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:48:45.912  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.913  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.913  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.913  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.914  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.914  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.914  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.914  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:48:45.914  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:45.914  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.914  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b578fd0 not in the list
10-30 17:48:45.914  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.914  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.915  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.916  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.916  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.916  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.916  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:45.916  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-30 17:48:45.916  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.916  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21995ef removed from the list
10-30 17:48:45.916  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:48:45.916  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.917  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.917  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:45.917  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:48:45.917  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e932ce removed from the list
10-30 17:48:45.917  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:45.917  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@113a20b added. We now have 3 listener(s)
10-30 17:48:45.919  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:48:45.919  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:48:45.919  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:48:45.919  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:45.919  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d88e8 added. We now have 4 listener(s)
10-30 17:48:45.919  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:45.920  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-30 17:48:45.921  5657  5673 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-30 17:48:45.921  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.923  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-30 17:48:45.927  5657  5673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-30 17:48:45.927  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:48:45.929  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:48:45.929  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:45.929  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:45.929  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:45.929  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:45.929  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.929  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:45.929  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-30 17:48:45.933  5657  5673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-30 17:48:45.933  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.933  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.933  5657  5676 D BtGatt.ScanManager: stopping BLe Batch
,10-30 17:48:45.934  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-30 17:48:45.934  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:45.934  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444cda6 added. We now have 4 listener(s)
10-30 17:48:45.935  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:48:45.935  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:48:45.935  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:48:45.935  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:45.935  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5853e7 added. We now have 5 listener(s)
10-30 17:48:45.935  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:45.935  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:48:45.936  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:48:45.936  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:45.936  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-30 17:48:45.936  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-30 17:48:45.936  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:48:45.936  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-30 17:48:45.938  5657  5673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-30 17:48:45.938  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.939  5657  5676 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-30 17:48:45.939  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:45.940  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-30 17:48:45.940  5432  5479 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-30 17:48:45.940  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-30 17:48:45.943  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.943  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-30 17:48:45.943  5657  5673 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-30 17:48:45.943  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.943  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-30 17:48:45.943  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-30 17:48:45.946  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.946  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-30 17:48:45.946  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-30 17:48:45.946  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-30 17:48:45.946  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-30 17:48:45.947  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.947  5432  5479 D BluetoothAdapter: STATE_ON
,10-30 17:48:45.949  5657  5686 D BtGatt.GattService: registerClient() - UUID=90d4f9b6-3a34-44df-989c-a2072cdb2edf
,10-30 17:48:45.950  5657  5673 D BtGatt.GattService: onClientRegistered() - UUID=90d4f9b6-3a34-44df-989c-a2072cdb2edf, clientIf=5
10-30 17:48:45.950  5432  5442 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-30 17:48:45.951  5657  5696 D BtGatt.GattService: start scan with filters
,10-30 17:48:45.953  5657  5676 D BtGatt.ScanManager: handling starting scan
,10-30 17:48:45.953  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-30 17:48:45.953  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.953  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-30 17:48:45.953  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.953  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-30 17:48:45.953  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-30 17:48:45.954  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.954  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-30 17:48:45.954  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-30 17:48:45.954  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.954  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.954  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-30 17:48:45.955  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-30 17:48:45.955  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.957  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.957  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:48:45.957  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.957  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.957  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-30 17:48:45.957  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:48:45.957  5432  5479 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-30 17:48:45.957  5657  5673 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-30 17:48:45.957  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:48:45.957  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.957  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:48:45.957  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:48:45.957  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:48:45.957  5657  5676 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-30 17:48:45.957  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.957  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-30 17:48:45.957  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:45.958  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:48:45.958  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@113a20b removed from the list
,10-30 17:48:45.958  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.959  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d88e8 removed from the list
10-30 17:48:45.959  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:48:45.959  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:48:45.959  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.959  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.959  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.959  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.959  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-30 17:48:45.959  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.959  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.959  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:48:45.959  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-30 17:48:45.959  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.960  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.960  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.960  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.960  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:48:45.960  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:45.960  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.961  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d88e8 not in the list
10-30 17:48:45.961  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-30 17:48:45.961  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-30 17:48:45.961  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-30 17:48:45.961  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.961  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.961  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.961  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-30 17:48:45.961  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.962  5657  5673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-30 17:48:45.962  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.962  5432  5479 D BluetoothAdapter: STATE_ON
10-30 17:48:45.962  5657  5676 D BtGatt.ScanManager: Starting BLE batch scan
10-30 17:48:45.962  5657  5676 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-30 17:48:45.963  5657  5696 D BtGatt.GattService: stopScan() - queue size =1
,10-30 17:48:45.963  5657  5667 D BtGatt.GattService: unregisterClient() - clientIf=5
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.964  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-30 17:48:45.964  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-30 17:48:45.965  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.965  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.966  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.966  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:48:45.966  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.966  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.966  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:45.966  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:48:45.966  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:45.966  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:48:45.966  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5853e7 removed from the list
10-30 17:48:45.966  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:48:45.966  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:48:45.966  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:45.966  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,10-30 17:48:45.966  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:45.966  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:45.966  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,10-30 17:48:45.966  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:48:45.966  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-30 17:48:45.966  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444cda6 removed from the list
10-30 17:48:45.966  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-30 17:48:45.966  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.966  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.966  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-30 17:48:45.967  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.967  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:45.967  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c4783 added. We now have 3 listener(s)
,10-30 17:48:45.967  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.967  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.968  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.968  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:48:45.968  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:48:45.968  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:48:45.968  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:48:45.969  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:48:45.969  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:45.969  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7968d00 added. We now have 4 listener(s)
10-30 17:48:45.969  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:45.969  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-30 17:48:45.970  5657  5673 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-30 17:48:45.970  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.971  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:48:45.976  5657  5673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-30 17:48:45.976  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.978  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:48:45.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:45.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:45.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:45.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:45.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:45.978  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-30 17:48:45.980  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:45.980  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-30 17:48:45.981  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:45.981  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6deb7e added. We now have 4 listener(s)
,10-30 17:48:45.982  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:48:45.982  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-30 17:48:45.982  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:48:45.983  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:45.983  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:45.983  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01d8df added. We now have 5 listener(s)
10-30 17:48:45.983  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:45.983  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:48:45.983  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-30 17:48:45.983  5657  5673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-30 17:48:45.983  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.983  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-30 17:48:45.983  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:48:45.983  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-30 17:48:45.983  5657  5676 D BtGatt.ScanManager: stopping BLe Batch
,10-30 17:48:45.985  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-30 17:48:45.988  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-30 17:48:45.988  5432  5479 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-30 17:48:45.988  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-30 17:48:45.988  5657  5673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-30 17:48:45.988  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.988  5657  5676 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-30 17:48:45.991  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.991  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-30 17:48:45.992  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-30 17:48:45.992  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-30 17:48:45.995  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:45.995  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-30 17:48:45.995  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-30 17:48:45.995  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-30 17:48:45.995  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-30 17:48:45.995  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:45.996  5432  5479 D BluetoothAdapter: STATE_ON
10-30 17:48:45.996  5657  5673 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
10-30 17:48:45.996  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:45.997  5657  5673 D BtGatt.GattService: current time is 232151972650
10-30 17:48:45.997  5657  5673 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-30 17:48:45.998  5657  5696 D BtGatt.GattService: registerClient() - UUID=a494102f-ec12-4dcf-9328-4f998ec31fa4
,10-30 17:48:45.998  5657  5673 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-30 17:48:45.999  5657  5673 D BtGatt.GattService: onClientRegistered() - UUID=a494102f-ec12-4dcf-9328-4f998ec31fa4, clientIf=5
,10-30 17:48:45.999  5432  5442 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-30 17:48:46.000  5657  5667 D BtGatt.GattService: start scan with filters
10-30 17:48:46.001  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-30 17:48:46.002  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.002  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-30 17:48:46.002  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.002  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-30 17:48:46.002  5657  5676 D BtGatt.ScanManager: handling starting scan
10-30 17:48:46.002  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-30 17:48:46.002  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.002  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-30 17:48:46.002  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-30 17:48:46.002  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.002  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.002  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-30 17:48:46.003  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-30 17:48:46.003  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:46.005  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.005  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:48:46.005  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.005  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.005  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-30 17:48:46.007  5657  5673 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-30 17:48:46.007  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:46.007  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:48:46.007  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:48:46.007  5657  5676 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-30 17:48:46.007  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-30 17:48:46.008  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-30 17:48:46.008  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:48:46.008  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-30 17:48:46.008  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:46.008  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:48:46.008  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34c4783 removed from the list
,10-30 17:48:46.008  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:46.008  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7968d00 removed from the list
10-30 17:48:46.008  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
10-30 17:48:46.008  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:48:46.008  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:46.009  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-30 17:48:46.009  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.009  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:48:46.009  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.009  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:48:46.009  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.009  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.009  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.009  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-30 17:48:46.009  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.010  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:46.010  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.010  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:48:46.010  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:46.010  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:46.010  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7968d00 not in the list
10-30 17:48:46.010  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-30 17:48:46.010  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-30 17:48:46.010  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-30 17:48:46.010  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.010  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.010  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.010  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-30 17:48:46.010  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.011  5432  5479 D BluetoothAdapter: STATE_ON
10-30 17:48:46.011  5657  5668 D BtGatt.GattService: stopScan() - queue size =1
,10-30 17:48:46.012  5657  5695 D BtGatt.GattService: unregisterClient() - clientIf=5
10-30 17:48:46.012  5657  5673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-30 17:48:46.012  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-30 17:48:46.013  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-30 17:48:46.013  5657  5676 D BtGatt.ScanManager: Starting BLE batch scan
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.013  5657  5676 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.013  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-30 17:48:46.013  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-30 17:48:46.014  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:46.015  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.015  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.015  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:48:46.015  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.016  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.016  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:46.016  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-30 17:48:46.016  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:46.016  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:48:46.016  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d01d8df removed from the list
10-30 17:48:46.016  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:48:46.016  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-30 17:48:46.016  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:46.016  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:46.016  5432  5432 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-30 17:48:46.016  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:46.016  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-30 17:48:46.016  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.016  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6deb7e removed from the list
10-30 17:48:46.016  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-30 17:48:46.016  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-30 17:48:46.016  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.016  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.016  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-30 17:48:46.016  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.017  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:46.017  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55523fb added. We now have 3 listener(s)
10-30 17:48:46.017  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-30 17:48:46.017  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.017  5432  5432 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.017  5432  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-30 17:48:46.017  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-30 17:48:46.018  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:48:46.018  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:48:46.018  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-30 17:48:46.018  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:46.018  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@558fc18 added. We now have 4 listener(s)
10-30 17:48:46.018  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:46.020  5657  5673 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-30 17:48:46.020  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:46.020  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-30 17:48:46.022  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-30 17:48:46.024  5657  5673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-30 17:48:46.025  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:48:46.027  5432  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-30 17:48:46.027  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-30 17:48:46.027  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-30 17:48:46.027  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-30 17:48:46.027  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-30 17:48:46.027  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-30 17:48:46.027  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-30 17:48:46.027  5432  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-30 17:48:46.029  5432  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-30 17:48:46.029  5432  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
10-30 17:48:46.029  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-30 17:48:46.030  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@431ec56 added. We now have 4 listener(s)
10-30 17:48:46.030  5657  5673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-30 17:48:46.030  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:46.030  5657  5676 D BtGatt.ScanManager: stopping BLe Batch
10-30 17:48:46.031  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-30 17:48:46.031  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-30 17:48:46.031  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-30 17:48:46.031  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-30 17:48:46.031  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc804d7 added. We now have 5 listener(s)
10-30 17:48:46.031  5432  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-30 17:48:46.031  5432  5479 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-30 17:48:46.031  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:48:46.031  5432  5479 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-30 17:48:46.031  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:48:46.031  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:46.031  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-30 17:48:46.031  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:46.032  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:48:46.032  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55523fb removed from the list
10-30 17:48:46.032  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:46.032  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@558fc18 removed from the list
10-30 17:48:46.032  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:46.032  5432  5479 D io.jxcore.node.ConnectivityMonitor: stop
,10-30 17:48:46.032  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:46.032  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:46.032  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:46.033  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.034  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-30 17:48:46.035  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.035  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.035  5657  5673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-30 17:48:46.035  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:46.035  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-30 17:48:46.035  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:48:46.035  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:46.035  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:46.035  5657  5676 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-30 17:48:46.035  5432  5479 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@558fc18 not in the list
10-30 17:48:46.035  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-30 17:48:46.035  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:46.035  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:46.036  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-30 17:48:46.036  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.036  5432  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-30 17:48:46.036  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-30 17:48:46.036  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-30 17:48:46.036  5432  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-30 17:48:46.036  5432  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc804d7 removed from the list
10-30 17:48:46.037  5432  5479 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-30 17:48:46.037  5432  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-30 17:48:46.037  5432  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-30 17:48:46.037  5432  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-30 17:48:46.037  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-30 17:48:46.037  5432  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@431ec56 removed from the list
10-30 17:48:46.037  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-30 17:48:46.038  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-30 17:48:46.038  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-30 17:48:46.038  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:48:46.038  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-30 17:48:46.038  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-30 17:48:46.039  5657  5673 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-30 17:48:46.039  5657  5673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-30 17:48:46.412  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-30 17:48:46.468  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-30 17:48:46.518  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-30 17:48:46.620   927  2839 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-30 17:48:46.730   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:47.731   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-30 17:48:48.186  5432  5738 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-30 17:48:48.186  5432  5738 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-30 17:48:48.975  5432  5738 W !!      : call onHalfStreamCopied
,10-30 17:48:48.975  5432  5738 I testCopyDataAndClose: closing input stream
,10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-30 17:48:49.750  5432  5738 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-30 17:48:51.411   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-30 17:48:52.732   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:53.541  5432  5740 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-30 17:48:53.541  5432  5740 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-30 17:48:53.576   927  2839 D ConnectivityService: handlePromptUnvalidated 101
,10-30 17:48:53.733   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:54.439   927  2839 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-30 17:48:54.735   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:55.541  5432  5479 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
10-30 17:48:55.541  5432  5479 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-30 17:48:55.541  5432  5479 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,10-30 17:48:55.558  5432  5740 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-30 17:48:55.558  5432  5740 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-30 17:48:55.558  5432  5740 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,10-30 17:48:55.668  5432  5741 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-30 17:48:55.668  5432  5741 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-30 17:48:55.736   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:56.683   927  2825 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,10-30 17:48:56.737   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-30 17:48:57.289  5432  5741 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-30 17:48:57.738   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-30 17:49:00.999  5432  5742 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-30 17:49:00.999  5432  5742 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-30 17:49:01.000  5432  5742 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
10-30 17:49:01.000  5432  5742 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-30 17:49:01.000  5432  5742 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-30 17:49:01.000  5432  5742 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-30 17:49:01.000  5432  5742 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-30 17:49:01.000  5432  5742 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-30 17:49:01.000  5432  5742 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-30 17:49:01.000  5432  5742 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-30 17:49:01.001  5432  5742 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-30 17:49:01.001  5432  5742 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-30 17:49:01.001  5432  5742 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-30 17:49:01.003  5432  5479 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-30 17:49:01.006  5432  5743 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-30 17:49:01.006  5432  5743 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-30 17:49:01.006  5432  5743 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
,10-30 17:49:01.006  5432  5743 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-30 17:49:01.006  5432  5743 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-30 17:49:01.007  5432  5743 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-30 17:49:01.007  5432  5743 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-30 17:49:01.007  5432  5743 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-30 17:49:01.012  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-30 17:49:01.012  5432  5479 I jxcore-log: 
,10-30 17:49:01.012  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-30 17:49:01.012  5432  5479 I jxcore-log: 
10-30 17:49:01.013  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-30 17:49:01.013  5432  5479 I jxcore-log: 
10-30 17:49:01.013  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-30 17:49:01.013  5432  5479 I jxcore-log: 
10-30 17:49:01.013  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG UnitTest_app: 'Total duration:  90739'
10-30 17:49:01.013  5432  5479 I jxcore-log: 
,10-30 17:49:01.015  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-30 17:49:01.015  5432  5479 I jxcore-log: 
,10-30 17:49:01.018  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.018  5432  5479 I jxcore-log: 
10-30 17:49:01.019  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.019  5432  5479 I jxcore-log: 
,10-30 17:49:01.019  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.019  5432  5479 I jxcore-log: 
10-30 17:49:01.020  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.020  5432  5479 I jxcore-log: 
10-30 17:49:01.020  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-30 17:49:01.020  5432  5479 I jxcore-log: 
10-30 17:49:01.020  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
10-30 17:49:01.020  5432  5479 I jxcore-log: 
10-30 17:49:01.021  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-30 17:49:01.021  5432  5479 I jxcore-log: 
10-30 17:49:01.021  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-30 17:49:01.021  5432  5479 I jxcore-log: 
10-30 17:49:01.021  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-30 17:49:01.021  5432  5479 I jxcore-log: 
,10-30 17:49:01.022  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.022  5432  5479 I jxcore-log: 
10-30 17:49:01.022  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.022  5432  5479 I jxcore-log: 
10-30 17:49:01.022  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-30 17:49:01.022  5432  5479 I jxcore-log: 
10-30 17:49:01.022  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
10-30 17:49:01.022  5432  5479 I jxcore-log: 
10-30 17:49:01.022  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-30 17:49:01.022  5432  5479 I jxcore-log: 
10-30 17:49:01.023  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-30 17:49:01.023  5432  5479 I jxcore-log: 
,10-30 17:49:01.023  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-30 17:49:01.023  5432  5479 I jxcore-log: 
10-30 17:49:01.023  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-30 17:49:01.023  5432  5479 I jxcore-log: 
10-30 17:49:01.023  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-30 17:49:01.023  5432  5479 I jxcore-log: 
10-30 17:49:01.023  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.023  5432  5479 I jxcore-log: 
10-30 17:49:01.024  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.024  5432  5479 I jxcore-log: 
10-30 17:49:01.024  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-30 17:49:01.024  5432  5479 I jxcore-log: 
,10-30 17:49:01.024  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-30 17:49:01.024  5432  5479 I jxcore-log: 
10-30 17:49:01.024  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-30 17:49:01.024  5432  5479 I jxcore-log: 
10-30 17:49:01.025  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.025  5432  5479 I jxcore-log: 
10-30 17:49:01.026  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.026  5432  5479 I jxcore-log: 
10-30 17:49:01.026  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.026  5432  5479 I jxcore-log: 
10-30 17:49:01.027  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.027  5432  5479 I jxcore-log: 
,10-30 17:49:01.027  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-30 17:49:01.027  5432  5479 I jxcore-log: 
10-30 17:49:01.027  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-30 17:49:01.027  5432  5479 I jxcore-log: 
10-30 17:49:01.027  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-30 17:49:01.027  5432  5479 I jxcore-log: 
10-30 17:49:01.028  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.028  5432  5479 I jxcore-log: 
,10-30 17:49:01.028  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.028  5432  5479 I jxcore-log: 
,10-30 17:49:01.028  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.028  5432  5479 I jxcore-log: 
10-30 17:49:01.028  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.028  5432  5479 I jxcore-log: 
10-30 17:49:01.029  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.029  5432  5479 I jxcore-log: 
10-30 17:49:01.029  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.029  5432  5479 I jxcore-log: 
10-30 17:49:01.029  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.029  5432  5479 I jxcore-log: 
10-30 17:49:01.029  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.029  5432  5479 I jxcore-log: 
10-30 17:49:01.029  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.029  5432  5479 I jxcore-log: 
10-30 17:49:01.029  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.029  5432  5479 I jxcore-log: 
,10-30 17:49:01.030  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.030  5432  5479 I jxcore-log: 
10-30 17:49:01.030  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-30 17:49:01.030  5432  5479 I jxcore-log: 
10-30 17:49:01.030  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-30 17:49:01.030  5432  5479 I jxcore-log: 
10-30 17:49:01.030  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-30 17:49:01.030  5432  5479 I jxcore-log: 
10-30 17:49:01.030  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.030  5432  5479 I jxcore-log: 
10-30 17:49:01.031  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.031  5432  5479 I jxcore-log: 
10-30 17:49:01.031  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.031  5432  5479 I jxcore-log: 
,10-30 17:49:01.031  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.031  5432  5479 I jxcore-log: 
10-30 17:49:01.031  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.031  5432  5479 I jxcore-log: 
10-30 17:49:01.032  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-30 17:49:01.032  5432  5479 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-30 17:49:01.032  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.032  5432  5479 I jxcore-log: 
10-30 17:49:01.032  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.032  5432  5479 I jxcore-log: 
10-30 17:49:01.032  5432  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-30 17:49:01.032  5432  5479 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-30 17:49:01.032  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-30 17:49:01.032  5432  5479 I jxcore-log: 
,10-30 17:49:01.033  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-30 17:49:01.033  5432  5479 I jxcore-log: 
10-30 17:49:01.033  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-30 17:49:01.033  5432  5479 I jxcore-log: 
10-30 17:49:01.033  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-30 17:49:01.033  5432  5479 I jxcore-log: 
10-30 17:49:01.033  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-30 17:49:01.033  5432  5479 I jxcore-log: 
10-30 17:49:01.034  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-30 17:49:01.034  5432  5479 I jxcore-log: 
10-30 17:49:01.034  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-30 17:49:01.034  5432  5479 I jxcore-log: 
10-30 17:49:01.038  5432  5432 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-30 17:49:01.039  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-30 17:49:01.039  5432  5479 I jxcore-log: 
10-30 17:49:01.039  5432  5479 I jxcore-log: 2016-10-30 21:49:01 - WARN testUtils: 'myNameCallback not set!'
10-30 17:49:01.039  5432  5479 I jxcore-log: 
,10-30 17:49:03.103  5432  5479 I jxcore-log: 2016-10-30 21:49:03 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
10-30 17:49:03.103  5432  5479 I jxcore-log: 
,10-30 17:49:03.105  5432  5479 I jxcore-log: 2016-10-30 21:49:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-30 17:49:03.105  5432  5479 I jxcore-log: 
,10-30 17:49:03.446  5432  5479 I jxcore-log: 2016-10-30 21:49:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-30 17:49:03.446  5432  5479 I jxcore-log: 
,10-30 17:49:03.459  5432  5479 I jxcore-log: 2016-10-30 21:49:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-30 17:49:03.459  5432  5479 I jxcore-log: 
,10-30 17:49:04.479   927  5714 D NetlinkSocketObserver: NeighborEvent{elapsedMs=250634, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-30 17:49:04.576  5432  5479 I jxcore-log: 2016-10-30 21:49:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-30 17:49:04.576  5432  5479 I jxcore-log: 
,10-30 17:49:04.765  5432  5479 I jxcore-log: 2016-10-30 21:49:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-30 17:49:04.765  5432  5479 I jxcore-log: 
,10-30 17:49:04.770  5432  5479 I jxcore-log: 2016-10-30 21:49:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-30 17:49:04.770  5432  5479 I jxcore-log: 
,10-30 17:49:04.775  5432  5479 I jxcore-log: 2016-10-30 21:49:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-30 17:49:04.775  5432  5479 I jxcore-log: 
,10-30 17:49:05.257  5432  5479 I jxcore-log: 2016-10-30 21:49:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-30 17:49:05.257  5432  5479 I jxcore-log: 
,10-30 17:49:05.302  5432  5479 I jxcore-log: 2016-10-30 21:49:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-30 17:49:05.302  5432  5479 I jxcore-log: 
,10-30 17:49:05.315  5432  5479 I jxcore-log: 2016-10-30 21:49:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-30 17:49:05.315  5432  5479 I jxcore-log: 
,10-30 17:49:05.319  5432  5479 I jxcore-log: 2016-10-30 21:49:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-30 17:49:05.319  5432  5479 I jxcore-log: 
,10-30 17:49:05.608  5432  5479 I jxcore-log: 2016-10-30 21:49:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-30 17:49:05.608  5432  5479 I jxcore-log: 
,10-30 17:49:05.737  5432  5479 I jxcore-log: 2016-10-30 21:49:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-30 17:49:05.737  5432  5479 I jxcore-log: 
,10-30 17:49:06.098  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-30 17:49:06.098  5432  5479 I jxcore-log: 
,10-30 17:49:06.106  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-30 17:49:06.106  5432  5479 I jxcore-log: 
,10-30 17:49:06.110  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-30 17:49:06.110  5432  5479 I jxcore-log: 
,10-30 17:49:06.116  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-30 17:49:06.116  5432  5479 I jxcore-log: 
,10-30 17:49:06.121  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-30 17:49:06.121  5432  5479 I jxcore-log: 
,10-30 17:49:06.148  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-30 17:49:06.148  5432  5479 I jxcore-log: 
,10-30 17:49:06.183  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-30 17:49:06.183  5432  5479 I jxcore-log: 
,10-30 17:49:06.191  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-30 17:49:06.191  5432  5479 I jxcore-log: 
,10-30 17:49:06.197  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-30 17:49:06.197  5432  5479 I jxcore-log: 
,10-30 17:49:06.212  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-30 17:49:06.212  5432  5479 I jxcore-log: 
,10-30 17:49:06.216  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-30 17:49:06.216  5432  5479 I jxcore-log: 
,10-30 17:49:06.222  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-30 17:49:06.222  5432  5479 I jxcore-log: 
,10-30 17:49:06.227  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-30 17:49:06.227  5432  5479 I jxcore-log: 
,10-30 17:49:06.240  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-30 17:49:06.240  5432  5479 I jxcore-log: 
,10-30 17:49:06.246  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-30 17:49:06.246  5432  5479 I jxcore-log: 
,10-30 17:49:06.268  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-30 17:49:06.268  5432  5479 I jxcore-log: 
,10-30 17:49:06.279  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-30 17:49:06.279  5432  5479 I jxcore-log: 
,10-30 17:49:06.290  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-30 17:49:06.290  5432  5479 I jxcore-log: 
,10-30 17:49:06.300  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-30 17:49:06.300  5432  5479 I jxcore-log: 
,10-30 17:49:06.313  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-30 17:49:06.313  5432  5479 I jxcore-log: 
,10-30 17:49:06.324  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-30 17:49:06.324  5432  5479 I jxcore-log: 
,10-30 17:49:06.331  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-30 17:49:06.331  5432  5479 I jxcore-log: 
,10-30 17:49:06.353  5432  5479 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-30 17:49:06.354  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - INFO testUtils: 'BLE multiple advertisement supported'
10-30 17:49:06.354  5432  5479 I jxcore-log: 
,10-30 17:49:06.499  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:06.499  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:06.499  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:06.499  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:06.499  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:06.499  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:06.499  5432  5479 I jxcore-log: 
,10-30 17:49:06.826  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:06.826  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:06.826  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:06.826  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:06.826  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:06.826  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:06.826  5432  5479 I jxcore-log: 
,10-30 17:49:06.832  5432  5479 I jxcore-log: 2016-10-30 21:49:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:06.832  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:06.832  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:06.832  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:06.832  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:06.832  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:06.832  5432  5479 I jxcore-log: 
,10-30 17:49:07.460  5432  5479 I jxcore-log: 2016-10-30 21:49:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:07.460  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:07.460  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:07.460  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:07.460  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:07.460  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:07.460  5432  5479 I jxcore-log: 
,10-30 17:49:07.466  5432  5479 I jxcore-log: 2016-10-30 21:49:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:07.466  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:07.466  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:07.466  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:07.466  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:07.466  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:07.466  5432  5479 I jxcore-log: 
,10-30 17:49:07.739   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:49:08.581  5432  5479 I jxcore-log: 2016-10-30 21:49:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:08.581  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:08.581  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:08.581  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:08.581  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:08.581  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:08.581  5432  5479 I jxcore-log: 
,10-30 17:49:08.587  5432  5479 I jxcore-log: 2016-10-30 21:49:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:08.587  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:08.587  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:08.587  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:08.587  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:08.587  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:08.587  5432  5479 I jxcore-log: 
,10-30 17:49:08.740   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:49:09.617  5432  5479 I jxcore-log: 2016-10-30 21:49:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:09.617  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:09.617  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:09.617  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:09.617  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:09.617  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:09.617  5432  5479 I jxcore-log: 
,10-30 17:49:09.622  5432  5479 I jxcore-log: 2016-10-30 21:49:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:09.622  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:09.622  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:09.622  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:09.622  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:09.622  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:09.622  5432  5479 I jxcore-log: 
,10-30 17:49:09.741   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:49:10.657  5432  5479 I jxcore-log: 2016-10-30 21:49:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:10.657  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:10.657  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:10.657  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:10.657  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:10.657  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:10.657  5432  5479 I jxcore-log: 
,10-30 17:49:10.662  5432  5479 I jxcore-log: 2016-10-30 21:49:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:10.662  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:10.662  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:10.662  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:10.662  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:10.662  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:10.662  5432  5479 I jxcore-log: 
,10-30 17:49:10.742   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:49:11.418   927  5714 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257573, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,10-30 17:49:11.691  5432  5479 I jxcore-log: 2016-10-30 21:49:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:11.691  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:11.691  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:11.691  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:11.691  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:11.691  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:11.691  5432  5479 I jxcore-log: 
,10-30 17:49:11.695  5432  5479 I jxcore-log: 2016-10-30 21:49:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:11.695  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:11.695  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:11.695  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:11.695  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:11.695  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:11.695  5432  5479 I jxcore-log: 
,10-30 17:49:11.743   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-30 17:49:12.732  5432  5479 I jxcore-log: 2016-10-30 21:49:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:12.732  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:12.732  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:12.732  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:12.732  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:12.732  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:12.732  5432  5479 I jxcore-log: 
,10-30 17:49:12.738  5432  5479 I jxcore-log: 2016-10-30 21:49:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:12.738  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:12.738  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:12.738  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:12.738  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:12.738  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:12.738  5432  5479 I jxcore-log: 
,10-30 17:49:12.743   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-30 17:49:13.771  5432  5479 I jxcore-log: 2016-10-30 21:49:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:13.771  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:13.771  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:13.771  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:13.771  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:13.771  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:13.771  5432  5479 I jxcore-log: 
,10-30 17:49:13.776  5432  5479 I jxcore-log: 2016-10-30 21:49:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:13.776  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:13.776  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:13.776  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:13.776  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:13.776  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:13.776  5432  5479 I jxcore-log: 
,10-30 17:49:14.808  5432  5479 I jxcore-log: 2016-10-30 21:49:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:14.808  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:14.808  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:14.808  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:14.808  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:14.808  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:14.808  5432  5479 I jxcore-log: 
,10-30 17:49:14.811  5432  5479 I jxcore-log: 2016-10-30 21:49:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:14.811  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:14.811  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:14.811  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:14.811  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:14.811  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:14.811  5432  5479 I jxcore-log: 
,10-30 17:49:15.871  5432  5479 I jxcore-log: 2016-10-30 21:49:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:15.871  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:15.871  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:15.871  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:15.871  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:15.871  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:15.871  5432  5479 I jxcore-log: 
,10-30 17:49:15.876  5432  5479 I jxcore-log: 2016-10-30 21:49:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:15.876  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:15.876  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:15.876  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:15.876  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:15.876  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:15.876  5432  5479 I jxcore-log: 
,10-30 17:49:17.610  5432  5479 I jxcore-log: 2016-10-30 21:49:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:17.610  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:17.610  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:17.610  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:17.610  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:17.610  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:17.610  5432  5479 I jxcore-log: 
,10-30 17:49:17.616  5432  5479 I jxcore-log: 2016-10-30 21:49:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:17.616  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:17.616  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:17.616  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:17.616  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:17.616  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:17.616  5432  5479 I jxcore-log: 
,10-30 17:49:18.642  5432  5479 I jxcore-log: 2016-10-30 21:49:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:18.642  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:18.642  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:18.642  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:18.642  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:18.642  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:18.642  5432  5479 I jxcore-log: 
10-30 17:49:18.646  5432  5479 I jxcore-log: 2016-10-30 21:49:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:18.646  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:18.646  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:18.646  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:18.646  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:18.646  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:18.646  5432  5479 I jxcore-log: 
,10-30 17:49:19.676  5432  5479 I jxcore-log: 2016-10-30 21:49:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:19.676  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:19.676  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:19.676  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:19.676  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:19.676  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:19.676  5432  5479 I jxcore-log: 
,10-30 17:49:19.680  5432  5479 I jxcore-log: 2016-10-30 21:49:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:19.680  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:19.680  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:19.680  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:19.680  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:19.680  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:19.680  5432  5479 I jxcore-log: 
,10-30 17:49:20.721  5432  5479 I jxcore-log: 2016-10-30 21:49:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:20.721  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:20.721  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:20.721  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:20.721  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:20.721  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:20.721  5432  5479 I jxcore-log: 
,10-30 17:49:20.725  5432  5479 I jxcore-log: 2016-10-30 21:49:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:20.725  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:20.725  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:20.725  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:20.725  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:20.725  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:20.725  5432  5479 I jxcore-log: 
,10-30 17:49:22.526  5432  5479 I jxcore-log: 2016-10-30 21:49:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-30 17:49:22.526  5432  5479 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-30 17:49:22.526  5432  5479 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-30 17:49:22.526  5432  5479 I jxcore-log: emit@events.js:82:1
10-30 17:49:22.526  5432  5479 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-30 17:49:22.526  5432  5479 I jxcore-log: emit@events.js:82:1'
10-30 17:49:22.526  5432  5479 I jxcore-log: 
,10-30 17:49:22.539  5432  5479 E jxcore  : Error!: error is undefined
10-30 17:49:22.539  5432  5479 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-30 17:49:22.544  5432  5479 I jxcore-log: 2016-10-30 21:49:22 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-30 17:49:22.544  5432  5479 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
10-30 17:49:22.544  5432  5479 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-30 17:49:22.544  5432  5479 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-30 17:49:22.544  5432  5479 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-30 17:49:22.544  5432  5479 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-30 17:49:22.544  5432  5479 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-30 17:49:22.544  5432  5479 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-30 17:49:22.545  5432  5479 I jxcore-log: 2016-10-30 21:49:22 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-30 17:49:22.545  5432  5479 I jxcore-log: 
,10-30 17:49:22.547  5432  5479 E jxcore-log: TypeError: 
10-30 17:49:22.547  5432  5479 E jxcore-log: error is undefined
10-30 17:49:22.547  5432  5479 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
10-30 17:49:22.547  5432  5479 E jxcore-log: 
,10-30 17:49:22.610   927  2767 W InputDispatcher: channel '83ff199 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-30 17:49:22.611   927  2767 E InputDispatcher: channel '83ff199 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-30 17:49:22.622   927  3292 D GraphicsStats: Buffer count: 2
,10-30 17:49:22.625   527   527 I Zygote  : Process 5432 exited cleanly (139)
10-30 17:49:22.630   927  3666 I WindowState: WIN DEATH: Window{83ff199 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-30 17:49:22.630   927  3666 W InputDispatcher: Attempted to unregister already unregistered input channel '83ff199 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-30 17:49:22.625   927  2834 D WifiService: Client connection lost with reason: 4
,10-30 17:49:22.631   927  3026 I ActivityManager: Process com.test.thalitest (pid 5432) has died
,10-30 17:49:22.663   927  3026 I ActivityManager: Start proc 5746:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-30 17:49:22.992   927  3292 I WindowManager: Screenshot max retries 4 of Token{11b3503 ActivityRecord{f0851b2 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{924415d u0 Starting com.test.thalitest} drawState=4
,10-30 17:49:23.068  5744  5744 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-30 17:49:23.072  5744  5744 D AndroidRuntime: CheckJNI is OFF
,10-30 17:49:23.080  5746  5746 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-30 17:49:23.097  5746  5746 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-30 17:49:23.099  5744  5744 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-30 17:49:23.102  5746  5746 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9255-9257)
,10-30 17:49:23.102  5746  5746 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-30 17:49:23.111  5746  5746 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d34a1e}
,10-30 17:49:23.111  5746  5746 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-30 17:49:23.111  5746  5746 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-30 17:49:23.114  5746  5746 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-30 17:49:23.115  5746  5746 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-30 17:49:23.124  5744  5744 I Radio-JNI: register_android_hardware_Radio DONE
,10-30 17:49:23.125  5746  5746 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-30 17:49:23.133  5746  5746 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-30 17:49:23.133  5746  5746 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-30 17:49:23.133  5746  5746 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-30 17:49:23.133  5746  5746 I Adreno  : Build Date                       : 12/06/15
10-30 17:49:23.133  5746  5746 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-30 17:49:23.133  5746  5746 I Adreno  : Local Branch                     : mybranch17112971
10-30 17:49:23.133  5746  5746 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-30 17:49:23.133  5746  5746 I Adreno  : Remote Branch                    : NONE
10-30 17:49:23.133  5746  5746 I Adreno  : Reconstruct Branch               : NOTHING
,10-30 17:49:23.139  5744  5744 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-30 17:49:23.145   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
10-30 17:49:23.145   927   940 I ActivityManager: Killing 5746:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-30 17:49:23.256   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-30 17:49:23.257   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-30 17:49:23.259   927   950 I art     : Starting a blocking GC Explicit
,10-30 17:49:23.260   927   940 E ActivityManager: Failure starting process com.test.thalitest
10-30 17:49:23.260   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-30 17:49:23.260   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:49:23.260   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:49:23.260   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-30 17:49:23.260   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-30 17:49:23.262   927   940 I ActivityManager:   Force finishing activity ActivityRecord{f0851b2 u0 com.test.thalitest/.MainActivity t2}
,10-30 17:49:23.282   927   945 W WindowManager: Failed looking up window
10-30 17:49:23.282   927   945 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@1facf34 does not exist
10-30 17:49:23.282   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-30 17:49:23.282   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-30 17:49:23.282   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-30 17:49:23.282   927   945 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-30 17:49:23.282   927   945 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-30 17:49:23.282   927   945 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-30 17:49:23.282   927   945 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-30 17:49:23.282   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:49:23.282   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:49:23.282   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-30 17:49:23.282   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-30 17:49:23.283   927  3712 W ActivityManager: Spurious death for ProcessRecord{80faaa0 0:com.test.thalitest/u0a77}, curProc for 5746: null
,10-30 17:49:23.356   927   950 I art     : Explicit concurrent mark sweep GC freed 54245(3MB) AllocSpace objects, 16(584KB) LOS objects, 33% free, 29MB/43MB, paused 1.665ms total 96.955ms
,10-30 17:49:23.379   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-30 17:49:23.382  5744  5744 I art     : System.exit called, status: 0
,10-30 17:49:23.382  5744  5744 I AndroidRuntime: VM exiting with result code 0.
,10-30 17:49:23.397   927   950 I ActivityManager: Start proc 5772:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-30 17:49:23.398   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-30 17:49:23.403   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-30 17:49:23.408  3975  4039 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-30 17:49:23.409  5657  5657 D BluetoothMapAppObserver: onReceive
10-30 17:49:23.409  5657  5657 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-30 17:49:23.411  3530  3530 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-30 17:49:23.428   927  2768 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-30 17:49:23.444  3530  5784 I Keyboard.Facilitator.DecoderInitializer: run()
,10-30 17:49:23.445  3277  5785 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-30 17:49:23.460    28    28 W kworker/1:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-30 17:49:23.467    28    28 W kworker/1:1: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-30 17:49:23.476  3530  5784 I Decoder : createOrResetDecoder
,10-30 17:49:23.481  3632  3632 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-30 17:49:23.482  3463  3463 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,10-30 17:49:23.483  3463  3463 D AndroidRuntime: Shutting down VM
--------- beginning of crash
10-30 17:49:23.484  3463  3463 E AndroidRuntime: FATAL EXCEPTION: main
10-30 17:49:23.484  3463  3463 E AndroidRuntime: Process: com.google.process.gapps, PID: 3463
10-30 17:49:23.484  3463  3463 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-30 17:49:23.484  3463  3463 E AndroidRuntime: 	... 8 more
,10-30 17:49:23.497  3463  3463 I Process : Sending signal. PID: 3463 SIG: 9
,10-30 17:49:23.499   927   940 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2708)
,10-30 17:49:23.499   927   940 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
10-30 17:49:23.499   927   940 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-30 17:49:23.499   927   940 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-30 17:49:23.504   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-30 17:49:23.504    28    28 W kworker/1:1: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-30 17:49:23.530  3277  3300 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
10-30 17:49:23.531  3277  3300 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-30 17:49:23.531  3277  3300 E AndroidRuntime: Process: android.process.acore, PID: 3277
10-30 17:49:23.531  3277  3300 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:49:23.531  3277  3300 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-30 17:49:23.539   927  2834 D WifiService: Client connection lost with reason: 4
,10-30 17:49:23.542   927   940 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,10-30 17:49:23.542   927   940 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
10-30 17:49:23.542   927   940 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 20999ms
10-30 17:49:23.545  3277  5785 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-30 17:49:23.545  3277  5785 I Process : Sending signal. PID: 3277 SIG: 9
,10-30 17:49:23.554   927   940 I ActivityManager: Start proc 5792:com.google.process.gapps/u0a12 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,10-30 17:49:23.556   927  3666 W ActivityManager: Spurious death for ProcessRecord{4b85133 5792:com.google.process.gapps/u0a12}, curProc for 3463: null
10-30 17:49:23.556  3653  3814 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
10-30 17:49:23.557   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
10-30 17:49:23.558   927   939 E PackageManager: Failed to write settings, restoring backup
10-30 17:49:23.558   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-30 17:49:23.558   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-30 17:49:23.558   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-30 17:49:23.558   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-30 17:49:23.558   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-30 17:49:23.558   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-30 17:49:23.558   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:49:23.558   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-30 17:49:23.562   927   940 E DropBoxManagerService: Can't write: system_server_wtf
10-30 17:49:23.562   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-30 17:49:23.562   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-30 17:49:23.562   927   940 E DropBoxManagerService: 	... 13 more
,10-30 17:49:23.571   927   937 I ActivityManager: Start proc 5800:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,10-30 17:49:23.572  3653  3814 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-30 17:49:23.572  3653  3814 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3653
10-30 17:49:23.572  3653  3814 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-30 17:49:23.572  3653  3814 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-30 17:49:23.575   927  3279 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-30 17:49:23.575   927  5807 E DropBoxManagerService: Can't write: system_app_crash
10-30 17:49:23.575   927  5807 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-30 17:49:23.575   927  5807 E DropBoxManagerService: 	... 5 more
,10-30 17:49:23.579  3653  3814 I Process : Sending signal. PID: 3653 SIG: 9
,10-30 17:49:23.642   927  2767 W InputDispatcher: channel 'a721e41 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-30 17:49:23.642   927  2767 E InputDispatcher: channel 'a721e41 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-30 17:49:23.643   927  3279 D GraphicsStats: Buffer count: 1
10-30 17:49:23.643   927   937 I WindowState: WIN DEATH: Window{a721e41 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
10-30 17:49:23.643   927   937 W InputDispatcher: Attempted to unregister already unregistered input channel 'a721e41 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-30 17:49:23.659   927  3279 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3653) has died
10-30 17:49:23.660   927  3279 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-30 17:49:23.662   927  3279 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-30 17:49:23.684   927   940 I ActivityManager: Start proc 5819:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-30 17:49:23.684   927  3292 I ActivityManager: Process android.process.acore (pid 3277) has died
,10-30 17:49:23.685   927  3292 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-30 17:49:23.869   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
