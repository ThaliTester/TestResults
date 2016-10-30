#### Test 914795746e6bc70_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-29 21:23:24.515  5551  5596 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
10-29 21:23:24.549  3696  4889 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
10-29 21:23:24.555  3696  3696 I ConfigFetchService: fetch service done; releasing wakelock
10-29 21:23:24.557  3696  3696 I ConfigFetchService: stopping self
10-29 21:23:24.663  3696  4889 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
10-29 21:23:24.678  5551  5596 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
10-29 21:23:24.715  5551  5596 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,10-29 21:23:26.281  5609  5609 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-29 21:23:26.286  5609  5609 D AndroidRuntime: CheckJNI is OFF
10-29 21:23:26.311  5609  5609 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-29 21:23:26.354  5609  5609 I Radio-JNI: register_android_hardware_Radio DONE
10-29 21:23:26.369  5609  5609 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-29 21:23:26.382   927   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-29 21:23:26.430   927   938 I ActivityManager: Start proc 5618:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-29 21:23:26.435  5609  5609 D AndroidRuntime: Shutting down VM
,10-29 21:23:26.772   927  3856 I WindowManager: Screenshot max retries 4 of Token{cf74d68 ActivityRecord{e3fa88b u0 com.test.thalitest/.MainActivity t2}} appWin=Window{c229e03 u0 Starting com.test.thalitest} drawState=2
,10-29 21:23:26.869  5618  5618 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-29 21:23:26.902  5618  5618 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-29 21:23:26.973  5618  5618 I LibraryLoader: Time to load native libraries: 66 ms (timestamps 8022-8088)
,10-29 21:23:26.973  5618  5618 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-29 21:23:27.000  5618  5618 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {965feda}
,10-29 21:23:27.001  5618  5618 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-29 21:23:27.001  5618  5618 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-29 21:23:27.007  5618  5618 I BrowserStartupController: Initializing chromium process, singleProcess=true,
10-29 21:23:27.009  5618  5618 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-29 21:23:27.055  5618  5618 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-29 21:23:27.072  5618  5618 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-29 21:23:27.072  5618  5618 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-29 21:23:27.072  5618  5618 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-29 21:23:27.072  5618  5618 I Adreno  : Build Date                       : 12/06/15
10-29 21:23:27.072  5618  5618 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-29 21:23:27.072  5618  5618 I Adreno  : Local Branch                     : mybranch17112971
10-29 21:23:27.072  5618  5618 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-29 21:23:27.072  5618  5618 I Adreno  : Remote Branch                    : NONE
10-29 21:23:27.072  5618  5618 I Adreno  : Reconstruct Branch               : NOTHING
,10-29 21:23:27.117   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2afa4d6:true
,10-29 21:23:27.141   412   412 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15988]" dev="sockfs" ino=15988 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-29 21:23:27.141   412   412 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[15988]" dev="sockfs" ino=15988 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-29 21:23:27.161  5618  5618 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-29 21:23:27.174  5618  5618 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-29 21:23:27.208   951   951 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33818]" dev="sockfs" ino=33818 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-29 21:23:27.209  5618  5655 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-29 21:23:27.208   951   951 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33818]" dev="sockfs" ino=33818 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-29 21:23:27.214  3564  3564 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[26168]" dev="sockfs" ino=26168 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-29 21:23:27.214  3564  3564 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[26168]" dev="sockfs" ino=26168 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-29 21:23:27.220  5618  5642 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-29 21:23:27.250  5618  5655 I OpenGLRenderer: Initialized EGL, version 1.4
,10-29 21:23:27.325   927   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +549ms (total +924ms),
,10-29 21:23:27.357  5618  5618 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5618
,10-29 21:23:27.441  5618  5618 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-29 21:23:27.584  5618  5657 D jxcore_app_log: JniHelper::setJavaVM(0xf527c000), pthread_self() = -580650704
,10-29 21:23:27.588  5618  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-29 21:23:27.588  5618  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-29 21:23:27.588  5618  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-29 21:23:27.588  5618  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-29 21:23:27.588  5618  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-29 21:23:27.588  5618  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6792c0 added. We now have 1 listener(s)
10-29 21:23:27.591  5618  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
10-29 21:23:27.591  5618  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-29 21:23:27.592  5618  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-29 21:23:27.592  5618  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-29 21:23:27.594  5618  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c3e99f added. We now have 1 listener(s)
10-29 21:23:27.594  5618  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 21:23:27.598   927  2950 D WifiService: New client listening to asynchronous messages
,10-29 21:23:27.599  5618  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-29 21:23:27.599  5618  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-29 21:23:27.599  5618  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
10-29 21:23:27.599  5618  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-29 21:23:27.599  5618  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-29 21:23:27.599  5618  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-29 21:23:27.599  5618  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,10-29 21:23:27.601  5618  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 21:23:27.601  5618  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-29 21:23:27.605  5618  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-29 21:23:27.605  5618  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:23:27.605  5618  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:23:27.605  5618  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:23:27.605  5618  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:23:27.605  5618  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:23:27.605  5618  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:27.605  5618  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:23:27.605  5618  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:23:27.605  5618  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-29 21:23:27.605  5618  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-29 21:23:27.606  5618  5657 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-29 21:23:27.723  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:23:27.726  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:23:27.730  5618  5618 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-29 21:23:28.224  5618  5664 W jxcore-log: Initializing JXcore engine
10-29 21:23:28.224  5618  5664 W jxcore-log: JXcore engine is ready
,10-29 21:23:28.248  5664  5664 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11713 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-29 21:23:28.248  5664  5664 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[17417]" dev="sockfs" ino=17417 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-29 21:23:28.248  5664  5664 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-29 21:23:28.248  5664  5664 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30437]" dev="sockfs" ino=30437 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-29 21:23:28.256  5618  5664 W jxcore-log: Starting JXcore engine
,10-29 21:23:28.304  5618  5664 W jxcore-log: Platform android
10-29 21:23:28.304  5618  5664 W jxcore-log: 
,10-29 21:23:28.304  5618  5664 W jxcore-log: Process ARCH arm
10-29 21:23:28.304  5618  5664 W jxcore-log: 
,10-29 21:23:28.484  5618  5664 I jxcore-log: JXcore Cordova bridge is ready!
10-29 21:23:28.484  5618  5664 I jxcore-log: 
10-29 21:23:28.484  5618  5664 W jxcore-log: JXcore engine is started
,10-29 21:23:28.492  5618  5657 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-29 21:23:28.499  5618  5618 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-29 21:23:29.566  3548  3548 I ConfigService: onDestroy
,10-29 21:23:32.669   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:23:33.670   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:23:34.671   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:23:35.672   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:23:36.673   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:23:37.674   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-29 21:23:38.016  3548  5666 I VacuumService: Vacuum at: now=1477790618016 tag=VacuumService
,10-29 21:23:38.045  3548  5669 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-29 21:23:38.082  3548  5667 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-29 21:23:38.085  3548  5667 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-29 21:23:38.105  4768  4836 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-29 21:23:38.106  4768  4768 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-29 21:23:38.109  3548  5669 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-29 21:23:38.119  5618  5664 I jxcore-log: 2016-10-30 01:23:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-29 21:23:38.119  5618  5664 I jxcore-log: 
,10-29 21:23:38.120  5618  5664 I jxcore-log: 2016-10-30 01:23:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-29 21:23:38.120  5618  5664 I jxcore-log: 
,10-29 21:23:38.122  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:23:38.122  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:23:38.122  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:23:38.122  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:23:38.122  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:23:38.122  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:38.122  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:23:38.122  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 21:23:38.123  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 21:23:38.124  5618  5664 I jxcore-log: 2016-10-30 01:23:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-29 21:23:38.124  5618  5664 I jxcore-log: 
,10-29 21:23:38.125  5618  5664 I jxcore-log: 2016-10-30 01:23:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-29 21:23:38.125  5618  5664 I jxcore-log: 
,10-29 21:23:38.348  3548  5667 W Uploader:  no longer exists, so no auth token.
,10-29 21:23:38.360  3548  5671 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-29 21:23:38.366  5618  5664 I jxcore-log: 2016-10-30 01:23:38 - DEBUG UnitTest_app: 'Running unit tests'
10-29 21:23:38.366  5618  5664 I jxcore-log: 
,10-29 21:23:38.367  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:23:38.367  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@405e26e added. We now have 2 listener(s)
10-29 21:23:38.368  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 21:23:38.368  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-29 21:23:38.368  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:23:38.368  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:23:38.368  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@931d0f added. We now have 2 listener(s)
10-29 21:23:38.368  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:23:38.370  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-29 21:23:38.373  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 21:23:38.375  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:23:38.375  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:23:38.375  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:23:38.375  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:23:38.375  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:23:38.375  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:38.375  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:23:38.375  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:23:38.376  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:38.376  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 21:23:38.376  5618  5664 D executeNativeTests: Running unit tests
,10-29 21:23:38.381  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:23:38.386  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:23:38.413  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:23:38.413  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 added. We now have 3 listener(s)
,10-29 21:23:38.414  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 21:23:38.414  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:23:38.414  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:23:38.414  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:23:38.414  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a added. We now have 3 listener(s)
10-29 21:23:38.414  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:23:38.415  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-29 21:23:38.416  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 21:23:38.421  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:23:38.421  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:23:38.421  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:23:38.421  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:23:38.421  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:23:38.421  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:38.421  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:23:38.421  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 21:23:38.424  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:38.425  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-29 21:23:38.426  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-29 21:23:38.426  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-29 21:23:38.426  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 21:23:38.426  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 21:23:38.427  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:23:38.427  5618  5664 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-29 21:23:38.428  5618  5664 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-29 21:23:38.428  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-29 21:23:38.428  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 21:23:38.428  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 21:23:38.428  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:23:38.428  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 21:23:38.428  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:23:38.428  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:38.428  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:38.428  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:38.429  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:38.429  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:23:38.429  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:38.429  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:23:38.429  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 removed from the list
10-29 21:23:38.429  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:38.429  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a removed from the list
10-29 21:23:38.429  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:38.429  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:38.429  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:38.429  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:38.429  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.430  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.430  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.430  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.430  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:38.430  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:38.430  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:38.430  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:38.431  5618  5664 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-29 21:23:38.431  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:23:38.431  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:38.431  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:38.432  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:38.432  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:38.432  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:38.432  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:38.432  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:38.432  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:38.432  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:38.432  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:38.432  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:38.432  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:38.432  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:38.432  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:38.432  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.432  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.432  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.432  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.433  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:38.433  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:38.433  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:38.433  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-29 21:23:38.435  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-29 21:23:38.436  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:23:38.436  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:38.436  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:38.436  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:38.436  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:38.436  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:38.436  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:38.436  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:38.436  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:38.436  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:38.436  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:38.436  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:38.436  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:38.436  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:38.436  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:38.436  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.442  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.442  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.442  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.442  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:38.442  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:38.442  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:38.442  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:38.443  5618  5664 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-29 21:23:38.444  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:23:38.446  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:23:38.446  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:23:38.446  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:23:38.446  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:23:38.446  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:23:38.446  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:38.446  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:23:38.446  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:23:38.447  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:38.447  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 21:23:38.447  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:23:38.447  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 21:23:38.447  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 21:23:38.448  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:23:38.448  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-29 21:23:38.448  3548  5669 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
10-29 21:23:38.449  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-29 21:23:38.449  5618  5664 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 21:23:38.449  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-29 21:23:38.453  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:23:38.455  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.455  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-29 21:23:38.456  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 21:23:38.456  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-29 21:23:38.456  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:23:38.457  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-29 21:23:38.459  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-29 21:23:38.460  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.460  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 21:23:38.460  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 21:23:38.460  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-29 21:23:38.461  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 21:23:38.461  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.462  5618  5664 D BluetoothAdapter: STATE_ON
10-29 21:23:38.464  4556  4570 D BtGatt.GattService: registerClient() - UUID=5035d37f-0e58-4a87-b57f-7ff6bc2fe814
10-29 21:23:38.465  4556  4618 D BtGatt.GattService: onClientRegistered() - UUID=5035d37f-0e58-4a87-b57f-7ff6bc2fe814, clientIf=5
10-29 21:23:38.467  5618  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-29 21:23:38.467  4556  4788 D BtGatt.GattService: start scan with filters
10-29 21:23:38.472  4556  4623 D BtGatt.ScanManager: handling starting scan
10-29 21:23:38.472  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-29 21:23:38.472  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.472  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 21:23:38.473  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.473  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-29 21:23:38.473  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 21:23:38.473  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:23:38.473  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 21:23:38.473  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 21:23:38.473  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:23:38.473  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-29 21:23:38.473  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 21:23:38.473  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.473  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-29 21:23:38.473  4556  4623 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:23:38.474  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.474  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:23:38.475  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.475  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:38.475  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:23:38.475  5618  5664 I io.jxcore.node.ConnectionHelper: start: OK
10-29 21:23:38.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-29 21:23:38.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:38.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:38.477  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:23:38.478  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:23:38.481  4556  4618 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-29 21:23:38.481  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:38.482  4556  4623 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-29 21:23:38.488  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 21:23:38.488  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:38.489  4556  4623 D BtGatt.ScanManager: Starting BLE batch scan
10-29 21:23:38.489  4556  4623 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-29 21:23:38.498  4556  4618 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-29 21:23:38.498  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:38.503  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 21:23:38.503  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:23:38.622  3548  5671 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-29 21:23:38.691  3548  5667 W Uploader:  no longer exists, so no auth token.
,10-29 21:23:38.703  3548  5669 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-29 21:23:38.794  3548  5671 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-29 21:23:38.979  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-29 21:23:38.979  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-29 21:23:38.980  5618  5618 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-29 21:23:39.008  4556  4556 D BtGatt.ScanManager: awakened up at time 170123
,10-29 21:23:39.013  4556  4623 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-29 21:23:39.028  4556  4618 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-29 21:23:39.029  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:23:39.032  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,10-29 21:23:43.480  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 21:23:43.480  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:43.481  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-29 21:23:43.481  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:43.481  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-29 21:23:43.481  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:43.481  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-29 21:23:43.481  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 21:23:43.481  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 21:23:43.481  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-29 21:23:43.482  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.482  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.483  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.483  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 21:23:43.483  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:43.484  5618  5664 D BluetoothAdapter: STATE_ON
10-29 21:23:43.485  4556  4570 D BtGatt.GattService: stopScan() - queue size =1
10-29 21:23:43.487  4556  4788 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-29 21:23:43.488  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-29 21:23:43.489  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.489  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 21:23:43.490  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.490  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.490  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.490  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.491  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-29 21:23:43.491  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.492  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.492  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.492  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-29 21:23:43.492  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 21:23:43.493  4556  4556 D BtGatt.ScanManager: awakened up at time 174608
10-29 21:23:43.494  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:23:43.494  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.498  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.498  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:23:43.499  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.499  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:43.499  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:43.499  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:43.499  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:23:43.499  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:43.499  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:23:43.500  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:43.500  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:23:43.500  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:43.500  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 21:23:43.500  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:23:43.500  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:23:43.500  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:43.500  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 21:23:43.500  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:43.500  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 21:23:43.500  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:23:43.500  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 21:23:43.500  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 21:23:43.500  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-29 21:23:43.503  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:23:43.503  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:43.503  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:43.503  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:23:43.503  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:23:43.503  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-29 21:23:43.503  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:43.504  4556  4623 D BtGatt.ScanManager: stopping BLe Batch
,10-29 21:23:43.511  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 21:23:43.511  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:43.512  4556  4623 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-29 21:23:43.530  4556  4618 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-29 21:23:43.530  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:43.530  4556  4618 D BtGatt.GattService: current time is 174645624108
10-29 21:23:43.531  4556  4618 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -80, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -93, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -78, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -88, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,10-29 21:23:43.533  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-29 21:23:43.534  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-29 21:23:43.534  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-29 21:23:43.534  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-29 21:23:43.535  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-29 21:23:43.535  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,10-29 21:23:44.004  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 21:23:48.502  5618  5664 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-29 21:23:48.507  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 21:23:48.518  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:23:48.518  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:23:48.518  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:23:48.518  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:23:48.518  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:23:48.518  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:48.518  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:23:48.518  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 21:23:48.523  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 21:23:48.523  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-29 21:23:48.524  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-29 21:23:48.524  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 21:23:48.524  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 21:23:48.524  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:23:48.524  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-29 21:23:48.531  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-29 21:23:48.531  5618  5664 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 21:23:48.531  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-29 21:23:48.532  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:23:48.540  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:23:48.540  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.541  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-29 21:23:48.542  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-29 21:23:48.542  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-29 21:23:48.548  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:48.548  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 21:23:48.548  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 21:23:48.548  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-29 21:23:48.549  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 21:23:48.549  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.550  5618  5664 D BluetoothAdapter: STATE_ON
10-29 21:23:48.553  4556  4788 D BtGatt.GattService: registerClient() - UUID=8b6b507e-40b6-4b7d-bbbd-f11f4500abd4
10-29 21:23:48.554  4556  4618 D BtGatt.GattService: onClientRegistered() - UUID=8b6b507e-40b6-4b7d-bbbd-f11f4500abd4, clientIf=5
,10-29 21:23:48.555  5618  5629 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-29 21:23:48.555  4556  4787 D BtGatt.GattService: start scan with filters
,10-29 21:23:48.560  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-29 21:23:48.560  4556  4623 D BtGatt.ScanManager: handling starting scan
10-29 21:23:48.560  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.560  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 21:23:48.561  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.561  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-29 21:23:48.561  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 21:23:48.561  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.561  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 21:23:48.561  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 21:23:48.562  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.562  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,10-29 21:23:48.563  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-29 21:23:48.564  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:48.565  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-29 21:23:48.568  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.568  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:23:48.568  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.568  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.569  5618  5664 I io.jxcore.node.ConnectionHelper: start: OK
,10-29 21:23:48.569  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.571  4556  4618 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-29 21:23:48.571  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:48.572  4556  4623 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-29 21:23:48.575  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.576  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.576  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.576  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,10-29 21:23:48.576  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-29 21:23:48.576  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 21:23:48.577  5618  5664 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-29 21:23:48.577  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:48.577  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-29 21:23:48.577  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:48.577  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-29 21:23:48.577  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:48.577  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-29 21:23:48.577  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 21:23:48.577  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 21:23:48.577  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-29 21:23:48.578  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.578  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.578  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.578  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 21:23:48.578  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.579  5618  5664 D BluetoothAdapter: STATE_ON
10-29 21:23:48.580  4556  4788 D BtGatt.GattService: stopScan() - queue size =1
10-29 21:23:48.581  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 21:23:48.581  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:48.581  4556  4767 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-29 21:23:48.581  4556  4623 D BtGatt.ScanManager: Starting BLE batch scan
10-29 21:23:48.581  4556  4623 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-29 21:23:48.581  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-29 21:23:48.582  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.582  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 21:23:48.582  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.582  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:48.582  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.582  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.582  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-29 21:23:48.582  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.582  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.583  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.583  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-29 21:23:48.583  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 21:23:48.583  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:23:48.584  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.586  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.586  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:23:48.586  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.586  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.586  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:48.586  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:48.586  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:23:48.587  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:23:48.587  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:23:48.587  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:48.587  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:48.587  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:48.587  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 21:23:48.587  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:48.587  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.587  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:48.587  5618  5664 D org.thaliproject.p2p.btco,nnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:48.587  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 21:23:48.587  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 21:23:48.587  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.587  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.588  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 21:23:48.588  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.590  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.590  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.590  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.590  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.591  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:23:48.591  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:48.591  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:48.591  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.593  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.593  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.593  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.593  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:48.593  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:48.594  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:48.594  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:48.594  5618  5664 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-29 21:23:48.596  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:23:48.599  4556  4618 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-29 21:23:48.599  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:23:48.602  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:23:48.602  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:23:48.602  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:23:48.602  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:23:48.602  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:23:48.602  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:48.602  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:23:48.602  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:23:48.604  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:23:48.604  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 21:23:48.604  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:23:48.604  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 21:23:48.605  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 21:23:48.605  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:23:48.605  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-29 21:23:48.607  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 21:23:48.607  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:23:48.608  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:23:48.609  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-29 21:23:48.610  5618  5664 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 21:23:48.610  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-29 21:23:48.611  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:23:48.614  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.614  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-29 21:23:48.614  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 21:23:48.614  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-29 21:23:48.616  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-29 21:23:48.616  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:48.616  4556  4623 D BtGatt.ScanManager: stopping BLe Batch
10-29 21:23:48.618  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.618  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 21:23:48.618  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 21:23:48.618  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-29 21:23:48.618  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 21:23:48.618  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.619  5618  5664 D BluetoothAdapter: STATE_ON
10-29 21:23:48.621  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-29 21:23:48.621  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:48.621  4556  4623 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-29 21:23:48.622  4556  4570 D BtGatt.GattService: registerClient() - UUID=e7ba7921-aa41-448c-85e8-44e2f6f2315f
10-29 21:23:48.623  4556  4618 D BtGatt.GattService: onClientRegistered() - UUID=e7ba7921-aa41-448c-85e8-44e2f6f2315f, clientIf=5
10-29 21:23:48.623  5618  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-29 21:23:48.623  4556  4767 D BtGatt.GattService: start scan with filters
,10-29 21:23:48.626  4556  4618 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-29 21:23:48.626  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:23:48.628  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-29 21:23:48.628  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.628  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 21:23:48.628  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.628  4556  4623 D BtGatt.ScanManager: handling starting scan
10-29 21:23:48.628  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-29 21:23:48.629  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 21:23:48.629  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.629  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 21:23:48.629  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 21:23:48.629  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-29 21:23:48.629  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.629  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-29 21:23:48.630  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-29 21:23:48.630  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:48.634  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.634  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:23:48.634  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:48.634  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:48.634  5618  5664 I io.jxcore.node.ConnectionHelper: start: OK
10-29 21:23:48.634  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.635  4556  4618 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-29 21:23:48.635  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:48.636  4556  4623 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-29 21:23:48.636  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.637  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.637  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.637  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:23:48.637  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-29 21:23:48.641  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-29 21:23:48.641  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:48.641  4556  4623 D BtGatt.ScanManager: Starting BLE batch scan
10-29 21:23:48.641  4556  4623 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-29 21:23:48.651  4556  4618 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-29 21:23:48.651  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:23:48.657  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 21:23:48.657  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:23:49.138  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-29 21:23:49.139  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:23:49.139  5618  5618 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-29 21:23:49.489   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-29 21:23:49.495   927  2951 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-29 21:23:50.414   927  2949 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-29 21:23:52.512   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-29 21:23:52.524   927  2951 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-29 21:23:53.635  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 21:23:53.635  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-29 21:23:53.635  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-29 21:23:53.636  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:23:53.636  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-29 21:23:53.636  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:53.636  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-29 21:23:53.636  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 21:23:53.636  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-29 21:23:53.636  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-29 21:23:53.637  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:53.637  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.637  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.638  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-29 21:23:53.638  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:53.642  5618  5664 D BluetoothAdapter: STATE_ON
,10-29 21:23:53.645  4556  4570 D BtGatt.GattService: stopScan() - queue size =1
,10-29 21:23:53.650  4556  4767 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-29 21:23:53.651  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-29 21:23:53.651  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.651  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 21:23:53.652  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:53.652  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.652  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.652  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.652  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-29 21:23:53.653  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.653  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.653  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.653  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-29 21:23:53.653  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 21:23:53.654  4556  4556 D BtGatt.ScanManager: awakened up at time 184769
,10-29 21:23:53.655  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:23:53.655  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:53.656   927  3825 I ActivityManager: Killing 5049:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,10-29 21:23:53.657  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.658  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:23:53.658  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.658  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:53.658  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:23:53.658  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:23:53.658  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,10-29 21:23:53.659  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:23:53.659  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 21:23:53.659  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 21:23:53.659  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:23:53.659  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 21:23:53.659  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-29 21:23:53.659  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:23:53.661  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:23:53.661  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:53.661  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:23:53.661  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:23:53.662  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-29 21:23:53.687  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-29 21:23:53.687  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:23:53.688  4556  4623 D BtGatt.ScanManager: stopping BLe Batch
,10-29 21:23:53.693  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-29 21:23:53.693  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:23:53.693  4556  4623 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-29 21:23:53.709  4556  4618 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
10-29 21:23:53.710  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:23:53.710  4556  4618 D BtGatt.GattService: current time is 184825415356
10-29 21:23:53.710  4556  4618 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -78, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -95, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -87, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
10-29 21:23:53.710  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-29 21:23:53.711  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-29 21:23:53.711  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-29 21:23:53.711  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-29 21:23:53.711  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-29 21:23:53.711  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,10-29 21:23:54.163  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 21:23:54.163  5618  5618 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-29 21:23:54.163  5618  5618 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-29 21:23:55.546   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-29 21:23:55.553   927  2951 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-29 21:23:57.675   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:23:58.659  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 21:23:58.660  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-29 21:23:58.660  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-29 21:23:58.660  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-29 21:23:58.660  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:23:58.660  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:23:58.660  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-29 21:23:58.661  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:58.661  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.661  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:23:58.661  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.661  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:23:58.663  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.664  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:23:58.664  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.670  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.671  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:58.671  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.672  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.672  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:58.672  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 21:23:58.672  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:23:58.675  5618  5664 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-29 21:23:58.676   541   541 I ServiceManager: Waiting for service AtCmdFwd...
10-29 21:23:58.677  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:23:58.678  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:58.678  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:58.678  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:58.678  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.679  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:23:58.679  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:58.679  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:58.679  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.679  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.679  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.679  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:23:58.679  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.680  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.680  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.680  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:58.682  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:58.682  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.682  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.682  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.682  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:58.682  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.683  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.684  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-29 21:23:58.684  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 21:23:58.684  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:58.684  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:58.685  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:58.685  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.685  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.685  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:58.685  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
,10-29 21:23:58.685  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.685  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.685  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.685  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.685  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.685  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.685  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.685  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:58.687  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.687  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.687  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.687  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.687  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:58.687  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.687  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.688  5618  5664 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-29 21:23:58.689  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 21:23:58.689  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:58.689  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:58.689  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:58.689  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.689  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.689  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:58.690  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:58.690  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.690  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:23:58.690  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.690  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.690  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.690  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.690  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.690  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.692  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:58.692  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.692  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.692  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.692  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:58.693  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.693  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.694  5618  5664 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-29 21:23:58.694  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 21:23:58.694  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:58.694  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:58.694  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:58.694  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.694  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.694  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:58.694  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
,10-29 21:23:58.695  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.695  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.695  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.695  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.695  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.695  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:23:58.695  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.695  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.697  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.697  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.697  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.697  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.697  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-29 21:23:58.697  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.698  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:23:58.699  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-29 21:23:58.699  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 21:23:58.699  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 21:23:58.699  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-29 21:23:58.699  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 21:23:58.700  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 21:23:58.700  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-29 21:23:58.700  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-29 21:23:58.700  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-29 21:23:58.700  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:23:58.700  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:58.700  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:58.700  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:58.700  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.701  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.701  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:58.701  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
,10-29 21:23:58.701  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.701  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.701  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.701  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.701  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.701  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.701  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.701  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.706  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.706  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.706  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.706  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.706  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:58.706  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.707  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.708  5618  5664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-29 21:23:58.708  5618  5664 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-29 21:23:58.709  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-29 21:23:58.712  5618  5664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-29 21:23:58.713  5618  5664 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-29 21:23:58.713  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-29 21:23:58.713  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-29 21:23:58.713  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-29 21:23:58.713  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-29 21:23:58.713  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-29 21:23:58.713  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-29 21:23:58.713  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,10-29 21:23:58.713  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,10-29 21:23:58.714  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-29 21:23:58.715  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-29 21:23:58.716  5618  5664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-29 21:23:58.716  5618  5664 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-29 21:23:58.716  5618  5664 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,10-29 21:23:58.716  5618  5664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-29 21:23:58.716  5618  5664 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-29 21:23:58.717  5618  5664 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-29 21:23:58.717  5618  5664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-29 21:23:58.717  5618  5664 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-29 21:23:58.717  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-29 21:23:58.722  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-29 21:23:58.723  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-29 21:23:58.723  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-29 21:23:58.723  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-29 21:23:58.724  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,10-29 21:23:58.724  5618  5664 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-29 21:23:58.724  5618  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-29 21:23:58.724  5618  5664 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-29 21:23:58.724  5618  5664 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,10-29 21:23:58.724  5618  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-29 21:23:58.724  5618  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-29 21:23:58.724  5618  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-29 21:23:58.725  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:23:58.726  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:58.726  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:58.726  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-29 21:23:58.726  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.726  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.726  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:58.726  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-29 21:23:58.726  5618  5676 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-29 21:23:58.727  5618  5676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 21:23:58.727  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:58.727  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.727  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.727  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
,10-29 21:23:58.727  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.727  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.727  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.727  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:23:58.728  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.728  5618  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-29 21:23:58.729  5618  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
10-29 21:23:58.729  5618  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-29 21:23:58.729  5618  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-29 21:23:58.729  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.729  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.729  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:58.729  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.729  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:58.729  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.729  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:23:58.728  4569  4569 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30511]" dev="sockfs" ino=30511 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-29 21:23:58.730  5618  5664 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-29 21:23:58.731  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:23:58.731  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:58.731  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:58.731  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:58.731  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.731  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:23:58.731  5618  5676 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-29 21:23:58.728  4569  4569 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30511]" dev="sockfs" ino=30511 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-29 21:23:58.731  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:58.731  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:58.731  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.731  5618  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-29 21:23:58.732  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.732  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.732  5618  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-29 21:23:58.732  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.732  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.732  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.732  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.732  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.734  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.734  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.734  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.734  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.734  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:58.734  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.734  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.735  5618  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-29 21:23:58.736  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 21:23:58.736  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:23:58.736  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:58.736  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:58.736  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.736  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.736  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-29 21:23:58.736  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:58.736  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.736  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.736  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.736  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.736  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.736  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.736  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:23:58.736  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.737  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.737  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.738  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.738  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.738  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:58.738  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.738  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:23:58.738  5618  5664 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-29 21:23:58.739  5618  5664 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-29 21:23:58.739  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-29 21:23:58.739  5618  5664 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-29 21:23:58.739  5618  5664 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-29 21:23:58.739  5618  5664 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-29 21:23:58.739  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-29 21:23:58.739  5618  5664 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-29 21:23:58.739  5618  5664 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-29 21:23:58.739  5618  5664 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-29 21:23:58.739  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-29 21:23:58.739  5618  5664 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-29 21:23:58.739  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:23:58.739  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-29 21:23:58.739  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:23:58.739  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:58.739  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.740  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.740  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:58.740  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:58.740  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.740  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:23:58.740  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.740  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.740  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.740  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:23:58.740  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.740  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.741  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.741  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:23:58.741  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:23:58.741  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:23:58.741  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:23:58.741  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.741  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.742  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:23:58.742  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:23:58.742  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:23:58.742  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:23:58.742  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:23:58.742  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:23:58.742  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:23:58.742  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:23:58.742  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:23:58.742  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:23:59.677   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:00.678   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:01.679   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:02.679   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-29 21:24:03.743  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 21:24:03.744  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.744  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:03.744  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.744  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.744  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-29 21:24:03.744  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:24:03.745  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:24:03.745  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:03.745  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:24:03.745  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:03.745  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:24:03.746  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.746  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:03.746  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:24:03.746  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.746  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.746  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
,10-29 21:24:03.746  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.747  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.747  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.747  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.747  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:03.751  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:03.751  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.751  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.751  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:03.752  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-29 21:24:03.752  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.752  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.756  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-29 21:24:03.757  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:24:03.758  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-29 21:24:03.760  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-29 21:24:03.760  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-29 21:24:03.761  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-29 21:24:03.761  5618  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-29 21:24:03.761  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-29 21:24:03.762  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-29 21:24:03.762  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-29 21:24:03.762  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:03.763  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-29 21:24:03.763  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-29 21:24:03.763  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-29 21:24:03.763  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.763  5618  5678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 21:24:03.763  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-29 21:24:03.763  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-29 21:24:03.763  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:24:03.763  5618  5618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-29 21:24:03.763  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.763  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 21:24:03.763  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 21:24:03.763  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-29 21:24:03.763  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.763  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.764  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:03.765  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.765  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:24:03.765  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.765  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.765  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.765  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:24:03.765  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:24:03.765  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:24:03.765  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:03.766  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:24:03.766  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:24:03.766  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-29 21:24:03.766  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.766  5618  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-29 21:24:03.766  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.766  5618  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-29 21:24:03.766  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-29 21:24:03.766  5618  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-29 21:24:03.766  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:24:03.766  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.766  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.766  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:03.766  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.766  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.766  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:24:03.766  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-29 21:24:03.766  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.766  5618  5618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:03.766  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.764  4570  4570 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32388]" dev="sockfs" ino=32388 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-29 21:24:03.764  4570  4570 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32388]" dev="sockfs" ino=32388 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-29 21:24:03.768  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.768  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.768  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.768  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:03.768  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:03.768  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 21:24:03.769  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.770  5618  5664 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-29 21:24:03.770  5618  5664 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-29 21:24:03.770  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-29 21:24:03.770  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 21:24:03.771  5618  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-29 21:24:03.771  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:24:03.771  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:03.771  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:24:03.771  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:03.771  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:24:03.771  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.771  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:03.771  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:24:03.771  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.771  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.771  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:03.771  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.772  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.772  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.772  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:03.772  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.774  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:03.774  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.774  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.774  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:03.774  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:03.774  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.774  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.781  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:24:03.781  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:03.781  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:24:03.781  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:03.781  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.781  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:03.782  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:03.782  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:24:03.782  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.782  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.782  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:03.782  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.782  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.782  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.782  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.782  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:03.784  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.784  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.784  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.784  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:03.784  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:03.784  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.784  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:24:03.786  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-29 21:24:03.786  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:03.786  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:24:03.786  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:03.786  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.786  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.786  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:03.786  5618  5664 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee72415 not in the list
10-29 21:24:03.786  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.787  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
10-29 21:24:03.787  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
,10-29 21:24:03.787  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.787  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.787  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:03.787  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:03.787  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.788  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.788  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.788  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:03.788  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:03.788  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:03.788  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:03.788  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f32a not in the list
,10-29 21:24:03.789  5618  5664 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-29 21:24:03.789  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-29 21:24:03.789  5618  5664 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-29 21:24:03.789  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-29 21:24:03.789  5618  5664 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-29 21:24:03.790  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-29 21:24:03.791  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-29 21:24:03.791  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-29 21:24:03.791  5618  5664 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-29 21:24:03.792  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-29 21:24:03.792  5618  5664 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-29 21:24:03.792  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-29 21:24:03.792  5618  5664 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-29 21:24:03.792  5618  5664 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-29 21:24:03.792  5618  5664 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-29 21:24:03.792  5618  5664 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-29 21:24:03.792  5618  5664 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-29 21:24:03.793  5618  5664 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-29 21:24:03.793  5618  5664 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-29 21:24:03.793  5618  5664 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-29 21:24:03.793  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:03.793  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afc9dfc added. We now have 3 listener(s)
10-29 21:24:03.793  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:03.796  5618  5664 D BluetoothAdapter: enable(): BT is already enabled..!
,10-29 21:24:03.796   927  3856 D WifiService: setWifiEnabled: true pid=5618, uid=10077
10-29 21:24:03.796   927  3856 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 21:24:03.858  4556  4762 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-29 21:24:03.859  4556  4765 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-29 21:24:04.267  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 21:24:08.802  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 21:24:08.803  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29a3c85 added. We now have 4 listener(s)
,10-29 21:24:08.803  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 21:24:08.817  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 21:24:08.817  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29a3c85 removed from the list
10-29 21:24:08.818  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:08.818  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:24:08.819  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:08.822  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 21:24:08.822  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dfa7ada added. We now have 4 listener(s)
10-29 21:24:08.822  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 21:24:08.826  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:08.827  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dfa7ada removed from the list
10-29 21:24:08.827  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:08.827  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:24:08.827  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:08.829  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 21:24:08.829  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b0eb0b added. We now have 4 listener(s)
10-29 21:24:08.829  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:08.834   927  3130 D WifiService: setWifiEnabled: false pid=5618, uid=10077
,10-29 21:24:08.834   927  3130 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 21:24:08.840   927  2949 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-29 21:24:08.840   927  2949 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-29 21:24:08.840   927  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-29 21:24:08.841   927  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 21:24:08.850  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:24:08.853  4556  4614 D BluetoothAdapterState: Current state: ON, message: 23
10-29 21:24:08.853  4556  4614 D BluetoothAdapterProperties: Setting state to 13
10-29 21:24:08.853  4556  4614 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-29 21:24:08.854  4556  4614 D BluetoothAdapterProperties: onBluetoothDisable()
,10-29 21:24:08.855   927  5381 D DhcpClient: Clearing IP address
,10-29 21:24:08.855  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.855  4556  4614 I BluetoothAdapterState: Entering PendingCommandState
10-29 21:24:08.855  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:24:08.855  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.855  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.855  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:08.855  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.855  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:08.855  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:08.855  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:08.855   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-29 21:24:08.857  4556  4618 D BluetoothAdapterProperties: Scan Mode:20
10-29 21:24:08.857  4556  4614 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-29 21:24:08.857  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.858  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:08.858  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 21:24:08.860  4556  4556 D HeadsetService: Received stop request...Stopping profile...
,10-29 21:24:08.865  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:08.866   507   921 D CommandListener: Setting iface cfg
10-29 21:24:08.869  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:08.874  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:08.874  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.874  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.874  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.874  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:08.874  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.874  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:08.874  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:08.874  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:08.874  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.874  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:08.876  3548  5436 V NativeCrypto: Read error: ssl=0x7f59382a80: I/O error during system call, Connection timed out
10-29 21:24:08.879  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.879  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.879  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.879  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.879  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:08.879  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.879  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:08.879  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:08.879  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:08.881  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.881   927  5382 D DhcpClient: Receive thread stopped
10-29 21:24:08.881  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:08.885  3548  5436 V NativeCrypto: SSL shutdown failed: ssl=0x7f59382a80: I/O error during system call, Broken pipe
10-29 21:24:08.885  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.885  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.885  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.885  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.885  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:08.885  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.885  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:08.885  5618  5618 V io.jxcore.node.Co,nnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:08.885  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:08.886  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.887  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:08.887   927  3130 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,10-29 21:24:08.887   927  5379 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-29 21:24:08.890  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.890  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.890  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.890  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.890  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:08.890  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.890  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:08.890  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:08.890  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:08.891  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.891  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:08.892   927  5379 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-29 21:24:08.893   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,10-29 21:24:08.893   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-29 21:24:08.894   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-29 21:24:08.895  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.895  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.895  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.895  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.895  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:08.895  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.895  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:08.895  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:08.895  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:08.897  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.897  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:08.899   927   941 I ActivityManager: Start proc 5682:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-29 21:24:08.900   927   927 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:08.900   927   927 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:08.901  3782  3964 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:08.901  4556  4556 D BluetoothMapService: onReceive
10-29 21:24:08.901  4556  4556 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-29 21:24:08.901  4556  4556 D BluetoothMapService: STATE_TURNING_OFF
10-29 21:24:08.901  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:08.902   927   927 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:08.902  3118  3131 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:08.902  3118  3118 D HeadsetProfile: Bluetooth service disconnected
10-29 21:24:08.906  4556  4556 D A2dpService: Received stop request...Stopping profile...
10-29 21:24:08.906  4556  4782 D A2dpStateMachine: Exit Disconnected: -1
,10-29 21:24:08.909   538   538 E Parcel  : Reading a NULL string not supported here.
10-29 21:24:08.913   927   927 D RttService: SCAN_AVAILABLE : 1
10-29 21:24:08.913   927  3059 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-29 21:24:08.910   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-29 21:24:08.914   927   927 D BluetoothA2dp: Proxy object disconnected
10-29 21:24:08.914   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-29 21:24:08.916  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:08.916  4556  4556 V BluetoothAdapterState: isTurningOn()=false
,10-29 21:24:08.916  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:08.916  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:08.918  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-29 21:24:08.919  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-29 21:24:08.919  4556  4618 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-29 21:24:08.919  4556  4762 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:08.919  4556  4762 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:08.919  4556  4762 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:08.919  4556  4556 D HidService: Received stop request...Stopping profile...
10-29 21:24:08.919  4556  4556 D HidService: Stopping Bluetooth HidService
10-29 21:24:08.920  4556  4618 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-29 21:24:08.920  3118  3118 D BluetoothA2dp: Proxy object disconnected
10-29 21:24:08.921  4556  4556 D BluetoothMapService: MAP Service closeService in
10-29 21:24:08.921  4556  4556 D BluetoothMapMasInstance0: MAP Service shutdown
,10-29 21:24:08.921  4556  4556 D ObexServerSockets0: shutdown(block = true)
10-29 21:24:08.921  3118  3118 D BluetoothInputDevice: Proxy object disconnected
10-29 21:24:08.922  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-29 21:24:08.922  4556  4793 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-29 21:24:08.922  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-29 21:24:08.922  4556  4765 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-29 21:24:08.922  4556  4794 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-29 21:24:08.922  3118  3118 D HidProfile: Bluetooth service disconnected
10-29 21:24:08.924  4556  4556 I BtOppRfcommListener: stopping Accept Thread
10-29 21:24:08.924  4556  5318 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,10-29 21:24:08.925   927  2951 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-29 21:24:08.924  4556  5318 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-29 21:24:08.926  3745  3884 W QCNEJ   : |CORE| network lost: 100
10-29 21:24:08.927  3745  3884 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-29 21:24:08.928   927  2949 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-29 21:24:08.928   927  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-29 21:24:08.932  4556  4556 D HealthService: Received stop request...Stopping profile...
,10-29 21:24:08.934  4556  4556 D PanService: Received stop request...Stopping profile...
,10-29 21:24:08.937  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:08.938  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:08.938  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:08.938  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:08.940  4556  4762 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-29 21:24:08.940  4556  4762 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:08.941  4556  4762 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-29 21:24:08.941  4556  4762 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-29 21:24:08.941  4556  4556 D BluetoothMapService: Received stop request...Stopping profile...
10-29 21:24:08.941  4556  4762 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-29 21:24:08.941  4556  4556 D BluetoothMapService: stop()
10-29 21:24:08.941  4556  4762 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-29 21:24:08.941  4556  4618 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-29 21:24:08.941  4556  4556 D BluetoothMapAppObserver: deinitObservers()
10-29 21:24:08.942  4556  4556 D BluetoothMapAppObserver: removeReceiver()
10-29 21:24:08.943  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:08.944  4556  4556 V BluetoothAdapterState: isTurningOn()=false
,10-29 21:24:08.944  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:08.944  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:08.945  4556  4556 D SapService: Received stop request...Stopping profile...
,10-29 21:24:08.945  4556  4556 V SapService: stop()
10-29 21:24:08.948  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-29 21:24:08.948  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,10-29 21:24:08.948  4556  4618 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-29 21:24:08.950  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:08.950  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:08.950  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:08.950  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:08.950  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-29 21:24:08.951  4556  4618 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-29 21:24:08.951  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-29 21:24:08.951  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:08.951  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:08.951  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,10-29 21:24:08.951  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:08.952  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-29 21:24:08.952  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-29 21:24:08.952   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-29 21:24:08.953  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-29 21:24:08.953  3118  3118 D PanProfile: Bluetooth service disconnected
10-29 21:24:08.953  3118  3118 D BluetoothMap: Proxy object disconnected
10-29 21:24:08.953  3118  3118 D MapProfile: Bluetooth service disconnected
10-29 21:24:08.957  4556  4556 D BluetoothMapService: MAP Service closeService in
10-29 21:24:08.957  4556  4556 V BluetoothAdapterState: isTurningOff()=true
,10-29 21:24:08.957  4556  4556 V BluetoothAdapterState: isTurningOn()=false
,10-29 21:24:08.957  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,10-29 21:24:08.957  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:08.958  4556  4556 D BluetoothMapService: cleanup()
10-29 21:24:08.958  4556  4556 D BluetoothMapService: MAP Service closeService in
10-29 21:24:08.958  4556  4556 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:08.958  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:08.958  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:08.958  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:08.958  4556  4614 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,10-29 21:24:08.959  4556  4614 D BluetoothAdapterProperties: Setting state to 15
10-29 21:24:08.959  4556  4614 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-29 21:24:08.959  4556  4614 I BluetoothAdapterState: Entering BleOnState
10-29 21:24:08.960  3118  3132 D BluetoothPan: onBluetoothStateChange on: false
10-29 21:24:08.961  3118  3132 D BluetoothMap: onBluetoothStateChange: up=false
10-29 21:24:08.962  3118  3937 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:08.962  3118  3131 D BluetoothA2dp: onBluetoothStateChange: up=false
10-29 21:24:08.963  3118  3132 D BluetoothPbap: onBluetoothStateChange: up=false
10-29 21:24:08.963   927   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-29 21:24:08.964   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:08.964  3118  3937 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-29 21:24:08.964   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:08.964  5682  5682 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-29 21:24:08.964  3782  3806 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:08.965   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:08.965  4556  4614 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-29 21:24:08.965  4556  4614 D BluetoothAdapterProperties: Setting state to 16
10-29 21:24:08.965  4556  4614 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-29 21:24:08.967  4556  4614 D BluetoothAdapterProperties: onBleDisable
10-29 21:24:08.967  4556  4615 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-29 21:24:08.967  4556  4614 I BluetoothAdapterState: Entering PendingCommandState
10-29 21:24:08.968  4556  4618 D BluetoothAdapterProperties: Scan Mode:20
10-29 21:24:08.969  4556  4762 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-29 21:24:08.969  4556  4762 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:08.972  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.972  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.972  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.972  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.972  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:08.972  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.972  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:08.972  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:08.972  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:08.975  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:08.975  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.975  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.975  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.975  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:08.975  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.975  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:08.975  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:08.975  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:08.979  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.979  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.979  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.979  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.979  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:08.979  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.979  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:08.979  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:08.979  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:08.981  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:08.982  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:08.983   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-29 21:24:08.983   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-29 21:24:08.983  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:08.983   507   921 D TetherController: Setting IP forward enable = 0
10-29 21:24:08.984   927  2951 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-29 21:24:08.984   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-29 21:24:08.987   927  2949 D DhcpClient: doQuit
10-29 21:24:08.987   927  2949 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-29 21:24:08.988   927  5381 D DhcpClient: onQuitting
10-29 21:24:08.988  3425  3425 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-29 21:24:08.988  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:08.988   927   945 D Tethering: MasterInitialState.processMessage what=3
,10-29 21:24:08.991  5290  5290 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@20cf166 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-29 21:24:08.991  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.991  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.991  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.991  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.991  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:08.991  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.991  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:08.991  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:08.991  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:08.992  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:08.992  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-29 21:24:08.993  4904  4904 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-29 21:24:08.994  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.994  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.994  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.994  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.994  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:08.994  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.994  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:08.994  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:08.994  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:08.994  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:08.995  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:08.996  5037  5061 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-29 21:24:08.997  5037  5061 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-29 21:24:08.997  5037  5061 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-29 21:24:08.997  5037  5061 E SarControlService: no key has been found,reset the power
10-29 21:24:08.997  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-29 21:24:08.997  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.997  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-29 21:24:08.997  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:08.997  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:08.997  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:08.997  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:08.997  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:08.997  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:08.997  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:08.997  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 21:24:08.997  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-29 21:24:08.997  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:08.998  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 21:24:08.998  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:08.998  5062  5062 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-29 21:24:08.999  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-29 21:24:08.999  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-29 21:24:08.999  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:08.999  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-29 21:24:09.000  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:09.001  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 21:24:09.001  5062  5062 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-29 21:24:09.004  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cf381fc HexData = [00000000ea03000000000000ffffffff]
10-29 21:24:09.004  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-29 21:24:09.004  5062  5076 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-29 21:24:09.004  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 21:24:09.004  5037  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-29 21:24:09.007  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-29 21:24:09.011  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cf381fc HexData = [00000000eb03000000000000ffffffff]
10-29 21:24:09.011  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 21:24:09.011  5062  5076 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-29 21:24:09.011  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 21:24:09.012  5037  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-29 21:24:09.013  3548  3548 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-29 21:24:09.015   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@52f1722:true
,10-29 21:24:09.019  3425  3425 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-29 21:24:09.024  3425  3425 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-29 21:24:09.027   927   939 I ActivityManager: Start proc 5708:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-29 21:24:09.042   507   921 E Netd    : netlink response contains error (No such file or directory)
,10-29 21:24:09.043   927  2951 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-29 21:24:09.046  5682  5682 D LocalBluetoothProfileManager: Adding local MAP profile
,10-29 21:24:09.052  5682  5682 D BluetoothMap: Create BluetoothMap proxy object
,10-29 21:24:09.060  3425  3425 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-29 21:24:09.063  5682  5682 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-29 21:24:09.072  3425  3425 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-29 21:24:09.072  5708  5708 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-29 21:24:09.082  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,10-29 21:24:09.084   927   939 I ActivityManager: Killing 4958:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-29 21:24:09.174  5010  5010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-29 21:24:09.174   927  2949 D wifi    : In wifi stop Hal
10-29 21:24:09.175   927  2949 D wifi    : halHandle = 0x7f5849d180, mVM = 0x7f74acd140, mCls = 0x100a02
10-29 21:24:09.175   927  3423 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-29 21:24:09.175   927  3423 D WifiHAL : Got a signal to exit!!!
10-29 21:24:09.175   927  3423 I WifiHAL : Exit wifi_event_loop
10-29 21:24:09.175   927  2949 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-29 21:24:09.175   927  2949 E WifiHAL : Event processing terminated
10-29 21:24:09.176   927  2949 D wifi    : In wifi cleaned up handler
10-29 21:24:09.176   927  2949 I WifiHAL : Internal cleanup completed
10-29 21:24:09.177  4031  4193 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-29 21:24:09.177  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:09.179  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:09.181  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:09.186  4556  4618 I bt_hci  : shut_down
,10-29 21:24:09.189  4556  4624 D bt_hwcfg: hw_epilog_process
,10-29 21:24:09.190  4556  4624 I bt_vendor: low_power_mode_cb
,10-29 21:24:09.193  4556  4624 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-29 21:24:09.193  4556  4624 I bt_vendor: epilog_cb
10-29 21:24:09.193  4556  4624 I bt_hci  : epilog_finished_callback
,10-29 21:24:09.195  4556  4618 I bt_hci_h4: hal_close
,10-29 21:24:09.195  4556  4618 I bt_userial_vendor: device fd = 54 close
,10-29 21:24:09.197   927  3423 D wifi    : set interface wlan0 flags (DOWN)
,10-29 21:24:09.197   927  2949 D WifiNative-HAL: HAL event thread stopped successfully
,10-29 21:24:09.266  5708  5708 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at java.io.File.exists(File.java:361)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 21:24:09.266  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 21:24:09.267  5708  5708 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 21:24:09.267  5708  5708 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 21:24:09.267  5708  5708 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.e.b(PG:170)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 21:24:09.267  5708  5708 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.k.d(PG:583)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.e.b(PG:170)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 21:24:09.267  5708  5708 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.File.exists(File.java:361)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 21:24:09.267  5708  5708 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.File.exists(File.java:361)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 21:24:09.267  5708  5708 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-29 21:24:09.267  5708  5708 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-29 21:24:09.272  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-29 21:24:09.277  3548  3548 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 21:24:09.283  5682  5682 D DockEventReceiver: finishStartingService: stopping service
10-29 21:24:09.290   927  3825 I ActivityManager: Killing 5410:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
10-29 21:24:09.299  4556  4615 D bt_stack_manager: event_shut_down_stack finished.
10-29 21:24:09.300  4556  4614 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-29 21:24:09.313  4556  4614 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-29 21:24:09.313  4556  4556 D BtGatt.DebugUtils: handleDebugAction() action=null
10-29 21:24:09.314  4556  4556 D BtGatt.GattService: Received stop request...Stopping profile...
10-29 21:24:09.314  4556  4556 D BtGatt.GattService: stop()
10-29 21:24:09.314  4556  4556 D BtGatt.AdvertiseManager: advertise clients cleared
10-29 21:24:09.316  4556  4556 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:09.316  4556  4556 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:09.316  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:09.316  4556  4556 V BluetoothAdapterState: isBleTurningOff()=true
10-29 21:24:09.316  4556  4614 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-29 21:24:09.316  4556  4614 D BluetoothAdapterProperties: Setting state to 10
10-29 21:24:09.316  4556  4614 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-29 21:24:09.317  4556  4614 I BluetoothAdapterState: Entering OffState
10-29 21:24:09.318   927   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-29 21:24:09.330  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-29 21:24:09.330  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-29 21:24:09.330  4556  4556 I BluetoothServiceJni: cleanupNative: return from cleanup
10-29 21:24:09.331  4556  4615 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-29 21:24:09.335  3696  3696 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-29 21:24:09.341  3696  3696 D SystemUpdateService: onCreate
,10-29 21:24:09.347  4556  4615 D bt_stack_manager: event_clean_up_stack finished.
10-29 21:24:09.348  3696  3696 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-29 21:24:09.355  3696  3696 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-29 21:24:09.361  4556  4556 I art     : System.exit called, status: 0
,10-29 21:24:09.361  4556  4556 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-29 21:24:09.369  3696  5407 I iu.UploadsManager: num queued entries: 0
,10-29 21:24:09.369  3696  5407 I iu.UploadsManager: num updated entries: 0
10-29 21:24:09.370  3696  5407 I iu.SyncManager: NEXT; no task
,10-29 21:24:09.381  3696  3696 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-29 21:24:09.383  3696  3696 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-29 21:24:09.388  3696  5742 I SystemUpdateService: active receiver: enabled
,10-29 21:24:09.395   927  3565 I ActivityManager: Start proc 5744:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-29 21:24:09.399   927   939 I ActivityManager: Process com.android.bluetooth (pid 4556) has died
,10-29 21:24:09.401   927   945 D Tethering: InitialState.processMessage what=4
,10-29 21:24:09.406   927   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-29 21:24:09.409  3696  5742 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-29 21:24:09.419  3696  5742 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-29 21:24:09.419  3696  5742 I SystemUpdateService: now status is 0 (complete)
10-29 21:24:09.419  3696  5742 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-29 21:24:09.419  3696  5742 I SystemUpdateService: file has been verified
10-29 21:24:09.419  3696  5742 I SystemUpdateService: OTA package size = 21989297
,10-29 21:24:09.437  5744  5744 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-29 21:24:09.440  5744  5744 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-29 21:24:09.448  5744  5744 D SprintDMHelper: simOperator: 
,10-29 21:24:09.448  5744  5744 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-29 21:24:09.449  3696  5742 I SystemUpdateService: showing system update notification
,10-29 21:24:09.459  5010  5756 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-29 21:24:09.474   927  3549 I ActivityManager: Start proc 5757:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-29 21:24:09.504  5757  5757 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-29 21:24:09.517  3696  3696 D SystemUpdateService: onDestroy
,10-29 21:24:09.519   927   939 I ActivityManager: Killing 5290:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-29 21:24:09.554   927   939 I ActivityManager: Killing 4628:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-29 21:24:09.658  5708  5729 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-29 21:24:09.672   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99dc4f7:true
,10-29 21:24:10.058   507   921 D TetherController: Setting IP forward enable = 0
,10-29 21:24:13.861   927  3564 D WifiService: setWifiEnabled: true pid=5618, uid=10077
,10-29 21:24:13.861   927  3564 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 21:24:13.874   507   921 D SoftapController: Softap fwReload - Ok
,10-29 21:24:13.880   507   921 D CommandListener: Setting iface cfg
,10-29 21:24:13.880   507   921 D CommandListener: Trying to bring down wlan0
10-29 21:24:13.882   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-29 21:24:13.886   927  2949 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-29 21:24:14.466   927  2949 D wifi    : set interface wlan0 flags (UP)
,10-29 21:24:14.469   927  2949 I WifiHAL : Initializing wifi
10-29 21:24:14.469   927  2949 I WifiHAL : Creating socket
10-29 21:24:14.471   927   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-29 21:24:14.474   927  2949 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-29 21:24:14.474   927  2949 D wifi    : Did set static halHandle = 0x7f5849d180
10-29 21:24:14.474   927  2949 D wifi    : halHandle = 0x7f5849d180, mVM = 0x7f74acd140, mCls = 0x19ba
10-29 21:24:14.474   927  2949 D wifi    : array field set
10-29 21:24:14.474   927  2949 I WifiNative-HAL: interface[0] = wlan0
,10-29 21:24:14.478   927  5781 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546942079360
10-29 21:24:14.478   927  5781 D wifi    : waitForHalEvents called, vm = 0x7f74acd140, obj = 0x19ba, env = 0x7f5849af80
,10-29 21:24:14.543  5782  5782 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-29 21:24:14.556  5782  5782 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-29 21:24:14.562  5782  5782 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-29 21:24:14.562  5782  5782 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-29 21:24:14.578   927  2949 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-29 21:24:14.580  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:14.580  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:14.580  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:14.580  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:14.580  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:14.580  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:14.580  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:14.580  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:14.580  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:14.580  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:14.581  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:14.582  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:14.582  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:14.582  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:14.582  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:14.582  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:14.582  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:14.582  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:14.582  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:14.582  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:14.582  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:14.582  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:14.582   927  2949 D WifiConfigStore: Loading config and enabling all networks 
,10-29 21:24:14.585  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:14.585  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:14.585  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:14.585  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:14.585  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:14.585  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:14.585  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:14.585  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:14.585  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:14.585  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:14.585  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:14.586  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:14.587  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:14.587  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:14.592   927  2949 D WifiConfigStore: loaded 0 passpoint configs
,10-29 21:24:14.592   927  2949 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-29 21:24:14.592   927  2949 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-29 21:24:14.593   927  2949 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-29 21:24:14.593   927  2949 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-29 21:24:14.594   927  2949 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-29 21:24:14.594   927  2949 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-29 21:24:14.594   927  2949 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-29 21:24:14.597   927  2949 D WifiNative-HAL: Setting external_sim to 1
,10-29 21:24:14.597   927  2949 D wifi    : setting dfs flag to true, 0x7f5da34c80
10-29 21:24:14.597  5010  5010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-29 21:24:14.597   927  2949 D WifiStateMachine: Setting OUI to DA-A1-19
10-29 21:24:14.598   927  2949 D wifi    : setting scan oui 0x7f5da34c80
10-29 21:24:14.598   927  2949 D WifiHAL : Sending mac address OUI
,10-29 21:24:14.600   927  2949 E native  : do suspend false
,10-29 21:24:14.607   927  2949 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-29 21:24:14.607   927   927 D RttService: SCAN_AVAILABLE : 3
10-29 21:24:14.607   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-29 21:24:14.608   927  3059 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-29 21:24:14.608   507   921 D CommandListener: Setting iface cfg
,10-29 21:24:14.612   927  2948 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
10-29 21:24:14.613   927  2948 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-29 21:24:14.620   927  2948 D WifiNative-HAL: p2pGetDeviceAddress
,10-29 21:24:14.620   927  2948 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-29 21:24:14.624   927   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=205739 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-29 21:24:17.671  5782  5782 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 21:24:17.675  5782  5782 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 21:24:17.679  5782  5782 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 21:24:17.752   927  2949 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-29 21:24:17.754   927  2949 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-29 21:24:17.754   927  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 21:24:17.766   927  2949 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-29 21:24:17.800   927  2949 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-29 21:24:17.802  5782  5782 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-29 21:24:18.242  5782  5782 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-29 21:24:18.273  5782  5782 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-29 21:24:18.274  5782  5782 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-29 21:24:18.284   927  2949 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-29 21:24:18.285   927  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-29 21:24:18.285   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-29 21:24:18.302   927  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 21:24:18.318   507   921 D CommandListener: Setting iface cfg
,10-29 21:24:18.324   927  2949 D WifiStateMachine: Start Dhcp Watchdog 2
,10-29 21:24:18.330   927  5788 D DhcpClient: Receive thread started
,10-29 21:24:18.335   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-29 21:24:18.335   927  2949 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-29 21:24:18.335   927  2951 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-29 21:24:18.416   927  2949 E native  : do suspend false
,10-29 21:24:18.431   927  5787 D DhcpClient: Broadcasting DHCPDISCOVER
,10-29 21:24:18.468   927  5788 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172632, domain null
,10-29 21:24:18.469   927  5787 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172632 seconds
,10-29 21:24:18.471   927  5787 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-29 21:24:18.483   927  5788 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-29 21:24:18.484   927  5787 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-29 21:24:18.487   507   921 D CommandListener: Setting iface cfg
10-29 21:24:18.493   927  2949 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-29 21:24:18.495   927  5787 D DhcpClient: Scheduling renewal in 86399s
,10-29 21:24:18.503   927  2949 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-29 21:24:18.504   927  2949 D WifiConfigStore: No blacklist allowed without epno enabled
10-29 21:24:18.505   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-29 21:24:18.507   927  2951 D ConnectivityService: Adding iface wlan0 to network 101
,10-29 21:24:18.516   927  2949 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-29 21:24:18.557   927  2951 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-29 21:24:18.557   927  2951 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-29 21:24:18.561   927  2951 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-29 21:24:18.563   927  2951 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
10-29 21:24:18.564   927  2951 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-29 21:24:18.570   927  2951 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-29 21:24:18.574   927  2951 D ConnectivityService: scheduleUnvalidatedPrompt 101
10-29 21:24:18.575   927  2951 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-29 21:24:18.575   927  2951 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-29 21:24:18.575   927  2949 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-29 21:24:18.575   927  2951 D ConnectivityService:    accepting network in place of null
10-29 21:24:18.575   927  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-29 21:24:18.576   927  2951 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-29 21:24:18.597   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 21:24:18.598   927  5786 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209713, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-29 21:24:18.618   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 21:24:18.621   927  2951 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-29 21:24:18.621  3745  3884 W QCNEJ   : |CORE| network available: 101
,10-29 21:24:18.621   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-29 21:24:18.623   927  2951 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-29 21:24:18.625   927   945 D Tethering: MasterInitialState.processMessage what=3
10-29 21:24:18.626  3745  3884 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-29 21:24:18.627  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.627  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:18.627  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:18.627  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:18.627  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:18.627  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:18.627  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:18.627  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:18.627  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:18.627  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.627  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:18.628  3745  3884 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-29 21:24:18.628  3745  3884 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-29 21:24:18.631  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:18.631  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:18.631  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:18.631  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:18.631  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:18.631  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:18.631  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:18.631  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:18.631  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:18.631  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.631  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:18.634  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.635  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:18.635  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:18.635  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:18.635  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:18.635  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:18.635  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:18.635  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:18.635  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:18.635  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.635  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:18.635  4904  4904 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-29 21:24:18.638  5037  5061 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-29 21:24:18.638  5037  5061 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-29 21:24:18.638  5037  5061 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-29 21:24:18.638  5037  5061 E SarControlService: no key has been found,reset the power
10-29 21:24:18.638  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-29 21:24:18.638  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-29 21:24:18.638  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-29 21:24:18.639  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 21:24:18.639  5062  5062 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-29 21:24:18.640  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-29 21:24:18.640  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-29 21:24:18.640  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-29 21:24:18.641  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 21:24:18.641  5062  5062 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-29 21:24:18.643  3696  3696 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-29 21:24:18.647  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cf381fc HexData = [00000000ec03000000000000ffffffff]
10-29 21:24:18.647  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 21:24:18.647  5062  5076 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-29 21:24:18.647  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cf381fc HexData = [00000000ed03000000000000ffffffff]
10-29 21:24:18.647  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 21:24:18.647  5062  5076 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-29 21:24:18.648  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 21:24:18.648  5037  5047 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-29 21:24:18.648  3696  3696 D SystemUpdateService: onCreate
10-29 21:24:18.649  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 21:24:18.649  5037  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-29 21:24:18.653  3696  3696 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-29 21:24:18.663  3696  3696 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-29 21:24:18.666   927  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-29 21:24:18.670  3696  5407 I iu.UploadsManager: num queued entries: 0
,10-29 21:24:18.671  3696  5407 I iu.UploadsManager: num updated entries: 0
10-29 21:24:18.671  3696  5407 I iu.SyncManager: NEXT; no task
,10-29 21:24:18.673  3696  3696 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-29 21:24:18.674  3696  3696 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-29 21:24:18.676  5744  5744 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-29 21:24:18.680  5744  5744 D SprintDMHelper: simOperator: 
10-29 21:24:18.680  5744  5744 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-29 21:24:18.690  3696  5798 I SystemUpdateService: active receiver: enabled
,10-29 21:24:18.711   927  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 30 Oct 2016 01:24:18 GMT], X-Android-Received-Millis=[1477790658710], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477790658688]}
,10-29 21:24:18.711  3696  5798 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-29 21:24:18.711   927  2951 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-29 21:24:18.712   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,10-29 21:24:18.712   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-29 21:24:18.713   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-29 21:24:18.718  3696  5798 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-29 21:24:18.718  3696  5798 I SystemUpdateService: now status is 0 (complete)
10-29 21:24:18.718  3696  5798 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-29 21:24:18.718  3696  5798 I SystemUpdateService: file has been verified
10-29 21:24:18.718  3696  5798 I SystemUpdateService: OTA package size = 21989297
,10-29 21:24:18.724  3696  5798 I SystemUpdateService: showing system update notification
,10-29 21:24:18.733  3696  3696 D SystemUpdateService: onDestroy
,10-29 21:24:18.783  5010  5802 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-29 21:24:18.874   927  3856 D WifiService: setWifiEnabled: false pid=5618, uid=10077
,10-29 21:24:18.874   927  3856 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 21:24:18.876   927  2949 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-29 21:24:18.876   927  2949 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-29 21:24:18.877   927  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-29 21:24:18.877   927  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 21:24:18.888   927  5787 D DhcpClient: Clearing IP address
10-29 21:24:18.888   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-29 21:24:18.891   507   921 D CommandListener: Setting iface cfg
,10-29 21:24:18.894  3548  5809 V NativeCrypto: Read error: ssl=0x7f5a6c7300: I/O error during system call, Connection timed out
,10-29 21:24:18.895   927  5788 D DhcpClient: Receive thread stopped
10-29 21:24:18.895  3548  5809 V NativeCrypto: SSL shutdown failed: ssl=0x7f5a6c7300: I/O error during system call, Broken pipe
,10-29 21:24:18.901   927  3565 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,10-29 21:24:18.902   927  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-29 21:24:18.902   927  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-29 21:24:18.904   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-29 21:24:18.904   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-29 21:24:18.908   538   538 E Parcel  : Reading a NULL string not supported here.
,10-29 21:24:18.912   927   927 D RttService: SCAN_AVAILABLE : 1
10-29 21:24:18.912   927  3059 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-29 21:24:18.913   927  2951 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-29 21:24:18.914  3745  3884 W QCNEJ   : |CORE| network lost: 101
10-29 21:24:18.914   927  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
10-29 21:24:18.914  3745  3884 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-29 21:24:18.916   927  2949 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-29 21:24:18.920   927  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-29 21:24:18.936   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 21:24:18.956   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 21:24:18.956   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-29 21:24:18.956   927  2951 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-29 21:24:18.956   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-29 21:24:18.960   927  2949 D DhcpClient: doQuit
,10-29 21:24:18.960   927  2949 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-29 21:24:18.960   927  5787 D DhcpClient: onQuitting
10-29 21:24:18.961  5782  5782 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-29 21:24:18.961  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.961  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:18.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:18.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:18.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:18.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:18.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:18.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:18.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:18.961  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.961  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:18.962   927   945 D Tethering: MasterInitialState.processMessage what=3
10-29 21:24:18.964  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.964  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:18.964  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:18.964  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:18.964  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:18.964  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:18.964  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:18.964  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:18.964  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:18.964  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.964  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:18.964  4904  4904 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-29 21:24:18.967  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.967  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:18.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:18.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertise,ment supported: SUPPORTED
10-29 21:24:18.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:18.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:18.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:18.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:18.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:18.967  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.967  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:18.968  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.968  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:18.968  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:18.968  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:18.968  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:18.968  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:18.968  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:18.968  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:18.968  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:18.968  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:18.968  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:18.969  3696  3696 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-29 21:24:18.969  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:18.969  5037  5061 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-29 21:24:18.969  5037  5061 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-29 21:24:18.969  5037  5061 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-29 21:24:18.970  5037  5061 E SarControlService: no key has been found,reset the power
10-29 21:24:18.970  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-29 21:24:18.970  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-29 21:24:18.970  5782  5782 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-29 21:24:18.970  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:18.970  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-29 21:24:18.970  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 21:24:18.971  5062  5062 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-29 21:24:18.972  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-29 21:24:18.972  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-29 21:24:18.972  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-29 21:24:18.972  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 21:24:18.973  5782  5782 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-29 21:24:18.973  5062  5062 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-29 21:24:18.976  3696  3696 D SystemUpdateService: onCreate
10-29 21:24:18.977  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cf381fc HexData = [00000000ee03000000000000ffffffff]
10-29 21:24:18.977  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 21:24:18.977  5062  5076 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-29 21:24:18.977  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 21:24:18.978  5037  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-29 21:24:18.980  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cf381fc HexData = [00000000ef03000000000000ffffffff]
10-29 21:24:18.980  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 21:24:18.980  5062  5076 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-29 21:24:18.981  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 21:24:18.981  5037  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-29 21:24:18.982  3696  3696 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-29 21:24:18.985  3696  5818 I SystemUpdateService: active receiver: enabled
,10-29 21:24:18.990  3696  3696 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-29 21:24:18.996  3696  5407 I iu.UploadsManager: num queued entries: 0
,10-29 21:24:18.996  3696  5407 I iu.UploadsManager: num updated entries: 0
10-29 21:24:18.997  3696  5407 I iu.SyncManager: NEXT; no task
,10-29 21:24:18.999  3696  3696 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-29 21:24:19.001  3696  3696 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-29 21:24:19.002  5744  5744 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-29 21:24:19.006  5744  5744 D SprintDMHelper: simOperator: 
10-29 21:24:19.006  5744  5744 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-29 21:24:19.011   507   921 E Netd    : netlink response contains error (No such file or directory)
10-29 21:24:19.012   927  2951 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-29 21:24:19.012   927  2951 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-29 21:24:19.013  3696  5818 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-29 21:24:19.016  5782  5782 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-29 21:24:19.017  5010  5822 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-29 21:24:19.021  3696  5818 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-29 21:24:19.021  3696  5818 I SystemUpdateService: now status is 0 (complete)
10-29 21:24:19.021  3696  5818 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-29 21:24:19.021  3696  5818 I SystemUpdateService: file has been verified
10-29 21:24:19.021  3696  5818 I SystemUpdateService: OTA package size = 21989297
,10-29 21:24:19.032  5782  5782 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-29 21:24:19.036  3696  5818 I SystemUpdateService: showing system update notification
,10-29 21:24:19.043  3696  3696 D SystemUpdateService: onDestroy
,10-29 21:24:19.133   927  2949 D wifi    : In wifi stop Hal
10-29 21:24:19.133   927  2949 D wifi    : halHandle = 0x7f5849d180, mVM = 0x7f74acd140, mCls = 0x19ba
,10-29 21:24:19.134   927  5781 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-29 21:24:19.134   927  5781 D WifiHAL : Got a signal to exit!!!
10-29 21:24:19.134   927  5781 I WifiHAL : Exit wifi_event_loop
10-29 21:24:19.134   927  2949 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-29 21:24:19.134   927  2949 E WifiHAL : Event processing terminated
10-29 21:24:19.134   927  2949 D wifi    : In wifi cleaned up handler
10-29 21:24:19.135   927  2949 I WifiHAL : Internal cleanup completed
,10-29 21:24:19.138  5010  5010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-29 21:24:19.138  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:19.139  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:19.140  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:19.140  4031  4193 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-29 21:24:19.159   927  5781 D wifi    : set interface wlan0 flags (DOWN)
,10-29 21:24:19.159   927  2949 D WifiNative-HAL: HAL event thread stopped successfully
,10-29 21:24:19.367   927   945 D Tethering: InitialState.processMessage what=4
,10-29 21:24:19.373   927   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-29 21:24:19.623   927  2951 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-29 21:24:23.912   927   945 I ActivityManager: Start proc 5824:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-29 21:24:24.003  5824  5824 D AdapterServiceConfig: Adding HeadsetService
10-29 21:24:24.003  5824  5824 D AdapterServiceConfig: Adding A2dpService
10-29 21:24:24.003  5824  5824 D AdapterServiceConfig: Adding HidService
10-29 21:24:24.004  5824  5824 D AdapterServiceConfig: Adding HealthService
10-29 21:24:24.004  5824  5824 D AdapterServiceConfig: Adding PanService
10-29 21:24:24.004  5824  5824 D AdapterServiceConfig: Adding GattService
10-29 21:24:24.004  5824  5824 D AdapterServiceConfig: Adding BluetoothMapService
10-29 21:24:24.004  5824  5824 D AdapterServiceConfig: Adding SapService
,10-29 21:24:24.014   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4d7c29a:true
,10-29 21:24:24.014  5824  5824 D BluetoothAdapterState: make() - Creating AdapterState
,10-29 21:24:24.016  5824  5824 I bt_bluedroid: init
,10-29 21:24:24.016  5824  5836 I BluetoothAdapterState: Entering OffState
,10-29 21:24:24.019  5824  5837 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-29 21:24:24.019  5824  5837 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-29 21:24:24.019  5824  5837 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-29 21:24:24.019  5824  5837 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-29 21:24:24.019  5824  5824 I bt_bluedroid: get_profile_interface socket
,10-29 21:24:24.021  5824  5840 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-29 21:24:24.021  5824  5824 I bt_bluedroid: get_profile_interface sdp
10-29 21:24:24.023  5824  5840 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-29 21:24:24.026  5824  5835 I bt_bluedroid: config_hci_snoop_log
10-29 21:24:24.027   927   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-29 21:24:24.031  5824  5836 D BluetoothAdapterState: Current state: OFF, message: 0
10-29 21:24:24.031  5824  5836 D BluetoothAdapterProperties: Setting state to 14
,10-29 21:24:24.031  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-29 21:24:24.033  5824  5836 D BluetoothBondStateMachine: make
,10-29 21:24:24.035  5824  5841 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-29 21:24:24.037  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
,10-29 21:24:24.038  5824  5824 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-29 21:24:24.040  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:24.041  5824  5824 D BtGatt.DebugUtils: handleDebugAction() action=null
10-29 21:24:24.042  5824  5824 D BtGatt.GattService: Received start request. Starting profile...
10-29 21:24:24.042  5824  5824 D BtGatt.GattService: start()
10-29 21:24:24.042  5824  5824 I bt_bluedroid: get_profile_interface gatt
,10-29 21:24:24.043  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
,10-29 21:24:24.043  5824  5824 D BtGatt.AdvertiseManager: advertise manager created
,10-29 21:24:24.048  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:24.048  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:24.048  5824  5824 V BluetoothAdapterState: isBleTurningOn()=true
10-29 21:24:24.048  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:24.048  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-29 21:24:24.049  5824  5836 I bt_bluedroid: bt_bluedroid
10-29 21:24:24.050  5824  5837 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-29 21:24:24.050  5824  5837 I bt_hci  : start_up
,10-29 21:24:24.055  5824  5837 I bt_vendor: alloc value 0xf3f4d871
,10-29 21:24:24.055  5824  5837 I bt_vendor: init
10-29 21:24:24.055  5824  5837 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-29 21:24:24.055  5824  5837 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-29 21:24:24.167  5824  5837 D bt_hci  : start_up starting async portion
,10-29 21:24:24.167  5824  5844 I bt_hci  : event_finish_startup
10-29 21:24:24.167  5824  5844 I bt_hci_h4: hal_open
,10-29 21:24:24.167  5824  5844 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-29 21:24:24.184  5824  5844 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-29 21:24:24.187  5824  5844 D bt_hwcfg: Chipset BCM4358A3
,10-29 21:24:24.187  5824  5844 D bt_hwcfg: Target name = [BCM4358A3]
10-29 21:24:24.187  5824  5844 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-29 21:24:24.590  5824  5844 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-29 21:24:24.590  5824  5844 D bt_hwcfg: Settlement delay -- 100 ms
,10-29 21:24:24.590  5824  5844 I bt_hwcfg: Setting fw settlement delay to 100 
,10-29 21:24:24.724  5824  5844 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-29 21:24:24.725  5824  5844 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-29 21:24:24.726  5824  5844 I bt_hwcfg: vendor lib fwcfg completed
10-29 21:24:24.726  5824  5844 I bt_vendor: firmware callback
10-29 21:24:24.727  5824  5844 I bt_hci  : firmware_config_callback
,10-29 21:24:24.736  5824  5847 I bt_btu  : btu_task pending for preload complete event
,10-29 21:24:24.736  5824  5847 I bt_btu_task: Bluetooth chip preload is complete
10-29 21:24:24.736  5824  5847 I bt_btu  : btu_task received preload complete event
,10-29 21:24:24.745  5824  5847 I         : BTE_InitTraceLevels -- TRC_HCI
,10-29 21:24:24.745  5824  5847 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-29 21:24:24.745  5824  5847 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-29 21:24:24.746  5824  5847 I         : BTE_InitTraceLevels -- TRC_AVDT
10-29 21:24:24.746  5824  5847 I         : BTE_InitTraceLevels -- TRC_AVRC
10-29 21:24:24.746  5824  5847 I         : BTE_InitTraceLevels -- TRC_A2D
10-29 21:24:24.746  5824  5847 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-29 21:24:24.746  5824  5847 I         : BTE_InitTraceLevels -- TRC_BTM
10-29 21:24:24.746  5824  5847 I         : BTE_InitTraceLevels -- TRC_GAP
10-29 21:24:24.746  5824  5847 I         : BTE_InitTraceLevels -- TRC_PAN
10-29 21:24:24.746  5824  5847 I         : BTE_InitTraceLevels -- TRC_SDP
10-29 21:24:24.747  5824  5847 I         : BTE_InitTraceLevels -- TRC_GATT
10-29 21:24:24.747  5824  5847 I         : BTE_InitTraceLevels -- TRC_SMP
,10-29 21:24:24.747  5824  5847 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-29 21:24:24.747  5824  5847 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-29 21:24:24.830  5824  5847 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ecb549
10-29 21:24:24.830  5824  5847 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ecb549 
,10-29 21:24:24.840  5824  5840 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-29 21:24:24.841  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-29 21:24:24.842  5824  5840 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-29 21:24:24.844  5824  5840 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-29 21:24:24.848  5824  5840 D BluetoothAdapterProperties: Scan Mode:20
,10-29 21:24:24.848  5824  5840 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-29 21:24:24.849  5824  5840 D bt_hci  : do_postload posting postload work item
10-29 21:24:24.849  5824  5844 I bt_hci  : event_postload
,10-29 21:24:24.849  5824  5844 I bt_vendor: sco_config_cb
,10-29 21:24:24.849  5824  5844 I bt_hci  : sco_config_callback postload finished.
,10-29 21:24:24.850  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:24.851  5824  5840 D bt_bte_conf: Device ID record 1 : primary
10-29 21:24:24.851  5824  5840 D bt_bte_conf:   vendorId            = 000f
10-29 21:24:24.851  5824  5840 D bt_bte_conf:   vendorIdSource      = 0001
10-29 21:24:24.852  5824  5840 D bt_bte_conf:   product             = 1200
10-29 21:24:24.852  5824  5840 D bt_bte_conf:   version             = 1436
10-29 21:24:24.852  5824  5840 D bt_bte_conf:   clientExecutableURL = 
10-29 21:24:24.852  5824  5840 D bt_bte_conf:   serviceDescription  = 
10-29 21:24:24.852  5824  5840 D bt_bte_conf:   documentationURL    = 
10-29 21:24:24.852  5824  5840 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-29 21:24:24.852  5824  5837 D bt_stack_manager: event_start_up_stack finished
,10-29 21:24:24.853  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:24.856  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:24.857  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-29 21:24:24.857  5824  5836 D BluetoothAdapterProperties: Setting state to 15
10-29 21:24:24.857  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-29 21:24:24.859  5824  5836 I BluetoothAdapterState: Entering BleOnState
,10-29 21:24:24.866  5824  5836 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-29 21:24:24.866  5824  5836 D BluetoothAdapterProperties: Setting state to 11
,10-29 21:24:24.866  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-29 21:24:24.866  5824  5844 I bt_vendor: low_power_mode_cb
10-29 21:24:24.871  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:24.876  5824  5824 D HeadsetService: Received start request. Starting profile...
10-29 21:24:24.879  5824  5824 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-29 21:24:24.879  5824  5824 D HeadsetStateMachine: make
,10-29 21:24:24.884  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:24.885  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:24.887  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
10-29 21:24:24.887  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:24.892  5824  5824 D HeadsetStateMachine: max_hf_connections = 1
10-29 21:24:24.893  5824  5824 I bt_bluedroid: get_profile_interface handsfree
,10-29 21:24:24.893  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-29 21:24:24.893  5824  5840 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-29 21:24:24.896  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:24.896  5824  5824 D A2dpService: Received start request. Starting profile...
,10-29 21:24:24.897  5824  5824 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-29 21:24:24.897  5824  5824 I bt_bluedroid: get_profile_interface avrcp
,10-29 21:24:24.903  5824  5824 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-29 21:24:24.903  5824  5824 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-29 21:24:24.904  5824  5824 D A2dpStateMachine: make
,10-29 21:24:24.906  5824  5824 I bt_bluedroid: get_profile_interface a2dp
,10-29 21:24:24.906  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-29 21:24:24.908  5824  5824 I BluetoothHidServiceJni: classInitNative: succeeds
,10-29 21:24:24.909  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
,10-29 21:24:24.911  5682  5682 D BluetoothInputDevice: Proxy object connected
,10-29 21:24:24.912  5824  5824 D HidService: Received start request. Starting profile...
,10-29 21:24:24.912  5682  5682 D HidProfile: Bluetooth service connected
10-29 21:24:24.912  5824  5824 I bt_bluedroid: get_profile_interface hidhost
10-29 21:24:24.912  5824  5840 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3eac56d
10-29 21:24:24.912  5824  5824 D HidService: setHidService(): set to: null
10-29 21:24:24.912  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-29 21:24:24.913  5824  5824 I BluetoothHealthServiceJni: classInitNative: succeeds
10-29 21:24:24.914  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
,10-29 21:24:24.914  5824  5855 D A2dpStateMachine: Enter Disconnected: -2
10-29 21:24:24.915  5824  5824 D HealthService: Received start request. Starting profile...
10-29 21:24:24.916  5824  5824 I bt_bluedroid: get_profile_interface health
,10-29 21:24:24.917  5824  5824 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-29 21:24:24.918  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
,10-29 21:24:24.919  5682  5682 D BluetoothPan: BluetoothPAN Proxy object connected
10-29 21:24:24.920  5682  5682 D PanProfile: Bluetooth service connected
,10-29 21:24:24.921  5824  5824 D PanService: Received start request. Starting profile...
,10-29 21:24:24.921  5824  5824 D BluetoothPanServiceJni: initializeNative(L110): pan
,10-29 21:24:24.921  5824  5824 I bt_bluedroid: get_profile_interface pan
10-29 21:24:24.924  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:24.922  5824  5840 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-29 21:24:24.925  5682  5682 D BluetoothMap: Proxy object connected
,10-29 21:24:24.925  5824  5824 D BluetoothMapService: Received start request. Starting profile...
10-29 21:24:24.925  5824  5824 D BluetoothMapService: start()
10-29 21:24:24.926  5682  5682 D MapProfile: Bluetooth service connected
10-29 21:24:24.926  5682  5682 D BluetoothMap: getConnectedDevices()
10-29 21:24:24.926  5682  5682 D BluetoothMap: Bluetooth is Not enabled
10-29 21:24:24.927  5824  5824 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-29 21:24:24.928  5824  5824 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-29 21:24:24.928  5824  5824 D BluetoothMapAppObserver: createReceiver()
,10-29 21:24:24.930  5824  5824 D BluetoothMapAppObserver: initObservers()
,10-29 21:24:24.930  5824  5824 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-29 21:24:24.937  5824  5824 V SapService: SapBinder()
,10-29 21:24:24.937  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:24.937  3548  3548 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 21:24:24.937  5824  5824 D SapService: Received start request. Starting profile...
10-29 21:24:24.937  5824  5824 V SapService: start()
,10-29 21:24:24.940  5824  5824 V BluetoothAdapterState: isTurningOff()=false
,10-29 21:24:24.940  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:24.940  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:24.940  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:24.941  5824  5852 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:24.941  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:24.942  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:24.942  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:24.942  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:24.942  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:24.943  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:24.943  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:24.943  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:24.943  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:24.944  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-29 21:24:24.944  5824  5836 D BluetoothAdapterProperties: ScanMode =  20
10-29 21:24:24.944  5824  5836 D BluetoothAdapterProperties: State =  11
10-29 21:24:24.944  5824  5836 D BluetoothAdapterProperties: Setting state to 12
10-29 21:24:24.944  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-29 21:24:24.945  5824  5836 I BluetoothAdapterState: Entering OnState
,10-29 21:24:24.945  5682  5694 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-29 21:24:24.946  3118  3132 D BluetoothPan: onBluetoothStateChange on: true
10-29 21:24:24.948  5824  5840 D BluetoothAdapterProperties: Scan Mode:21
10-29 21:24:24.948  5824  5840 D BluetoothAdapterProperties: Discoverable Timeout:120
10-29 21:24:24.948  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-29 21:24:24.948  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
10-29 21:24:24.948  5682  5693 D BluetoothMap: onBluetoothStateChange: up=true
10-29 21:24:24.948  3118  3118 D PanProfile: Bluetooth service connected
,10-29 21:24:24.949  5682  5694 D BluetoothPbap: onBluetoothStateChange: up=true
10-29 21:24:24.950  5682  5693 D BluetoothPan: onBluetoothStateChange on: true
10-29 21:24:24.950  3118  3131 D BluetoothMap: onBluetoothStateChange: up=true
10-29 21:24:24.951  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:24.951  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:24.951  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:24.951  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:24.951  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:24.951  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:24.951  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:24.951  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:24.952  3118  3118 D BluetoothMap: Proxy object connected
10-29 21:24:24.952  3118  3132 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:24.952  3118  3118 D MapProfile: Bluetooth service connected
10-29 21:24:24.952  3118  3118 D BluetoothMap: getConnectedDevices()
10-29 21:24:24.953  3118  3131 D BluetoothA2dp: onBluetoothStateChange: up=true
10-29 21:24:24.954  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-29 21:24:24.955  3118  3937 D BluetoothPbap: onBluetoothStateChange: up=true
10-29 21:24:24.955  5824  5824 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-29 21:24:24.955  5824  5824 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-29 21:24:24.957   927   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-29 21:24:24.957  5824  5824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 21:24:24.957   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:24.958  3118  3132 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-29 21:24:24.959  5824  5824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 21:24:24.959   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:24.960  3118  3118 D BluetoothInputDevice: Proxy object connected
10-29 21:24:24.960  3118  3118 D HidProfile: Bluetooth service connected
10-29 21:24:24.960  3782  3964 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:24.960   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:24.961  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:24.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:24.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:24.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:24.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:24.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:24.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:24.961  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 21:24:24.962  5824  5824 D ObexServerSockets: Succeed to create listening sockets 
,10-29 21:24:24.962  5824  5824 D ObexServerSockets0: startAccept()
10-29 21:24:24.962  5824  5824 D ObexServerSockets0: prepareForNewConnect()
10-29 21:24:24.963  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:24.963   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-29 21:24:24.965  5824  5824 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-29 21:24:24.965  5824  5824 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-29 21:24:24.967  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:24.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:24.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:24.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:24.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:24.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:24.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:24.967  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 21:24:24.967  5682  5682 D LocalBluetoothProfileManager: Adding local A2DP profile
10-29 21:24:24.969  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:24.969  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-29 21:24:24.970  5824  5861 D ObexServerSockets0: Accepting socket connection...
10-29 21:24:24.970  5824  5862 D ObexServerSockets0: Accepting socket connection...
10-29 21:24:24.970  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:24.970   927   927 D BluetoothA2dp: Proxy object connected
10-29 21:24:24.970  5824  5824 D BluetoothMapService: onReceive
,10-29 21:24:24.971  5824  5824 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-29 21:24:24.971  5824  5824 D BluetoothMapService: STATE_ON
,10-29 21:24:24.971  3118  3118 D BluetoothA2dp: Proxy object connected
10-29 21:24:24.974  5824  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 21:24:24.974  5682  5682 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-29 21:24:24.974  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:24.975  5824  5864 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-29 21:24:24.975  5824  5864 D BluetoothSdpJni: SDP Create record success - handle: 1
10-29 21:24:24.976  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:24.981  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-29 21:24:24.982  5682  5682 D BluetoothA2dp: Proxy object connected
,10-29 21:24:24.989  3548  3548 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 21:24:24.994  3118  3118 D BluetoothPbap: Proxy object connected
10-29 21:24:24.994  3118  3118 D PbapServerProfile: Bluetooth service connected
,10-29 21:24:24.995  5824  5824 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-29 21:24:24.995  5824  5824 D ObexServerSockets0: prepareForNewConnect()
,10-29 21:24:24.998  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,10-29 21:24:24.999  5682  5682 D BluetoothPbap: Proxy object connected
10-29 21:24:24.999  5682  5682 D PbapServerProfile: Bluetooth service connected
,10-29 21:24:25.003  5824  5868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 21:24:25.017  5824  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 21:24:25.018  5824  5872 I BtOppRfcommListener: Accept thread started.
,10-29 21:24:25.054   927   927 D BluetoothHeadset: Proxy object connected
,10-29 21:24:25.054   927   927 D BluetoothHeadset: Proxy object connected
10-29 21:24:25.055  3782  3806 D BluetoothHeadset: Proxy object connected
10-29 21:24:25.055   927   927 D BluetoothHeadset: Proxy object connected
10-29 21:24:25.055  3118  3131 D BluetoothHeadset: Proxy object connected
10-29 21:24:25.056  3118  3118 D HeadsetProfile: Bluetooth service connected
,10-29 21:24:25.057   927   945 D BluetoothHeadset: Proxy object connected
,10-29 21:24:25.060   927   945 D BluetoothHeadset: Proxy object connected
,10-29 21:24:25.060  3782  3808 D BluetoothHeadset: Proxy object connected
10-29 21:24:25.061   927   945 D BluetoothHeadset: Proxy object connected
,10-29 21:24:25.077  5682  5693 D BluetoothHeadset: Proxy object connected
,10-29 21:24:25.078  5682  5682 D HeadsetProfile: Bluetooth service connected
,10-29 21:24:26.581   927  2951 D ConnectivityService: handlePromptUnvalidated 101
,10-29 21:24:27.680   541   541 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-29 21:24:27.680   541   541 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-29 21:24:28.892  5824  5836 D BluetoothAdapterState: Current state: ON, message: 23
,10-29 21:24:28.892  5824  5836 D BluetoothAdapterProperties: Setting state to 13
,10-29 21:24:28.892  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-29 21:24:28.894  5824  5836 D BluetoothAdapterProperties: onBluetoothDisable()
,10-29 21:24:28.896  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
,10-29 21:24:28.899  5824  5824 D BluetoothMapService: onReceive
10-29 21:24:28.899  5824  5824 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-29 21:24:28.900  5824  5824 D BluetoothMapService: STATE_TURNING_OFF
,10-29 21:24:28.900  5824  5824 D BluetoothMapService: MAP Service closeService in
10-29 21:24:28.900  5824  5824 D BluetoothMapMasInstance0: MAP Service shutdown
10-29 21:24:28.901  5824  5824 D ObexServerSockets0: shutdown(block = true)
10-29 21:24:28.903  5824  5861 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-29 21:24:28.904  5824  5840 D BluetoothAdapterProperties: Scan Mode:20
10-29 21:24:28.905  5824  5824 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-29 21:24:28.906  5824  5824 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-29 21:24:28.906  5824  5862 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-29 21:24:28.906  5824  5849 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-29 21:24:28.906  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-29 21:24:28.907  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:28.907  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:28.907  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:28.907  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:28.907  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:28.907  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:28.907  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:28.907  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:28.907  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:28.911  5824  5824 I BtOppRfcommListener: stopping Accept Thread
10-29 21:24:28.911  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:28.911  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-29 21:24:28.913  5824  5872 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-29 21:24:28.914  5824  5872 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-29 21:24:28.917  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-29 21:24:28.917  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:28.917  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:28.917  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:28.917  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:28.917  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:28.917  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:28.917  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:28.917  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:28.919  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:28.919  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:28.920  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-29 21:24:28.921  5824  5824 D HeadsetService: Received stop request...Stopping profile...
,10-29 21:24:28.924  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:28.924  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:28.924  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:28.924  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:28.924  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:28.924  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-29 21:24:28.924  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:28.924  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:28.924  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 21:24:28.926  5618  5618 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-29 21:24:28.926  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:28.926   927   927 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:28.927  5824  5824 D A2dpService: Received stop request...Stopping profile...
10-29 21:24:28.928  5824  5855 D A2dpStateMachine: Exit Disconnected: -1
10-29 21:24:28.929  5682  5694 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:28.929   927   927 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:28.929  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:28.929  3782  3964 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:28.930   927   927 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:28.930  3118  3132 D BluetoothHeadset: Proxy object disconnected
10-29 21:24:28.931   927   927 D BluetoothA2dp: Proxy object disconnected
10-29 21:24:28.932  5824  5824 D HidService: Received stop request...Stopping profile...
10-29 21:24:28.932  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:28.932  5824  5824 D HidService: Stopping Bluetooth HidService
10-29 21:24:28.933  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:28.934  5682  5682 D DockEventReceiver: finishStartingService: stopping service
10-29 21:24:28.935  5824  5824 D HealthService: Received stop request...Stopping profile...
10-29 21:24:28.935  5682  5682 D HeadsetProfile: Bluetooth service disconnected
10-29 21:24:28.936  5682  5682 D BluetoothA2dp: Proxy object disconnected
10-29 21:24:28.936  5682  5682 D BluetoothInputDevice: Proxy object disconnected
10-29 21:24:28.936  5682  5682 D HidProfile: Bluetooth service disconnected
10-29 21:24:28.937  5824  5824 D PanService: Received stop request...Stopping profile...
10-29 21:24:28.939  5682  5682 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-29 21:24:28.939  5682  5682 D PanProfile: Bluetooth service disconnected
10-29 21:24:28.940  3118  3118 D BluetoothA2dp: Proxy object disconnected
10-29 21:24:28.940  3118  3118 D HeadsetProfile: Bluetooth service disconnected
10-29 21:24:28.940  3118  3118 D BluetoothInputDevice: Proxy object disconnected
10-29 21:24:28.940  3118  3118 D HidProfile: Bluetooth service disconnected
10-29 21:24:28.940  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-29 21:24:28.940  3118  3118 D PanProfile: Bluetooth service disconnected
10-29 21:24:28.941  5824  5824 D BluetoothMapService: Received stop request...Stopping profile...
10-29 21:24:28.941  5824  5824 D BluetoothMapService: stop()
,10-29 21:24:28.942  5824  5824 D BluetoothMapAppObserver: deinitObservers()
10-29 21:24:28.942  5824  5824 D BluetoothMapAppObserver: removeReceiver()
10-29 21:24:28.944  3118  3118 D BluetoothMap: Proxy object disconnected
10-29 21:24:28.944  5682  5682 D BluetoothMap: Proxy object disconnected
,10-29 21:24:28.944  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:28.944  3118  3118 D MapProfile: Bluetooth service disconnected
10-29 21:24:28.944  5682  5682 D MapProfile: Bluetooth service disconnected
10-29 21:24:28.944  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:28.944  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:28.944  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:28.945  5824  5824 D SapService: Received stop request...Stopping profile...
10-29 21:24:28.945  5824  5824 V SapService: stop()
,10-29 21:24:28.950  3548  3548 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-29 21:24:28.950  5824  5824 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-29 21:24:28.950  5824  5824 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-29 21:24:28.951  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:28.951  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:28.951  5824  5824 V BluetoothAdapterState: isTurningOff()=true
,10-29 21:24:28.951  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:28.951  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:28.951  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:28.951  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-29 21:24:28.951  5824  5840 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-29 21:24:28.951  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:28.961  5824  5824 V BluetoothAdapterState: isTurningOff()=true
,10-29 21:24:28.962  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:28.962  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:28.962  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:28.962  5824  5824 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-29 21:24:28.962  5824  5824 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-29 21:24:28.962  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:28.962  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-29 21:24:28.962  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:28.962  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:28.962  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:28.962  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:28.962  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-29 21:24:28.962  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:28.962  5824  5824 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-29 21:24:28.963  5824  5847 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-29 21:24:28.963  5824  5847 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-29 21:24:28.963  5824  5847 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-29 21:24:28.963  5824  5824 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-29 21:24:28.963  5824  5847 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-29 21:24:28.963  5824  5840 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-29 21:24:28.963  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:28.963  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:28.963  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:28.963  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:28.963  5824  5824 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-29 21:24:28.964  5824  5824 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-29 21:24:28.964  5824  5824 D BluetoothMapService: MAP Service closeService in
10-29 21:24:28.964  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:28.965  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:28.965  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:28.965  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:28.965  5824  5824 D BluetoothMapService: cleanup()
10-29 21:24:28.965  5824  5824 D BluetoothMapService: MAP Service closeService in
10-29 21:24:28.965  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-29 21:24:28.965  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:28.965  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:28.965  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:28.965  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-29 21:24:28.966  5824  5836 D BluetoothAdapterProperties: Setting state to 15
10-29 21:24:28.966  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-29 21:24:28.966  5824  5836 I BluetoothAdapterState: Entering BleOnState
,10-29 21:24:28.966  5682  5693 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-29 21:24:28.967  3118  3132 D BluetoothPan: onBluetoothStateChange on: false
10-29 21:24:28.967  5682  5694 D BluetoothMap: onBluetoothStateChange: up=false
,10-29 21:24:28.969  5682  5693 D BluetoothPbap: onBluetoothStateChange: up=false
10-29 21:24:28.970  3118  3118 D BluetoothPbap: Proxy object disconnected
,10-29 21:24:28.970  3118  3118 D PbapServerProfile: Bluetooth service disconnected
10-29 21:24:28.970  5682  5694 D BluetoothPan: onBluetoothStateChange on: false
10-29 21:24:28.971  3118  3132 D BluetoothMap: onBluetoothStateChange: up=false
,10-29 21:24:28.972  3118  3937 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-29 21:24:28.972  3118  3131 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-29 21:24:28.974  3118  3132 D BluetoothPbap: onBluetoothStateChange: up=false
,10-29 21:24:28.975   927   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-29 21:24:28.975  5682  5693 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:28.975   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:28.976  3118  3937 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-29 21:24:28.976  5682  5694 D BluetoothA2dp: onBluetoothStateChange: up=false
10-29 21:24:28.976   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:28.977  3782  3806 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:28.977   927   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-29 21:24:28.977  5824  5836 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-29 21:24:28.977  5824  5836 D BluetoothAdapterProperties: Setting state to 16
10-29 21:24:28.977  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-29 21:24:28.979  5824  5836 D BluetoothAdapterProperties: onBleDisable
10-29 21:24:28.979  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
10-29 21:24:28.979  5824  5837 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-29 21:24:28.980  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:28.980  5824  5847 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-29 21:24:28.981  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-29 21:24:28.982  5824  5840 D BluetoothAdapterProperties: Scan Mode:20
10-29 21:24:28.982  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:28.984  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:28.986  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-29 21:24:28.986  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:28.987  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:28.988  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:28.991  3548  3548 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-29 21:24:28.991  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,10-29 21:24:29.190  5824  5840 I bt_hci  : shut_down
,10-29 21:24:29.196  5824  5844 D bt_hwcfg: hw_epilog_process
,10-29 21:24:29.196  5824  5844 I bt_vendor: low_power_mode_cb
,10-29 21:24:29.198  5824  5844 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-29 21:24:29.198  5824  5844 I bt_vendor: epilog_cb
10-29 21:24:29.198  5824  5844 I bt_hci  : epilog_finished_callback
,10-29 21:24:29.200  5824  5840 I bt_hci_h4: hal_close
,10-29 21:24:29.201  5824  5840 I bt_userial_vendor: device fd = 54 close
,10-29 21:24:29.309  5824  5837 D bt_stack_manager: event_shut_down_stack finished.
,10-29 21:24:29.310  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-29 21:24:29.314  5824  5836 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-29 21:24:29.315  5824  5824 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-29 21:24:29.316  5824  5824 D BtGatt.GattService: Received stop request...Stopping profile...
,10-29 21:24:29.316  5824  5824 D BtGatt.GattService: stop()
10-29 21:24:29.316  5824  5824 D BtGatt.AdvertiseManager: advertise clients cleared
,10-29 21:24:29.321  5824  5824 V BluetoothAdapterState: isTurningOff()=false
,10-29 21:24:29.321  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:29.321  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:29.321  5824  5824 V BluetoothAdapterState: isBleTurningOff()=true
10-29 21:24:29.322  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-29 21:24:29.322  5824  5836 D BluetoothAdapterProperties: Setting state to 10
,10-29 21:24:29.323  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-29 21:24:29.324  5824  5836 I BluetoothAdapterState: Entering OffState
10-29 21:24:29.325   927   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-29 21:24:29.338  5824  5824 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-29 21:24:29.339  5824  5824 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-29 21:24:29.339  5824  5824 I BluetoothServiceJni: cleanupNative: return from cleanup
10-29 21:24:29.341  5824  5837 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-29 21:24:29.351  5824  5824 I art     : System.exit called, status: 0
,10-29 21:24:29.351  5824  5824 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-29 21:24:29.377   927  3549 I ActivityManager: Process com.android.bluetooth (pid 5824) has died
,10-29 21:24:33.890  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
,10-29 21:24:33.890  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:33.896  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 21:24:33.896  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b0eb0b removed from the list
,10-29 21:24:33.896  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
,10-29 21:24:33.896  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:33.897  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:33.899  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:33.899  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c71c01 added. We now have 4 listener(s)
,10-29 21:24:33.899  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:33.902  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 21:24:33.902  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c71c01 removed from the list
10-29 21:24:33.902  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:33.902  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:24:33.902  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:33.904  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:33.904  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4156aa6 added. We now have 4 listener(s)
10-29 21:24:33.905  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 21:24:37.682   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:38.683   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:38.915  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:38.953   927   945 I ActivityManager: Start proc 5884:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-29 21:24:39.036  5884  5884 D AdapterServiceConfig: Adding HeadsetService
,10-29 21:24:39.037  5884  5884 D AdapterServiceConfig: Adding A2dpService
10-29 21:24:39.037  5884  5884 D AdapterServiceConfig: Adding HidService
10-29 21:24:39.037  5884  5884 D AdapterServiceConfig: Adding HealthService
10-29 21:24:39.037  5884  5884 D AdapterServiceConfig: Adding PanService
10-29 21:24:39.037  5884  5884 D AdapterServiceConfig: Adding GattService
10-29 21:24:39.037  5884  5884 D AdapterServiceConfig: Adding BluetoothMapService
10-29 21:24:39.037  5884  5884 D AdapterServiceConfig: Adding SapService
,10-29 21:24:39.048   927   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f1ce78b:true
,10-29 21:24:39.048  5884  5884 D BluetoothAdapterState: make() - Creating AdapterState
,10-29 21:24:39.051  5884  5884 I bt_bluedroid: init
,10-29 21:24:39.052  5884  5896 I BluetoothAdapterState: Entering OffState
,10-29 21:24:39.053  5884  5897 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-29 21:24:39.054  5884  5897 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-29 21:24:39.054  5884  5897 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-29 21:24:39.054  5884  5897 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-29 21:24:39.054  5884  5884 I bt_bluedroid: get_profile_interface socket
,10-29 21:24:39.056  5884  5900 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-29 21:24:39.056  5884  5884 I bt_bluedroid: get_profile_interface sdp
10-29 21:24:39.058  5884  5900 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-29 21:24:39.062  5884  5895 I bt_bluedroid: config_hci_snoop_log
10-29 21:24:39.063   927   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-29 21:24:39.067  5884  5896 D BluetoothAdapterState: Current state: OFF, message: 0
10-29 21:24:39.067  5884  5896 D BluetoothAdapterProperties: Setting state to 14
10-29 21:24:39.067  5884  5896 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-29 21:24:39.069  5884  5896 D BluetoothBondStateMachine: make
10-29 21:24:39.071  5884  5901 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-29 21:24:39.073  5884  5896 I BluetoothAdapterState: Entering PendingCommandState
10-29 21:24:39.074  5884  5884 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
10-29 21:24:39.077  5884  5884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:39.077  5884  5884 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-29 21:24:39.078  5884  5884 D BtGatt.GattService: Received start request. Starting profile...
10-29 21:24:39.078  5884  5884 D BtGatt.GattService: start()
10-29 21:24:39.078  5884  5884 I bt_bluedroid: get_profile_interface gatt
,10-29 21:24:39.079  5884  5884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:39.079  5884  5884 D BtGatt.AdvertiseManager: advertise manager created
,10-29 21:24:39.085  5884  5884 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:39.085  5884  5884 V BluetoothAdapterState: isTurningOn()=false
10-29 21:24:39.085  5884  5884 V BluetoothAdapterState: isBleTurningOn()=true
,10-29 21:24:39.085  5884  5884 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:39.086  5884  5896 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-29 21:24:39.087  5884  5896 I bt_bluedroid: bt_bluedroid
10-29 21:24:39.087  5884  5897 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-29 21:24:39.087  5884  5897 I bt_hci  : start_up
,10-29 21:24:39.092  5884  5897 I bt_vendor: alloc value 0xf3f4d871
10-29 21:24:39.092  5884  5897 I bt_vendor: init
10-29 21:24:39.092  5884  5897 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,10-29 21:24:39.093  5884  5897 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-29 21:24:39.203  5884  5897 D bt_hci  : start_up starting async portion
,10-29 21:24:39.203  5884  5904 I bt_hci  : event_finish_startup
,10-29 21:24:39.204  5884  5904 I bt_hci_h4: hal_open
10-29 21:24:39.204  5884  5904 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-29 21:24:39.204  5905  5905 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-29 21:24:39.207  5884  5904 I bt_userial_vendor: device fd = 54 open
,10-29 21:24:39.226  5884  5904 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-29 21:24:39.229  5884  5904 D bt_hwcfg: Chipset BCM4358A3
,10-29 21:24:39.230  5884  5904 D bt_hwcfg: Target name = [BCM4358A3]
10-29 21:24:39.230  5884  5904 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-29 21:24:39.684   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:39.748  5884  5904 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-29 21:24:39.749  5884  5904 D bt_hwcfg: Settlement delay -- 100 ms
10-29 21:24:39.749  5884  5904 I bt_hwcfg: Setting fw settlement delay to 100 
,10-29 21:24:39.881  5884  5904 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-29 21:24:39.882  5884  5904 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-29 21:24:39.884  5884  5904 I bt_hwcfg: vendor lib fwcfg completed
10-29 21:24:39.884  5884  5904 I bt_vendor: firmware callback
10-29 21:24:39.884  5884  5904 I bt_hci  : firmware_config_callback
,10-29 21:24:39.893  5884  5907 I bt_btu  : btu_task pending for preload complete event
,10-29 21:24:39.893  5884  5907 I bt_btu_task: Bluetooth chip preload is complete
10-29 21:24:39.893  5884  5907 I bt_btu  : btu_task received preload complete event
,10-29 21:24:39.901  5884  5907 I         : BTE_InitTraceLevels -- TRC_HCI
,10-29 21:24:39.901  5884  5907 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-29 21:24:39.901  5884  5907 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-29 21:24:39.901  5884  5907 I         : BTE_InitTraceLevels -- TRC_AVDT
10-29 21:24:39.901  5884  5907 I         : BTE_InitTraceLevels -- TRC_AVRC
10-29 21:24:39.902  5884  5907 I         : BTE_InitTraceLevels -- TRC_A2D
,10-29 21:24:39.902  5884  5907 I         : BTE_InitTraceLevels -- TRC_BNEP
10-29 21:24:39.902  5884  5907 I         : BTE_InitTraceLevels -- TRC_BTM
10-29 21:24:39.902  5884  5907 I         : BTE_InitTraceLevels -- TRC_GAP
,10-29 21:24:39.902  5884  5907 I         : BTE_InitTraceLevels -- TRC_PAN
10-29 21:24:39.902  5884  5907 I         : BTE_InitTraceLevels -- TRC_SDP
,10-29 21:24:39.902  5884  5907 I         : BTE_InitTraceLevels -- TRC_GATT
10-29 21:24:39.902  5884  5907 I         : BTE_InitTraceLevels -- TRC_SMP
,10-29 21:24:39.902  5884  5907 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-29 21:24:39.903  5884  5907 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-29 21:24:39.985  5884  5907 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ecb549
,10-29 21:24:39.985  5884  5907 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ecb549 
,10-29 21:24:40.009  5884  5900 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-29 21:24:40.011  5884  5900 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-29 21:24:40.011  5884  5900 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-29 21:24:40.014  5884  5900 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-29 21:24:40.016  5884  5900 D BluetoothAdapterProperties: Scan Mode:20
,10-29 21:24:40.017  5884  5900 D BluetoothAdapterProperties: Discoverable Timeout:120
10-29 21:24:40.017  5884  5900 D bt_hci  : do_postload posting postload work item
10-29 21:24:40.017  5884  5904 I bt_hci  : event_postload
10-29 21:24:40.017  5884  5904 I bt_vendor: sco_config_cb
,10-29 21:24:40.017  5884  5904 I bt_hci  : sco_config_callback postload finished.
10-29 21:24:40.022  5884  5900 D bt_bte_conf: Device ID record 1 : primary
10-29 21:24:40.022  5884  5900 D bt_bte_conf:   vendorId            = 000f
10-29 21:24:40.022  5884  5900 D bt_bte_conf:   vendorIdSource      = 0001
10-29 21:24:40.023  5884  5900 D bt_bte_conf:   product             = 1200
,10-29 21:24:40.023  5884  5900 D bt_bte_conf:   version             = 1436
10-29 21:24:40.023  5884  5900 D bt_bte_conf:   clientExecutableURL = 
10-29 21:24:40.023  5884  5900 D bt_bte_conf:   serviceDescription  = 
10-29 21:24:40.023  5884  5900 D bt_bte_conf:   documentationURL    = 
10-29 21:24:40.023  5884  5900 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-29 21:24:40.023  5884  5897 D bt_stack_manager: event_start_up_stack finished
10-29 21:24:40.024  5884  5896 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-29 21:24:40.024  5884  5896 D BluetoothAdapterProperties: Setting state to 15
,10-29 21:24:40.025  5884  5896 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-29 21:24:40.025  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:40.027  5884  5904 I bt_vendor: low_power_mode_cb
10-29 21:24:40.030  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:40.030  5884  5896 I BluetoothAdapterState: Entering BleOnState
10-29 21:24:40.031  5884  5896 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-29 21:24:40.031  5884  5896 D BluetoothAdapterProperties: Setting state to 11
10-29 21:24:40.031  5884  5896 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-29 21:24:40.035  5884  5884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
,10-29 21:24:40.038  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:40.040  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:40.040  5884  5884 D HeadsetService: Received start request. Starting profile...
10-29 21:24:40.043  5884  5884 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-29 21:24:40.043  5884  5884 D HeadsetStateMachine: make
,10-29 21:24:40.052  5884  5896 I BluetoothAdapterState: Entering PendingCommandState
,10-29 21:24:40.058  5884  5884 D HeadsetStateMachine: max_hf_connections = 1
,10-29 21:24:40.058  5884  5884 I bt_bluedroid: get_profile_interface handsfree
10-29 21:24:40.058  5884  5900 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-29 21:24:40.058  5884  5900 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
10-29 21:24:40.062  5884  5884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
,10-29 21:24:40.062  5884  5884 D A2dpService: Received start request. Starting profile...
,10-29 21:24:40.063  5884  5884 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-29 21:24:40.063  5884  5884 I bt_bluedroid: get_profile_interface avrcp
,10-29 21:24:40.071  5884  5884 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-29 21:24:40.071  5884  5884 I BluetoothA2dpServiceJni: classInitNative: succeeds
,10-29 21:24:40.071  5884  5884 D A2dpStateMachine: make
,10-29 21:24:40.073  5884  5884 I bt_bluedroid: get_profile_interface a2dp
,10-29 21:24:40.074  5884  5900 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-29 21:24:40.076  5884  5915 D A2dpStateMachine: Enter Disconnected: -2
,10-29 21:24:40.078  5884  5884 I BluetoothHidServiceJni: classInitNative: succeeds
,10-29 21:24:40.079  5884  5884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:40.079  3548  3548 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 21:24:40.079  5884  5884 D HidService: Received start request. Starting profile...
10-29 21:24:40.080  5884  5884 I bt_bluedroid: get_profile_interface hidhost
10-29 21:24:40.080  5884  5884 D HidService: setHidService(): set to: null
10-29 21:24:40.080  5884  5900 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3eac56d
10-29 21:24:40.080  5884  5900 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-29 21:24:40.080  5884  5884 I BluetoothHealthServiceJni: classInitNative: succeeds
10-29 21:24:40.081  5884  5884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
,10-29 21:24:40.082  5884  5884 D HealthService: Received start request. Starting profile...
,10-29 21:24:40.083  5884  5884 I bt_bluedroid: get_profile_interface health
10-29 21:24:40.084  5884  5884 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-29 21:24:40.084  5884  5884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
,10-29 21:24:40.085  5884  5884 D PanService: Received start request. Starting profile...
10-29 21:24:40.085  5884  5884 D BluetoothPanServiceJni: initializeNative(L110): pan
,10-29 21:24:40.085  5884  5884 I bt_bluedroid: get_profile_interface pan
10-29 21:24:40.086  5884  5900 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-29 21:24:40.088  5884  5884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:40.088  5884  5884 D BluetoothMapService: Received start request. Starting profile...
10-29 21:24:40.088  5884  5884 D BluetoothMapService: start()
10-29 21:24:40.091  5884  5884 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-29 21:24:40.092  5884  5884 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-29 21:24:40.092  5884  5884 D BluetoothMapAppObserver: createReceiver()
10-29 21:24:40.093  5884  5884 D BluetoothMapAppObserver: initObservers()
,10-29 21:24:40.093  5884  5884 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-29 21:24:40.099  5884  5884 V SapService: SapBinder()
,10-29 21:24:40.099  5884  5884 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
,10-29 21:24:40.101  5884  5884 D SapService: Received start request. Starting profile...
10-29 21:24:40.101  5884  5884 V SapService: start()
,10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isTurningOff()=false
,10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:40.103  5884  5913 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:40.103  5884  5884 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:40.104  5884  5884 V BluetoothAdapterState: isTurningOff()=false
,10-29 21:24:40.104  5884  5884 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:40.104  5884  5884 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:40.104  5884  5884 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:40.104  5884  5884 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:40.104  5884  5884 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:40.104  5884  5884 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:40.104  5884  5884 V BluetoothAdapterState: isBleTurningOff()=false
10-29 21:24:40.105  5884  5884 V BluetoothAdapterState: isTurningOff()=false
10-29 21:24:40.105  5884  5884 V BluetoothAdapterState: isTurningOn()=true
10-29 21:24:40.105  5884  5884 V BluetoothAdapterState: isBleTurningOn()=false
,10-29 21:24:40.105  5884  5884 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:40.105  5884  5884 V BluetoothAdapterState: isTurningOff()=false
,10-29 21:24:40.105  5884  5884 V BluetoothAdapterState: isTurningOn()=true
,10-29 21:24:40.105  5884  5884 V BluetoothAdapterState: isBleTurningOn()=false
10-29 21:24:40.105  5884  5884 V BluetoothAdapterState: isBleTurningOff()=false
,10-29 21:24:40.106  5884  5896 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-29 21:24:40.106  5884  5896 D BluetoothAdapterProperties: ScanMode =  20
10-29 21:24:40.106  5884  5896 D BluetoothAdapterProperties: State =  11
10-29 21:24:40.110  5884  5900 D BluetoothAdapterProperties: Scan Mode:21
10-29 21:24:40.110  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-29 21:24:40.110  5884  5900 D BluetoothAdapterProperties: Discoverable Timeout:120
10-29 21:24:40.110  5884  5896 D BluetoothAdapterProperties: Setting state to 12
10-29 21:24:40.110  5884  5896 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-29 21:24:40.111  5682  5693 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-29 21:24:40.111  5884  5896 I BluetoothAdapterState: Entering OnState
10-29 21:24:40.113  3118  3131 D BluetoothPan: onBluetoothStateChange on: true
10-29 21:24:40.113  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:40.113  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:40.113  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:40.113  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:40.113  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:40.113  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:40.113  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:40.113  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:40.114  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:40.115  5682  5682 D BluetoothInputDevice: Proxy object connected
10-29 21:24:40.115  5682  5879 D BluetoothMap: onBluetoothStateChange: up=true
10-29 21:24:40.115  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
10-29 21:24:40.115  3118  3118 D PanProfile: Bluetooth service connected
10-29 21:24:40.117  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:40.117  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:40.117  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:40.117  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:40.117  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:40.117  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:40.117  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:40.117  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:40.117  5682  5694 D BluetoothPbap: onBluetoothStateChange: up=true
,10-29 21:24:40.118  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-29 21:24:40.118  5682  5693 D BluetoothPan: onBluetoothStateChange on: true
10-29 21:24:40.119  5884  5884 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-29 21:24:40.119  5884  5884 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-29 21:24:40.120  3118  3132 D BluetoothMap: onBluetoothStateChange: up=true
10-29 21:24:40.121  5884  5884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 21:24:40.121  3118  3118 D BluetoothMap: Proxy object connected
10-29 21:24:40.121  3118  3118 D MapProfile: Bluetooth service connected
10-29 21:24:40.121  3118  3131 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:40.122  3118  3118 D BluetoothMap: getConnectedDevices()
10-29 21:24:40.122  3118  3132 D BluetoothA2dp: onBluetoothStateChange: up=true
10-29 21:24:40.122  5884  5884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 21:24:40.123  5682  5682 D HidProfile: Bluetooth service connected
10-29 21:24:40.124  5884  5884 D ObexServerSockets: Succeed to create listening sockets 
10-29 21:24:40.124  5884  5884 D ObexServerSockets0: startAccept()
10-29 21:24:40.124  5884  5884 D ObexServerSockets0: prepareForNewConnect()
,10-29 21:24:40.124  3118  3937 D BluetoothPbap: onBluetoothStateChange: up=true
10-29 21:24:40.125   927   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-29 21:24:40.125  5884  5884 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-29 21:24:40.125  5884  5884 D BluetoothSdpJni: SDP Create record success - handle: 0
10-29 21:24:40.125  5682  5694 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:40.126   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:40.126   927   927 D BluetoothA2dp: Proxy object connected
10-29 21:24:40.126  5884  5921 D ObexServerSockets0: Accepting socket connection...
10-29 21:24:40.126  3118  3132 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-29 21:24:40.126  3118  3118 D BluetoothA2dp: Proxy object connected
10-29 21:24:40.127  5884  5922 D ObexServerSockets0: Accepting socket connection...
10-29 21:24:40.127  5682  5879 D BluetoothA2dp: onBluetoothStateChange: up=true
10-29 21:24:40.128  3118  3118 D BluetoothInputDevice: Proxy object connected
10-29 21:24:40.128  3118  3118 D HidProfile: Bluetooth service connected
,10-29 21:24:40.129   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:40.129  3782  3808 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:40.129   927   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-29 21:24:40.131  5884  5884 D BluetoothMapService: onReceive
10-29 21:24:40.131  5884  5884 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-29 21:24:40.131  5884  5884 D BluetoothMapService: STATE_ON
10-29 21:24:40.131   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-29 21:24:40.131  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-29 21:24:40.132  5682  5682 D BluetoothMap: Proxy object connected
10-29 21:24:40.132  5682  5682 D MapProfile: Bluetooth service connected
10-29 21:24:40.132  5682  5682 D BluetoothMap: getConnectedDevices()
10-29 21:24:40.132  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:40.133  5682  5682 D BluetoothPan: BluetoothPAN Proxy object connected
10-29 21:24:40.133  5682  5682 D PanProfile: Bluetooth service connected
10-29 21:24:40.134  5682  5682 D BluetoothA2dp: Proxy object connected
10-29 21:24:40.134  5884  5923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-29 21:24:40.134  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:40.135  5884  5923 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-29 21:24:40.135  5884  5923 D BluetoothSdpJni: SDP Create record success - handle: 1
10-29 21:24:40.140  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-29 21:24:40.144  3548  3548 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-29 21:24:40.144  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,10-29 21:24:40.147  5682  5682 D BluetoothPbap: Proxy object connected
,10-29 21:24:40.147  5682  5682 D PbapServerProfile: Bluetooth service connected
,10-29 21:24:40.149  5884  5926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 21:24:40.158  5884  5884 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-29 21:24:40.158  5884  5884 D ObexServerSockets0: prepareForNewConnect()
10-29 21:24:40.160  3118  3118 D BluetoothPbap: Proxy object connected
10-29 21:24:40.160  3118  3118 D PbapServerProfile: Bluetooth service connected
,10-29 21:24:40.163  5884  5932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-29 21:24:40.164  5884  5932 I BtOppRfcommListener: Accept thread started.
,10-29 21:24:40.223   927   927 D BluetoothHeadset: Proxy object connected
,10-29 21:24:40.223  5682  5694 D BluetoothHeadset: Proxy object connected
,10-29 21:24:40.224   927   927 D BluetoothHeadset: Proxy object connected
10-29 21:24:40.224  3782  3964 D BluetoothHeadset: Proxy object connected
10-29 21:24:40.224   927   927 D BluetoothHeadset: Proxy object connected
10-29 21:24:40.224  3118  3937 D BluetoothHeadset: Proxy object connected
10-29 21:24:40.224  3118  3118 D HeadsetProfile: Bluetooth service connected
10-29 21:24:40.226  5682  5682 D HeadsetProfile: Bluetooth service connected
10-29 21:24:40.227  5682  5693 D BluetoothHeadset: Proxy object connected
10-29 21:24:40.227   927   945 D BluetoothHeadset: Proxy object connected
10-29 21:24:40.228  5682  5682 D HeadsetProfile: Bluetooth service connected
10-29 21:24:40.229   927   945 D BluetoothHeadset: Proxy object connected
10-29 21:24:40.229  3782  3806 D BluetoothHeadset: Proxy object connected
10-29 21:24:40.230   927   945 D BluetoothHeadset: Proxy object connected
,10-29 21:24:40.685   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:41.686   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:42.687   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-29 21:24:43.931  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:43.931  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:43.931  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:43.931  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-29 21:24:43.931  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:43.931  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:43.931  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:43.931  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 21:24:43.936  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-29 21:24:43.936  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:43.937  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4156aa6 removed from the list
10-29 21:24:43.937  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:43.937  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:43.937  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:43.941  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 21:24:43.941  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6012ce7 added. We now have 4 listener(s)
,10-29 21:24:43.941  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 21:24:43.944   927   939 D WifiService: setWifiEnabled: false pid=5618, uid=10077
10-29 21:24:43.944   927   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 21:24:47.688   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:48.689   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:48.954  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:48.955   927  3549 D WifiService: setWifiEnabled: true pid=5618, uid=10077
,10-29 21:24:48.955   927  3549 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-29 21:24:48.962   507   921 D SoftapController: Softap fwReload - Ok
,10-29 21:24:48.969   507   921 D CommandListener: Setting iface cfg
10-29 21:24:48.969   507   921 D CommandListener: Trying to bring down wlan0
,10-29 21:24:48.973   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-29 21:24:48.977   927  2949 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-29 21:24:49.589   927  2949 D wifi    : set interface wlan0 flags (UP)
,10-29 21:24:49.593   927  2949 I WifiHAL : Initializing wifi
,10-29 21:24:49.593   927  2949 I WifiHAL : Creating socket
10-29 21:24:49.595   927   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-29 21:24:49.601   927  2949 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-29 21:24:49.602   927  2949 D wifi    : Did set static halHandle = 0x7f5849d180
,10-29 21:24:49.602   927  2949 D wifi    : halHandle = 0x7f5849d180, mVM = 0x7f74acd140, mCls = 0x1017ca
10-29 21:24:49.602   927  2949 D wifi    : array field set
10-29 21:24:49.602   927  2949 I WifiNative-HAL: interface[0] = wlan0
10-29 21:24:49.604   927  5937 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546942079360
10-29 21:24:49.604   927  5937 D wifi    : waitForHalEvents called, vm = 0x7f74acd140, obj = 0x1017ca, env = 0x7f593d85c0
,10-29 21:24:49.662  5938  5938 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-29 21:24:49.683  5938  5938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-29 21:24:49.689   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:49.705   927  2949 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-29 21:24:49.712  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:49.716  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:49.723  5938  5938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-29 21:24:49.723  5938  5938 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-29 21:24:49.739   927  2949 D WifiConfigStore: Loading config and enabling all networks 
,10-29 21:24:49.740  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:49.740  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:49.740  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:49.740  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:49.740  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:49.740  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:49.740  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:49.740  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-29 21:24:49.742  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-29 21:24:49.746  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:49.746  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:49.746  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:49.746  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:49.746  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:49.746  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-29 21:24:49.746  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-29 21:24:49.746  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-29 21:24:49.747  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-29 21:24:49.755   927  2949 D WifiConfigStore: loaded 0 passpoint configs
,10-29 21:24:49.756   927  2949 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-29 21:24:49.756   927  2949 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-29 21:24:49.757   927  2949 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-29 21:24:49.758   927  2949 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-29 21:24:49.758   927  2949 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-29 21:24:49.758   927  2949 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-29 21:24:49.758   927  2949 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-29 21:24:49.762   927  2949 D WifiNative-HAL: Setting external_sim to 1
,10-29 21:24:49.762  5010  5010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-29 21:24:49.762   927  2949 D wifi    : setting dfs flag to true, 0x7f57ce6e60
10-29 21:24:49.762   927  2949 D WifiStateMachine: Setting OUI to DA-A1-19
10-29 21:24:49.763   927  2949 D wifi    : setting scan oui 0x7f57ce6e60
10-29 21:24:49.763   927  2949 D WifiHAL : Sending mac address OUI
,10-29 21:24:49.766   927  2949 E native  : do suspend false
,10-29 21:24:49.773   927  2949 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-29 21:24:49.773   927   927 D RttService: SCAN_AVAILABLE : 3
10-29 21:24:49.773   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-29 21:24:49.774   927  3059 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-29 21:24:49.775   507   921 D CommandListener: Setting iface cfg
,10-29 21:24:49.778   927  2948 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,10-29 21:24:49.778   927  2948 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-29 21:24:49.786   927  2948 D WifiNative-HAL: p2pGetDeviceAddress
,10-29 21:24:49.790   927  2948 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-29 21:24:49.790   927   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=240905 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-29 21:24:50.690   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:51.691   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:24:52.692   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-29 21:24:52.854  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 21:24:52.858  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
10-29 21:24:52.863  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-29 21:24:52.915   927  2949 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-29 21:24:52.916   927  2949 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-29 21:24:52.916   927  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 21:24:52.927   927  2949 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-29 21:24:52.961   927  2949 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-29 21:24:52.963  5938  5938 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-29 21:24:53.390  5938  5938 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-29 21:24:53.424  5938  5938 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-29 21:24:53.424  5938  5938 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-29 21:24:53.433   927  2949 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-29 21:24:53.433   927  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-29 21:24:53.434   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-29 21:24:53.451   927  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-29 21:24:53.464   507   921 D CommandListener: Setting iface cfg
,10-29 21:24:53.470   927  2949 D WifiStateMachine: Start Dhcp Watchdog 3
,10-29 21:24:53.476   927  5943 D DhcpClient: Receive thread started
,10-29 21:24:53.480   927  2949 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-29 21:24:53.480   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-29 21:24:53.481   927  2951 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-29 21:24:53.561   927  2949 E native  : do suspend false
,10-29 21:24:53.573   927  5942 D DhcpClient: Broadcasting DHCPDISCOVER
,10-29 21:24:53.589   927  5943 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-29 21:24:53.590   927  5942 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-29 21:24:53.591   927  5942 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-29 21:24:53.612   927  5943 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-29 21:24:53.613   927  5942 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-29 21:24:53.617   507   921 D CommandListener: Setting iface cfg
10-29 21:24:53.621   927  2949 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-29 21:24:53.629   927  5942 D DhcpClient: Scheduling renewal in 86399s
,10-29 21:24:53.638   927  2949 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-29 21:24:53.640   927  2949 D WifiConfigStore: No blacklist allowed without epno enabled
,10-29 21:24:53.642   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-29 21:24:53.645   927  2951 D ConnectivityService: Adding iface wlan0 to network 102
,10-29 21:24:53.655   927  2949 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-29 21:24:53.696   927  2951 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-29 21:24:53.697   927  2951 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-29 21:24:53.703   927  2951 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-29 21:24:53.704   927  2951 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-29 21:24:53.706   927  2951 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-29 21:24:53.713   927  2951 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-29 21:24:53.717   927  2951 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-29 21:24:53.717   927  2951 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-29 21:24:53.717   927  2951 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-29 21:24:53.717   927  2951 D ConnectivityService:    accepting network in place of null
10-29 21:24:53.717   927  2949 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-29 21:24:53.717   927  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-29 21:24:53.718   927  2951 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-29 21:24:53.730   927  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244845, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-29 21:24:53.741   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 21:24:53.763   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-29 21:24:53.766   927  2951 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-29 21:24:53.766  3745  3884 W QCNEJ   : |CORE| network available: 102
,10-29 21:24:53.766   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-29 21:24:53.767   927  2951 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-29 21:24:53.767  3745  3884 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-29 21:24:53.770   927   945 D Tethering: MasterInitialState.processMessage what=3
10-29 21:24:53.772  3745  3884 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-29 21:24:53.772  3745  3884 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-29 21:24:53.776  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:53.776  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:53.776  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:53.776  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:53.776  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:53.776  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:53.776  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:53.776  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:53.779  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:53.784  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:53.784  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:53.784  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:53.784  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:53.784  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:53.784  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:53.784  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:53.784  5618  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:53.785  5618  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 21:24:53.786  5037  5061 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-29 21:24:53.786  5037  5061 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-29 21:24:53.786  5037  5061 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-29 21:24:53.787  5037  5061 E SarControlService: no key has been found,reset the power
10-29 21:24:53.787  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-29 21:24:53.787  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-29 21:24:53.787  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-29 21:24:53.787  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 21:24:53.787  5062  5062 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-29 21:24:53.788  5037  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-29 21:24:53.788  5037  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-29 21:24:53.788  5037  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-29 21:24:53.789  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-29 21:24:53.789  5062  5062 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-29 21:24:53.792  4904  4904 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-29 21:24:53.794   927  5940 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:400d:803::200e
10-29 21:24:53.794  3696  3696 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-29 21:24:53.796  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cf381fc HexData = [00000000f003000000000000ffffffff]
10-29 21:24:53.796  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 21:24:53.796  5062  5076 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-29 21:24:53.796  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 21:24:53.796  5037  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-29 21:24:53.799  3696  3696 D SystemUpdateService: onCreate
10-29 21:24:53.803  3696  3696 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-29 21:24:53.804  5062  5076 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cf381fc HexData = [00000000f103000000000000ffffffff]
10-29 21:24:53.804  5062  5076 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-29 21:24:53.804  5062  5076 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-29 21:24:53.804  5062  5062 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-29 21:24:53.805  5037  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-29 21:24:53.813  3696  3696 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-29 21:24:53.818  3696  5953 I SystemUpdateService: active receiver: enabled
,10-29 21:24:53.820  3696  5407 I iu.UploadsManager: num queued entries: 0
,10-29 21:24:53.821  3696  5407 I iu.UploadsManager: num updated entries: 0
,10-29 21:24:53.825  3696  3696 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-29 21:24:53.826  3696  3696 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-29 21:24:53.828  5744  5744 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-29 21:24:53.831  5744  5744 D SprintDMHelper: simOperator: 
,10-29 21:24:53.831  5744  5744 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-29 21:24:53.845   927  5940 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 30 Oct 2016 01:24:53 GMT], X-Android-Received-Millis=[1477790693844], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477790693816]}
,10-29 21:24:53.846  3696  5407 I iu.SyncManager: NEXT; no task
10-29 21:24:53.845   927  2951 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-29 21:24:53.846   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-29 21:24:53.846   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-29 21:24:53.846  3696  5953 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-29 21:24:53.847   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-29 21:24:53.865  3696  5953 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-29 21:24:53.865  3696  5953 I SystemUpdateService: now status is 0 (complete)
10-29 21:24:53.865  3696  5953 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-29 21:24:53.865  3696  5953 I SystemUpdateService: file has been verified
10-29 21:24:53.865  3696  5953 I SystemUpdateService: OTA package size = 21989297
,10-29 21:24:53.873  3696  5953 I SystemUpdateService: showing system update notification
,10-29 21:24:53.883  3696  3696 D SystemUpdateService: onDestroy
,10-29 21:24:53.937  5010  5958 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-29 21:24:53.969  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-29 21:24:53.969  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:53.969  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:53.969  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:53.969  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:53.969  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:53.969  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:53.969  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 21:24:53.970  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:53.971  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:53.971  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6012ce7 removed from the list
10-29 21:24:53.971  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:53.971  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:53.971  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:53.973  5618  5664 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-29 21:24:53.974  5618  5664 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-29 21:24:53.976  5618  5664 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1dbe600 Bundle[{}]
10-29 21:24:53.976  5618  5664 I io.jxcore.node.LifeCycleMonitor: start: OK
10-29 21:24:53.976  5618  5664 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-29 21:24:53.977  5618  5664 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-29 21:24:53.977  5618  5664 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-29 21:24:53.978  5618  5664 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-29 21:24:53.979  5618  5664 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-29 21:24:53.984  5618  5664 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,10-29 21:24:53.984  5618  5664 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-29 21:24:53.984  5618  5664 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,10-29 21:24:53.987  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-29 21:24:53.987  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd8b094 added. We now have 3 listener(s)
,10-29 21:24:53.988  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-29 21:24:53.989  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:53.989  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:24:53.989  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:53.989  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788773d added. We now have 4 listener(s)
10-29 21:24:53.989  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-29 21:24:53.990  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-29 21:24:53.993  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 21:24:53.996  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:24:53.996  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:53.996  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:53.996  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:53.996  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:53.996  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:53.996  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:53.996  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 21:24:53.998  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:53.998  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 21:24:53.998  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-29 21:24:53.998  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@129b083 added. We now have 4 listener(s)
10-29 21:24:54.000  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-29 21:24:54.000  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:54.000  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:24:54.000  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:54.000  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ada4200 added. We now have 5 listener(s)
10-29 21:24:54.000  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:54.000  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:24:54.000  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:54.000  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:24:54.000  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.000  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.000  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:24:54.000  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-29 21:24:54.000  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.000  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd8b094 removed from the list
10-29 21:24:54.000  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:54.000  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.001  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788773d removed from the list
10-29 21:24:54.002  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:54.003  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:54.003  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:54.003  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-29 21:24:54.003  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.003  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.004  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.004  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.004  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.005  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.005  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.005  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.005  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788773d not in the list
,10-29 21:24:54.005  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.005  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.005  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.007  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.007  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.007  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.007  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.007  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.007  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.007  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ada4200 removed from the list
10-29 21:24:54.007  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.007  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.007  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-29 21:24:54.007  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:54.007  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.008  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@129b083 removed from the list
10-29 21:24:54.008  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:24:54.008  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0a4a39 added. We now have 3 listener(s)
,10-29 21:24:54.010  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-29 21:24:54.010  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:54.010  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:24:54.010  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:54.010  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@715287e added. We now have 4 listener(s)
10-29 21:24:54.010  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:54.011  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-29 21:24:54.013  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 21:24:54.016  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:24:54.016  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:54.016  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:54.016  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:54.016  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:54.016  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:54.016  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:54.016  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 21:24:54.018  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 21:24:54.018  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 21:24:54.018  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:24:54.018  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a17e2c added. We now have 4 listener(s)
,10-29 21:24:54.019  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 21:24:54.019  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:54.019  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:24:54.019  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:54.019  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83c50f5 added. We now have 5 listener(s)
10-29 21:24:54.019  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:54.020  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:24:54.020  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 21:24:54.020  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 21:24:54.020  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:24:54.020  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-29 21:24:54.020  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:54.022  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:54.023  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-29 21:24:54.023  5618  5664 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 21:24:54.023  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-29 21:24:54.026  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.026  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-29 21:24:54.026  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 21:24:54.026  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-29 21:24:54.028  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.028  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 21:24:54.028  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 21:24:54.028  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-29 21:24:54.028  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 21:24:54.028  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.029  5618  5664 D BluetoothAdapter: STATE_ON
,10-29 21:24:54.032  5884  5894 D BtGatt.GattService: registerClient() - UUID=6f7f5776-6a99-4783-9017-396fe093274d
,10-29 21:24:54.033  5884  5900 D BtGatt.GattService: onClientRegistered() - UUID=6f7f5776-6a99-4783-9017-396fe093274d, clientIf=5
,10-29 21:24:54.033  5618  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-29 21:24:54.034  5884  5895 D BtGatt.GattService: start scan with filters
10-29 21:24:54.036  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-29 21:24:54.037  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.037  5884  5903 D BtGatt.ScanManager: handling starting scan
10-29 21:24:54.037  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 21:24:54.037  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.037  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-29 21:24:54.037  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 21:24:54.037  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.037  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 21:24:54.037  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 21:24:54.037  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.037  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.037  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-29 21:24:54.038  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-29 21:24:54.038  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.039  5884  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e0b3d
10-29 21:24:54.041  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.041  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:24:54.041  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.041  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.041  5618  5664 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-29 21:24:54.041  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.041  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:54.041  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-29 21:24:54.041  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.041  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-29 21:24:54.041  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:54.041  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-29 21:24:54.043  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.043  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.043  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.043  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.043  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 21:24:54.043  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 21:24:54.043  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-29 21:24:54.043  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:24:54.044  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.044  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.044  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.044  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 21:24:54.044  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.044  5618  5664 D BluetoothAdapter: STATE_ON
10-29 21:24:54.045  5884  5895 D BtGatt.GattService: stopScan() - queue size =1
10-29 21:24:54.046  5884  5900 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-29 21:24:54.046  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.046  5884  5920 D BtGatt.GattService: unregisterClient() - clientIf=5
10-29 21:24:54.046  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-29 21:24:54.046  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.046  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 21:24:54.046  5884  5903 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-29 21:24:54.047  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.047  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.047  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.047  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.047  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-29 21:24:54.047  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.047  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.047  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.047  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-29 21:24:54.047  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 21:24:54.049  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:24:54.049  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.050  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.050  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:24:54.050  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.050  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.050  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:24:54.050  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:24:54.050  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 21:24:54.050  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.050  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-29 21:24:54.050  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 21:24:54.050  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.050  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.051  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 21:24:54.051  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.052  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:24:54.052  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:54.052  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:24:54.052  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.052  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.052  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:24:54.052  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-29 21:24:54.052  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.052  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0a4a39 removed from the list
10-29 21:24:54.052  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.052  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@715287e removed from the list
10-29 21:24:54.052  5884  5900 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 21:24:54.052  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:54.052  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.052  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.053  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.053  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.053  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.053  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.053  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.053  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.053  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,10-29 21:24:54.053  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:24:54.054  5884  5903 D BtGatt.ScanManager: Starting BLE batch scan
10-29 21:24:54.054  5884  5903 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-29 21:24:54.054  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.055  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.055  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.055  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.055  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.055  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.055  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@715287e not in the list
10-29 21:24:54.055  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.055  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.055  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.056  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.056  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.056  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.056  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.056  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.057  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.057  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83c50f5 removed from the list
10-29 21:24:54.057  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.057  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.057  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.057  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:54.057  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.057  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a17e2c removed from the list
10-29 21:24:54.058  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:24:54.058  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4e0771 added. We now have 3 listener(s)
10-29 21:24:54.059  5618  5664 D org.thaliproject.p2p.btconnectorlib.,internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 21:24:54.059  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:54.059  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:24:54.059  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:54.059  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be3c956 added. We now have 4 listener(s)
10-29 21:24:54.059  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:54.060  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-29 21:24:54.062  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 21:24:54.064  5884  5900 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-29 21:24:54.064  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:24:54.064  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:24:54.064  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:54.064  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:54.064  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:54.064  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:54.064  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:54.064  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:54.064  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 21:24:54.066  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:54.069  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-29 21:24:54.069  5884  5900 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 21:24:54.069  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:24:54.069  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.069  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd366c4 added. We now have 4 listener(s)
10-29 21:24:54.071  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 21:24:54.071  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:54.071  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:24:54.071  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:54.071  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5eaa9ad added. We now have 5 listener(s)
10-29 21:24:54.071  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:54.071  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:54.071  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:24:54.072  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:24:54.072  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 21:24:54.072  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-29 21:24:54.072  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:24:54.072  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-29 21:24:54.073  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:54.077  5884  5900 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-29 21:24:54.077  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:24:54.077  5884  5903 D BtGatt.ScanManager: stopping BLe Batch
10-29 21:24:54.078  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-29 21:24:54.078  5618  5664 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 21:24:54.078  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-29 21:24:54.082  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.083  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-29 21:24:54.083  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 21:24:54.083  5884  5900 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 21:24:54.083  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-29 21:24:54.083  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.084  5884  5903 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-29 21:24:54.088  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.088  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 21:24:54.088  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 21:24:54.088  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-29 21:24:54.088  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 21:24:54.088  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.089  5618  5664 D BluetoothAdapter: STATE_ON
,10-29 21:24:54.089  5884  5900 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-29 21:24:54.090  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:24:54.091  5884  5924 D BtGatt.GattService: registerClient() - UUID=b093d7b7-9471-40ee-b228-7404a51031a9
,10-29 21:24:54.092  5884  5900 D BtGatt.GattService: onClientRegistered() - UUID=b093d7b7-9471-40ee-b228-7404a51031a9, clientIf=5
10-29 21:24:54.092  5618  5724 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-29 21:24:54.092  5884  5894 D BtGatt.GattService: start scan with filters
,10-29 21:24:54.094  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-29 21:24:54.094  5884  5903 D BtGatt.ScanManager: handling starting scan
10-29 21:24:54.094  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.094  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-29 21:24:54.094  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.094  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-29 21:24:54.094  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 21:24:54.094  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.094  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-29 21:24:54.094  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 21:24:54.094  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.094  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.095  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-29 21:24:54.096  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-29 21:24:54.096  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.099  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.099  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:24:54.099  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.099  5884  5900 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-29 21:24:54.099  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.099  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.099  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.099  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:24:54.099  5618  5664 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-29 21:24:54.099  5884  5903 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-29 21:24:54.099  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:24:54.099  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:54.099  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-29 21:24:54.099  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.099  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.099  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-29 21:24:54.099  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:54.099  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.099  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4e0771 removed from the list
10-29 21:24:54.099  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.100  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be3c956 removed from the list
10-29 21:24:54.100  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:54.100  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:24:54.100  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.100  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,10-29 21:24:54.100  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.100  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:24:54.100  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.101  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.101  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.101  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.101  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.101  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:24:54.103  5884  5900 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 21:24:54.103  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.103  5884  5903 D BtGatt.ScanManager: Starting BLE batch scan
10-29 21:24:54.103  5884  5903 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-29 21:24:54.103  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.103  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.103  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.103  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.103  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.103  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.103  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be3c956 not in the list
10-29 21:24:54.103  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 21:24:54.103  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-29 21:24:54.103  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-29 21:24:54.104  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.104  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.104  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.104  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 21:24:54.104  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.105  5618  5664 D BluetoothAdapter: STATE_ON
,10-29 21:24:54.105  5884  5894 D BtGatt.GattService: stopScan() - queue size =1
10-29 21:24:54.106  5884  5895 D BtGatt.GattService: unregisterClient() - clientIf=5
10-29 21:24:54.106  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-29 21:24:54.106  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.106  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 21:24:54.106  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.106  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.106  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.106  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.106  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-29 21:24:54.106  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.107  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.107  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.107  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-29 21:24:54.107  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 21:24:54.107  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.107  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.108  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.108  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-29 21:24:54.108  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.108  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.108  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.108  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.109  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-29 21:24:54.109  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:24:54.109  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5eaa9ad removed from the list
10-29 21:24:54.109  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.109  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:24:54.109  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.109  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.109  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 21:24:54.109  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:54.109  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.109  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.109  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd366c4 removed from the list
,10-29 21:24:54.109  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 21:24:54.109  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 21:24:54.109  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.109  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.109  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 21:24:54.109  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.109  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:24:54.109  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53533a9 added. We now have 3 listener(s)
10-29 21:24:54.110  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.110  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-29 21:24:54.110  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.111  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.111  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:24:54.111  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 21:24:54.111  5884  5900 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-29 21:24:54.111  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.111  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:54.111  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:24:54.111  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:54.111  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1aad2e added. We now have 4 listener(s)
10-29 21:24:54.111  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:54.114  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-29 21:24:54.116  5884  5900 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-29 21:24:54.116  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.116  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 21:24:54.121  5884  5900 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-29 21:24:54.121  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:24:54.121  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:24:54.121  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:54.121  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:54.121  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:54.121  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:54.121  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:54.121  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:54.121  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-29 21:24:54.121  5884  5903 D BtGatt.ScanManager: stopping BLe Batch
,10-29 21:24:54.123  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-29 21:24:54.123  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-29 21:24:54.123  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:24:54.124  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@116ca5c added. We now have 4 listener(s)
10-29 21:24:54.125  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 21:24:54.125  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:54.125  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-29 21:24:54.125  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:54.125  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:54.125  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7846165 added. We now have 5 listener(s)
10-29 21:24:54.125  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:54.126  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:24:54.126  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-29 21:24:54.126  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-29 21:24:54.126  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-29 21:24:54.126  5884  5900 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 21:24:54.126  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-29 21:24:54.126  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.126  5884  5903 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-29 21:24:54.127  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-29 21:24:54.129  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-29 21:24:54.129  5618  5664 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-29 21:24:54.129  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-29 21:24:54.131  5884  5900 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-29 21:24:54.131  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:24:54.132  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.132  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-29 21:24:54.133  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-29 21:24:54.133  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-29 21:24:54.136  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.136  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-29 21:24:54.136  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-29 21:24:54.136  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-29 21:24:54.136  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-29 21:24:54.136  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.137  5618  5664 D BluetoothAdapter: STATE_ON
,10-29 21:24:54.138  5884  5895 D BtGatt.GattService: registerClient() - UUID=eeb8a672-370d-4148-8e57-2d5ec95e91a0
,10-29 21:24:54.139  5884  5900 D BtGatt.GattService: onClientRegistered() - UUID=eeb8a672-370d-4148-8e57-2d5ec95e91a0, clientIf=5
10-29 21:24:54.139  5618  5629 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-29 21:24:54.139  5884  5911 D BtGatt.GattService: start scan with filters
,10-29 21:24:54.141  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-29 21:24:54.141  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.142  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-29 21:24:54.142  5884  5903 D BtGatt.ScanManager: handling starting scan
10-29 21:24:54.142  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.142  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-29 21:24:54.142  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-29 21:24:54.142  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.142  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-29 21:24:54.142  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-29 21:24:54.142  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.142  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.142  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-29 21:24:54.143  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-29 21:24:54.143  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.145  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.145  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:24:54.145  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.145  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.145  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.146  5884  5900 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-29 21:24:54.146  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.146  5884  5903 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-29 21:24:54.148  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:24:54.148  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.148  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:54.148  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:24:54.148  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.148  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.148  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.149  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.149  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-29 21:24:54.149  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.149  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:54.149  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-29 21:24:54.149  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.149  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53533a9 removed from the list
10-29 21:24:54.149  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.149  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1aad2e removed from the list
10-29 21:24:54.149  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
10-29 21:24:54.149  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-29 21:24:54.150  5884  5900 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-29 21:24:54.150  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.150  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.150  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-29 21:24:54.150  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.150  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:24:54.150  5884  5903 D BtGatt.ScanManager: Starting BLE batch scan
,10-29 21:24:54.150  5884  5903 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-29 21:24:54.150  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.151  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.151  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.151  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.151  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.152  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.152  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.152  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1aad2e not in the list
10-29 21:24:54.152  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-29 21:24:54.152  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-29 21:24:54.152  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-29 21:24:54.152  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.152  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.152  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.152  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-29 21:24:54.152  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.153  5618  5664 D BluetoothAdapter: STATE_ON
10-29 21:24:54.153  5884  5911 D BtGatt.GattService: stopScan() - queue size =1
,10-29 21:24:54.154  5884  5895 D BtGatt.GattService: unregisterClient() - clientIf=5
10-29 21:24:54.154  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-29 21:24:54.154  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.154  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-29 21:24:54.154  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.154  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.155  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.155  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.155  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-29 21:24:54.155  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.155  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.155  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.155  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-29 21:24:54.155  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-29 21:24:54.156  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.156  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.158  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.158  5884  5900 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-29 21:24:54.158  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.158  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:24:54.158  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.158  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.158  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.159  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.159  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.159  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7846165 removed from the list
10-29 21:24:54.159  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:24:54.159  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.159  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.159  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-29 21:24:54.159  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.159  5618  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-29 21:24:54.159  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:54.159  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.159  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.159  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-29 21:24:54.159  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@116ca5c removed from the list
10-29 21:24:54.159  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-29 21:24:54.159  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.159  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,10-29 21:24:54.159  5618  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-29 21:24:54.159  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.160  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:24:54.160  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@deaee1 added. We now have 3 listener(s)
10-29 21:24:54.160  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.160  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.160  5618  5618 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.160  5618  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-29 21:24:54.160  5618  5618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-29 21:24:54.161  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-29 21:24:54.161  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:54.161  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:24:54.161  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-29 21:24:54.161  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1f3406 added. We now have 4 listener(s)
10-29 21:24:54.161  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:54.163  5884  5900 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-29 21:24:54.163  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-29 21:24:54.163  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-29 21:24:54.164  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-29 21:24:54.168  5884  5900 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-29 21:24:54.168  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.168  5884  5903 D BtGatt.ScanManager: stopping BLe Batch
10-29 21:24:54.168  5618  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-29 21:24:54.168  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-29 21:24:54.168  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-29 21:24:54.168  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-29 21:24:54.168  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-29 21:24:54.168  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:54.168  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-29 21:24:54.168  5618  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-29 21:24:54.170  5618  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-29 21:24:54.170  5618  5664 D io.jxcore.node.ConnectivityMonitor: start: OK
10-29 21:24:54.170  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-29 21:24:54.170  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c008f4 added. We now have 4 listener(s)
,10-29 21:24:54.171  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-29 21:24:54.172  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-29 21:24:54.172  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-29 21:24:54.172  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-29 21:24:54.172  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@536581d added. We now have 5 listener(s)
10-29 21:24:54.172  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:54.172  5618  5664 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-29 21:24:54.172  5884  5900 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-29 21:24:54.172  5618  5664 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-29 21:24:54.172  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.172  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:24:54.172  5618  5664 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-29 21:24:54.172  5884  5903 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-29 21:24:54.172  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.172  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.173  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-29 21:24:54.173  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:54.173  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.173  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@deaee1 removed from the list
10-29 21:24:54.173  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.173  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1f3406 removed from the list
,10-29 21:24:54.174  5618  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-29 21:24:54.174  5618  5664 D io.jxcore.node.ConnectivityMonitor: stop
,10-29 21:24:54.174  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.175  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.175  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.175  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.176  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.176  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.176  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.176  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.176  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.176  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.176  5618  5664 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1f3406 not in the list
10-29 21:24:54.176  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.176  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.176  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.176  5884  5900 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-29 21:24:54.176  5884  5900 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-29 21:24:54.177  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.177  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-29 21:24:54.177  5618  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-29 21:24:54.177  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-29 21:24:54.177  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-29 21:24:54.177  5618  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-29 21:24:54.178  5618  5664 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@536581d removed from the list
10-29 21:24:54.178  5618  5664 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-29 21:24:54.178  5618  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-29 21:24:54.178  5618  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-29 21:24:54.178  5618  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-29 21:24:54.178  5618  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-29 21:24:54.178  5618  5664 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c008f4 removed from the list
,10-29 21:24:54.179  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-29 21:24:54.179  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-29 21:24:54.179  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,10-29 21:24:54.179  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:24:54.179  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-29 21:24:54.180  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-29 21:24:54.554  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 21:24:54.612  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 21:24:54.661  5618  5618 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-29 21:24:56.312  5618  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-29 21:24:56.312  5618  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 21:24:56.503   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-29 21:24:57.101  5618  5965 W !!      : call onHalfStreamCopied
,10-29 21:24:57.101  5618  5965 I testCopyDataAndClose: closing input stream
,10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-29 21:24:57.878  5618  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-29 21:25:01.673  5618  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-29 21:25:01.673  5618  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 21:25:01.723   927  2951 D ConnectivityService: handlePromptUnvalidated 102
,10-29 21:25:02.548   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-29 21:25:02.696   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:03.673  5618  5664 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-29 21:25:03.673  5618  5664 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 21:25:03.673  5618  5664 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-29 21:25:03.697   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:03.808  5618  5968 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-29 21:25:03.808  5618  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 21:25:03.831  5618  5966 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-29 21:25:03.831  5618  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-29 21:25:03.831  5618  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,10-29 21:25:04.698   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:04.789   927  2949 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-29 21:25:05.420  5618  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-29 21:25:05.568   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-29 21:25:05.699   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:06.700   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:07.701   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-29 21:25:09.177  5618  5969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-29 21:25:09.177  5618  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-29 21:25:09.177  5618  5969 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-29 21:25:09.177  5618  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 21:25:09.177  5618  5969 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-29 21:25:09.177  5618  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 21:25:09.177  5618  5969 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-29 21:25:09.178  5618  5969 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-29 21:25:09.178  5618  5969 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-29 21:25:09.178  5618  5969 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-29 21:25:09.178  5618  5969 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-29 21:25:09.178  5618  5969 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-29 21:25:09.178  5618  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-29 21:25:09.180  5618  5664 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-29 21:25:09.183  5618  5970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-29 21:25:09.183  5618  5970 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-29 21:25:09.183  5618  5970 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
10-29 21:25:09.183  5618  5970 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-29 21:25:09.183  5618  5970 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-29 21:25:09.184  5618  5970 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-29 21:25:09.184  5618  5970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-29 21:25:09.184  5618  5970 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-29 21:25:09.188  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-29 21:25:09.188  5618  5664 I jxcore-log: 
10-29 21:25:09.188  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-29 21:25:09.188  5618  5664 I jxcore-log: 
10-29 21:25:09.189  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-29 21:25:09.189  5618  5664 I jxcore-log: 
10-29 21:25:09.189  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-29 21:25:09.189  5618  5664 I jxcore-log: 
10-29 21:25:09.190  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG UnitTest_app: 'Total duration:  90773'
10-29 21:25:09.190  5618  5664 I jxcore-log: 
,10-29 21:25:09.192  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-29 21:25:09.192  5618  5664 I jxcore-log: 
,10-29 21:25:09.196  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.196  5618  5664 I jxcore-log: 
10-29 21:25:09.197  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.197  5618  5664 I jxcore-log: 
,10-29 21:25:09.197  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.197  5618  5664 I jxcore-log: 
10-29 21:25:09.197  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.197  5618  5664 I jxcore-log: 
10-29 21:25:09.198  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-29 21:25:09.198  5618  5664 I jxcore-log: 
10-29 21:25:09.198  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
10-29 21:25:09.198  5618  5664 I jxcore-log: 
10-29 21:25:09.198  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 21:25:09.198  5618  5664 I jxcore-log: 
10-29 21:25:09.199  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 21:25:09.199  5618  5664 I jxcore-log: 
10-29 21:25:09.199  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 21:25:09.199  5618  5664 I jxcore-log: 
10-29 21:25:09.199  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.199  5618  5664 I jxcore-log: 
10-29 21:25:09.200  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.200  5618  5664 I jxcore-log: 
10-29 21:25:09.200  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-29 21:25:09.200  5618  5664 I jxcore-log: 
10-29 21:25:09.200  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
10-29 21:25:09.200  5618  5664 I jxcore-log: 
10-29 21:25:09.200  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 21:25:09.200  5618  5664 I jxcore-log: 
,10-29 21:25:09.201  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 21:25:09.201  5618  5664 I jxcore-log: 
10-29 21:25:09.201  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 21:25:09.201  5618  5664 I jxcore-log: 
10-29 21:25:09.201  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 21:25:09.201  5618  5664 I jxcore-log: 
10-29 21:25:09.201  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 21:25:09.201  5618  5664 I jxcore-log: 
10-29 21:25:09.201  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.201  5618  5664 I jxcore-log: 
10-29 21:25:09.202  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.202  5618  5664 I jxcore-log: 
10-29 21:25:09.202  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.202  5618  5664 I jxcore-log: 
10-29 21:25:09.203  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 21:25:09.203  5618  5664 I jxcore-log: 
10-29 21:25:09.203  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 21:25:09.203  5618  5664 I jxcore-log: 
,10-29 21:25:09.203  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 21:25:09.203  5618  5664 I jxcore-log: 
10-29 21:25:09.205  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.205  5618  5664 I jxcore-log: 
10-29 21:25:09.206  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.206  5618  5664 I jxcore-log: 
,10-29 21:25:09.206  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.206  5618  5664 I jxcore-log: 
10-29 21:25:09.206  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 21:25:09.206  5618  5664 I jxcore-log: 
10-29 21:25:09.206  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 21:25:09.206  5618  5664 I jxcore-log: 
,10-29 21:25:09.207  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 21:25:09.207  5618  5664 I jxcore-log: 
10-29 21:25:09.207  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.207  5618  5664 I jxcore-log: 
10-29 21:25:09.207  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.207  5618  5664 I jxcore-log: 
10-29 21:25:09.207  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.207  5618  5664 I jxcore-log: 
10-29 21:25:09.208  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-29 21:25:09.208  5618  5664 I jxcore-log: 
10-29 21:25:09.208  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.208  5618  5664 I jxcore-log: 
,10-29 21:25:09.208  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.208  5618  5664 I jxcore-log: 
10-29 21:25:09.208  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.208  5618  5664 I jxcore-log: 
10-29 21:25:09.209  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.209  5618  5664 I jxcore-log: 
10-29 21:25:09.209  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.209  5618  5664 I jxcore-log: 
10-29 21:25:09.209  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.209  5618  5664 I jxcore-log: 
10-29 21:25:09.209  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.209  5618  5664 I jxcore-log: 
10-29 21:25:09.210  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.210  5618  5664 I jxcore-log: 
10-29 21:25:09.210  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.210  5618  5664 I jxcore-log: 
10-29 21:25:09.210  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.210  5618  5664 I jxcore-log: 
,10-29 21:25:09.210  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.210  5618  5664 I jxcore-log: 
10-29 21:25:09.210  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-29 21:25:09.210  5618  5664 I jxcore-log: 
10-29 21:25:09.211  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-29 21:25:09.211  5618  5664 I jxcore-log: 
10-29 21:25:09.211  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-29 21:25:09.211  5618  5664 I jxcore-log: 
10-29 21:25:09.211  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.211  5618  5664 I jxcore-log: 
10-29 21:25:09.211  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.211  5618  5664 I jxcore-log: 
10-29 21:25:09.212  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.212  5618  5664 I jxcore-log: 
,10-29 21:25:09.212  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.212  5618  5664 I jxcore-log: 
10-29 21:25:09.212  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.212  5618  5664 I jxcore-log: 
10-29 21:25:09.212  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-29 21:25:09.212  5618  5664 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-29 21:25:09.213  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.213  5618  5664 I jxcore-log: 
10-29 21:25:09.213  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.213  5618  5664 I jxcore-log: 
10-29 21:25:09.213  5618  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-29 21:25:09.213  5618  5664 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-29 21:25:09.213  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-29 21:25:09.213  5618  5664 I jxcore-log: 
10-29 21:25:09.214  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 21:25:09.214  5618  5664 I jxcore-log: 
10-29 21:25:09.214  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 21:25:09.214  5618  5664 I jxcore-log: 
,10-29 21:25:09.214  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 21:25:09.214  5618  5664 I jxcore-log: 
10-29 21:25:09.214  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 21:25:09.214  5618  5664 I jxcore-log: 
10-29 21:25:09.214  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-29 21:25:09.214  5618  5664 I jxcore-log: 
10-29 21:25:09.214  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
10-29 21:25:09.214  5618  5664 I jxcore-log: 
10-29 21:25:09.219  5618  5618 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-29 21:25:09.220  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-29 21:25:09.220  5618  5664 I jxcore-log: 
10-29 21:25:09.220  5618  5664 I jxcore-log: 2016-10-30 01:25:09 - WARN testUtils: 'myNameCallback not set!'
10-29 21:25:09.220  5618  5664 I jxcore-log: 
,10-29 21:25:11.278  5618  5664 I jxcore-log: 2016-10-30 01:25:11 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
10-29 21:25:11.278  5618  5664 I jxcore-log: 
,10-29 21:25:11.280  5618  5664 I jxcore-log: 2016-10-30 01:25:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-29 21:25:11.280  5618  5664 I jxcore-log: 
,10-29 21:25:11.622  5618  5664 I jxcore-log: 2016-10-30 01:25:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-29 21:25:11.622  5618  5664 I jxcore-log: 
,10-29 21:25:11.633  5618  5664 I jxcore-log: 2016-10-30 01:25:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-29 21:25:11.633  5618  5664 I jxcore-log: 
,10-29 21:25:12.752  5618  5664 I jxcore-log: 2016-10-30 01:25:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-29 21:25:12.752  5618  5664 I jxcore-log: 
,10-29 21:25:12.941  5618  5664 I jxcore-log: 2016-10-30 01:25:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-29 21:25:12.941  5618  5664 I jxcore-log: 
,10-29 21:25:12.946  5618  5664 I jxcore-log: 2016-10-30 01:25:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-29 21:25:12.946  5618  5664 I jxcore-log: 
,10-29 21:25:12.951  5618  5664 I jxcore-log: 2016-10-30 01:25:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-29 21:25:12.951  5618  5664 I jxcore-log: 
,10-29 21:25:13.438  5618  5664 I jxcore-log: 2016-10-30 01:25:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-29 21:25:13.438  5618  5664 I jxcore-log: 
,10-29 21:25:13.483  5618  5664 I jxcore-log: 2016-10-30 01:25:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-29 21:25:13.483  5618  5664 I jxcore-log: 
,10-29 21:25:13.496  5618  5664 I jxcore-log: 2016-10-30 01:25:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-29 21:25:13.496  5618  5664 I jxcore-log: 
,10-29 21:25:13.501  5618  5664 I jxcore-log: 2016-10-30 01:25:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-29 21:25:13.501  5618  5664 I jxcore-log: 
,10-29 21:25:13.790  5618  5664 I jxcore-log: 2016-10-30 01:25:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-29 21:25:13.790  5618  5664 I jxcore-log: 
,10-29 21:25:13.919  5618  5664 I jxcore-log: 2016-10-30 01:25:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-29 21:25:13.919  5618  5664 I jxcore-log: 
,10-29 21:25:14.281  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-29 21:25:14.281  5618  5664 I jxcore-log: 
,10-29 21:25:14.290  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-29 21:25:14.290  5618  5664 I jxcore-log: 
,10-29 21:25:14.294  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-29 21:25:14.294  5618  5664 I jxcore-log: 
,10-29 21:25:14.299  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-29 21:25:14.299  5618  5664 I jxcore-log: 
,10-29 21:25:14.304  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-29 21:25:14.304  5618  5664 I jxcore-log: 
,10-29 21:25:14.331  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-29 21:25:14.331  5618  5664 I jxcore-log: 
,10-29 21:25:14.365  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-29 21:25:14.365  5618  5664 I jxcore-log: 
,10-29 21:25:14.371  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-29 21:25:14.371  5618  5664 I jxcore-log: 
,10-29 21:25:14.377  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-29 21:25:14.377  5618  5664 I jxcore-log: 
,10-29 21:25:14.390  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-29 21:25:14.390  5618  5664 I jxcore-log: 
,10-29 21:25:14.394  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-29 21:25:14.394  5618  5664 I jxcore-log: 
,10-29 21:25:14.399  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-29 21:25:14.399  5618  5664 I jxcore-log: 
,10-29 21:25:14.404  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-29 21:25:14.404  5618  5664 I jxcore-log: 
,10-29 21:25:14.415  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-29 21:25:14.415  5618  5664 I jxcore-log: 
,10-29 21:25:14.421  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-29 21:25:14.421  5618  5664 I jxcore-log: 
,10-29 21:25:14.441  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-29 21:25:14.441  5618  5664 I jxcore-log: 
,10-29 21:25:14.451  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-29 21:25:14.451  5618  5664 I jxcore-log: 
,10-29 21:25:14.462  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-29 21:25:14.462  5618  5664 I jxcore-log: 
,10-29 21:25:14.473  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-29 21:25:14.473  5618  5664 I jxcore-log: 
,10-29 21:25:14.486  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-29 21:25:14.486  5618  5664 I jxcore-log: 
,10-29 21:25:14.496  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-29 21:25:14.496  5618  5664 I jxcore-log: 
,10-29 21:25:14.503  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-29 21:25:14.503  5618  5664 I jxcore-log: 
,10-29 21:25:14.525  5618  5664 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-29 21:25:14.526  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - INFO testUtils: 'BLE multiple advertisement supported'
10-29 21:25:14.526  5618  5664 I jxcore-log: 
,10-29 21:25:14.676  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:14.676  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:14.676  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:14.676  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:14.676  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:14.676  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:14.676  5618  5664 I jxcore-log: 
,10-29 21:25:14.996  5618  5664 I jxcore-log: 2016-10-30 01:25:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:14.996  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:14.996  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:14.996  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:14.996  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:14.996  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:14.996  5618  5664 I jxcore-log: 
,10-29 21:25:15.000  5618  5664 I jxcore-log: 2016-10-30 01:25:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:15.000  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:15.000  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:15.000  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:15.000  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:15.000  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:15.000  5618  5664 I jxcore-log: 
,10-29 21:25:15.637  5618  5664 I jxcore-log: 2016-10-30 01:25:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:15.637  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:15.637  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:15.637  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:15.637  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:15.637  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:15.637  5618  5664 I jxcore-log: 
,10-29 21:25:15.642  5618  5664 I jxcore-log: 2016-10-30 01:25:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:15.642  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:15.642  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:15.642  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:15.642  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:15.642  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:15.642  5618  5664 I jxcore-log: 
,10-29 21:25:16.435  5618  5664 I jxcore-log: 2016-10-30 01:25:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:16.435  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:16.435  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:16.435  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:16.435  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:16.435  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:16.435  5618  5664 I jxcore-log: 
,10-29 21:25:16.439  5618  5664 I jxcore-log: 2016-10-30 01:25:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:16.439  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:16.439  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:16.439  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:16.439  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:16.439  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:16.439  5618  5664 I jxcore-log: 
,10-29 21:25:17.458  5618  5664 I jxcore-log: 2016-10-30 01:25:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:17.458  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:17.458  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:17.458  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:17.458  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:17.458  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:17.458  5618  5664 I jxcore-log: 
,10-29 21:25:17.463  5618  5664 I jxcore-log: 2016-10-30 01:25:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:17.463  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:17.463  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:17.463  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:17.463  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:17.463  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:17.463  5618  5664 I jxcore-log: 
,10-29 21:25:17.638   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-29 21:25:18.742  5618  5664 I jxcore-log: 2016-10-30 01:25:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:18.742  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:18.742  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:18.742  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:18.742  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:18.742  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:18.742  5618  5664 I jxcore-log: 
,10-29 21:25:18.747  5618  5664 I jxcore-log: 2016-10-30 01:25:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:18.747  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:18.747  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:18.747  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:18.747  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:18.747  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:18.747  5618  5664 I jxcore-log: 
,10-29 21:25:19.776  5618  5664 I jxcore-log: 2016-10-30 01:25:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:19.776  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:19.776  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:19.776  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:19.776  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:19.776  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:19.776  5618  5664 I jxcore-log: 
,10-29 21:25:19.780  5618  5664 I jxcore-log: 2016-10-30 01:25:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:19.780  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:19.780  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:19.780  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:19.780  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:19.780  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:19.780  5618  5664 I jxcore-log: 
,10-29 21:25:20.670   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-29 21:25:20.812  5618  5664 I jxcore-log: 2016-10-30 01:25:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:20.812  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:20.812  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:20.812  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:20.812  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:20.812  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:20.812  5618  5664 I jxcore-log: 
,10-29 21:25:20.816  5618  5664 I jxcore-log: 2016-10-30 01:25:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:20.816  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:20.816  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:20.816  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:20.816  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:20.816  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:20.816  5618  5664 I jxcore-log: 
,10-29 21:25:21.846  5618  5664 I jxcore-log: 2016-10-30 01:25:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:21.846  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:21.846  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:21.846  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:21.846  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:21.846  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:21.846  5618  5664 I jxcore-log: 
,10-29 21:25:21.850  5618  5664 I jxcore-log: 2016-10-30 01:25:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:21.850  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:21.850  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:21.850  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:21.850  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:21.850  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:21.850  5618  5664 I jxcore-log: 
,10-29 21:25:22.703   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:22.880  5618  5664 I jxcore-log: 2016-10-30 01:25:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:22.880  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:22.880  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:22.880  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:22.880  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:22.880  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:22.880  5618  5664 I jxcore-log: 
,10-29 21:25:22.884  5618  5664 I jxcore-log: 2016-10-30 01:25:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:22.884  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:22.884  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:22.884  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:22.884  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:22.884  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:22.884  5618  5664 I jxcore-log: 
,10-29 21:25:23.704   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:23.942  5618  5664 I jxcore-log: 2016-10-30 01:25:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:23.942  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:23.942  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:23.942  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:23.942  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:23.942  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:23.942  5618  5664 I jxcore-log: 
,10-29 21:25:23.946  5618  5664 I jxcore-log: 2016-10-30 01:25:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:23.946  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:23.946  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:23.946  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:23.946  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:23.946  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:23.946  5618  5664 I jxcore-log: 
,10-29 21:25:24.705   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:24.978  5618  5664 I jxcore-log: 2016-10-30 01:25:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:24.978  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:24.978  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:24.978  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:24.978  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:24.978  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:24.978  5618  5664 I jxcore-log: 
,10-29 21:25:24.985  5618  5664 I jxcore-log: 2016-10-30 01:25:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:24.985  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:24.985  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:24.985  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:24.985  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:24.985  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:24.985  5618  5664 I jxcore-log: 
,10-29 21:25:25.707   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:26.020  5618  5664 I jxcore-log: 2016-10-30 01:25:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:26.020  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:26.020  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:26.020  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:26.020  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:26.020  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:26.020  5618  5664 I jxcore-log: 
,10-29 21:25:26.024  5618  5664 I jxcore-log: 2016-10-30 01:25:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:26.024  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:26.024  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:26.024  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:26.024  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:26.024  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:26.024  5618  5664 I jxcore-log: 
,10-29 21:25:26.708   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,10-29 21:25:27.053  5618  5664 I jxcore-log: 2016-10-30 01:25:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:27.053  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:27.053  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:27.053  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:27.053  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:27.053  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:27.053  5618  5664 I jxcore-log: 
,10-29 21:25:27.057  5618  5664 I jxcore-log: 2016-10-30 01:25:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:27.057  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:27.057  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:27.057  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:27.057  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:27.057  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:27.057  5618  5664 I jxcore-log: 
,10-29 21:25:27.709   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-29 21:25:28.087  5618  5664 I jxcore-log: 2016-10-30 01:25:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:28.087  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:28.087  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:28.087  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:28.087  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:28.087  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:28.087  5618  5664 I jxcore-log: 
,10-29 21:25:28.094  5618  5664 I jxcore-log: 2016-10-30 01:25:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:28.094  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:28.094  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:28.094  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:28.094  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:28.094  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:28.094  5618  5664 I jxcore-log: 
,10-29 21:25:29.129  5618  5664 I jxcore-log: 2016-10-30 01:25:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-29 21:25:29.129  5618  5664 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-29 21:25:29.129  5618  5664 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-29 21:25:29.129  5618  5664 I jxcore-log: emit@events.js:82:1
10-29 21:25:29.129  5618  5664 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-29 21:25:29.129  5618  5664 I jxcore-log: emit@events.js:82:1'
10-29 21:25:29.129  5618  5664 I jxcore-log: 
,10-29 21:25:29.140  5618  5664 E jxcore  : Error!: error is undefined
10-29 21:25:29.140  5618  5664 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-29 21:25:29.143  5618  5664 I jxcore-log: 2016-10-30 01:25:29 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-29 21:25:29.143  5618  5664 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
10-29 21:25:29.143  5618  5664 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-29 21:25:29.143  5618  5664 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-29 21:25:29.143  5618  5664 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-29 21:25:29.143  5618  5664 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-29 21:25:29.143  5618  5664 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-29 21:25:29.143  5618  5664 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-29 21:25:29.146  5618  5664 I jxcore-log: 2016-10-30 01:25:29 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-29 21:25:29.146  5618  5664 I jxcore-log: 
,10-29 21:25:29.149  5618  5664 E jxcore-log: TypeError: 
10-29 21:25:29.149  5618  5664 E jxcore-log: error is undefined
10-29 21:25:29.149  5618  5664 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
10-29 21:25:29.149  5618  5664 E jxcore-log: 
,10-29 21:25:29.246   927  3565 I WindowState: WIN DEATH: Window{58ef86 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-29 21:25:29.247   927  2950 D WifiService: Client connection lost with reason: 4
,10-29 21:25:29.247   927  3825 D GraphicsStats: Buffer count: 2
,10-29 21:25:29.259   527   527 I Zygote  : Process 5618 exited cleanly (139)
,10-29 21:25:29.263   927   938 I ActivityManager: Process com.test.thalitest (pid 5618) has died
,10-29 21:25:29.278   927   938 I ActivityManager: Start proc 5973:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-29 21:25:29.538  5971  5971 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-29 21:25:29.544  5971  5971 D AndroidRuntime: CheckJNI is OFF
,10-29 21:25:29.572  5971  5971 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-29 21:25:29.607  5971  5971 I Radio-JNI: register_android_hardware_Radio DONE
,10-29 21:25:29.608   927  3856 I WindowManager: Screenshot max retries 4 of Token{cf74d68 ActivityRecord{e3fa88b u0 com.test.thalitest/.MainActivity t2}} appWin=Window{105e5ad u0 Starting com.test.thalitest} drawState=4
,10-29 21:25:29.626  5971  5971 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-29 21:25:29.635   927   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
10-29 21:25:29.636   927   941 I ActivityManager: Killing 5973:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-29 21:25:29.758   927   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-29 21:25:29.758   927   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-29 21:25:29.759   927   953 I art     : Starting a blocking GC Explicit
10-29 21:25:29.761   927   941 E ActivityManager: Failure starting process com.test.thalitest
10-29 21:25:29.761   927   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-29 21:25:29.761   927   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:25:29.761   927   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:25:29.761   927   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 21:25:29.761   927   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-29 21:25:29.762   927   941 I ActivityManager:   Force finishing activity ActivityRecord{e3fa88b u0 com.test.thalitest/.MainActivity t2}
,10-29 21:25:29.778   927   946 W WindowManager: Failed looking up window
10-29 21:25:29.778   927   946 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@da612c4 does not exist
10-29 21:25:29.778   927   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-29 21:25:29.778   927   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-29 21:25:29.778   927   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-29 21:25:29.778   927   946 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-29 21:25:29.778   927   946 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-29 21:25:29.778   927   946 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-29 21:25:29.778   927   946 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-29 21:25:29.778   927   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:25:29.778   927   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:25:29.778   927   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 21:25:29.778   927   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-29 21:25:29.781   927   939 W ActivityManager: Spurious death for ProcessRecord{ceb5c73 0:com.test.thalitest/u0a77}, curProc for 5973: null
,10-29 21:25:29.854   927   953 I art     : Explicit concurrent mark sweep GC freed 56750(3MB) AllocSpace objects, 16(560KB) LOS objects, 33% free, 29MB/43MB, paused 1.444ms total 94.797ms
,10-29 21:25:29.874   927   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-29 21:25:29.877  5971  5971 I art     : System.exit called, status: 0
,10-29 21:25:29.877  5971  5971 I AndroidRuntime: VM exiting with result code 0.
,10-29 21:25:29.881   927   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-29 21:25:29.893   927   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-29 21:25:29.898  3635  3635 I Keyboard.Facilitator: resetDictionaries() : en_US
10-29 21:25:29.899  5884  5884 D BluetoothMapAppObserver: onReceive
10-29 21:25:29.900  5884  5884 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-29 21:25:29.901  4031  4156 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-29 21:25:29.911   927  2915 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-29 21:25:29.925  3635  5994 I Keyboard.Facilitator.DecoderInitializer: run()
,10-29 21:25:29.935  3635  5994 I Decoder : createOrResetDecoder
,10-29 21:25:29.950  3782  3782 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-29 21:25:29.964    28    28 W kworker/1:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-29 21:25:29.964  3548  3548 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-29 21:25:29.964  3548  3548 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-29 21:25:29.973  3368  5997 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-29 21:25:29.971    28    28 W kworker/1:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-29 21:25:29.978    28    28 W kworker/1:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-29 21:25:29.980  3696  6000 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-29 21:25:29.982  3696  6000 D AccountUtils: Clearing selected account for com.test.thalitest
,10-29 21:25:29.989   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-29 21:25:29.994   927   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,10-29 21:25:29.994   927   940 E PackageManager: Failed to write settings, restoring backup
10-29 21:25:29.994   927   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-29 21:25:29.994   927   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-29 21:25:29.994   927   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-29 21:25:29.994   927   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-29 21:25:29.994   927   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-29 21:25:29.994   927   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:25:29.994   927   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:25:29.994   927   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-29 21:25:29.995  3817  3925 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-29 21:25:30.000   927   941 E DropBoxManagerService: Can't write: system_server_wtf
10-29 21:25:30.000   927   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-29 21:25:30.000   927   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-29 21:25:30.000   927   941 E DropBoxManagerService: 	... 13 more
,10-29 21:25:30.001  3368  3390 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjDBBC0B938) - 
,10-29 21:25:30.007   927  3565 I ActivityManager: Start proc 6002:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-29 21:25:30.008  3817  3925 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-29 21:25:30.008  3817  3925 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3817
10-29 21:25:30.008  3817  3925 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:25:30.008  3817  3925 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-29 21:25:30.010  3548  3548 I ConfigService: onCreate
,10-29 21:25:30.013   927   939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-29 21:25:30.013  3548  6011 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-29 21:25:30.013  3548  6011 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-29 21:25:30.013  3548  6011 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-29 21:25:30.016  3548  6011 W SQLiteOpenHelper: Opened config.db in read-only mode
10-29 21:25:30.017   927  6013 E DropBoxManagerService: Can't write: system_app_crash
10-29 21:25:30.017   927  6013 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-29 21:25:30.017   927  6013 E DropBoxManagerService: 	... 5 more
10-29 21:25:30.020  3817  3925 I Process : Sending signal. PID: 3817 SIG: 9
10-29 21:25:30.038  3635  5994 I Keyboard.Facilitator.MainLanguageModelLoader: run()
10-29 21:25:30.061  3696  6000 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-29 21:25:30.086  3696  6000 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:25:30.086  3696  6000 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-29 21:25:30.087  3696  6000 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:25:30.087  3696  6000 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 21:25:30.087  3696  6000 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
10-29 21:25:30.100  3368  3390 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-29 21:25:30.100  3368  3390 E AndroidRuntime: Process: android.process.acore, PID: 3368
10-29 21:25:30.100  3368  3390 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-29 21:25:30.100  3368  3390 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: Can't write: system_app_crash
10-29 21:25:30.102   927  6019 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-29 21:25:30.102   927  6019 E DropBoxManagerService: 	... 5 more
10-29 21:25:30.115   927  2914 W InputDispatcher: channel '5ae8fd1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-29 21:25:30.115   927  2914 E InputDispatcher: channel '5ae8fd1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
10-29 21:25:30.116   927  3856 D GraphicsStats: Buffer count: 1
10-29 21:25:30.116   927   939 I WindowState: WIN DEATH: Window{5ae8fd1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
10-29 21:25:30.117   927   939 W InputDispatcher: Attempted to unregister already unregistered input channel '5ae8fd1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
10-29 21:25:30.120  3368  3390 I Process : Sending signal. PID: 3368 SIG: 9
,10-29 21:25:30.127   927  3130 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3817) has died
10-29 21:25:30.128   927  3130 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
10-29 21:25:30.157  3696  6021 I GMPM-SVC: App measurement is starting up
10-29 21:25:30.160  3696  6021 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-29 21:25:30.161  3696  6021 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-29 21:25:30.361   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
