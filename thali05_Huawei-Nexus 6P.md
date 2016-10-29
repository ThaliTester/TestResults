#### Test 91479574d68feab_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-29 01:41:51.516  5640  5683 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
10-29 01:41:51.560  3809  3809 I ConfigFetchService: fetch service done; releasing wakelock
10-29 01:41:51.562  3809  3809 I ConfigFetchService: stopping self
10-29 01:41:51.578  3809  5001 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
10-29 01:41:51.607  5640  5683 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
10-29 01:41:51.657  3809  5001 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
10-29 01:41:51.693  5640  5683 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,10-29 01:41:54.164  5695  5695 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-29 01:41:54.170  5695  5695 D AndroidRuntime: CheckJNI is OFF
10-29 01:41:54.198  5695  5695 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-29 01:41:54.233  5695  5695 I Radio-JNI: register_android_hardware_Radio DONE
10-29 01:41:54.250  5695  5695 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-29 01:41:54.256   930  3229 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-29 01:41:54.301   930  3229 I ActivityManager: Start proc 5704:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-29 01:41:54.322  5695  5695 D AndroidRuntime: Shutting down VM
,10-29 01:41:54.638   930   940 I WindowManager: Screenshot max retries 4 of Token{751449f ActivityRecord{26cae3e u0 com.test.thalitest/.MainActivity t2}} appWin=Window{66e4716 u0 Starting com.test.thalitest} drawState=2
,10-29 01:41:54.719  5704  5704 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-29 01:41:54.742  5704  5704 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-29 01:41:54.810  5704  5704 I LibraryLoader: Time to load native libraries: 63 ms (timestamps 9594-9657)
,10-29 01:41:54.810  5704  5704 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-29 01:41:54.838  5704  5704 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b5a66c}
,10-29 01:41:54.839  5704  5704 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-29 01:41:54.839  5704  5704 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-29 01:41:54.842  5704  5704 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-29 01:41:54.843  5704  5704 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-29 01:41:54.891  5704  5704 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-29 01:41:54.912  5704  5704 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-29 01:41:54.912  5704  5704 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-29 01:41:54.912  5704  5704 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-29 01:41:54.912  5704  5704 I Adreno  : Build Date                       : 12/06/15
10-29 01:41:54.912  5704  5704 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-29 01:41:54.912  5704  5704 I Adreno  : Local Branch                     : mybranch17112971
10-29 01:41:54.912  5704  5704 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-29 01:41:54.912  5704  5704 I Adreno  : Remote Branch                    : NONE
10-29 01:41:54.912  5704  5704 I Adreno  : Reconstruct Branch               : NOTHING
,10-29 01:41:54.946   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c84a225:true
,10-29 01:41:54.967  4245  4245 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27201]" dev="sockfs" ino=27201 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-29 01:41:54.967  4245  4245 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[27201]" dev="sockfs" ino=27201 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-29 01:41:54.980  5704  5704 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-29 01:41:54.988  5704  5704 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-29 01:41:55.019  5704  5741 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-29 01:41:55.014  4245  4245 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33938]" dev="sockfs" ino=33938 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-29 01:41:55.014  4245  4245 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33938]" dev="sockfs" ino=33938 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-29 01:41:55.017  3209  3209 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[27213]" dev="sockfs" ino=27213 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-29 01:41:55.017  3209  3209 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[27213]" dev="sockfs" ino=27213 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-29 01:41:55.024  5704  5728 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-29 01:41:55.059  5704  5741 I OpenGLRenderer: Initialized EGL, version 1.4
,10-29 01:41:55.140   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +498ms (total +866ms)
,10-29 01:41:55.163  5704  5704 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5704
,10-29 01:41:55.248  5704  5704 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-29 01:41:55.388  5704  5744 D jxcore_app_log: JniHelper::setJavaVM(0xf513c000), pthread_self() = -583530192
,10-29 01:41:55.391  5704  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-29 01:41:55.391  5704  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-29 01:41:55.391  5704  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-29 01:41:55.391  5704  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-29 01:41:55.391  5704  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-29 01:41:55.392  5704  5744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f756ad added. We now have 1 listener(s)
,10-29 01:41:55.394  5704  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-29 01:41:55.394  5704  5744 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-29 01:41:55.395  5704  5744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-29 01:41:55.395  5704  5744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-29 01:41:55.397  5704  5744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c047c30 added. We now have 1 listener(s)
10-29 01:41:55.397  5704  5744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 01:41:55.401   930  3044 D WifiService: New client listening to asynchronous messages
10-29 01:41:55.401  5704  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-29 01:41:55.401  5704  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,10-29 01:41:55.401  5704  5744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
10-29 01:41:55.402  5704  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-29 01:41:55.402  5704  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-29 01:41:55.402  5704  5744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-29 01:41:55.402  5704  5744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,10-29 01:41:55.403  5704  5744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 01:41:55.403  5704  5744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-29 01:41:55.409  5704  5744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-29 01:41:55.409  5704  5744 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:41:55.409  5704  5744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:41:55.409  5704  5744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:41:55.409  5704  5744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:41:55.409  5704  5744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:41:55.409  5704  5744 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:41:55.409  5704  5744 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:41:55.409  5704  5744 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:41:55.409  5704  5744 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-29 01:41:55.409  5704  5744 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:41:55.410  5704  5744 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-29 01:41:55.412  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:41:55.415  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:41:55.427  5704  5704 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-29 01:41:55.682  5704  5713 I art     : Background sticky concurrent mark sweep GC freed 84899(8MB) AllocSpace objects, 17(1096KB) LOS objects, 20% free, 25MB/32MB, paused 2.185ms total 100.620ms
,10-29 01:41:55.942  5704  5713 I art     : Background partial concurrent mark sweep GC freed 56277(6MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 26MB/42MB, paused 1.523ms total 107.590ms
,10-29 01:41:56.035  5704  5750 W jxcore-log: Initializing JXcore engine
,10-29 01:41:56.035  5704  5750 W jxcore-log: JXcore engine is ready
,10-29 01:41:56.061  5750  5750 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12591 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-29 01:41:56.061  5750  5750 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15455]" dev="sockfs" ino=15455 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-29 01:41:56.061  5750  5750 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-29 01:41:56.061  5750  5750 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32229]" dev="sockfs" ino=32229 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-29 01:41:56.070  5704  5750 W jxcore-log: Starting JXcore engine
,10-29 01:41:56.119  5704  5750 W jxcore-log: Platform android
10-29 01:41:56.119  5704  5750 W jxcore-log: 
,10-29 01:41:56.119  5704  5750 W jxcore-log: Process ARCH arm
10-29 01:41:56.119  5704  5750 W jxcore-log: 
,10-29 01:41:56.301  5704  5750 I jxcore-log: JXcore Cordova bridge is ready!
10-29 01:41:56.301  5704  5750 I jxcore-log: 
,10-29 01:41:56.301  5704  5750 W jxcore-log: JXcore engine is started
,10-29 01:41:56.313  5704  5744 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-29 01:41:56.320  5704  5704 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-29 01:41:56.570  3645  3645 I ConfigService: onDestroy
,10-29 01:41:59.568   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:42:00.569   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:42:01.570   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:42:02.571   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:42:03.572   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:42:04.573   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-29 01:42:05.078  3645  5752 I VacuumService: Vacuum at: now=1477719725078 tag=VacuumService
,10-29 01:42:05.115  3645  5755 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-29 01:42:05.133  4902  4932 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-29 01:42:05.135  4902  4902 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-29 01:42:05.145  3645  5753 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-29 01:42:05.148  3645  5753 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-29 01:42:05.175  3645  5753 W Uploader:  no longer exists, so no auth token.
,10-29 01:42:05.181  3645  5755 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-29 01:42:05.574  3645  5757 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-29 01:42:05.655  3645  5753 W Uploader:  no longer exists, so no auth token.
,10-29 01:42:05.667  3645  5755 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-29 01:42:05.765  3645  5757 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-29 01:42:06.029  5704  5750 I jxcore-log: 2016-10-29 05:42:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-29 01:42:06.029  5704  5750 I jxcore-log: 
,10-29 01:42:06.031  5704  5750 I jxcore-log: 2016-10-29 05:42:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-29 01:42:06.031  5704  5750 I jxcore-log: 
,10-29 01:42:06.035  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:42:06.035  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:06.035  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:06.035  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:06.035  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:42:06.035  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:06.035  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:06.035  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:42:06.037  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 01:42:06.038  5704  5750 I jxcore-log: 2016-10-29 05:42:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-29 01:42:06.038  5704  5750 I jxcore-log: 
,10-29 01:42:06.039  5704  5750 I jxcore-log: 2016-10-29 05:42:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-29 01:42:06.039  5704  5750 I jxcore-log: 
,10-29 01:42:06.292  5704  5750 I jxcore-log: 2016-10-29 05:42:06 - DEBUG UnitTest_app: 'Running unit tests'
10-29 01:42:06.292  5704  5750 I jxcore-log: 
,10-29 01:42:06.292  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:42:06.292  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444dde3 added. We now have 2 listener(s)
10-29 01:42:06.293  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:42:06.293  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:42:06.293  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 01:42:06.294  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:42:06.294  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7fd3e0 added. We now have 2 listener(s)
10-29 01:42:06.294  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 01:42:06.295  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-29 01:42:06.298  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 01:42:06.301  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:42:06.301  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:06.301  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:06.301  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:06.301  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:42:06.301  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:06.301  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:06.301  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:42:06.302  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:06.302  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:42:06.302  5704  5750 D executeNativeTests: Running unit tests
,10-29 01:42:06.307  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:06.312  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:06.338  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-29 01:42:06.338  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e added. We now have 3 listener(s)
10-29 01:42:06.338  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:42:06.338  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:42:06.338  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-29 01:42:06.339  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 01:42:06.339  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f added. We now have 3 listener(s)
10-29 01:42:06.339  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:42:06.339  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-29 01:42:06.340  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 01:42:06.342  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:42:06.342  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:06.342  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:06.342  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:06.342  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:42:06.342  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:06.342  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:06.342  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:42:06.343  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:06.343  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-29 01:42:06.345  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-29 01:42:06.345  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 01:42:06.345  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-29 01:42:06.345  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 01:42:06.345  5704  5750 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-29 01:42:06.346  5704  5750 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-29 01:42:06.346  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-29 01:42:06.346  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 01:42:06.346  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 01:42:06.346  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 01:42:06.346  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:06.346  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:06.346  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:06.346  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:06.346  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:06.346  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:42:06.347  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:06.347  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:42:06.347  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e removed from the list
10-29 01:42:06.347  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:06.347  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f removed from the list
10-29 01:42:06.349  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:06.354  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:06.355  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:06.355  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:06.355  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:06.355  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:06.356  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:06.356  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.356  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.356  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.356  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:06.356  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:06.356  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:06.356  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:06.357  5704  5750 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-29 01:42:06.357  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:06.357  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:06.357  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-29 01:42:06.357  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:06.358  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:06.358  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:06.358  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:06.358  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:06.358  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:06.358  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
,10-29 01:42:06.358  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:06.358  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:06.358  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:06.358  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:06.358  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:06.358  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:06.358  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.358  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.358  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.358  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:06.358  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:06.358  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:06.359  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-29 01:42:06.361  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-29 01:42:06.362  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:06.362  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:06.362  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:06.362  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:06.362  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:06.362  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:06.362  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:06.362  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
,10-29 01:42:06.362  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:06.362  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:06.362  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:06.362  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:06.362  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:06.362  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:06.362  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:06.362  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.363  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.363  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.363  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.363  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:06.363  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:06.363  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:06.363  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:06.363  5704  5750 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-29 01:42:06.364  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:42:06.366  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:42:06.366  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:06.366  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:06.366  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:06.366  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:42:06.366  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:06.366  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:06.366  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:06.367  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:06.367  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:42:06.367  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 01:42:06.367  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 01:42:06.367  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 01:42:06.367  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 01:42:06.367  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-29 01:42:06.370  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-29 01:42:06.370  5704  5750 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 01:42:06.370  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-29 01:42:06.371  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:06.373  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:06.373  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:06.373  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-29 01:42:06.374  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 01:42:06.374  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-29 01:42:06.375  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-29 01:42:06.376  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-29 01:42:06.376  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.376  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 01:42:06.376  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 01:42:06.377  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-29 01:42:06.377  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 01:42:06.377  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.377  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:42:06.379  4676  4689 D BtGatt.GattService: registerClient() - UUID=9b648a8e-5735-447e-aba7-b87dfc5e28d2
,10-29 01:42:06.380  4676  4738 D BtGatt.GattService: onClientRegistered() - UUID=9b648a8e-5735-447e-aba7-b87dfc5e28d2, clientIf=5
,10-29 01:42:06.381  5704  5714 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-29 01:42:06.384  4676  4886 D BtGatt.GattService: start scan with filters
,10-29 01:42:06.391  4676  4741 D BtGatt.ScanManager: handling starting scan
10-29 01:42:06.391  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-29 01:42:06.391  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:06.391  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 01:42:06.391  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.392  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-29 01:42:06.392  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 01:42:06.392  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:42:06.392  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-29 01:42:06.392  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-29 01:42:06.392  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.392  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 01:42:06.392  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:42:06.392  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,10-29 01:42:06.392  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-29 01:42:06.393  4676  4741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:42:06.393  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.393  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.393  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:06.394  5704  5750 I io.jxcore.node.ConnectionHelper: start: OK
10-29 01:42:06.394  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-29 01:42:06.396  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 01:42:06.396  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:42:06.397  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:06.397  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:06.397  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:42:06.397  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-29 01:42:06.400  4676  4738 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-29 01:42:06.400  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 01:42:06.401  4676  4741 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-29 01:42:06.406  4676  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-29 01:42:06.406  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:06.407  4676  4741 D BtGatt.ScanManager: Starting BLE batch scan
10-29 01:42:06.407  4676  4741 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-29 01:42:06.416  4676  4738 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-29 01:42:06.416  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 01:42:06.421  4676  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 01:42:06.421  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 01:42:06.898  5704  5704 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-29 01:42:06.898  5704  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 01:42:06.899  5704  5704 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-29 01:42:09.059   930  3045 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-29 01:42:09.065   930  3045 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-29 01:42:11.398  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 01:42:11.398  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:11.398  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-29 01:42:11.398  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:11.398  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-29 01:42:11.399  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:11.399  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-29 01:42:11.399  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 01:42:11.399  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 01:42:11.399  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-29 01:42:11.400  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.400  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.400  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.401  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 01:42:11.401  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:11.402  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:42:11.403  4676  4897 D BtGatt.GattService: stopScan() - queue size =1
,10-29 01:42:11.404  4676  4687 D BtGatt.GattService: unregisterClient() - clientIf=5
10-29 01:42:11.405  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-29 01:42:11.406  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:11.406  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 01:42:11.406  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.406  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:11.406  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.406  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.407  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-29 01:42:11.407  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.407  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.407  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.407  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-29 01:42:11.408  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 01:42:11.408  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:42:11.409  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.411  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.411  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:42:11.411  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.411  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:11.412  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:11.412  4676  4676 D BtGatt.ScanManager: awakened up at time 176259
,10-29 01:42:11.412  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:11.412  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:42:11.412  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:11.412  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:11.412  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:11.412  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
,10-29 01:42:11.412  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:11.412  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:42:11.413  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:11.413  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:42:11.413  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 01:42:11.413  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:42:11.413  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 01:42:11.414  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 01:42:11.414  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-29 01:42:11.414  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 01:42:11.415  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 01:42:11.415  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 01:42:11.418  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 01:42:11.419  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:11.419  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:11.419  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:42:11.419  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-29 01:42:11.420  4676  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-29 01:42:11.420  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:11.420  4676  4741 D BtGatt.ScanManager: stopping BLe Batch
,10-29 01:42:11.429  4676  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 01:42:11.429  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 01:42:11.429  4676  4741 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-29 01:42:11.444  4676  4738 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-29 01:42:11.444  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:11.444  4676  4738 D BtGatt.GattService: current time is 176292283986
10-29 01:42:11.445  4676  4738 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -85, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -85, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -93, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -79, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-29 01:42:11.446  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-29 01:42:11.447  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-29 01:42:11.447  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-29 01:42:11.447  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-29 01:42:11.447  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
10-29 01:42:11.447  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-29 01:42:11.920  5704  5704 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 01:42:12.096   930  3045 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-29 01:42:12.100   930  3045 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-29 01:42:16.026   930  3043 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-29 01:42:16.420  5704  5750 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-29 01:42:16.427  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 01:42:16.437  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:42:16.437  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:16.437  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:16.437  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:16.437  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:42:16.437  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:16.437  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:16.437  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:42:16.441  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 01:42:16.442  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:42:16.442  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-29 01:42:16.442  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-29 01:42:16.442  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 01:42:16.442  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:42:16.442  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-29 01:42:16.445  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:16.447  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-29 01:42:16.447  5704  5750 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 01:42:16.447  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-29 01:42:16.451  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:16.451  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.451  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-29 01:42:16.451  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 01:42:16.451  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-29 01:42:16.455  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.456  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-29 01:42:16.456  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 01:42:16.456  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-29 01:42:16.456  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 01:42:16.456  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.457  5704  5750 D BluetoothAdapter: STATE_ON
,10-29 01:42:16.460  4676  4898 D BtGatt.GattService: registerClient() - UUID=39f1b5f2-538a-4f47-b0d2-b8dee6fb0223
10-29 01:42:16.461  4676  4738 D BtGatt.GattService: onClientRegistered() - UUID=39f1b5f2-538a-4f47-b0d2-b8dee6fb0223, clientIf=5
10-29 01:42:16.461  5704  5715 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-29 01:42:16.461  4676  4897 D BtGatt.GattService: start scan with filters
,10-29 01:42:16.464  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-29 01:42:16.464  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:16.464  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 01:42:16.464  4676  4741 D BtGatt.ScanManager: handling starting scan
10-29 01:42:16.464  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:16.464  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-29 01:42:16.464  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 01:42:16.464  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,10-29 01:42:16.464  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 01:42:16.464  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 01:42:16.464  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.465  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.465  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-29 01:42:16.466  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-29 01:42:16.466  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.468  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.468  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:42:16.469  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.469  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.469  5704  5750 I io.jxcore.node.ConnectionHelper: start: OK
,10-29 01:42:16.469  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.471  4676  4738 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-29 01:42:16.471  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.471  4676  4741 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-29 01:42:16.472  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.473  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.473  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.473  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.473  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-29 01:42:16.473  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:16.473  5704  5750 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-29 01:42:16.473  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:16.473  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-29 01:42:16.473  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:16.473  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-29 01:42:16.473  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:16.473  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-29 01:42:16.474  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 01:42:16.474  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 01:42:16.474  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-29 01:42:16.474  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.474  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.474  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.474  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 01:42:16.474  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:16.476  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:42:16.476  4676  4885 D BtGatt.GattService: stopScan() - queue size =1
10-29 01:42:16.477  4676  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 01:42:16.477  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.477  4676  4741 D BtGatt.ScanManager: Starting BLE batch scan
10-29 01:42:16.477  4676  4741 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-29 01:42:16.477  4676  4689 D BtGatt.GattService: unregisterClient() - clientIf=5
10-29 01:42:16.478  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-29 01:42:16.478  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.478  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 01:42:16.478  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.478  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.478  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.478  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.478  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-29 01:42:16.478  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.479  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.479  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.479  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-29 01:42:16.479  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 01:42:16.479  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:42:16.479  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.481  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.481  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:42:16.481  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.481  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.481  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:16.481  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:42:16.481  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:16.481  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:42:16.481  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:42:16.481  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:16.481  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:16.481  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleP,eerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 01:42:16.481  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:16.481  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.481  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:16.481  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:16.481  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 01:42:16.481  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:16.481  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 01:42:16.481  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.481  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.481  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 01:42:16.482  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.483  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.483  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.483  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.483  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.483  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:42:16.483  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:16.483  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:16.484  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.485  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.485  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.485  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.485  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:16.485  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:16.485  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:16.485  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:16.486  5704  5750 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-29 01:42:16.488  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:42:16.489  4676  4738 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-29 01:42:16.489  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.492  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:42:16.492  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:16.492  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:16.492  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:16.492  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:42:16.492  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:16.492  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:16.492  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:16.493  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:16.494  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:42:16.494  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 01:42:16.494  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 01:42:16.494  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 01:42:16.494  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:42:16.494  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-29 01:42:16.496  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:16.497  4676  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 01:42:16.497  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-29 01:42:16.497  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.497  5704  5750 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 01:42:16.497  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-29 01:42:16.498  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:16.500  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.500  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-29 01:42:16.500  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 01:42:16.500  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-29 01:42:16.502  4676  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-29 01:42:16.502  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.503  4676  4741 D BtGatt.ScanManager: stopping BLe Batch
10-29 01:42:16.504  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.505  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 01:42:16.505  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 01:42:16.505  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-29 01:42:16.505  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 01:42:16.505  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.505  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:42:16.508  4676  4897 D BtGatt.GattService: registerClient() - UUID=5a1cc1f8-6074-4d9e-a59e-c3cb710d6ac0
10-29 01:42:16.508  4676  4738 D BtGatt.GattService: onClientRegistered() - UUID=5a1cc1f8-6074-4d9e-a59e-c3cb710d6ac0, clientIf=5
10-29 01:42:16.508  5704  5714 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-29 01:42:16.508  4676  4886 D BtGatt.GattService: start scan with filters
10-29 01:42:16.509  4676  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 01:42:16.509  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.509  4676  4741 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-29 01:42:16.510  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-29 01:42:16.511  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.511  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 01:42:16.511  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.511  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-29 01:42:16.511  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 01:42:16.511  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.511  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 01:42:16.511  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 01:42:16.511  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.511  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.511  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-29 01:42:16.512  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-29 01:42:16.512  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.514  4676  4738 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-29 01:42:16.514  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.514  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.514  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:42:16.514  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.514  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:16.514  5704  5750 I io.jxcore.node.ConnectionHelper: start: OK
10-29 01:42:16.515  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.517  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.517  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.517  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.517  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:42:16.517  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:42:16.518  4676  4741 D BtGatt.ScanManager: handling starting scan
,10-29 01:42:16.523  4676  4738 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-29 01:42:16.523  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.523  4676  4741 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-29 01:42:16.528  4676  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 01:42:16.528  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.528  4676  4741 D BtGatt.ScanManager: Starting BLE batch scan
10-29 01:42:16.528  4676  4741 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-29 01:42:16.537  4676  4738 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-29 01:42:16.537  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:16.541  4676  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 01:42:16.541  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 01:42:17.019  5704  5704 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-29 01:42:17.019  5704  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-29 01:42:17.019  5704  5704 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-29 01:42:18.142   930  3045 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-29 01:42:18.146   930  3045 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-29 01:42:21.170   930  3045 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-29 01:42:21.175   930  3045 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-29 01:42:21.515  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:21.515  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-29 01:42:21.515  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-29 01:42:21.515  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:21.516  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-29 01:42:21.516  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:21.516  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-29 01:42:21.516  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 01:42:21.516  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-29 01:42:21.516  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-29 01:42:21.516  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:21.517  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.517  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.517  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 01:42:21.517  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:21.519  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:42:21.520  4676  4885 D BtGatt.GattService: stopScan() - queue size =1
10-29 01:42:21.521  4676  4897 D BtGatt.GattService: unregisterClient() - clientIf=5
10-29 01:42:21.521  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-29 01:42:21.522  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.522  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 01:42:21.522  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.522  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.522  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:21.523  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.523  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-29 01:42:21.523  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.523  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.523  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.523  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-29 01:42:21.523  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 01:42:21.525  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:42:21.526  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.528  4676  4676 D BtGatt.ScanManager: awakened up at time 186376
10-29 01:42:21.529  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.529  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-29 01:42:21.529  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.530  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:21.530  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:42:21.530  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:42:21.530  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 01:42:21.531   930  4853 I ActivityManager: Killing 5495:com.android.chrome/u0a39 (adj 15): empty #17
10-29 01:42:21.531  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,10-29 01:42:21.531  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 01:42:21.531  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 01:42:21.531  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:42:21.531  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 01:42:21.531  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 01:42:21.531  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-29 01:42:21.537  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-29 01:42:21.537  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:21.537  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:42:21.537  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:42:21.537  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-29 01:42:21.556  4676  4738 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-29 01:42:21.556  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 01:42:21.557  4676  4741 D BtGatt.ScanManager: stopping BLe Batch
,10-29 01:42:21.563  4676  4738 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 01:42:21.563  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:21.564  4676  4741 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-29 01:42:21.578  4676  4738 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-29 01:42:21.578  4676  4738 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:42:21.578  4676  4738 D BtGatt.GattService: current time is 186425830543
10-29 01:42:21.578  4676  4738 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -87, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -89, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -79, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-29 01:42:21.578  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-29 01:42:21.579  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-29 01:42:21.579  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-29 01:42:21.580  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-29 01:42:21.580  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-29 01:42:21.580  4676  4738 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-29 01:42:22.038  5704  5704 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 01:42:22.039  5704  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:22.039  5704  5704 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-29 01:42:24.574   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:42:25.576   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:42:26.531  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 01:42:26.532  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-29 01:42:26.532  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:26.532  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-29 01:42:26.532  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.532  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-29 01:42:26.533  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.533  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
,10-29 01:42:26.533  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.533  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.533  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.533  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.535  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.535  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.535  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:26.538  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.539  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.539  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.539  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:26.539  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.539  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.540  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.541  5704  5750 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-29 01:42:26.543  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:26.543  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:26.543  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:26.543  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-29 01:42:26.543  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.543  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.544  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.544  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.544  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.544  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.544  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.544  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.544  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.545  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.545  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.545  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.549  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:26.549  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.550  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.550  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-29 01:42:26.550  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.550  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.550  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.552  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-29 01:42:26.552  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:26.552  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:26.552  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:26.552  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:26.552  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.552  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.552  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.552  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.553  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.553  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.553  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.553  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.553  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.553  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.553  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.553  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.554  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.554  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:26.554  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.554  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:26.554  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.555  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.555  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.555  5704  5750 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-29 01:42:26.556  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:26.556  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:26.556  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:26.556  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:26.556  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.556  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:26.556  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.556  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.556  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.556  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.556  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.556  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.557  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.557  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.557  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.557  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:26.558  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.558  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.558  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.558  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:26.558  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.558  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.558  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.559  5704  5750 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,10-29 01:42:26.559  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:26.560  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:26.560  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:26.560  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:26.560  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.560  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.560  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.560  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.560  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:26.560  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.560  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.560  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.560  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.560  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.560  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.560  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.562  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.562  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:26.562  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.562  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:26.562  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.562  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.562  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.563  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-29 01:42:26.563  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 01:42:26.563  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 01:42:26.563  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-29 01:42:26.563  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 01:42:26.563  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-29 01:42:26.563  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-29 01:42:26.563  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 01:42:26.564  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 01:42:26.564  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:26.564  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:26.564  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:26.564  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:26.564  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.564  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:26.564  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.564  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.564  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.565  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.565  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.565  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.565  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.565  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:42:26.565  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.565  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.567  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.567  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.567  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.567  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:26.567  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.567  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:26.567  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.568  5704  5750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-29 01:42:26.568  5704  5750 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-29 01:42:26.568  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-29 01:42:26.572  5704  5750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-29 01:42:26.572  5704  5750 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-29 01:42:26.572  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-29 01:42:26.572  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-29 01:42:26.572  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,10-29 01:42:26.572  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-29 01:42:26.572  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-29 01:42:26.573  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-29 01:42:26.574  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-29 01:42:26.574  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-29 01:42:26.574  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-29 01:42:26.574  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-29 01:42:26.574  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-29 01:42:26.575  5704  5750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-29 01:42:26.575  5704  5750 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-29 01:42:26.575  5704  5750 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-29 01:42:26.575  5704  5750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-29 01:42:26.575  5704  5750 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-29 01:42:26.575  5704  5750 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-29 01:42:26.575  5704  5750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-29 01:42:26.575  5704  5750 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-29 01:42:26.575  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-29 01:42:26.576   535   535 I ServiceManager: Waiting for service AtCmdFwd...
10-29 01:42:26.579  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-29 01:42:26.580  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-29 01:42:26.580  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-29 01:42:26.580  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-29 01:42:26.580  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-29 01:42:26.580  5704  5750 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,10-29 01:42:26.581  5704  5750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-29 01:42:26.581  5704  5750 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-29 01:42:26.581  5704  5762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-29 01:42:26.581  5704  5762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-29 01:42:26.581  5704  5762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-29 01:42:26.581  5704  5762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-29 01:42:26.582  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:26.582  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:26.582  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-29 01:42:26.582  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:26.582  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.582  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.582  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.582  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,10-29 01:42:26.584  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.584  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.584  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.584  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.584  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.584  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.585  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.585  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:26.584  4687  4687 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32885]" dev="sockfs" ino=32885 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-29 01:42:26.584  4687  4687 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32885]" dev="sockfs" ino=32885 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-29 01:42:26.585  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.585  5704  5762 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-29 01:42:26.585  5704  5762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 01:42:26.586  5704  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
,10-29 01:42:26.586  5704  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
10-29 01:42:26.586  5704  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-29 01:42:26.586  5704  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-29 01:42:26.587  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.587  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.587  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.588  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:26.588  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.588  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:26.588  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.588  5704  5762 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-29 01:42:26.588  5704  5762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-29 01:42:26.588  5704  5762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-29 01:42:26.588  5704  5750 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-29 01:42:26.590  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:26.590  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:26.590  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:26.590  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:26.590  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:42:26.590  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.590  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.590  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.590  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:26.590  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.590  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.590  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.590  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.590  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:42:26.590  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.591  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.591  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.592  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.592  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.592  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:26.592  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.592  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.592  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
,10-29 01:42:26.593  5704  5750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-29 01:42:26.593  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:26.593  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:26.593  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:26.593  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:26.593  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.593  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.593  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.593  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.593  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:26.593  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.594  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.594  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.594  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.594  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.594  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.594  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.595  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.595  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:26.595  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.595  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:26.595  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.595  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.595  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.596  5704  5750 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-29 01:42:26.596  5704  5750 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-29 01:42:26.596  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-29 01:42:26.596  5704  5750 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-29 01:42:26.596  5704  5750 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-29 01:42:26.596  5704  5750 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,10-29 01:42:26.596  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-29 01:42:26.596  5704  5750 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-29 01:42:26.596  5704  5750 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-29 01:42:26.596  5704  5750 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-29 01:42:26.596  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-29 01:42:26.596  5704  5750 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-29 01:42:26.596  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:26.597  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:26.597  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-29 01:42:26.597  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:26.597  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.597  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.597  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.597  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.597  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.597  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.597  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.597  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.597  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.597  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:42:26.597  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.597  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.599  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.599  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.599  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:26.599  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:26.599  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:26.599  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.600  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
,10-29 01:42:26.600  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:26.600  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.600  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:26.600  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:26.600  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:26.600  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:26.601  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:26.601  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:26.601  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:26.601  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:27.578   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:42:28.579   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:42:29.580   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-29 01:42:31.601  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:31.601  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:31.602  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:31.602  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:42:31.602  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.602  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-29 01:42:31.602  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:31.602  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 01:42:31.602  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:31.602  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-29 01:42:31.603  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:31.603  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.603  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:31.603  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:31.603  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:31.603  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.603  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:31.603  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
,10-29 01:42:31.604  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.604  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.604  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:42:31.604  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.604  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:31.606  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.606  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.606  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:31.606  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:31.606  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:31.606  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.607  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:31.609  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-29 01:42:31.609  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 01:42:31.610  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-29 01:42:31.612  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-29 01:42:31.612  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-29 01:42:31.612  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-29 01:42:31.612  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-29 01:42:31.612  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-29 01:42:31.613  5704  5704 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-29 01:42:31.613  5704  5764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-29 01:42:31.613  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:31.613  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-29 01:42:31.613  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-29 01:42:31.613  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-29 01:42:31.613  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.614  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-29 01:42:31.614  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-29 01:42:31.614  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:31.614  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.614  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 01:42:31.614  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 01:42:31.614  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-29 01:42:31.614  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.614  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.615  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.615  5704  5704 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-29 01:42:31.617  5704  5764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 01:42:31.617  4885  4885 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33979]" dev="sockfs" ino=33979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-29 01:42:31.617  4885  4885 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33979]" dev="sockfs" ino=33979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-29 01:42:31.622  5704  5764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-29 01:42:31.622  5704  5764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-29 01:42:31.622  5704  5764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-29 01:42:31.622  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.622  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:42:31.623  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.623  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.623  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
,10-29 01:42:31.623  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:42:31.623  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:31.623  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:42:31.623  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:31.624  5704  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-29 01:42:31.624  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:31.624  5704  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:31.624  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-29 01:42:31.624  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:42:31.624  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.624  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.624  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:31.624  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:31.624  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.625  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:31.625  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:31.625  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.625  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:31.625  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.625  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.625  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.628  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.628  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.628  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.628  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:31.629  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:31.629  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:31.629  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:31.631  5704  5750 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-29 01:42:31.631  5704  5750 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-29 01:42:31.631  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-29 01:42:31.631  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 01:42:31.631  5704  5750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 01:42:31.632  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:31.632  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:31.632  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-29 01:42:31.632  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:31.632  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.632  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.632  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:31.632  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:31.633  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.633  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:31.633  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:31.633  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.633  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.633  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.633  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:31.635  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:42:31.641  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.641  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.641  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.641  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:31.642  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:31.642  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.642  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:31.645  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:42:31.646  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:31.646  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-29 01:42:31.646  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:31.646  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.646  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.646  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:31.646  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:31.646  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.646  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:31.646  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:31.646  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.646  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:31.646  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.647  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.647  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.648  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.648  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.648  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.648  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:31.648  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:42:31.648  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.648  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
,10-29 01:42:31.650  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 01:42:31.650  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:42:31.650  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:42:31.651  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:42:31.651  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.651  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.651  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:42:31.651  5704  5750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8033a0e not in the list
10-29 01:42:31.651  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.651  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
,10-29 01:42:31.651  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:31.651  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.651  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.651  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:31.651  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:31.651  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.653  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.653  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.653  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:42:31.653  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:42:31.653  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-29 01:42:31.653  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:42:31.653  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e42c2f not in the list
10-29 01:42:31.654  5704  5750 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-29 01:42:31.655  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-29 01:42:31.655  5704  5750 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-29 01:42:31.655  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-29 01:42:31.655  5704  5750 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-29 01:42:31.655  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-29 01:42:31.657  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-29 01:42:31.657  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-29 01:42:31.658  5704  5750 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-29 01:42:31.658  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-29 01:42:31.658  5704  5750 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-29 01:42:31.658  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-29 01:42:31.658  5704  5750 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-29 01:42:31.658  5704  5750 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-29 01:42:31.660  5704  5750 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-29 01:42:31.660  5704  5750 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-29 01:42:31.660  5704  5750 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-29 01:42:31.660  5704  5750 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-29 01:42:31.660  5704  5750 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-29 01:42:31.661  5704  5750 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-29 01:42:31.661  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:42:31.661  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ebc6579 added. We now have 3 listener(s)
10-29 01:42:31.661  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:42:31.663  5704  5750 D BluetoothAdapter: enable(): BT is already enabled..!
10-29 01:42:31.664   930   941 D WifiService: setWifiEnabled: true pid=5704, uid=10077
10-29 01:42:31.664   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 01:42:31.715  4676  4867 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-29 01:42:31.717  4676  4883 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-29 01:42:32.124  5704  5704 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 01:42:36.030   930  3043 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-29 01:42:36.669  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 01:42:36.669  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b842be added. We now have 4 listener(s)
,10-29 01:42:36.670  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 01:42:36.683  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:36.684  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b842be removed from the list
10-29 01:42:36.684  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:36.684  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:36.684  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:42:36.686  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:42:36.686  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cbe7f1f added. We now have 4 listener(s)
10-29 01:42:36.686  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:42:36.689  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:42:36.689  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cbe7f1f removed from the list
10-29 01:42:36.689  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:42:36.690  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:42:36.690  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:42:36.691  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 01:42:36.691  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d1c26c added. We now have 4 listener(s)
10-29 01:42:36.691  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 01:42:36.696   930   941 D WifiService: setWifiEnabled: false pid=5704, uid=10077
,10-29 01:42:36.696   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 01:42:36.701   930  3043 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-29 01:42:36.701   930  3043 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-29 01:42:36.701   930  3043 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-29 01:42:36.702   930  3043 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 01:42:36.714  4676  4734 D BluetoothAdapterState: Current state: ON, message: 23
,10-29 01:42:36.715  4676  4734 D BluetoothAdapterProperties: Setting state to 13
,10-29 01:42:36.715  4676  4734 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-29 01:42:36.715  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:42:36.716  4676  4734 D BluetoothAdapterProperties: onBluetoothDisable()
10-29 01:42:36.717  4676  4734 I BluetoothAdapterState: Entering PendingCommandState
10-29 01:42:36.721  4676  4676 D BluetoothMapService: onReceive
10-29 01:42:36.721  4676  4676 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-29 01:42:36.721  4676  4676 D BluetoothMapService: STATE_TURNING_OFF
10-29 01:42:36.721   930  5453 D DhcpClient: Clearing IP address
10-29 01:42:36.721  4676  4676 D BluetoothMapService: MAP Service closeService in
,10-29 01:42:36.721  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.721  4676  4676 D BluetoothMapMasInstance0: MAP Service shutdown
10-29 01:42:36.721   507   927 D CommandListener: Clearing all IP addresses on wlan0
10-29 01:42:36.721  4676  4676 D ObexServerSockets0: shutdown(block = true)
10-29 01:42:36.721  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:42:36.721  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.721  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.721  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:36.721  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.721  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:36.721  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:36.721  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:36.722  4676  4676 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-29 01:42:36.722  4676  4883 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-29 01:42:36.723  4676  4901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-29 01:42:36.722  4676  4676 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-29 01:42:36.724  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.724  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:36.724  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:42:36.724  4676  4738 D BluetoothAdapterProperties: Scan Mode:20
10-29 01:42:36.725  4676  4734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-29 01:42:36.726  4676  4900 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,10-29 01:42:36.728  4676  4676 I BtOppRfcommListener: stopping Accept Thread
10-29 01:42:36.729  4676  5383 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,10-29 01:42:36.729  4676  5383 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-29 01:42:36.729  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:36.733   507   927 D CommandListener: Setting iface cfg
,10-29 01:42:36.736  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:36.737  3645  5510 V NativeCrypto: Read error: ssl=0x7f70724900: I/O error during system call, Connection timed out
10-29 01:42:36.739  3645  5510 V NativeCrypto: SSL shutdown failed: ssl=0x7f70724900: I/O error during system call, Broken pipe
10-29 01:42:36.741  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.741  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.741  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.741  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.741  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:36.741  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.741  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:36.741  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:36.741  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:36.742  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.742   930  3950 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-29 01:42:36.742  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:36.742   930  5451 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-29 01:42:36.745   930  5451 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-29 01:42:36.745   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-29 01:42:36.746   930  3045 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-29 01:42:36.746  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.746  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.746  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.746  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.746  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:36.746  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.746  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:36.746  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:36.746  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:36.747   930  3045 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-29 01:42:36.747  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.747  5704,  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 01:42:36.751  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.752  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.752  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.752  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.752  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:36.752  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.752  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:36.752  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:36.752  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:36.752  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 01:42:36.753  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:36.756  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.756  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.756  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.756  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.756  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:36.756  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.756  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:36.756  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:36.756  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:36.757  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.757  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:36.760   930   943 I ActivityManager: Start proc 5768:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-29 01:42:36.761  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 01:42:36.761  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.761  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.761  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.761  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:36.761  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.761  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:36.761  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:36.761  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:42:36.762  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 01:42:36.762  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-29 01:42:36.763  4676  4676 D HeadsetService: Received stop request...Stopping profile...
10-29 01:42:36.764   930  5454 D DhcpClient: Receive thread stopped
10-29 01:42:36.764   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-29 01:42:36.764   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-29 01:42:36.765   930   930 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:36.765   930   930 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:36.765   930   930 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:36.766  3200  3213 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:36.766  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:36.766  3200  3200 D HeadsetProfile: Bluetooth service disconnected
10-29 01:42:36.766  3858  4277 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:36.769   930  3045 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-29 01:42:36.771  3827  3972 W QCNEJ   : |CORE| network lost: 100
10-29 01:42:36.770   533   533 E Parcel  : Reading a NULL string not supported here.
10-29 01:42:36.772  4676  4676 D A2dpService: Received stop request...Stopping profile...
10-29 01:42:36.774  4676  4892 D A2dpStateMachine: Exit Disconnected: -1
,10-29 01:42:36.775   930   930 D BluetoothA2dp: Proxy object disconnected
10-29 01:42:36.776  4676  4676 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:36.776  4676  4676 V BluetoothAdapterState: isTurningOn()=false
,10-29 01:42:36.776  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:36.776  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:36.777   930   930 D RttService: SCAN_AVAILABLE : 1
10-29 01:42:36.777   930  3153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-29 01:42:36.778  3827  3972 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-29 01:42:36.778  4676  4676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-29 01:42:36.778  4676  4676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-29 01:42:36.778  4676  4738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-29 01:42:36.778  4676  4867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:36.778  4676  4867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:36.778  4676  4867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:36.778  3200  3200 D BluetoothA2dp: Proxy object disconnected
10-29 01:42:36.779  4676  4738 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-29 01:42:36.779  4676  4676 D HidService: Received stop request...Stopping profile...
10-29 01:42:36.780  4676  4676 D HidService: Stopping Bluetooth HidService
,10-29 01:42:36.781  4676  4676 D HealthService: Received stop request...Stopping profile...
,10-29 01:42:36.783  4676  4676 D PanService: Received stop request...Stopping profile...
10-29 01:42:36.784  4676  4676 V BluetoothAdapterState: isTurningOff()=true
,10-29 01:42:36.784  4676  4676 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:36.784  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:36.785  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:36.785  4676  4676 D BluetoothMapService: Received stop request...Stopping profile...
10-29 01:42:36.785  4676  4676 D BluetoothMapService: stop()
,10-29 01:42:36.786  4676  4676 D BluetoothMapAppObserver: deinitObservers()
10-29 01:42:36.786  4676  4676 D BluetoothMapAppObserver: removeReceiver()
,10-29 01:42:36.788  4676  4867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-29 01:42:36.788  4676  4867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:36.789  4676  4676 D SapService: Received stop request...Stopping profile...
10-29 01:42:36.789   930  3043 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-29 01:42:36.789  4676  4676 V SapService: stop()
10-29 01:42:36.789  4676  4738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-29 01:42:36.789  4676  4867 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-29 01:42:36.789  4676  4867 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-29 01:42:36.789  4676  4867 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-29 01:42:36.789  4676  4867 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-29 01:42:36.790  4676  4676 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:36.790  4676  4676 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:36.790  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:36.790  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:36.790  4676  4676 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-29 01:42:36.790  4676  4676 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-29 01:42:36.790  4676  4738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-29 01:42:36.790  4676  4676 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:36.790  4676  4676 V BluetoothAdapterState: isTurningOn()=false
,10-29 01:42:36.790  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:36.790  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:36.791  4676  4676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-29 01:42:36.791  4676  4738 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-29 01:42:36.791  4676  4676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-29 01:42:36.792  4676  4676 V BluetoothAdapterState: isTurningOff()=true
,10-29 01:42:36.793  4676  4676 V BluetoothAdapterState: isTurningOn()=false
,10-29 01:42:36.793  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:36.793  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 01:42:36.793  4676  4676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-29 01:42:36.793  4676  4676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-29 01:42:36.796  3200  3200 D BluetoothInputDevice: Proxy object disconnected
,10-29 01:42:36.796  3200  3200 D HidProfile: Bluetooth service disconnected
,10-29 01:42:36.796  3200  3200 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-29 01:42:36.796  3200  3200 D PanProfile: Bluetooth service disconnected
10-29 01:42:36.796  3200  3200 D BluetoothMap: Proxy object disconnected
10-29 01:42:36.797  3200  3200 D MapProfile: Bluetooth service disconnected
,10-29 01:42:36.797  4676  4676 D BluetoothMapService: MAP Service closeService in
10-29 01:42:36.797  4676  4676 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:36.797  4676  4676 V BluetoothAdapterState: isTurningOn()=false
,10-29 01:42:36.797  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:36.797  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:36.797  4676  4676 D BluetoothMapService: cleanup()
,10-29 01:42:36.797  4676  4676 D BluetoothMapService: MAP Service closeService in
,10-29 01:42:36.798  4676  4676 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:36.798  4676  4676 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:36.798  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:36.798  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:36.798  4676  4734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-29 01:42:36.798  4676  4734 D BluetoothAdapterProperties: Setting state to 15
10-29 01:42:36.798  4676  4734 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-29 01:42:36.799  4676  4734 I BluetoothAdapterState: Entering BleOnState
10-29 01:42:36.799  3200  3993 D BluetoothMap: onBluetoothStateChange: up=false
10-29 01:42:36.800  3858  4277 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:36.800  3200  3212 D BluetoothPan: onBluetoothStateChange on: false
10-29 01:42:36.801  3200  4033 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-29 01:42:36.801   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:36.801  3200  3213 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-29 01:42:36.804   930  3043 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-29 01:42:36.806  3200  3212 D BluetoothPbap: onBluetoothStateChange: up=false
10-29 01:42:36.806   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:36.807  3200  4033 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:36.807   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:36.807   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-29 01:42:36.809  4676  4734 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-29 01:42:36.809  4676  4734 D BluetoothAdapterProperties: Setting state to 16
10-29 01:42:36.809  4676  4734 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-29 01:42:36.812  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.812  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.812  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.812  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.812  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:36.812  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.812  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:36.812  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:36.812  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:36.813  4676  4734 D BluetoothAdapterProperties: onBleDisable
10-29 01:42:36.813  4676  4734 I BluetoothAdapterState: Entering PendingCommandState
10-29 01:42:36.813  4676  4735 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-29 01:42:36.814  4676  4738 D BluetoothAdapterProperties: Scan Mode:20
10-29 01:42:36.814  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.814  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.814  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.814  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.814  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:36.814  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.814  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:36.814  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:36.814  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:36.814  4676  4867 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-29 01:42:36.814  4676  4867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-29 01:42:36.816  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.816  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.816  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.816  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.816  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:36.816  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.816  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:36.816  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:36.816  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:36.818  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:36.818  5768  5768 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-29 01:42:36.819  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:36.821   507   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-29 01:42:36.822  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:36.839  5768  5768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-29 01:42:36.839   507   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-29 01:42:36.840   507   927 D CommandListener: Clearing all IP addresses on wlan0
10-29 01:42:36.840   930  3045 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-29 01:42:36.840   930  3045 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-29 01:42:36.840   507   927 D TetherController: Setting IP forward enable = 0
,10-29 01:42:36.842   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-29 01:42:36.844   930  3043 D DhcpClient: doQuit
10-29 01:42:36.844   930  3043 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-29 01:42:36.844  5368  5368 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@46b8218 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-29 01:42:36.844   930  5453 D DhcpClient: onQuitting
10-29 01:42:36.844  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:36.845  3510  3510 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-29 01:42:36.847  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:36.847  3980  3980 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-29 01:42:36.849  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.849  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.849  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.849  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.849  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:36.849  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.849  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:36.849  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:36.849  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:36.850  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.850  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:36.850  3645  3645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 01:42:36.850  5116  5132 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-29 01:42:36.850  5116  5132 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-29 01:42:36.850  5116  5132 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-29 01:42:36.850  5116  5132 E SarControlService: no key has been found,reset the power
10-29 01:42:36.851  5116  5153 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-29 01:42:36.851  5116  5153 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-29 01:42:36.851  5116  5153 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-29 01:42:36.851  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 01:42:36.851  5141  5141 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-29 01:42:36.852  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.852  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:36.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:36.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:36.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:36.853  5116  5153 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-29 01:42:36.853  5116  5153 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-29 01:42:36.853  5116  5153 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-29 01:42:36.853  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 01:42:36.853  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:36.854  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 01:42:36.854  5141  5141 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-29 01:42:36.856  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.856  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:36.856  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:36.856  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:36.856  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:36.856  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:36.856  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:36.856  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:36.856  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 01:42:36.857  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:36.857  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:36.858  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:36.861  5141  5155 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9886be HexData = [00000000ea03000000000000ffffffff]
10-29 01:42:36.861  5141  5155 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 01:42:36.861  5141  5155 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-29 01:42:36.862  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 01:42:36.862  5116  5127 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-29 01:42:36.866   930  3229 I ActivityManager: Start proc 5793:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
10-29 01:42:36.870   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42cf161:true
,10-29 01:42:36.871  5141  5155 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9886be HexData = [00000000eb03000000000000ffffffff]
,10-29 01:42:36.871  5141  5155 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 01:42:36.871  5141  5155 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-29 01:42:36.872  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 01:42:36.872  5116  5126 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-29 01:42:36.874  3510  3510 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-29 01:42:36.880  3510  3510 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-29 01:42:36.895  5768  5768 D LocalBluetoothProfileManager: Adding local MAP profile
,10-29 01:42:36.899   507   920 W SocketClient: write error (Broken pipe)
,10-29 01:42:36.899   507   920 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-29 01:42:36.899   507   920 W SocketListener: Error sending broadcast (Broken pipe)
,10-29 01:42:36.900  5768  5768 D BluetoothMap: Create BluetoothMap proxy object
,10-29 01:42:36.911   507   927 E Netd    : netlink response contains error (No such file or directory)
,10-29 01:42:36.912   507   927 D TetherController: Setting IP forward enable = 0
10-29 01:42:36.913   930  3045 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-29 01:42:36.913   930  3045 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-29 01:42:36.915  5768  5768 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-29 01:42:36.925  3510  3510 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-29 01:42:36.925  5793  5793 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-29 01:42:36.933  3510  3510 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-29 01:42:36.934  5768  5768 D DockEventReceiver: finishStartingService: stopping service
,10-29 01:42:36.937   930  3229 I ActivityManager: Killing 5026:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-29 01:42:37.019  4676  4738 I bt_hci  : shut_down
,10-29 01:42:37.023  4676  4742 D bt_hwcfg: hw_epilog_process
,10-29 01:42:37.023  4676  4742 I bt_vendor: low_power_mode_cb
,10-29 01:42:37.026  4676  4742 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-29 01:42:37.026  4676  4742 I bt_vendor: epilog_cb
10-29 01:42:37.026  4676  4742 I bt_hci  : epilog_finished_callback
,10-29 01:42:37.028  4676  4738 I bt_hci_h4: hal_close
,10-29 01:42:37.029  4676  4738 I bt_userial_vendor: device fd = 54 close
,10-29 01:42:37.036  5090  5090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-29 01:42:37.036   930  3043 D wifi    : In wifi stop Hal
,10-29 01:42:37.037   930  3043 D wifi    : halHandle = 0x7f5ebb1180, mVM = 0x7f7b28d140, mCls = 0x100a02
10-29 01:42:37.037   930  3509 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-29 01:42:37.037   930  3509 D WifiHAL : Got a signal to exit!!!
10-29 01:42:37.037   930  3509 I WifiHAL : Exit wifi_event_loop
10-29 01:42:37.039   930  3043 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-29 01:42:37.039   930  3043 E WifiHAL : Event processing terminated
10-29 01:42:37.039   930  3043 D wifi    : In wifi cleaned up handler
10-29 01:42:37.039   930  3043 I WifiHAL : Internal cleanup completed
,10-29 01:42:37.040  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:37.041  4138  4289 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-29 01:42:37.044  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:37.046  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:37.058   930  3509 D wifi    : set interface wlan0 flags (DOWN)
,10-29 01:42:37.058   930  3043 D WifiNative-HAL: HAL event thread stopped successfully
,10-29 01:42:37.131  5793  5793 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.io.File.exists(File.java:361)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-29 01:42:37.131  5793  5793 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 01:42:37.131  5793  5793 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 01:42:37.131  5793  5793 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.r.e.b(PG:170)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 01:42:37.131  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 01:42:37.132  5793  5793 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.r.k.d(PG:583)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.r.e.b(PG:170)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 01:42:37.132  5793  5793 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.io.File.exists(File.java:361)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 01:42:37.132  5793  5793 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.io.File.exists(File.java:361)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 01:42:37.132  5793  5793 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 01:42:37.132  5793  5793 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 01:42:37.138  4676  4735 D bt_stack_manager: event_shut_down_stack finished.
10-29 01:42:37.139  4676  4734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-29 01:42:37.140  5768  5768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-29 01:42:37.140  4676  4734 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-29 01:42:37.141  4676  4676 D BtGatt.DebugUtils: handleDebugAction() action=null
10-29 01:42:37.141  4676  4676 D BtGatt.GattService: Received stop request...Stopping profile...
10-29 01:42:37.141  4676  4676 D BtGatt.GattService: stop()
10-29 01:42:37.141  4676  4676 D BtGatt.AdvertiseManager: advertise clients cleared
10-29 01:42:37.145  4676  4676 V BluetoothAdapterState: isTurningOff()=false
10-29 01:42:37.145  4676  4676 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:37.145  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:37.145  4676  4676 V BluetoothAdapterState: isBleTurningOff()=true
10-29 01:42:37.145  4676  4734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-29 01:42:37.145  4676  4734 D BluetoothAdapterProperties: Setting state to 10
10-29 01:42:37.146  4676  4734 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-29 01:42:37.146  4676  4734 I BluetoothAdapterState: Entering OffState
10-29 01:42:37.147   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-29 01:42:37.147  3645  3645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 01:42:37.154  4676  4676 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-29 01:42:37.154  4676  4676 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-29 01:42:37.154  4676  4676 I BluetoothServiceJni: cleanupNative: return from cleanup
10-29 01:42:37.156  4676  4735 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-29 01:42:37.161  5768  5768 D DockEventReceiver: finishStartingService: stopping service
,10-29 01:42:37.169  4676  4735 D bt_stack_manager: event_clean_up_stack finished.
10-29 01:42:37.180  4676  4676 I art     : System.exit called, status: 0
10-29 01:42:37.180  4676  4676 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-29 01:42:37.203   930  3896 I ActivityManager: Killing 5198:com.google.android.deskclock/u0a66 (adj 15): empty #17
,10-29 01:42:37.227   930  3229 I ActivityManager: Process com.android.bluetooth (pid 4676) has died
,10-29 01:42:37.229  3809  3809 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-29 01:42:37.232  3809  3809 D SystemUpdateService: onCreate
,10-29 01:42:37.236  3809  3809 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-29 01:42:37.244  3809  3809 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-29 01:42:37.250  3809  3809 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-29 01:42:37.252  3809  3809 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-29 01:42:37.253  3809  5480 I iu.UploadsManager: num queued entries: 0
,10-29 01:42:37.254  3809  5480 I iu.UploadsManager: num updated entries: 0
,10-29 01:42:37.255  3809  5480 I iu.SyncManager: NEXT; no task
,10-29 01:42:37.261   930   947 D Tethering: InitialState.processMessage what=4
,10-29 01:42:37.267   930   940 I ActivityManager: Start proc 5835:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
10-29 01:42:37.267  3809  5833 I SystemUpdateService: active receiver: enabled
,10-29 01:42:37.268   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-29 01:42:37.278  3809  5833 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-29 01:42:37.307  5835  5835 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-29 01:42:37.308  3809  5833 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-29 01:42:37.308  3809  5833 I SystemUpdateService: now status is 0 (complete)
10-29 01:42:37.308  3809  5833 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-29 01:42:37.308  3809  5833 I SystemUpdateService: file has been verified
10-29 01:42:37.309  3809  5833 I SystemUpdateService: OTA package size = 21989297
,10-29 01:42:37.311  5835  5835 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-29 01:42:37.320  5835  5835 D SprintDMHelper: simOperator: 
,10-29 01:42:37.321  5835  5835 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-29 01:42:37.324  3809  5833 I SystemUpdateService: showing system update notification
,10-29 01:42:37.332   930  3900 I ActivityManager: Start proc 5847:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-29 01:42:37.370  3809  3809 D SystemUpdateService: onDestroy
,10-29 01:42:37.371   930  3896 I ActivityManager: Killing 5530:com.qualcomm.timeservice/1000 (adj 15): empty #17
,10-29 01:42:37.439  5090  5861 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-29 01:42:37.453   930  4853 I ActivityManager: Start proc 5862:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-29 01:42:37.454   930  4853 I ActivityManager: Killing 5368:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-29 01:42:37.510  5862  5862 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-29 01:42:37.525   930  3661 I ActivityManager: Killing 4748:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-29 01:42:37.605  5793  5822 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-29 01:42:37.613   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5eb1a1a:true
,10-29 01:42:41.726   930  3900 D WifiService: setWifiEnabled: true pid=5704, uid=10077
10-29 01:42:41.727   930  3900 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 01:42:41.736   507   927 D SoftapController: Softap fwReload - Ok
,10-29 01:42:41.741   507   927 D CommandListener: Setting iface cfg
,10-29 01:42:41.741   507   927 D CommandListener: Trying to bring down wlan0
,10-29 01:42:41.744   507   927 D CommandListener: Clearing all IP addresses on wlan0
,10-29 01:42:41.750   930  3043 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-29 01:42:42.331   930  3043 D wifi    : set interface wlan0 flags (UP)
,10-29 01:42:42.336   930  3043 I WifiHAL : Initializing wifi
10-29 01:42:42.336   930  3043 I WifiHAL : Creating socket
10-29 01:42:42.337   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-29 01:42:42.341   930  3043 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-29 01:42:42.341   930  3043 D wifi    : Did set static halHandle = 0x7f5ebb1180
10-29 01:42:42.341   930  3043 D wifi    : halHandle = 0x7f5ebb1180, mVM = 0x7f7b28d140, mCls = 0x1926
,10-29 01:42:42.341   930  3043 D wifi    : array field set
,10-29 01:42:42.342   930  3043 I WifiNative-HAL: interface[0] = wlan0
10-29 01:42:42.343   930  5881 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547050164608
,10-29 01:42:42.344   930  5881 D wifi    : waitForHalEvents called, vm = 0x7f7b28d140, obj = 0x1926, env = 0x7f5fae4a80
,10-29 01:42:42.413  5882  5882 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-29 01:42:42.425  5882  5882 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-29 01:42:42.432  5882  5882 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-29 01:42:42.432  5882  5882 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-29 01:42:42.445   930  3043 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-29 01:42:42.448  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 01:42:42.448  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:42.448  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:42.448  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:42.448  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:42.448  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:42.448  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:42.448  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:42.448  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:42.448  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:42.448  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:42.450   930  3043 D WifiConfigStore: Loading config and enabling all networks 
10-29 01:42:42.451  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:42.451  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:42.451  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:42.451  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:42.451  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:42.451  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:42.451  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:42.451  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:42.451  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:42.451  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:42.451  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:42.452  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:42.453  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:42.453  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:42.453  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:42.453  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:42.453  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:42.453  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:42.453  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:42.453  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:42.453  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:42.453  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:42.454  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:42.454  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:42.455  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:42.459   930  3043 D WifiConfigStore: loaded 0 passpoint configs
10-29 01:42:42.459   930  3043 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-29 01:42:42.460   930  3043 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-29 01:42:42.460   930  3043 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-29 01:42:42.461   930  3043 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-29 01:42:42.461   930  3043 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,10-29 01:42:42.461   930  3043 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-29 01:42:42.461   930  3043 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-29 01:42:42.464   930  3043 D WifiNative-HAL: Setting external_sim to 1
,10-29 01:42:42.465   930  3043 D wifi    : setting dfs flag to true, 0x7f6497f5c0
10-29 01:42:42.465  5090  5090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-29 01:42:42.465   930  3043 D WifiStateMachine: Setting OUI to DA-A1-19
10-29 01:42:42.465   930  3043 D wifi    : setting scan oui 0x7f6497f5c0
10-29 01:42:42.465   930  3043 D WifiHAL : Sending mac address OUI
,10-29 01:42:42.468   930  3043 E native  : do suspend false
,10-29 01:42:42.476   930  3043 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-29 01:42:42.476   930   930 D RttService: SCAN_AVAILABLE : 3
,10-29 01:42:42.477   930  3153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-29 01:42:42.477   507   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-29 01:42:42.478   507   927 D CommandListener: Setting iface cfg
,10-29 01:42:42.481   930  3037 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
,10-29 01:42:42.481   930  3037 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-29 01:42:42.489   930  3037 D WifiNative-HAL: p2pGetDeviceAddress
,10-29 01:42:42.489   930  3037 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-29 01:42:42.495   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=207342 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-29 01:42:45.552  5882  5882 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 01:42:45.557  5882  5882 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 01:42:45.563  5882  5882 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 01:42:45.611   930  3043 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-29 01:42:45.612   930  3043 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-29 01:42:45.612   930  3043 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 01:42:45.623   930  3043 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-29 01:42:45.655   930  3043 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-29 01:42:45.657  5882  5882 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-29 01:42:46.079  5882  5882 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-29 01:42:46.111  5882  5882 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-29 01:42:46.111  5882  5882 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-29 01:42:46.118   930  3043 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-29 01:42:46.119   930  3043 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-29 01:42:46.119   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-29 01:42:46.134   930  3043 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 01:42:46.146   507   927 D CommandListener: Setting iface cfg
,10-29 01:42:46.152   930  3043 D WifiStateMachine: Start Dhcp Watchdog 2
,10-29 01:42:46.163   930  3043 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-29 01:42:46.163   930  3045 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-29 01:42:46.164   930  3045 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-29 01:42:46.168   930  5888 D DhcpClient: Receive thread started
,10-29 01:42:46.248   930  3043 E native  : do suspend false
,10-29 01:42:46.259   930  5887 D DhcpClient: Broadcasting DHCPDISCOVER
,10-29 01:42:46.271   930  5888 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172630, domain null
,10-29 01:42:46.272   930  5887 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172630 seconds
,10-29 01:42:46.273   930  5887 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-29 01:42:46.285   930  5888 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-29 01:42:46.286   930  5887 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-29 01:42:46.288   507   927 D CommandListener: Setting iface cfg
10-29 01:42:46.292   930  3043 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-29 01:42:46.295   930  5887 D DhcpClient: Scheduling renewal in 86399s
,10-29 01:42:46.302   930  3043 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-29 01:42:46.302   930  3043 D WifiConfigStore: No blacklist allowed without epno enabled
10-29 01:42:46.303   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-29 01:42:46.305   930  3043 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-29 01:42:46.310   930  3045 D ConnectivityService: Adding iface wlan0 to network 101
,10-29 01:42:46.354   930  3045 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-29 01:42:46.355   930  3045 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-29 01:42:46.356   930  3045 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-29 01:42:46.358   930  3045 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-29 01:42:46.360   930  3045 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-29 01:42:46.367   930  3045 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-29 01:42:46.371   930  3045 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-29 01:42:46.371   930  3045 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-29 01:42:46.371   930  3045 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-29 01:42:46.371   930  3043 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-29 01:42:46.371   930  3045 D ConnectivityService:    accepting network in place of null
10-29 01:42:46.371   930  3043 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-29 01:42:46.372   930  3045 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-29 01:42:46.383   930  5886 D NetlinkSocketObserver: NeighborEvent{elapsedMs=211230, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-29 01:42:46.393   507   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 01:42:46.413   507   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 01:42:46.416   930  3045 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-29 01:42:46.416   930  3045 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-29 01:42:46.416  3827  3972 W QCNEJ   : |CORE| network available: 101
10-29 01:42:46.417   930  3045 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-29 01:42:46.418   930   947 D Tethering: MasterInitialState.processMessage what=3
10-29 01:42:46.418  3827  3972 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-29 01:42:46.421  3827  3972 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-29 01:42:46.421  3827  3972 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-29 01:42:46.422  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.422  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:46.422  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:46.422  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:46.422  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:46.422  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:46.422  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:46.422  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:46.422  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:46.423  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 01:42:46.423  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 01:42:46.425  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 01:42:46.425  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:46.425  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:46.425  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:46.425  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:46.425  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:46.425  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:46.425  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:46.425  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:46.425  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.425  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:46.428  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.428  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:46.428  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:46.428  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:46.428  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:42:46.428  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:46.428  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:46.428  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:42:46.428  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:42:46.428  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.428  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:42:46.432  5116  5132 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-29 01:42:46.434  3980  3980 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-29 01:42:46.435  5116  5132 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-29 01:42:46.435  5116  5132 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-29 01:42:46.436  5116  5132 E SarControlService: no key has been found,reset the power
10-29 01:42:46.437  3809  3809 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-29 01:42:46.440  3809  3809 D SystemUpdateService: onCreate
,10-29 01:42:46.441  5116  5153 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-29 01:42:46.441  5116  5153 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-29 01:42:46.441  5116  5153 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-29 01:42:46.442  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 01:42:46.442  5141  5141 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-29 01:42:46.444  5116  5153 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-29 01:42:46.444  5116  5153 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-29 01:42:46.444  5116  5153 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-29 01:42:46.445  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 01:42:46.445  5141  5141 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-29 01:42:46.448   930  5885 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-29 01:42:46.449  3809  3809 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-29 01:42:46.449  5141  5155 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9886be HexData = [00000000ec03000000000000ffffffff]
10-29 01:42:46.449  5141  5155 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 01:42:46.449  5141  5155 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-29 01:42:46.450  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 01:42:46.450  5116  5127 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-29 01:42:46.453  5141  5155 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9886be HexData = [00000000ed03000000000000ffffffff]
,10-29 01:42:46.453  5141  5155 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 01:42:46.453  5141  5155 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-29 01:42:46.454  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 01:42:46.454  5116  5126 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-29 01:42:46.458  3809  3809 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-29 01:42:46.467  3809  5480 I iu.UploadsManager: num queued entries: 0
,10-29 01:42:46.467  3809  5480 I iu.UploadsManager: num updated entries: 0
,10-29 01:42:46.470  3809  3809 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-29 01:42:46.472  3809  3809 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-29 01:42:46.474  5835  5835 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-29 01:42:46.479  5835  5835 D SprintDMHelper: simOperator: 
,10-29 01:42:46.479  5835  5835 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-29 01:42:46.482  3809  5898 I SystemUpdateService: active receiver: enabled
,10-29 01:42:46.489  3809  5480 I iu.SyncManager: NEXT; no task
,10-29 01:42:46.500   930  5885 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 29 Oct 2016 05:42:46 GMT], X-Android-Received-Millis=[1477719766499], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477719766479]}
,10-29 01:42:46.500   930  3045 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-29 01:42:46.500   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-29 01:42:46.500   930  3045 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-29 01:42:46.502   930  3045 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-29 01:42:46.508  3809  5898 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-29 01:42:46.513  3809  5898 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-29 01:42:46.513  3809  5898 I SystemUpdateService: now status is 0 (complete)
10-29 01:42:46.514  3809  5898 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-29 01:42:46.514  3809  5898 I SystemUpdateService: file has been verified
10-29 01:42:46.514  3809  5898 I SystemUpdateService: OTA package size = 21989297
,10-29 01:42:46.519  3809  5898 I SystemUpdateService: showing system update notification
,10-29 01:42:46.531  3809  3809 D SystemUpdateService: onDestroy
,10-29 01:42:46.585  5090  5903 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-29 01:42:46.733   930  3474 D WifiService: setWifiEnabled: false pid=5704, uid=10077
10-29 01:42:46.733   930  3474 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 01:42:46.735   930  3043 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-29 01:42:46.736   930  3043 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-29 01:42:46.736   930  3043 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-29 01:42:46.736   930  3043 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 01:42:46.749   930  5887 D DhcpClient: Clearing IP address
,10-29 01:42:46.750   507   927 D CommandListener: Clearing all IP addresses on wlan0
,10-29 01:42:46.751   507   927 D CommandListener: Setting iface cfg
,10-29 01:42:46.757   930  5888 D DhcpClient: Receive thread stopped
,10-29 01:42:46.759  3645  5908 V NativeCrypto: Read error: ssl=0x7f713ca880: I/O error during system call, Connection timed out
10-29 01:42:46.760  3645  5908 V NativeCrypto: SSL shutdown failed: ssl=0x7f713ca880: I/O error during system call, Broken pipe
10-29 01:42:46.763   930  3950 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,10-29 01:42:46.763   930  5885 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-29 01:42:46.763   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-29 01:42:46.764   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-29 01:42:46.764   930  5885 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-29 01:42:46.769   533   533 E Parcel  : Reading a NULL string not supported here.
10-29 01:42:46.769   930  3045 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-29 01:42:46.770   930   930 D RttService: SCAN_AVAILABLE : 1
10-29 01:42:46.770   930  3153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-29 01:42:46.770  3827  3972 W QCNEJ   : |CORE| network lost: 101
10-29 01:42:46.770   930  3043 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-29 01:42:46.771  3827  3972 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-29 01:42:46.773   930  3043 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-29 01:42:46.776   930  5885 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,10-29 01:42:46.795   507   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 01:42:46.816   507   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 01:42:46.816   507   927 D CommandListener: Clearing all IP addresses on wlan0
,10-29 01:42:46.817   930  3045 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-29 01:42:46.817   930  3045 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-29 01:42:46.818   930   947 D Tethering: MasterInitialState.processMessage what=3
10-29 01:42:46.820   930  3043 D DhcpClient: doQuit
10-29 01:42:46.820   930  3043 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-29 01:42:46.820   930  5887 D DhcpClient: onQuitting
10-29 01:42:46.821  5882  5882 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-29 01:42:46.822  3980  3980 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-29 01:42:46.833  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.833  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:46.833  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:46.833  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:46.833  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:46.833  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:46.833  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:46.833  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:46.833  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:46.833  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.833  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:46.834  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.834  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:46.834  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:46.834  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:46.834  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:46.834  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:46.834  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:46.834  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:46.834  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:46.834  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.834  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:46.835  5882  5882 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-29 01:42:46.835  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.835  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:46.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:46.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:46.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:46.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:46.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:46.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to, active network: false
10-29 01:42:46.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:46.836  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:46.836  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:46.836  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:46.837  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:46.838  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:46.839  5116  5132 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-29 01:42:46.840  5116  5132 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-29 01:42:46.840  5116  5132 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-29 01:42:46.840  5882  5882 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-29 01:42:46.840  5116  5132 E SarControlService: no key has been found,reset the power
,10-29 01:42:46.840  5116  5153 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-29 01:42:46.840  5116  5153 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-29 01:42:46.840  5116  5153 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-29 01:42:46.841  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 01:42:46.841  5141  5141 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-29 01:42:46.843  3809  3809 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-29 01:42:46.844  5116  5153 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-29 01:42:46.844  5116  5153 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-29 01:42:46.845  5116  5153 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-29 01:42:46.845  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-29 01:42:46.845  5141  5141 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-29 01:42:46.848  5141  5155 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9886be HexData = [00000000ee03000000000000ffffffff]
10-29 01:42:46.848  5141  5155 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 01:42:46.848  5141  5155 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-29 01:42:46.848  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 01:42:46.848  5116  5126 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-29 01:42:46.849  3809  3809 D SystemUpdateService: onCreate
,10-29 01:42:46.851  5141  5155 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9886be HexData = [00000000ef03000000000000ffffffff]
,10-29 01:42:46.851  5141  5155 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 01:42:46.852  5141  5155 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-29 01:42:46.852  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-29 01:42:46.852  5116  5127 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-29 01:42:46.855  3809  3809 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-29 01:42:46.861  3809  5918 I SystemUpdateService: active receiver: enabled
,10-29 01:42:46.863  3809  3809 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-29 01:42:46.868  3809  5480 I iu.UploadsManager: num queued entries: 0
,10-29 01:42:46.871  3809  3809 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-29 01:42:46.872   507   927 E Netd    : netlink response contains error (No such file or directory)
10-29 01:42:46.872  3809  3809 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-29 01:42:46.873   930  3045 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-29 01:42:46.873   930  3045 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-29 01:42:46.874  5835  5835 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-29 01:42:46.874  5882  5882 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-29 01:42:46.877  5835  5835 D SprintDMHelper: simOperator: 
10-29 01:42:46.877  5835  5835 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-29 01:42:46.886  3809  5918 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-29 01:42:46.891  5090  5921 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-29 01:42:46.898  3809  5480 I iu.UploadsManager: num updated entries: 0
,10-29 01:42:46.899  5882  5882 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-29 01:42:46.900  3809  5918 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-29 01:42:46.900  3809  5918 I SystemUpdateService: now status is 0 (complete)
10-29 01:42:46.900  3809  5918 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-29 01:42:46.900  3809  5918 I SystemUpdateService: file has been verified
,10-29 01:42:46.900  3809  5918 I SystemUpdateService: OTA package size = 21989297
,10-29 01:42:46.908  3809  5480 I iu.SyncManager: NEXT; no task
,10-29 01:42:46.911  3809  5918 I SystemUpdateService: showing system update notification
,10-29 01:42:46.919  3809  3809 D SystemUpdateService: onDestroy
,10-29 01:42:47.001   930  3043 D wifi    : In wifi stop Hal
,10-29 01:42:47.001   930  3043 D wifi    : halHandle = 0x7f5ebb1180, mVM = 0x7f7b28d140, mCls = 0x1926
10-29 01:42:47.002   930  5881 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-29 01:42:47.002   930  5881 D WifiHAL : Got a signal to exit!!!
10-29 01:42:47.002   930  5881 I WifiHAL : Exit wifi_event_loop
10-29 01:42:47.004  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:47.004  5090  5090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-29 01:42:47.005  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:47.006   930  3043 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-29 01:42:47.006   930  3043 E WifiHAL : Event processing terminated
10-29 01:42:47.006   930  3043 D wifi    : In wifi cleaned up handler
10-29 01:42:47.006   930  3043 I WifiHAL : Internal cleanup completed
10-29 01:42:47.006  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:47.006  4138  4289 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-29 01:42:47.025   930  5881 D wifi    : set interface wlan0 flags (DOWN)
,10-29 01:42:47.025   930  3043 D WifiNative-HAL: HAL event thread stopped successfully
,10-29 01:42:47.232   930   947 D Tethering: InitialState.processMessage what=4
,10-29 01:42:47.240   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-29 01:42:47.417   930  3045 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-29 01:42:51.777   930   947 I ActivityManager: Start proc 5923:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-29 01:42:51.873  5923  5923 D AdapterServiceConfig: Adding HeadsetService
,10-29 01:42:51.873  5923  5923 D AdapterServiceConfig: Adding A2dpService
10-29 01:42:51.873  5923  5923 D AdapterServiceConfig: Adding HidService
10-29 01:42:51.873  5923  5923 D AdapterServiceConfig: Adding HealthService
10-29 01:42:51.874  5923  5923 D AdapterServiceConfig: Adding PanService
10-29 01:42:51.874  5923  5923 D AdapterServiceConfig: Adding GattService
10-29 01:42:51.874  5923  5923 D AdapterServiceConfig: Adding BluetoothMapService
10-29 01:42:51.874  5923  5923 D AdapterServiceConfig: Adding SapService
,10-29 01:42:51.887   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fd1f839:true
,10-29 01:42:51.888  5923  5923 D BluetoothAdapterState: make() - Creating AdapterState
,10-29 01:42:51.892  5923  5923 I bt_bluedroid: init
,10-29 01:42:51.892  5923  5935 I BluetoothAdapterState: Entering OffState
,10-29 01:42:51.894  5923  5936 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-29 01:42:51.894  5923  5936 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-29 01:42:51.894  5923  5936 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-29 01:42:51.894  5923  5936 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-29 01:42:51.895  5923  5923 I bt_bluedroid: get_profile_interface socket
,10-29 01:42:51.896  5923  5939 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-29 01:42:51.897  5923  5923 I bt_bluedroid: get_profile_interface sdp
,10-29 01:42:51.898  5923  5939 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-29 01:42:51.902  5923  5934 I bt_bluedroid: config_hci_snoop_log
10-29 01:42:51.903   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-29 01:42:51.907  5923  5935 D BluetoothAdapterState: Current state: OFF, message: 0
10-29 01:42:51.907  5923  5935 D BluetoothAdapterProperties: Setting state to 14
10-29 01:42:51.907  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-29 01:42:51.909  5923  5935 D BluetoothBondStateMachine: make
,10-29 01:42:51.911  5923  5940 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-29 01:42:51.914  5923  5935 I BluetoothAdapterState: Entering PendingCommandState
,10-29 01:42:51.915  5923  5923 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-29 01:42:51.917  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
,10-29 01:42:51.918  5923  5923 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-29 01:42:51.918  5923  5923 D BtGatt.GattService: Received start request. Starting profile...
10-29 01:42:51.918  5923  5923 D BtGatt.GattService: start()
10-29 01:42:51.918  5923  5923 I bt_bluedroid: get_profile_interface gatt
,10-29 01:42:51.920  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:42:51.920  5923  5923 D BtGatt.AdvertiseManager: advertise manager created
,10-29 01:42:51.925  5923  5923 V BluetoothAdapterState: isTurningOff()=false
,10-29 01:42:51.925  5923  5923 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:51.925  5923  5923 V BluetoothAdapterState: isBleTurningOn()=true
10-29 01:42:51.925  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:51.925  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-29 01:42:51.927  5923  5935 I bt_bluedroid: bt_bluedroid
10-29 01:42:51.927  5923  5936 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-29 01:42:51.927  5923  5936 I bt_hci  : start_up
,10-29 01:42:51.932  5923  5936 I bt_vendor: alloc value 0xf3e0b871
,10-29 01:42:51.932  5923  5936 I bt_vendor: init
10-29 01:42:51.932  5923  5936 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-29 01:42:51.932  5923  5936 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-29 01:42:52.042  5923  5936 D bt_hci  : start_up starting async portion
,10-29 01:42:52.043  5923  5943 I bt_hci  : event_finish_startup
,10-29 01:42:52.043  5923  5943 I bt_hci_h4: hal_open
,10-29 01:42:52.043  5923  5943 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-29 01:42:52.046  5923  5943 I bt_userial_vendor: device fd = 54 open
10-29 01:42:52.041  5944  5944 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-29 01:42:52.060  5923  5943 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-29 01:42:52.063  5923  5943 D bt_hwcfg: Chipset BCM4358A3
,10-29 01:42:52.063  5923  5943 D bt_hwcfg: Target name = [BCM4358A3]
10-29 01:42:52.064  5923  5943 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-29 01:42:52.471  5923  5943 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-29 01:42:52.472  5923  5943 D bt_hwcfg: Settlement delay -- 100 ms
10-29 01:42:52.472  5923  5943 I bt_hwcfg: Setting fw settlement delay to 100 
,10-29 01:42:52.605  5923  5943 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-29 01:42:52.606  5923  5943 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-29 01:42:52.607  5923  5943 I bt_hwcfg: vendor lib fwcfg completed
,10-29 01:42:52.607  5923  5943 I bt_vendor: firmware callback
10-29 01:42:52.608  5923  5943 I bt_hci  : firmware_config_callback
10-29 01:42:52.617  5923  5946 I bt_btu  : btu_task pending for preload complete event
10-29 01:42:52.617  5923  5946 I bt_btu_task: Bluetooth chip preload is complete
10-29 01:42:52.617  5923  5946 I bt_btu  : btu_task received preload complete event
,10-29 01:42:52.624  5923  5946 I         : BTE_InitTraceLevels -- TRC_HCI
,10-29 01:42:52.624  5923  5946 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-29 01:42:52.624  5923  5946 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-29 01:42:52.625  5923  5946 I         : BTE_InitTraceLevels -- TRC_AVDT
10-29 01:42:52.625  5923  5946 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-29 01:42:52.625  5923  5946 I         : BTE_InitTraceLevels -- TRC_A2D
,10-29 01:42:52.625  5923  5946 I         : BTE_InitTraceLevels -- TRC_BNEP
10-29 01:42:52.625  5923  5946 I         : BTE_InitTraceLevels -- TRC_BTM
,10-29 01:42:52.625  5923  5946 I         : BTE_InitTraceLevels -- TRC_GAP
,10-29 01:42:52.626  5923  5946 I         : BTE_InitTraceLevels -- TRC_PAN
10-29 01:42:52.626  5923  5946 I         : BTE_InitTraceLevels -- TRC_SDP
10-29 01:42:52.626  5923  5946 I         : BTE_InitTraceLevels -- TRC_GATT
10-29 01:42:52.626  5923  5946 I         : BTE_InitTraceLevels -- TRC_SMP
,10-29 01:42:52.626  5923  5946 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-29 01:42:52.626  5923  5946 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-29 01:42:52.711  5923  5946 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d89549
10-29 01:42:52.712  5923  5946 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d89549 
,10-29 01:42:52.743  5923  5939 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-29 01:42:52.745  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-29 01:42:52.745  5923  5939 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-29 01:42:52.748  5923  5939 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-29 01:42:52.751  5923  5939 D BluetoothAdapterProperties: Scan Mode:20
,10-29 01:42:52.751  5923  5939 D BluetoothAdapterProperties: Discoverable Timeout:120
10-29 01:42:52.752  5923  5939 D bt_hci  : do_postload posting postload work item
10-29 01:42:52.752  5923  5943 I bt_hci  : event_postload
10-29 01:42:52.752  5923  5943 I bt_vendor: sco_config_cb
10-29 01:42:52.752  5923  5943 I bt_hci  : sco_config_callback postload finished.
,10-29 01:42:52.756  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:52.758  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:52.758  5923  5943 I bt_vendor: low_power_mode_cb
10-29 01:42:52.759  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:52.760  5923  5939 D bt_bte_conf: Device ID record 1 : primary
10-29 01:42:52.760  5923  5939 D bt_bte_conf:   vendorId            = 000f
10-29 01:42:52.760  5923  5939 D bt_bte_conf:   vendorIdSource      = 0001
10-29 01:42:52.760  5923  5939 D bt_bte_conf:   product             = 1200
10-29 01:42:52.761  5923  5939 D bt_bte_conf:   version             = 1436
,10-29 01:42:52.761  5923  5939 D bt_bte_conf:   clientExecutableURL = 
10-29 01:42:52.761  5923  5939 D bt_bte_conf:   serviceDescription  = 
10-29 01:42:52.761  5923  5939 D bt_bte_conf:   documentationURL    = 
10-29 01:42:52.761  5923  5939 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-29 01:42:52.761  5923  5936 D bt_stack_manager: event_start_up_stack finished
10-29 01:42:52.761  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-29 01:42:52.762  5923  5935 D BluetoothAdapterProperties: Setting state to 15
10-29 01:42:52.762  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-29 01:42:52.762  5923  5935 I BluetoothAdapterState: Entering BleOnState
,10-29 01:42:52.765  5923  5935 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-29 01:42:52.765  5923  5935 D BluetoothAdapterProperties: Setting state to 11
10-29 01:42:52.765  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-29 01:42:52.771  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
,10-29 01:42:52.771  5923  5923 D HeadsetService: Received start request. Starting profile...
,10-29 01:42:52.773  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:52.774  5923  5923 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-29 01:42:52.774  5923  5923 D HeadsetStateMachine: make
10-29 01:42:52.775  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:52.776  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:52.782  5923  5935 I BluetoothAdapterState: Entering PendingCommandState
,10-29 01:42:52.783  5923  5923 D HeadsetStateMachine: max_hf_connections = 1
,10-29 01:42:52.784  5923  5923 I bt_bluedroid: get_profile_interface handsfree
10-29 01:42:52.784  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-29 01:42:52.784  5923  5939 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-29 01:42:52.786  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
,10-29 01:42:52.787  5923  5923 D A2dpService: Received start request. Starting profile...
,10-29 01:42:52.788  5923  5923 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-29 01:42:52.788  5923  5923 I bt_bluedroid: get_profile_interface avrcp
,10-29 01:42:52.793  5923  5923 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-29 01:42:52.793  5923  5923 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-29 01:42:52.793  5923  5923 D A2dpStateMachine: make
10-29 01:42:52.794  5923  5923 I bt_bluedroid: get_profile_interface a2dp
,10-29 01:42:52.794  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-29 01:42:52.796  5923  5954 D A2dpStateMachine: Enter Disconnected: -2
,10-29 01:42:52.798  5923  5923 I BluetoothHidServiceJni: classInitNative: succeeds
10-29 01:42:52.799  3645  3645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 01:42:52.799  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
,10-29 01:42:52.800  5768  5768 D BluetoothInputDevice: Proxy object connected
10-29 01:42:52.800  5923  5923 D HidService: Received start request. Starting profile...
,10-29 01:42:52.800  5923  5923 I bt_bluedroid: get_profile_interface hidhost
10-29 01:42:52.800  5923  5923 D HidService: setHidService(): set to: null
10-29 01:42:52.800  5923  5939 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d6a56d
10-29 01:42:52.801  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-29 01:42:52.801  5768  5768 D HidProfile: Bluetooth service connected
10-29 01:42:52.801  5923  5923 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-29 01:42:52.802  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:42:52.803  5923  5923 D HealthService: Received start request. Starting profile...
,10-29 01:42:52.804  5923  5923 I bt_bluedroid: get_profile_interface health
,10-29 01:42:52.805  5923  5923 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-29 01:42:52.805  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
,10-29 01:42:52.807  5768  5768 D BluetoothPan: BluetoothPAN Proxy object connected
10-29 01:42:52.807  5923  5923 D PanService: Received start request. Starting profile...
10-29 01:42:52.807  5923  5923 D BluetoothPanServiceJni: initializeNative(L110): pan
10-29 01:42:52.807  5923  5923 I bt_bluedroid: get_profile_interface pan
10-29 01:42:52.807  5768  5768 D PanProfile: Bluetooth service connected
10-29 01:42:52.807  5923  5939 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-29 01:42:52.809  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
,10-29 01:42:52.811  5923  5923 D BluetoothMapService: Received start request. Starting profile...
,10-29 01:42:52.811  5923  5923 D BluetoothMapService: start()
10-29 01:42:52.813  5923  5923 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-29 01:42:52.814  5923  5923 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-29 01:42:52.814  5923  5923 D BluetoothMapAppObserver: createReceiver()
10-29 01:42:52.815  5923  5923 D BluetoothMapAppObserver: initObservers()
10-29 01:42:52.815  5923  5923 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-29 01:42:52.820  5768  5768 D BluetoothMap: Proxy object connected
,10-29 01:42:52.821  5768  5768 D MapProfile: Bluetooth service connected
10-29 01:42:52.821  5768  5768 D BluetoothMap: getConnectedDevices()
10-29 01:42:52.823  5923  5923 V SapService: SapBinder()
10-29 01:42:52.823  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:42:52.824  5923  5923 D SapService: Received start request. Starting profile...
10-29 01:42:52.824  5923  5923 V SapService: start()
10-29 01:42:52.825  5768  5768 D BluetoothMap: Bluetooth is Not enabled
,10-29 01:42:52.826  5923  5923 V BluetoothAdapterState: isTurningOff()=false
,10-29 01:42:52.826  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-29 01:42:52.826  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:52.826  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:52.826  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-29 01:42:52.826  5923  5952 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-29 01:42:52.826  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-29 01:42:52.826  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:52.826  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 01:42:52.827  5923  5923 V BluetoothAdapterState: isTurningOff()=false
,10-29 01:42:52.827  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-29 01:42:52.827  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:52.827  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:52.827  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-29 01:42:52.827  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-29 01:42:52.827  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:52.827  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:52.828  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-29 01:42:52.828  5923  5923 V BluetoothAdapterState: isTurningOn()=true
,10-29 01:42:52.828  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:52.828  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:52.828  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-29 01:42:52.828  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-29 01:42:52.828  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:52.828  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:52.829  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-29 01:42:52.829  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-29 01:42:52.829  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:52.829  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:52.829  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-29 01:42:52.829  5923  5935 D BluetoothAdapterProperties: ScanMode =  20
10-29 01:42:52.830  5923  5935 D BluetoothAdapterProperties: State =  11
10-29 01:42:52.830  5923  5939 D BluetoothAdapterProperties: Scan Mode:21
10-29 01:42:52.830  5923  5935 D BluetoothAdapterProperties: Setting state to 12
10-29 01:42:52.831  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-29 01:42:52.831  5923  5939 D BluetoothAdapterProperties: Discoverable Timeout:120
10-29 01:42:52.831  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-29 01:42:52.831  3200  3993 D BluetoothMap: onBluetoothStateChange: up=true
10-29 01:42:52.832  5923  5935 I BluetoothAdapterState: Entering OnState
10-29 01:42:52.833  3858  4051 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 01:42:52.834  3200  3200 D BluetoothMap: Proxy object connected
10-29 01:42:52.834  3200  3200 D MapProfile: Bluetooth service connected
,10-29 01:42:52.834  3200  3200 D BluetoothMap: getConnectedDevices()
,10-29 01:42:52.834  5768  5779 D BluetoothPbap: onBluetoothStateChange: up=true
10-29 01:42:52.835  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:52.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:52.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:52.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:52.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:42:52.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:52.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:52.835  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:52.836  3200  3213 D BluetoothPan: onBluetoothStateChange on: true
,10-29 01:42:52.837  3200  3993 D BluetoothA2dp: onBluetoothStateChange: up=true
10-29 01:42:52.837  3200  3200 D BluetoothPan: BluetoothPAN Proxy object connected
10-29 01:42:52.838  3200  3200 D PanProfile: Bluetooth service connected
10-29 01:42:52.838  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:52.839   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 01:42:52.839  3200  3212 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-29 01:42:52.840  3200  3200 D BluetoothA2dp: Proxy object connected
10-29 01:42:52.840  5923  5923 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-29 01:42:52.841  5923  5923 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-29 01:42:52.841  5768  5781 D BluetoothMap: onBluetoothStateChange: up=true
10-29 01:42:52.841  5768  5779 D BluetoothPan: onBluetoothStateChange on: true
10-29 01:42:52.842  3200  3200 D BluetoothInputDevice: Proxy object connected
10-29 01:42:52.842  3200  3993 D BluetoothPbap: onBluetoothStateChange: up=true
10-29 01:42:52.842  3200  3200 D HidProfile: Bluetooth service connected
,10-29 01:42:52.842  5923  5923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 01:42:52.844   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 01:42:52.844  3200  3213 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-29 01:42:52.844  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:52.844  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:52.844  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:52.844  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:52.844  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:42:52.844  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:52.844  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:52.844  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:52.845   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 01:42:52.845   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-29 01:42:52.845  5923  5923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 01:42:52.846  5768  5781 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-29 01:42:52.846   930   930 D BluetoothA2dp: Proxy object connected
10-29 01:42:52.847  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:52.849  5923  5923 D ObexServerSockets: Succeed to create listening sockets 
10-29 01:42:52.849  5923  5923 D ObexServerSockets0: startAccept()
10-29 01:42:52.849  5923  5923 D ObexServerSockets0: prepareForNewConnect()
,10-29 01:42:52.850  5768  5768 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-29 01:42:52.850   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-29 01:42:52.852  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:52.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:52.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:52.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:52.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:42:52.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:52.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:52.852  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:52.852  5923  5923 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-29 01:42:52.852  5923  5923 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-29 01:42:52.854  5923  5961 D ObexServerSockets0: Accepting socket connection...
,10-29 01:42:52.854  5923  5962 D ObexServerSockets0: Accepting socket connection...
10-29 01:42:52.854  5923  5923 D BluetoothMapService: onReceive
10-29 01:42:52.854  5923  5923 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-29 01:42:52.854  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-29 01:42:52.854  5923  5923 D BluetoothMapService: STATE_ON
10-29 01:42:52.855  5768  5768 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-29 01:42:52.855  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-29 01:42:52.856  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:52.858  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:52.859  5923  5963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 01:42:52.860  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:52.862  5923  5963 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-29 01:42:52.862  5923  5963 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-29 01:42:52.864  5768  5768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-29 01:42:52.866  5768  5768 D BluetoothA2dp: Proxy object connected
,10-29 01:42:52.870  3645  3645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-29 01:42:52.870  5768  5768 D DockEventReceiver: finishStartingService: stopping service
,10-29 01:42:52.877  3200  3200 D BluetoothPbap: Proxy object connected
10-29 01:42:52.877  3200  3200 D PbapServerProfile: Bluetooth service connected
,10-29 01:42:52.877  5768  5768 D BluetoothPbap: Proxy object connected
10-29 01:42:52.877  5768  5768 D PbapServerProfile: Bluetooth service connected
,10-29 01:42:52.883  5923  5923 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-29 01:42:52.883  5923  5923 D ObexServerSockets0: prepareForNewConnect()
,10-29 01:42:52.890  5923  5967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 01:42:52.899  5923  5971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 01:42:52.900  5923  5971 I BtOppRfcommListener: Accept thread started.
,10-29 01:42:52.936   930   930 D BluetoothHeadset: Proxy object connected
,10-29 01:42:52.936   930   930 D BluetoothHeadset: Proxy object connected
10-29 01:42:52.936   930   930 D BluetoothHeadset: Proxy object connected
10-29 01:42:52.936  3200  3212 D BluetoothHeadset: Proxy object connected
10-29 01:42:52.936  3200  3200 D HeadsetProfile: Bluetooth service connected
10-29 01:42:52.937  3858  3887 D BluetoothHeadset: Proxy object connected
,10-29 01:42:52.939   930   947 D BluetoothHeadset: Proxy object connected
,10-29 01:42:52.943   930   947 D BluetoothHeadset: Proxy object connected
,10-29 01:42:52.945  3200  4033 D BluetoothHeadset: Proxy object connected
,10-29 01:42:52.945  3200  3200 D HeadsetProfile: Bluetooth service connected
10-29 01:42:52.945   930   947 D BluetoothHeadset: Proxy object connected
,10-29 01:42:52.958  5768  5781 D BluetoothHeadset: Proxy object connected
,10-29 01:42:52.959  5768  5768 D HeadsetProfile: Bluetooth service connected
,10-29 01:42:54.378   930  3045 D ConnectivityService: handlePromptUnvalidated 101
,10-29 01:42:54.580   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-29 01:42:54.581   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-29 01:42:56.749  5923  5935 D BluetoothAdapterState: Current state: ON, message: 23
,10-29 01:42:56.749  5923  5935 D BluetoothAdapterProperties: Setting state to 13
10-29 01:42:56.749  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-29 01:42:56.750  5923  5935 D BluetoothAdapterProperties: onBluetoothDisable()
10-29 01:42:56.752  5923  5935 I BluetoothAdapterState: Entering PendingCommandState
,10-29 01:42:56.755  5923  5923 D BluetoothMapService: onReceive
10-29 01:42:56.755  5923  5923 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-29 01:42:56.755  5923  5923 D BluetoothMapService: STATE_TURNING_OFF
10-29 01:42:56.756  5923  5923 D BluetoothMapService: MAP Service closeService in
10-29 01:42:56.756  5923  5923 D BluetoothMapMasInstance0: MAP Service shutdown
10-29 01:42:56.756  5923  5923 D ObexServerSockets0: shutdown(block = true)
10-29 01:42:56.757  5923  5923 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-29 01:42:56.758  5923  5923 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-29 01:42:56.758  5923  5961 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,10-29 01:42:56.758  5923  5962 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-29 01:42:56.758  5923  5948 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-29 01:42:56.760  5923  5939 D BluetoothAdapterProperties: Scan Mode:20
10-29 01:42:56.760  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-29 01:42:56.760  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:56.760  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:56.760  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:56.760  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:56.760  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:56.760  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:56.760  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:56.760  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:56.760  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:56.761  5768  5768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-29 01:42:56.762  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 01:42:56.762  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-29 01:42:56.764  5923  5923 I BtOppRfcommListener: stopping Accept Thread
,10-29 01:42:56.765  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:56.765  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:56.765  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:56.765  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:56.765  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:56.765  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:56.765  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:56.765  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:56.765  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:56.768  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:56.768  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:56.768  5923  5971 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-29 01:42:56.768  5923  5971 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-29 01:42:56.771  5923  5923 D HeadsetService: Received stop request...Stopping profile...
10-29 01:42:56.774  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 01:42:56.774   930   930 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:56.774  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:42:56.774  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:42:56.774  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:42:56.774  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:42:56.774  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 01:42:56.774  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:42:56.774  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:42:56.774  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:42:56.774   930   930 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:56.776  5704  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 01:42:56.776  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:42:56.776  5923  5923 D A2dpService: Received stop request...Stopping profile...
10-29 01:42:56.777  5923  5954 D A2dpStateMachine: Exit Disconnected: -1
10-29 01:42:56.778  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:56.780  5768  5779 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:56.780   930   930 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:56.780  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:56.780  3200  4033 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:56.781  3858  4277 D BluetoothHeadset: Proxy object disconnected
10-29 01:42:56.782  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:56.782   930   930 D BluetoothA2dp: Proxy object disconnected
10-29 01:42:56.784  5923  5923 D HidService: Received stop request...Stopping profile...
10-29 01:42:56.785  5923  5923 D HidService: Stopping Bluetooth HidService
10-29 01:42:56.786  3200  3200 D HeadsetProfile: Bluetooth service disconnected
10-29 01:42:56.786  3200  3200 D BluetoothA2dp: Proxy object disconnected
10-29 01:42:56.786  3200  3200 D BluetoothInputDevice: Proxy object disconnected
10-29 01:42:56.786  3200  3200 D HidProfile: Bluetooth service disconnected
10-29 01:42:56.786  5923  5923 D HealthService: Received stop request...Stopping profile...
,10-29 01:42:56.788  5768  5768 D DockEventReceiver: finishStartingService: stopping service
10-29 01:42:56.790  5768  5768 D HeadsetProfile: Bluetooth service disconnected
10-29 01:42:56.790  5768  5768 D BluetoothA2dp: Proxy object disconnected
10-29 01:42:56.791  5768  5768 D BluetoothInputDevice: Proxy object disconnected
10-29 01:42:56.791  5768  5768 D HidProfile: Bluetooth service disconnected
10-29 01:42:56.791  5923  5923 V BluetoothAdapterState: isTurningOff()=true
,10-29 01:42:56.791  5923  5923 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:56.791  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:56.791  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 01:42:56.796  3645  3645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 01:42:56.797  5923  5923 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-29 01:42:56.797  5923  5923 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-29 01:42:56.797  5923  5946 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:56.797  5923  5946 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:56.797  5923  5946 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:56.798  5923  5923 D PanService: Received stop request...Stopping profile...
10-29 01:42:56.799  3200  3200 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-29 01:42:56.799  3200  3200 D PanProfile: Bluetooth service disconnected
10-29 01:42:56.800  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-29 01:42:56.800  5923  5923 D BluetoothMapService: Received stop request...Stopping profile...
10-29 01:42:56.800  5923  5923 D BluetoothMapService: stop()
10-29 01:42:56.800  5923  5939 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-29 01:42:56.801  5923  5923 D BluetoothMapAppObserver: deinitObservers()
10-29 01:42:56.801  5923  5923 D BluetoothMapAppObserver: removeReceiver()
10-29 01:42:56.802  3200  3200 D BluetoothMap: Proxy object disconnected
10-29 01:42:56.800  5768  5768 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-29 01:42:56.810  3200  3200 D MapProfile: Bluetooth service disconnected
10-29 01:42:56.810  5768  5768 D PanProfile: Bluetooth service disconnected
10-29 01:42:56.810  5768  5768 D BluetoothMap: Proxy object disconnected
10-29 01:42:56.810  5768  5768 D MapProfile: Bluetooth service disconnected
10-29 01:42:56.803  5923  5923 D SapService: Received stop request...Stopping profile...
10-29 01:42:56.811  5923  5923 V SapService: stop()
10-29 01:42:56.812  5923  5923 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:56.812  5923  5923 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:56.812  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:56.813  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 01:42:56.814  5923  5923 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:56.814  5923  5923 V BluetoothAdapterState: isTurningOn()=false
,10-29 01:42:56.814  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:56.814  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:56.814  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-29 01:42:56.814  5923  5946 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:56.814  5923  5923 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-29 01:42:56.814  5923  5946 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:56.814  5923  5923 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-29 01:42:56.814  5923  5946 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-29 01:42:56.814  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-29 01:42:56.814  5923  5946 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-29 01:42:56.814  5923  5946 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-29 01:42:56.814  5923  5923 V BluetoothAdapterState: isTurningOff()=true
,10-29 01:42:56.814  5923  5946 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-29 01:42:56.814  5923  5923 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:56.815  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:56.815  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:56.815  5923  5923 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-29 01:42:56.815  5923  5939 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-29 01:42:56.815  5923  5923 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-29 01:42:56.817  3200  3200 D BluetoothPbap: Proxy object disconnected
10-29 01:42:56.817  3200  3200 D PbapServerProfile: Bluetooth service disconnected
10-29 01:42:56.818  5923  5923 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:56.818  5923  5923 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:56.818  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:56.818  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:56.818  5923  5923 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-29 01:42:56.824  5923  5923 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-29 01:42:56.826  5923  5923 D BluetoothMapService: MAP Service closeService in
10-29 01:42:56.826  5923  5923 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:56.826  5923  5923 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:56.826  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:56.826  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:56.826  5923  5923 D BluetoothMapService: cleanup()
10-29 01:42:56.826  5923  5923 D BluetoothMapService: MAP Service closeService in
10-29 01:42:56.826  5923  5923 V BluetoothAdapterState: isTurningOff()=true
10-29 01:42:56.826  5923  5923 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:56.826  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
,10-29 01:42:56.826  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:42:56.826  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-29 01:42:56.827  5923  5935 D BluetoothAdapterProperties: Setting state to 15
10-29 01:42:56.827  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-29 01:42:56.827  5923  5935 I BluetoothAdapterState: Entering BleOnState
10-29 01:42:56.827  3200  4033 D BluetoothMap: onBluetoothStateChange: up=false
10-29 01:42:56.828  5768  5781 D BluetoothA2dp: onBluetoothStateChange: up=false
10-29 01:42:56.828  3858  3894 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:56.829  5768  5779 D BluetoothPbap: onBluetoothStateChange: up=false
10-29 01:42:56.829  3200  3993 D BluetoothPan: onBluetoothStateChange on: false
10-29 01:42:56.830  3200  3213 D BluetoothA2dp: onBluetoothStateChange: up=false
10-29 01:42:56.830   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:56.830  5768  5781 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:56.830  3200  3212 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-29 01:42:56.831  5768  5779 D BluetoothMap: onBluetoothStateChange: up=false
10-29 01:42:56.831  5768  5781 D BluetoothPan: onBluetoothStateChange on: false
10-29 01:42:56.832  3200  4033 D BluetoothPbap: onBluetoothStateChange: up=false
10-29 01:42:56.832   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:56.833  3200  3993 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:56.833   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 01:42:56.833   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-29 01:42:56.833  5768  5779 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-29 01:42:56.833  5923  5935 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-29 01:42:56.834  5923  5935 D BluetoothAdapterProperties: Setting state to 16
10-29 01:42:56.834  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-29 01:42:56.834  5923  5935 D BluetoothAdapterProperties: onBleDisable
,10-29 01:42:56.828  5768  5768 D BluetoothPbap: Proxy object disconnected
10-29 01:42:56.835  5768  5768 D PbapServerProfile: Bluetooth service disconnected
10-29 01:42:56.835  5923  5935 I BluetoothAdapterState: Entering PendingCommandState
10-29 01:42:56.835  5923  5936 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-29 01:42:56.836  5923  5946 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-29 01:42:56.836  5923  5946 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 01:42:56.837  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:56.837  5923  5939 D BluetoothAdapterProperties: Scan Mode:20
10-29 01:42:56.837  5768  5768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-29 01:42:56.838  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:56.841  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:56.843  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:56.843  5768  5768 D DockEventReceiver: finishStartingService: stopping service
10-29 01:42:56.844  3645  3645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 01:42:56.845  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:42:56.846  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:42:57.048  5923  5939 I bt_hci  : shut_down
,10-29 01:42:57.059  5923  5943 D bt_hwcfg: hw_epilog_process
,10-29 01:42:57.060  5923  5943 I bt_vendor: low_power_mode_cb
,10-29 01:42:57.064  5923  5943 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-29 01:42:57.064  5923  5943 I bt_vendor: epilog_cb
10-29 01:42:57.064  5923  5943 I bt_hci  : epilog_finished_callback
,10-29 01:42:57.070  5923  5939 I bt_hci_h4: hal_close
,10-29 01:42:57.071  5923  5939 I bt_userial_vendor: device fd = 54 close
,10-29 01:42:57.185  5923  5936 D bt_stack_manager: event_shut_down_stack finished.
,10-29 01:42:57.186  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-29 01:42:57.190  5923  5923 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-29 01:42:57.191  5923  5935 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-29 01:42:57.191  5923  5923 D BtGatt.GattService: Received stop request...Stopping profile...
10-29 01:42:57.192  5923  5923 D BtGatt.GattService: stop()
10-29 01:42:57.192  5923  5923 D BtGatt.AdvertiseManager: advertise clients cleared
10-29 01:42:57.195  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-29 01:42:57.195  5923  5923 V BluetoothAdapterState: isTurningOn()=false
10-29 01:42:57.195  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:42:57.195  5923  5923 V BluetoothAdapterState: isBleTurningOff()=true
10-29 01:42:57.196  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-29 01:42:57.196  5923  5935 D BluetoothAdapterProperties: Setting state to 10
10-29 01:42:57.196  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-29 01:42:57.198  5923  5935 I BluetoothAdapterState: Entering OffState
,10-29 01:42:57.199   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-29 01:42:57.220  5923  5923 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-29 01:42:57.220  5923  5923 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,10-29 01:42:57.220  5923  5936 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-29 01:42:57.224  5923  5923 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-29 01:42:57.228  5923  5923 I art     : System.exit called, status: 0
,10-29 01:42:57.229  5923  5923 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-29 01:42:57.259   930  3900 I ActivityManager: Process com.android.bluetooth (pid 5923) has died
,10-29 01:43:01.746  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:43:01.747  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:43:01.752  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:43:01.752  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d1c26c removed from the list
,10-29 01:43:01.752  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:43:01.752  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:43:01.753  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:43:01.757  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 01:43:01.757  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@131ccca added. We now have 4 listener(s)
,10-29 01:43:01.758  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 01:43:01.760  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:43:01.761  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@131ccca removed from the list
10-29 01:43:01.761  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:43:01.761  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:01.761  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:01.763  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:01.763  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd5ee3b added. We now have 4 listener(s)
10-29 01:43:01.763  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 01:43:04.582   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:05.584   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:06.585   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:06.774  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:43:06.804   930   947 I ActivityManager: Start proc 5979:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-29 01:43:06.876  5979  5979 D AdapterServiceConfig: Adding HeadsetService
,10-29 01:43:06.876  5979  5979 D AdapterServiceConfig: Adding A2dpService
10-29 01:43:06.877  5979  5979 D AdapterServiceConfig: Adding HidService
10-29 01:43:06.877  5979  5979 D AdapterServiceConfig: Adding HealthService
10-29 01:43:06.877  5979  5979 D AdapterServiceConfig: Adding PanService
10-29 01:43:06.877  5979  5979 D AdapterServiceConfig: Adding GattService
10-29 01:43:06.877  5979  5979 D AdapterServiceConfig: Adding BluetoothMapService
10-29 01:43:06.877  5979  5979 D AdapterServiceConfig: Adding SapService
,10-29 01:43:06.890   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff5993e:true
,10-29 01:43:06.890  5979  5979 D BluetoothAdapterState: make() - Creating AdapterState
,10-29 01:43:06.893  5979  5979 I bt_bluedroid: init
,10-29 01:43:06.893  5979  5991 I BluetoothAdapterState: Entering OffState
,10-29 01:43:06.895  5979  5992 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-29 01:43:06.895  5979  5992 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,10-29 01:43:06.895  5979  5992 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-29 01:43:06.895  5979  5992 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-29 01:43:06.896  5979  5979 I bt_bluedroid: get_profile_interface socket
,10-29 01:43:06.898  5979  5979 I bt_bluedroid: get_profile_interface sdp
,10-29 01:43:06.898  5979  5995 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-29 01:43:06.899  5979  5995 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-29 01:43:06.903  5979  5990 I bt_bluedroid: config_hci_snoop_log
10-29 01:43:06.904   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-29 01:43:06.908  5979  5991 D BluetoothAdapterState: Current state: OFF, message: 0
10-29 01:43:06.908  5979  5991 D BluetoothAdapterProperties: Setting state to 14
,10-29 01:43:06.908  5979  5991 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-29 01:43:06.909  5979  5991 D BluetoothBondStateMachine: make
,10-29 01:43:06.912  5979  5996 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-29 01:43:06.916  5979  5991 I BluetoothAdapterState: Entering PendingCommandState
,10-29 01:43:06.917  5979  5979 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-29 01:43:06.920  5979  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
,10-29 01:43:06.921  5979  5979 D BtGatt.DebugUtils: handleDebugAction() action=null
10-29 01:43:06.922  5979  5979 D BtGatt.GattService: Received start request. Starting profile...
,10-29 01:43:06.922  5979  5979 D BtGatt.GattService: start()
10-29 01:43:06.922  5979  5979 I bt_bluedroid: get_profile_interface gatt
10-29 01:43:06.923  5979  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:43:06.923  5979  5979 D BtGatt.AdvertiseManager: advertise manager created
,10-29 01:43:06.932  5979  5979 V BluetoothAdapterState: isTurningOff()=false
,10-29 01:43:06.932  5979  5979 V BluetoothAdapterState: isTurningOn()=false
10-29 01:43:06.932  5979  5979 V BluetoothAdapterState: isBleTurningOn()=true
10-29 01:43:06.932  5979  5979 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:43:06.933  5979  5991 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-29 01:43:06.934  5979  5991 I bt_bluedroid: bt_bluedroid
10-29 01:43:06.934  5979  5992 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-29 01:43:06.934  5979  5992 I bt_hci  : start_up
,10-29 01:43:06.940  5979  5992 I bt_vendor: alloc value 0xf3e0b871
,10-29 01:43:06.940  5979  5992 I bt_vendor: init
10-29 01:43:06.940  5979  5992 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-29 01:43:06.940  5979  5992 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-29 01:43:07.051  5979  5992 D bt_hci  : start_up starting async portion
,10-29 01:43:07.052  5979  5999 I bt_hci  : event_finish_startup
10-29 01:43:07.052  5979  5999 I bt_hci_h4: hal_open
10-29 01:43:07.052  5979  5999 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-29 01:43:07.054  5979  5999 I bt_userial_vendor: device fd = 54 open
,10-29 01:43:07.051  6000  6000 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-29 01:43:07.071  5979  5999 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-29 01:43:07.075  5979  5999 D bt_hwcfg: Chipset BCM4358A3
,10-29 01:43:07.076  5979  5999 D bt_hwcfg: Target name = [BCM4358A3]
,10-29 01:43:07.076  5979  5999 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-29 01:43:07.580  5979  5999 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-29 01:43:07.580  5979  5999 D bt_hwcfg: Settlement delay -- 100 ms
10-29 01:43:07.580  5979  5999 I bt_hwcfg: Setting fw settlement delay to 100 
,10-29 01:43:07.586   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:07.715  5979  5999 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-29 01:43:07.715  5979  5999 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-29 01:43:07.717  5979  5999 I bt_hwcfg: vendor lib fwcfg completed
10-29 01:43:07.717  5979  5999 I bt_vendor: firmware callback
,10-29 01:43:07.717  5979  5999 I bt_hci  : firmware_config_callback
,10-29 01:43:07.729  5979  6002 I bt_btu  : btu_task pending for preload complete event
,10-29 01:43:07.729  5979  6002 I bt_btu_task: Bluetooth chip preload is complete
10-29 01:43:07.729  5979  6002 I bt_btu  : btu_task received preload complete event
,10-29 01:43:07.735  5979  6002 I         : BTE_InitTraceLevels -- TRC_HCI
,10-29 01:43:07.736  5979  6002 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-29 01:43:07.736  5979  6002 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-29 01:43:07.736  5979  6002 I         : BTE_InitTraceLevels -- TRC_AVDT
10-29 01:43:07.736  5979  6002 I         : BTE_InitTraceLevels -- TRC_AVRC
10-29 01:43:07.736  5979  6002 I         : BTE_InitTraceLevels -- TRC_A2D
10-29 01:43:07.736  5979  6002 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-29 01:43:07.736  5979  6002 I         : BTE_InitTraceLevels -- TRC_BTM
10-29 01:43:07.737  5979  6002 I         : BTE_InitTraceLevels -- TRC_GAP
10-29 01:43:07.737  5979  6002 I         : BTE_InitTraceLevels -- TRC_PAN
10-29 01:43:07.737  5979  6002 I         : BTE_InitTraceLevels -- TRC_SDP
10-29 01:43:07.737  5979  6002 I         : BTE_InitTraceLevels -- TRC_GATT
10-29 01:43:07.737  5979  6002 I         : BTE_InitTraceLevels -- TRC_SMP
,10-29 01:43:07.737  5979  6002 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-29 01:43:07.737  5979  6002 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-29 01:43:07.830  5979  6002 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d89549
,10-29 01:43:07.831  5979  6002 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d89549 
,10-29 01:43:07.861  5979  5995 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-29 01:43:07.864  5979  5995 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-29 01:43:07.864  5979  5995 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-29 01:43:07.867  5979  5995 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-29 01:43:07.871  5979  5995 D BluetoothAdapterProperties: Scan Mode:20
,10-29 01:43:07.872  5979  5995 D BluetoothAdapterProperties: Discoverable Timeout:120
10-29 01:43:07.872  5979  5995 D bt_hci  : do_postload posting postload work item
10-29 01:43:07.872  5979  5999 I bt_hci  : event_postload
10-29 01:43:07.872  5979  5999 I bt_vendor: sco_config_cb
10-29 01:43:07.872  5979  5999 I bt_hci  : sco_config_callback postload finished.
10-29 01:43:07.873  5979  5995 D bt_bte_conf: Device ID record 1 : primary
10-29 01:43:07.873  5979  5995 D bt_bte_conf:   vendorId            = 000f
10-29 01:43:07.873  5979  5995 D bt_bte_conf:   vendorIdSource      = 0001
10-29 01:43:07.873  5979  5995 D bt_bte_conf:   product             = 1200
10-29 01:43:07.873  5979  5995 D bt_bte_conf:   version             = 1436
10-29 01:43:07.873  5979  5995 D bt_bte_conf:   clientExecutableURL = 
10-29 01:43:07.873  5979  5995 D bt_bte_conf:   serviceDescription  = 
10-29 01:43:07.874  5979  5995 D bt_bte_conf:   documentationURL    = 
10-29 01:43:07.874  5979  5995 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-29 01:43:07.874  5979  5992 D bt_stack_manager: event_start_up_stack finished
10-29 01:43:07.875  5979  5991 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-29 01:43:07.875  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:43:07.875  5979  5991 D BluetoothAdapterProperties: Setting state to 15
10-29 01:43:07.875  5979  5991 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-29 01:43:07.876  5979  5991 I BluetoothAdapterState: Entering BleOnState
10-29 01:43:07.879  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:07.881  5979  5991 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-29 01:43:07.881  5979  5991 D BluetoothAdapterProperties: Setting state to 11
10-29 01:43:07.881  5979  5991 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-29 01:43:07.882  5979  5999 I bt_vendor: low_power_mode_cb
,10-29 01:43:07.889  5979  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:43:07.890  5979  5979 D HeadsetService: Received start request. Starting profile...
10-29 01:43:07.893  5979  5979 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-29 01:43:07.893  5979  5979 D HeadsetStateMachine: make
,10-29 01:43:07.895  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:07.897  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:43:07.903  5979  5979 D HeadsetStateMachine: max_hf_connections = 1
10-29 01:43:07.903  5979  5979 I bt_bluedroid: get_profile_interface handsfree
10-29 01:43:07.903  5979  5995 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-29 01:43:07.904  5979  5995 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-29 01:43:07.909  5979  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
,10-29 01:43:07.910  5979  5979 D A2dpService: Received start request. Starting profile...
10-29 01:43:07.911  5979  5979 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-29 01:43:07.911  5979  5979 I bt_bluedroid: get_profile_interface avrcp
10-29 01:43:07.913  5979  5991 I BluetoothAdapterState: Entering PendingCommandState
,10-29 01:43:07.919  5979  5979 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-29 01:43:07.919  5979  5979 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-29 01:43:07.919  5979  5979 D A2dpStateMachine: make
,10-29 01:43:07.921  5979  5979 I bt_bluedroid: get_profile_interface a2dp
10-29 01:43:07.921  5979  5995 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-29 01:43:07.926  5979  6010 D A2dpStateMachine: Enter Disconnected: -2
,10-29 01:43:07.927  5979  5979 I BluetoothHidServiceJni: classInitNative: succeeds
10-29 01:43:07.928  5979  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:43:07.928  5979  5979 V BluetoothAdapterState: isTurningOff()=false
10-29 01:43:07.929  5979  5979 V BluetoothAdapterState: isTurningOn()=true
10-29 01:43:07.929  5979  5979 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:43:07.929  5979  5979 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 01:43:07.929  5979  5979 D HidService: Received start request. Starting profile...
10-29 01:43:07.930  5979  5979 I bt_bluedroid: get_profile_interface hidhost
10-29 01:43:07.930  5979  5979 D HidService: setHidService(): set to: null
,10-29 01:43:07.930  5979  5995 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d6a56d
10-29 01:43:07.930  5979  5995 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-29 01:43:07.930  5979  5979 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-29 01:43:07.931  5979  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:43:07.932  5979  5979 D HealthService: Received start request. Starting profile...
,10-29 01:43:07.933  5979  5979 I bt_bluedroid: get_profile_interface health
10-29 01:43:07.934  5979  6008 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-29 01:43:07.934  5979  5979 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-29 01:43:07.935  5979  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:43:07.936  5979  5979 D PanService: Received start request. Starting profile...
,10-29 01:43:07.936  5979  5979 D BluetoothPanServiceJni: initializeNative(L110): pan
10-29 01:43:07.936  5979  5979 I bt_bluedroid: get_profile_interface pan
10-29 01:43:07.937  5979  5995 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-29 01:43:07.940  5979  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
,10-29 01:43:07.940  5979  5979 D BluetoothMapService: Received start request. Starting profile...
10-29 01:43:07.941  5979  5979 D BluetoothMapService: start()
,10-29 01:43:07.943  5979  5979 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-29 01:43:07.944  5979  5979 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-29 01:43:07.944  5979  5979 D BluetoothMapAppObserver: createReceiver()
,10-29 01:43:07.945  5979  5979 D BluetoothMapAppObserver: initObservers()
10-29 01:43:07.945  5979  5979 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-29 01:43:07.954  5979  5979 V SapService: SapBinder()
10-29 01:43:07.955  5979  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:43:07.955  5979  5979 D SapService: Received start request. Starting profile...
,10-29 01:43:07.955  5979  5979 V SapService: start()
,10-29 01:43:07.957  5979  5979 V BluetoothAdapterState: isTurningOff()=false
10-29 01:43:07.957  5979  5979 V BluetoothAdapterState: isTurningOn()=true
10-29 01:43:07.957  5979  5979 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:43:07.957  5979  5979 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:43:07.957  5979  5979 V BluetoothAdapterState: isTurningOff()=false
10-29 01:43:07.957  5979  5979 V BluetoothAdapterState: isTurningOn()=true
10-29 01:43:07.957  5979  5979 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:43:07.957  5979  5979 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isTurningOff()=false
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isTurningOn()=true
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isTurningOff()=false
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isTurningOn()=true
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isTurningOff()=false
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isTurningOn()=true
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:43:07.958  5979  5979 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:43:07.959  5979  5979 V BluetoothAdapterState: isTurningOff()=false
10-29 01:43:07.959  3645  3645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-29 01:43:07.959  5979  5979 V BluetoothAdapterState: isTurningOn()=true
10-29 01:43:07.959  5979  5979 V BluetoothAdapterState: isBleTurningOn()=false
10-29 01:43:07.959  5979  5979 V BluetoothAdapterState: isBleTurningOff()=false
10-29 01:43:07.959  5979  5991 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-29 01:43:07.959  5979  5991 D BluetoothAdapterProperties: ScanMode =  20
10-29 01:43:07.959  5979  5991 D BluetoothAdapterProperties: State =  11
,10-29 01:43:07.962  5979  5995 D BluetoothAdapterProperties: Scan Mode:21
,10-29 01:43:07.962  5979  5991 D BluetoothAdapterProperties: Setting state to 12
10-29 01:43:07.962  5979  5991 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-29 01:43:07.962  5979  5995 D BluetoothAdapterProperties: Discoverable Timeout:120
10-29 01:43:07.962  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-29 01:43:07.963  3200  3212 D BluetoothMap: onBluetoothStateChange: up=true
10-29 01:43:07.964  5979  5991 I BluetoothAdapterState: Entering OnState
,10-29 01:43:07.965  5768  5781 D BluetoothA2dp: onBluetoothStateChange: up=true
10-29 01:43:07.966  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:43:07.966  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:07.966  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:07.966  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:43:07.966  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:07.966  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:43:07.966  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:43:07.966  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:43:07.966  3200  3200 D BluetoothMap: Proxy object connected
10-29 01:43:07.966  3200  3200 D MapProfile: Bluetooth service connected
10-29 01:43:07.966  3200  3200 D BluetoothMap: getConnectedDevices()
,10-29 01:43:07.967  3858  3894 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 01:43:07.968  5768  5779 D BluetoothPbap: onBluetoothStateChange: up=true
10-29 01:43:07.971  3200  3993 D BluetoothPan: onBluetoothStateChange on: true
10-29 01:43:07.971  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:43:07.971  5768  5768 D BluetoothA2dp: Proxy object connected
10-29 01:43:07.973  3200  3213 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-29 01:43:07.974  5979  5979 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-29 01:43:07.974  5979  5979 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-29 01:43:07.974  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:43:07.974  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:07.974  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:07.974  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:43:07.974  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:07.974  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:43:07.974  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:43:07.974  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 01:43:07.976   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-29 01:43:07.977  5768  5781 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 01:43:07.977  5979  5979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 01:43:07.977  3200  3200 D BluetoothA2dp: Proxy object connected
10-29 01:43:07.977  3200  4033 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-29 01:43:07.977  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-29 01:43:07.980  5768  5779 D BluetoothMap: onBluetoothStateChange: up=true
,10-29 01:43:07.980  5979  5979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 01:43:07.981  5768  5781 D BluetoothPan: onBluetoothStateChange on: true
10-29 01:43:07.982  5979  5979 D ObexServerSockets: Succeed to create listening sockets 
10-29 01:43:07.982  5979  5979 D ObexServerSockets0: startAccept()
10-29 01:43:07.982  5979  5979 D ObexServerSockets0: prepareForNewConnect()
10-29 01:43:07.983  3200  3993 D BluetoothPbap: onBluetoothStateChange: up=true
10-29 01:43:07.984  5979  5979 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-29 01:43:07.984  5979  5979 D BluetoothSdpJni: SDP Create record success - handle: 0
10-29 01:43:07.984  5768  5768 D BluetoothMap: Proxy object connected
10-29 01:43:07.984  5768  5768 D MapProfile: Bluetooth service connected
10-29 01:43:07.984  5768  5768 D BluetoothMap: getConnectedDevices()
,10-29 01:43:07.985   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 01:43:07.985  5979  6017 D ObexServerSockets0: Accepting socket connection...
10-29 01:43:07.985  5979  6018 D ObexServerSockets0: Accepting socket connection...
10-29 01:43:07.985  3200  3213 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 01:43:07.986  3200  3200 D BluetoothPan: BluetoothPAN Proxy object connected
10-29 01:43:07.986   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 01:43:07.986  3200  3200 D PanProfile: Bluetooth service connected
10-29 01:43:07.986   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-29 01:43:07.987   930   930 D BluetoothA2dp: Proxy object connected
10-29 01:43:07.987  5768  5779 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-29 01:43:07.987  5768  5768 D BluetoothPan: BluetoothPAN Proxy object connected
10-29 01:43:07.987  3200  3200 D BluetoothInputDevice: Proxy object connected
10-29 01:43:07.988  5768  5768 D PanProfile: Bluetooth service connected
,10-29 01:43:07.988  3200  3200 D HidProfile: Bluetooth service connected
10-29 01:43:07.990  5768  5768 D BluetoothInputDevice: Proxy object connected
10-29 01:43:07.990  5768  5768 D HidProfile: Bluetooth service connected
10-29 01:43:07.991   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-29 01:43:07.992  5979  5979 D BluetoothMapService: onReceive
10-29 01:43:07.992  5979  5979 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-29 01:43:07.992  5979  5979 D BluetoothMapService: STATE_ON
10-29 01:43:07.992  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-29 01:43:07.994  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:43:07.995  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:43:07.995  5979  6019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 01:43:07.997  5979  6019 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-29 01:43:07.997  5979  6019 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-29 01:43:07.999  5768  5768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-29 01:43:08.005  5768  5768 D DockEventReceiver: finishStartingService: stopping service
10-29 01:43:08.005  3645  3645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-29 01:43:08.012  5768  5768 D BluetoothPbap: Proxy object connected
,10-29 01:43:08.012  5768  5768 D PbapServerProfile: Bluetooth service connected
10-29 01:43:08.012  3200  3200 D BluetoothPbap: Proxy object connected
10-29 01:43:08.012  3200  3200 D PbapServerProfile: Bluetooth service connected
,10-29 01:43:08.018  5979  5979 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-29 01:43:08.018  5979  5979 D ObexServerSockets0: prepareForNewConnect()
10-29 01:43:08.021  5979  6024 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 01:43:08.037  5979  6028 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 01:43:08.039  5979  6028 I BtOppRfcommListener: Accept thread started.
,10-29 01:43:08.070   930   930 D BluetoothHeadset: Proxy object connected
10-29 01:43:08.070   930   930 D BluetoothHeadset: Proxy object connected
10-29 01:43:08.071  5768  6016 D BluetoothHeadset: Proxy object connected
10-29 01:43:08.071   930   930 D BluetoothHeadset: Proxy object connected
10-29 01:43:08.071  3200  3213 D BluetoothHeadset: Proxy object connected
,10-29 01:43:08.071  3200  3200 D HeadsetProfile: Bluetooth service connected
10-29 01:43:08.071  3858  4051 D BluetoothHeadset: Proxy object connected
,10-29 01:43:08.073  5768  5768 D HeadsetProfile: Bluetooth service connected
,10-29 01:43:08.077   930   947 D BluetoothHeadset: Proxy object connected
,10-29 01:43:08.078  5768  5781 D BluetoothHeadset: Proxy object connected
10-29 01:43:08.078  5768  5768 D HeadsetProfile: Bluetooth service connected
,10-29 01:43:08.085   930   947 D BluetoothHeadset: Proxy object connected
,10-29 01:43:08.086  3200  3993 D BluetoothHeadset: Proxy object connected
10-29 01:43:08.086  3200  3200 D HeadsetProfile: Bluetooth service connected
,10-29 01:43:08.087   930   947 D BluetoothHeadset: Proxy object connected
,10-29 01:43:08.588   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:09.589   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-29 01:43:11.788  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:43:11.788  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:11.788  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:11.788  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 01:43:11.788  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:11.788  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:43:11.788  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:43:11.788  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 01:43:11.795  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-29 01:43:11.795  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:43:11.796  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd5ee3b removed from the list
10-29 01:43:11.796  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:43:11.796  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:11.796  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:11.799  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 01:43:11.800  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24e9958 added. We now have 4 listener(s)
,10-29 01:43:11.800  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 01:43:11.802   930  3896 D WifiService: setWifiEnabled: false pid=5704, uid=10077
10-29 01:43:11.802   930  3896 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 01:43:14.590   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:15.591   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:16.593   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:16.812  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:43:16.813   930  4853 D WifiService: setWifiEnabled: true pid=5704, uid=10077
10-29 01:43:16.814   930  4853 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 01:43:16.821   507   927 D SoftapController: Softap fwReload - Ok
,10-29 01:43:16.828   507   927 D CommandListener: Setting iface cfg
,10-29 01:43:16.828   507   927 D CommandListener: Trying to bring down wlan0
,10-29 01:43:16.830   507   927 D CommandListener: Clearing all IP addresses on wlan0
,10-29 01:43:16.836   930  3043 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-29 01:43:17.517   930  3043 D wifi    : set interface wlan0 flags (UP)
10-29 01:43:17.517   930  3043 I WifiHAL : Initializing wifi
10-29 01:43:17.517   930  3043 I WifiHAL : Creating socket
,10-29 01:43:17.523   930  3043 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-29 01:43:17.524   930  3043 D wifi    : Did set static halHandle = 0x7f5ebb1180
10-29 01:43:17.524   930  3043 D wifi    : halHandle = 0x7f5ebb1180, mVM = 0x7f7b28d140, mCls = 0x164e
10-29 01:43:17.524   930  3043 D wifi    : array field set
,10-29 01:43:17.524   930  3043 I WifiNative-HAL: interface[0] = wlan0
10-29 01:43:17.525   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-29 01:43:17.527   930  6033 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547050164608
10-29 01:43:17.527   930  6033 D wifi    : waitForHalEvents called, vm = 0x7f7b28d140, obj = 0x164e, env = 0x7f61122b00
,10-29 01:43:17.576  6034  6034 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-29 01:43:17.593   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:17.599  6034  6034 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-29 01:43:17.621  6034  6034 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-29 01:43:17.621  6034  6034 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-29 01:43:17.630   930  3043 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-29 01:43:17.643  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:43:17.646   930  3043 D WifiConfigStore: Loading config and enabling all networks 
,10-29 01:43:17.648  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:43:17.648  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:17.648  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:17.648  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:17.648  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:17.648  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:43:17.648  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:43:17.648  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 01:43:17.650  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-29 01:43:17.654   930  3043 D WifiConfigStore: loaded 0 passpoint configs
10-29 01:43:17.654   930  3043 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-29 01:43:17.655   930  3043 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-29 01:43:17.655  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:43:17.655  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:17.655  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:17.655  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:17.655  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:17.655  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 01:43:17.655  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 01:43:17.655  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 01:43:17.656   930  3043 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-29 01:43:17.657   930  3043 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-29 01:43:17.657   930  3043 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-29 01:43:17.658   930  3043 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-29 01:43:17.658  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 01:43:17.658   930  3043 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-29 01:43:17.659  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:43:17.662   930  3043 D WifiNative-HAL: Setting external_sim to 1
,10-29 01:43:17.662   930  3043 D wifi    : setting dfs flag to true, 0x7f647105e0
10-29 01:43:17.663   930  3043 D WifiStateMachine: Setting OUI to DA-A1-19
10-29 01:43:17.663   930  3043 D wifi    : setting scan oui 0x7f647105e0
10-29 01:43:17.663   930  3043 D WifiHAL : Sending mac address OUI
10-29 01:43:17.663  5090  5090 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-29 01:43:17.667   930  3043 E native  : do suspend false
,10-29 01:43:17.675   930  3043 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-29 01:43:17.676   930   930 D RttService: SCAN_AVAILABLE : 3
,10-29 01:43:17.676   930  3153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-29 01:43:17.676   507   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-29 01:43:17.677   507   927 D CommandListener: Setting iface cfg
,10-29 01:43:17.680   930  3037 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,10-29 01:43:17.680   930  3037 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-29 01:43:17.690   930  3037 D WifiNative-HAL: p2pGetDeviceAddress
,10-29 01:43:17.690   930  3037 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-29 01:43:17.696   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=242543 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-29 01:43:18.594   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:19.595   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-29 01:43:20.753  6034  6034 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 01:43:20.758  6034  6034 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 01:43:20.763  6034  6034 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 01:43:20.821   930  3043 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-29 01:43:20.822   930  3043 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-29 01:43:20.823   930  3043 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 01:43:20.834   930  3043 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-29 01:43:20.866   930  3043 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-29 01:43:20.868  6034  6034 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-29 01:43:21.290  6034  6034 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-29 01:43:21.326  6034  6034 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-29 01:43:21.328  6034  6034 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-29 01:43:21.340   930  3043 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-29 01:43:21.340   930  3043 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-29 01:43:21.340   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-29 01:43:21.355   930  3043 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 01:43:21.367   507   927 D CommandListener: Setting iface cfg
,10-29 01:43:21.372   930  3043 D WifiStateMachine: Start Dhcp Watchdog 3
,10-29 01:43:21.378   930  6039 D DhcpClient: Receive thread started
,10-29 01:43:21.383   930  3045 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-29 01:43:21.383   930  3043 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-29 01:43:21.383   930  3045 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-29 01:43:21.464   930  3043 E native  : do suspend false
,10-29 01:43:21.480   930  6038 D DhcpClient: Broadcasting DHCPDISCOVER
,10-29 01:43:21.494   930  6039 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-29 01:43:21.495   930  6038 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-29 01:43:21.497   930  6038 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-29 01:43:21.511   930  6039 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-29 01:43:21.512   930  6038 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-29 01:43:21.515   507   927 D CommandListener: Setting iface cfg
10-29 01:43:21.520   930  3043 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-29 01:43:21.526   930  6038 D DhcpClient: Scheduling renewal in 86399s
,10-29 01:43:21.538   930  3043 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-29 01:43:21.540   930  3043 D WifiConfigStore: No blacklist allowed without epno enabled
,10-29 01:43:21.541   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-29 01:43:21.543   930  3045 D ConnectivityService: Adding iface wlan0 to network 102
10-29 01:43:21.554   930  3043 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-29 01:43:21.603   930  3045 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-29 01:43:21.603   930  3045 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-29 01:43:21.609   930  3045 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-29 01:43:21.612   930  3045 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-29 01:43:21.617   930  3045 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-29 01:43:21.625   930  3045 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-29 01:43:21.631   930  3045 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-29 01:43:21.631   930  3045 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-29 01:43:21.631   930  3045 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-29 01:43:21.631   930  3043 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-29 01:43:21.631   930  3045 D ConnectivityService:    accepting network in place of null
10-29 01:43:21.631   930  3043 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-29 01:43:21.632   930  3045 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-29 01:43:21.651   930  6037 D NetlinkSocketObserver: NeighborEvent{elapsedMs=246498, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-29 01:43:21.658   507   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 01:43:21.681   507   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 01:43:21.685   930  3045 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-29 01:43:21.685  3827  3972 W QCNEJ   : |CORE| network available: 102
10-29 01:43:21.685   930  3045 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-29 01:43:21.687   930  3045 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,10-29 01:43:21.687  3827  3972 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-29 01:43:21.687   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-29 01:43:21.689  3827  3972 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-29 01:43:21.690  3827  3972 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-29 01:43:21.699  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:43:21.699  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:21.699  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:21.699  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:21.699  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:21.699  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.699  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:43:21.699  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:43:21.703  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 01:43:21.706  5116  5132 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-29 01:43:21.707  5116  5132 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-29 01:43:21.707  5116  5132 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,10-29 01:43:21.707  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:43:21.707  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:21.707  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:21.707  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:21.707  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:21.707  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.707  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:43:21.707  5704  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:43:21.707  5116  5132 E SarControlService: no key has been found,reset the power
10-29 01:43:21.707  5116  5153 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-29 01:43:21.707  5116  5153 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-29 01:43:21.707  5116  5153 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-29 01:43:21.708  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 01:43:21.708  5141  5141 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-29 01:43:21.708  5116  5153 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-29 01:43:21.708  5116  5153 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-29 01:43:21.709  5116  5153 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-29 01:43:21.709  5704  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.709  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 01:43:21.709  5141  5141 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-29 01:43:21.710  3980  3980 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-29 01:43:21.713  3809  3809 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-29 01:43:21.715  5141  5155 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9886be HexData = [00000000f003000000000000ffffffff]
10-29 01:43:21.716  5141  5155 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 01:43:21.716  5141  5155 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-29 01:43:21.716  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 01:43:21.716  5116  5126 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-29 01:43:21.716   930  6036 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-29 01:43:21.717  3809  3809 D SystemUpdateService: onCreate
,10-29 01:43:21.722  3809  3809 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-29 01:43:21.723  5141  5155 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9886be HexData = [00000000f103000000000000ffffffff]
10-29 01:43:21.723  5141  5155 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 01:43:21.723  5141  5155 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-29 01:43:21.723  5141  5141 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 01:43:21.724  5116  5127 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-29 01:43:21.733  3809  3809 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-29 01:43:21.738  3809  5480 I iu.UploadsManager: num queued entries: 0
,10-29 01:43:21.738  3809  5480 I iu.UploadsManager: num updated entries: 0
10-29 01:43:21.739  3809  5480 I iu.SyncManager: NEXT; no task
,10-29 01:43:21.742  3809  6049 I SystemUpdateService: active receiver: enabled
,10-29 01:43:21.744  3809  3809 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-29 01:43:21.746  3809  3809 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-29 01:43:21.748  5835  5835 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-29 01:43:21.751  5835  5835 D SprintDMHelper: simOperator: 
10-29 01:43:21.751  5835  5835 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-29 01:43:21.762   930  6036 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 29 Oct 2016 05:43:21 GMT], X-Android-Received-Millis=[1477719801761], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477719801741]}
,10-29 01:43:21.763   930  3045 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-29 01:43:21.763   930  3045 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-29 01:43:21.763   930  3045 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-29 01:43:21.764   930  3045 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-29 01:43:21.773  3809  6049 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-29 01:43:21.786  3809  6049 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-29 01:43:21.786  3809  6049 I SystemUpdateService: now status is 0 (complete)
10-29 01:43:21.786  3809  6049 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-29 01:43:21.786  3809  6049 I SystemUpdateService: file has been verified
10-29 01:43:21.786  3809  6049 I SystemUpdateService: OTA package size = 21989297
,10-29 01:43:21.792  3809  6049 I SystemUpdateService: showing system update notification
,10-29 01:43:21.803  3809  3809 D SystemUpdateService: onDestroy
,10-29 01:43:21.824  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 01:43:21.824  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:21.824  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:21.824  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:21.824  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:21.824  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.824  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:43:21.824  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:43:21.826  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 01:43:21.826  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:21.826  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24e9958 removed from the list
10-29 01:43:21.826  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:43:21.826  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.826  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:21.829  5704  5750 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-29 01:43:21.829  5704  5750 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-29 01:43:21.831  5704  5750 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7fc2f22 Bundle[{}]
10-29 01:43:21.831  5704  5750 I io.jxcore.node.LifeCycleMonitor: start: OK
10-29 01:43:21.831  5704  5750 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-29 01:43:21.831  5704  5750 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-29 01:43:21.833  5704  5750 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-29 01:43:21.833  5704  5750 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-29 01:43:21.834  5704  5750 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-29 01:43:21.838  5704  5750 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,10-29 01:43:21.839  5704  5750 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-29 01:43:21.839  5704  5750 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,10-29 01:43:21.840  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:21.840  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@404ab1 added. We now have 3 listener(s)
,10-29 01:43:21.841  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:21.842  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:43:21.842  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 01:43:21.842  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:21.842  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@807eb96 added. We now have 4 listener(s)
10-29 01:43:21.842  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:43:21.842  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-29 01:43:21.844  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 01:43:21.849  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:43:21.849  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:21.849  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:21.849  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:21.849  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:21.849  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.849  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:43:21.849  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:43:21.852  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 01:43:21.852  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:43:21.852  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:21.852  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bff304 added. We now have 4 listener(s)
,10-29 01:43:21.854  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:21.854  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:21.854  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:43:21.854  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 01:43:21.854  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:21.854  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddde0ed added. We now have 5 listener(s)
10-29 01:43:21.855  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 01:43:21.855  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:43:21.855  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:43:21.855  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:43:21.855  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:43:21.855  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.855  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:43:21.855  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:21.855  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:21.856  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@404ab1 removed from the list
10-29 01:43:21.856  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:21.856  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@807eb96 removed from the list
,10-29 01:43:21.856  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:21.857  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:43:21.857  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:43:21.857  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.857  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:21.857  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.858  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.858  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.859  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.859  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:43:21.859  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:43:21.859  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:21.859  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@807eb96 not in the list
10-29 01:43:21.859  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.859  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:21.859  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.860  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.860  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.860  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.860  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:43:21.860  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:43:21.860  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:21.860  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddde0ed removed from the list
10-29 01:43:21.860  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:43:21.860  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.860  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:21.860  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:21.860  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:21.860  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bff304 removed from the list
10-29 01:43:21.861  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:21.861  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f2b22 added. We now have 3 listener(s)
10-29 01:43:21.862  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:21.862  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-29 01:43:21.862  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 01:43:21.862  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:21.863  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25e9b3 added. We now have 4 listener(s)
10-29 01:43:21.863  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:43:21.863  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-29 01:43:21.865  5090  6054 I Babel   : connection state changed from DISCONNECTED to CONNECTED
10-29 01:43:21.865  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 01:43:21.872  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:43:21.872  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:21.872  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:21.872  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:21.872  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:21.872  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.872  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:43:21.872  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:43:21.875  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 01:43:21.875  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:43:21.875  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:21.875  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@449ee9 added. We now have 4 listener(s)
10-29 01:43:21.877  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:21.877  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:43:21.877  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-29 01:43:21.877  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:21.877  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:21.877  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d8d76e added. We now have 5 listener(s)
10-29 01:43:21.877  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:43:21.877  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 01:43:21.878  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 01:43:21.878  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 01:43:21.878  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:43:21.878  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-29 01:43:21.880  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 01:43:21.881  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-29 01:43:21.881  5704  5750 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 01:43:21.881  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-29 01:43:21.884  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.884  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-29 01:43:21.884  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 01:43:21.884  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-29 01:43:21.887  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.887  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 01:43:21.887  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 01:43:21.887  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-29 01:43:21.887  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 01:43:21.887  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.888  5704  5750 D BluetoothAdapter: STATE_ON
,10-29 01:43:21.890  5979  6015 D BtGatt.GattService: registerClient() - UUID=6b218616-080c-45a5-8eb2-eeda7a8f602b
,10-29 01:43:21.891  5979  5995 D BtGatt.GattService: onClientRegistered() - UUID=6b218616-080c-45a5-8eb2-eeda7a8f602b, clientIf=5
10-29 01:43:21.892  5704  5714 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-29 01:43:21.892  5979  6006 D BtGatt.GattService: start scan with filters
,10-29 01:43:21.896  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-29 01:43:21.896  5979  5998 D BtGatt.ScanManager: handling starting scan
10-29 01:43:21.896  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.896  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 01:43:21.896  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.896  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-29 01:43:21.896  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 01:43:21.897  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.897  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 01:43:21.897  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 01:43:21.897  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.897  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.897  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-29 01:43:21.898  5979  5998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e8aa717
10-29 01:43:21.898  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-29 01:43:21.898  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.901  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.901  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:43:21.901  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.901  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.901  5704  5750 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-29 01:43:21.901  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-29 01:43:21.901  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.901  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-29 01:43:21.901  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.901  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-29 01:43:21.902  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:21.902  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-29 01:43:21.904  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-29 01:43:21.904  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.904  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.904  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 01:43:21.904  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 01:43:21.904  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.904  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-29 01:43:21.904  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:43:21.904  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.904  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.904  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.904  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 01:43:21.904  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.904  5979  5995 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-29 01:43:21.905  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.905  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:43:21.905  5979  5998 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-29 01:43:21.905  5979  6015 D BtGatt.GattService: stopScan() - queue size =1
,10-29 01:43:21.906  5979  6006 D BtGatt.GattService: unregisterClient() - clientIf=5
10-29 01:43:21.906  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.907  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-29 01:43:21.907  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-29 01:43:21.909  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-29 01:43:21.909  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.910  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.910  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:43:21.910  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.910  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.910  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-29 01:43:21.910  5979  5995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 01:43:21.910  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:43:21.910  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.911  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 01:43:21.911  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.911  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 01:43:21.911  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-29 01:43:21.911  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.911  5979  5998 D BtGatt.ScanManager: Starting BLE batch scan
10-29 01:43:21.911  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.911  5979  5998 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-29 01:43:21.911  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 01:43:21.911  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-29 01:43:21.913  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 01:43:21.913  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:43:21.913  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:43:21.913  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:43:21.913  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.913  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:43:21.913  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:21.913  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:21.914  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f2b22 removed from the list
10-29 01:43:21.914  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:21.914  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25e9b3 removed from the list
10-29 01:43:21.914  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
,10-29 01:43:21.914  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:21.914  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.914  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.914  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.914  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.914  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:43:21.916  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.916  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:21.916  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.917  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.917  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.917  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.917  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:43:21.917  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:43:21.917  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:21.917  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d25e9b3 not in the list
10-29 01:43:21.917  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:43:21.917  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:21.917  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.918  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.918  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.918  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.918  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:43:21.918  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:43:21.918  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:21.918  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d8d76e removed from the list
10-29 01:43:21.918  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:43:21.918  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.918  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:43:21.919  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:21.919  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:21.919  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@449ee9 removed from the list
10-29 01:43:21.919  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:21.919  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3efc7a added. We now have 3 listener(s)
10-29 01:43:21.920  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:21.920  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:43:21.920  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-29 01:43:21.921  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:21.921  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21adc2b added. We now have 4 listener(s)
10-29 01:43:21.921  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:43:21.921  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-29 01:43:21.922  5979  5995 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-29 01:43:21.922  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.924  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 01:43:21.927  5979  5995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-29 01:43:21.927  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.928  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:43:21.928  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:21.928  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:21.928  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:21.928  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:21.928  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.928  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:43:21.928  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:43:21.930  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.930  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:43:21.930  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:21.930  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2884221 added. We now have 4 listener(s)
10-29 01:43:21.931  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:21.931  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:43:21.931  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 01:43:21.932  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:21.932  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb06646 added. We now have 5 listener(s)
10-29 01:43:21.932  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:43:21.932  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 01:43:21.932  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:21.933  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-29 01:43:21.933  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 01:43:21.933  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 01:43:21.933  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:43:21.933  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-29 01:43:21.935  5979  5995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-29 01:43:21.935  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:21.935  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.935  5979  5998 D BtGatt.ScanManager: stopping BLe Batch
,10-29 01:43:21.936  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-29 01:43:21.936  5704  5750 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 01:43:21.936  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-29 01:43:21.941  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.941  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-29 01:43:21.941  5979  5995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 01:43:21.941  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.941  5979  5998 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-29 01:43:21.941  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 01:43:21.941  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-29 01:43:21.944  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.944  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 01:43:21.944  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 01:43:21.944  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-29 01:43:21.944  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 01:43:21.944  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.945  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:43:21.945  5979  5995 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-29 01:43:21.945  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 01:43:21.947  5979  5989 D BtGatt.GattService: registerClient() - UUID=4cf64eb3-0cb6-4d57-8eff-98935b808fb2
10-29 01:43:21.947  5979  5995 D BtGatt.GattService: onClientRegistered() - UUID=4cf64eb3-0cb6-4d57-8eff-98935b808fb2, clientIf=5
,10-29 01:43:21.947  5704  5715 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-29 01:43:21.947  5979  6015 D BtGatt.GattService: start scan with filters
,10-29 01:43:21.949  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-29 01:43:21.949  5979  5998 D BtGatt.ScanManager: handling starting scan
10-29 01:43:21.949  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.950  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 01:43:21.950  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.950  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-29 01:43:21.950  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 01:43:21.950  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.950  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 01:43:21.950  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 01:43:21.950  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.950  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.950  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-29 01:43:21.951  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-29 01:43:21.951  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.953  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.953  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:43:21.954  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.954  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.954  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.954  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 01:43:21.954  5704  5750 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-29 01:43:21.954  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:43:21.954  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:43:21.954  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:43:21.954  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:43:21.954  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:43:21.954  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-29 01:43:21.954  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:21.954  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:21.954  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3efc7a removed from the list
10-29 01:43:21.954  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:21.954  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21adc2b removed from the list
10-29 01:43:21.954  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:43:21.954  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-29 01:43:21.954  5979  5995 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-29 01:43:21.954  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.955  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.955  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-29 01:43:21.955  5979  5998 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-29 01:43:21.955  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.955  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:43:21.955  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.956  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.956  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.956  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.956  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.956  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:43:21.956  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.956  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.956  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.956  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-29 01:43:21.957  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:43:21.957  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:43:21.957  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21adc2b not in the list
10-29 01:43:21.957  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 01:43:21.957  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 01:43:21.957  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-29 01:43:21.957  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.957  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.957  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.957  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 01:43:21.957  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.958  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:43:21.959  5979  6015 D BtGatt.GattService: stopScan() - queue size =1
10-29 01:43:21.959  5979  6020 D BtGatt.GattService: unregisterClient() - clientIf=5
10-29 01:43:21.959  5979  5995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 01:43:21.959  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-29 01:43:21.960  5979  5998 D BtGatt.ScanManager: Starting BLE batch scan
10-29 01:43:21.960  5979  5998 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.960  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-29 01:43:21.960  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 01:43:21.961  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:43:21.961  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.962  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.962  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:43:21.962  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.962  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.962  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:43:21.962  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:43:21.962  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:21.962  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb06646 removed from the list
10-29 01:43:21.962  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-29 01:43:21.962  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:43:21.963  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:21.963  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:21.963  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:43:21.963  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:21.963  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:21.963  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 01:43:21.963  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2884221 removed from the list
,10-29 01:43:21.963  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.963  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 01:43:21.963  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 01:43:21.963  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.963  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.963  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-29 01:43:21.963  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.963  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:21.963  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7ca0d2 added. We now have 3 listener(s)
,10-29 01:43:21.964  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:21.964  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:43:21.965  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 01:43:21.965  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:21.965  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7ca5a3 added. We now have 4 listener(s)
10-29 01:43:21.965  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:43:21.965  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-29 01:43:21.965  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.965  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.965  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.965  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:43:21.966  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-29 01:43:21.968  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:43:21.970  5979  5995 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-29 01:43:21.970  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.972  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:43:21.972  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:21.972  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:21.972  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:21.972  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:21.972  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.972  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:43:21.972  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 01:43:21.973  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:21.973  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 01:43:21.973  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:21.973  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c61459 added. We now have 4 listener(s)
10-29 01:43:21.974  5979  5995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 01:43:21.974  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.974  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:21.975  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:43:21.975  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 01:43:21.975  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:21.975  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5ff81e added. We now have 5 listener(s)
10-29 01:43:21.975  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:43:21.975  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is, advertising: false - Start operation: Should affect listening to advertisements only
10-29 01:43:21.975  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 01:43:21.975  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 01:43:21.975  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:43:21.975  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-29 01:43:21.976  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:21.978  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:21.980  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-29 01:43:21.980  5704  5750 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 01:43:21.980  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-29 01:43:21.980  5979  5995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-29 01:43:21.980  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.980  5979  5998 D BtGatt.ScanManager: stopping BLe Batch
,10-29 01:43:21.984  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.984  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-29 01:43:21.985  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 01:43:21.985  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-29 01:43:21.986  5979  5995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 01:43:21.986  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:21.986  5979  5998 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-29 01:43:21.989  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.989  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 01:43:21.989  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 01:43:21.989  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-29 01:43:21.989  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 01:43:21.990  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:21.991  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:43:21.991  5979  5995 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-29 01:43:21.991  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 01:43:21.993  5979  6015 D BtGatt.GattService: registerClient() - UUID=96651568-276e-4814-9567-c8e579ca28cf
,10-29 01:43:21.994  5979  5995 D BtGatt.GattService: onClientRegistered() - UUID=96651568-276e-4814-9567-c8e579ca28cf, clientIf=5
10-29 01:43:21.994  5704  5715 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-29 01:43:21.994  5979  6020 D BtGatt.GattService: start scan with filters
,10-29 01:43:21.997  5979  5998 D BtGatt.ScanManager: handling starting scan
,10-29 01:43:21.997  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-29 01:43:21.997  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.997  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 01:43:21.997  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:21.997  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-29 01:43:21.997  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 01:43:21.997  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.997  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 01:43:21.997  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 01:43:21.998  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-29 01:43:21.998  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 01:43:21.998  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-29 01:43:21.998  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-29 01:43:21.998  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.000  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.000  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:43:22.000  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.001  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.001  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.002  5979  5995 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-29 01:43:22.002  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:22.002  5979  5998 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-29 01:43:22.003  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:43:22.003  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:43:22.003  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-29 01:43:22.003  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-29 01:43:22.003  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:22.003  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-29 01:43:22.003  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:22.003  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:22.003  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7ca0d2 removed from the list
10-29 01:43:22.003  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:22.004  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7ca5a3 removed from the list
10-29 01:43:22.004  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:43:22.004  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:43:22.004  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:43:22.004  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.004  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-29 01:43:22.004  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:22.004  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.004  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:43:22.004  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.004  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.004  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.004  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 01:43:22.005  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:22.005  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.005  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.005  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:43:22.005  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:43:22.005  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:22.005  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7ca5a3 not in the list
10-29 01:43:22.005  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 01:43:22.005  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 01:43:22.005  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-29 01:43:22.006  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.006  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:22.006  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.006  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 01:43:22.006  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:22.006  5704  5750 D BluetoothAdapter: STATE_ON
10-29 01:43:22.006  5979  5995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 01:43:22.006  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:22.007  5979  5998 D BtGatt.ScanManager: Starting BLE batch scan
10-29 01:43:22.007  5979  6015 D BtGatt.GattService: stopScan() - queue size =1
10-29 01:43:22.007  5979  5998 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-29 01:43:22.007  5979  6020 D BtGatt.GattService: unregisterClient() - clientIf=5
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.008  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-29 01:43:22.008  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 01:43:22.009  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:22.009  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.010  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.010  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:43:22.010  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.010  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.010  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-29 01:43:22.010  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:43:22.010  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:22.010  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:43:22.010  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5ff81e removed from the list
10-29 01:43:22.010  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:43:22.010  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 01:43:22.010  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:22.010  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:22.010  5704  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 01:43:22.011  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:22.011  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.011  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:22.011  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-29 01:43:22.011  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c61459 removed from the list
10-29 01:43:22.011  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 01:43:22.011  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.011  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.011  5704  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 01:43:22.011  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.011  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:22.011  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8f782a added. We now have 3 listener(s)
,10-29 01:43:22.012  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.012  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.012  5704  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.012  5704  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 01:43:22.012  5704  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 01:43:22.013  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:22.013  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:43:22.014  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 01:43:22.014  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:22.014  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2f261b added. We now have 4 listener(s)
10-29 01:43:22.014  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 01:43:22.014  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-29 01:43:22.015  5979  5995 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-29 01:43:22.015  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:22.019  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 01:43:22.021  5979  5995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 01:43:22.021  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 01:43:22.025  5704  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 01:43:22.025  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 01:43:22.025  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 01:43:22.025  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 01:43:22.025  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 01:43:22.025  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 01:43:22.025  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 01:43:22.025  5704  5750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 01:43:22.028  5979  5995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-29 01:43:22.028  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:22.028  5979  5998 D BtGatt.ScanManager: stopping BLe Batch
10-29 01:43:22.028  5704  5750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 01:43:22.028  5704  5750 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-29 01:43:22.028  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 01:43:22.028  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@134f591 added. We now have 4 listener(s)
10-29 01:43:22.029  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 01:43:22.029  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 01:43:22.030  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 01:43:22.030  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 01:43:22.030  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@584ecf6 added. We now have 5 listener(s)
10-29 01:43:22.030  5704  5750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 01:43:22.030  5704  5750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 01:43:22.030  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:43:22.030  5704  5750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 01:43:22.030  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:43:22.030  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:22.030  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 01:43:22.030  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:22.030  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:22.030  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8f782a removed from the list
10-29 01:43:22.030  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 01:43:22.030  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2f261b removed from the list
10-29 01:43:22.031  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:22.031  5704  5750 D io.jxcore.node.ConnectivityMonitor: stop
10-29 01:43:22.032  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:43:22.032  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:43:22.032  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 01:43:22.032  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.032  5979  5995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 01:43:22.033  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:22.033  5979  5998 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-29 01:43:22.034  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:22.034  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.034  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.034  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:43:22.034  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:43:22.034  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:22.034  5704  5750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2f261b not in the list
10-29 01:43:22.034  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 01:43:22.034  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:22.034  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 01:43:22.035  5704  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 01:43:22.036  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.036  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.036  5704  5750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 01:43:22.036  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 01:43:22.036  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 01:43:22.036  5704  5750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 01:43:22.036  5704  5750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@584ecf6 removed from the list
10-29 01:43:22.036  5704  5750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 01:43:22.036  5704  5750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 01:43:22.036  5704  5750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 01:43:22.036  5704  5750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 01:43:22.036  5704  5750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 01:43:22.036  5704  5750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@134f591 removed from the list
10-29 01:43:22.037  5979  5995 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-29 01:43:22.037  5979  5995 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 01:43:22.037  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-29 01:43:22.037  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,10-29 01:43:22.037  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-29 01:43:22.037  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 01:43:22.037  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-29 01:43:22.037  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-29 01:43:22.416  5704  5704 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 01:43:22.466  5704  5704 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 01:43:22.513  5704  5704 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 01:43:24.187  5704  6061 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-29 01:43:24.187  5704  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 01:43:24.996  5704  6061 W !!      : call onHalfStreamCopied
,10-29 01:43:24.997  5704  6061 I testCopyDataAndClose: closing input stream
,10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-29 01:43:25.777  5704  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-29 01:43:29.571  5704  6062 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-29 01:43:29.571  5704  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 01:43:29.596   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:29.637   930  3045 D ConnectivityService: handlePromptUnvalidated 102
,10-29 01:43:30.598   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:31.571  5704  5750 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-29 01:43:31.571  5704  5750 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 01:43:31.571  5704  5750 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-29 01:43:31.598   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:31.707  5704  6062 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-29 01:43:31.707  5704  6062 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-29 01:43:31.707  5704  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,10-29 01:43:31.722  5704  6063 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-29 01:43:31.722  5704  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 01:43:32.599   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:32.691   930  3043 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,10-29 01:43:33.357  5704  6063 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-29 01:43:33.357  5704  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 01:43:33.358  5704  6063 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-29 01:43:33.358  5704  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 01:43:33.358  5704  6063 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-29 01:43:33.358  5704  6063 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-29 01:43:33.358  5704  6063 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-29 01:43:33.358  5704  6063 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-29 01:43:33.358  5704  6063 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-29 01:43:33.358  5704  6063 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-29 01:43:33.358  5704  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-29 01:43:33.601   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:34.602   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-29 01:43:37.101  5704  6064 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-29 01:43:37.101  5704  6064 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 01:43:37.101  5704  6064 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-29 01:43:37.101  5704  6064 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 01:43:37.102  5704  6064 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-29 01:43:37.102  5704  6064 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 01:43:37.102  5704  6064 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-29 01:43:37.102  5704  6064 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-29 01:43:37.102  5704  6064 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-29 01:43:37.102  5704  6064 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-29 01:43:37.102  5704  6064 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-29 01:43:37.103  5704  6064 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-29 01:43:37.103  5704  6064 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-29 01:43:37.104  5704  5750 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-29 01:43:37.108  5704  6065 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-29 01:43:37.108  5704  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 01:43:37.109  5704  6065 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
10-29 01:43:37.109  5704  6065 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-29 01:43:37.109  5704  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-29 01:43:37.110  5704  6065 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-29 01:43:37.110  5704  6065 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-29 01:43:37.110  5704  6065 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-29 01:43:37.114  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-29 01:43:37.114  5704  5750 I jxcore-log: 
,10-29 01:43:37.114  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-29 01:43:37.114  5704  5750 I jxcore-log: 
10-29 01:43:37.115  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-29 01:43:37.115  5704  5750 I jxcore-log: 
10-29 01:43:37.115  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-29 01:43:37.115  5704  5750 I jxcore-log: 
10-29 01:43:37.115  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG UnitTest_app: 'Total duration:  90774'
10-29 01:43:37.115  5704  5750 I jxcore-log: 
,10-29 01:43:37.118  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-29 01:43:37.118  5704  5750 I jxcore-log: 
,10-29 01:43:37.122  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.122  5704  5750 I jxcore-log: 
,10-29 01:43:37.123  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.123  5704  5750 I jxcore-log: 
10-29 01:43:37.123  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.123  5704  5750 I jxcore-log: 
10-29 01:43:37.123  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.123  5704  5750 I jxcore-log: 
10-29 01:43:37.124  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-29 01:43:37.124  5704  5750 I jxcore-log: 
10-29 01:43:37.124  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
10-29 01:43:37.124  5704  5750 I jxcore-log: 
,10-29 01:43:37.124  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 01:43:37.124  5704  5750 I jxcore-log: 
10-29 01:43:37.125  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 01:43:37.125  5704  5750 I jxcore-log: 
,10-29 01:43:37.125  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 01:43:37.125  5704  5750 I jxcore-log: 
,10-29 01:43:37.125  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.125  5704  5750 I jxcore-log: 
,10-29 01:43:37.126  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.126  5704  5750 I jxcore-log: 
10-29 01:43:37.126  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-29 01:43:37.126  5704  5750 I jxcore-log: 
10-29 01:43:37.126  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
10-29 01:43:37.126  5704  5750 I jxcore-log: 
10-29 01:43:37.126  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 01:43:37.126  5704  5750 I jxcore-log: 
,10-29 01:43:37.127  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 01:43:37.127  5704  5750 I jxcore-log: 
10-29 01:43:37.127  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 01:43:37.127  5704  5750 I jxcore-log: 
10-29 01:43:37.127  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 01:43:37.127  5704  5750 I jxcore-log: 
,10-29 01:43:37.127  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 01:43:37.127  5704  5750 I jxcore-log: 
10-29 01:43:37.127  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.127  5704  5750 I jxcore-log: 
10-29 01:43:37.128  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.128  5704  5750 I jxcore-log: 
,10-29 01:43:37.128  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 01:43:37.128  5704  5750 I jxcore-log: 
10-29 01:43:37.128  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 01:43:37.128  5704  5750 I jxcore-log: 
10-29 01:43:37.128  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 01:43:37.128  5704  5750 I jxcore-log: 
10-29 01:43:37.129  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.129  5704  5750 I jxcore-log: 
10-29 01:43:37.130  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.130  5704  5750 I jxcore-log: 
10-29 01:43:37.131  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.131  5704  5750 I jxcore-log: 
10-29 01:43:37.131  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.131  5704  5750 I jxcore-log: 
,10-29 01:43:37.132  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 01:43:37.132  5704  5750 I jxcore-log: 
10-29 01:43:37.132  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 01:43:37.132  5704  5750 I jxcore-log: 
10-29 01:43:37.132  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 01:43:37.132  5704  5750 I jxcore-log: 
10-29 01:43:37.132  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.132  5704  5750 I jxcore-log: 
10-29 01:43:37.133  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.133  5704  5750 I jxcore-log: 
10-29 01:43:37.133  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.133  5704  5750 I jxcore-log: 
10-29 01:43:37.133  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.133  5704  5750 I jxcore-log: 
10-29 01:43:37.133  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.133  5704  5750 I jxcore-log: 
10-29 01:43:37.133  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.133  5704  5750 I jxcore-log: 
,10-29 01:43:37.134  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.134  5704  5750 I jxcore-log: 
10-29 01:43:37.134  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.134  5704  5750 I jxcore-log: 
10-29 01:43:37.134  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.134  5704  5750 I jxcore-log: 
10-29 01:43:37.134  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.134  5704  5750 I jxcore-log: 
10-29 01:43:37.135  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.135  5704  5750 I jxcore-log: 
10-29 01:43:37.135  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.135  5704  5750 I jxcore-log: 
10-29 01:43:37.135  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.135  5704  5750 I jxcore-log: 
,10-29 01:43:37.135  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.135  5704  5750 I jxcore-log: 
10-29 01:43:37.135  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 01:43:37.135  5704  5750 I jxcore-log: 
10-29 01:43:37.136  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-29 01:43:37.136  5704  5750 I jxcore-log: 
10-29 01:43:37.136  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-29 01:43:37.136  5704  5750 I jxcore-log: 
10-29 01:43:37.136  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.136  5704  5750 I jxcore-log: 
10-29 01:43:37.136  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.136  5704  5750 I jxcore-log: 
,10-29 01:43:37.137  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.137  5704  5750 I jxcore-log: 
10-29 01:43:37.137  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.137  5704  5750 I jxcore-log: 
10-29 01:43:37.137  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.137  5704  5750 I jxcore-log: 
10-29 01:43:37.137  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 01:43:37.137  5704  5750 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-29 01:43:37.138  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.138  5704  5750 I jxcore-log: 
,10-29 01:43:37.138  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.138  5704  5750 I jxcore-log: 
10-29 01:43:37.138  5704  5750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 01:43:37.138  5704  5750 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-29 01:43:37.138  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 01:43:37.138  5704  5750 I jxcore-log: 
10-29 01:43:37.139  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 01:43:37.139  5704  5750 I jxcore-log: 
,10-29 01:43:37.139  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 01:43:37.139  5704  5750 I jxcore-log: 
10-29 01:43:37.139  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 01:43:37.139  5704  5750 I jxcore-log: 
10-29 01:43:37.139  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 01:43:37.139  5704  5750 I jxcore-log: 
10-29 01:43:37.139  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 01:43:37.139  5704  5750 I jxcore-log: 
10-29 01:43:37.140  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 01:43:37.140  5704  5750 I jxcore-log: 
10-29 01:43:37.144  5704  5704 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-29 01:43:37.145  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-29 01:43:37.145  5704  5750 I jxcore-log: 
10-29 01:43:37.145  5704  5750 I jxcore-log: 2016-10-29 05:43:37 - WARN testUtils: 'myNameCallback not set!'
10-29 01:43:37.145  5704  5750 I jxcore-log: 
,10-29 01:43:39.246  5704  5750 I jxcore-log: 2016-10-29 05:43:39 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
10-29 01:43:39.246  5704  5750 I jxcore-log: 
,10-29 01:43:39.247  5704  5750 I jxcore-log: 2016-10-29 05:43:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-29 01:43:39.247  5704  5750 I jxcore-log: 
,10-29 01:43:39.596  5704  5750 I jxcore-log: 2016-10-29 05:43:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-29 01:43:39.596  5704  5750 I jxcore-log: 
,10-29 01:43:39.610  5704  5750 I jxcore-log: 2016-10-29 05:43:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-29 01:43:39.610  5704  5750 I jxcore-log: 
,10-29 01:43:40.750  5704  5750 I jxcore-log: 2016-10-29 05:43:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-29 01:43:40.750  5704  5750 I jxcore-log: 
,10-29 01:43:40.941  5704  5750 I jxcore-log: 2016-10-29 05:43:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-29 01:43:40.941  5704  5750 I jxcore-log: 
,10-29 01:43:40.947  5704  5750 I jxcore-log: 2016-10-29 05:43:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-29 01:43:40.947  5704  5750 I jxcore-log: 
,10-29 01:43:40.952  5704  5750 I jxcore-log: 2016-10-29 05:43:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-29 01:43:40.952  5704  5750 I jxcore-log: 
,10-29 01:43:41.443  5704  5750 I jxcore-log: 2016-10-29 05:43:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-29 01:43:41.443  5704  5750 I jxcore-log: 
,10-29 01:43:41.489  5704  5750 I jxcore-log: 2016-10-29 05:43:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-29 01:43:41.489  5704  5750 I jxcore-log: 
,10-29 01:43:41.503  5704  5750 I jxcore-log: 2016-10-29 05:43:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-29 01:43:41.503  5704  5750 I jxcore-log: 
,10-29 01:43:41.507  5704  5750 I jxcore-log: 2016-10-29 05:43:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-29 01:43:41.507  5704  5750 I jxcore-log: 
,10-29 01:43:41.805  5704  5750 I jxcore-log: 2016-10-29 05:43:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-29 01:43:41.805  5704  5750 I jxcore-log: 
,10-29 01:43:41.936  5704  5750 I jxcore-log: 2016-10-29 05:43:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-29 01:43:41.936  5704  5750 I jxcore-log: 
,10-29 01:43:42.312  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-29 01:43:42.312  5704  5750 I jxcore-log: 
,10-29 01:43:42.321  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-29 01:43:42.321  5704  5750 I jxcore-log: 
,10-29 01:43:42.325  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-29 01:43:42.325  5704  5750 I jxcore-log: 
,10-29 01:43:42.330  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-29 01:43:42.330  5704  5750 I jxcore-log: 
,10-29 01:43:42.335  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-29 01:43:42.335  5704  5750 I jxcore-log: 
,10-29 01:43:42.362  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-29 01:43:42.362  5704  5750 I jxcore-log: 
,10-29 01:43:42.399  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-29 01:43:42.399  5704  5750 I jxcore-log: 
,10-29 01:43:42.406  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-29 01:43:42.406  5704  5750 I jxcore-log: 
,10-29 01:43:42.413  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-29 01:43:42.413  5704  5750 I jxcore-log: 
,10-29 01:43:42.428  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-29 01:43:42.428  5704  5750 I jxcore-log: 
,10-29 01:43:42.432  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-29 01:43:42.432  5704  5750 I jxcore-log: 
,10-29 01:43:42.438  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-29 01:43:42.438  5704  5750 I jxcore-log: 
,10-29 01:43:42.443  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-29 01:43:42.443  5704  5750 I jxcore-log: 
,10-29 01:43:42.457  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-29 01:43:42.457  5704  5750 I jxcore-log: 
,10-29 01:43:42.463  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-29 01:43:42.463  5704  5750 I jxcore-log: 
,10-29 01:43:42.485  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-29 01:43:42.485  5704  5750 I jxcore-log: 
,10-29 01:43:42.496  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-29 01:43:42.496  5704  5750 I jxcore-log: 
,10-29 01:43:42.508  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-29 01:43:42.508  5704  5750 I jxcore-log: 
,10-29 01:43:42.518  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-29 01:43:42.518  5704  5750 I jxcore-log: 
,10-29 01:43:42.531  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-29 01:43:42.531  5704  5750 I jxcore-log: 
,10-29 01:43:42.542  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-29 01:43:42.542  5704  5750 I jxcore-log: 
,10-29 01:43:42.549  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-29 01:43:42.549  5704  5750 I jxcore-log: 
,10-29 01:43:42.570  5704  5750 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-29 01:43:42.571  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - INFO testUtils: 'BLE multiple advertisement supported'
10-29 01:43:42.571  5704  5750 I jxcore-log: 
,10-29 01:43:42.754  5704  5750 I jxcore-log: 2016-10-29 05:43:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:42.754  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:42.754  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:42.754  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:42.754  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:42.754  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:42.754  5704  5750 I jxcore-log: 
,10-29 01:43:43.078  5704  5750 I jxcore-log: 2016-10-29 05:43:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:43.078  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:43.078  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:43.078  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:43.078  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:43.078  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:43.078  5704  5750 I jxcore-log: 
,10-29 01:43:43.083  5704  5750 I jxcore-log: 2016-10-29 05:43:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:43.083  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:43.083  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:43.083  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:43.083  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:43.083  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:43.083  5704  5750 I jxcore-log: 
,10-29 01:43:43.718  5704  5750 I jxcore-log: 2016-10-29 05:43:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:43.718  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:43.718  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:43.718  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:43.718  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:43.718  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:43.718  5704  5750 I jxcore-log: 
,10-29 01:43:43.721  5704  5750 I jxcore-log: 2016-10-29 05:43:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:43.721  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:43.721  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:43.721  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:43.721  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:43.721  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:43.721  5704  5750 I jxcore-log: 
,10-29 01:43:44.358  5704  5750 I jxcore-log: 2016-10-29 05:43:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:44.358  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:44.358  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:44.358  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:44.358  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:44.358  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:44.358  5704  5750 I jxcore-log: 
,10-29 01:43:44.364  5704  5750 I jxcore-log: 2016-10-29 05:43:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:44.364  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:44.364  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:44.364  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:44.364  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:44.364  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:44.364  5704  5750 I jxcore-log: 
,10-29 01:43:45.383  5704  5750 I jxcore-log: 2016-10-29 05:43:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:45.383  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:45.383  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:45.383  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:45.383  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:45.383  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:45.383  5704  5750 I jxcore-log: 
,10-29 01:43:45.386  5704  5750 I jxcore-log: 2016-10-29 05:43:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:45.386  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:45.386  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:45.386  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:45.386  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:45.386  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:45.386  5704  5750 I jxcore-log: 
,10-29 01:43:46.430  5704  5750 I jxcore-log: 2016-10-29 05:43:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:46.430  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:46.430  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:46.430  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:46.430  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:46.430  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:46.430  5704  5750 I jxcore-log: 
,10-29 01:43:46.435  5704  5750 I jxcore-log: 2016-10-29 05:43:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:46.435  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:46.435  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:46.435  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:46.435  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:46.435  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:46.435  5704  5750 I jxcore-log: 
,10-29 01:43:47.472  5704  5750 I jxcore-log: 2016-10-29 05:43:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:47.472  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:47.472  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:47.472  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:47.472  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:47.472  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:47.472  5704  5750 I jxcore-log: 
,10-29 01:43:47.477  5704  5750 I jxcore-log: 2016-10-29 05:43:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:47.477  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:47.477  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:47.477  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:47.477  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:47.477  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:47.477  5704  5750 I jxcore-log: 
,10-29 01:43:48.505  5704  5750 I jxcore-log: 2016-10-29 05:43:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:48.505  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:48.505  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:48.505  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:48.505  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:48.505  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:48.505  5704  5750 I jxcore-log: 
,10-29 01:43:48.511  5704  5750 I jxcore-log: 2016-10-29 05:43:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:48.511  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:48.511  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:48.511  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:48.511  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:48.511  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:48.511  5704  5750 I jxcore-log: 
,10-29 01:43:49.545  5704  5750 I jxcore-log: 2016-10-29 05:43:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:49.545  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:49.545  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:49.545  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:49.545  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:49.545  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:49.545  5704  5750 I jxcore-log: 
,10-29 01:43:49.549  5704  5750 I jxcore-log: 2016-10-29 05:43:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:49.549  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:49.549  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:49.549  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:49.549  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:49.549  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:49.549  5704  5750 I jxcore-log: 
,10-29 01:43:49.603   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:50.582  5704  5750 I jxcore-log: 2016-10-29 05:43:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:50.582  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:50.582  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:50.582  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:50.582  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:50.582  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:50.582  5704  5750 I jxcore-log: 
,10-29 01:43:50.586  5704  5750 I jxcore-log: 2016-10-29 05:43:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:50.586  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:50.586  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:50.586  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:50.586  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:50.586  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:50.586  5704  5750 I jxcore-log: 
,10-29 01:43:50.604   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:51.605   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:51.665  5704  5750 I jxcore-log: 2016-10-29 05:43:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:51.665  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:51.665  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:51.665  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:51.665  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:51.665  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:51.665  5704  5750 I jxcore-log: 
,10-29 01:43:51.670  5704  5750 I jxcore-log: 2016-10-29 05:43:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:51.670  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:51.670  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:51.670  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:51.670  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:51.670  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:51.670  5704  5750 I jxcore-log: 
,10-29 01:43:52.607   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:52.698  5704  5750 I jxcore-log: 2016-10-29 05:43:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:52.698  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:52.698  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:52.698  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:52.698  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:52.698  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:52.698  5704  5750 I jxcore-log: 
,10-29 01:43:52.704  5704  5750 I jxcore-log: 2016-10-29 05:43:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:52.704  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:52.704  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:52.704  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:52.704  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:52.704  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:52.704  5704  5750 I jxcore-log: 
,10-29 01:43:53.608   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 01:43:53.741  5704  5750 I jxcore-log: 2016-10-29 05:43:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:53.741  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:53.741  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:53.741  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:53.741  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:53.741  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:53.741  5704  5750 I jxcore-log: 
,10-29 01:43:53.747  5704  5750 I jxcore-log: 2016-10-29 05:43:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:53.747  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:53.747  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:53.747  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:53.747  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:53.747  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:53.747  5704  5750 I jxcore-log: 
,10-29 01:43:54.609   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-29 01:43:54.775  5704  5750 I jxcore-log: 2016-10-29 05:43:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:54.775  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:54.775  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:54.775  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:54.775  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:54.775  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:54.775  5704  5750 I jxcore-log: 
,10-29 01:43:54.782  5704  5750 I jxcore-log: 2016-10-29 05:43:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:54.782  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:54.782  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:54.782  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:54.782  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:54.782  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:54.782  5704  5750 I jxcore-log: 
,10-29 01:43:55.812  5704  5750 I jxcore-log: 2016-10-29 05:43:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:55.812  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:55.812  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:55.812  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:55.812  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:55.812  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:55.812  5704  5750 I jxcore-log: 
,10-29 01:43:55.817  5704  5750 I jxcore-log: 2016-10-29 05:43:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:55.817  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:55.817  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:55.817  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:55.817  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:55.817  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:55.817  5704  5750 I jxcore-log: 
,10-29 01:43:56.845  5704  5750 I jxcore-log: 2016-10-29 05:43:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 01:43:56.845  5704  5750 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 01:43:56.845  5704  5750 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 01:43:56.845  5704  5750 I jxcore-log: emit@events.js:82:1
10-29 01:43:56.845  5704  5750 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 01:43:56.845  5704  5750 I jxcore-log: emit@events.js:82:1'
10-29 01:43:56.845  5704  5750 I jxcore-log: 
,10-29 01:43:56.854  5704  5750 E jxcore  : Error!: error is undefined
10-29 01:43:56.854  5704  5750 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-29 01:43:56.858  5704  5750 I jxcore-log: 2016-10-29 05:43:56 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-29 01:43:56.858  5704  5750 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
10-29 01:43:56.858  5704  5750 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-29 01:43:56.858  5704  5750 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-29 01:43:56.858  5704  5750 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-29 01:43:56.858  5704  5750 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-29 01:43:56.858  5704  5750 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-29 01:43:56.858  5704  5750 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-29 01:43:56.859  5704  5750 I jxcore-log: 2016-10-29 05:43:56 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-29 01:43:56.859  5704  5750 I jxcore-log: 
10-29 01:43:56.861  5704  5750 E jxcore-log: TypeError: 
10-29 01:43:56.861  5704  5750 E jxcore-log: error is undefined
10-29 01:43:56.861  5704  5750 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
10-29 01:43:56.861  5704  5750 E jxcore-log: 
,10-29 01:43:56.964   930  4853 D GraphicsStats: Buffer count: 2
,10-29 01:43:56.964   930  3229 I WindowState: WIN DEATH: Window{db5e95 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-29 01:43:56.964   930  3044 D WifiService: Client connection lost with reason: 4
,10-29 01:43:56.975   527   527 I Zygote  : Process 5704 exited cleanly (139)
,10-29 01:43:56.980   930  3896 I ActivityManager: Process com.test.thalitest (pid 5704) has died
,10-29 01:43:56.998   930  3896 I ActivityManager: Start proc 6068:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-29 01:43:57.320   930  3900 I WindowManager: Screenshot max retries 4 of Token{751449f ActivityRecord{26cae3e u0 com.test.thalitest/.MainActivity t2}} appWin=Window{25df488 u0 Starting com.test.thalitest} drawState=4
,10-29 01:43:57.411  6068  6068 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-29 01:43:57.429  6068  6068 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-29 01:43:57.429  6066  6066 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-29 01:43:57.434  6068  6068 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2280-2281)
,10-29 01:43:57.434  6068  6068 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-29 01:43:57.444  6068  6068 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ef3731f}
,10-29 01:43:57.444  6068  6068 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-29 01:43:57.444  6068  6068 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-29 01:43:57.445  6066  6066 D AndroidRuntime: CheckJNI is OFF
,10-29 01:43:57.448  6068  6068 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-29 01:43:57.449  6068  6068 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-29 01:43:57.459  6068  6068 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-29 01:43:57.467  6068  6068 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-29 01:43:57.467  6068  6068 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-29 01:43:57.467  6068  6068 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-29 01:43:57.467  6068  6068 I Adreno  : Build Date                       : 12/06/15
10-29 01:43:57.467  6068  6068 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-29 01:43:57.467  6068  6068 I Adreno  : Local Branch                     : mybranch17112971
10-29 01:43:57.467  6068  6068 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-29 01:43:57.467  6068  6068 I Adreno  : Remote Branch                    : NONE
10-29 01:43:57.467  6068  6068 I Adreno  : Reconstruct Branch               : NOTHING
,10-29 01:43:57.468  6066  6066 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-29 01:43:57.493  6066  6066 I Radio-JNI: register_android_hardware_Radio DONE
,10-29 01:43:57.498   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4441059:true
,10-29 01:43:57.510  6066  6066 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-29 01:43:57.511   404   404 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[36187]" dev="sockfs" ino=36187 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-29 01:43:57.511   404   404 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[36187]" dev="sockfs" ino=36187 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-29 01:43:57.518   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-29 01:43:57.518   930   943 I ActivityManager: Killing 6068:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-29 01:43:57.626   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-29 01:43:57.627   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-29 01:43:57.628   930   943 E ActivityManager: Failure starting process com.test.thalitest
10-29 01:43:57.628   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-29 01:43:57.628   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:43:57.628   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:43:57.628   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 01:43:57.628   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-29 01:43:57.630   930   943 I ActivityManager:   Force finishing activity ActivityRecord{26cae3e u0 com.test.thalitest/.MainActivity t2}
,10-29 01:43:57.632   930   953 I art     : Starting a blocking GC Explicit
,10-29 01:43:57.650   930   948 W WindowManager: Failed looking up window
10-29 01:43:57.650   930   948 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@149f82b does not exist
10-29 01:43:57.650   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-29 01:43:57.650   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-29 01:43:57.650   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-29 01:43:57.650   930   948 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-29 01:43:57.650   930   948 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-29 01:43:57.650   930   948 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-29 01:43:57.650   930   948 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-29 01:43:57.650   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:43:57.650   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:43:57.650   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 01:43:57.650   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-29 01:43:57.651   930  3661 W ActivityManager: Spurious death for ProcessRecord{775ef64 0:com.test.thalitest/u0a77}, curProc for 6068: null
,10-29 01:43:57.728   930   953 I art     : Explicit concurrent mark sweep GC freed 56420(3MB) AllocSpace objects, 16(576KB) LOS objects, 33% free, 29MB/43MB, paused 1.657ms total 95.481ms
,10-29 01:43:57.749   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-29 01:43:57.753  6066  6066 I art     : System.exit called, status: 0
10-29 01:43:57.753  6066  6066 I AndroidRuntime: VM exiting with result code 0.
,10-29 01:43:57.765   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-29 01:43:57.769   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-29 01:43:57.779  5979  5979 D BluetoothMapAppObserver: onReceive
10-29 01:43:57.779  5979  5979 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-29 01:43:57.787  3723  3723 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-29 01:43:57.788   930  3009 I InputReader: Reconfiguring input devices.  changes=0x00000010
10-29 01:43:57.790  4138  4251 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-29 01:43:57.809  3723  6109 I Keyboard.Facilitator.DecoderInitializer: run()
,10-29 01:43:57.834   212   212 W kworker/3:2: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-29 01:43:57.841  3858  3858 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-29 01:43:57.847  3723  6109 I Decoder : createOrResetDecoder
,10-29 01:43:57.851  3645  3645 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,10-29 01:43:57.837   212   212 W kworker/3:2: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-29 01:43:57.851  3645  3645 D AndroidRuntime: Shutting down VM
--------- beginning of crash
10-29 01:43:57.852  3645  3645 E AndroidRuntime: FATAL EXCEPTION: main
10-29 01:43:57.852  3645  3645 E AndroidRuntime: Process: com.google.process.gapps, PID: 3645
10-29 01:43:57.852  3645  3645 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-29 01:43:57.852  3645  3645 E AndroidRuntime: 	... 8 more
,10-29 01:43:57.857   212   212 W kworker/3:2: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-29 01:43:57.860  3645  3645 I Process : Sending signal. PID: 3645 SIG: 9
10-29 01:43:57.862   930   943 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2708)
10-29 01:43:57.863   930   943 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
10-29 01:43:57.863   930   943 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 01:43:57.863   930   943 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-29 01:43:57.872  3461  6112 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-29 01:43:57.875   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-29 01:43:57.877  3461  3485 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
10-29 01:43:57.877  3461  3485 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjFE35B6920) - 
10-29 01:43:57.878  3461  3485 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-29 01:43:57.878  3461  3485 E AndroidRuntime: Process: android.process.acore, PID: 3461
10-29 01:43:57.878  3461  3485 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:43:57.878  3461  3485 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-29 01:43:57.891   930  3044 D WifiService: Client connection lost with reason: 4
,10-29 01:43:57.895   930   943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 1000ms
10-29 01:43:57.895   930   943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
,10-29 01:43:57.895   930   943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,10-29 01:43:57.907   930   943 I ActivityManager: Start proc 6116:com.google.process.gapps/u0a12 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,10-29 01:43:57.909  3908  4030 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
10-29 01:43:57.909   930   942 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
10-29 01:43:57.910   930  3896 W ActivityManager: Spurious death for ProcessRecord{fc2431d 6116:com.google.process.gapps/u0a12}, curProc for 3645: null
,10-29 01:43:57.911   930   942 E PackageManager: Failed to write settings, restoring backup
10-29 01:43:57.911   930   942 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-29 01:43:57.911   930   942 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-29 01:43:57.911   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-29 01:43:57.911   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-29 01:43:57.911   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-29 01:43:57.911   930   942 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 01:43:57.911   930   942 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:43:57.911   930   942 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-29 01:43:57.912  3461  6112 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-29 01:43:57.912  3461  6112 I Process : Sending signal. PID: 3461 SIG: 9
10-29 01:43:57.916   930   943 E DropBoxManagerService: Can't write: system_server_wtf
10-29 01:43:57.916   930   943 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-29 01:43:57.916   930   943 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-29 01:43:57.916   930   943 E DropBoxManagerService: 	... 13 more
10-29 01:43:57.917   930  6126 E DropBoxManagerService: Can't write: system_app_crash
10-29 01:43:57.917   930  6126 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:43,8)
10-29 01:43:57.917   930  6126 E DropBoxManagerService: 	... 5 more
10-29 01:43:57.927   930  3661 I ActivityManager: Start proc 6129:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
10-29 01:43:57.927   379   379 E lowmemorykiller: Error writing /proc/3461/oom_score_adj; errno=22
10-29 01:43:57.927  3908  4030 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-29 01:43:57.927  3908  4030 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3908
10-29 01:43:57.927  3908  4030 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-29 01:43:57.927  3908  4030 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: Can't write: system_app_crash
10-29 01:43:57.938   930  6140 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-29 01:43:57.938   930  6140 E DropBoxManagerService: 	... 5 more
10-29 01:43:57.941   930   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-29 01:43:57.944  3908  4030 I Process : Sending signal. PID: 3908 SIG: 9
,10-29 01:43:57.981   930  3008 W InputDispatcher: channel '5d57767 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-29 01:43:57.981   930  3008 E InputDispatcher: channel '5d57767 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
10-29 01:43:57.981   930  3900 I WindowState: WIN DEATH: Window{5d57767 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
10-29 01:43:57.981   930  3950 D GraphicsStats: Buffer count: 1
10-29 01:43:57.981   930  3900 W InputDispatcher: Attempted to unregister already unregistered input channel '5d57767 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-29 01:43:57.997   930  3474 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3908) has died
,10-29 01:43:57.997   930  3474 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-29 01:43:57.999   930  3474 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
10-29 01:43:58.002   930  3474 W WindowManager: On display=0 Rebuild removed 1 windows but added 0
10-29 01:43:58.002   930  3474 W WindowManager: java.lang.RuntimeException: here
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.wm.WindowManagerService.rebuildAppWindowListLocked(WindowManagerService.java:8817)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.wm.WindowManagerService.moveStackWindowsLocked(WindowManagerService.java:5049)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.wm.WindowManagerService.moveTaskToTop(WindowManagerService.java:5115)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStack.moveToFront(ActivityStack.java:508)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStackSupervisor.setFocusedStack(ActivityStackSupervisor.java:1824)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityManagerService.setFocusedActivityLocked(ActivityManagerService.java:2688)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLocked(ActivityStackSupervisor.java:2462)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStackSupervisor.startActivityLocked(ActivityStackSupervisor.java:1675)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStackSupervisor.startHomeActivity(ActivityStackSupervisor.java:910)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityManagerService.startHomeActivityLocked(ActivityManagerService.java:3507)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStackSupervisor.resumeHomeStackTask(ActivityStackSupervisor.java:518)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1608)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4736)
10-29 01:43:58.002   930  3474 W WindowManager: 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1330)
10-29 01:43:58.002   930  3474 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:558)
10-29 01:43:58.003   930  3474 E WindowState: getStack: Window{5d57767 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{97888f token=Token{3f2cbee ActivityRecord{f739569 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.dump:1579 com.android.server.wm.WindowManagerService.rebuildAppWindowListLocked:8823 com.android.server.wm.WindowManagerService.moveStackWindowsLocked:5049 com.android.server.wm.WindowManagerService.moveTaskToTop:5115 
10-29 01:43:58.004   930  3474 E WindowState: getStack: Window{5d57767 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{97888f token=Token{3f2cbee ActivityRecord{f739569 u0 com.google.an,droid.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowState.dump:1580 com.android.server.wm.WindowManagerService.rebuildAppWindowListLocked:8823 
10-29 01:43:58.006   930  3474 W WindowManager: This window was lost: Window{5d57767 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
10-29 01:43:58.006   930  3474 W WindowManager: mDisplayId=0 stackId=0 mSession=Session{737ce68 3908:u0a10029} mClient=android.os.BinderProxy@9ba4f26
10-29 01:43:58.006   930  3474 W WindowManager: mOwnerUid=10029 mShowToOwnerOnly=true package=com.google.android.googlequicksearchbox appop=NONE
10-29 01:43:58.006   930  3474 W WindowManager: mAttrs=WM.LayoutParams{(0,0)(fillxfill) sim=#120 ty=1 fl=#81910100 fmt=-3 wanim=0x103045b vsysui=0x600 needsMenuKey=2}
10-29 01:43:58.006   930  3474 W WindowManager: Requested w=1440 h=2560 mLayoutSeq=41
10-29 01:43:58.006   930  3474 W WindowManager: mBaseLayer=21000 mSubLayer=0 mAnimLayer=21000+0=21000 mLastLayer=0
10-29 01:43:58.006   930  3474 W WindowManager: mToken=AppWindowToken{97888f token=Token{3f2cbee ActivityRecord{f739569 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}}
10-29 01:43:58.006   930  3474 W WindowManager: mRootToken=AppWindowToken{97888f token=Token{3f2cbee ActivityRecord{f739569 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}}
10-29 01:43:58.006   930  3474 W WindowManager: mAppToken=AppWindowToken{97888f token=Token{3f2cbee ActivityRecord{f739569 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}}
10-29 01:43:58.006   930  3474 W WindowManager: mViewVisibility=0x4 mHaveFrame=true mObscured=true
10-29 01:43:58.006   930  3474 W WindowManager: mSeq=0 mSystemUiVisibility=0x600
10-29 01:43:58.006   930  3474 W WindowManager: mPolicyVisibility=false mPolicyVisibilityAfterAnim=false mAppOpVisibility=true mAttachedHidden=false
10-29 01:43:58.006   930  3474 W WindowManager: mGivenContentInsets=[0,0][0,0] mGivenVisibleInsets=[0,0][0,0]
10-29 01:43:58.006   930  3474 W WindowManager: mConfiguration={1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h659dp 560dpi nrml port finger -keyb/v/h -nav/h s.5}
10-29 01:43:58.006   930  3474 W WindowManager: mHasSurface=true mShownFrame=[0.0,0.0][1440.0,2560.0] isReadyForDisplay()=false
10-29 01:43:58.006   930  3474 W WindowManager: mFrame=[0,0][1440,2560] last=[0,0][1440,2560]
10-29 01:43:58.006   930  3474 W WindowManager: mSystemDecorRect=[0,0][1440,2560] last=[0,0][0,0]
10-29 01:43:58.006   930  3474 W WindowManager: Frames: containing=[0,0][1440,2560] parent=[0,0][1440,2560]
10-29 01:43:58.006   930  3474 W WindowManager:     display=[0,0][1440,2560] overscan=[0,0][1440,2560]
10-29 01:43:58.006   930  3474 W WindowManager:     content=[0,84][1440,2392] visible=[0,84][1440,2392]
10-29 01:43:58.006   930  3474 W WindowManager:     decor=[0,0][1440,2560]
10-29 01:43:58.006   930  3474 W WindowManager:     outset=[0,0][0,0]
10-29 01:43:58.006   930  3474 W WindowManager: Cur insets: overscan=[0,0][0,0] content=[0,84][0,168] visible=[0,84][0,168] stable=[0,84][0,168] outsets=[0,0][0,0]
10-29 01:43:58.006   930  3474 W WindowManager: Lst insets: overscan=[0,0][0,0] content=[0,84][0,168] visible=[0,84][0,168] stable=[0,84][0,168] physical=[0,0][0,0] outset=[0,0][0,0]
10-29 01:43:58.006   930  3474 W WindowManager: WindowStateAnimator{c00cfbc com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}:
10-29 01:43:58.006   930  3474 W WindowManager:   mSurface=Surface(name=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL)
10-29 01:43:58.006   930  3474 W WindowManager:   mDrawState=HAS_DRAWN mLastHidden=true
10-29 01:43:58.006   930  3474 W WindowManager:   Surface: shown=false layer=21005 alpha=0.0 rect=(0.0,0.0) 1440.0 x 2560.0
10-29 01:43:58.006   930  3474 W WindowManager:   mShownAlpha=1.0 mAlpha=1.0 mLastAlpha=-1.0
10-29 01:43:58.006   930  3474 W WindowManager: mExiting=true mRemoveOnExit=true mDestroying=false mRemoved=false
10-29 01:43:58.006   930  3474 W WindowManager: mWallpaperX=0.0 mWallpaperY=0.5
10-29 01:43:58.006   930  3474 W WindowManager: Current app token list:
10-29 01:43:58.007   930  3474 V WindowManager:   Stack #0 tasks from bottom to top:
10-29 01:43:58.007   930  3474 V WindowManager:     Task #3 activities from bottom to top:
10-29 01:43:58.007   930  3474 V WindowManager:       activity #0: Token{51a1b8e ActivityRecord{4addf89 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t3}}
10-29 01:43:58.007   930  3474 W WindowManager: Final window list:
10-29 01:43:58.007   930  3474 V WindowManager:  Display #0
10-29 01:43:58.007   930  3474 V WindowManager:   #4: Window{9c6cdf5 u0 NavigationBar}
10-29 01:43:58.007   930  3474 V WindowManager:   #3: Window{93081e7 u0 StatusBar}
10-29 01:43:58.007   930  3474 V WindowManager:   #2: Window{f1b6892 u0 KeyguardScrim}
10-29 01:43:58.007   930  3474 V WindowManager:   #1: Window{ffa3b33 u0 com.android.systemui.ImageWallpaper}
10-29 01:43:58.007   930  3474 V WindowManager:   #0: Window{af1c6df u0 AssistPreviewPanel}
10-29 01:43:58.016   930  3900 I ActivityManager: Process android.process.acore (pid 3461) has died
10-29 01:43:58.016   930  3900 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
10-29 01:43:58.028   930   943 I ActivityManager: Start proc 6142:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-29 01:43:58.249   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
