#### Test 9137166157d7cd0_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-28 08:37:49.027  5493  5540 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
10-28 08:37:49.065  3995  3995 I ConfigFetchService: fetch service done; releasing wakelock
10-28 08:37:49.067  3995  3995 I ConfigFetchService: stopping self
10-28 08:37:49.089  5493  5540 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
10-28 08:37:49.112  3995  4898 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
10-28 08:37:49.189  3995  4898 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
10-28 08:37:49.208  5493  5540 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,10-28 08:37:51.632  5551  5551 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-28 08:37:51.637  5551  5551 D AndroidRuntime: CheckJNI is OFF
10-28 08:37:51.665  5551  5551 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-28 08:37:51.702  5551  5551 I Radio-JNI: register_android_hardware_Radio DONE
10-28 08:37:51.719  5551  5551 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-28 08:37:51.725   930  3728 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-28 08:37:51.771   930  3728 I ActivityManager: Start proc 5560:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-28 08:37:51.790  5551  5551 D AndroidRuntime: Shutting down VM
,10-28 08:37:52.107   930  3541 I WindowManager: Screenshot max retries 4 of Token{8984940 ActivityRecord{b0a4cc3 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{3a6913b u0 Starting com.test.thalitest} drawState=2
,10-28 08:37:52.186  5560  5560 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-28 08:37:52.209  5560  5560 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-28 08:37:52.279  5560  5560 I LibraryLoader: Time to load native libraries: 67 ms (timestamps 5782-5849)
10-28 08:37:52.280  5560  5560 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-28 08:37:52.307  5560  5560 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {318eeee}
,10-28 08:37:52.307  5560  5560 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-28 08:37:52.307  5560  5560 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-28 08:37:52.311  5560  5560 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-28 08:37:52.312  5560  5560 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-28 08:37:52.364  5560  5560 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-28 08:37:52.375  5560  5560 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-28 08:37:52.375  5560  5560 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-28 08:37:52.375  5560  5560 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-28 08:37:52.375  5560  5560 I Adreno  : Build Date                       : 12/06/15
10-28 08:37:52.375  5560  5560 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-28 08:37:52.375  5560  5560 I Adreno  : Local Branch                     : mybranch17112971
10-28 08:37:52.375  5560  5560 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-28 08:37:52.375  5560  5560 I Adreno  : Remote Branch                    : NONE
10-28 08:37:52.375  5560  5560 I Adreno  : Reconstruct Branch               : NOTHING
,10-28 08:37:52.414   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d8f66e:true
,10-28 08:37:52.431   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14211]" dev="sockfs" ino=14211 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 08:37:52.431   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[14211]" dev="sockfs" ino=14211 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 08:37:52.445  5560  5560 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-28 08:37:52.453  5560  5560 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-28 08:37:52.478   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32845]" dev="sockfs" ino=32845 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-28 08:37:52.478   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32845]" dev="sockfs" ino=32845 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-28 08:37:52.483  5560  5597 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-28 08:37:52.481  3728  3728 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14223]" dev="sockfs" ino=14223 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-28 08:37:52.481  3728  3728 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14223]" dev="sockfs" ino=14223 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-28 08:37:52.489  5560  5584 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-28 08:37:52.524  5560  5597 I OpenGLRenderer: Initialized EGL, version 1.4
,10-28 08:37:52.601   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +490ms (total +859ms)
,10-28 08:37:52.625  5560  5560 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5560
,10-28 08:37:52.686  5560  5560 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-28 08:37:52.823  5560  5600 D jxcore_app_log: JniHelper::setJavaVM(0xf543c000), pthread_self() = -583263952
,10-28 08:37:52.826  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-28 08:37:52.826  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-28 08:37:52.826  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-28 08:37:52.826  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-28 08:37:52.826  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-28 08:37:52.826  5560  5600 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0cd47 added. We now have 1 listener(s)
,10-28 08:37:52.829  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-28 08:37:52.829  5560  5600 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:37:52.830  5560  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:37:52.830  5560  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-28 08:37:52.833  5560  5600 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b206f12 added. We now have 1 listener(s)
10-28 08:37:52.833  5560  5600 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 08:37:52.837   930  2908 D WifiService: New client listening to asynchronous messages
10-28 08:37:52.837  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 08:37:52.837  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-28 08:37:52.837  5560  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
10-28 08:37:52.837  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-28 08:37:52.837  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-28 08:37:52.837  5560  5600 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-28 08:37:52.838  5560  5600 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,10-28 08:37:52.839  5560  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:37:52.839  5560  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-28 08:37:52.843  5560  5600 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-28 08:37:52.844  5560  5600 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:37:52.844  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:37:52.844  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:37:52.844  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:37:52.844  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:37:52.844  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:37:52.844  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:37:52.844  5560  5600 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:37:52.844  5560  5600 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-28 08:37:52.844  5560  5600 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:37:52.844  5560  5600 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-28 08:37:52.846  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:37:52.849  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:37:52.861  5560  5560 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-28 08:37:53.641  5560  5606 W jxcore-log: Initializing JXcore engine
,10-28 08:37:53.641  5560  5606 W jxcore-log: JXcore engine is ready
,10-28 08:37:53.661  5606  5606 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1169 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-28 08:37:53.661  5606  5606 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13536]" dev="sockfs" ino=13536 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-28 08:37:53.661  5606  5606 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=6259 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-28 08:37:53.661  5606  5606 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32822]" dev="sockfs" ino=32822 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-28 08:37:53.673  5560  5606 W jxcore-log: Starting JXcore engine
,10-28 08:37:53.723  5560  5606 W jxcore-log: Platform android
10-28 08:37:53.723  5560  5606 W jxcore-log: 
,10-28 08:37:53.723  5560  5606 W jxcore-log: Process ARCH arm
10-28 08:37:53.723  5560  5606 W jxcore-log: 
,10-28 08:37:53.909  5560  5606 I jxcore-log: JXcore Cordova bridge is ready!
10-28 08:37:53.909  5560  5606 I jxcore-log: 
,10-28 08:37:53.909  5560  5606 W jxcore-log: JXcore engine is started
,10-28 08:37:53.924  5560  5600 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-28 08:37:53.931  5560  5560 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-28 08:37:54.075  3527  3527 I ConfigService: onDestroy
,10-28 08:38:00.798   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:01.799   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:02.542  3527  5612 I VacuumService: Vacuum at: now=1477658282542 tag=VacuumService
,10-28 08:38:02.565  3527  5615 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-28 08:38:02.610  3527  5613 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-28 08:38:02.612  3527  5613 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-28 08:38:02.634  4785  4822 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-28 08:38:02.635  4785  4785 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-28 08:38:02.642  3527  5613 W Uploader:  no longer exists, so no auth token.
,10-28 08:38:02.647  3527  5615 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 08:38:02.801   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:03.054  3527  5617 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 08:38:03.109  3527  5613 W Uploader:  no longer exists, so no auth token.
,10-28 08:38:03.117  3527  5615 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 08:38:03.196  3527  5617 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-28 08:38:03.775  5560  5606 I jxcore-log: 2016-10-28 12:38:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-28 08:38:03.775  5560  5606 I jxcore-log: 
,10-28 08:38:03.777  5560  5606 I jxcore-log: 2016-10-28 12:38:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-28 08:38:03.777  5560  5606 I jxcore-log: 
,10-28 08:38:03.782  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:38:03.782  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:03.782  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:03.782  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:03.782  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:38:03.782  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:03.782  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:03.782  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:38:03.783  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 08:38:03.784  5560  5606 I jxcore-log: 2016-10-28 12:38:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-28 08:38:03.784  5560  5606 I jxcore-log: 
,10-28 08:38:03.785  5560  5606 I jxcore-log: 2016-10-28 12:38:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-28 08:38:03.785  5560  5606 I jxcore-log: 
,10-28 08:38:03.801   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:04.039  5560  5606 I jxcore-log: 2016-10-28 12:38:04 - DEBUG UnitTest_app: 'Running unit tests'
10-28 08:38:04.039  5560  5606 I jxcore-log: 
,10-28 08:38:04.039  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:38:04.040  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b0718d added. We now have 2 listener(s)
,10-28 08:38:04.040  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:38:04.041  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:38:04.041  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:38:04.041  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:38:04.041  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c77f42 added. We now have 2 listener(s)
10-28 08:38:04.041  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 08:38:04.041  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 08:38:04.043  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 08:38:04.046  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:38:04.046  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:04.046  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:04.046  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:04.046  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:38:04.046  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:04.046  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:04.046  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:04.047  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 08:38:04.048  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:38:04.048  5560  5606 D executeNativeTests: Running unit tests
,10-28 08:38:04.054  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:04.060  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:04.087  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:38:04.087  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 added. We now have 3 listener(s)
,10-28 08:38:04.088  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-28 08:38:04.088  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:38:04.088  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-28 08:38:04.088  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:38:04.088  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 added. We now have 3 listener(s)
10-28 08:38:04.088  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:38:04.089  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 08:38:04.090  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 08:38:04.092  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:38:04.092  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:04.092  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:04.092  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:04.092  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:38:04.092  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:04.092  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:04.092  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:04.093  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 08:38:04.093  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-28 08:38:04.094  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-28 08:38:04.094  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-28 08:38:04.094  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-28 08:38:04.094  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 08:38:04.095  5560  5606 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-28 08:38:04.095  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-28 08:38:04.095  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-28 08:38:04.095  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 08:38:04.095  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 08:38:04.095  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 08:38:04.096  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 08:38:04.096  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:04.096  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:04.096  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:04.096  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:04.096  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:38:04.096  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:04.096  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:38:04.096  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 removed from the list
10-28 08:38:04.096  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:04.096  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 removed from the list
10-28 08:38:04.097  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:04.102  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:04.102  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:04.102  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:04.103  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:04.103  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:04.103  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.103  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.103  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.103  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.103  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:04.103  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:04.103  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:04.104  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:04.104  5560  5606 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-28 08:38:04.105  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:04.105  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:04.105  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:04.105  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:04.105  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:04.105  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:04.105  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:04.105  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:04.105  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:04.105  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:04.105  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:04.105  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:04.105  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:04.105  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:04.105  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:04.105  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.106  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.106  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.106  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.106  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:04.106  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:04.106  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:04.106  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-28 08:38:04.108  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-28 08:38:04.109  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-28 08:38:04.109  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:04.109  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:04.109  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:04.109  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:04.109  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:04.109  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:04.109  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:04.109  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:04.109  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:04.110  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:04.110  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:04.110  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:04.110  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:04.110  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:04.110  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:04.110  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.110  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.110  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.110  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.110  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:04.111  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:04.111  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:04.111  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:04.111  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-28 08:38:04.112  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:38:04.114  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:38:04.114  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:04.114  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:04.114  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:04.114  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:38:04.114  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:04.114  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:04.114  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:04.115  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:04.115  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:38:04.115  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:38:04.115  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 08:38:04.115  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 08:38:04.115  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:38:04.115  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 08:38:04.117  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 08:38:04.117  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 08:38:04.117  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 08:38:04.119  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:04.121  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.121  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:04.121  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-28 08:38:04.121  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-28 08:38:04.122  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-28 08:38:04.123  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-28 08:38:04.124  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-28 08:38:04.124  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.124  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 08:38:04.124  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 08:38:04.124  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 08:38:04.124  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-28 08:38:04.125  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.125  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:38:04.127  4554  4566 D BtGatt.GattService: registerClient() - UUID=b494bc27-db75-46a3-9a07-62b9fa41a4aa
10-28 08:38:04.128  4554  4616 D BtGatt.GattService: onClientRegistered() - UUID=b494bc27-db75-46a3-9a07-62b9fa41a4aa, clientIf=5
10-28 08:38:04.128  5560  5571 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-28 08:38:04.129  4554  4567 D BtGatt.GattService: start scan with filters
10-28 08:38:04.133  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-28 08:38:04.134  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.134  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 08:38:04.134  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.134  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 08:38:04.134  4554  4619 D BtGatt.ScanManager: handling starting scan
10-28 08:38:04.134  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 08:38:04.135  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 08:38:04.135  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:38:04.135  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.135  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 08:38:04.135  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 08:38:04.135  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:38:04.135  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 08:38:04.135  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-28 08:38:04.135  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.135  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.135  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:04.135  4554  4619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:38:04.135  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:38:04.136  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
10-28 08:38:04.138  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:38:04.138  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:38:04.138  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:04.138  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:04.138  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:38:04.139  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:38:04.143  4554  4616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-28 08:38:04.143  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:04.143  4554  4619 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-28 08:38:04.148  4554  4616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 08:38:04.148  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:04.149  4554  4619 D BtGatt.ScanManager: Starting BLE batch scan
10-28 08:38:04.149  4554  4619 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-28 08:38:04.159  4554  4616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 08:38:04.159  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:04.165  4554  4616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 08:38:04.165  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:38:04.640  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-28 08:38:04.641  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:38:04.641  5560  5560 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-28 08:38:04.803   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:05.803   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-28 08:38:09.140  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 08:38:09.140  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-28 08:38:09.140  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-28 08:38:09.140  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:38:09.140  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-28 08:38:09.141  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:09.141  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-28 08:38:09.141  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 08:38:09.141  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 08:38:09.141  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 08:38:09.142  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.142  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:09.142  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.142  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 08:38:09.143  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.144  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:38:09.145  4554  4800 D BtGatt.GattService: stopScan() - queue size =1
10-28 08:38:09.146  4554  4566 D BtGatt.GattService: unregisterClient() - clientIf=5
10-28 08:38:09.147  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 08:38:09.148  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.148  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 08:38:09.148  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.148  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:09.149  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.149  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.150  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 08:38:09.150  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.150  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.151  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.151  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 08:38:09.151  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 08:38:09.153  4554  4554 D BtGatt.ScanManager: awakened up at time 172722
10-28 08:38:09.153  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-28 08:38:09.154  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.156  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.156  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:38:09.156  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.156  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:09.157  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:09.157  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:09.157  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:38:09.157  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:09.157  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:09.157  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:38:09.158  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:09.158  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:09.158  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:38:09.158  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:09.158  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:09.158  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 08:38:09.158  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:38:09.158  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 08:38:09.159  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 08:38:09.159  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-28 08:38:09.159  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 08:38:09.159  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 08:38:09.160  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:38:09.164  4554  4616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 08:38:09.164  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:09.165  4554  4619 D BtGatt.ScanManager: stopping BLe Batch
10-28 08:38:09.165  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:38:09.165  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:09.165  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:09.165  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:38:09.165  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-28 08:38:09.176  4554  4616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-28 08:38:09.176  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:09.176  4554  4619 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-28 08:38:09.197  4554  4616 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-28 08:38:09.198  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:09.198  4554  4616 D BtGatt.GattService: current time is 172767792189
10-28 08:38:09.198  4554  4616 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -88, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -86, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -81, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -81, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -79, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-28 08:38:09.200  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-28 08:38:09.201  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-28 08:38:09.202  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-28 08:38:09.202  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-28 08:38:09.202  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-28 08:38:09.202  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-28 08:38:09.666  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 08:38:14.160  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-28 08:38:14.165  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 08:38:14.176  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:38:14.176  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:14.176  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:14.176  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:14.176  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:38:14.176  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:14.176  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:14.176  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:38:14.181  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 08:38:14.182  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:38:14.182  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:38:14.182  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 08:38:14.182  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-28 08:38:14.182  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:38:14.182  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 08:38:14.187  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:14.193  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:14.194  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-28 08:38:14.194  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 08:38:14.194  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-28 08:38:14.202  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.203  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-28 08:38:14.204  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-28 08:38:14.204  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-28 08:38:14.210  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.211  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-28 08:38:14.211  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-28 08:38:14.211  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-28 08:38:14.211  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-28 08:38:14.211  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.212  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:38:14.216  4554  4799 D BtGatt.GattService: registerClient() - UUID=ea9b7ce7-016b-4b32-a8f6-aba6ec3e53fb
10-28 08:38:14.217  4554  4616 D BtGatt.GattService: onClientRegistered() - UUID=ea9b7ce7-016b-4b32-a8f6-aba6ec3e53fb, clientIf=5
,10-28 08:38:14.217  5560  5571 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-28 08:38:14.218  4554  4566 D BtGatt.GattService: start scan with filters
10-28 08:38:14.222  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-28 08:38:14.223  4554  4619 D BtGatt.ScanManager: handling starting scan
10-28 08:38:14.223  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.223  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-28 08:38:14.223  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.223  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 08:38:14.223  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 08:38:14.223  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.224  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 08:38:14.224  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 08:38:14.224  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.224  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.224  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-28 08:38:14.226  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-28 08:38:14.226  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.230  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.230  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:38:14.231  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.231  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.231  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
10-28 08:38:14.231  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-28 08:38:14.233  4554  4616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 08:38:14.233  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:14.234  4554  4619 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-28 08:38:14.235  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:14.235  5560  5606 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-28 08:38:14.235  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:14.235  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-28 08:38:14.236  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:14.236  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-28 08:38:14.236  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:14.236  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-28 08:38:14.238  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.238  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.238  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.238  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 08:38:14.238  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.238  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-28 08:38:14.238  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 08:38:14.238  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:38:14.238  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.239  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.239  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.239  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 08:38:14.239  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.240  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:38:14.242  4554  4779 D BtGatt.GattService: stopScan() - queue size =1
,10-28 08:38:14.243  4554  4616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 08:38:14.243  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:14.244  4554  4799 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-28 08:38:14.244  4554  4619 D BtGatt.ScanManager: Starting BLE batch scan
10-28 08:38:14.244  4554  4619 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-28 08:38:14.244  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 08:38:14.244  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.244  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 08:38:14.244  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.244  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.244  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.245  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.245  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 08:38:14.245  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.245  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.245  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.245  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 08:38:14.245  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 08:38:14.246  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:38:14.246  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.248  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.248  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:38:14.248  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.248  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.248  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:14.248  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:14.248  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:38:14.249  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:14.249  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:38:14.249  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
,10-28 08:38:14.249  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:38:14.249  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:14.249  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:14.249  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 08:38:14.249  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:14.249  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:14.249  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.249  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 08:38:14.249  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 08:38:14.249  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.249  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.249  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 08:38:14.249  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.251  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-28 08:38:14.251  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.251  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.251  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.251  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:38:14.251  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:14.251  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:14.251  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.253  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.253  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.253  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.253  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:14.253  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:14.253  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:14.253  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:14.254  5560  5606 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-28 08:38:14.256  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:38:14.258  4554  4616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 08:38:14.258  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:38:14.261  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:38:14.261  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:14.261  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:14.261  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:14.261  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:38:14.261  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:14.261  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:14.261  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:14.264  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:14.264  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:38:14.264  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:38:14.264  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 08:38:14.264  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 08:38:14.264  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:38:14.264  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-28 08:38:14.264  4554  4616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 08:38:14.265  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:14.267  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:14.269  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 08:38:14.269  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 08:38:14.269  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 08:38:14.270  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:14.275  4554  4616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-28 08:38:14.275  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:14.275  4554  4619 D BtGatt.ScanManager: stopping BLe Batch
10-28 08:38:14.276  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.276  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-28 08:38:14.276  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-28 08:38:14.277  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-28 08:38:14.281  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.281  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 08:38:14.281  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 08:38:14.281  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 08:38:14.281  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-28 08:38:14.281  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.282  4554  4616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-28 08:38:14.282  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:14.282  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:38:14.282  4554  4619 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-28 08:38:14.284  4554  4779 D BtGatt.GattService: registerClient() - UUID=821c2f98-0c97-437c-a56f-890843a1a5bc
10-28 08:38:14.284  4554  4616 D BtGatt.GattService: onClientRegistered() - UUID=821c2f98-0c97-437c-a56f-890843a1a5bc, clientIf=5
,10-28 08:38:14.285  5560  5571 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-28 08:38:14.285  4554  4567 D BtGatt.GattService: start scan with filters
10-28 08:38:14.286  4554  4616 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-28 08:38:14.286  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:14.287  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-28 08:38:14.287  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.287  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 08:38:14.287  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.287  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 08:38:14.288  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 08:38:14.288  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.288  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 08:38:14.288  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 08:38:14.288  4554  4619 D BtGatt.ScanManager: handling starting scan
10-28 08:38:14.288  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.288  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.288  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-28 08:38:14.289  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 08:38:14.289  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.291  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.291  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:38:14.291  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:14.292  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:14.292  5560  5606 I io.jxcore.node.ConnectionHelper: start: OK
,10-28 08:38:14.292  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.293  4554  4616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 08:38:14.293  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:14.294  4554  4619 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-28 08:38:14.294  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.294  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.294  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.294  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:38:14.294  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-28 08:38:14.298  4554  4616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 08:38:14.299  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:38:14.299  4554  4619 D BtGatt.ScanManager: Starting BLE batch scan
10-28 08:38:14.299  4554  4619 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-28 08:38:14.307  4554  4616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 08:38:14.307  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:38:14.312  4554  4616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 08:38:14.312  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:38:14.795  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-28 08:38:14.796  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-28 08:38:14.796  5560  5560 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-28 08:38:17.694   930  2897 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-28 08:38:19.292  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 08:38:19.292  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:19.293  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-28 08:38:19.293  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:19.293  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-28 08:38:19.293  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:19.293  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-28 08:38:19.293  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 08:38:19.294  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 08:38:19.294  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 08:38:19.294  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.294  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.295  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:19.295  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 08:38:19.295  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.297  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:38:19.299  4554  4779 D BtGatt.GattService: stopScan() - queue size =1
,10-28 08:38:19.302  4554  4567 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-28 08:38:19.303  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 08:38:19.303  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:19.303  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 08:38:19.304  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.304  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.304  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.304  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:19.304  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 08:38:19.305  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.305  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:19.305  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:19.305  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-28 08:38:19.305  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-28 08:38:19.306  4554  4554 D BtGatt.ScanManager: awakened up at time 182876
10-28 08:38:19.307  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-28 08:38:19.308  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.308   930  3659 I ActivityManager: Killing 4997:com.google.android.apps.maps/u0a58 (adj 15): empty #17
10-28 08:38:19.310  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:19.311  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:38:19.311  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.311  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:19.311  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-28 08:38:19.312  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:38:19.312  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 08:38:19.312  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,10-28 08:38:19.312  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 08:38:19.312  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 08:38:19.313  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:38:19.313  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,10-28 08:38:19.313  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 08:38:19.313  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:38:19.315  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:38:19.315  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-28 08:38:19.316  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:38:19.316  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:38:19.316  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-28 08:38:19.355  4554  4616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-28 08:38:19.355  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:19.355  4554  4619 D BtGatt.ScanManager: stopping BLe Batch
,10-28 08:38:19.361  4554  4616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-28 08:38:19.361  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:19.362  4554  4619 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-28 08:38:19.380  4554  4616 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-28 08:38:19.380  4554  4616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:38:19.380  4554  4616 D BtGatt.GattService: current time is 182949774155
10-28 08:38:19.380  4554  4616 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -87, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -81, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -79, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -88, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-28 08:38:19.380  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-28 08:38:19.381  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-28 08:38:19.381  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-28 08:38:19.381  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-28 08:38:19.381  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-28 08:38:19.381  4554  4616 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-28 08:38:19.816  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 08:38:19.817  5560  5560 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:19.817  5560  5560 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-28 08:38:24.313  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 08:38:24.313  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:24.313  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-28 08:38:24.314  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:24.314  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.314  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:38:24.314  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-28 08:38:24.314  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:24.314  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.315  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:24.315  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.315  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:24.317  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.317  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:24.318  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:24.321  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:24.322  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.322  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:24.322  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.322  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:24.322  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.323  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.324  5560  5606 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-28 08:38:24.326  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:24.326  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:24.326  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:24.326  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-28 08:38:24.326  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.326  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.327  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.327  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:24.327  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.327  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.327  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.327  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.327  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:24.328  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.328  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.328  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.331  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.331  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.331  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:24.331  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.331  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:24.331  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.331  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.333  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-28 08:38:24.333  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:24.333  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:24.333  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:24.333  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:24.333  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:38:24.333  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.333  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.333  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:24.333  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.333  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.334  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.334  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:38:24.334  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.334  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.334  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.334  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.335  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.335  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.336  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.336  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.336  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-28 08:38:24.336  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.336  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.337  5560  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-28 08:38:24.337  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:24.337  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:24.337  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:24.337  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:24.337  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.337  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.337  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.337  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:24.337  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.338  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.338  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.338  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.338  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.338  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.338  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.338  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.339  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.340  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.340  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.340  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.340  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:24.340  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.340  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:24.341  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,10-28 08:38:24.341  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:24.341  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:24.341  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:24.341  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-28 08:38:24.341  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:38:24.341  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.341  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.342  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:24.342  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.342  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.342  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.342  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.342  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.342  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.342  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.342  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.344  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.344  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.344  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.344  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.344  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:24.344  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.345  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.345  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-28 08:38:24.345  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 08:38:24.345  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 08:38:24.346  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-28 08:38:24.346  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 08:38:24.346  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 08:38:24.346  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-28 08:38:24.346  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 08:38:24.346  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-28 08:38:24.346  5560  5606 I io.jxcore.node.ConnectionHelper: sto,p: Stopping all activities and killing connections
10-28 08:38:24.346  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:24.346  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:24.346  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:24.346  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.346  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.347  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.347  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:24.347  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.347  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.347  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.347  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.347  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.347  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.347  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.347  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.350  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.350  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.350  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.350  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.350  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:24.350  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.350  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.351  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-28 08:38:24.351  5560  5606 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-28 08:38:24.351  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-28 08:38:24.354  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-28 08:38:24.355  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-28 08:38:24.355  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-28 08:38:24.356  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-28 08:38:24.356  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-28 08:38:24.357  5560  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-28 08:38:24.357  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-28 08:38:24.358  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-28 08:38:24.358  5560  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-28 08:38:24.358  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-28 08:38:24.358  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-28 08:38:24.358  5560  5606 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-28 08:38:24.358  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-28 08:38:24.361  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-28 08:38:24.362  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-28 08:38:24.362  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-28 08:38:24.363  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-28 08:38:24.363  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-28 08:38:24.363  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-28 08:38:24.363  5560  5606 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-28 08:38:24.364  5560  5606 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,10-28 08:38:24.364  5560  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
10-28 08:38:24.364  5560  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-28 08:38:24.364  5560  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-28 08:38:24.364  5560  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-28 08:38:24.365  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:24.365  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:24.365  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:24.365  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-28 08:38:24.365  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.365  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.365  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.366  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-28 08:38:24.366  5560  5622 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-28 08:38:24.366  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:24.366  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.367  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.367  5560  5622 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 08:38:24.367  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 08:38:24.367  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.367  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.367  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.367  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.367  5560  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
10-28 08:38:24.367  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.367  5560  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
10-28 08:38:24.367  5560  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
10-28 08:38:24.367  5560  5623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
,10-28 08:38:24.370  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:24.370  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.370  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.370  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.370  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:24.370  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.370  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.371  5560  5606 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-28 08:38:24.371  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:24.372  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:24.365  4779  4779 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32891]" dev="sockfs" ino=32891 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-28 08:38:24.365  4779  4779 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32891]" dev="sockfs" ino=32891 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-28 08:38:24.372  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:24.372  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.372  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:24.372  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.372  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:24.372  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.372  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.372  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.372  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.372  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.372  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.372  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:24.372  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.374  5560  5622 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-28 08:38:24.374  5560  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-28 08:38:24.374  5560  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
10-28 08:38:24.375  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.375  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.375  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.375  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.375  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:24.375  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 08:38:24.375  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.376  5560  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-28 08:38:24.376  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:24.376  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-28 08:38:24.376  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:24.376  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:24.376  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.377  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.377  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.377  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
,10-28 08:38:24.377  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.377  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.377  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.377  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.377  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.377  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.377  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.377  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.378  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:24.378  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.378  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.378  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.378  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:24.378  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 08:38:24.378  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.379  5560  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-28 08:38:24.379  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-28 08:38:24.379  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-28 08:38:24.379  5560  5606 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-28 08:38:24.379  5560  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-28 08:38:24.379  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,10-28 08:38:24.380  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-28 08:38:24.380  5560  5606 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-28 08:38:24.380  5560  5606 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-28 08:38:24.380  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-28 08:38:24.380  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-28 08:38:24.380  5560  5606 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-28 08:38:24.380  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:24.380  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:24.380  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:24.380  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:24.380  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.380  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:24.380  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.380  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:24.380  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.380  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.380  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.380  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.381  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.381  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.381  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.381  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.382  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:24.382  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.382  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:24.382  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:24.382  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:24.382  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.382  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.383  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:24.383  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.383  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:24.383  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:24.383  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
,10-28 08:38:24.383  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:24.384  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:24.384  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:24.384  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:24.384  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:25.804   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:26.805   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:27.806   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:28.807   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:28.886   930  2913 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-28 08:38:29.384  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 08:38:29.385  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:29.385  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:29.385  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.385  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.385  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-28 08:38:29.386  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:29.386  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:29.386  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:29.386  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:29.386  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:29.387  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:38:29.387  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.387  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:29.387  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:29.387  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:29.388  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:29.388  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:29.388  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.388  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.388  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.388  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.389  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:29.392  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.392  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.393  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.393  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:29.393  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:29.393  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:29.394  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:29.399  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-28 08:38:29.401  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 08:38:29.404  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-28 08:38:29.405  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-28 08:38:29.406  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-28 08:38:29.406  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-28 08:38:29.406  5560  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-28 08:38:29.406  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-28 08:38:29.407  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-28 08:38:29.407  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-28 08:38:29.408  4567  4567 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31650]" dev="sockfs" ino=31650 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-28 08:38:29.408  4567  4567 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31650]" dev="sockfs" ino=31650 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-28 08:38:29.407  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:29.408  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-28 08:38:29.408  5560  5624 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 08:38:29.408  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-28 08:38:29.408  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-28 08:38:29.408  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.408  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-28 08:38:29.408  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-28 08:38:29.409  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
,10-28 08:38:29.409  5560  5560 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-28 08:38:29.409  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:29.409  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 08:38:29.409  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 08:38:29.409  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 08:38:29.409  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.409  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.410  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.412  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.412  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:38:29.412  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.412  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:29.412  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:29.412  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:29.413  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:38:29.413  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:29.413  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:29.413  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:38:29.413  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:29.413  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:38:29.413  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.413  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.413  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-28 08:38:29.413  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:29.413  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:29.414  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:29.414  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:29.414  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.414  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.414  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.414  5560  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-28 08:38:29.414  5560  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-28 08:38:29.414  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.414  5560  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-28 08:38:29.414  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.415  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-28 08:38:29.415  5560  5560 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:29.416  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.416  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.417  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.417  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:29.417  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:29.417  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:29.417  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:29.419  5560  5606 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-28 08:38:29.420  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-28 08:38:29.420  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-28 08:38:29.420  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 08:38:29.420  5560  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-28 08:38:29.421  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 08:38:29.421  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:29.421  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:29.421  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:29.421  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.421  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.421  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:29.421  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:29.422  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 08:38:29.422  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:29.422  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:29.422  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.422  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.422  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.422  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.422  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.427  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.428  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.428  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.428  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:29.428  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-28 08:38:29.428  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:29.429  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:29.435  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:29.435  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:38:29.435  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:29.435  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:29.435  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.435  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.435  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:29.435  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:29.436  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 08:38:29.436  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:29.436  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:29.436  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.436  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.436  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.436  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.436  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:38:29.438  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.438  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.438  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.438  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:29.438  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:29.439  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:29.439  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:29.441  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:38:29.441  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-28 08:38:29.441  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:38:29.441  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:38:29.441  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.441  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.441  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:38:29.441  5560  5606 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4a9c0 not in the list
10-28 08:38:29.441  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:29.441  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
10-28 08:38:29.442  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:29.442  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:38:29.442  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.442  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:29.442  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:29.442  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.444  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.445  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.445  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:38:29.445  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:38:29.445  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:38:29.445  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:29.445  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4f6f9 not in the list
,10-28 08:38:29.446  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-28 08:38:29.446  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-28 08:38:29.446  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-28 08:38:29.446  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-28 08:38:29.447  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-28 08:38:29.447  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-28 08:38:29.449  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-28 08:38:29.449  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-28 08:38:29.450  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-28 08:38:29.450  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-28 08:38:29.450  5560  5606 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-28 08:38:29.450  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-28 08:38:29.450  5560  5606 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-28 08:38:29.450  5560  5606 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-28 08:38:29.451  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-28 08:38:29.451  5560  5606 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-28 08:38:29.451  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,10-28 08:38:29.451  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-28 08:38:29.451  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-28 08:38:29.451  5560  5606 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-28 08:38:29.453  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:38:29.453  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f391f33 added. We now have 3 listener(s)
10-28 08:38:29.453  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:38:29.455  5560  5606 D BluetoothAdapter: enable(): BT is already enabled..!
10-28 08:38:29.455   930  3357 D WifiService: setWifiEnabled: true pid=5560, uid=10077
,10-28 08:38:29.456   930  3357 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 08:38:29.497  4554  4772 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-28 08:38:29.498  4554  4777 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-28 08:38:29.808   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:38:29.913  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 08:38:30.809   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-28 08:38:31.919   930  2913 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-28 08:38:32.055   930  5320 D NetlinkSocketObserver: NeighborEvent{elapsedMs=195623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-28 08:38:34.461  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:38:34.462  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74602f0 added. We now have 4 listener(s)
,10-28 08:38:34.462  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 08:38:34.476  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 08:38:34.476  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74602f0 removed from the list
10-28 08:38:34.476  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:34.477  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:38:34.477  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:34.478  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:38:34.479  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3549069 added. We now have 4 listener(s)
,10-28 08:38:34.479  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:38:34.481  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-28 08:38:34.482  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3549069 removed from the list
10-28 08:38:34.482  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:34.482  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:38:34.482  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:34.483  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-28 08:38:34.484  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@937aaee added. We now have 4 listener(s)
10-28 08:38:34.484  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 08:38:34.489   930   940 D WifiService: setWifiEnabled: false pid=5560, uid=10077
10-28 08:38:34.489   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 08:38:34.498   930  2897 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-28 08:38:34.498   930  2897 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-28 08:38:34.499   930  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-28 08:38:34.499   930  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-28 08:38:34.508  4554  4612 D BluetoothAdapterState: Current state: ON, message: 23
,10-28 08:38:34.508  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:38:34.508  4554  4612 D BluetoothAdapterProperties: Setting state to 13
10-28 08:38:34.508  4554  4612 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-28 08:38:34.511  4554  4612 D BluetoothAdapterProperties: onBluetoothDisable()
10-28 08:38:34.515  4554  4612 I BluetoothAdapterState: Entering PendingCommandState
10-28 08:38:34.515  4554  4554 D BluetoothMapService: onReceive
10-28 08:38:34.515  4554  4554 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-28 08:38:34.515  4554  4554 D BluetoothMapService: STATE_TURNING_OFF
10-28 08:38:34.516  4554  4554 D BluetoothMapService: MAP Service closeService in
,10-28 08:38:34.517  4554  4554 D BluetoothMapMasInstance0: MAP Service shutdown
10-28 08:38:34.517  4554  4554 D ObexServerSockets0: shutdown(block = true)
10-28 08:38:34.518  4554  4554 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-28 08:38:34.518  4554  4802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,10-28 08:38:34.518  4554  4554 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-28 08:38:34.518  4554  4777 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-28 08:38:34.519  4554  4803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-28 08:38:34.521   930  5321 D DhcpClient: Clearing IP address
10-28 08:38:34.521   506   925 D CommandListener: Clearing all IP addresses on wlan0
,10-28 08:38:34.525  4554  4554 I BtOppRfcommListener: stopping Accept Thread
,10-28 08:38:34.526  4554  5284 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-28 08:38:34.526  4554  5284 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-28 08:38:34.528  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.528  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:38:34.528  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.528  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.528  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.528  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.528  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:34.528  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:34.528  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:34.529  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:34.529  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:34.529  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:38:34.529   506   925 D CommandListener: Setting iface cfg
10-28 08:38:34.533  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:34.533   930  5322 D DhcpClient: Receive thread stopped
,10-28 08:38:34.537  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:34.538  3527  5375 V NativeCrypto: Read error: ssl=0x7f91218000: I/O error during system call, Connection timed out
,10-28 08:38:34.539  3527  5375 V NativeCrypto: SSL shutdown failed: ssl=0x7f91218000: I/O error during system call, Broken pipe
,10-28 08:38:34.541  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.541  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.541  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.541  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.541  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.541  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.541  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:34.541  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:34.541  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:38:34.542  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.542  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:34.543   930   943 I ActivityManager: Start proc 5628:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-28 08:38:34.546   930  3105 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-28 08:38:34.546   930  5319 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-28 08:38:34.546  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.547  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.547  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.547  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.547  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.547  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.547  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:34.547  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:34.547  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:34.547  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.547  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 08:38:34.550  4554  4616 D BluetoothAdapterProperties: Scan Mode:20
10-28 08:38:34.550   930  5319 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-28 08:38:34.550  4554  4612 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-28 08:38:34.550   930  2913 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-28 08:38:34.551   930  2913 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-28 08:38:34.552   930  2913 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-28 08:38:34.555  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.555  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.555  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.555  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.555  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.555  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.555  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.555  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:34.555  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:34.555  4554  4554 D HeadsetService: Received stop request...Stopping profile...
,10-28 08:38:34.556  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:34.556  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:34.557   930  2913 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-28 08:38:34.557   930  2913 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-28 08:38:34.558   532   532 E Parcel  : Reading a NULL string not supported here.
10-28 08:38:34.560   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:34.560  3064  3076 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:34.560  3064  3064 D HeadsetProfile: Bluetooth service disconnected
10-28 08:38:34.561   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:34.561  3704  3736 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:34.562   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:34.562   930   930 D RttService: SCAN_AVAILABLE : 1
10-28 08:38:34.563   930  3027 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-28 08:38:34.563  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.563  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:38:34.563  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:34.564  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.564  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:34.566   930  2913 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-28 08:38:34.568  4554  4554 D A2dpService: Received stop request...Stopping profile...
10-28 08:38:34.567  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:34.568  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.568  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.568  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.568  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.568  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.568  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.568  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:34.568  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:34.569  4554  4782 D A2dpStateMachine: Exit Disconnected: -1
10-28 08:38:34.569  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:34.569  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:34.570   930   930 D BluetoothA2dp: Proxy object disconnected
10-28 08:38:34.570  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:34.570  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:34.570  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
,10-28 08:38:34.570  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:34.570  3669  3836 W QCNEJ   : |CORE| network lost: 100
10-28 08:38:34.571  3669  3836 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-28 08:38:34.571  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:34.571  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.571  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.571  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.571  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.571  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.571  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.571  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:34.571  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:38:34.572  4554  4554 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-28 08:38:34.572  4554  4554 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-28 08:38:34.572  4554  4772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:34.572  4554  4772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:34.572  4554  4772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:34.572  4554  4616 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-28 08:38:34.572  4554  4616 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-28 08:38:34.572  4554  4554 D HidService: Received stop request...Stopping profile...
10-28 08:38:34.572  4554  4554 D HidService: Stopping Bluetooth HidService
10-28 08:38:34.573  4554  4554 D HealthService: Received stop request...Stopping profile...
,10-28 08:38:34.574  4554  4554 D PanService: Received stop request...Stopping profile...
10-28 08:38:34.575  4554  4554 D BluetoothMapService: Received stop request...Stopping profile...
10-28 08:38:34.576  4554  4554 D BluetoothMapService: stop()
,10-28 08:38:34.576  4554  4554 D BluetoothMapAppObserver: deinitObservers()
10-28 08:38:34.576  4554  4554 D BluetoothMapAppObserver: removeReceiver()
10-28 08:38:34.578  4554  4554 D SapService: Received stop request...Stopping profile...
10-28 08:38:34.578  4554  4554 V SapService: stop()
,10-28 08:38:34.583   930  2897 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-28 08:38:34.583   930  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-28 08:38:34.585  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:34.585  4554  4554 V BluetoothAdapterState: isTurningOn()=false
,10-28 08:38:34.585  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:34.585  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:34.586  4554  4616 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-28 08:38:34.586  4554  4772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-28 08:38:34.587  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:34.587  4554  4554 V BluetoothAdapterState: isTurningOn()=false
,10-28 08:38:34.587  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
,10-28 08:38:34.587  4554  4772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-28 08:38:34.587  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
,10-28 08:38:34.587  4554  4772 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-28 08:38:34.587  4554  4772 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-28 08:38:34.587  4554  4772 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-28 08:38:34.587  4554  4772 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-28 08:38:34.587  4554  4554 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-28 08:38:34.587  3064  3064 D BluetoothA2dp: Proxy object disconnected
10-28 08:38:34.587  4554  4554 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-28 08:38:34.587  3064  3064 D BluetoothInputDevice: Proxy object disconnected
10-28 08:38:34.587  3064  3064 D HidProfile: Bluetooth service disconnected
10-28 08:38:34.588  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:34.588  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-28 08:38:34.588  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:34.588  3064  3064 D PanProfile: Bluetooth service disconnected
10-28 08:38:34.588  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:34.588  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:34.588  3064  3064 D BluetoothMap: Proxy object disconnected
10-28 08:38:34.588  3064  3064 D MapProfile: Bluetooth service disconnected
10-28 08:38:34.588  4554  4554 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-28 08:38:34.588  4554  4554 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-28 08:38:34.588  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:34.588  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:34.588  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:34.589  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:34.589  4554  4554 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-28 08:38:34.589  4554  4554 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-28 08:38:34.590  4554  4616 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-28 08:38:34.590  4554  4616 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-28 08:38:34.592  4554  4554 D BluetoothMapService: MAP Service closeService in
10-28 08:38:34.593  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:34.593  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:34.593  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:34.593  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
,10-28 08:38:34.593  4554  4554 D BluetoothMapService: cleanup()
10-28 08:38:34.593  4554  4554 D BluetoothMapService: MAP Service closeService in
10-28 08:38:34.593  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:34.593  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:34.593  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:34.593  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:34.594  4554  4612 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-28 08:38:34.594  4554  4612 D BluetoothAdapterProperties: Setting state to 15
10-28 08:38:34.594  4554  4612 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-28 08:38:34.594  4554  4612 I BluetoothAdapterState: Entering BleOnState
10-28 08:38:34.594   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-28 08:38:34.594  3064  3076 D BluetoothMap: onBluetoothStateChange: up=false
10-28 08:38:34.595   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 08:38:34.595   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:34.595  3064  3077 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-28 08:38:34.596  3064  3804 D BluetoothPan: onBluetoothStateChange on: false
10-28 08:38:34.596  3064  3076 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 08:38:34.597  3064  3804 D BluetoothPbap: onBluetoothStateChange: up=false
10-28 08:38:34.598  3064  3077 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:34.598   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:34.599  3704  3755 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:34.599  4554  4612 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-28 08:38:34.599  4554  4612 D BluetoothAdapterProperties: Setting state to 16
10-28 08:38:34.599  4554  4612 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-28 08:38:34.601  4554  4612 D BluetoothAdapterProperties: onBleDisable
,10-28 08:38:34.601  4554  4612 I BluetoothAdapterState: Entering PendingCommandState
10-28 08:38:34.601  4554  4613 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-28 08:38:34.602  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.602  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.602  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.602  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.602  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.602  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.602  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.602  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:34.602  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:34.603  4554  4772 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-28 08:38:34.603  4554  4772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:34.603  4554  4616 D BluetoothAdapterProperties: Scan Mode:20
10-28 08:38:34.604  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.604  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.604  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.604  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.604  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.604  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.604  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.604  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:34.604  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 08:38:34.606  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:34.606  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.606  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.606  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.606  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:34.606  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.606  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.606  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:34.606  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:34.607  5628  5628 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-28 08:38:34.608  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:34.609  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:34.610  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:34.611   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 08:38:34.625  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-28 08:38:34.630   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@967fc1d:true
,10-28 08:38:34.633  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-28 08:38:34.637   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-28 08:38:34.637   930  2913 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-28 08:38:34.638   930  2913 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-28 08:38:34.640   506   925 D CommandListener: Clearing all IP addresses on wlan0
,10-28 08:38:34.641   506   925 D TetherController: Setting IP forward enable = 0
,10-28 08:38:34.649   930   940 I ActivityManager: Start proc 5650:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-28 08:38:34.650   930   947 D Tethering: MasterInitialState.processMessage what=3
,10-28 08:38:34.652   930  2897 D DhcpClient: doQuit
10-28 08:38:34.653   930  2897 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-28 08:38:34.653  3387  3387 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-28 08:38:34.654   930  5321 D DhcpClient: onQuitting
10-28 08:38:34.654  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:34.656  5207  5207 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@24842ba and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-28 08:38:34.657  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.658  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.658  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.658  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.658  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:34.658  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.658  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.658  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:34.658  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:34.659  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.659  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-28 08:38:34.661  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:34.661  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:34.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:34.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:34.662  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.662  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:34.662  4983  4996 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-28 08:38:34.662  4983  4996 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-28 08:38:34.662  4983  4996 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-28 08:38:34.662  4983  4996 E SarControlService: no key has been found,reset the power
10-28 08:38:34.662  4983  5021 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-28 08:38:34.662  4983  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-28 08:38:34.663  4983  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-28 08:38:34.663  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 08:38:34.663  5009  5009 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-28 08:38:34.665  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.665  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:34.665  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:34.665  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:34.665  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:34.665  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:34.665  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:34.665  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:34.665  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 08:38:34.665  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:34.665  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:34.667  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:34.669  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:34.670  4983  5021 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-28 08:38:34.670  4983  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-28 08:38:34.670  4983  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-28 08:38:34.671  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 08:38:34.671  5009  5009 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-28 08:38:34.657  4900  4900 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-28 08:38:34.674  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3cca6f0 HexData = [00000000ea03000000000000ffffffff]
10-28 08:38:34.674  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 08:38:34.674  5009  5023 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-28 08:38:34.674  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-28 08:38:34.674  4983  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-28 08:38:34.681  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3cca6f0 HexData = [00000000eb03000000000000ffffffff]
10-28 08:38:34.681  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 08:38:34.681  5009  5023 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-28 08:38:34.681  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-28 08:38:34.682  4983  4994 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-28 08:38:34.683  3387  3387 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-28 08:38:34.688  3387  3387 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-28 08:38:34.709  3387  3387 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-28 08:38:34.710  5628  5628 D LocalBluetoothProfileManager: Adding local MAP profile
,10-28 08:38:34.712   506   925 E Netd    : netlink response contains error (No such file or directory)
,10-28 08:38:34.712  5628  5628 D BluetoothMap: Create BluetoothMap proxy object
10-28 08:38:34.713   506   925 D TetherController: Setting IP forward enable = 0
10-28 08:38:34.713   930  2913 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-28 08:38:34.720  5650  5650 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-28 08:38:34.720  3387  3387 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-28 08:38:34.726   930  2897 D wifi    : In wifi stop Hal
,10-28 08:38:34.726   930  2897 D wifi    : halHandle = 0x7f763d6e00, mVM = 0x7f92a0d140, mCls = 0x100a02
10-28 08:38:34.726  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-28 08:38:34.726   930  3386 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-28 08:38:34.726   930  3386 D WifiHAL : Got a signal to exit!!!
10-28 08:38:34.726   930  3386 I WifiHAL : Exit wifi_event_loop
10-28 08:38:34.726   930  2897 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-28 08:38:34.726   930  2897 E WifiHAL : Event processing terminated
10-28 08:38:34.727   930  2897 D wifi    : In wifi cleaned up handler
10-28 08:38:34.727   930  2897 I WifiHAL : Internal cleanup completed
,10-28 08:38:34.727  3875  4148 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-28 08:38:34.727  5628  5628 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
10-28 08:38:34.728  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:34.729  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:34.729  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:34.741  5628  5628 D DockEventReceiver: finishStartingService: stopping service
,10-28 08:38:34.746   930  3386 D wifi    : set interface wlan0 flags (DOWN)
10-28 08:38:34.746   930  2897 D WifiNative-HAL: HAL event thread stopped successfully
,10-28 08:38:34.747   930  3357 I ActivityManager: Killing 4941:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-28 08:38:34.808  4554  4616 I bt_hci  : shut_down
,10-28 08:38:34.811  4554  4620 D bt_hwcfg: hw_epilog_process
,10-28 08:38:34.811  4554  4620 I bt_vendor: low_power_mode_cb
,10-28 08:38:34.813  4554  4620 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-28 08:38:34.814  4554  4620 I bt_vendor: epilog_cb
10-28 08:38:34.814  4554  4620 I bt_hci  : epilog_finished_callback
,10-28 08:38:34.815  4554  4616 I bt_hci_h4: hal_close
,10-28 08:38:34.816  4554  4616 I bt_userial_vendor: device fd = 54 close
,10-28 08:38:34.916  5650  5650 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at java.io.File.exists(File.java:361)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 08:38:34.916  5650  5650 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 08:38:34.916  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 08:38:34.917  5650  5650 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5422)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 08:38:34.917  5650  5650 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.r.e.b(PG:170)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 08:38:34.917  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 08:38:34.921  4554  4613 D bt_stack_manager: event_shut_down_stack finished.
10-28 08:38:34.922  5650  5650 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.r.k.d(PG:583)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.r.e.b(PG:170)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 08:38:34.922  4554  4612 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-28 08:38:34.922  5650  5650 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.io.File.exists(File.java:361)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 08:38:34.922  5650  5650 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.io.File.exists(File.java:361)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 08:38:34.922  5650  5650 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 08:38:34.922  5650  5650 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 08:38:34.923  4554  4554 D BtGatt.DebugUtils: handleDebugAction() action=null
10-28 08:38:34.924  4554  4612 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-28 08:38:34.924  4554  4554 D BtGatt.GattService: Received stop request...Stopping profile...
10-28 08:38:34.924  4554  4554 D BtGatt.GattService: stop()
10-28 08:38:34.924  4554  4554 D BtGatt.AdvertiseManager: advertise clients cleared
10-28 08:38:34.925  4554  4554 V BluetoothAdapterState: isTurningOff()=false
10-28 08:38:34.925  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:34.925  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:34.925  4554  4554 V BluetoothAdapterState: isBleTurningOff()=true
10-28 08:38:34.926  4554  4612 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-28 08:38:34.926  4554  4612 D BluetoothAdapterProperties: Setting state to 10
10-28 08:38:34.926  4554  4612 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-28 08:38:34.927  4554  4612 I BluetoothAdapterState: Entering OffState
10-28 08:38:34.927   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-28 08:38:34.928  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-28 08:38:34.934  4554  4554 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-28 08:38:34.934  4554  4554 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-28 08:38:34.934  4554  4554 I BluetoothServiceJni: cleanupNative: return from cleanup
10-28 08:38:34.935  4554  4613 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-28 08:38:34.945  4554  4554 I art     : System.exit called, status: 0
10-28 08:38:34.945  4554  4554 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-28 08:38:34.948   930   947 D Tethering: InitialState.processMessage what=4
10-28 08:38:34.950   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-28 08:38:34.955  5628  5628 D DockEventReceiver: finishStartingService: stopping service
10-28 08:38:34.956   930  3766 I ActivityManager: Killing 5348:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
10-28 08:38:34.992   930  3106 I ActivityManager: Process com.android.bluetooth (pid 4554) has died
,10-28 08:38:34.994  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-28 08:38:35.005   930  3357 I ActivityManager: Start proc 5693:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,10-28 08:38:35.069  5693  5693 D AdapterServiceConfig: Adding HeadsetService
10-28 08:38:35.069  5693  5693 D AdapterServiceConfig: Adding A2dpService
,10-28 08:38:35.070  5693  5693 D AdapterServiceConfig: Adding HidService
10-28 08:38:35.070  5693  5693 D AdapterServiceConfig: Adding HealthService
10-28 08:38:35.070  5693  5693 D AdapterServiceConfig: Adding PanService
10-28 08:38:35.070  5693  5693 D AdapterServiceConfig: Adding GattService
10-28 08:38:35.070  5693  5693 D AdapterServiceConfig: Adding BluetoothMapService
10-28 08:38:35.070  5693  5693 D AdapterServiceConfig: Adding SapService
10-28 08:38:35.073   930  3106 I ActivityManager: Killing 5362:com.android.chrome/u0a39 (adj 15): empty #17
,10-28 08:38:35.098  3995  3995 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-28 08:38:35.101  3995  3995 D SystemUpdateService: onCreate
,10-28 08:38:35.104  3995  3995 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-28 08:38:35.112  3995  3995 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-28 08:38:35.116  3995  5345 I iu.UploadsManager: num queued entries: 0
,10-28 08:38:35.122  3995  5705 I SystemUpdateService: active receiver: enabled
,10-28 08:38:35.124  3995  3995 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-28 08:38:35.125  3995  3995 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-28 08:38:35.117  3995  5345 I iu.UploadsManager: num updated entries: 0
,10-28 08:38:35.135  3995  5345 I iu.SyncManager: NEXT; no task
10-28 08:38:35.137   930  3766 I ActivityManager: Start proc 5707:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-28 08:38:35.140  3995  5705 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-28 08:38:35.146  3995  5705 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-28 08:38:35.148  3995  5705 I SystemUpdateService: now status is 0 (complete)
10-28 08:38:35.149  3995  5705 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-28 08:38:35.149  3995  5705 I SystemUpdateService: file has been verified
10-28 08:38:35.149  3995  5705 I SystemUpdateService: OTA package size = 21989297
,10-28 08:38:35.176  5707  5707 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-28 08:38:35.178  5707  5707 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-28 08:38:35.184  5707  5707 D SprintDMHelper: simOperator: 
,10-28 08:38:35.184  5707  5707 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-28 08:38:35.187  3995  5705 I SystemUpdateService: showing system update notification
,10-28 08:38:35.198   930  3705 I ActivityManager: Start proc 5719:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-28 08:38:35.225  3995  3995 D SystemUpdateService: onDestroy
,10-28 08:38:35.227   930  3659 I ActivityManager: Killing 5379:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-28 08:38:35.297  4355  5733 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-28 08:38:35.307   930   941 I ActivityManager: Start proc 5734:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-28 08:38:35.309   930   941 I ActivityManager: Killing 5207:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-28 08:38:35.366  5734  5734 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-28 08:38:35.526  5650  5685 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-28 08:38:35.550   930  3705 I ActivityManager: Killing 4626:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-28 08:38:35.571   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23b5c43:true
,10-28 08:38:35.595   930  3105 I ActivityManager: Start proc 5748:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-28 08:38:35.628  5748  5748 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-28 08:38:35.636   930  3106 I ActivityManager: Killing 5434:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-28 08:38:39.532   930  3659 D WifiService: setWifiEnabled: true pid=5560, uid=10077
10-28 08:38:39.532   930  3659 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 08:38:39.540   506   925 D SoftapController: Softap fwReload - Ok
,10-28 08:38:39.545   506   925 D CommandListener: Setting iface cfg
,10-28 08:38:39.546   506   925 D CommandListener: Trying to bring down wlan0
10-28 08:38:39.548   506   925 D CommandListener: Clearing all IP addresses on wlan0
,10-28 08:38:39.553   930  2897 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-28 08:38:40.124   930  2897 D wifi    : set interface wlan0 flags (UP)
,10-28 08:38:40.128   930  2897 I WifiHAL : Initializing wifi
,10-28 08:38:40.129   930  2897 I WifiHAL : Creating socket
,10-28 08:38:40.132   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-28 08:38:40.133   930  2897 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-28 08:38:40.133   930  2897 D wifi    : Did set static halHandle = 0x7f763d6e00
10-28 08:38:40.133   930  2897 D wifi    : halHandle = 0x7f763d6e00, mVM = 0x7f92a0d140, mCls = 0x19aa
,10-28 08:38:40.134   930  2897 D wifi    : array field set
10-28 08:38:40.134   930  2897 I WifiNative-HAL: interface[0] = wlan0
10-28 08:38:40.136   930  5766 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547444583936
10-28 08:38:40.136   930  5766 D wifi    : waitForHalEvents called, vm = 0x7f92a0d140, obj = 0x19aa, env = 0x7f763d1b40
,10-28 08:38:40.142   930  2897 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-28 08:38:40.145   930  2897 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,10-28 08:38:40.147  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:40.150  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:40.152  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:40.211  5767  5767 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-28 08:38:40.233  5767  5767 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-28 08:38:40.270  5767  5767 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-28 08:38:40.270  5767  5767 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-28 08:38:41.159  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:41.159  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:41.159  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:41.159  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:41.159  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:41.159  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:41.159  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:41.159  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:41.159  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:41.160  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:41.160   930  2897 D WifiConfigStore: Loading config and enabling all networks 
,10-28 08:38:41.160  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,10-28 08:38:41.163  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:41.163  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:41.163  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:41.163  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:41.163  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:41.163  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:41.163  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:41.163  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:41.163  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:41.163  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:41.164  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:41.165  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:41.166  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:41.166  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:41.166  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:41.166  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:38:41.166  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:41.166  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:41.166  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:41.166  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:41.166  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:41.166  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-28 08:38:41.178   930  2897 D WifiConfigStore: loaded 0 passpoint configs
,10-28 08:38:41.178   930  2897 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-28 08:38:41.179   930  2897 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-28 08:38:41.180   930  2897 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-28 08:38:41.182   930  2897 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-28 08:38:41.182   930  2897 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-28 08:38:41.182   930  2897 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-28 08:38:41.182   930  2897 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-28 08:38:41.186  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-28 08:38:41.186   930  2897 D WifiNative-HAL: Setting external_sim to 1
10-28 08:38:41.187   930  2897 D wifi    : setting dfs flag to true, 0x7f7a0d2aa0
10-28 08:38:41.188   930  2897 D WifiStateMachine: Setting OUI to DA-A1-19
10-28 08:38:41.188   930  2897 D wifi    : setting scan oui 0x7f7a0d2aa0
10-28 08:38:41.188   930  2897 D WifiHAL : Sending mac address OUI
,10-28 08:38:41.193   930  2897 E native  : do suspend false
,10-28 08:38:41.201   930  2897 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-28 08:38:41.201   506   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-28 08:38:41.202   930   930 D RttService: SCAN_AVAILABLE : 3
10-28 08:38:41.202   930  3027 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-28 08:38:41.202   506   925 D CommandListener: Setting iface cfg
,10-28 08:38:41.206   930  2894 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
10-28 08:38:41.206   930  2894 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-28 08:38:41.216   930  2894 D WifiNative-HAL: p2pGetDeviceAddress
,10-28 08:38:41.221   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=204790 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
10-28 08:38:41.221   930  2894 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-28 08:38:44.283  5767  5767 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-28 08:38:44.292  5767  5767 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-28 08:38:44.298  5767  5767 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-28 08:38:44.324   930  2897 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-28 08:38:44.325   930  2897 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-28 08:38:44.325   930  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-28 08:38:44.336   930  2897 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-28 08:38:44.370   930  2897 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-28 08:38:44.371  5767  5767 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-28 08:38:44.537   930  3357 D WifiService: setWifiEnabled: false pid=5560, uid=10077
,10-28 08:38:44.538   930  3357 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 08:38:44.546   930   930 D RttService: SCAN_AVAILABLE : 1
,10-28 08:38:44.547   930  3027 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-28 08:38:44.561   930  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-28 08:38:44.562   506   925 D CommandListener: Clearing all IP addresses on wlan0
,10-28 08:38:44.573   930  2897 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-28 08:38:44.575  5767  5767 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-28 08:38:44.583  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:44.583  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:44.583  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:44.583  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:44.583  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:44.583  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:44.583  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:44.583  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:44.583  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:44.583  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:44.583  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:44.585  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:44.585  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:44.585  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:44.585  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:44.585  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:44.585  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:44.585  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:44.585  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:44.585  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:44.585  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:44.585  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:44.586  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:44.586  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:44.586  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:44.586  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:44.586  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:44.586  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:44.586  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:44.586  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:44.586  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:44.587  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:44.587  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-28 08:38:44.592  5767  5767 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-28 08:38:44.595  5767  5767 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,10-28 08:38:44.619  5767  5767 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-28 08:38:44.624  5767  5767 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-28 08:38:44.728  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-28 08:38:44.729   930  2897 D wifi    : In wifi stop Hal
,10-28 08:38:44.729   930  2897 D wifi    : halHandle = 0x7f763d6e00, mVM = 0x7f92a0d140, mCls = 0x19aa
,10-28 08:38:44.733  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:44.736  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:44.737   930  5766 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-28 08:38:44.737   930  5766 D WifiHAL : Got a signal to exit!!!
10-28 08:38:44.738   930  5766 I WifiHAL : Exit wifi_event_loop
10-28 08:38:44.738  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:44.739   930  2897 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-28 08:38:44.740   930  2897 E WifiHAL : Event processing terminated
10-28 08:38:44.740   930  2897 D wifi    : In wifi cleaned up handler
10-28 08:38:44.741   930  2897 I WifiHAL : Internal cleanup completed
10-28 08:38:44.742  3875  4148 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-28 08:38:44.764   930  5766 D wifi    : set interface wlan0 flags (DOWN)
,10-28 08:38:44.764   930  2897 D WifiNative-HAL: HAL event thread stopped successfully
,10-28 08:38:44.970   930   947 D Tethering: InitialState.processMessage what=4
,10-28 08:38:44.976   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-28 08:38:49.574   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@934bee:true
,10-28 08:38:49.575  5693  5693 D BluetoothAdapterState: make() - Creating AdapterState
,10-28 08:38:49.579  5693  5693 I bt_bluedroid: init
10-28 08:38:49.579  5693  5773 I BluetoothAdapterState: Entering OffState
,10-28 08:38:49.583  5693  5774 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-28 08:38:49.583  5693  5774 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-28 08:38:49.583  5693  5774 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-28 08:38:49.583  5693  5774 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-28 08:38:49.584  5693  5693 I bt_bluedroid: get_profile_interface socket
,10-28 08:38:49.588  5693  5777 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-28 08:38:49.588  5693  5693 I bt_bluedroid: get_profile_interface sdp
,10-28 08:38:49.591  5693  5777 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-28 08:38:49.595  5693  5703 I bt_bluedroid: config_hci_snoop_log
,10-28 08:38:49.596   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-28 08:38:49.602  5693  5773 D BluetoothAdapterState: Current state: OFF, message: 0
,10-28 08:38:49.602  5693  5773 D BluetoothAdapterProperties: Setting state to 14
10-28 08:38:49.602  5693  5773 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-28 08:38:49.604  5693  5773 D BluetoothBondStateMachine: make
10-28 08:38:49.606  5693  5778 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-28 08:38:49.610  5693  5773 I BluetoothAdapterState: Entering PendingCommandState
,10-28 08:38:49.611  5693  5693 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-28 08:38:49.614  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
,10-28 08:38:49.615  5693  5693 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-28 08:38:49.616  5693  5693 D BtGatt.GattService: Received start request. Starting profile...
,10-28 08:38:49.616  5693  5693 D BtGatt.GattService: start()
10-28 08:38:49.616  5693  5693 I bt_bluedroid: get_profile_interface gatt
,10-28 08:38:49.617  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:38:49.618  5693  5693 D BtGatt.AdvertiseManager: advertise manager created
,10-28 08:38:49.625  5693  5693 V BluetoothAdapterState: isTurningOff()=false
,10-28 08:38:49.625  5693  5693 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:49.625  5693  5693 V BluetoothAdapterState: isBleTurningOn()=true
10-28 08:38:49.625  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:49.625  5693  5773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-28 08:38:49.627  5693  5773 I bt_bluedroid: bt_bluedroid
,10-28 08:38:49.627  5693  5774 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-28 08:38:49.628  5693  5774 I bt_hci  : start_up
,10-28 08:38:49.635  5693  5774 I bt_vendor: alloc value 0xf40b8871
10-28 08:38:49.636  5693  5774 I bt_vendor: init
,10-28 08:38:49.636  5693  5774 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-28 08:38:49.636  5693  5774 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-28 08:38:49.750  5693  5774 D bt_hci  : start_up starting async portion
10-28 08:38:49.751  5693  5781 I bt_hci  : event_finish_startup
,10-28 08:38:49.751  5693  5781 I bt_hci_h4: hal_open
10-28 08:38:49.751  5693  5781 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-28 08:38:49.754  5693  5781 I bt_userial_vendor: device fd = 54 open
,10-28 08:38:49.748  5782  5782 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-28 08:38:49.768  5693  5781 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-28 08:38:49.772  5693  5781 D bt_hwcfg: Chipset BCM4358A3
10-28 08:38:49.772  5693  5781 D bt_hwcfg: Target name = [BCM4358A3]
10-28 08:38:49.772  5693  5781 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-28 08:38:50.285  5693  5781 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-28 08:38:50.285  5693  5781 D bt_hwcfg: Settlement delay -- 100 ms
10-28 08:38:50.285  5693  5781 I bt_hwcfg: Setting fw settlement delay to 100 
,10-28 08:38:50.420  5693  5781 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-28 08:38:50.421  5693  5781 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-28 08:38:50.422  5693  5781 I bt_hwcfg: vendor lib fwcfg completed
10-28 08:38:50.423  5693  5781 I bt_vendor: firmware callback
10-28 08:38:50.423  5693  5781 I bt_hci  : firmware_config_callback
,10-28 08:38:50.432  5693  5784 I bt_btu  : btu_task pending for preload complete event
,10-28 08:38:50.432  5693  5784 I bt_btu_task: Bluetooth chip preload is complete
10-28 08:38:50.432  5693  5784 I bt_btu  : btu_task received preload complete event
,10-28 08:38:50.441  5693  5784 I         : BTE_InitTraceLevels -- TRC_HCI
,10-28 08:38:50.441  5693  5784 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-28 08:38:50.441  5693  5784 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-28 08:38:50.441  5693  5784 I         : BTE_InitTraceLevels -- TRC_AVDT
10-28 08:38:50.441  5693  5784 I         : BTE_InitTraceLevels -- TRC_AVRC
10-28 08:38:50.441  5693  5784 I         : BTE_InitTraceLevels -- TRC_A2D
,10-28 08:38:50.442  5693  5784 I         : BTE_InitTraceLevels -- TRC_BNEP
10-28 08:38:50.442  5693  5784 I         : BTE_InitTraceLevels -- TRC_BTM
10-28 08:38:50.442  5693  5784 I         : BTE_InitTraceLevels -- TRC_GAP
10-28 08:38:50.442  5693  5784 I         : BTE_InitTraceLevels -- TRC_PAN
,10-28 08:38:50.442  5693  5784 I         : BTE_InitTraceLevels -- TRC_SDP
10-28 08:38:50.442  5693  5784 I         : BTE_InitTraceLevels -- TRC_GATT
10-28 08:38:50.442  5693  5784 I         : BTE_InitTraceLevels -- TRC_SMP
10-28 08:38:50.442  5693  5784 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-28 08:38:50.443  5693  5784 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-28 08:38:50.527  5693  5784 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4036549
,10-28 08:38:50.528  5693  5784 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4036549 
,10-28 08:38:50.547  5693  5777 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-28 08:38:50.548  5693  5777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-28 08:38:50.549  5693  5777 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-28 08:38:50.551  5693  5777 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-28 08:38:50.554  5693  5777 D BluetoothAdapterProperties: Scan Mode:20
,10-28 08:38:50.555  5693  5777 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-28 08:38:50.555  5693  5777 D bt_hci  : do_postload posting postload work item
,10-28 08:38:50.555  5693  5781 I bt_hci  : event_postload
10-28 08:38:50.555  5693  5781 I bt_vendor: sco_config_cb
10-28 08:38:50.555  5693  5781 I bt_hci  : sco_config_callback postload finished.
,10-28 08:38:50.562  5693  5777 D bt_bte_conf: Device ID record 1 : primary
,10-28 08:38:50.562  5693  5777 D bt_bte_conf:   vendorId            = 000f
10-28 08:38:50.562  5693  5777 D bt_bte_conf:   vendorIdSource      = 0001
10-28 08:38:50.562  5693  5777 D bt_bte_conf:   product             = 1200
10-28 08:38:50.562  5693  5777 D bt_bte_conf:   version             = 1436
10-28 08:38:50.563  5693  5777 D bt_bte_conf:   clientExecutableURL = 
10-28 08:38:50.563  5693  5777 D bt_bte_conf:   serviceDescription  = 
10-28 08:38:50.563  5693  5777 D bt_bte_conf:   documentationURL    = 
10-28 08:38:50.563  5693  5777 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-28 08:38:50.563  5693  5774 D bt_stack_manager: event_start_up_stack finished
10-28 08:38:50.564  5693  5773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-28 08:38:50.564  5693  5781 I bt_vendor: low_power_mode_cb
10-28 08:38:50.564  5693  5773 D BluetoothAdapterProperties: Setting state to 15
10-28 08:38:50.565  5693  5773 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-28 08:38:50.565  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:50.567  5693  5773 I BluetoothAdapterState: Entering BleOnState
10-28 08:38:50.568  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:50.569  5693  5773 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-28 08:38:50.569  5693  5773 D BluetoothAdapterProperties: Setting state to 11
10-28 08:38:50.569  5693  5773 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-28 08:38:50.570  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:50.574  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:38:50.575  5693  5693 D HeadsetService: Received start request. Starting profile...
,10-28 08:38:50.578  5693  5693 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-28 08:38:50.579  5693  5693 D HeadsetStateMachine: make
,10-28 08:38:50.581  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:50.583  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:50.585  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:50.591  5693  5773 I BluetoothAdapterState: Entering PendingCommandState
,10-28 08:38:50.592  5693  5693 D HeadsetStateMachine: max_hf_connections = 1
,10-28 08:38:50.592  5693  5693 I bt_bluedroid: get_profile_interface handsfree
10-28 08:38:50.593  5693  5777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-28 08:38:50.593  5693  5777 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-28 08:38:50.595  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
,10-28 08:38:50.596  5693  5693 D A2dpService: Received start request. Starting profile...
,10-28 08:38:50.597  5693  5693 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-28 08:38:50.597  5693  5693 I bt_bluedroid: get_profile_interface avrcp
,10-28 08:38:50.602  5693  5693 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-28 08:38:50.603  5693  5693 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-28 08:38:50.603  5693  5693 D A2dpStateMachine: make
10-28 08:38:50.604  5693  5693 I bt_bluedroid: get_profile_interface a2dp
10-28 08:38:50.604  5693  5777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-28 08:38:50.606  5693  5793 D A2dpStateMachine: Enter Disconnected: -2
,10-28 08:38:50.607  5693  5693 I BluetoothHidServiceJni: classInitNative: succeeds
,10-28 08:38:50.608  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-28 08:38:50.608  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:38:50.610  5628  5628 D BluetoothInputDevice: Proxy object connected
10-28 08:38:50.610  5693  5693 D HidService: Received start request. Starting profile...
10-28 08:38:50.610  5693  5693 I bt_bluedroid: get_profile_interface hidhost
,10-28 08:38:50.610  5693  5693 D HidService: setHidService(): set to: null
10-28 08:38:50.610  5693  5777 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf401756d
10-28 08:38:50.610  5628  5628 D HidProfile: Bluetooth service connected
10-28 08:38:50.611  5693  5777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-28 08:38:50.611  5693  5693 I BluetoothHealthServiceJni: classInitNative: succeeds
10-28 08:38:50.611  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
,10-28 08:38:50.612  5693  5693 D HealthService: Received start request. Starting profile...
10-28 08:38:50.613  5693  5693 I bt_bluedroid: get_profile_interface health
,10-28 08:38:50.614  5693  5693 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-28 08:38:50.615  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
,10-28 08:38:50.616  5628  5628 D BluetoothPan: BluetoothPAN Proxy object connected
,10-28 08:38:50.616  5628  5628 D PanProfile: Bluetooth service connected
10-28 08:38:50.617  5693  5693 D PanService: Received start request. Starting profile...
10-28 08:38:50.617  5693  5693 D BluetoothPanServiceJni: initializeNative(L110): pan
10-28 08:38:50.617  5693  5693 I bt_bluedroid: get_profile_interface pan
10-28 08:38:50.618  5693  5777 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-28 08:38:50.620  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:38:50.621  5628  5628 D BluetoothMap: Proxy object connected
10-28 08:38:50.621  5693  5693 D BluetoothMapService: Received start request. Starting profile...
10-28 08:38:50.621  5693  5693 D BluetoothMapService: start()
,10-28 08:38:50.622  5628  5628 D MapProfile: Bluetooth service connected
10-28 08:38:50.622  5628  5628 D BluetoothMap: getConnectedDevices()
10-28 08:38:50.622  5628  5628 D BluetoothMap: Bluetooth is Not enabled
,10-28 08:38:50.625  5693  5693 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-28 08:38:50.626  5693  5693 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-28 08:38:50.626  5693  5693 D BluetoothMapAppObserver: createReceiver()
,10-28 08:38:50.627  5693  5693 D BluetoothMapAppObserver: initObservers()
,10-28 08:38:50.628  5693  5693 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-28 08:38:50.635  5693  5693 V SapService: SapBinder()
,10-28 08:38:50.635  5693  5693 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:38:50.635  5693  5693 D SapService: Received start request. Starting profile...
10-28 08:38:50.635  5693  5693 V SapService: start()
,10-28 08:38:50.637  5693  5693 V BluetoothAdapterState: isTurningOff()=false
10-28 08:38:50.637  5693  5693 V BluetoothAdapterState: isTurningOn()=true
,10-28 08:38:50.637  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:50.637  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isTurningOff()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isTurningOn()=true
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:50.638  5693  5790 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isTurningOff()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isTurningOn()=true
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isTurningOff()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isTurningOn()=true
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isTurningOff()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isTurningOn()=true
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:50.638  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:50.639  5693  5693 V BluetoothAdapterState: isTurningOff()=false
10-28 08:38:50.639  5693  5693 V BluetoothAdapterState: isTurningOn()=true
10-28 08:38:50.639  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
,10-28 08:38:50.639  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:50.640  5693  5693 V BluetoothAdapterState: isTurningOff()=false
10-28 08:38:50.640  5693  5693 V BluetoothAdapterState: isTurningOn()=true
10-28 08:38:50.640  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:50.640  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:50.641  5693  5773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-28 08:38:50.641  5693  5773 D BluetoothAdapterProperties: ScanMode =  20
10-28 08:38:50.641  5693  5773 D BluetoothAdapterProperties: State =  11
10-28 08:38:50.641  5693  5773 D BluetoothAdapterProperties: Setting state to 12
10-28 08:38:50.641  5693  5773 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-28 08:38:50.642   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 08:38:50.642  5693  5773 I BluetoothAdapterState: Entering OnState
10-28 08:38:50.642  3064  3804 D BluetoothMap: onBluetoothStateChange: up=true
,10-28 08:38:50.644  3064  3064 D BluetoothMap: Proxy object connected
,10-28 08:38:50.644  3064  3064 D MapProfile: Bluetooth service connected
10-28 08:38:50.644  5693  5777 D BluetoothAdapterProperties: Scan Mode:21
10-28 08:38:50.644  3064  3064 D BluetoothMap: getConnectedDevices()
10-28 08:38:50.644  5693  5777 D BluetoothAdapterProperties: Discoverable Timeout:120
10-28 08:38:50.645  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-28 08:38:50.646   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 08:38:50.647   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 08:38:50.647  3064  3076 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-28 08:38:50.647   930   930 D BluetoothA2dp: Proxy object connected
10-28 08:38:50.648  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:50.648  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:50.648  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:50.648  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:50.648  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:38:50.648  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:50.648  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:50.648  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:50.649  3064  3064 D BluetoothInputDevice: Proxy object connected
10-28 08:38:50.649  3064  3064 D HidProfile: Bluetooth service connected
10-28 08:38:50.649  5628  5640 D BluetoothMap: onBluetoothStateChange: up=true
10-28 08:38:50.649  5628  5639 D BluetoothPbap: onBluetoothStateChange: up=true
10-28 08:38:50.650  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:50.651  5628  5640 D BluetoothPan: onBluetoothStateChange on: true
10-28 08:38:50.652  3064  3804 D BluetoothPan: onBluetoothStateChange on: true
,10-28 08:38:50.652  5693  5693 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-28 08:38:50.653  5693  5693 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-28 08:38:50.653  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:50.653  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:50.653  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:50.653  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:50.653  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:38:50.653  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:50.653  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:50.653  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:50.653  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
10-28 08:38:50.653  3064  3077 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 08:38:50.653  3064  3064 D PanProfile: Bluetooth service connected
10-28 08:38:50.655  5693  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 08:38:50.655  5628  5639 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-28 08:38:50.655  3064  3064 D BluetoothA2dp: Proxy object connected
10-28 08:38:50.655  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:50.655  3064  3076 D BluetoothPbap: onBluetoothStateChange: up=true
10-28 08:38:50.657  3064  3077 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 08:38:50.657   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 08:38:50.657  3704  3940 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 08:38:50.658  5693  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-28 08:38:50.659   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,10-28 08:38:50.661  5693  5693 D ObexServerSockets: Succeed to create listening sockets 
10-28 08:38:50.661  5693  5693 D ObexServerSockets0: startAccept()
10-28 08:38:50.661  5693  5693 D ObexServerSockets0: prepareForNewConnect()
10-28 08:38:50.661  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:50.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:50.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:50.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:50.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:38:50.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:50.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:50.661  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 08:38:50.663  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-28 08:38:50.663  5693  5693 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-28 08:38:50.663  5693  5693 D BluetoothSdpJni: SDP Create record success - handle: 0
10-28 08:38:50.663  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-28 08:38:50.664  5693  5800 D ObexServerSockets0: Accepting socket connection...
10-28 08:38:50.664  5693  5801 D ObexServerSockets0: Accepting socket connection...
10-28 08:38:50.664  5693  5693 D BluetoothMapService: onReceive
10-28 08:38:50.664  5693  5693 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-28 08:38:50.664  5693  5693 D BluetoothMapService: STATE_ON
10-28 08:38:50.665  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:50.666  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:50.666  5693  5802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-28 08:38:50.667  5628  5628 D LocalBluetoothProfileManager: Adding local A2DP profile
10-28 08:38:50.667  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:50.668  5693  5802 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-28 08:38:50.668  5693  5802 D BluetoothSdpJni: SDP Create record success - handle: 1
10-28 08:38:50.670  5628  5628 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-28 08:38:50.677  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-28 08:38:50.679  5628  5628 D BluetoothA2dp: Proxy object connected
,10-28 08:38:50.684  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-28 08:38:50.688  5628  5628 D DockEventReceiver: finishStartingService: stopping service
,10-28 08:38:50.690  3064  3064 D BluetoothPbap: Proxy object connected
10-28 08:38:50.690  3064  3064 D PbapServerProfile: Bluetooth service connected
,10-28 08:38:50.691  5628  5628 D BluetoothPbap: Proxy object connected
10-28 08:38:50.691  5693  5693 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-28 08:38:50.691  5693  5693 D ObexServerSockets0: prepareForNewConnect()
,10-28 08:38:50.691  5628  5628 D PbapServerProfile: Bluetooth service connected
,10-28 08:38:50.701  5693  5806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-28 08:38:50.713  5693  5810 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-28 08:38:50.714  5693  5810 I BtOppRfcommListener: Accept thread started.
,10-28 08:38:50.743   930   930 D BluetoothHeadset: Proxy object connected
,10-28 08:38:50.743  3064  3076 D BluetoothHeadset: Proxy object connected
10-28 08:38:50.743  3064  3064 D HeadsetProfile: Bluetooth service connected
10-28 08:38:50.743   930   930 D BluetoothHeadset: Proxy object connected
10-28 08:38:50.743  3704  3755 D BluetoothHeadset: Proxy object connected
10-28 08:38:50.744   930   930 D BluetoothHeadset: Proxy object connected
,10-28 08:38:50.747   930   947 D BluetoothHeadset: Proxy object connected
,10-28 08:38:50.758  3064  3077 D BluetoothHeadset: Proxy object connected
,10-28 08:38:50.759  3064  3064 D HeadsetProfile: Bluetooth service connected
10-28 08:38:50.759   930   947 D BluetoothHeadset: Proxy object connected
10-28 08:38:50.759  3704  3736 D BluetoothHeadset: Proxy object connected
,10-28 08:38:50.773  5628  5640 D BluetoothHeadset: Proxy object connected
,10-28 08:38:50.776  5628  5628 D HeadsetProfile: Bluetooth service connected
,10-28 08:38:54.559  5693  5773 D BluetoothAdapterState: Current state: ON, message: 23
10-28 08:38:54.559  5693  5773 D BluetoothAdapterProperties: Setting state to 13
10-28 08:38:54.559  5693  5773 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-28 08:38:54.561  5693  5773 D BluetoothAdapterProperties: onBluetoothDisable()
10-28 08:38:54.563  5693  5773 I BluetoothAdapterState: Entering PendingCommandState
,10-28 08:38:54.568  5693  5693 D BluetoothMapService: onReceive
,10-28 08:38:54.568  5693  5693 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-28 08:38:54.568  5693  5693 D BluetoothMapService: STATE_TURNING_OFF
10-28 08:38:54.569  5693  5693 D BluetoothMapService: MAP Service closeService in
,10-28 08:38:54.569  5693  5693 D BluetoothMapMasInstance0: MAP Service shutdown
,10-28 08:38:54.569  5693  5693 D ObexServerSockets0: shutdown(block = true)
10-28 08:38:54.569  5693  5777 D BluetoothAdapterProperties: Scan Mode:20
,10-28 08:38:54.570  5693  5773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-28 08:38:54.575  5693  5693 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-28 08:38:54.575  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-28 08:38:54.575  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:54.575  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:54.575  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:54.575  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:54.575  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:54.575  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:54.575  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:54.575  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:54.575  5693  5693 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-28 08:38:54.575  5693  5786 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-28 08:38:54.576  5693  5801 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-28 08:38:54.576  5693  5800 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-28 08:38:54.577  5693  5693 I BtOppRfcommListener: stopping Accept Thread
10-28 08:38:54.577  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:54.577  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:54.578  5693  5810 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-28 08:38:54.578  5693  5810 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-28 08:38:54.578  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-28 08:38:54.581  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:54.581  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:54.581  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:54.581  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:54.581  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:54.581  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:54.581  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:54.581  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:54.581  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:54.583  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:54.583  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:38:54.585  5628  5628 D DockEventReceiver: finishStartingService: stopping service
,10-28 08:38:54.585  5693  5693 D HeadsetService: Received stop request...Stopping profile...
10-28 08:38:54.588   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:54.588  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:54.588  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:38:54.588  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:38:54.588  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:38:54.588  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:38:54.588  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-28 08:38:54.588  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:38:54.588  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:38:54.588  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:38:54.588  5628  5639 D BluetoothHeadset: Proxy object disconnected
,10-28 08:38:54.589  3064  3804 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:54.589   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:54.589  3704  3940 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:54.589  5560  5560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-28 08:38:54.589  5693  5693 D A2dpService: Received stop request...Stopping profile...
10-28 08:38:54.589  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-28 08:38:54.590   930   930 D BluetoothHeadset: Proxy object disconnected
10-28 08:38:54.590  5693  5793 D A2dpStateMachine: Exit Disconnected: -1
10-28 08:38:54.590  5628  5628 D HeadsetProfile: Bluetooth service disconnected
10-28 08:38:54.591   930   930 D BluetoothA2dp: Proxy object disconnected
10-28 08:38:54.591  5628  5628 D BluetoothA2dp: Proxy object disconnected
10-28 08:38:54.591  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:54.592  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:38:54.594  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:54.598  3064  3064 D HeadsetProfile: Bluetooth service disconnected
10-28 08:38:54.598  3064  3064 D BluetoothA2dp: Proxy object disconnected
10-28 08:38:54.599  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-28 08:38:54.600  5693  5693 D HidService: Received stop request...Stopping profile...
10-28 08:38:54.600  5693  5693 D HidService: Stopping Bluetooth HidService
10-28 08:38:54.601  5693  5693 V BluetoothAdapterState: isTurningOff()=true
,10-28 08:38:54.602  5693  5693 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:54.602  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:54.602  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:54.602  3064  3064 D BluetoothInputDevice: Proxy object disconnected
,10-28 08:38:54.603  3064  3064 D HidProfile: Bluetooth service disconnected
10-28 08:38:54.604  5693  5693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-28 08:38:54.604  5693  5693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-28 08:38:54.604  5693  5777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-28 08:38:54.604  5693  5784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:54.604  5693  5784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:54.604  5693  5784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:54.605  5693  5693 D HealthService: Received stop request...Stopping profile...
10-28 08:38:54.606  5693  5693 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:54.606  5693  5777 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-28 08:38:54.606  5693  5693 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:54.606  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:54.606  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:54.606  5628  5628 D BluetoothInputDevice: Proxy object disconnected
10-28 08:38:54.606  5628  5628 D HidProfile: Bluetooth service disconnected
10-28 08:38:54.607  5693  5784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:54.607  5693  5784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:54.607  5693  5777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-28 08:38:54.607  5693  5784 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-28 08:38:54.607  5693  5784 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-28 08:38:54.607  5693  5784 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-28 08:38:54.607  5693  5784 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-28 08:38:54.609  3064  3064 D BluetoothPbap: Proxy object disconnected
10-28 08:38:54.609  3064  3064 D PbapServerProfile: Bluetooth service disconnected
,10-28 08:38:54.609  5693  5693 D PanService: Received stop request...Stopping profile...
,10-28 08:38:54.610  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-28 08:38:54.610  3064  3064 D PanProfile: Bluetooth service disconnected
10-28 08:38:54.610  5628  5628 D BluetoothPbap: Proxy object disconnected
10-28 08:38:54.610  5628  5628 D PbapServerProfile: Bluetooth service disconnected
,10-28 08:38:54.610  5693  5693 D BluetoothMapService: Received stop request...Stopping profile...
,10-28 08:38:54.610  5693  5693 D BluetoothMapService: stop()
10-28 08:38:54.610  5628  5628 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-28 08:38:54.610  5628  5628 D PanProfile: Bluetooth service disconnected
10-28 08:38:54.611  5693  5693 D BluetoothMapAppObserver: deinitObservers()
10-28 08:38:54.611  5693  5693 D BluetoothMapAppObserver: removeReceiver()
10-28 08:38:54.612  3064  3064 D BluetoothMap: Proxy object disconnected
10-28 08:38:54.612  3064  3064 D MapProfile: Bluetooth service disconnected
10-28 08:38:54.613  5628  5628 D BluetoothMap: Proxy object disconnected,
,10-28 08:38:54.613  5628  5628 D MapProfile: Bluetooth service disconnected
10-28 08:38:54.614  5693  5693 D SapService: Received stop request...Stopping profile...
10-28 08:38:54.614  5693  5693 V SapService: stop()
10-28 08:38:54.615  5693  5693 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:54.615  5693  5693 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:54.615  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
,10-28 08:38:54.615  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:54.615  5693  5693 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-28 08:38:54.615  5693  5693 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-28 08:38:54.616  5693  5777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-28 08:38:54.616  5693  5693 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:54.616  5693  5693 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:54.616  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:54.616  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:54.617  5693  5693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-28 08:38:54.617  5693  5777 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-28 08:38:54.617  5693  5693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-28 08:38:54.617  5693  5693 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:54.617  5693  5693 V BluetoothAdapterState: isTurningOn()=false
,10-28 08:38:54.617  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:54.618  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:54.618  5693  5693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-28 08:38:54.618  5693  5693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-28 08:38:54.618  5693  5693 D BluetoothMapService: MAP Service closeService in
10-28 08:38:54.618  5693  5693 V BluetoothAdapterState: isTurningOff()=true
10-28 08:38:54.619  5693  5693 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:54.619  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:54.619  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:54.619  5693  5693 D BluetoothMapService: cleanup()
10-28 08:38:54.619  5693  5693 D BluetoothMapService: MAP Service closeService in
10-28 08:38:54.619  5693  5693 V BluetoothAdapterState: isTurningOff()=true
,10-28 08:38:54.619  5693  5693 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:54.619  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:54.619  5693  5693 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:38:54.619  5693  5773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-28 08:38:54.619  5693  5773 D BluetoothAdapterProperties: Setting state to 15
10-28 08:38:54.619  5693  5773 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-28 08:38:54.620  5693  5773 I BluetoothAdapterState: Entering BleOnState
10-28 08:38:54.620  5628  5640 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 08:38:54.621   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:54.622  3064  3077 D BluetoothMap: onBluetoothStateChange: up=false
10-28 08:38:54.622   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 08:38:54.622   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:54.622  3064  3804 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-28 08:38:54.623  5628  5639 D BluetoothMap: onBluetoothStateChange: up=false
10-28 08:38:54.623  5628  5640 D BluetoothPbap: onBluetoothStateChange: up=false
10-28 08:38:54.624  5628  5639 D BluetoothPan: onBluetoothStateChange on: false
10-28 08:38:54.625  3064  3077 D BluetoothPan: onBluetoothStateChange on: false
10-28 08:38:54.627  3064  3804 D BluetoothA2dp: onBluetoothStateChange: up=false
10-28 08:38:54.627  5628  5640 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-28 08:38:54.628  3064  3076 D BluetoothPbap: onBluetoothStateChange: up=false
10-28 08:38:54.628  3064  3077 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:54.628  5628  5639 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:54.629   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:54.629  3704  3755 D BluetoothHeadset: onBluetoothStateChange: up=false
10-28 08:38:54.629  5693  5773 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-28 08:38:54.629  5693  5773 D BluetoothAdapterProperties: Setting state to 16
10-28 08:38:54.629  5693  5773 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-28 08:38:54.630  5693  5773 D BluetoothAdapterProperties: onBleDisable
10-28 08:38:54.630  5693  5773 I BluetoothAdapterState: Entering PendingCommandState
10-28 08:38:54.630  5693  5774 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-28 08:38:54.631  5693  5784 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-28 08:38:54.631  5693  5784 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-28 08:38:54.632  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:54.633  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:54.633  5693  5777 D BluetoothAdapterProperties: Scan Mode:20
10-28 08:38:54.634  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-28 08:38:54.634  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:54.637  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:54.638  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-28 08:38:54.641  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInf,o: No relevant state changes
10-28 08:38:54.642  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:38:54.650  5628  5628 D DockEventReceiver: finishStartingService: stopping service
,10-28 08:38:54.845  5693  5777 I bt_hci  : shut_down
,10-28 08:38:54.850  5693  5781 D bt_hwcfg: hw_epilog_process
,10-28 08:38:54.851  5693  5781 I bt_vendor: low_power_mode_cb
,10-28 08:38:54.854  5693  5781 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-28 08:38:54.854  5693  5781 I bt_vendor: epilog_cb
10-28 08:38:54.854  5693  5781 I bt_hci  : epilog_finished_callback
,10-28 08:38:54.860  5693  5777 I bt_hci_h4: hal_close
,10-28 08:38:54.861  5693  5777 I bt_userial_vendor: device fd = 54 close
,10-28 08:38:54.976  5693  5774 D bt_stack_manager: event_shut_down_stack finished.
,10-28 08:38:54.977  5693  5773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-28 08:38:54.982  5693  5773 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-28 08:38:54.982  5693  5693 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-28 08:38:54.983  5693  5693 D BtGatt.GattService: Received stop request...Stopping profile...
10-28 08:38:54.983  5693  5693 D BtGatt.GattService: stop()
10-28 08:38:54.983  5693  5693 D BtGatt.AdvertiseManager: advertise clients cleared
,10-28 08:38:54.986  5693  5693 V BluetoothAdapterState: isTurningOff()=false
,10-28 08:38:54.987  5693  5693 V BluetoothAdapterState: isTurningOn()=false
10-28 08:38:54.987  5693  5693 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:38:54.987  5693  5693 V BluetoothAdapterState: isBleTurningOff()=true
10-28 08:38:54.987  5693  5773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-28 08:38:54.988  5693  5773 D BluetoothAdapterProperties: Setting state to 10
10-28 08:38:54.988  5693  5773 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-28 08:38:54.989  5693  5773 I BluetoothAdapterState: Entering OffState
,10-28 08:38:54.992   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-28 08:38:55.005  5693  5693 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-28 08:38:55.006  5693  5693 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,10-28 08:38:55.006  5693  5693 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-28 08:38:55.008  5693  5774 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-28 08:38:55.015  5693  5693 I art     : System.exit called, status: 0
10-28 08:38:55.015  5693  5693 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-28 08:38:55.042   930  3105 I ActivityManager: Process com.android.bluetooth (pid 5693) has died
,10-28 08:38:55.810   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-28 08:38:55.810   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-28 08:38:59.556  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 08:38:59.556  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:59.562  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:59.563  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@937aaee removed from the list
10-28 08:38:59.563  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 08:38:59.563  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:38:59.563  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:38:59.568  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-28 08:38:59.569  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f205e1c added. We now have 4 listener(s)
10-28 08:38:59.569  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 08:38:59.571  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:38:59.571  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f205e1c removed from the list
10-28 08:38:59.571  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:38:59.571  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:38:59.572  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:38:59.573  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:38:59.574  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31cca25 added. We now have 4 listener(s)
10-28 08:38:59.574  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 08:39:04.586  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:39:04.625   930   947 I ActivityManager: Start proc 5818:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-28 08:39:04.714  5818  5818 D AdapterServiceConfig: Adding HeadsetService
,10-28 08:39:04.714  5818  5818 D AdapterServiceConfig: Adding A2dpService
10-28 08:39:04.715  5818  5818 D AdapterServiceConfig: Adding HidService
10-28 08:39:04.715  5818  5818 D AdapterServiceConfig: Adding HealthService
10-28 08:39:04.715  5818  5818 D AdapterServiceConfig: Adding PanService
10-28 08:39:04.715  5818  5818 D AdapterServiceConfig: Adding GattService
10-28 08:39:04.715  5818  5818 D AdapterServiceConfig: Adding BluetoothMapService
10-28 08:39:04.716  5818  5818 D AdapterServiceConfig: Adding SapService
,10-28 08:39:04.728   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ca65c4f:true
,10-28 08:39:04.729  5818  5818 D BluetoothAdapterState: make() - Creating AdapterState
,10-28 08:39:04.731  5818  5818 I bt_bluedroid: init
,10-28 08:39:04.733  5818  5830 I BluetoothAdapterState: Entering OffState
,10-28 08:39:04.736  5818  5831 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-28 08:39:04.736  5818  5831 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-28 08:39:04.736  5818  5831 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-28 08:39:04.736  5818  5831 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-28 08:39:04.737  5818  5818 I bt_bluedroid: get_profile_interface socket
,10-28 08:39:04.739  5818  5834 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-28 08:39:04.739  5818  5818 I bt_bluedroid: get_profile_interface sdp
10-28 08:39:04.741  5818  5834 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-28 08:39:04.745  5818  5829 I bt_bluedroid: config_hci_snoop_log
10-28 08:39:04.746   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-28 08:39:04.751  5818  5830 D BluetoothAdapterState: Current state: OFF, message: 0
10-28 08:39:04.751  5818  5830 D BluetoothAdapterProperties: Setting state to 14
,10-28 08:39:04.751  5818  5830 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-28 08:39:04.753  5818  5830 D BluetoothBondStateMachine: make
,10-28 08:39:04.755  5818  5835 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-28 08:39:04.759  5818  5818 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-28 08:39:04.760  5818  5830 I BluetoothAdapterState: Entering PendingCommandState
,10-28 08:39:04.762  5818  5818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:39:04.763  5818  5818 D BtGatt.DebugUtils: handleDebugAction() action=null
10-28 08:39:04.763  5818  5818 D BtGatt.GattService: Received start request. Starting profile...
10-28 08:39:04.763  5818  5818 D BtGatt.GattService: start()
10-28 08:39:04.764  5818  5818 I bt_bluedroid: get_profile_interface gatt
,10-28 08:39:04.765  5818  5818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:39:04.765  5818  5818 D BtGatt.AdvertiseManager: advertise manager created
,10-28 08:39:04.772  5818  5818 V BluetoothAdapterState: isTurningOff()=false
10-28 08:39:04.772  5818  5818 V BluetoothAdapterState: isTurningOn()=false
10-28 08:39:04.772  5818  5818 V BluetoothAdapterState: isBleTurningOn()=true
,10-28 08:39:04.772  5818  5818 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:39:04.772  5818  5830 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-28 08:39:04.774  5818  5830 I bt_bluedroid: bt_bluedroid
10-28 08:39:04.774  5818  5831 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-28 08:39:04.775  5818  5831 I bt_hci  : start_up
,10-28 08:39:04.779  5818  5831 I bt_vendor: alloc value 0xf4108871
,10-28 08:39:04.779  5818  5831 I bt_vendor: init
10-28 08:39:04.780  5818  5831 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-28 08:39:04.780  5818  5831 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-28 08:39:04.891  5818  5831 D bt_hci  : start_up starting async portion
,10-28 08:39:04.892  5818  5838 I bt_hci  : event_finish_startup
10-28 08:39:04.892  5818  5838 I bt_hci_h4: hal_open
10-28 08:39:04.892  5818  5838 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-28 08:39:04.895  5818  5838 I bt_userial_vendor: device fd = 54 open
,10-28 08:39:04.888  5839  5839 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-28 08:39:04.911  5818  5838 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-28 08:39:04.914  5818  5838 D bt_hwcfg: Chipset BCM4358A3
,10-28 08:39:04.915  5818  5838 D bt_hwcfg: Target name = [BCM4358A3]
10-28 08:39:04.915  5818  5838 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-28 08:39:05.434  5818  5838 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-28 08:39:05.459  5818  5838 D bt_hwcfg: Settlement delay -- 100 ms
10-28 08:39:05.459  5818  5838 I bt_hwcfg: Setting fw settlement delay to 100 
,10-28 08:39:05.573  5818  5838 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-28 08:39:05.573  5818  5838 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-28 08:39:05.576  5818  5838 I bt_hwcfg: vendor lib fwcfg completed
10-28 08:39:05.576  5818  5838 I bt_vendor: firmware callback
10-28 08:39:05.576  5818  5838 I bt_hci  : firmware_config_callback
,10-28 08:39:05.586  5818  5841 I bt_btu  : btu_task pending for preload complete event
,10-28 08:39:05.586  5818  5841 I bt_btu_task: Bluetooth chip preload is complete
10-28 08:39:05.586  5818  5841 I bt_btu  : btu_task received preload complete event
,10-28 08:39:05.594  5818  5841 I         : BTE_InitTraceLevels -- TRC_HCI
,10-28 08:39:05.594  5818  5841 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-28 08:39:05.594  5818  5841 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-28 08:39:05.594  5818  5841 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-28 08:39:05.595  5818  5841 I         : BTE_InitTraceLevels -- TRC_AVRC
10-28 08:39:05.595  5818  5841 I         : BTE_InitTraceLevels -- TRC_A2D
,10-28 08:39:05.595  5818  5841 I         : BTE_InitTraceLevels -- TRC_BNEP
10-28 08:39:05.595  5818  5841 I         : BTE_InitTraceLevels -- TRC_BTM
10-28 08:39:05.595  5818  5841 I         : BTE_InitTraceLevels -- TRC_GAP
,10-28 08:39:05.595  5818  5841 I         : BTE_InitTraceLevels -- TRC_PAN
10-28 08:39:05.595  5818  5841 I         : BTE_InitTraceLevels -- TRC_SDP
,10-28 08:39:05.596  5818  5841 I         : BTE_InitTraceLevels -- TRC_GATT
10-28 08:39:05.596  5818  5841 I         : BTE_InitTraceLevels -- TRC_SMP
10-28 08:39:05.596  5818  5841 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-28 08:39:05.596  5818  5841 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-28 08:39:05.689  5818  5841 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4086549
,10-28 08:39:05.690  5818  5841 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4086549 
,10-28 08:39:05.710  5818  5834 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-28 08:39:05.712  5818  5834 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-28 08:39:05.713  5818  5834 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-28 08:39:05.715  5818  5834 D BluetoothAdapterProperties: Name is: Nexus 6P
10-28 08:39:05.718  5818  5834 D BluetoothAdapterProperties: Scan Mode:20
10-28 08:39:05.718  5818  5834 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-28 08:39:05.718  5818  5834 D bt_hci  : do_postload posting postload work item
10-28 08:39:05.719  5818  5838 I bt_hci  : event_postload
10-28 08:39:05.719  5818  5838 I bt_vendor: sco_config_cb
10-28 08:39:05.719  5818  5838 I bt_hci  : sco_config_callback postload finished.
,10-28 08:39:05.724  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:39:05.726  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:05.727  5818  5834 D bt_bte_conf: Device ID record 1 : primary
10-28 08:39:05.727  5818  5834 D bt_bte_conf:   vendorId            = 000f
10-28 08:39:05.727  5818  5834 D bt_bte_conf:   vendorIdSource      = 0001
10-28 08:39:05.727  5818  5834 D bt_bte_conf:   product             = 1200
10-28 08:39:05.727  5818  5834 D bt_bte_conf:   version             = 1436
,10-28 08:39:05.727  5818  5834 D bt_bte_conf:   clientExecutableURL = 
10-28 08:39:05.727  5818  5834 D bt_bte_conf:   serviceDescription  = 
10-28 08:39:05.728  5818  5834 D bt_bte_conf:   documentationURL    = 
10-28 08:39:05.728  5818  5834 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-28 08:39:05.728  5818  5831 D bt_stack_manager: event_start_up_stack finished
10-28 08:39:05.728  5818  5830 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-28 08:39:05.729  5818  5830 D BluetoothAdapterProperties: Setting state to 15
10-28 08:39:05.729  5818  5830 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-28 08:39:05.729  5818  5830 I BluetoothAdapterState: Entering BleOnState
,10-28 08:39:05.732  5818  5838 I bt_vendor: low_power_mode_cb
10-28 08:39:05.733  5818  5830 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-28 08:39:05.733  5818  5830 D BluetoothAdapterProperties: Setting state to 11
10-28 08:39:05.733  5818  5830 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-28 08:39:05.740  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:39:05.742  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:05.748  5818  5818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
,10-28 08:39:05.750  5818  5818 D HeadsetService: Received start request. Starting profile...
,10-28 08:39:05.753  5818  5818 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-28 08:39:05.753  5818  5818 D HeadsetStateMachine: make
,10-28 08:39:05.760  5818  5830 I BluetoothAdapterState: Entering PendingCommandState
,10-28 08:39:05.768  5818  5818 D HeadsetStateMachine: max_hf_connections = 1
,10-28 08:39:05.768  5818  5818 I bt_bluedroid: get_profile_interface handsfree
10-28 08:39:05.768  5818  5834 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-28 08:39:05.769  5818  5834 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-28 08:39:05.773  5818  5818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
,10-28 08:39:05.774  5818  5818 D A2dpService: Received start request. Starting profile...
10-28 08:39:05.775  5818  5818 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-28 08:39:05.775  5818  5818 I bt_bluedroid: get_profile_interface avrcp
,10-28 08:39:05.776  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-28 08:39:05.781  5818  5818 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-28 08:39:05.782  5818  5818 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-28 08:39:05.782  5818  5818 D A2dpStateMachine: make
10-28 08:39:05.783  5818  5818 I bt_bluedroid: get_profile_interface a2dp
10-28 08:39:05.784  5818  5834 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-28 08:39:05.785  5818  5849 D A2dpStateMachine: Enter Disconnected: -2
,10-28 08:39:05.786  5818  5818 I BluetoothHidServiceJni: classInitNative: succeeds
10-28 08:39:05.787  5818  5818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
,10-28 08:39:05.787  5818  5818 D HidService: Received start request. Starting profile...
10-28 08:39:05.788  5818  5818 I bt_bluedroid: get_profile_interface hidhost
10-28 08:39:05.788  5818  5818 D HidService: setHidService(): set to: null
10-28 08:39:05.788  5818  5834 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf406756d
10-28 08:39:05.788  5818  5834 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-28 08:39:05.788  5818  5818 I BluetoothHealthServiceJni: classInitNative: succeeds
10-28 08:39:05.789  5818  5818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
,10-28 08:39:05.790  5818  5818 D HealthService: Received start request. Starting profile...
,10-28 08:39:05.792  5818  5818 I bt_bluedroid: get_profile_interface health
,10-28 08:39:05.792  5818  5818 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-28 08:39:05.793  5818  5818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
,10-28 08:39:05.794  5818  5818 D PanService: Received start request. Starting profile...
,10-28 08:39:05.794  5818  5818 D BluetoothPanServiceJni: initializeNative(L110): pan
10-28 08:39:05.794  5818  5818 I bt_bluedroid: get_profile_interface pan
10-28 08:39:05.795  5818  5834 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-28 08:39:05.797  5818  5818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:39:05.798  5818  5818 D BluetoothMapService: Received start request. Starting profile...
10-28 08:39:05.798  5818  5818 D BluetoothMapService: start()
,10-28 08:39:05.801  5818  5818 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-28 08:39:05.802  5818  5818 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-28 08:39:05.802  5818  5818 D BluetoothMapAppObserver: createReceiver()
10-28 08:39:05.807  5818  5818 D BluetoothMapAppObserver: initObservers()
10-28 08:39:05.807  5818  5818 D BluetoothMapAppObserver: getEnabledAccountItems()
10-28 08:39:05.811   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:05.812  5818  5818 V SapService: SapBinder()
10-28 08:39:05.812  5818  5818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:39:05.812  5818  5818 D SapService: Received start request. Starting profile...
10-28 08:39:05.812  5818  5818 V SapService: start()
,10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isTurningOff()=false
10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isTurningOn()=true
10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isBleTurningOff()=false
,10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isTurningOff()=false
,10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isTurningOn()=true
,10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:39:05.815  5818  5847 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isTurningOff()=false
10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isTurningOn()=true
10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:39:05.815  5818  5818 V BluetoothAdapterState: isTurningOff()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isTurningOn()=true
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isBleTurningOff()=false
,10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isTurningOff()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isTurningOn()=true
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isTurningOff()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isTurningOn()=true
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isTurningOff()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isTurningOn()=true
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isBleTurningOn()=false
10-28 08:39:05.816  5818  5818 V BluetoothAdapterState: isBleTurningOff()=false
10-28 08:39:05.817  5818  5830 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-28 08:39:05.817  5818  5830 D BluetoothAdapterProperties: ScanMode =  20
10-28 08:39:05.817  5818  5830 D BluetoothAdapterProperties: State =  11
,10-28 08:39:05.817  5818  5830 D BluetoothAdapterProperties: Setting state to 12
10-28 08:39:05.817  5818  5830 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-28 08:39:05.818  5818  5830 I BluetoothAdapterState: Entering OnState
10-28 08:39:05.819  5628  5639 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 08:39:05.819  5818  5834 D BluetoothAdapterProperties: Scan Mode:21
10-28 08:39:05.819  5818  5834 D BluetoothAdapterProperties: Discoverable Timeout:120
10-28 08:39:05.820  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-28 08:39:05.821   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 08:39:05.821  3064  3077 D BluetoothMap: onBluetoothStateChange: up=true
10-28 08:39:05.823   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 08:39:05.823   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 08:39:05.824   930   930 D BluetoothA2dp: Proxy object connected
10-28 08:39:05.824  3064  3076 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-28 08:39:05.824  5628  5628 D BluetoothA2dp: Proxy object connected
10-28 08:39:05.824  3064  3064 D BluetoothMap: Proxy object connected
10-28 08:39:05.824  3064  3064 D MapProfile: Bluetooth service connected
10-28 08:39:05.824  3064  3064 D BluetoothMap: getConnectedDevices()
10-28 08:39:05.828  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:39:05.828  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:05.828  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:05.828  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:39:05.828  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:05.828  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:39:05.828  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:39:05.828  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:39:05.829  5628  5639 D BluetoothMap: onBluetoothStateChange: up=true
10-28 08:39:05.830  3064  3064 D BluetoothInputDevice: Proxy object connected
10-28 08:39:05.830  3064  3064 D HidProfile: Bluetooth service connected
10-28 08:39:05.831  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:39:05.831  5628  5640 D BluetoothPbap: onBluetoothStateChange: up=true
10-28 08:39:05.832  5818  5818 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-28 08:39:05.833  5818  5818 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-28 08:39:05.835  5628  5639 D BluetoothPan: onBluetoothStateChange on: true
10-28 08:39:05.835  5818  5818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 08:39:05.835  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:39:05.835  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:05.835  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:05.835  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:39:05.835  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:05.835  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:39:05.835  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:39:05.835  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:39:05.836  3064  3077 D BluetoothPan: onBluetoothStateChange on: true
10-28 08:39:05.836  5818  5818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-28 08:39:05.837  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:39:05.837  5818  5818 D ObexServerSockets: Succeed to create listening sockets 
10-28 08:39:05.838  5818  5818 D ObexServerSockets0: startAccept()
10-28 08:39:05.838  5818  5818 D ObexServerSockets0: prepareForNewConnect()
10-28 08:39:05.838  3064  3076 D BluetoothA2dp: onBluetoothStateChange: up=true
10-28 08:39:05.839  5818  5818 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-28 08:39:05.839  5818  5818 D BluetoothSdpJni: SDP Create record success - handle: 0
10-28 08:39:05.839  5818  5857 D ObexServerSockets0: Accepting socket connection...
10-28 08:39:05.839  5818  5858 D ObexServerSockets0: Accepting socket connection...
10-28 08:39:05.839  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
10-28 08:39:05.840  3064  3064 D PanProfile: Bluetooth service connected
10-28 08:39:05.840  3064  3064 D BluetoothA2dp: Proxy object connected
10-28 08:39:05.840  5628  5639 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-28 08:39:05.842  5628  5628 D BluetoothMap: Proxy object connected
10-28 08:39:05.842  5628  5628 D MapProfile: Bluetooth service connected
10-28 08:39:05.842  5628  5628 D BluetoothMap: getConnectedDevices()
10-28 08:39:05.842  3064  3076 D BluetoothPbap: onBluetoothStateChange: up=true
10-28 08:39:05.844  3064  3804 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 08:39:05.844  5628  5640 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-28 08:39:05.844   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-28 08:39:05.845  3704  3736 D BluetoothHeadset: onBluetoothStateChange: up=true
10-28 08:39:05.846  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-28 08:39:05.846   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
10-28 08:39:05.846  5818  5818 D BluetoothMapService: onReceive
10-28 08:39:05.846  5818  5818 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-28 08:39:05.846  5818  5818 D BluetoothMapService: STATE_ON
,10-28 08:39:05.847  5628  5628 D BluetoothPan: BluetoothPAN Proxy object connected
10-28 08:39:05.847  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:05.847  5628  5628 D PanProfile: Bluetooth service connected
10-28 08:39:05.847  5628  5628 D BluetoothInputDevice: Proxy object connected
10-28 08:39:05.848  5628  5628 D HidProfile: Bluetooth service connected
10-28 08:39:05.849  5818  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 08:39:05.850  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:05.851  5818  5859 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-28 08:39:05.851  5818  5859 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-28 08:39:05.854  5628  5628 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-28 08:39:05.860  5628  5628 D DockEventReceiver: finishStartingService: stopping service
10-28 08:39:05.860  3527  3527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-28 08:39:05.866  5818  5861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 08:39:05.866  5628  5628 D BluetoothPbap: Proxy object connected
10-28 08:39:05.866  5628  5628 D PbapServerProfile: Bluetooth service connected
10-28 08:39:05.869  3064  3064 D BluetoothPbap: Proxy object connected
,10-28 08:39:05.869  3064  3064 D PbapServerProfile: Bluetooth service connected
,10-28 08:39:05.879  5818  5818 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-28 08:39:05.879  5818  5818 D ObexServerSockets0: prepareForNewConnect()
,10-28 08:39:05.884  5818  5867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-28 08:39:05.885  5818  5867 I BtOppRfcommListener: Accept thread started.
,10-28 08:39:05.922   930   930 D BluetoothHeadset: Proxy object connected
10-28 08:39:05.922  5628  5640 D BluetoothHeadset: Proxy object connected
10-28 08:39:05.923  3064  3076 D BluetoothHeadset: Proxy object connected
,10-28 08:39:05.923  3064  3064 D HeadsetProfile: Bluetooth service connected
10-28 08:39:05.923   930   930 D BluetoothHeadset: Proxy object connected
10-28 08:39:05.923  3704  3940 D BluetoothHeadset: Proxy object connected
10-28 08:39:05.923   930   930 D BluetoothHeadset: Proxy object connected
10-28 08:39:05.923   930   947 D BluetoothHeadset: Proxy object connected
,10-28 08:39:05.926  5628  5628 D HeadsetProfile: Bluetooth service connected
,10-28 08:39:05.944  3064  3804 D BluetoothHeadset: Proxy object connected
10-28 08:39:05.944  3064  3064 D HeadsetProfile: Bluetooth service connected
,10-28 08:39:05.945  5628  5856 D BluetoothHeadset: Proxy object connected
10-28 08:39:05.945   930   947 D BluetoothHeadset: Proxy object connected
10-28 08:39:05.945  3704  3755 D BluetoothHeadset: Proxy object connected
,10-28 08:39:05.946  5628  5628 D HeadsetProfile: Bluetooth service connected
,10-28 08:39:06.812   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:07.813   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:08.814   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:09.601  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:39:09.601  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:09.601  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:09.601  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-28 08:39:09.601  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:09.601  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:39:09.601  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:39:09.601  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 08:39:09.608  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-28 08:39:09.609  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:09.609  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31cca25 removed from the list
10-28 08:39:09.609  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:39:09.609  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:09.609  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:39:09.612  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-28 08:39:09.612  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67787fa added. We now have 4 listener(s)
10-28 08:39:09.612  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 08:39:09.615   930  3106 D WifiService: setWifiEnabled: false pid=5560, uid=10077
10-28 08:39:09.616   930  3106 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 08:39:09.815   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:10.815   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-28 08:39:14.626  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:14.627   930   940 D WifiService: setWifiEnabled: true pid=5560, uid=10077
,10-28 08:39:14.627   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-28 08:39:14.638   506   925 D SoftapController: Softap fwReload - Ok
,10-28 08:39:14.643   506   925 D CommandListener: Setting iface cfg
,10-28 08:39:14.643   506   925 D CommandListener: Trying to bring down wlan0
,10-28 08:39:14.645   506   925 D CommandListener: Clearing all IP addresses on wlan0
,10-28 08:39:14.652   930  2897 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-28 08:39:15.338   930  2897 D wifi    : set interface wlan0 flags (UP)
,10-28 08:39:15.339   930  2897 I WifiHAL : Initializing wifi
10-28 08:39:15.339   930  2897 I WifiHAL : Creating socket
,10-28 08:39:15.348   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-28 08:39:15.348   930  2897 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-28 08:39:15.348   930  2897 D wifi    : Did set static halHandle = 0x7f763d6e00
10-28 08:39:15.349   930  2897 D wifi    : halHandle = 0x7f763d6e00, mVM = 0x7f92a0d140, mCls = 0x1892
,10-28 08:39:15.349   930  2897 D wifi    : array field set
,10-28 08:39:15.349   930  2897 I WifiNative-HAL: interface[0] = wlan0
10-28 08:39:15.352   930  5872 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547444583936
10-28 08:39:15.352   930  5872 D wifi    : waitForHalEvents called, vm = 0x7f92a0d140, obj = 0x1892, env = 0x7f78c7a200
,10-28 08:39:15.420  5873  5873 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-28 08:39:15.442  5873  5873 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-28 08:39:15.454   930  2897 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-28 08:39:15.464  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:15.465  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:39:15.484  5873  5873 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-28 08:39:15.484  5873  5873 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-28 08:39:15.502   930  2897 D WifiConfigStore: Loading config and enabling all networks 
,10-28 08:39:15.506  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:39:15.506  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:15.506  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:15.506  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:15.506  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:15.506  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:39:15.506  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:39:15.506  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-28 08:39:15.508  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-28 08:39:15.512   930  2897 D WifiConfigStore: loaded 0 passpoint configs
10-28 08:39:15.513   930  2897 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-28 08:39:15.513  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:39:15.513  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:15.513  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:15.513  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:15.513  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:15.513  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-28 08:39:15.513  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-28 08:39:15.513  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-28 08:39:15.513   930  2897 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-28 08:39:15.514   930  2897 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-28 08:39:15.515  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-28 08:39:15.515   930  2897 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-28 08:39:15.516   930  2897 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-28 08:39:15.516   930  2897 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-28 08:39:15.516   930  2897 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-28 08:39:15.520   930  2897 D WifiNative-HAL: Setting external_sim to 1
,10-28 08:39:15.520  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-28 08:39:15.520   930  2897 D wifi    : setting dfs flag to true, 0x7f79431de0
10-28 08:39:15.521   930  2897 D WifiStateMachine: Setting OUI to DA-A1-19
10-28 08:39:15.521   930  2897 D wifi    : setting scan oui 0x7f79431de0
10-28 08:39:15.521   930  2897 D WifiHAL : Sending mac address OUI
,10-28 08:39:15.527   930  2897 E native  : do suspend false
,10-28 08:39:15.540   930  2897 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-28 08:39:15.540   930   930 D RttService: SCAN_AVAILABLE : 3
10-28 08:39:15.541   930  3027 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-28 08:39:15.546   506   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-28 08:39:15.548   506   925 D CommandListener: Setting iface cfg
,10-28 08:39:15.551   930  2894 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '135 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 135 Failed to set address (No such device)'
10-28 08:39:15.551   930  2894 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-28 08:39:15.557   930  2894 D WifiNative-HAL: p2pGetDeviceAddress
,10-28 08:39:15.563   930  2894 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
10-28 08:39:15.564   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=239133 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,10-28 08:39:15.817   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:16.818   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:17.819   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:18.671   930  2897 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-28 08:39:18.672   930  2897 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-28 08:39:18.672   930  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-28 08:39:18.684   930  2897 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-28 08:39:18.718   930  2897 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-28 08:39:18.720  5873  5873 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-28 08:39:18.820   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:19.138  5873  5873 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-28 08:39:19.173  5873  5873 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-28 08:39:19.176  5873  5873 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-28 08:39:19.185   930  2897 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-28 08:39:19.185   930  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-28 08:39:19.185   930  2913 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-28 08:39:19.202   930  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-28 08:39:19.212   506   925 D CommandListener: Setting iface cfg
,10-28 08:39:19.216   930  2897 D WifiStateMachine: Start Dhcp Watchdog 2
,10-28 08:39:19.222   930  5878 D DhcpClient: Receive thread started
,10-28 08:39:19.225   930  2913 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-28 08:39:19.225   930  2897 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-28 08:39:19.225   930  2913 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-28 08:39:19.305   930  2897 E native  : do suspend false
,10-28 08:39:19.316   930  5877 D DhcpClient: Broadcasting DHCPDISCOVER
,10-28 08:39:19.331   930  5878 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172599, domain null
,10-28 08:39:19.331   930  5877 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172599 seconds
10-28 08:39:19.333   930  5877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-28 08:39:19.344   930  5878 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-28 08:39:19.345   930  5877 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-28 08:39:19.347   506   925 D CommandListener: Setting iface cfg
,10-28 08:39:19.350   930  2897 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-28 08:39:19.356   930  5877 D DhcpClient: Scheduling renewal in 86399s
,10-28 08:39:19.364   930  2897 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-28 08:39:19.365   930  2897 D WifiConfigStore: No blacklist allowed without epno enabled
,10-28 08:39:19.365   930  2913 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-28 08:39:19.368   930  2897 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
10-28 08:39:19.371   930  2913 D ConnectivityService: Adding iface wlan0 to network 101
,10-28 08:39:19.425   930  2913 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-28 08:39:19.426   930  2913 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-28 08:39:19.429   930  2913 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-28 08:39:19.431   930  2913 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-28 08:39:19.433   930  2913 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-28 08:39:19.442   930  2913 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-28 08:39:19.446   930  2913 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-28 08:39:19.447   930  2913 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-28 08:39:19.447   930  2897 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-28 08:39:19.447   930  2913 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-28 08:39:19.447   930  2913 D ConnectivityService:    accepting network in place of null
10-28 08:39:19.447   930  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-28 08:39:19.448   930  2913 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-28 08:39:19.471   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 08:39:19.485   930  5876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=243054, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-28 08:39:19.495   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-28 08:39:19.498   930  2913 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-28 08:39:19.498  3669  3836 W QCNEJ   : |CORE| network available: 101
10-28 08:39:19.498   930  2913 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-28 08:39:19.499   930  2913 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-28 08:39:19.500   930   947 D Tethering: MasterInitialState.processMessage what=3
10-28 08:39:19.503  3669  3836 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-28 08:39:19.508  3669  3836 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-28 08:39:19.509  3669  3836 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-28 08:39:19.509  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:39:19.509  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:19.509  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:19.509  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:19.509  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:19.509  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.509  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:39:19.509  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:39:19.512  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 08:39:19.516  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:39:19.516  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:19.516  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:19.516  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:19.516  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:19.516  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.516  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:39:19.516  5560  5560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:39:19.518  5560  5560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 08:39:19.526  4983  4996 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-28 08:39:19.526  4983  4996 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-28 08:39:19.526  4983  4996 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-28 08:39:19.526  4983  4996 E SarControlService: no key has been found,reset the power
10-28 08:39:19.526  4983  5021 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-28 08:39:19.527  4983  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-28 08:39:19.527  4983  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-28 08:39:19.527  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 08:39:19.527  5009  5009 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-28 08:39:19.528  4900  4900 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-28 08:39:19.529  4983  5021 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-28 08:39:19.529  4983  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-28 08:39:19.529  4983  5021 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-28 08:39:19.530  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-28 08:39:19.530  5009  5009 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-28 08:39:19.533  3995  3995 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-28 08:39:19.535  3995  3995 D SystemUpdateService: onCreate
10-28 08:39:19.536  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3cca6f0 HexData = [00000000ec03000000000000ffffffff]
10-28 08:39:19.536  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 08:39:19.537  5009  5023 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-28 08:39:19.537  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-28 08:39:19.537  4983  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-28 08:39:19.541  3995  3995 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-28 08:39:19.543  5009  5023 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3cca6f0 HexData = [00000000ed03000000000000ffffffff]
,10-28 08:39:19.543  5009  5023 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-28 08:39:19.543  5009  5023 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-28 08:39:19.544  5009  5009 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-28 08:39:19.544  4983  4994 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-28 08:39:19.549  3995  3995 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-28 08:39:19.557  3995  5888 I SystemUpdateService: active receiver: enabled
,10-28 08:39:19.559  3995  5345 I iu.UploadsManager: num queued entries: 0
,10-28 08:39:19.560  3995  5345 I iu.UploadsManager: num updated entries: 0
,10-28 08:39:19.564  3995  3995 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-28 08:39:19.565  3995  3995 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-28 08:39:19.567  5707  5707 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-28 08:39:19.569   930  5875 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.211.46,2a00:1450:4016:805::200e
,10-28 08:39:19.571  5707  5707 D SprintDMHelper: simOperator: 
10-28 08:39:19.571  5707  5707 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-28 08:39:19.582  3995  5888 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-28 08:39:19.594  3995  5345 I iu.SyncManager: NEXT; no task
,10-28 08:39:19.606  3995  5888 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-28 08:39:19.606  3995  5888 I SystemUpdateService: now status is 0 (complete)
10-28 08:39:19.606  3995  5888 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-28 08:39:19.606  3995  5888 I SystemUpdateService: file has been verified
,10-28 08:39:19.607  3995  5888 I SystemUpdateService: OTA package size = 21989297
,10-28 08:39:19.616  3995  5888 I SystemUpdateService: showing system update notification
,10-28 08:39:19.625  3995  3995 D SystemUpdateService: onDestroy
,10-28 08:39:19.639   930  5875 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 28 Oct 2016 12:39:19 GMT], X-Android-Received-Millis=[1477658359638], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477658359604]}
,10-28 08:39:19.640   930  2913 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-28 08:39:19.640   930  2913 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-28 08:39:19.640   930  2913 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-28 08:39:19.641   930  2913 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-28 08:39:19.643  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-28 08:39:19.643  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:19.643  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:19.643  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:19.643  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:19.643  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.643  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:39:19.643  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:39:19.645  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.646  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.646  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67787fa removed from the list
10-28 08:39:19.646  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:39:19.646  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.646  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:39:19.650  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-28 08:39:19.651  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-28 08:39:19.653  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4f5b8b4 Bundle[{}]
10-28 08:39:19.653  5560  5606 I io.jxcore.node.LifeCycleMonitor: start: OK
10-28 08:39:19.653  5560  5606 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-28 08:39:19.654  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-28 08:39:19.654  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-28 08:39:19.655  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-28 08:39:19.655  5560  5606 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-28 08:39:19.662  5560  5606 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,10-28 08:39:19.663  5560  5606 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-28 08:39:19.663  5560  5606 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
,10-28 08:39:19.665  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:39:19.665  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1af41ab added. We now have 3 listener(s)
,10-28 08:39:19.667  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-28 08:39:19.667  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.667  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.667  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.668  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e34008 added. We now have 4 listener(s)
10-28 08:39:19.668  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:39:19.668  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-28 08:39:19.671  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 08:39:19.676  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:39:19.676  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:19.676  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:19.676  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:19.676  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:19.676  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.676  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:39:19.676  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:39:19.677  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 08:39:19.677  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:39:19.677  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:39:19.677  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca629c6 added. We now have 4 listener(s)
10-28 08:39:19.678  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:39:19.679  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.679  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.679  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.679  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89e4d87 added. We now have 5 listener(s)
10-28 08:39:19.679  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:39:19.679  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:39:19.679  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:39:19.679  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:39:19.679  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-28 08:39:19.679  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.679  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:39:19.679  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.679  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.679  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1af41ab removed from the list
10-28 08:39:19.679  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:19.679  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.679  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e34008 removed from the list
10-28 08:39:19.682  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:19.682  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:39:19.682  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:39:19.683  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.683  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.683  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.684  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.684  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.684  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.684  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.684  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:39:19.685  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.685  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e34008 not in the list
10-28 08:39:19.685  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.685  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.685  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.686  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.686  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.686  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.686  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:39:19.686  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.686  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.687  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89e4d87 removed from the list
,10-28 08:39:19.687  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-28 08:39:19.687  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.687  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.687  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.687  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.687  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca629c6 removed from the list
10-28 08:39:19.688  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:39:19.688  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47054b4 added. We now have 3 listener(s)
10-28 08:39:19.689  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:39:19.689  4355  5893 I Babel   : connection state changed from DISCONNECTED to CONNECTED
10-28 08:39:19.689  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.690  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.690  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.690  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4db18dd added. We now have 4 listener(s)
10-28 08:39:19.690  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:39:19.691  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-28 08:39:19.694  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 08:39:19.699  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:39:19.699  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:19.699  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:19.699  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:19.699  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:19.699  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.699  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:39:19.699  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:39:19.701  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.701  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-28 08:39:19.701  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:39:19.701  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4883b23 added. We now have 4 listener(s)
10-28 08:39:19.702  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:39:19.702  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.702  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.703  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.703  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180820 added. We now have 5 listener(s)
10-28 08:39:19.703  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:39:19.703  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:19.703  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:39:19.703  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 08:39:19.703  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 08:39:19.703  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:39:19.703  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 08:39:19.705  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:39:19.706  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 08:39:19.706  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 08:39:19.706  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-28 08:39:19.708  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.709  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-28 08:39:19.709  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-28 08:39:19.709  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-28 08:39:19.711  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.711  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 08:39:19.711  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 08:39:19.712  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 08:39:19.712  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-28 08:39:19.712  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.712  5560  5606 D BluetoothAdapter: STATE_ON
,10-28 08:39:19.714  5818  5829 D BtGatt.GattService: registerClient() - UUID=1de21a22-0bb7-4003-b68a-a63a27736c77
10-28 08:39:19.715  5818  5834 D BtGatt.GattService: onClientRegistered() - UUID=1de21a22-0bb7-4003-b68a-a63a27736c77, clientIf=5
,10-28 08:39:19.715  5560  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-28 08:39:19.716  5818  5854 D BtGatt.GattService: start scan with filters
,10-28 08:39:19.718  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-28 08:39:19.719  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.719  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 08:39:19.719  5818  5837 D BtGatt.ScanManager: handling starting scan
10-28 08:39:19.719  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.719  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 08:39:19.719  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 08:39:19.719  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.719  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 08:39:19.719  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 08:39:19.719  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.719  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.719  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-28 08:39:19.720  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 08:39:19.720  5818  5837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e737a1
10-28 08:39:19.720  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.722  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.722  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:39:19.722  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.722  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.722  5560  5606 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-28 08:39:19.722  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.722  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-28 08:39:19.722  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-28 08:39:19.722  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.722  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-28 08:39:19.722  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.722  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-28 08:39:19.724  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.724  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.724  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.724  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.724  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 08:39:19.724  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 08:39:19.725  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 08:39:19.725  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:39:19.725  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.725  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.725  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.725  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 08:39:19.725  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.725  5818  5834 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 08:39:19.725  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.725  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:39:19.726  5818  5837 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-28 08:39:19.726  5818  5829 D BtGatt.GattService: stopScan() - queue size =1
10-28 08:39:19.727  5818  5854 D BtGatt.GattService: unregisterClient() - clientIf=5
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.727  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.728  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 08:39:19.728  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 08:39:19.728  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:39:19.728  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.729  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.729  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:39:19.729  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.729  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.729  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:39:19.729  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:39:19.729  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 08:39:19.729  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.729  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 08:39:19.729  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-28 08:39:19.729  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.729  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.730  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 08:39:19.730  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.730  5818  5834 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 08:39:19.730  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:39:19.731  5818  5837 D BtGatt.ScanManager: Starting BLE batch scan
10-28 08:39:19.731  5818  5837 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-28 08:39:19.731  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.731  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.731  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.731  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.731  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:39:19.732  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 08:39:19.732  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:39:19.732  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:39:19.732  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:39:19.732  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.732  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:39:19.732  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.732  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.732  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47054b4 removed from the list
10-28 08:39:19.732  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.732  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4db18dd removed from the list
10-28 08:39:19.732  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:39:19.732  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.733  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.733  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.733  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.734  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.734  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.734  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.734  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.734  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:39:19.734  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.734  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4db18dd not in the list
10-28 08:39:19.734  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.734  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.734  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.735  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.735  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.735  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.735  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:39:19.735  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.736  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.736  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180820 removed from the list
10-28 08:39:19.736  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:39:19.736  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:39:19.736  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.736  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.736  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.736  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4883b23 removed from the list
10-28 08:39:19.736  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:39:19.736  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c5864c added. We now have 3 listener(s)
,10-28 08:39:19.738  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:39:19.738  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.738  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.738  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.738  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd8695 added. We now have 4 listener(s)
10-28 08:39:19.738  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:39:19.739  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 08:39:19.739  5818  5834 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 08:39:19.739  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.741  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:39:19.744  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:39:19.744  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:19.744  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:19.744  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:19.744  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:19.744  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.744  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:39:19.744  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-28 08:39:19.744  5818  5834 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 08:39:19.744  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:39:19.746  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.746  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:39:19.746  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-28 08:39:19.746  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867eb9b added. We now have 4 listener(s)
10-28 08:39:19.748  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:39:19.748  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.748  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.748  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.748  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eabb38 added. We now have 5 listener(s)
10-28 08:39:19.748  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:39:19.748  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:39:19.749  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:39:19.749  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 08:39:19.749  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 08:39:19.749  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:39:19.749  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 08:39:19.750  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:19.750  5818  5834 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 08:39:19.751  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.751  5818  5837 D BtGatt.ScanManager: stopping BLe Batch
10-28 08:39:19.752  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 08:39:19.752  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-28 08:39:19.752  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 08:39:19.752  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-28 08:39:19.756  5818  5834 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-28 08:39:19.756  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.756  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.756  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-28 08:39:19.756  5818  5837 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-28 08:39:19.756  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-28 08:39:19.757  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-28 08:39:19.760  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.761  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 08:39:19.761  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 08:39:19.761  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 08:39:19.761  5818  5834 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-28 08:39:19.761  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-28 08:39:19.761  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.761  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.762  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:39:19.763  5818  5829 D BtGatt.GattService: registerClient() - UUID=07e6648e-e1d0-46c5-a6e8-3b4db3f55392
10-28 08:39:19.763  5818  5834 D BtGatt.GattService: onClientRegistered() - UUID=07e6648e-e1d0-46c5-a6e8-3b4db3f55392, clientIf=5
,10-28 08:39:19.764  5560  5571 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-28 08:39:19.764  5818  5828 D BtGatt.GattService: start scan with filters
,10-28 08:39:19.766  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-28 08:39:19.766  5818  5837 D BtGatt.ScanManager: handling starting scan
10-28 08:39:19.766  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.766  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 08:39:19.766  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.766  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 08:39:19.766  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 08:39:19.766  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.766  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 08:39:19.766  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 08:39:19.766  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.766  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.766  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-28 08:39:19.767  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 08:39:19.767  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.770  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.770  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:39:19.770  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.770  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.770  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.770  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:39:19.770  5560  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-28 08:39:19.770  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:39:19.770  5818  5834 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 08:39:19.770  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.770  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:39:19.771  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:39:19.771  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:39:19.771  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.771  5818  5837 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-28 08:39:19.771  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-28 08:39:19.771  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.771  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.771  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c5864c removed from the list
10-28 08:39:19.771  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.771  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd8695 removed from the list
10-28 08:39:19.771  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:39:19.771  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:39:19.771  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.772  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-28 08:39:19.772  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.772  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:39:19.772  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.772  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.772  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.772  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.772  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.772  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.772  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:39:19.772  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.773  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.773  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.773  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-28 08:39:19.773  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.773  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd8695 not in the list
10-28 08:39:19.773  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 08:39:19.773  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 08:39:19.773  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 08:39:19.773  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.773  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.773  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.773  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 08:39:19.773  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.775  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:39:19.775  5818  5834 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 08:39:19.775  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.775  5818  5837 D BtGatt.ScanManager: Starting BLE batch scan
10-28 08:39:19.775  5818  5837 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-28 08:39:19.775  5818  5855 D BtGatt.GattService: stopScan() - queue size =1
10-28 08:39:19.776  5818  5829 D BtGatt.GattService: unregisterClient() - clientIf=5
10-28 08:39:19.776  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 08:39:19.776  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.776  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 08:39:19.776  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.776  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.776  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.776  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.776  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 08:39:19.777  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.777  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.777  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.777  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 08:39:19.777  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 08:39:19.779  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.779  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.780  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.780  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:39:19.780  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.780  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.780  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:39:19.780  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.780  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.780  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:39:19.780  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:39:19.780  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 08:39:19.780  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eabb38 removed from the list
10-28 08:39:19.780  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.780  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:39:19.780  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 08:39:19.780  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:39:19.780  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 08:39:19.781  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.780  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.781  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.781  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.781  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 08:39:19.781  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.781  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.781  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@867eb9b removed from the list
10-28 08:39:19.781  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:39:19.781  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2c52e4 added. We now have 3 listener(s)
10-28 08:39:19.782  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.782  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.782  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.782  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.782  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:39:19.783  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:39:19.783  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.783  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.783  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.784  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a78f34d added. We now have 4 listener(s)
10-28 08:39:19.784  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:39:19.784  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 08:39:19.784  5818  5834 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-28 08:39:19.784  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:39:19.787  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-28 08:39:19.789  5818  5834 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 08:39:19.789  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:39:19.792  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:39:19.792  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:19.792  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:19.792  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:19.792  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:19.792  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.792  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:39:19.792  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:39:19.794  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 08:39:19.794  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:39:19.794  5818  5834 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 08:39:19.794  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.794  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:39:19.794  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28e3313 added. We now have 4 listener(s)
10-28 08:39:19.794  5818  5837 D BtGatt.ScanManager: stopping BLe Batch
10-28 08:39:19.795  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:39:19.796  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.796  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.796  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.796  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcdb950 added. We now have 5 listener(s)
10-28 08:39:19.796  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-28 08:39:19.796  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:39:19.796  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-28 08:39:19.796  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-28 08:39:19.796  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:39:19.796  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-28 08:39:19.796  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:19.798  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:19.799  5818  5834 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-28 08:39:19.799  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.800  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-28 08:39:19.800  5818  5837 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-28 08:39:19.800  5560  5606 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-28 08:39:19.800  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-28 08:39:19.802  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.802  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-28 08:39:19.803  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-28 08:39:19.803  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-28 08:39:19.804  5818  5834 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-28 08:39:19.804  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:39:19.805  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.805  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-28 08:39:19.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-28 08:39:19.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-28 08:39:19.806  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-28 08:39:19.806  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.806  5560  5606 D BluetoothAdapter: STATE_ON
,10-28 08:39:19.808  5818  5828 D BtGatt.GattService: registerClient() - UUID=0ae63e6e-6fac-4944-b37c-44d3703dcd30
10-28 08:39:19.809  5818  5834 D BtGatt.GattService: onClientRegistered() - UUID=0ae63e6e-6fac-4944-b37c-44d3703dcd30, clientIf=5
,10-28 08:39:19.809  5560  5570 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-28 08:39:19.809  5818  5854 D BtGatt.GattService: start scan with filters
10-28 08:39:19.811  5818  5837 D BtGatt.ScanManager: handling starting scan
10-28 08:39:19.811  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-28 08:39:19.811  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.811  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-28 08:39:19.812  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.812  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-28 08:39:19.812  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-28 08:39:19.812  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.812  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-28 08:39:19.812  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-28 08:39:19.812  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.812  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.812  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-28 08:39:19.813  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-28 08:39:19.813  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.816  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.816  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-28 08:39:19.816  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.816  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.816  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.817  5818  5834 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-28 08:39:19.817  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:39:19.817  5818  5837 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-28 08:39:19.819  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-28 08:39:19.819  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:39:19.819  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:39:19.820  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:39:19.820  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.820  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-28 08:39:19.820  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.820  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.820  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2c52e4 removed from the list
10-28 08:39:19.820  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.820  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a78f34d removed from the list
10-28 08:39:19.820  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
,10-28 08:39:19.820   534   534 I ServiceManager: Waiting for service AtCmdFwd...
10-28 08:39:19.820  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:39:19.820  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.820  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.820  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.821  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.821  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-28 08:39:19.821  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:39:19.821  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-28 08:39:19.821  5818  5834 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-28 08:39:19.821  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.821  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.821  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:39:19.821  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.821  5818  5837 D BtGatt.ScanManager: Starting BLE batch scan
10-28 08:39:19.821  5818  5837 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-28 08:39:19.822  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.822  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.822  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.822  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.822  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:39:19.822  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.823  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a78f34d not in the list
10-28 08:39:19.823  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-28 08:39:19.823  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-28 08:39:19.823  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-28 08:39:19.823  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.823  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.823  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.823  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-28 08:39:19.823  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.823  5560  5606 D BluetoothAdapter: STATE_ON
10-28 08:39:19.824  5818  5828 D BtGatt.GattService: stopScan() - queue size =1
10-28 08:39:19.824  5818  5829 D BtGatt.GattService: unregisterClient() - clientIf=5
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.825  ,5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.825  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-28 08:39:19.825  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-28 08:39:19.826  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.826  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.826  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.826  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:39:19.826  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.827  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.827  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:39:19.827  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.827  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.827  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcdb950 removed from the list
10-28 08:39:19.827  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:39:19.827  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.827  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:39:19.827  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.827  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.827  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28e3313 removed from the list
10-28 08:39:19.828  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:39:19.828  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:39:19.828  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dd1a7c added. We now have 3 listener(s)
10-28 08:39:19.828  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-28 08:39:19.828  5560  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-28 08:39:19.828  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.828  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-28 08:39:19.828  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-28 08:39:19.828  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.828  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.828  5560  5560 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-28 08:39:19.828  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.829  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:39:19.829  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.829  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.829  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.829  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.829  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.829  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1e3f05 added. We now have 4 listener(s)
10-28 08:39:19.829  5560  5560 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,10-28 08:39:19.829  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:39:19.829  5560  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-28 08:39:19.829  5560  5560 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-28 08:39:19.830  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-28 08:39:19.830  5818  5834 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-28 08:39:19.830  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.832  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-28 08:39:19.835  5818  5834 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-28 08:39:19.835  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.837  5560  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-28 08:39:19.837  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-28 08:39:19.837  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-28 08:39:19.837  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-28 08:39:19.837  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-28 08:39:19.837  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-28 08:39:19.837  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-28 08:39:19.837  5560  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-28 08:39:19.839  5560  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-28 08:39:19.840  5560  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
10-28 08:39:19.840  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-28 08:39:19.840  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@456f18b added. We now have 4 listener(s)
10-28 08:39:19.841  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-28 08:39:19.841  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-28 08:39:19.841  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-28 08:39:19.841  5818  5834 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-28 08:39:19.841  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-28 08:39:19.841  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31f6268 added. We now have 5 listener(s)
10-28 08:39:19.841  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.841  5560  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-28 08:39:19.842  5818  5837 D BtGatt.ScanManager: stopping BLe Batch
10-28 08:39:19.842  5560  5606 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-28 08:39:19.842  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:39:19.842  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:19.842  5560  5606 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-28 08:39:19.842  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:39:19.842  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.842  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-28 08:39:19.842  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.842  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.842  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dd1a7c removed from the list
,10-28 08:39:19.842  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.842  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1e3f05 removed from the list
10-28 08:39:19.844  5560  5560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-28 08:39:19.844  5560  5606 D io.jxcore.node.ConnectivityMonitor: stop
10-28 08:39:19.844  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-28 08:39:19.846  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-28 08:39:19.846  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.846  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.846  5818  5834 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-28 08:39:19.847  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-28 08:39:19.847  5818  5837 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-28 08:39:19.847  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.847  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.847  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.847  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.847  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:39:19.847  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.847  5560  5606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1e3f05 not in the list
10-28 08:39:19.847  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.847  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.847  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.848  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.848  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-28 08:39:19.848  5560  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-28 08:39:19.848  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-28 08:39:19.848  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-28 08:39:19.848  5560  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-28 08:39:19.848  5560  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31f6268 removed from the list
10-28 08:39:19.848  5560  5606 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-28 08:39:19.848  5560  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-28 08:39:19.848  5560  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-28 08:39:19.849  5560  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-28 08:39:19.849  5560  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-28 08:39:19.849  5560  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@456f18b removed from the list
10-28 08:39:19.849  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-28 08:39:19.849  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-28 08:39:19.849  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-28 08:39:19.850  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:39:19.850  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-28 08:39:19.850  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-28 08:39:19.851  5818  5834 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-28 08:39:19.851  5818  5834 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-28 08:39:20.232  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 08:39:20.282  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 08:39:20.330  5560  5560 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-28 08:39:20.499   930  2913 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-28 08:39:20.820   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-28 08:39:21.996  5560  5900 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-28 08:39:21.996  5560  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 08:39:22.246   930  2913 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-28 08:39:22.785  5560  5900 W !!      : call onHalfStreamCopied
,10-28 08:39:22.785  5560  5900 I testCopyDataAndClose: closing input stream
,10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-28 08:39:23.566  5560  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-28 08:39:27.379  5560  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-28 08:39:27.379  5560  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 08:39:27.452   930  2913 D ConnectivityService: handlePromptUnvalidated 101
,10-28 08:39:29.379  5560  5606 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
10-28 08:39:29.379  5560  5606 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 08:39:29.379  5560  5606 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,10-28 08:39:29.472  5560  5901 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-28 08:39:29.472  5560  5901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-28 08:39:29.472  5560  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,10-28 08:39:29.520  5560  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-28 08:39:29.520  5560  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 08:39:30.568   930  2897 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,10-28 08:39:30.821   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-28 08:39:31.158  5560  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-28 08:39:31.823   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:32.824   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:33.826   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:34.827   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:34.904  5560  5903 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-28 08:39:34.904  5560  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-28 08:39:34.904  5560  5903 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
10-28 08:39:34.904  5560  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-28 08:39:34.905  5560  5903 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-28 08:39:34.905  5560  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-28 08:39:34.905  5560  5903 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-28 08:39:34.905  5560  5903 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-28 08:39:34.905  5560  5903 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-28 08:39:34.905  5560  5903 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-28 08:39:34.905  5560  5903 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-28 08:39:34.906  5560  5903 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-28 08:39:34.906  5560  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-28 08:39:34.907  5560  5606 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-28 08:39:34.910  5560  5904 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-28 08:39:34.910  5560  5904 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-28 08:39:34.910  5560  5904 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
10-28 08:39:34.911  5560  5904 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-28 08:39:34.911  5560  5904 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-28 08:39:34.911  5560  5904 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-28 08:39:34.911  5560  5904 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-28 08:39:34.911  5560  5904 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-28 08:39:34.914  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-28 08:39:34.914  5560  5606 I jxcore-log: 
10-28 08:39:34.915  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-28 08:39:34.915  5560  5606 I jxcore-log: 
10-28 08:39:34.915  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-28 08:39:34.915  5560  5606 I jxcore-log: 
,10-28 08:39:34.915  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-28 08:39:34.915  5560  5606 I jxcore-log: 
,10-28 08:39:34.915  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG UnitTest_app: 'Total duration:  90826'
10-28 08:39:34.915  5560  5606 I jxcore-log: 
10-28 08:39:34.917  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-28 08:39:34.917  5560  5606 I jxcore-log: 
,10-28 08:39:34.920  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.920  5560  5606 I jxcore-log: 
10-28 08:39:34.921  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.921  5560  5606 I jxcore-log: 
,10-28 08:39:34.922  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.922  5560  5606 I jxcore-log: 
10-28 08:39:34.922  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.922  5560  5606 I jxcore-log: 
10-28 08:39:34.922  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-28 08:39:34.922  5560  5606 I jxcore-log: 
10-28 08:39:34.923  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 08:39:34.923  5560  5606 I jxcore-log: 
10-28 08:39:34.923  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.923  5560  5606 I jxcore-log: 
10-28 08:39:34.923  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.923  5560  5606 I jxcore-log: 
10-28 08:39:34.923  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-28 08:39:34.923  5560  5606 I jxcore-log: 
10-28 08:39:34.924  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 08:39:34.924  5560  5606 I jxcore-log: 
,10-28 08:39:34.924  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 08:39:34.924  5560  5606 I jxcore-log: 
10-28 08:39:34.924  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.924  5560  5606 I jxcore-log: 
10-28 08:39:34.924  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.924  5560  5606 I jxcore-log: 
10-28 08:39:34.925  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 08:39:34.925  5560  5606 I jxcore-log: 
10-28 08:39:34.925  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.925  5560  5606 I jxcore-log: 
10-28 08:39:34.925  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 08:39:34.925  5560  5606 I jxcore-log: 
10-28 08:39:34.925  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 08:39:34.925  5560  5606 I jxcore-log: 
10-28 08:39:34.926  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.926  5560  5606 I jxcore-log: 
10-28 08:39:34.926  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.926  5560  5606 I jxcore-log: 
,10-28 08:39:34.926  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.926  5560  5606 I jxcore-log: 
10-28 08:39:34.926  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 08:39:34.926  5560  5606 I jxcore-log: 
10-28 08:39:34.927  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 08:39:34.927  5560  5606 I jxcore-log: 
,10-28 08:39:34.927  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-28 08:39:34.927  5560  5606 I jxcore-log: 
10-28 08:39:34.928  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.928  5560  5606 I jxcore-log: 
10-28 08:39:34.929  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.929  5560  5606 I jxcore-log: 
10-28 08:39:34.929  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.929  5560  5606 I jxcore-log: 
,10-28 08:39:34.929  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.929  5560  5606 I jxcore-log: 
10-28 08:39:34.929  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.929  5560  5606 I jxcore-log: 
10-28 08:39:34.930  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.930  5560  5606 I jxcore-log: 
10-28 08:39:34.930  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.930  5560  5606 I jxcore-log: 
10-28 08:39:34.930  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.930  5560  5606 I jxcore-log: 
,10-28 08:39:34.930  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.930  5560  5606 I jxcore-log: 
10-28 08:39:34.930  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.930  5560  5606 I jxcore-log: 
10-28 08:39:34.931  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.931  5560  5606 I jxcore-log: 
10-28 08:39:34.931  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-28 08:39:34.931  5560  5606 I jxcore-log: 
10-28 08:39:34.931  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-28 08:39:34.931  5560  5606 I jxcore-log: 
10-28 08:39:34.931  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-28 08:39:34.931  5560  5606 I jxcore-log: 
,10-28 08:39:34.931  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.931  5560  5606 I jxcore-log: 
10-28 08:39:34.932  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.932  5560  5606 I jxcore-log: 
10-28 08:39:34.932  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.932  5560  5606 I jxcore-log: 
10-28 08:39:34.932  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.932  5560  5606 I jxcore-log: 
10-28 08:39:34.932  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.932  5560  5606 I jxcore-log: 
10-28 08:39:34.933  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-28 08:39:34.933  5560  5606 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-28 08:39:34.933  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.933  5560  5606 I jxcore-log: 
,10-28 08:39:34.933  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.933  5560  5606 I jxcore-log: 
10-28 08:39:34.933  5560  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-28 08:39:34.933  5560  5606 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-28 08:39:34.933  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-28 08:39:34.933  5560  5606 I jxcore-log: 
10-28 08:39:34.934  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 08:39:34.934  5560  5606 I jxcore-log: 
10-28 08:39:34.934  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 08:39:34.934  5560  5606 I jxcore-log: 
,10-28 08:39:34.934  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-28 08:39:34.934  5560  5606 I jxcore-log: 
10-28 08:39:34.939  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-28 08:39:34.939  5560  5606 I jxcore-log: 
10-28 08:39:34.940  5560  5606 I jxcore-log: 2016-10-28 12:39:34 - WARN testUtils: 'myNameCallback not set!'
10-28 08:39:34.940  5560  5606 I jxcore-log: 
10-28 08:39:34.943  5560  5560 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-28 08:39:35.828   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-28 08:39:37.048  5560  5606 I jxcore-log: 2016-10-28 12:39:37 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
10-28 08:39:37.048  5560  5606 I jxcore-log: 
,10-28 08:39:37.050  5560  5606 I jxcore-log: 2016-10-28 12:39:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-28 08:39:37.050  5560  5606 I jxcore-log: 
,10-28 08:39:37.401  5560  5606 I jxcore-log: 2016-10-28 12:39:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-28 08:39:37.401  5560  5606 I jxcore-log: 
,10-28 08:39:37.414  5560  5606 I jxcore-log: 2016-10-28 12:39:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-28 08:39:37.414  5560  5606 I jxcore-log: 
,10-28 08:39:38.560  5560  5606 I jxcore-log: 2016-10-28 12:39:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-28 08:39:38.560  5560  5606 I jxcore-log: 
,10-28 08:39:38.758  5560  5606 I jxcore-log: 2016-10-28 12:39:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-28 08:39:38.758  5560  5606 I jxcore-log: 
,10-28 08:39:38.763  5560  5606 I jxcore-log: 2016-10-28 12:39:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-28 08:39:38.763  5560  5606 I jxcore-log: 
,10-28 08:39:38.768  5560  5606 I jxcore-log: 2016-10-28 12:39:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-28 08:39:38.768  5560  5606 I jxcore-log: 
,10-28 08:39:39.268  5560  5606 I jxcore-log: 2016-10-28 12:39:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-28 08:39:39.268  5560  5606 I jxcore-log: 
,10-28 08:39:39.315  5560  5606 I jxcore-log: 2016-10-28 12:39:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-28 08:39:39.315  5560  5606 I jxcore-log: 
,10-28 08:39:39.329  5560  5606 I jxcore-log: 2016-10-28 12:39:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-28 08:39:39.329  5560  5606 I jxcore-log: 
,10-28 08:39:39.333  5560  5606 I jxcore-log: 2016-10-28 12:39:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-28 08:39:39.333  5560  5606 I jxcore-log: 
,10-28 08:39:39.631  5560  5606 I jxcore-log: 2016-10-28 12:39:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-28 08:39:39.631  5560  5606 I jxcore-log: 
,10-28 08:39:39.763  5560  5606 I jxcore-log: 2016-10-28 12:39:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-28 08:39:39.763  5560  5606 I jxcore-log: 
,10-28 08:39:40.151  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-28 08:39:40.151  5560  5606 I jxcore-log: 
,10-28 08:39:40.160  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-28 08:39:40.160  5560  5606 I jxcore-log: 
,10-28 08:39:40.164  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-28 08:39:40.164  5560  5606 I jxcore-log: 
,10-28 08:39:40.169  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-28 08:39:40.169  5560  5606 I jxcore-log: 
,10-28 08:39:40.174  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-28 08:39:40.174  5560  5606 I jxcore-log: 
,10-28 08:39:40.202  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-28 08:39:40.202  5560  5606 I jxcore-log: 
,10-28 08:39:40.239  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-28 08:39:40.239  5560  5606 I jxcore-log: 
,10-28 08:39:40.246  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-28 08:39:40.246  5560  5606 I jxcore-log: 
,10-28 08:39:40.253  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-28 08:39:40.253  5560  5606 I jxcore-log: 
,10-28 08:39:40.268  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-28 08:39:40.268  5560  5606 I jxcore-log: 
,10-28 08:39:40.273  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-28 08:39:40.273  5560  5606 I jxcore-log: 
,10-28 08:39:40.279  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-28 08:39:40.279  5560  5606 I jxcore-log: 
,10-28 08:39:40.284  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-28 08:39:40.284  5560  5606 I jxcore-log: 
,10-28 08:39:40.297  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-28 08:39:40.297  5560  5606 I jxcore-log: 
,10-28 08:39:40.303  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-28 08:39:40.303  5560  5606 I jxcore-log: 
,10-28 08:39:40.325  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-28 08:39:40.325  5560  5606 I jxcore-log: 
,10-28 08:39:40.336  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-28 08:39:40.336  5560  5606 I jxcore-log: 
,10-28 08:39:40.348  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-28 08:39:40.348  5560  5606 I jxcore-log: 
,10-28 08:39:40.358  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-28 08:39:40.358  5560  5606 I jxcore-log: 
,10-28 08:39:40.371  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-28 08:39:40.371  5560  5606 I jxcore-log: 
,10-28 08:39:40.382  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-28 08:39:40.382  5560  5606 I jxcore-log: 
,10-28 08:39:40.389  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-28 08:39:40.389  5560  5606 I jxcore-log: 
,10-28 08:39:40.411  5560  5606 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-28 08:39:40.412  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - INFO testUtils: 'BLE multiple advertisement supported'
10-28 08:39:40.412  5560  5606 I jxcore-log: 
,10-28 08:39:40.573  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:40.573  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:40.573  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:40.573  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:40.573  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:40.573  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:40.573  5560  5606 I jxcore-log: 
,10-28 08:39:40.870  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:40.870  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:40.870  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:40.870  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:40.870  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:40.870  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:40.870  5560  5606 I jxcore-log: 
,10-28 08:39:40.874  5560  5606 I jxcore-log: 2016-10-28 12:39:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:40.874  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:40.874  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:40.874  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:40.874  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:40.874  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:40.874  5560  5606 I jxcore-log: 
,10-28 08:39:41.377  5560  5606 I jxcore-log: 2016-10-28 12:39:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:41.377  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:41.377  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:41.377  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:41.377  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:41.377  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:41.377  5560  5606 I jxcore-log: 
,10-28 08:39:41.381  5560  5606 I jxcore-log: 2016-10-28 12:39:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:41.381  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:41.381  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:41.381  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:41.381  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:41.381  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:41.381  5560  5606 I jxcore-log: 
,10-28 08:39:42.000  5560  5606 I jxcore-log: 2016-10-28 12:39:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:42.000  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:42.000  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:42.000  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:42.000  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:42.000  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:42.000  5560  5606 I jxcore-log: 
,10-28 08:39:42.005  5560  5606 I jxcore-log: 2016-10-28 12:39:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:42.005  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:42.005  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:42.005  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:42.005  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:42.005  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:42.005  5560  5606 I jxcore-log: 
,10-28 08:39:43.124  5560  5606 I jxcore-log: 2016-10-28 12:39:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:43.124  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:43.124  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:43.124  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:43.124  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:43.124  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:43.124  5560  5606 I jxcore-log: 
,10-28 08:39:43.134  5560  5606 I jxcore-log: 2016-10-28 12:39:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:43.134  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:43.134  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:43.134  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:43.134  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:43.134  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:43.134  5560  5606 I jxcore-log: 
,10-28 08:39:43.382   930  2913 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-28 08:39:44.176  5560  5606 I jxcore-log: 2016-10-28 12:39:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:44.176  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:44.176  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:44.176  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:44.176  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:44.176  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:44.176  5560  5606 I jxcore-log: 
,10-28 08:39:44.181  5560  5606 I jxcore-log: 2016-10-28 12:39:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:44.181  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:44.181  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:44.181  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:44.181  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:44.181  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:44.181  5560  5606 I jxcore-log: 
,10-28 08:39:45.210  5560  5606 I jxcore-log: 2016-10-28 12:39:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:45.210  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:45.210  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:45.210  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:45.210  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:45.210  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:45.210  5560  5606 I jxcore-log: 
,10-28 08:39:45.214  5560  5606 I jxcore-log: 2016-10-28 12:39:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:45.214  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:45.214  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:45.214  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:45.214  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:45.214  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:45.214  5560  5606 I jxcore-log: 
,10-28 08:39:46.247  5560  5606 I jxcore-log: 2016-10-28 12:39:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:46.247  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:46.247  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:46.247  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:46.247  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:46.247  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:46.247  5560  5606 I jxcore-log: 
,10-28 08:39:46.250  5560  5606 I jxcore-log: 2016-10-28 12:39:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:46.250  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:46.250  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:46.250  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:46.250  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:46.250  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:46.250  5560  5606 I jxcore-log: 
,10-28 08:39:46.395   930  2913 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-28 08:39:47.283  5560  5606 I jxcore-log: 2016-10-28 12:39:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:47.283  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:47.283  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:47.283  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:47.283  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:47.283  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:47.283  5560  5606 I jxcore-log: 
,10-28 08:39:47.287  5560  5606 I jxcore-log: 2016-10-28 12:39:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:47.287  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:47.287  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:47.287  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:47.287  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:47.287  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:47.287  5560  5606 I jxcore-log: 
,10-28 08:39:48.318  5560  5606 I jxcore-log: 2016-10-28 12:39:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:48.318  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:48.318  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:48.318  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:48.318  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:48.318  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:48.318  5560  5606 I jxcore-log: 
,10-28 08:39:48.322  5560  5606 I jxcore-log: 2016-10-28 12:39:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:48.322  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:48.322  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:48.322  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:48.322  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:48.322  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:48.322  5560  5606 I jxcore-log: 
,10-28 08:39:48.768   930  5876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272337, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-28 08:39:49.386  5560  5606 I jxcore-log: 2016-10-28 12:39:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:49.386  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:49.386  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:49.386  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:49.386  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:49.386  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:49.386  5560  5606 I jxcore-log: 
,10-28 08:39:49.391  5560  5606 I jxcore-log: 2016-10-28 12:39:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:49.391  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:49.391  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:49.391  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:49.391  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:49.391  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:49.391  5560  5606 I jxcore-log: 
,10-28 08:39:50.424  5560  5606 I jxcore-log: 2016-10-28 12:39:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:50.424  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:50.424  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:50.424  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:50.424  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:50.424  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:50.424  5560  5606 I jxcore-log: 
,10-28 08:39:50.429  5560  5606 I jxcore-log: 2016-10-28 12:39:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:50.429  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:50.429  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:50.429  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:50.429  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:50.429  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:50.429  5560  5606 I jxcore-log: 
,10-28 08:39:50.829   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:51.458  5560  5606 I jxcore-log: 2016-10-28 12:39:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:51.458  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:51.458  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:51.458  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:51.458  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:51.458  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:51.458  5560  5606 I jxcore-log: 
,10-28 08:39:51.463  5560  5606 I jxcore-log: 2016-10-28 12:39:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:51.463  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:51.463  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:51.463  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:51.463  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:51.463  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:51.463  5560  5606 I jxcore-log: 
,10-28 08:39:51.831   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:52.493  5560  5606 I jxcore-log: 2016-10-28 12:39:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:52.493  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:52.493  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:52.493  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:52.493  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:52.493  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:52.493  5560  5606 I jxcore-log: 
,10-28 08:39:52.499  5560  5606 I jxcore-log: 2016-10-28 12:39:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:52.499  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:52.499  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:52.499  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:52.499  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:52.499  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:52.499  5560  5606 I jxcore-log: 
,10-28 08:39:52.832   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:53.526  5560  5606 I jxcore-log: 2016-10-28 12:39:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:53.526  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:53.526  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:53.526  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:53.526  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:53.526  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:53.526  5560  5606 I jxcore-log: 
,10-28 08:39:53.530  5560  5606 I jxcore-log: 2016-10-28 12:39:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:53.530  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:53.530  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:53.530  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:53.530  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:53.530  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:53.530  5560  5606 I jxcore-log: 
,10-28 08:39:53.834   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:54.375   930  5876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=277944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,10-28 08:39:54.556  5560  5606 I jxcore-log: 2016-10-28 12:39:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-28 08:39:54.556  5560  5606 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-28 08:39:54.556  5560  5606 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-28 08:39:54.556  5560  5606 I jxcore-log: emit@events.js:82:1
10-28 08:39:54.556  5560  5606 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-28 08:39:54.556  5560  5606 I jxcore-log: emit@events.js:82:1'
10-28 08:39:54.556  5560  5606 I jxcore-log: 
,10-28 08:39:54.566  5560  5606 E jxcore  : Error!: error is undefined
10-28 08:39:54.566  5560  5606 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"221","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:221:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-28 08:39:54.572  5560  5606 I jxcore-log: 2016-10-28 12:39:54 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-28 08:39:54.572  5560  5606 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:221:1
10-28 08:39:54.572  5560  5606 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-28 08:39:54.572  5560  5606 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-28 08:39:54.572  5560  5606 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-28 08:39:54.572  5560  5606 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-28 08:39:54.572  5560  5606 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-28 08:39:54.572  5560  5606 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-28 08:39:54.573  5560  5606 I jxcore-log: 2016-10-28 12:39:54 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-28 08:39:54.573  5560  5606 I jxcore-log: 
10-28 08:39:54.575  5560  5606 E jxcore-log: TypeError: 
,10-28 08:39:54.575  5560  5606 E jxcore-log: error is undefined
10-28 08:39:54.575  5560  5606 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 221:0)
10-28 08:39:54.575  5560  5606 E jxcore-log: 
,10-28 08:39:54.669   930  3357 D GraphicsStats: Buffer count: 2
10-28 08:39:54.670   930  3872 I WindowState: WIN DEATH: Window{525d71e u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-28 08:39:54.669   930  2908 D WifiService: Client connection lost with reason: 4
,10-28 08:39:54.682   526   526 I Zygote  : Process 5560 exited cleanly (139)
,10-28 08:39:54.685   930  3728 I ActivityManager: Process com.test.thalitest (pid 5560) has died
,10-28 08:39:54.700   930  3728 I ActivityManager: Start proc 5907:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-28 08:39:54.834   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-28 08:39:55.032   930  3357 I WindowManager: Screenshot max retries 4 of Token{8984940 ActivityRecord{b0a4cc3 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{afa8d51 u0 Starting com.test.thalitest} drawState=4
,10-28 08:39:55.077  5905  5905 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-28 08:39:55.081  5907  5907 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-28 08:39:55.093  5905  5905 D AndroidRuntime: CheckJNI is OFF
,10-28 08:39:55.098  5907  5907 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-28 08:39:55.104  5907  5907 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8671-8673)
,10-28 08:39:55.104  5907  5907 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-28 08:39:55.112  5907  5907 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6a06469}
,10-28 08:39:55.113  5907  5907 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-28 08:39:55.113  5907  5907 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-28 08:39:55.116  5907  5907 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-28 08:39:55.117  5907  5907 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-28 08:39:55.119  5905  5905 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-28 08:39:55.128  5907  5907 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-28 08:39:55.136  5907  5907 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-28 08:39:55.136  5907  5907 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-28 08:39:55.136  5907  5907 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-28 08:39:55.136  5907  5907 I Adreno  : Build Date                       : 12/06/15
10-28 08:39:55.136  5907  5907 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-28 08:39:55.136  5907  5907 I Adreno  : Local Branch                     : mybranch17112971
10-28 08:39:55.136  5907  5907 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-28 08:39:55.136  5907  5907 I Adreno  : Remote Branch                    : NONE
10-28 08:39:55.136  5907  5907 I Adreno  : Reconstruct Branch               : NOTHING
,10-28 08:39:55.143  5905  5905 I Radio-JNI: register_android_hardware_Radio DONE
,10-28 08:39:55.158  5905  5905 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-28 08:39:55.163   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
10-28 08:39:55.164   930   943 I ActivityManager: Killing 5907:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-28 08:39:55.269   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-28 08:39:55.270   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-28 08:39:55.272   930   943 E ActivityManager: Failure starting process com.test.thalitest
10-28 08:39:55.272   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-28 08:39:55.272   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:39:55.272   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:39:55.272   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-28 08:39:55.272   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-28 08:39:55.275   930   953 I art     : Starting a blocking GC Explicit
10-28 08:39:55.275   930   943 I ActivityManager:   Force finishing activity ActivityRecord{b0a4cc3 u0 com.test.thalitest/.MainActivity t2}
,10-28 08:39:55.291   930   948 W WindowManager: Failed looking up window
10-28 08:39:55.291   930   948 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@e93c278 does not exist
10-28 08:39:55.291   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-28 08:39:55.291   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-28 08:39:55.291   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-28 08:39:55.291   930   948 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-28 08:39:55.291   930   948 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-28 08:39:55.291   930   948 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-28 08:39:55.291   930   948 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-28 08:39:55.291   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:39:55.291   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:39:55.291   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-28 08:39:55.291   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-28 08:39:55.292   930  3766 W ActivityManager: Spurious death for ProcessRecord{a7e8e24 0:com.test.thalitest/u0a77}, curProc for 5907: null
,10-28 08:39:55.374   930   953 I art     : Explicit concurrent mark sweep GC freed 53896(3MB) AllocSpace objects, 15(464KB) LOS objects, 33% free, 28MB/43MB, paused 1.577ms total 98.944ms
,10-28 08:39:55.397   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-28 08:39:55.401  5905  5905 I art     : System.exit called, status: 0
,10-28 08:39:55.401  5905  5905 I AndroidRuntime: VM exiting with result code 0.
,10-28 08:39:55.424   930   953 I ActivityManager: Start proc 5941:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
10-28 08:39:55.424   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-28 08:39:55.430   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-28 08:39:55.435  5818  5818 D BluetoothMapAppObserver: onReceive
10-28 08:39:55.435  5818  5818 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-28 08:39:55.438  3607  3607 I Keyboard.Facilitator: resetDictionaries() : en_US
10-28 08:39:55.439  3875  4078 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-28 08:39:55.454   930  2887 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-28 08:39:55.473  3607  5954 I Keyboard.Facilitator.DecoderInitializer: run()
,10-28 08:39:55.482  3343  5955 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-28 08:39:55.496  3607  5954 I Decoder : createOrResetDecoder
,10-28 08:39:55.501    17    17 W kworker/2:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-28 08:39:55.508    17    17 W kworker/2:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-28 08:39:55.519  3704  3704 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-28 08:39:55.531    17    17 W kworker/2:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-28 08:39:55.538   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-28 08:39:55.548  3527  3527 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,10-28 08:39:55.549  3527  3527 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
10-28 08:39:55.551  3527  3527 E AndroidRuntime: FATAL EXCEPTION: main
10-28 08:39:55.551  3527  3527 E AndroidRuntime: Process: com.google.process.gapps, PID: 3527
10-28 08:39:55.551  3527  3527 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-28 08:39:55.551  3527  3527 E AndroidRuntime: 	... 8 more
10-28 08:39:55.554   930   942 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
10-28 08:39:55.555   930   942 E PackageManager: Failed to write settings, restoring backup
10-28 08:39:55.555   930   942 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-28 08:39:55.555   930   942 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-28 08:39:55.555   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-28 08:39:55.555   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-28 08:39:55.555   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-28 08:39:55.555   930   942 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:39:55.555   930   942 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:39:55.555   930   942 E PackageManager: 	at android.os.HandlerThread,.run(HandlerThread.java:61)
10-28 08:39:55.559  3743  3884 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
10-28 08:39:55.559  3527  3527 I Process : Sending signal. PID: 3527 SIG: 9
10-28 08:39:55.561  3343  3369 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj5C2FED955) - 
10-28 08:39:55.561   930  5960 E DropBoxManagerService: Can't write: system_app_crash
10-28 08:39:55.561   930  5960 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-28 08:39:55.561   930  5960 E DropBoxManagerService: 	... 5 more
10-28 08:39:55.561   930   943 E DropBoxManagerService: Can't write: system_server_wtf
10-28 08:39:55.561   930   943 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-28 08:39:55.561   930   943 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-28 08:39:55.561   930   943 E DropBoxManagerService: 	... 13 more
10-28 08:39:55.575   930  3541 I ActivityManager: Start proc 5961:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
10-28 08:39:55.576  3743  3884 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-28 08:39:55.576  3743  3884 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3743
10-28 08:39:55.576  3743  3884 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:39:55.576  3743  3884 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-28 08:39:55.577   930   943 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2708)
10-28 08:39:55.577   930   943 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
10-28 08:39:55.577   930   943 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-28 08:39:55.577   930   943 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-28 08:39:55.588  3343  5955 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
10-28 08:39:55.589  3343  5955 I Process : Sending signal. PID: 3343 SIG: 9
,10-28 08:39:55.602   930  2908 D WifiService: Client connection lost with reason: 4
10-28 08:39:55.605   930   943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
10-28 08:39:55.605   930   943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
10-28 08:39:55.605   930   943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 20999ms
10-28 08:39:55.617   930   943 I ActivityManager: Start proc 5973:com.google.process.gapps/u0a12 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
10-28 08:39:55.621   930  3106 W ActivityManager: Spurious death for ProcessRecord{3919512 5973:com.google.process.gapps/u0a12}, curProc for 3527: null
10-28 08:39:55.626   930  3705 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-28 08:39:55.627   930  5981 E DropBoxManagerService: Can't write: system_app_crash
10-28 08:39:55.627   930  5981 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-28 08:39:55.627   930  5981 E DropBoxManagerService: 	... 5 more
,10-28 08:39:55.633  3743  3884 I Process : Sending signal. PID: 3743 SIG: 9
,10-28 08:39:55.655   930  2886 W InputDispatcher: channel '4805894 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-28 08:39:55.655   930  2886 E InputDispatcher: channel '4805894 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-28 08:39:55.661   930  3872 D GraphicsStats: Buffer count: 1
,10-28 08:39:55.661   930   940 I WindowState: WIN DEATH: Window{4805894 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,10-28 08:39:55.661   930   940 W InputDispatcher: Attempted to unregister already unregistered input channel '4805894 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-28 08:39:55.672   930  3872 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3743) has died
10-28 08:39:55.672   930  3872 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 30933ms
,10-28 08:39:55.673   930  3872 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-28 08:39:55.690   930   943 I ActivityManager: Start proc 5986:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-28 08:39:55.697   930  3766 I ActivityManager: Process android.process.acore (pid 3343) has died
,10-28 08:39:55.697   930  3766 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-28 08:39:55.835   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-28 08:39:55.910   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
