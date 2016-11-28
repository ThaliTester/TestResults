#### Test 9554107330bd934_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-28 12:58:29.613  3501  5531 I VacuumService: Vacuum at: now=1480355909613 tag=VacuumService
,11-28 12:58:29.638  3501  5534 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-28 12:58:29.663  3501  5532 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-28 12:58:29.666  3501  5532 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-28 12:58:29.707  3501  5532 W Uploader:  no longer exists, so no auth token.
11-28 12:58:29.713  3501  5534 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-28 12:58:29.938  3501  5536 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-28 12:58:30.003  5537  5537 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-28 12:58:30.006  5537  5537 D AndroidRuntime: CheckJNI is OFF
11-28 12:58:30.019  3501  5534 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-28 12:58:30.029  5537  5537 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-28 12:58:30.057  5537  5537 I Radio-JNI: register_android_hardware_Radio DONE
11-28 12:58:30.072  5537  5537 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-28 12:58:30.076   931  3113 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-28 12:58:30.106   931  3113 I ActivityManager: Start proc 5549:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-28 12:58:30.109  5537  5537 D AndroidRuntime: Shutting down VM
,11-28 12:58:30.435   931  3123 I WindowManager: Screenshot max retries 4 of Token{a7455b6 ActivityRecord{b918951 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{b6b1189 u0 Starting com.test.thalitest} drawState=2
,11-28 12:58:30.458  3501  5536 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-28 12:58:30.514  5549  5549 I CordovaLog: Changing log level to DEBUG(3)
,11-28 12:58:30.514  5549  5549 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-28 12:58:30.514  5549  5549 D CordovaActivity: CordovaActivity.onCreate()
,11-28 12:58:30.522  5549  5549 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-28 12:58:30.523  3501  5532 W Uploader:  no longer exists, so no auth token.
,11-28 12:58:30.529  3501  5534 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-28 12:58:30.555  5549  5549 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-28 12:58:30.583  3501  5536 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-28 12:58:30.623  5549  5549 I LibraryLoader: Time to load native libraries: 64 ms (timestamps 917-981)
11-28 12:58:30.623  5549  5549 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-28 12:58:30.660  5549  5549 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dfa3910}
,11-28 12:58:30.661  5549  5549 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-28 12:58:30.661  5549  5549 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-28 12:58:30.671  5549  5549 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-28 12:58:30.673  5549  5549 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-28 12:58:30.710  5549  5549 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-28 12:58:30.725  5549  5549 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-28 12:58:30.726  5549  5549 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-28 12:58:30.726  5549  5549 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-28 12:58:30.726  5549  5549 I Adreno  : Build Date                       : 12/06/15
11-28 12:58:30.726  5549  5549 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-28 12:58:30.726  5549  5549 I Adreno  : Local Branch                     : mybranch17112971
11-28 12:58:30.726  5549  5549 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-28 12:58:30.726  5549  5549 I Adreno  : Remote Branch                    : NONE
11-28 12:58:30.726  5549  5549 I Adreno  : Reconstruct Branch               : NOTHING
,11-28 12:58:30.774   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9e6f454:true
,11-28 12:58:30.807  2833  2833 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33510]" dev="sockfs" ino=33510 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 12:58:30.807  2833  2833 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33510]" dev="sockfs" ino=33510 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 12:58:30.818  5549  5549 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-28 12:58:30.827  5549  5549 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-28 12:58:30.831  5549  5549 D PluginManager: init()
,11-28 12:58:30.833  5549  5549 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-28 12:58:30.848  5549  5549 D CordovaActivity: Started the activity.
,11-28 12:58:30.848  5549  5549 D CordovaActivity: Resumed the activity.
,11-28 12:58:30.852  5549  5586 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-28 12:58:30.850  2833  2833 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30572]" dev="sockfs" ino=30572 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 12:58:30.850  2833  2833 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30572]" dev="sockfs" ino=30572 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 12:58:30.850  3766  3766 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15239]" dev="sockfs" ino=15239 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 12:58:30.856  5549  5549 D CordovaActivity: Paused the activity.
11-28 12:58:30.853  3766  3766 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15239]" dev="sockfs" ino=15239 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 12:58:30.858  5549  5573 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-28 12:58:30.876  5549  5586 I OpenGLRenderer: Initialized EGL, version 1.4
,11-28 12:58:30.888  5549  5549 D CordovaActivity: Stopped the activity.
,11-28 12:58:30.945   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +505ms (total +855ms)
,11-28 12:58:30.967  5549  5549 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-28 12:58:30.992  5549  5549 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5549
,11-28 12:58:31.089  5549  5549 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-28 12:58:31.234  5549  5588 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -585893584
,11-28 12:58:31.238  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-28 12:58:31.238  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-28 12:58:31.238  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-28 12:58:31.238  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-28 12:58:31.238  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-28 12:58:31.238  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c3b1e7 added. We now have 1 listener(s)
,11-28 12:58:31.240  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
11-28 12:58:31.241  5549  5588 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-28 12:58:31.241  5549  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:58:31.241  5549  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-28 12:58:31.244  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd19432 added. We now have 1 listener(s)
11-28 12:58:31.244  5549  5588 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:58:31.248   931  2891 D WifiService: New client listening to asynchronous messages
,11-28 12:58:31.248  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 12:58:31.248  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-28 12:58:31.249  5549  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-28 12:58:31.249  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-28 12:58:31.249  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-28 12:58:31.249  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-28 12:58:31.249  5549  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-28 12:58:31.250  5549  5588 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-28 12:58:31.358  5549  5549 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-28 12:58:31.360  5549  5549 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-28 12:58:31.361  5549  5549 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-28 12:58:31.757  5549  5558 I art     : Background partial concurrent mark sweep GC freed 58024(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 2.167ms total 122.377ms
,11-28 12:58:31.880  5549  5596 W jxcore-log: Initializing JXcore engine
,11-28 12:58:31.880  5549  5596 W jxcore-log: JXcore engine is ready
,11-28 12:58:31.900  5596  5596 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12486 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-28 12:58:31.900  5596  5596 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13029]" dev="sockfs" ino=13029 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-28 12:58:31.900  5596  5596 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-28 12:58:31.900  5596  5596 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30551]" dev="sockfs" ino=30551 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-28 12:58:31.912  5549  5596 W jxcore-log: Starting JXcore engine
,11-28 12:58:31.962  5549  5596 W jxcore-log: Platform android
11-28 12:58:31.962  5549  5596 W jxcore-log: 
,11-28 12:58:31.962  5549  5596 W jxcore-log: Process ARCH arm
11-28 12:58:31.962  5549  5596 W jxcore-log: 
,11-28 12:58:32.157  5549  5596 I jxcore-log: JXcore Cordova bridge is ready!
11-28 12:58:32.157  5549  5596 I jxcore-log: 
,11-28 12:58:32.158  5549  5596 W jxcore-log: JXcore engine is started
,11-28 12:58:32.170  5549  5588 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-28 12:58:32.178  5549  5549 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-28 12:58:32.178  5549  5549 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-28 12:58:34.732   931  5293 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 12:58:34.794   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:58:35.796   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:58:36.796   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:58:37.797   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:58:38.798   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:58:39.799   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-28 12:58:41.919  5549  5596 I jxcore-log: 2016-11-28 17:58:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-28 12:58:41.919  5549  5596 I jxcore-log: 
,11-28 12:58:41.921  5549  5596 I jxcore-log: 2016-11-28 17:58:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-28 12:58:41.921  5549  5596 I jxcore-log: 
,11-28 12:58:41.927  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-28 12:58:41.928  5549  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 12:58:41.928  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:58:41.928  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:58:41.928  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:58:41.928  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 12:58:41.928  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 12:58:41.928  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 12:58:41.928  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 12:58:41.928  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 12:58:41.929  5549  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 12:58:41.930  5549  5596 I jxcore-log: 2016-11-28 17:58:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-28 12:58:41.930  5549  5596 I jxcore-log: 
,11-28 12:58:41.931  5549  5596 I jxcore-log: 2016-11-28 17:58:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-28 12:58:41.931  5549  5596 I jxcore-log: 
,11-28 12:58:42.176  5549  5596 I jxcore-log: 2016-11-28 17:58:42 - DEBUG UnitTest_app: 'Running unit tests'
11-28 12:58:42.176  5549  5596 I jxcore-log: 
,11-28 12:58:42.177  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:58:42.177  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8df17ae added. We now have 2 listener(s)
11-28 12:58:42.178  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:58:42.178  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 12:58:42.178  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:58:42.178  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:58:42.178  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec8494f added. We now have 2 listener(s)
11-28 12:58:42.178  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:58:42.179  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 12:58:42.180  5549  5596 D executeNativeTests: Running unit tests
,11-28 12:58:42.221  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 12:58:42.221  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c added. We now have 3 listener(s)
11-28 12:58:42.222  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:58:42.222  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 12:58:42.222  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:58:42.222  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:58:42.222  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 added. We now have 3 listener(s)
,11-28 12:58:42.222  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 12:58:42.223  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 12:58:42.224  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-28 12:58:42.224  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-28 12:58:42.225  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-28 12:58:42.225  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 12:58:42.225  5549  5596 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-28 12:58:42.225  5549  5596 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 12:58:42.225  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-28 12:58:42.226  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 12:58:42.226  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 12:58:42.226  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 12:58:42.226  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:58:42.226  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:58:42.226  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:58:42.226  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:58:42.226  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:58:42.226  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:58:42.227  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c removed from the list
11-28 12:58:42.227  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:58:42.227  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 removed from the list
11-28 12:58:42.227  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:58:42.227  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.227  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.227  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.227  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.227  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.228  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:58:42.228  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-28 12:58:42.228  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:58:42.228  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:58:42.228  5549  5596 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-28 12:58:42.229  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:58:42.229  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-28 12:58:42.229  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:58:42.229  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:58:42.229  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:58:42.229  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:58:42.229  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:58:42.229  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:58:42.229  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 12:58:42.229  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.229  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.230  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.230  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.230  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.230  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:58:42.230  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:58:42.230  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:58:42.230  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 12:58:42.232  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 12:58:42.233  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:58:42.233  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:58:42.233  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:58:42.233  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:58:42.233  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 12:58:42.233  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:58:42.233  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:58:42.233  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:58:42.233  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:58:42.233  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.233  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.234  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:42.234  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.234  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.234  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:58:42.234  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:58:42.234  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:58:42.234  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:58:42.235  5549  5596 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-28 12:58:42.236  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:58:42.236  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-28 12:58:42.247  5549  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 12:58:42.247  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:58:42.247  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:58:42.247  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:58:42.247  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 12:58:42.247  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 12:58:42.247  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 12:58:42.247  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 12:58:42.247  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 12:58:42.248  5549  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 12:58:42.248  5549  5596 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-28 12:58:42.248  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 12:58:42.248  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 12:58:42.248  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 12:58:42.248  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:58:42.248  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 12:58:42.250  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:58:42.251  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 12:58:42.251  5549  5596 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 12:58:42.251  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 12:58:42.254  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:42.254  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 12:58:42.254  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:58:42.255  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 12:58:42.256  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 12:58:42.256  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-28 12:58:42.259  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-28 12:58:42.263  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-28 12:58:42.263  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:42.263  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 12:58:42.263  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 12:58:42.263  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 12:58:42.264  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 12:58:42.264  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.265  5549  5596 D BluetoothAdapter: STATE_ON
,11-28 12:58:42.272  4504  4723 D BtGatt.GattService: registerClient() - UUID=0dd096ce-2d0b-426b-877e-ee9427591bb3
,11-28 12:58:42.273  4504  4565 D BtGatt.GattService: onClientRegistered() - UUID=0dd096ce-2d0b-426b-877e-ee9427591bb3, clientIf=5
,11-28 12:58:42.274  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-28 12:58:42.274  4504  4715 D BtGatt.GattService: start scan with filters
,11-28 12:58:42.278  4504  4568 D BtGatt.ScanManager: handling starting scan
11-28 12:58:42.278  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-28 12:58:42.278  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.278  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 12:58:42.278  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.279  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 12:58:42.279  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 12:58:42.279  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:58:42.279  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 12:58:42.279  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 12:58:42.279  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 12:58:42.279  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-28 12:58:42.279  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.279  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 12:58:42.280  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:58:42.280  4504  4568 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
11-28 12:58:42.280  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 12:58:42.280  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.280  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.280  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:42.281  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:58:42.281  5549  5596 I io.jxcore.node.ConnectionHelper: start: OK
11-28 12:58:42.282  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 12:58:42.282  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:58:42.282  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:58:42.282  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 12:58:42.282  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:58:42.287  4504  4565 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 12:58:42.287  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:42.288  4504  4568 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-28 12:58:42.294  4504  4565 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 12:58:42.294  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:42.294  4504  4568 D BtGatt.ScanManager: Starting BLE batch scan
11-28 12:58:42.295  4504  4568 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 12:58:42.304  4504  4565 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-28 12:58:42.304  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:58:42.310  4504  4565 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 12:58:42.310  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:58:42.784  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-28 12:58:42.785  5549  5549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 12:58:42.785  5549  5549 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 12:58:47.288  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 12:58:47.289  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 12:58:47.289  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-28 12:58:47.289  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-28 12:58:47.289  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-28 12:58:47.290  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 12:58:47.290  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 12:58:47.290  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 12:58:47.290  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.290  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 12:58:47.290  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-28 12:58:47.292  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.293  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.293  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.293  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 12:58:47.293  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.296  5549  5596 D BluetoothAdapter: STATE_ON
,11-28 12:58:47.297  4504  4715 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 12:58:47.298  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 12:58:47.300  4504  4568 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 12:58:47.300  5549  5596 D BluetoothAdapter: STATE_ON
,11-28 12:58:47.302  4504  4519 D BtGatt.GattService: stopScan() - queue size =1
,11-28 12:58:47.303  4504  4723 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 12:58:47.304  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 12:58:47.304  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:47.305  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 12:58:47.305  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.305  4504  4504 D BtGatt.ScanManager: awakened up at time 177663
11-28 12:58:47.305  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.305  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.305  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.306  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 12:58:47.306  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:47.306  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:47.307  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.307  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 12:58:47.307  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 12:58:47.308  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:58:47.309  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:47.311  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.311  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:58:47.311  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:47.311  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:47.311  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:58:47.311  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:58:47.311  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:58:47.311  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:58:47.311  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:58:47.311  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:58:47.311  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 12:58:47.312  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:58:47.312  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 12:58:47.312  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 12:58:47.312  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:58:47.312  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 12:58:47.312  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:58:47.312  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:58:47.313  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:58:47.313  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:58:47.313  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:58:47.313  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 12:58:47.313  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 12:58:47.313  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:58:47.313  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 12:58:47.316  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:58:47.316  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:58:47.316  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 12:58:47.324  4504  4565 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-28 12:58:47.324  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:47.324  4504  4565 D BtGatt.GattService: current time is 177682881688
11-28 12:58:47.325  4504  4565 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -67, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -68, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -69, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -106, -15, -31, -128, 20, -7, 1, -128, -100, 82, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -125, -124, 101, 3, 2, -25, 21, 62, -13, -8, 44, 0, 53, 33, -121, 80, 73, -44, 1, -128, -99, 82, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -1, -52, 101, 3, 2, -25, 21, 63, 64, -91, 33, 0, 37, -47, 14, -113, 116, -46, 1, -128, -74, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -68, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 12:58:47.326  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-28 12:58:47.327  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-28 12:58:47.327  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-28 12:58:47.327  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -125, -124, 101, 3, 2, -25, 21, 62, -13, -8, 44]
11-28 12:58:47.328  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -1, -52, 101, 3, 2, -25, 21, 63, 64, -91, 33]
,11-28 12:58:47.328  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-28 12:58:47.328  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-28 12:58:47.334  4504  4565 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 12:58:47.334  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:47.334  4504  4568 D BtGatt.ScanManager: stopping BLe Batch
,11-28 12:58:47.339  4504  4565 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 12:58:47.339  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:47.339  4504  4568 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 12:58:47.344  4504  4565 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 12:58:47.344  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:58:47.814  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 12:58:51.580   931  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 12:58:52.316  5549  5596 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-28 12:58:52.321  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:58:52.321  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-28 12:58:52.335  5549  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 12:58:52.335  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:58:52.335  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:58:52.335  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:58:52.335  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 12:58:52.335  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 12:58:52.335  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 12:58:52.335  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 12:58:52.335  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 12:58:52.339  5549  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 12:58:52.339  5549  5596 D io.jxcore.node.ConnectivityMonitor: start: OK
11-28 12:58:52.339  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 12:58:52.339  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 12:58:52.340  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 12:58:52.340  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:58:52.340  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 12:58:52.343  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:58:52.344  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 12:58:52.345  5549  5596 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 12:58:52.345  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 12:58:52.346  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:58:52.349  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:52.349  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 12:58:52.350  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 12:58:52.350  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 12:58:52.350  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-28 12:58:52.354  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.354  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 12:58:52.354  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 12:58:52.354  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 12:58:52.354  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-28 12:58:52.354  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.355  5549  5596 D BluetoothAdapter: STATE_ON
,11-28 12:58:52.359  4504  4723 D BtGatt.GattService: registerClient() - UUID=0f496964-c445-453d-9d22-0b5084177001
,11-28 12:58:52.360  4504  4565 D BtGatt.GattService: onClientRegistered() - UUID=0f496964-c445-453d-9d22-0b5084177001, clientIf=5
,11-28 12:58:52.360  5549  5559 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 12:58:52.360  4504  4519 D BtGatt.GattService: start scan with filters
11-28 12:58:52.363  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 12:58:52.363  4504  4568 D BtGatt.ScanManager: handling starting scan
11-28 12:58:52.363  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.363  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-28 12:58:52.363  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.363  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 12:58:52.363  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 12:58:52.363  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.363  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 12:58:52.363  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 12:58:52.363  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.363  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.364  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.364  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.364  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 12:58:52.364  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.367  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:52.367  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:58:52.367  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.367  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.367  5549  5596 I io.jxcore.node.ConnectionHelper: start: OK
11-28 12:58:52.367  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 12:58:52.370  4504  4565 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-28 12:58:52.370  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.370  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.370  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.370  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.371  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:58:52.371  4504  4568 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 12:58:52.371  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:58:52.371  5549  5596 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 12:58:52.371  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 12:58:52.371  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 12:58:52.371  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:58:52.372  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 12:58:52.372  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:58:52.372  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 12:58:52.372  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 12:58:52.372  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.372  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 12:58:52.372  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 12:58:52.372  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.372  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.372  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.372  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 12:58:52.372  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.373  5549  5596 D BluetoothAdapter: STATE_ON
,11-28 12:58:52.373  4504  4723 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 12:58:52.373  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 12:58:52.374  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:58:52.375  4504  4517 D BtGatt.GattService: stopScan() - queue size =1
,11-28 12:58:52.376  4504  4723 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 12:58:52.376  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 12:58:52.376  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.376  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 12:58:52.376  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.376  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.376  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.377  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.377  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 12:58:52.377  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.377  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.377  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.377  4504  4565 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 12:58:52.377  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 12:58:52.377  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.377  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 12:58:52.377  4504  4568 D BtGatt.ScanManager: Starting BLE batch scan
11-28 12:58:52.377  4504  4568 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 12:58:52.378  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:58:52.378  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.379  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.379  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:58:52.379  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.379  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.379  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:58:52.379  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:58:52.379  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:58:52.379  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:58:52,.379  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:58:52.379  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:58:52.379  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:58:52.379  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:58:52.380  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:58:52.380  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 12:58:52.380  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:58:52.380  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 12:58:52.380  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.380  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 12:58:52.380  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 12:58:52.380  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.380  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.380  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.380  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:58:52.380  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.380  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.381  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.381  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.382  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.382  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.382  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.383  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.383  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.383  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.383  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:58:52.383  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:58:52.383  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:58:52.383  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:58:52.384  5549  5596 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-28 12:58:52.386  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:58:52.387  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-28 12:58:52.389  4504  4565 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 12:58:52.389  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.393  5549  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 12:58:52.393  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:58:52.393  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:58:52.393  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:58:52.393  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 12:58:52.393  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 12:58:52.393  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 12:58:52.393  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 12:58:52.393  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 12:58:52.394  4504  4565 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 12:58:52.394  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.395  4504  4568 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 12:58:52.396  5549  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 12:58:52.396  5549  5596 D io.jxcore.node.ConnectivityMonitor: start: OK
11-28 12:58:52.396  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 12:58:52.396  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 12:58:52.396  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 12:58:52.396  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:58:52.396  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 12:58:52.399  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 12:58:52.400  4504  4565 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 12:58:52.400  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.401  4504  4565 E BtGatt.ContextMap: Context not found for ID 5
11-28 12:58:52.402  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 12:58:52.402  5549  5596 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 12:58:52.402  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 12:58:52.402  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 12:58:52.405  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.405  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 12:58:52.406  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 12:58:52.406  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 12:58:52.406  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-28 12:58:52.408  4504  4565 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 12:58:52.408  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.409  4504  4568 D BtGatt.ScanManager: stopping BLe Batch
11-28 12:58:52.411  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.411  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 12:58:52.411  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 12:58:52.411  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 12:58:52.411  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 12:58:52.411  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.412  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:58:52.414  4504  4565 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-28 12:58:52.414  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.414  4504  4568 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 12:58:52.416  4504  4519 D BtGatt.GattService: registerClient() - UUID=acc3cf0d-79ce-4893-a6c8-96829297f4a1
11-28 12:58:52.416  4504  4565 D BtGatt.GattService: onClientRegistered() - UUID=acc3cf0d-79ce-4893-a6c8-96829297f4a1, clientIf=5
11-28 12:58:52.417  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 12:58:52.417  4504  4715 D BtGatt.GattService: start scan with filters
11-28 12:58:52.418  4504  4565 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 12:58:52.419  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.419  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 12:58:52.419  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.419  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 12:58:52.419  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.419  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 12:58:52.420  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 12:58:52.420  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.420  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 12:58:52.420  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 12:58:52.420  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.420  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.420  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.420  4504  4568 D BtGatt.ScanManager: handling starting scan
11-28 12:58:52.420  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.421  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 12:58:52.421  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:52.423  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.423  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:58:52.423  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.423  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:52.423  5549  5596 I io.jxcore.node.ConnectionHelper: start: OK
11-28 12:58:52.424  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.426  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.426  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.426  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 12:58:52.426  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:58:52.427  4504  4565 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 12:58:52.427  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.427  4504  4568 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 12:58:52.432  4504  4565 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 12:58:52.432  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.432  4504  4568 D BtGatt.ScanManager: Starting BLE batch scan
11-28 12:58:52.432  4504  4568 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 12:58:52.441  4504  4565 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 12:58:52.441  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:52.445  4504  4565 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 12:58:52.446  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:58:52.927  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-28 12:58:52.927  5549  5549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-28 12:58:52.928  5549  5549 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 12:58:53.611   931  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 12:58:53.615   931  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-28 12:58:56.636   931  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 12:58:56.641   931  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-28 12:58:57.424  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 12:58:57.424  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 12:58:57.424  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-28 12:58:57.425  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-28 12:58:57.425  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-28 12:58:57.425  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:58:57.425  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 12:58:57.425  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 12:58:57.426  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.426  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 12:58:57.426  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 12:58:57.426  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.426  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.427  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.427  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 12:58:57.427  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:57.429  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:58:57.430  4504  4723 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 12:58:57.430  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 12:58:57.431  4504  4568 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 12:58:57.432  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:58:57.434  4504  4517 D BtGatt.GattService: stopScan() - queue size =1
11-28 12:58:57.437  4504  4715 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 12:58:57.438  4504  4504 D BtGatt.ScanManager: awakened up at time 187796
11-28 12:58:57.439  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 12:58:57.439  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.439  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-28 12:58:57.440  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.440  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.440  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.440  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.440  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 12:58:57.441  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.441  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.441  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.441  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 12:58:57.441  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 12:58:57.443  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:58:57.444  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.445  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.446  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:58:57.446  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:58:57.446  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:58:57.447  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:58:57.448  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:58:57.448  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 12:58:57.448  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:58:57.448  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 12:58:57.448  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 12:58:57.448  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:58:57.448  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-28 12:58:57.449  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:58:57.449  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:58:57.449  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 12:58:57.449  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:58:57.453  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:58:57.453  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-28 12:58:57.453  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 12:58:57.466  4504  4565 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,11-28 12:58:57.466  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:57.467  4504  4565 D BtGatt.GattService: current time is 187825014846
11-28 12:58:57.467  4504  4565 D BtGatt.GattService: Batch record : [86, -31, -99, 30, -52, -57, 1, 0, -92, 98, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, 12, -88, 101, 3, 2, -29, 20, 62, 24, -121, 35, 28, 6, 8, 116, 105, 115, 53, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 48, -60, -48, -14, 51, -33, 1, 0, -95, 98, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -26, 55, -125, -44, -32, -2, 61, 78, 9, -128, 101, 3, 2, -29, 20, 61, -36, 25, 60, 28, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 35, 97, 126, -92, 22, -56, 1, -128, -68, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -67, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -67, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -77, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -68, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 110, -101, -122, 59, -22, -58, 1, -128, -99, 52, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 94, -39, 35, -35, 57, 53, -105, -123, 5, -96, 101, 3, 3, -29, 27, -105, -10, -113, -80, 0]
11-28 12:58:57.467  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, 12, -88, 101, 3, 2, -29, 20, 62, 24, -121, 35, 6, 8, 116, 105, 115, 53, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-28 12:58:57.468  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -26, 55, -125, -44, -32, -2, 61, 78, 9, -128, 101, 3, 2, -29, 20, 61, -36, 25, 60, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,11-28 12:58:57.468  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-28 12:58:57.468  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-28 12:58:57.469  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-28 12:58:57.469  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-28 12:58:57.469  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 12:58:57.469  4504  4565 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 94, -39, 35, -35, 57, 53, -105, -123, 5, -96, 101, 3, 3, -29, 27, -105, -10, -113, -80]
,11-28 12:58:57.475  4504  4565 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 12:58:57.475  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:58:57.476  4504  4568 D BtGatt.ScanManager: stopping BLe Batch
,11-28 12:58:57.480  4504  4565 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 12:58:57.481  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:58:57.481  4504  4568 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 12:58:57.486  4504  4565 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 12:58:57.486  4504  4565 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:58:57.950  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 12:58:57.950  5549  5549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-28 12:58:57.950  5549  5549 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 12:58:59.800   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:00.802   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:01.803   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:02.226   931  5293 D NetlinkSocketObserver: NeighborEvent{elapsedMs=192584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-28 12:59:02.448  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 12:59:02.448  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:02.448  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-28 12:59:02.448  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 12:59:02.449  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-28 12:59:02.449  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-28 12:59:02.449  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 12:59:02.449  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
,11-28 12:59:02.449  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:59:02.450  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:02.450  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.450  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 12:59:02.453  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.453  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.456  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.456  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.457  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.457  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:02.457  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.457  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.457  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:02.458  5549  5596 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-28 12:59:02.460  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:02.460  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:02.460  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:02.461  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 12:59:02.461  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:02.461  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.461  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.461  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:02.462  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.462  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.462  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.464  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.465  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.466  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.466  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-28 12:59:02.466  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.466  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:59:02.466  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.468  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 12:59:02.469  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:02.469  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:02.469  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:02.469  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 12:59:02.469  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:02.470  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.470  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.470  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.470  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.470  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.470  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.472  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.472  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.472  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.472  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:02.473  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.473  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.473  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:02.474  5549  5596 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-28 12:59:02.474  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:02.474  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:02.474  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:02.474  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:02.475  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:02.475  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.475  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.475  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.475  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.475  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.475  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.477  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.477  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.477  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.477  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:02.478  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.478  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.478  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.479  5549  5596 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-28 12:59:02.479  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:02.479  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:02.480  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:02.480  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:02.480  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:02.480  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.480  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.480  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:02.480  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.480  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.481  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.482  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.483  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.483  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.483  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:02.483  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.483  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.483  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.484  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 12:59:02.484  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-28 12:59:02.485  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 12:59:02.485  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 12:59:02.485  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 12:59:02.485  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 12:59:02.485  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-28 12:59:02.485  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 12:59:02.486  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 12:59:02.486  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:02.486  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:02.486  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-28 12:59:02.486  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:02.486  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:02.486  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.486  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:59:02.487  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.487  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.487  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.487  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.489  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.489  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.489  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.489  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:02.489  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.489  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.490  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:02.490  5549  5596 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 12:59:02.491  5549  5596 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 12:59:02.491  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-28 12:59:02.496  5549  5596 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-28 12:59:02.496  5549  5596 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-28 12:59:02.496  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-28 12:59:02.496  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-28 12:59:02.497  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 12:59:02.498  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-28 12:59:02.499  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 12:59:02.499  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 12:59:02.499  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-28 12:59:02.499  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 12:59:02.499  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 12:59:02.499  5549  5596 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-28 12:59:02.500  5549  5596 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-28 12:59:02.500  5549  5596 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-28 12:59:02.500  5549  5596 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 12:59:02.500  5549  5596 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 12:59:02.500  5549  5596 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-28 12:59:02.500  5549  5596 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 12:59:02.500  5549  5596 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-28 12:59:02.500  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-28 12:59:02.505  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-28 12:59:02.506  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-28 12:59:02.506  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-28 12:59:02.507  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-28 12:59:02.507  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,11-28 12:59:02.507  5549  5596 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-28 12:59:02.507  5549  5596 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 12:59:02.508  5549  5596 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-28 12:59:02.508  5549  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-28 12:59:02.509  5549  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-28 12:59:02.509  5549  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,11-28 12:59:02.509  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:02.509  5549  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-28 12:59:02.509  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:02.509  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:02.509  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:02.510  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:02.510  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-28 12:59:02.511  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.511  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.511  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.511  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.511  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.511  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-28 12:59:02.511  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-28 12:59:02.512  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.513  5549  5597 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-28 12:59:02.513  5549  5597 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 12:59:02.513  4715  4715 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32257]" dev="sockfs" ino=32257 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 12:59:02.513  4715  4715 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32257]" dev="sockfs" ino=32257 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 12:59:02.516  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.516  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.516  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.516  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:02.516  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.516  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:59:02.516  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.517  5549  5596 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-28 12:59:02.518  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:02.518  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:02.518  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-28 12:59:02.518  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:02.518  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:02.518  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.518  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:59:02.519  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.519  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.519  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.519  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.521  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.521  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.521  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.521  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:02.521  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.522  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.522  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.523  5549  5596 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-28 12:59:02.523  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:02.523  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-28 12:59:02.523  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:02.523  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:02.523  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:02.524  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.524  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:59:02.524  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.524  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.524  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.524  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.525  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.525  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.526  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.526  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:02.526  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.526  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.526  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.526  5549  5596 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,11-28 12:59:02.527  5549  5596 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-28 12:59:02.527  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 12:59:02.527  5549  5596 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-28 12:59:02.527  5549  5596 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 12:59:02.527  5549  5596 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-28 12:59:02.527  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-28 12:59:02.527  5549  5596 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-28 12:59:02.527  5549  5596 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 12:59:02.527  5549  5596 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 12:59:02.527  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 12:59:02.527  5549  5596 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-28 12:59:02.527  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:02.527  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:02.527  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-28 12:59:02.528  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:02.528  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:02.528  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.528  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.528  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.528  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:02.528  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.528  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:02.529  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.529  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.529  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:02.530  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:02.530  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:02.530  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.530  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.530  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:02.530  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 12:59:02.530  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:02.530  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:02.531  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:02.531  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 12:59:02.805   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:03.806   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:04.807   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 12:59:07.531  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.532  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:07.532  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 12:59:07.532  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:07.532  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
,11-28 12:59:07.533  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:07.533  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-28 12:59:07.533  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:07.533  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 12:59:07.533  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:07.534  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
,11-28 12:59:07.534  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.534  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:07.534  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:07.534  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:07.535  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.538  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:07.538  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:07.539  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.539  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:07.539  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-28 12:59:07.539  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.539  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:07.544  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-28 12:59:07.545  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:59:07.545  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-28 12:59:07.550  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 12:59:07.551  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 12:59:07.551  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-28 12:59:07.551  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 12:59:07.551  5549  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 12:59:07.552  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-28 12:59:07.552  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 12:59:07.552  5549  5549 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 12:59:07.552  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:07.552  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 12:59:07.553  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-28 12:59:07.553  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 12:59:07.553  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 12:59:07.553  5549  5599 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 12:59:07.553  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-28 12:59:07.553  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 12:59:07.554  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:07.554  5549  5549 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 12:59:07.550  4517  4517 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33880]" dev="sockfs" ino=33880 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 12:59:07.554  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.554  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 12:59:07.554  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.554  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 12:59:07.554  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-28 12:59:07.554  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.556  5549  5599 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 12:59:07.556  5549  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 12:59:07.556  5549  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-28 12:59:07.550  4517  4517 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33880]" dev="sockfs" ino=33880 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 12:59:07.556  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.557  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:59:07.557  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.557  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.557  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:07.557  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:59:07.557  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:07.557  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-28 12:59:07.557  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:07.557  5549  5549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 12:59:07.557  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:07.557  5549  5549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:07.557  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:07.557  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:59:07.557  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 12:59:07.558  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:07.558  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.558  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:07.558  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:07.558  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.558  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.559  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:07.560  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.560  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.560  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:07.560  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:07.560  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.560  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:07.561  5549  5596 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-28 12:59:07.561  5549  5596 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 12:59:07.562  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 12:59:07.562  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 12:59:07.562  5549  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 12:59:07.562  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:07.562  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:07.562  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:07.562  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:07.562  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:07.562  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:07.562  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.563  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:07.563  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:07.563  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.563  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.564  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.565  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.565  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.565  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:07.565  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-28 12:59:07.565  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.565  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:07.572  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 12:59:07.572  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:07.572  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:07.572  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:07.572  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:07.572  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:07.572  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.572  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
,11-28 12:59:07.572  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:07.572  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.572  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.573  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.574  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.574  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.574  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:07.574  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:07.574  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.574  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:07.575  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:07.576  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:07.576  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:07.576  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:07.576  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:07.576  5549  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b8d10c not in the list
11-28 12:59:07.576  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.576  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:07.576  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:07.576  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.576  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.577  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.578  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:07.578  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:07.578  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:07.578  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:07.578  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:07.578  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaada55 not in the list
11-28 12:59:07.579  5549  5596 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-28 12:59:07.579  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 12:59:07.579  5549  5596 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-28 12:59:07.579  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 12:59:07.579  5549  5596 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-28 12:59:07.580  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-28 12:59:07.582  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-28 12:59:07.582  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-28 12:59:07.582  5549  5596 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-28 12:59:07.582  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 12:59:07.583  5549  5596 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-28 12:59:07.583  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 12:59:07.583  5549  5596 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-28 12:59:07.583  5549  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-28 12:59:07.583  5549  5596 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-28 12:59:07.583  5549  5596 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-28 12:59:07.583  5549  5596 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-28 12:59:07.583  5549  5596 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-28 12:59:07.584  5549  5596 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-28 12:59:07.584  5549  5596 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-28 12:59:07.584  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:07.584  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@82f641a added. We now have 3 listener(s)
11-28 12:59:07.584  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:07.587  5549  5596 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 12:59:07.587   931  3747 D WifiService: setWifiEnabled: true pid=5549, uid=10077
11-28 12:59:07.587   931  3747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 12:59:07.644  4504  4708 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-28 12:59:07.644  4504  4713 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-28 12:59:07.644  5549  5597 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-28 12:59:07.644  5549  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-28 12:59:07.644  5549  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-28 12:59:08.057  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 12:59:11.581   931  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 12:59:12.593  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 12:59:12.594  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c9bb4b added. We now have 4 listener(s)
11-28 12:59:12.594  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:12.608  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:59:12.608  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c9bb4b removed from the list
,11-28 12:59:12.609  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 12:59:12.610  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 12:59:12.611  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df7c928 added. We now have 4 listener(s)
,11-28 12:59:12.611  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:12.616  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:59:12.616  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df7c928 removed from the list
11-28 12:59:12.617  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 12:59:12.618  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:12.619  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ebb0641 added. We now have 4 listener(s)
11-28 12:59:12.619  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:12.625   931  3747 D WifiService: setWifiEnabled: false pid=5549, uid=10077
,11-28 12:59:12.625   931  3747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 12:59:12.632   931  2890 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-28 12:59:12.633   931  2890 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-28 12:59:12.633   931  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 12:59:12.633   931  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 12:59:12.640  4504  4561 D BluetoothAdapterState: Current state: ON, message: 23
11-28 12:59:12.640  4504  4561 D BluetoothAdapterProperties: Setting state to 13
11-28 12:59:12.640  4504  4561 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-28 12:59:12.641  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:59:12.642  4504  4561 D BluetoothAdapterProperties: onBluetoothDisable()
11-28 12:59:12.641  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-28 12:59:12.644  4504  4561 I BluetoothAdapterState: Entering PendingCommandState
,11-28 12:59:12.647  4504  4565 D BluetoothAdapterProperties: Scan Mode:20
,11-28 12:59:12.650  4504  4561 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-28 12:59:12.651  4504  4504 D BluetoothMapService: onReceive
11-28 12:59:12.651  4504  4504 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 12:59:12.651  4504  4504 D BluetoothMapService: STATE_TURNING_OFF
11-28 12:59:12.652  4504  4504 D BluetoothMapService: MAP Service closeService in
11-28 12:59:12.652  4504  4504 D BluetoothMapMasInstance0: MAP Service shutdown
11-28 12:59:12.652  4504  4504 D ObexServerSockets0: shutdown(block = true)
11-28 12:59:12.653  4504  4504 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 12:59:12.653  4504  4504 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 12:59:12.653  4504  4713 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-28 12:59:12.653  4504  4726 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-28 12:59:12.653  4504  4725 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-28 12:59:12.655  4504  4504 I BtOppRfcommListener: stopping Accept Thread
11-28 12:59:12.655   931  5294 D DhcpClient: Clearing IP address
11-28 12:59:12.655  4504  5206 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-28 12:59:12.656   511   928 D CommandListener: Clearing all IP addresses on wlan0
11-28 12:59:12.657  4504  5206 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-28 12:59:12.664   511   928 D CommandListener: Setting iface cfg
11-28 12:59:12.667  3501  5351 V NativeCrypto: Read error: ssl=0x7f74905700: I/O error during system call, Connection timed out
,11-28 12:59:12.669  3501  5351 V NativeCrypto: SSL shutdown failed: ssl=0x7f74905700: I/O error during system call, Broken pipe
,11-28 12:59:12.670   931  5295 D DhcpClient: Receive thread stopped
11-28 12:59:12.671   931  3747 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-28 12:59:12.671   931  5292 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-28 12:59:12.676   931  5292 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-28 12:59:12.676   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-28 12:59:12.677   931  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-28 12:59:12.678   931  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-28 12:59:12.685   931   944 I ActivityManager: Start proc 5603:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-28 12:59:12.690   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-28 12:59:12.691   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-28 12:59:12.693  4504  4504 D HeadsetService: Received stop request...Stopping profile...
11-28 12:59:12.694   537   537 E Parcel  : Reading a NULL string not supported here.
11-28 12:59:12.697  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 12:59:12.697  5549  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 12:59:12.697  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:12.697  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:12.697  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:59:12.697  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 12:59:12.697  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:12.697  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-28 12:59:12.697  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 12:59:12.697  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 12:59:12.697  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:12.697  5549  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-28 12:59:12.698  5549  5596 D io.jxcore.node.ConnectivityMonitor: start: OK
11-28 12:59:12.700   931  2892 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-28 12:59:12.701  3035  3048 D BluetoothHeadset: Proxy object disconnected
11-28 12:59:12.702  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:12.702  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:12.702  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:12.702  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:12.702  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:59:12.702  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 12:59:12.702  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:12.702  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 12:59:12.702  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 12:59:12.702  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 12:59:12.701  4504  4504 D A2dpService: Received stop request...Stopping profile...
,11-28 12:59:12.703  4504  4718 D A2dpStateMachine: Exit Disconnected: -1
,11-28 12:59:12.703   931   931 D BluetoothHeadset: Proxy object disconnected
11-28 12:59:12.703  3035  3035 D HeadsetProfile: Bluetooth service disconnected
,11-28 12:59:12.703  3707  3727 D BluetoothHeadset: Proxy object disconnected
11-28 12:59:12.704   931   931 D BluetoothHeadset: Proxy object disconnected
11-28 12:59:12.704   931   931 D BluetoothHeadset: Proxy object disconnected
11-28 12:59:12.704  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:12.704  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-28 12:59:12.705   931   931 D BluetoothA2dp: Proxy object disconnected
,11-28 12:59:12.706  3035  3035 D BluetoothA2dp: Proxy object disconnected
11-28 12:59:12.706  3670  3832 W QCNEJ   : |CORE| network lost: 100
11-28 12:59:12.707   931  2890 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-28 12:59:12.707  3670  3832 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-28 12:59:12.707   931   931 D RttService: SCAN_AVAILABLE : 1
11-28 12:59:12.707   931  3000 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 12:59:12.708  4504  4504 D HidService: Received stop request...Stopping profile...
11-28 12:59:12.708  4504  4504 D HidService: Stopping Bluetooth HidService
11-28 12:59:12.708  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:12.709  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:12.709  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:12.709  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:12.709  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:59:12.709  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 12:59:12.709  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:12.709  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 12:59:12.709  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 12:59:12.709  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-28 12:59:12.710  4504  4504 D HealthService: Received stop request...Stopping profile...
,11-28 12:59:12.714  4504  4504 D PanService: Received stop request...Stopping profile...
,11-28 12:59:12.715  4504  4504 D BluetoothMapService: Received stop request...Stopping profile...
,11-28 12:59:12.716  4504  4504 D BluetoothMapService: stop()
11-28 12:59:12.716  4504  4504 D BluetoothMapAppObserver: deinitObservers()
11-28 12:59:12.717   931  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 12:59:12.717  4504  4504 D BluetoothMapAppObserver: removeReceiver()
11-28 12:59:12.718  3035  3035 D BluetoothInputDevice: Proxy object disconnected
,11-28 12:59:12.718  3035  3035 D HidProfile: Bluetooth service disconnected
11-28 12:59:12.718  3035  3035 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-28 12:59:12.718  3035  3035 D PanProfile: Bluetooth service disconnected
11-28 12:59:12.720  4504  4504 D SapService: Received stop request...Stopping profile...
11-28 12:59:12.720  4504  4504 V SapService: stop()
11-28 12:59:12.721  4504  4504 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:12.721  4504  4504 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:12.721  4504  4504 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:12.722  4504  4504 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:12.726  4504  4504 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-28 12:59:12.726  4504  4504 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-28 12:59:12.726  4504  4565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-28 12:59:12.726  4504  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:12.726  4504  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:12.726  4504  4504 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:12.726  4504  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:12.726  4504  4504 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:12.726  4504  4504 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:12.726  4504  4565 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-28 12:59:12.726  4504  4504 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:12.727  4504  4565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-28 12:59:12.728  4504  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:12.728  4504  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:12.728  4504  4708 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 12:59:12.728  4504  4708 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 12:59:12.728  4504  4708 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 12:59:12.728  4504  4708 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 12:59:12.728  4504  4504 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:12.731  4504  4504 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:12.731  4504  4504 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:12.731  4504  4504 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:12.731  4504  4504 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-28 12:59:12.731  4504  4504 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-28 12:59:12.732  4504  4565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-28 12:59:12.732  4504  4504 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:12.732  4504  4504 V BluetoothAdapterState: isTurningOn()=false
,11-28 12:59:12.732  4504  4504 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:12.732  4504  4504 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:12.732  4504  4504 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-28 12:59:12.732  4504  4504 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-28 12:59:12.733  4504  4504 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:12.733  4504  4504 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:12.733  4504  4504 V BluetoothAdapterState: isBleTurningOn()=false
,11-28 12:59:12.733  4504  4504 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:12.733  4504  4504 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-28 12:59:12.733  4504  4504 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-28 12:59:12.733  4504  4565 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-28 12:59:12.736  4504  4504 D BluetoothMapService: MAP Service closeService in
11-28 12:59:12.736  4504  4504 V BluetoothAdapterState: isTurningOff()=true
,11-28 12:59:12.736  4504  4504 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:12.736  4504  4504 V BluetoothAdapterState: isBleTurningOn()=false
,11-28 12:59:12.736  4504  4504 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:12.736  4504  4504 D BluetoothMapService: cleanup()
,11-28 12:59:12.736  4504  4504 D BluetoothMapService: MAP Service closeService in
11-28 12:59:12.736  4504  4504 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:12.736  4504  4504 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:12.736  4504  4504 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:12.736  4504  4504 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:12.737  4504  4561 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-28 12:59:12.737  4504  4561 D BluetoothAdapterProperties: Setting state to 15
11-28 12:59:12.737  4504  4561 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-28 12:59:12.738  5603  5603 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-28 12:59:12.738  3035  3840 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 12:59:12.738   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-28 12:59:12.739  3707  3733 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 12:59:12.739  3035  3048 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-28 12:59:12.740  3035  3054 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 12:59:12.740  3035  3900 D BluetoothPan: onBluetoothStateChange on: false
11-28 12:59:12.740   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 12:59:12.741   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-28 12:59:12.741  3035  3840 D BluetoothMap: onBluetoothStateChange: up=false
11-28 12:59:12.741  3035  3048 D BluetoothPbap: onBluetoothStateChange: up=false
,11-28 12:59:12.742  4504  4561 I BluetoothAdapterState: Entering BleOnState
11-28 12:59:12.743   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 12:59:12.746  4504  4561 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-28 12:59:12.746  4504  4561 D BluetoothAdapterProperties: Setting state to 16
11-28 12:59:12.746  4504  4561 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-28 12:59:12.747  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 12:59:12.748  4504  4561 D BluetoothAdapterProperties: onBleDisable
11-28 12:59:12.748   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-28 12:59:12.748  4504  4562 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-28 12:59:12.748  4504  4561 I BluetoothAdapterState: Entering PendingCommandState
11-28 12:59:12.749  5603  5603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 12:59:12.749  4504  4565 D BluetoothAdapterProperties: Scan Mode:20
11-28 12:59:12.751  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 12:59:12.752  4504  4708 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-28 12:59:12.752  4504  4708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:12.755   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@478ba68:true
11-28 12:59:12.756  3501  3501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 12:59:12.769   931  3703 I ActivityManager: Start proc 5624:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-28 12:59:12.772   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 12:59:12.773   511   928 D CommandListener: Clearing all IP addresses on wlan0
,11-28 12:59:12.773   931  2892 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-28 12:59:12.774   931  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-28 12:59:12.774   511   928 D TetherController: Setting IP forward enable = 0
,11-28 12:59:12.776   931   948 D Tethering: MasterInitialState.processMessage what=3
11-28 12:59:12.778  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 12:59:12.779  5194  5194 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ec61efc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-28 12:59:12.781   931  2890 D DhcpClient: doQuit
,11-28 12:59:12.785  4960  4984 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-28 12:59:12.786  4960  4984 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 12:59:12.786   931  2890 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-28 12:59:12.786  4960  4984 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-28 12:59:12.786  4960  4984 E SarControlService: no key has been found,reset the power
11-28 12:59:12.786   931  5294 D DhcpClient: onQuitting
11-28 12:59:12.786  4960  4997 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 12:59:12.786  4960  4997 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 12:59:12.786  4960  4997 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 12:59:12.787  3357  3357 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-28 12:59:12.787  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 12:59:12.787  4985  4985 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 12:59:12.788  4960  4997 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 12:59:12.788  4960  4997 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 12:59:12.788  4960  4997 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 12:59:12.789  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 12:59:12.789  4985  4985 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 12:59:12.791  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:12.791  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:12.791  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:12.791  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:12.791  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 12:59:12.791  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 12:59:12.791  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:12.791  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 12:59:12.791  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 12:59:12.791  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 12:59:12.792  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:12.792  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-28 12:59:12.792  4985  4999 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4247c2 HexData = [00000000ea03000000000000ffffffff]
11-28 12:59:12.792  4985  4999 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 12:59:12.792  4985  4999 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-28 12:59:12.792  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 12:59:12.793  4960  4970 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-28 12:59:12.805  4985  4999 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4247c2 HexData = [00000000eb03000000000000ffffffff]
,11-28 12:59:12.806  4985  4999 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 12:59:12.806  4985  4999 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-28 12:59:12.807  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 12:59:12.807  4960  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-28 12:59:12.819  3357  3357 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-28 12:59:12.823  5603  5603 D LocalBluetoothProfileManager: Adding local MAP profile
11-28 12:59:12.824  3357  3357 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-28 12:59:12.824  5603  5603 D BluetoothMap: Create BluetoothMap proxy object
11-28 12:59:12.826   511   921 W SocketClient: write error (Broken pipe)
11-28 12:59:12.827   511   921 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-28 12:59:12.827   511   921 W SocketListener: Error sending broadcast (Broken pipe)
,11-28 12:59:12.837   511   928 E Netd    : netlink response contains error (No such file or directory)
11-28 12:59:12.838   511   928 D TetherController: Setting IP forward enable = 0
,11-28 12:59:12.838   931  2892 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-28 12:59:12.838   931  2892 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-28 12:59:12.840  5624  5624 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
11-28 12:59:12.841  5603  5603 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-28 12:59:12.860  5603  5603 D DockEventReceiver: finishStartingService: stopping service
11-28 12:59:12.862   931  3113 I ActivityManager: Killing 4900:com.google.android.calendar/u0a36 (adj 15): empty #17
11-28 12:59:12.864  3357  3357 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-28 12:59:12.890  3357  3357 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-28 12:59:12.961  4504  4565 I bt_hci  : shut_down
,11-28 12:59:12.965  4504  4569 D bt_hwcfg: hw_epilog_process
,11-28 12:59:12.965  4504  4569 I bt_vendor: low_power_mode_cb
,11-28 12:59:12.968  4504  4569 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-28 12:59:12.968  4504  4569 I bt_vendor: epilog_cb
11-28 12:59:12.968  4504  4569 I bt_hci  : epilog_finished_callback
,11-28 12:59:12.971  4504  4565 I bt_hci_h4: hal_close
,11-28 12:59:12.971  4504  4565 I bt_userial_vendor: device fd = 54 close
,11-28 12:59:12.992   931  2890 D wifi    : In wifi stop Hal
,11-28 12:59:12.992  4935  4935 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 12:59:12.992   931  2890 D wifi    : halHandle = 0x7f5e58dcc0, mVM = 0x7f7abcd140, mCls = 0x100a02
11-28 12:59:12.992   931  3356 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-28 12:59:12.992   931  3356 D WifiHAL : Got a signal to exit!!!
11-28 12:59:12.992   931  3356 I WifiHAL : Exit wifi_event_loop
11-28 12:59:12.993   931  2890 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-28 12:59:12.993   931  2890 E WifiHAL : Event processing terminated
,11-28 12:59:12.993   931  2890 D wifi    : In wifi cleaned up handler
11-28 12:59:12.993   931  2890 I WifiHAL : Internal cleanup completed
11-28 12:59:12.995  3999  4140 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 12:59:12.995  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:59:13.017   931  3356 D wifi    : set interface wlan0 flags (DOWN)
,11-28 12:59:13.017   931  2890 D WifiNative-HAL: HAL event thread stopped successfully
,11-28 12:59:13.046  5624  5624 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 12:59:13.046  5624  5624 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 12:59:13.046  5624  5624 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 12:59:13.046  5624  5624 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.e.b(PG:170)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 12:59:13.046  5624  5624 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.k.d(PG:583)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.e.b(PG:170)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 12:59:13.046  5624  5624 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 12:59:13.046  5624  5624 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 12:59:13.046  5624  5624 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 12:59:13.046  5624  5624 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 12:59:13.055  5603  5603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 12:59:13.061  3501  3501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 12:59:13.061  5603  5603 D DockEventReceiver: finishStartingService: stopping service
11-28 12:59:13.063   931  3766 I ActivityManager: Killing 5325:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
11-28 12:59:13.085  4504  4562 D bt_stack_manager: event_shut_down_stack finished.
11-28 12:59:13.086  4504  4561 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-28 12:59:13.086  3767  3767 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 12:59:13.087  4504  4561 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-28 12:59:13.087  4504  4504 D BtGatt.DebugUtils: handleDebugAction() action=null
11-28 12:59:13.088  4504  4504 D BtGatt.GattService: Received stop request...Stopping profile...
11-28 12:59:13.088  4504  4504 D BtGatt.GattService: stop()
11-28 12:59:13.088  4504  4504 D BtGatt.AdvertiseManager: advertise clients cleared
11-28 12:59:13.090  3767  3767 D SystemUpdateService: onCreate
11-28 12:59:13.091  4504  4504 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:13.091  4504  4504 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:13.091  4504  4504 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:13.091  4504  4504 V BluetoothAdapterState: isBleTurningOff()=true
11-28 12:59:13.091  4504  4561 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-28 12:59:13.092  4504  4561 D BluetoothAdapterProperties: Setting state to 10
11-28 12:59:13.092  4504  4561 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-28 12:59:13.093   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-28 12:59:13.093  4504  4561 I BluetoothAdapterState: Entering OffState
11-28 12:59:13.098  4504  4504 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-28 12:59:13.099  4504  4504 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-28 12:59:13.099  4504  4504 I BluetoothServiceJni: cleanupNative: return from cleanup
11-28 12:59:13.100  4504  4562 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-28 12:59:13.107  3767  3767 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-28 12:59:13.112  4504  4562 D bt_stack_manager: event_clean_up_stack finished.
11-28 12:59:13.117  3767  3767 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-28 12:59:13.119  3767  5322 I iu.UploadsManager: num queued entries: 0
11-28 12:59:13.119  3767  5322 I iu.UploadsManager: num updated entries: 0
11-28 12:59:13.120  3767  5322 I iu.SyncManager: NEXT; no task
,11-28 12:59:13.127  3767  3767 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-28 12:59:13.129  3767  3767 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 12:59:13.129  4504  4504 I art     : System.exit called, status: 0
,11-28 12:59:13.129  4504  4504 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-28 12:59:13.141   931  3703 I ActivityManager: Start proc 5669:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-28 12:59:13.149  3767  5667 I SystemUpdateService: active receiver: enabled
,11-28 12:59:13.173  5669  5669 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-28 12:59:13.175  5669  5669 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 12:59:13.180   931  3123 I ActivityManager: Process com.android.bluetooth (pid 4504) has died
,11-28 12:59:13.185  5669  5669 D SprintDMHelper: simOperator: 
,11-28 12:59:13.185  5669  5669 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 12:59:13.197  4935  5682 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-28 12:59:13.210   931   942 I ActivityManager: Start proc 5683:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-28 12:59:13.214  3767  5667 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 12:59:13.220   931   948 D Tethering: InitialState.processMessage what=4
,11-28 12:59:13.220  3767  5667 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-28 12:59:13.221  3767  5667 I SystemUpdateService: now status is 0 (complete)
11-28 12:59:13.221  3767  5667 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-28 12:59:13.225   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-28 12:59:13.222  3767  5667 I SystemUpdateService: file has been verified
11-28 12:59:13.227  3767  5667 I SystemUpdateService: OTA package size = 21989297
,11-28 12:59:13.251  5683  5683 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-28 12:59:13.256  3767  5667 I SystemUpdateService: showing system update notification
,11-28 12:59:13.260   931   942 I ActivityManager: Killing 5194:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-28 12:59:13.297  3767  3767 D SystemUpdateService: onDestroy
,11-28 12:59:13.302   931  3332 I ActivityManager: Killing 4588:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-28 12:59:13.393  5624  5653 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-28 12:59:13.406   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eba9be5:true
,11-28 12:59:17.700   931  3071 D WifiService: setWifiEnabled: true pid=5549, uid=10077
,11-28 12:59:17.701   931  3071 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 12:59:17.708   511   928 D SoftapController: Softap fwReload - Ok
,11-28 12:59:17.714   511   928 D CommandListener: Setting iface cfg
,11-28 12:59:17.714   511   928 D CommandListener: Trying to bring down wlan0
,11-28 12:59:17.717   511   928 D CommandListener: Clearing all IP addresses on wlan0
,11-28 12:59:17.723   931  2890 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 12:59:18.302   931  2890 D wifi    : set interface wlan0 flags (UP)
,11-28 12:59:18.305   931  2890 I WifiHAL : Initializing wifi
11-28 12:59:18.305   931  2890 I WifiHAL : Creating socket
11-28 12:59:18.306   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-28 12:59:18.309   931  2890 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-28 12:59:18.309   931  2890 D wifi    : Did set static halHandle = 0x7f5e58dcc0
,11-28 12:59:18.309   931  2890 D wifi    : halHandle = 0x7f5e58dcc0, mVM = 0x7f7abcd140, mCls = 0x10190a
,11-28 12:59:18.310   931  2890 D wifi    : array field set
11-28 12:59:18.310   931  2890 I WifiNative-HAL: interface[0] = wlan0
,11-28 12:59:18.312   931  5702 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547043728576
,11-28 12:59:18.312   931  5702 D wifi    : waitForHalEvents called, vm = 0x7f7abcd140, obj = 0x10190a, env = 0x7f5e58b880
,11-28 12:59:18.377  5703  5703 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-28 12:59:18.391  5703  5703 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 12:59:18.415   931  2890 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-28 12:59:18.420  5703  5703 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-28 12:59:18.420  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:59:18.420  5703  5703 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-28 12:59:18.440  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 12:59:18.440  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:18.440  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:18.440  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:18.440  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:59:18.440  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 12:59:18.440  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:18.440  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 12:59:18.440  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 12:59:18.440  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-28 12:59:18.440  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:18.440  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 12:59:18.441   931  2890 D WifiConfigStore: Loading config and enabling all networks 
,11-28 12:59:18.454   931  2890 D WifiConfigStore: loaded 0 passpoint configs
,11-28 12:59:18.454   931  2890 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-28 12:59:18.455   931  2890 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-28 12:59:18.456   931  2890 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-28 12:59:18.458   931  2890 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-28 12:59:18.458   931  2890 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-28 12:59:18.458   931  2890 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-28 12:59:18.458   931  2890 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-28 12:59:18.462   931  2890 D WifiNative-HAL: Setting external_sim to 1
,11-28 12:59:18.462  4935  4935 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 12:59:18.462   931  2890 D wifi    : setting dfs flag to true, 0x7f62272300
11-28 12:59:18.463   931  2890 D WifiStateMachine: Setting OUI to DA-A1-19
,11-28 12:59:18.463   931  2890 D wifi    : setting scan oui 0x7f62272300
11-28 12:59:18.463   931  2890 D WifiHAL : Sending mac address OUI
,11-28 12:59:18.467   931  2890 E native  : do suspend false
,11-28 12:59:18.474   931  2890 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-28 12:59:18.474   931   931 D RttService: SCAN_AVAILABLE : 3
11-28 12:59:18.474   931  3000 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-28 12:59:18.474   511   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-28 12:59:18.475   511   928 D CommandListener: Setting iface cfg
,11-28 12:59:18.479   931  2869 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-28 12:59:18.479   931  2869 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-28 12:59:18.487   931  2869 D WifiNative-HAL: p2pGetDeviceAddress
,11-28 12:59:18.487   931  2869 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-28 12:59:18.493   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=208851 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-28 12:59:21.654  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 12:59:21.660  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 12:59:21.667  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 12:59:21.670  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 12:59:21.721   931  2890 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-28 12:59:21.722   931  2890 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-28 12:59:21.722   931  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 12:59:21.734   931  2890 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-28 12:59:21.764   931  2890 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-28 12:59:21.767  5703  5703 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-28 12:59:22.189  5703  5703 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-28 12:59:22.227  5703  5703 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-28 12:59:22.228  5703  5703 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-28 12:59:22.236   931  2890 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-28 12:59:22.236   931  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 12:59:22.236   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-28 12:59:22.251   931  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 12:59:22.264   511   928 D CommandListener: Setting iface cfg
,11-28 12:59:22.270   931  2890 D WifiStateMachine: Start Dhcp Watchdog 2
,11-28 12:59:22.276   931  5709 D DhcpClient: Receive thread started
,11-28 12:59:22.280   931  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 12:59:22.280   931  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-28 12:59:22.280   931  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-28 12:59:22.360   931  2890 E native  : do suspend false
,11-28 12:59:22.375   931  5708 D DhcpClient: Broadcasting DHCPDISCOVER
,11-28 12:59:22.389   931  5709 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172629, domain null
,11-28 12:59:22.389   931  5708 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172629 seconds
,11-28 12:59:22.391   931  5708 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-28 12:59:22.409   931  5709 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-28 12:59:22.409   931  5708 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-28 12:59:22.411   511   928 D CommandListener: Setting iface cfg
11-28 12:59:22.416   931  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-28 12:59:22.422   931  5708 D DhcpClient: Scheduling renewal in 86399s
,11-28 12:59:22.432   931  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-28 12:59:22.434   931  2890 D WifiConfigStore: No blacklist allowed without epno enabled
,11-28 12:59:22.435   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-28 12:59:22.437   931  2892 D ConnectivityService: Adding iface wlan0 to network 101
11-28 12:59:22.446   931  2890 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-28 12:59:22.491   931  2892 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-28 12:59:22.491   931  2892 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-28 12:59:22.493   931  2892 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-28 12:59:22.494   931  2892 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
11-28 12:59:22.496   931  2892 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-28 12:59:22.504   931  2892 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 12:59:22.510   931  2892 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-28 12:59:22.510   931  2892 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-28 12:59:22.510   931  2892 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-28 12:59:22.510   931  2890 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-28 12:59:22.510   931  2892 D ConnectivityService:    accepting network in place of null
11-28 12:59:22.510   931  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 12:59:22.511   931  2892 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 12:59:22.527   931  5707 D NetlinkSocketObserver: NeighborEvent{elapsedMs=212885, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 12:59:22.533   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 12:59:22.555   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 12:59:22.558   931  2892 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-28 12:59:22.558   931  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-28 12:59:22.558  3670  3832 W QCNEJ   : |CORE| network available: 101
11-28 12:59:22.559   931  2892 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-28 12:59:22.561   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-28 12:59:22.562  3670  3832 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-28 12:59:22.563  3670  3832 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-28 12:59:22.563  3670  3832 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-28 12:59:22.567  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:22.567  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:22.567  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:22.567  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:22.567  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:59:22.567  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 12:59:22.567  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 12:59:22.567  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 12:59:22.567  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 12:59:22.567  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 12:59:22.567  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:22.567  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 12:59:22.573  4960  4984 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-28 12:59:22.573  4960  4984 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 12:59:22.573  4960  4984 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,11-28 12:59:22.573  4960  4984 E SarControlService: no key has been found,reset the power
11-28 12:59:22.573  4960  4997 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 12:59:22.573  4960  4997 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-28 12:59:22.574  4960  4997 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-28 12:59:22.574  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 12:59:22.574  4985  4985 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 12:59:22.575  4960  4997 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 12:59:22.576  4960  4997 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 12:59:22.576  4960  4997 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 12:59:22.576  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 12:59:22.576  4985  4985 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-28 12:59:22.578  3767  3767 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-28 12:59:22.582  4985  4999 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4247c2 HexData = [00000000ec03000000000000ffffffff]
,11-28 12:59:22.582  4985  4999 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 12:59:22.582  4985  4999 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-28 12:59:22.582  4985  4999 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4247c2 HexData = [00000000ed03000000000000ffffffff]
11-28 12:59:22.582  4985  4999 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 12:59:22.582  4985  4999 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-28 12:59:22.583  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 12:59:22.583  4960  4970 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 12:59:22.584  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 12:59:22.584  4960  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-28 12:59:22.585  3767  3767 D SystemUpdateService: onCreate
11-28 12:59:22.588  3767  3767 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-28 12:59:22.593   931  5706 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-28 12:59:22.599  3767  3767 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-28 12:59:22.604  3767  5322 I iu.UploadsManager: num queued entries: 0
,11-28 12:59:22.604  3767  5322 I iu.UploadsManager: num updated entries: 0
11-28 12:59:22.605  3767  5322 I iu.SyncManager: NEXT; no task
,11-28 12:59:22.607  3767  5719 I SystemUpdateService: active receiver: enabled
,11-28 12:59:22.608  3767  3767 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-28 12:59:22.610  3767  3767 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 12:59:22.611  5669  5669 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 12:59:22.615  5669  5669 D SprintDMHelper: simOperator: 
11-28 12:59:22.615  5669  5669 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 12:59:22.636  3767  5719 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 12:59:22.648  3767  5719 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-28 12:59:22.648  3767  5719 I SystemUpdateService: now status is 0 (complete)
11-28 12:59:22.648  3767  5719 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 12:59:22.649  3767  5719 I SystemUpdateService: file has been verified
,11-28 12:59:22.649  3767  5719 I SystemUpdateService: OTA package size = 21989297
,11-28 12:59:22.651   931  5706 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 28 Nov 2016 17:59:22 GMT], X-Android-Received-Millis=[1480355962650], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480355962620]}
,11-28 12:59:22.651   931  2892 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-28 12:59:22.652   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-28 12:59:22.652   931  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 12:59:22.653   931  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-28 12:59:22.654  3767  5719 I SystemUpdateService: showing system update notification
,11-28 12:59:22.663  3767  3767 D SystemUpdateService: onDestroy
,11-28 12:59:22.705   931  3766 D WifiService: setWifiEnabled: false pid=5549, uid=10077
11-28 12:59:22.705   931  3766 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 12:59:22.707   931  2890 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-28 12:59:22.707   931  2890 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-28 12:59:22.707   931  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 12:59:22.707   931  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 12:59:22.716   931  5708 D DhcpClient: Clearing IP address
11-28 12:59:22.717   511   928 D CommandListener: Clearing all IP addresses on wlan0
,11-28 12:59:22.718   511   928 D CommandListener: Setting iface cfg
11-28 12:59:22.718  4935  5723 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,11-28 12:59:22.722  3501  5720 V NativeCrypto: SSL handshake aborted: ssl=0x7f74905700: I/O error during system call, Connection timed out
,11-28 12:59:22.726   931  3071 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-28 12:59:22.726   931  5706 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-28 12:59:22.728   931  5709 D DhcpClient: Receive thread stopped
11-28 12:59:22.727   931  5706 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-28 12:59:22.729  4935  5723 W Babel_NetworkC,onnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
11-28 12:59:22.729  4935  5723 W Babel_NetworkConnectionCheckingService: 	... 21 more
11-28 12:59:22.729  4935  5723 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-28 12:59:22.731   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-28 12:59:22.732   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-28 12:59:22.733   537   537 E Parcel  : Reading a NULL string not supported here.
11-28 12:59:22.735   931   931 D RttService: SCAN_AVAILABLE : 1
11-28 12:59:22.736   931  3000 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-28 12:59:22.738   931  5706 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-28 12:59:22.739   931  2892 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-28 12:59:22.739   931  2890 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-28 12:59:22.740  3670  3832 W QCNEJ   : |CORE| network lost: 101
11-28 12:59:22.741  3670  3832 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-28 12:59:22.743   931  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-28 12:59:22.761   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 12:59:22.783   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 12:59:22.783   931  2892 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-28 12:59:22.784   931  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-28 12:59:22.784   511   928 D CommandListener: Clearing all IP addresses on wlan0
,11-28 12:59:22.785   931   948 D Tethering: MasterInitialState.processMessage what=3
11-28 12:59:22.787  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:22.787  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:22.787  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:22.787  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:22.787  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:59:22.787  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 12:59:22.787  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:22.787  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 12:59:22.787  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 12:59:22.787  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-28 12:59:22.787  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 12:59:22.787  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-28 12:59:22.794  3767  3767 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 12:59:22.796  4960  4984 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-28 12:59:22.796  4960  4984 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 12:59:22.796  4960  4984 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-28 12:59:22.796  4960  4984 E SarControlService: no key has been found,reset the power
11-28 12:59:22.796  4960  4997 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 12:59:22.796  4960  4997 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 12:59:22.797  4960  4997 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 12:59:22.797  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 12:59:22.797  4985  4985 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 12:59:22.799  4960  4997 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 12:59:22.799  4960  4997 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 12:59:22.799  4960  4997 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 12:59:22.799  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 12:59:22.800  4985  4985 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-28 12:59:22.803  3767  3767 D SystemUpdateService: onCreate
11-28 12:59:22.804  4985  4999 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4247c2 HexData = [00000000ee03000000000000ffffffff]
11-28 12:59:22.804  4985  4999 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 12:59:22.804  4985  4999 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-28 12:59:22.804  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 12:59:22.805  4960  4971 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 12:59:22.805  4985  4999 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4247c2 HexData = [00000000ef03000000000000ffffffff]
11-28 12:59:22.805  4985  4999 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 12:59:22.805  4985  4999 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-28 12:59:22.806  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 12:59:22.806  4960  4970 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-28 12:59:22.809  3767  3767 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-28 12:59:22.813  3767  5738 I SystemUpdateService: active receiver: enabled
,11-28 12:59:22.817  3767  3767 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-28 12:59:22.824  3767  5738 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 12:59:22.825  3767  3767 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-28 12:59:22.826  3767  3767 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 12:59:22.828  5669  5669 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 12:59:22.832  5669  5669 D SprintDMHelper: simOperator: 
11-28 12:59:22.832  5669  5669 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 12:59:22.840   511   928 E Netd    : netlink response contains error (No such file or directory)
,11-28 12:59:22.841   931  2892 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-28 12:59:22.842   931  2890 D DhcpClient: doQuit
,11-28 12:59:22.842   931  2890 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 12:59:22.843   931  5708 D DhcpClient: onQuitting
,11-28 12:59:22.843  3767  5322 I iu.UploadsManager: num queued entries: 0
11-28 12:59:22.843  5703  5703 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-28 12:59:22.843  3767  5322 I iu.UploadsManager: num updated entries: 0
11-28 12:59:22.844  3767  5322 I iu.SyncManager: NEXT; no task
11-28 12:59:22.845  4935  5742 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-28 12:59:22.846  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:22.846  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:22.846  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:22.846  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:22.846  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 12:59:22.846  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 12:59:22.846  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:22.846  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 12:59:22.846  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 12:59:22.846  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-28 12:59:22.846  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 12:59:22.846  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 12:59:22.852  3767  5738 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-28 12:59:22.852  3767  5738 I SystemUpdateService: now status is 0 (complete)
11-28 12:59:22.852  3767  5738 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 12:59:22.853  3767  5738 I SystemUpdateService: file has been verified
11-28 12:59:22.853  3767  5738 I SystemUpdateService: OTA package size = 21989297
,11-28 12:59:22.857  5703  5703 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-28 12:59:22.859  5703  5703 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-28 12:59:22.863  3767  5738 I SystemUpdateService: showing system update notification
,11-28 12:59:22.873  3767  3767 D SystemUpdateService: onDestroy
,11-28 12:59:22.892  5703  5703 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-28 12:59:22.905  5703  5703 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-28 12:59:23.012   931  2890 D wifi    : In wifi stop Hal
,11-28 12:59:23.012   931  2890 D wifi    : halHandle = 0x7f5e58dcc0, mVM = 0x7f7abcd140, mCls = 0x10190a
,11-28 12:59:23.012   931  5702 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-28 12:59:23.012   931  5702 D WifiHAL : Got a signal to exit!!!
11-28 12:59:23.012   931  5702 I WifiHAL : Exit wifi_event_loop
11-28 12:59:23.013   931  2890 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-28 12:59:23.013   931  2890 E WifiHAL : Event processing terminated
,11-28 12:59:23.013   931  2890 D wifi    : In wifi cleaned up handler
11-28 12:59:23.013   931  2890 I WifiHAL : Internal cleanup completed
11-28 12:59:23.014  4935  4935 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 12:59:23.015  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 12:59:23.016  3999  4140 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 12:59:23.036   931  5702 D wifi    : set interface wlan0 flags (DOWN)
11-28 12:59:23.036   931  2890 D WifiNative-HAL: HAL event thread stopped successfully
,11-28 12:59:23.243   931   948 D Tethering: InitialState.processMessage what=4
,11-28 12:59:23.249   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-28 12:59:23.558   931  2892 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-28 12:59:27.744   931   948 I ActivityManager: Start proc 5744:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-28 12:59:27.838  5744  5744 D AdapterServiceConfig: Adding HeadsetService
,11-28 12:59:27.838  5744  5744 D AdapterServiceConfig: Adding A2dpService
11-28 12:59:27.838  5744  5744 D AdapterServiceConfig: Adding HidService
,11-28 12:59:27.839  5744  5744 D AdapterServiceConfig: Adding HealthService
,11-28 12:59:27.839  5744  5744 D AdapterServiceConfig: Adding PanService
11-28 12:59:27.839  5744  5744 D AdapterServiceConfig: Adding GattService
,11-28 12:59:27.839  5744  5744 D AdapterServiceConfig: Adding BluetoothMapService
11-28 12:59:27.839  5744  5744 D AdapterServiceConfig: Adding SapService
,11-28 12:59:27.851   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@878b9a0:true
,11-28 12:59:27.852  5744  5744 D BluetoothAdapterState: make() - Creating AdapterState
,11-28 12:59:27.855  5744  5744 I bt_bluedroid: init
,11-28 12:59:27.856  5744  5756 I BluetoothAdapterState: Entering OffState
,11-28 12:59:27.858  5744  5757 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-28 12:59:27.858  5744  5757 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-28 12:59:27.858  5744  5757 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-28 12:59:27.858  5744  5757 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-28 12:59:27.859  5744  5744 I bt_bluedroid: get_profile_interface socket
,11-28 12:59:27.860  5744  5744 I bt_bluedroid: get_profile_interface sdp
11-28 12:59:27.861  5744  5760 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-28 12:59:27.865  5744  5760 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 12:59:27.865  5744  5755 I bt_bluedroid: config_hci_snoop_log
,11-28 12:59:27.867   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-28 12:59:27.870  5744  5756 D BluetoothAdapterState: Current state: OFF, message: 0
11-28 12:59:27.870  5744  5756 D BluetoothAdapterProperties: Setting state to 14
,11-28 12:59:27.870  5744  5756 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-28 12:59:27.873  5744  5756 D BluetoothBondStateMachine: make
,11-28 12:59:27.874  5744  5761 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-28 12:59:27.877  5744  5756 I BluetoothAdapterState: Entering PendingCommandState
,11-28 12:59:27.878  5744  5744 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-28 12:59:27.881  5744  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:27.882  5744  5744 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-28 12:59:27.883  5744  5744 D BtGatt.GattService: Received start request. Starting profile...
,11-28 12:59:27.883  5744  5744 D BtGatt.GattService: start()
11-28 12:59:27.883  5744  5744 I bt_bluedroid: get_profile_interface gatt
,11-28 12:59:27.884  5744  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:27.884  5744  5744 D BtGatt.AdvertiseManager: advertise manager created
,11-28 12:59:27.890  5744  5744 V BluetoothAdapterState: isTurningOff()=false
,11-28 12:59:27.890  5744  5744 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:27.890  5744  5744 V BluetoothAdapterState: isBleTurningOn()=true
11-28 12:59:27.890  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:27.891  5744  5756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-28 12:59:27.892  5744  5756 I bt_bluedroid: bt_bluedroid
,11-28 12:59:27.892  5744  5757 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-28 12:59:27.893  5744  5757 I bt_hci  : start_up
,11-28 12:59:27.898  5744  5757 I bt_vendor: alloc value 0xf3ca6871
,11-28 12:59:27.898  5744  5757 I bt_vendor: init
11-28 12:59:27.898  5744  5757 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-28 12:59:27.898  5744  5757 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-28 12:59:28.009  5744  5757 D bt_hci  : start_up starting async portion
,11-28 12:59:28.009  5744  5764 I bt_hci  : event_finish_startup
11-28 12:59:28.009  5744  5764 I bt_hci_h4: hal_open
11-28 12:59:28.010  5744  5764 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-28 12:59:28.007  5765  5765 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 12:59:28.027  5744  5764 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 12:59:28.029  5744  5764 D bt_hwcfg: Chipset BCM4358A3
,11-28 12:59:28.030  5744  5764 D bt_hwcfg: Target name = [BCM4358A3]
,11-28 12:59:28.030  5744  5764 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-28 12:59:28.426  5744  5764 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-28 12:59:28.427  5744  5764 D bt_hwcfg: Settlement delay -- 100 ms
,11-28 12:59:28.427  5744  5764 I bt_hwcfg: Setting fw settlement delay to 100 
,11-28 12:59:28.561  5744  5764 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 12:59:28.561  5744  5764 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-28 12:59:28.563  5744  5764 I bt_hwcfg: vendor lib fwcfg completed
11-28 12:59:28.563  5744  5764 I bt_vendor: firmware callback
11-28 12:59:28.563  5744  5764 I bt_hci  : firmware_config_callback
,11-28 12:59:28.571  5744  5767 I bt_btu  : btu_task pending for preload complete event
,11-28 12:59:28.572  5744  5767 I bt_btu_task: Bluetooth chip preload is complete
,11-28 12:59:28.572  5744  5767 I bt_btu  : btu_task received preload complete event
,11-28 12:59:28.580  5744  5767 I         : BTE_InitTraceLevels -- TRC_HCI
,11-28 12:59:28.580  5744  5767 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-28 12:59:28.580  5744  5767 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-28 12:59:28.580  5744  5767 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-28 12:59:28.580  5744  5767 I         : BTE_InitTraceLevels -- TRC_AVRC
11-28 12:59:28.581  5744  5767 I         : BTE_InitTraceLevels -- TRC_A2D
11-28 12:59:28.581  5744  5767 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-28 12:59:28.581  5744  5767 I         : BTE_InitTraceLevels -- TRC_BTM
,11-28 12:59:28.581  5744  5767 I         : BTE_InitTraceLevels -- TRC_GAP
,11-28 12:59:28.581  5744  5767 I         : BTE_InitTraceLevels -- TRC_PAN
11-28 12:59:28.581  5744  5767 I         : BTE_InitTraceLevels -- TRC_SDP
11-28 12:59:28.581  5744  5767 I         : BTE_InitTraceLevels -- TRC_GATT
11-28 12:59:28.582  5744  5767 I         : BTE_InitTraceLevels -- TRC_SMP
,11-28 12:59:28.583  5744  5767 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-28 12:59:28.583  5744  5767 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-28 12:59:28.664  5744  5767 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c24549
11-28 12:59:28.664  5744  5767 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c24549 
,11-28 12:59:28.687  5744  5760 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-28 12:59:28.688  5744  5760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-28 12:59:28.688  5744  5760 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-28 12:59:28.690  5744  5760 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 12:59:28.692  5744  5760 D BluetoothAdapterProperties: Scan Mode:20
11-28 12:59:28.693  5744  5760 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 12:59:28.693  5744  5760 D bt_hci  : do_postload posting postload work item
11-28 12:59:28.693  5744  5764 I bt_hci  : event_postload
11-28 12:59:28.693  5744  5764 I bt_vendor: sco_config_cb
,11-28 12:59:28.693  5744  5764 I bt_hci  : sco_config_callback postload finished.
,11-28 12:59:28.697  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:59:28.700  5744  5760 D bt_bte_conf: Device ID record 1 : primary
,11-28 12:59:28.700  5744  5760 D bt_bte_conf:   vendorId            = 000f
11-28 12:59:28.700  5744  5760 D bt_bte_conf:   vendorIdSource      = 0001
11-28 12:59:28.700  5744  5760 D bt_bte_conf:   product             = 1200
11-28 12:59:28.700  5744  5760 D bt_bte_conf:   version             = 1436
11-28 12:59:28.700  5744  5760 D bt_bte_conf:   clientExecutableURL = 
11-28 12:59:28.700  5744  5760 D bt_bte_conf:   serviceDescription  = 
11-28 12:59:28.700  5744  5760 D bt_bte_conf:   documentationURL    = 
11-28 12:59:28.700  5744  5764 I bt_vendor: low_power_mode_cb
11-28 12:59:28.700  5744  5760 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-28 12:59:28.701  5744  5757 D bt_stack_manager: event_start_up_stack finished
11-28 12:59:28.701  5744  5756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-28 12:59:28.702  5744  5756 D BluetoothAdapterProperties: Setting state to 15
,11-28 12:59:28.702  5744  5756 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-28 12:59:28.704  5744  5756 I BluetoothAdapterState: Entering BleOnState
,11-28 12:59:28.707  5744  5756 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-28 12:59:28.707  5744  5756 D BluetoothAdapterProperties: Setting state to 11
11-28 12:59:28.707  5744  5756 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-28 12:59:28.711  5744  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:28.712  5744  5744 D HeadsetService: Received start request. Starting profile...
,11-28 12:59:28.714  5744  5744 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-28 12:59:28.714  5744  5744 D HeadsetStateMachine: make
11-28 12:59:28.718  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 12:59:28.721  5744  5756 I BluetoothAdapterState: Entering PendingCommandState
,11-28 12:59:28.725  5744  5744 D HeadsetStateMachine: max_hf_connections = 1
11-28 12:59:28.726  5744  5744 I bt_bluedroid: get_profile_interface handsfree
,11-28 12:59:28.726  5744  5760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-28 12:59:28.726  5744  5760 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-28 12:59:28.729  5744  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:28.730  5744  5744 D A2dpService: Received start request. Starting profile...
,11-28 12:59:28.730  5744  5744 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-28 12:59:28.731  5744  5744 I bt_bluedroid: get_profile_interface avrcp
,11-28 12:59:28.736  5744  5744 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-28 12:59:28.736  5744  5744 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-28 12:59:28.736  5744  5744 D A2dpStateMachine: make
,11-28 12:59:28.737  5744  5744 I bt_bluedroid: get_profile_interface a2dp
11-28 12:59:28.738  5744  5760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-28 12:59:28.739  5744  5775 D A2dpStateMachine: Enter Disconnected: -2
,11-28 12:59:28.740  5744  5744 I BluetoothHidServiceJni: classInitNative: succeeds
11-28 12:59:28.740  5744  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:28.742  5603  5603 D BluetoothInputDevice: Proxy object connected
11-28 12:59:28.742  5744  5744 D HidService: Received start request. Starting profile...
11-28 12:59:28.742  5744  5744 I bt_bluedroid: get_profile_interface hidhost
11-28 12:59:28.742  5744  5744 D HidService: setHidService(): set to: null
,11-28 12:59:28.742  5744  5760 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c0556d
11-28 12:59:28.742  5744  5760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-28 12:59:28.742  5603  5603 D HidProfile: Bluetooth service connected
11-28 12:59:28.743  5744  5744 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-28 12:59:28.744  5744  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:28.744  5744  5744 D HealthService: Received start request. Starting profile...
,11-28 12:59:28.746  5744  5744 I bt_bluedroid: get_profile_interface health
,11-28 12:59:28.747  5744  5744 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-28 12:59:28.747  5744  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
11-28 12:59:28.748  5603  5603 D BluetoothPan: BluetoothPAN Proxy object connected
,11-28 12:59:28.748  5744  5744 D PanService: Received start request. Starting profile...
11-28 12:59:28.749  5744  5744 D BluetoothPanServiceJni: initializeNative(L110): pan
11-28 12:59:28.749  5744  5744 I bt_bluedroid: get_profile_interface pan
11-28 12:59:28.749  5603  5603 D PanProfile: Bluetooth service connected
11-28 12:59:28.749  5744  5760 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-28 12:59:28.751  5744  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:28.753  5603  5603 D BluetoothMap: Proxy object connected
,11-28 12:59:28.753  5744  5744 D BluetoothMapService: Received start request. Starting profile...
11-28 12:59:28.753  5744  5744 D BluetoothMapService: start()
11-28 12:59:28.753  5603  5603 D MapProfile: Bluetooth service connected
11-28 12:59:28.753  5603  5603 D BluetoothMap: getConnectedDevices()
11-28 12:59:28.754  5603  5603 D BluetoothMap: Bluetooth is Not enabled
,11-28 12:59:28.756  5744  5744 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-28 12:59:28.757  5744  5744 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-28 12:59:28.757  5744  5744 D BluetoothMapAppObserver: createReceiver()
,11-28 12:59:28.758  5744  5744 D BluetoothMapAppObserver: initObservers()
,11-28 12:59:28.758  5744  5744 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-28 12:59:28.764  5744  5744 V SapService: SapBinder()
,11-28 12:59:28.764  5744  5744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
11-28 12:59:28.765  5744  5744 D SapService: Received start request. Starting profile...
11-28 12:59:28.765  5744  5744 V SapService: start()
,11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isTurningOn()=true
,11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:28.769  5744  5772 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isTurningOn()=true
,11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:28.769  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:28.770  3501  3501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:28.770  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:28.771  5744  5744 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:28.771  5744  5744 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:28.771  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:28.771  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:28.772  5744  5756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-28 12:59:28.772  5744  5756 D BluetoothAdapterProperties: ScanMode =  20
,11-28 12:59:28.772  5744  5756 D BluetoothAdapterProperties: State =  11
11-28 12:59:28.772  5744  5756 D BluetoothAdapterProperties: Setting state to 12
11-28 12:59:28.772  5744  5756 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-28 12:59:28.773  5744  5756 I BluetoothAdapterState: Entering OnState
11-28 12:59:28.773  5603  5614 D BluetoothMap: onBluetoothStateChange: up=true
,11-28 12:59:28.774  3035  3054 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 12:59:28.775  5744  5760 D BluetoothAdapterProperties: Scan Mode:21
11-28 12:59:28.775  5744  5760 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-28 12:59:28.775  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-28 12:59:28.776   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 12:59:28.777  5603  5615 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 12:59:28.777  5603  5614 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 12:59:28.777  3035  3035 D BluetoothA2dp: Proxy object connected
11-28 12:59:28.779  3707  3733 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 12:59:28.779  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:28.779  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:28.779  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:28.779  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 12:59:28.779  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 12:59:28.779  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:28.779  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 12:59:28.779  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 12:59:28.779  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-28 12:59:28.779  3035  3048 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 12:59:28.781  3035  3900 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 12:59:28.781  3035  3035 D BluetoothInputDevice: Proxy object connected
11-28 12:59:28.781  3035  3035 D HidProfile: Bluetooth service connected
11-28 12:59:28.781  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-28 12:59:28.782  3035  3840 D BluetoothPan: onBluetoothStateChange on: true
,11-28 12:59:28.784  3035  3035 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 12:59:28.784   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 12:59:28.784  3035  3035 D PanProfile: Bluetooth service connected
11-28 12:59:28.784  5744  5744 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-28 12:59:28.785  5744  5744 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-28 12:59:28.785   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 12:59:28.785   931   931 D BluetoothA2dp: Proxy object connected
11-28 12:59:28.785  3035  3054 D BluetoothMap: onBluetoothStateChange: up=true
,11-28 12:59:28.786  5744  5744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 12:59:28.787  3035  3035 D BluetoothMap: Proxy object connected
11-28 12:59:28.787  3035  3035 D MapProfile: Bluetooth service connected
11-28 12:59:28.787  3035  3035 D BluetoothMap: getConnectedDevices()
11-28 12:59:28.788  3035  3840 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 12:59:28.788  5744  5744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 12:59:28.790  5603  5615 D BluetoothPan: onBluetoothStateChange on: true
,11-28 12:59:28.790  5744  5744 D ObexServerSockets: Succeed to create listening sockets 
11-28 12:59:28.790  5744  5744 D ObexServerSockets0: startAccept()
11-28 12:59:28.790  5744  5744 D ObexServerSockets0: prepareForNewConnect()
,11-28 12:59:28.790   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 12:59:28.791   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,11-28 12:59:28.792  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-28 12:59:28.792  5744  5744 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-28 12:59:28.792  5744  5744 D BluetoothSdpJni: SDP Create record success - handle: 0
11-28 12:59:28.793  5744  5744 D BluetoothMapService: onReceive
11-28 12:59:28.793  5744  5744 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 12:59:28.793  5744  5744 D BluetoothMapService: STATE_ON
,11-28 12:59:28.793  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 12:59:28.794  5744  5782 D ObexServerSockets0: Accepting socket connection...
,11-28 12:59:28.795  5603  5603 D LocalBluetoothProfileManager: Adding local A2DP profile
11-28 12:59:28.796  5744  5781 D ObexServerSockets0: Accepting socket connection...
11-28 12:59:28.797  5744  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 12:59:28.799  5603  5603 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-28 12:59:28.800  5744  5784 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-28 12:59:28.800  5744  5784 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-28 12:59:28.804  5603  5603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 12:59:28.807  5603  5603 D BluetoothA2dp: Proxy object connected
,11-28 12:59:28.812  3501  3501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 12:59:28.813  5603  5603 D DockEventReceiver: finishStartingService: stopping service
,11-28 12:59:28.819  3035  3035 D BluetoothPbap: Proxy object connected
,11-28 12:59:28.819  3035  3035 D PbapServerProfile: Bluetooth service connected
11-28 12:59:28.819  5603  5603 D BluetoothPbap: Proxy object connected
,11-28 12:59:28.819  5744  5744 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-28 12:59:28.819  5744  5744 D ObexServerSockets0: prepareForNewConnect()
11-28 12:59:28.819  5603  5603 D PbapServerProfile: Bluetooth service connected
,11-28 12:59:28.827  5744  5788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 12:59:28.842  5744  5792 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 12:59:28.843  5744  5792 I BtOppRfcommListener: Accept thread started.
,11-28 12:59:28.878  3035  3048 D BluetoothHeadset: Proxy object connected
,11-28 12:59:28.878  3035  3035 D HeadsetProfile: Bluetooth service connected
11-28 12:59:28.878   931   931 D BluetoothHeadset: Proxy object connected
11-28 12:59:28.879  3707  3932 D BluetoothHeadset: Proxy object connected
11-28 12:59:28.879   931   931 D BluetoothHeadset: Proxy object connected
11-28 12:59:28.879   931   931 D BluetoothHeadset: Proxy object connected
11-28 12:59:28.879  3707  3727 D BluetoothHeadset: Proxy object connected
,11-28 12:59:28.882  3035  3054 D BluetoothHeadset: Proxy object connected
11-28 12:59:28.882  3035  3035 D HeadsetProfile: Bluetooth service connected
,11-28 12:59:28.885   931   948 D BluetoothHeadset: Proxy object connected
,11-28 12:59:28.891   931   948 D BluetoothHeadset: Proxy object connected
,11-28 12:59:28.901  5603  5614 D BluetoothHeadset: Proxy object connected
,11-28 12:59:28.902  5603  5603 D HeadsetProfile: Bluetooth service connected
,11-28 12:59:29.807   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-28 12:59:29.808   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 12:59:30.517   931  2892 D ConnectivityService: handlePromptUnvalidated 101
,11-28 12:59:32.721  5744  5756 D BluetoothAdapterState: Current state: ON, message: 23
,11-28 12:59:32.722  5744  5756 D BluetoothAdapterProperties: Setting state to 13
,11-28 12:59:32.722  5744  5756 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-28 12:59:32.724  5744  5756 D BluetoothAdapterProperties: onBluetoothDisable()
11-28 12:59:32.726  5744  5756 I BluetoothAdapterState: Entering PendingCommandState
,11-28 12:59:32.728  5744  5760 D BluetoothAdapterProperties: Scan Mode:20
11-28 12:59:32.729  5744  5756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-28 12:59:32.731  5744  5744 D BluetoothMapService: onReceive
11-28 12:59:32.732  5744  5744 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 12:59:32.732  5744  5744 D BluetoothMapService: STATE_TURNING_OFF
11-28 12:59:32.733  5744  5744 D BluetoothMapService: MAP Service closeService in
11-28 12:59:32.733  5744  5744 D BluetoothMapMasInstance0: MAP Service shutdown
11-28 12:59:32.733  5744  5744 D ObexServerSockets0: shutdown(block = true)
,11-28 12:59:32.734  5744  5781 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-28 12:59:32.742  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 12:59:32.742  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:32.742  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:32.742  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:32.742  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 12:59:32.742  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 12:59:32.742  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:32.742  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 12:59:32.742  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 12:59:32.742  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 12:59:32.742  5603  5603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 12:59:32.743  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 12:59:32.743  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-28 12:59:32.745  5744  5744 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-28 12:59:32.746  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 12:59:32.746  5744  5744 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 12:59:32.746  5744  5782 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-28 12:59:32.746  5744  5769 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-28 12:59:32.748  5744  5744 I BtOppRfcommListener: stopping Accept Thread
11-28 12:59:32.749  5744  5792 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-28 12:59:32.750  5744  5792 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-28 12:59:32.753  5603  5603 D DockEventReceiver: finishStartingService: stopping service
11-28 12:59:32.754  5744  5744 D HeadsetService: Received stop request...Stopping profile...
11-28 12:59:32.759  3035  3900 D BluetoothHeadset: Proxy object disconnected
,11-28 12:59:32.759  3035  3035 D HeadsetProfile: Bluetooth service disconnected
11-28 12:59:32.759   931   931 D BluetoothHeadset: Proxy object disconnected
11-28 12:59:32.760  5603  5615 D BluetoothHeadset: Proxy object disconnected
11-28 12:59:32.761  3707  3733 D BluetoothHeadset: Proxy object disconnected
11-28 12:59:32.761   931   931 D BluetoothHeadset: Proxy object disconnected
11-28 12:59:32.761   931   931 D BluetoothHeadset: Proxy object disconnected
,11-28 12:59:32.763  5744  5744 D A2dpService: Received stop request...Stopping profile...
,11-28 12:59:32.763  5603  5603 D HeadsetProfile: Bluetooth service disconnected
11-28 12:59:32.763  5744  5775 D A2dpStateMachine: Exit Disconnected: -1
,11-28 12:59:32.765  3035  3035 D BluetoothA2dp: Proxy object disconnected
11-28 12:59:32.766  5603  5603 D BluetoothA2dp: Proxy object disconnected
,11-28 12:59:32.768  5744  5744 D HidService: Received stop request...Stopping profile...
,11-28 12:59:32.768  5744  5744 D HidService: Stopping Bluetooth HidService
,11-28 12:59:32.768   931   931 D BluetoothA2dp: Proxy object disconnected
11-28 12:59:32.769  3035  3035 D BluetoothInputDevice: Proxy object disconnected
11-28 12:59:32.769  3035  3035 D HidProfile: Bluetooth service disconnected
11-28 12:59:32.770  5744  5744 D HealthService: Received stop request...Stopping profile...
11-28 12:59:32.770  5603  5603 D BluetoothInputDevice: Proxy object disconnected
11-28 12:59:32.770  5603  5603 D HidProfile: Bluetooth service disconnected
,11-28 12:59:32.773  5744  5744 D PanService: Received stop request...Stopping profile...
,11-28 12:59:32.775  3501  3501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 12:59:32.775  5603  5603 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-28 12:59:32.775  5603  5603 D PanProfile: Bluetooth service disconnected
11-28 12:59:32.775  3035  3035 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-28 12:59:32.775  3035  3035 D PanProfile: Bluetooth service disconnected
,11-28 12:59:32.778  5744  5744 D BluetoothMapService: Received stop request...Stopping profile...
,11-28 12:59:32.778  5744  5744 D BluetoothMapService: stop()
11-28 12:59:32.779  5744  5744 D BluetoothMapAppObserver: deinitObservers()
11-28 12:59:32.779  5744  5744 D BluetoothMapAppObserver: removeReceiver()
11-28 12:59:32.780  3035  3035 D BluetoothMap: Proxy object disconnected
11-28 12:59:32.780  3035  3035 D MapProfile: Bluetooth service disconnected
11-28 12:59:32.781  5603  5603 D BluetoothMap: Proxy object disconnected
11-28 12:59:32.781  5603  5603 D MapProfile: Bluetooth service disconnected
,11-28 12:59:32.781  5744  5744 D SapService: Received stop request...Stopping profile...
11-28 12:59:32.781  5744  5744 V SapService: stop()
11-28 12:59:32.782  5744  5744 V BluetoothAdapterState: isTurningOff()=true
,11-28 12:59:32.782  5744  5744 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:32.782  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:32.782  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:32.784  5744  5744 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-28 12:59:32.784  5744  5744 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-28 12:59:32.784  5744  5767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:32.785  5744  5767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-28 12:59:32.785  5744  5744 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:32.785  5744  5767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:32.785  5744  5744 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:32.785  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:32.785  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:32.785  5744  5760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-28 12:59:32.786  5744  5760 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-28 12:59:32.786  5744  5760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-28 12:59:32.786  5744  5767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:32.786  5744  5744 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:32.786  5744  5767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 12:59:32.786  5744  5767 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 12:59:32.786  5744  5767 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 12:59:32.787  5744  5767 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-28 12:59:32.787  5744  5767 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-28 12:59:32.788  5744  5744 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:32.788  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:32.788  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:32.789  5744  5744 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-28 12:59:32.789  5744  5744 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-28 12:59:32.789  5744  5744 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:32.789  5744  5744 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:32.789  5744  5760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-28 12:59:32.789  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:32.789  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 12:59:32.790  5744  5744 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-28 12:59:32.790  5744  5760 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-28 12:59:32.790  5744  5744 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-28 12:59:32.793  3035  3035 D BluetoothPbap: Proxy object disconnected
11-28 12:59:32.793  3035  3035 D PbapServerProfile: Bluetooth service disconnected
,11-28 12:59:32.793  5744  5744 V BluetoothAdapterState: isTurningOff()=true
,11-28 12:59:32.793  5744  5744 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:32.793  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:32.793  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:32.793  5744  5744 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-28 12:59:32.793  5744  5744 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-28 12:59:32.794  5744  5744 D BluetoothMapService: MAP Service closeService in
,11-28 12:59:32.794  5744  5744 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:32.794  5744  5744 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:32.794  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:32.795  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:32.795  5744  5744 D BluetoothMapService: cleanup()
11-28 12:59:32.796  5744  5744 D BluetoothMapService: MAP Service closeService in
11-28 12:59:32.796  5744  5744 V BluetoothAdapterState: isTurningOff()=true
11-28 12:59:32.796  5744  5744 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:32.796  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:32.796  5744  5744 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:32.796  5744  5756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-28 12:59:32.796  5744  5756 D BluetoothAdapterProperties: Setting state to 15
11-28 12:59:32.796  5744  5756 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-28 12:59:32.797  5744  5756 I BluetoothAdapterState: Entering BleOnState
11-28 12:59:32.797  5603  5603 D BluetoothPbap: Proxy object disconnected
11-28 12:59:32.797  5603  5603 D PbapServerProfile: Bluetooth service disconnected
11-28 12:59:32.798  5603  5614 D BluetoothMap: onBluetoothStateChange: up=false
11-28 12:59:32.799  5603  5615 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 12:59:32.800  3035  3900 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 12:59:32.800   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 12:59:32.800  5603  5614 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-28 12:59:32.801  5603  5615 D BluetoothPbap: onBluetoothStateChange: up=false
,11-28 12:59:32.802  3707  3932 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 12:59:32.802  5603  5614 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 12:59:32.803  3035  3840 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-28 12:59:32.804  3035  3048 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 12:59:32.804  3035  3054 D BluetoothPan: onBluetoothStateChange on: false
11-28 12:59:32.804   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-28 12:59:32.804   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 12:59:32.805  3035  3900 D BluetoothMap: onBluetoothStateChange: up=false
11-28 12:59:32.805  3035  3840 D BluetoothPbap: onBluetoothStateChange: up=false
11-28 12:59:32.806  5603  5615 D BluetoothPan: onBluetoothStateChange on: false
11-28 12:59:32.806   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 12:59:32.807  5744  5756 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-28 12:59:32.807  5744  5756 D BluetoothAdapterProperties: Setting state to 16
11-28 12:59:32.807  5744  5756 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-28 12:59:32.807  5744  5756 D BluetoothAdapterProperties: onBleDisable
11-28 12:59:32.808  5744  5756 I BluetoothAdapterState: Entering PendingCommandState
11-28 12:59:32.808  5744  5757 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-28 12:59:32.809  5744  5760 D BluetoothAdapterProperties: Scan Mode:20
11-28 12:59:32.809  5744  5767 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-28 12:59:32.809  5744  5767 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-28 12:59:32.810  5603  5603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 12:59:32.810  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:59:32.814  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:59:32.819  5603  5603 D DockEventReceiver: finishStartingService: stopping service
,11-28 12:59:32.820  3501  3501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 12:59:33.023  5744  5760 I bt_hci  : shut_down
,11-28 12:59:33.034  5744  5764 D bt_hwcfg: hw_epilog_process
,11-28 12:59:33.034  5744  5764 I bt_vendor: low_power_mode_cb
,11-28 12:59:33.037  5744  5764 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-28 12:59:33.037  5744  5764 I bt_vendor: epilog_cb
11-28 12:59:33.038  5744  5764 I bt_hci  : epilog_finished_callback
,11-28 12:59:33.043  5744  5760 I bt_hci_h4: hal_close
,11-28 12:59:33.044  5744  5760 I bt_userial_vendor: device fd = 54 close
,11-28 12:59:33.159  5744  5757 D bt_stack_manager: event_shut_down_stack finished.
,11-28 12:59:33.161  5744  5756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-28 12:59:33.165  5744  5756 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-28 12:59:33.165  5744  5744 D BtGatt.DebugUtils: handleDebugAction() action=null
11-28 12:59:33.166  5744  5744 D BtGatt.GattService: Received stop request...Stopping profile...
,11-28 12:59:33.167  5744  5744 D BtGatt.GattService: stop()
11-28 12:59:33.167  5744  5744 D BtGatt.AdvertiseManager: advertise clients cleared
,11-28 12:59:33.171  5744  5744 V BluetoothAdapterState: isTurningOff()=false
,11-28 12:59:33.171  5744  5744 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:33.171  5744  5744 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:33.171  5744  5744 V BluetoothAdapterState: isBleTurningOff()=true
,11-28 12:59:33.172  5744  5756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-28 12:59:33.173  5744  5756 D BluetoothAdapterProperties: Setting state to 10
11-28 12:59:33.173  5744  5756 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-28 12:59:33.174  5744  5756 I BluetoothAdapterState: Entering OffState
,11-28 12:59:33.176   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-28 12:59:33.190  5744  5744 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-28 12:59:33.190  5744  5744 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-28 12:59:33.190  5744  5744 I BluetoothServiceJni: cleanupNative: return from cleanup
11-28 12:59:33.192  5744  5757 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-28 12:59:33.199  5744  5744 I art     : System.exit called, status: 0
,11-28 12:59:33.200  5744  5744 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-28 12:59:33.229   931  3705 I ActivityManager: Process com.android.bluetooth (pid 5744) has died
,11-28 12:59:37.721  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 12:59:37.721  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 12:59:37.728  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:37.728  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ebb0641 removed from the list
11-28 12:59:37.728  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 12:59:37.730  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:37.730  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7944fd4 added. We now have 4 listener(s)
11-28 12:59:37.731  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:37.733  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:37.733  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7944fd4 removed from the list
11-28 12:59:37.734  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:37.736  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:37.736  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c70c57d added. We now have 4 listener(s)
,11-28 12:59:37.736  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:39.809   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:40.810   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:41.812   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:42.747  5549  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:59:42.777   931   948 I ActivityManager: Start proc 5802:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-28 12:59:42.813   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:42.862  5802  5802 D AdapterServiceConfig: Adding HeadsetService
,11-28 12:59:42.863  5802  5802 D AdapterServiceConfig: Adding A2dpService
11-28 12:59:42.863  5802  5802 D AdapterServiceConfig: Adding HidService
11-28 12:59:42.863  5802  5802 D AdapterServiceConfig: Adding HealthService
11-28 12:59:42.863  5802  5802 D AdapterServiceConfig: Adding PanService
11-28 12:59:42.863  5802  5802 D AdapterServiceConfig: Adding GattService
11-28 12:59:42.864  5802  5802 D AdapterServiceConfig: Adding BluetoothMapService
11-28 12:59:42.864  5802  5802 D AdapterServiceConfig: Adding SapService
,11-28 12:59:42.874   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8312719:true
,11-28 12:59:42.875  5802  5802 D BluetoothAdapterState: make() - Creating AdapterState
,11-28 12:59:42.877  5802  5802 I bt_bluedroid: init
,11-28 12:59:42.878  5802  5814 I BluetoothAdapterState: Entering OffState
,11-28 12:59:42.880  5802  5815 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-28 12:59:42.880  5802  5815 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-28 12:59:42.880  5802  5815 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-28 12:59:42.880  5802  5815 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-28 12:59:42.881  5802  5802 I bt_bluedroid: get_profile_interface socket
,11-28 12:59:42.883  5802  5802 I bt_bluedroid: get_profile_interface sdp
,11-28 12:59:42.883  5802  5818 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-28 12:59:42.884  5802  5818 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 12:59:42.888  5802  5813 I bt_bluedroid: config_hci_snoop_log
11-28 12:59:42.889   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-28 12:59:42.893  5802  5814 D BluetoothAdapterState: Current state: OFF, message: 0
11-28 12:59:42.893  5802  5814 D BluetoothAdapterProperties: Setting state to 14
11-28 12:59:42.893  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-28 12:59:42.895  5802  5814 D BluetoothBondStateMachine: make
,11-28 12:59:42.897  5802  5819 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-28 12:59:42.900  5802  5814 I BluetoothAdapterState: Entering PendingCommandState
,11-28 12:59:42.901  5802  5802 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-28 12:59:42.904  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
11-28 12:59:42.904  5802  5802 D BtGatt.DebugUtils: handleDebugAction() action=null
11-28 12:59:42.905  5802  5802 D BtGatt.GattService: Received start request. Starting profile...
11-28 12:59:42.905  5802  5802 D BtGatt.GattService: start()
,11-28 12:59:42.905  5802  5802 I bt_bluedroid: get_profile_interface gatt
,11-28 12:59:42.906  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
11-28 12:59:42.906  5802  5802 D BtGatt.AdvertiseManager: advertise manager created
,11-28 12:59:42.911  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:42.911  5802  5802 V BluetoothAdapterState: isTurningOn()=false
11-28 12:59:42.911  5802  5802 V BluetoothAdapterState: isBleTurningOn()=true
11-28 12:59:42.911  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 12:59:42.912  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-28 12:59:42.913  5802  5814 I bt_bluedroid: bt_bluedroid
11-28 12:59:42.913  5802  5815 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-28 12:59:42.914  5802  5815 I bt_hci  : start_up
,11-28 12:59:42.920  5802  5815 I bt_vendor: alloc value 0xf3ca6871
,11-28 12:59:42.920  5802  5815 I bt_vendor: init
,11-28 12:59:42.930  5802  5815 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-28 12:59:42.930  5802  5815 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-28 12:59:43.043  5802  5815 D bt_hci  : start_up starting async portion
11-28 12:59:43.043  5802  5822 I bt_hci  : event_finish_startup
,11-28 12:59:43.043  5802  5822 I bt_hci_h4: hal_open
11-28 12:59:43.043  5802  5822 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-28 12:59:43.040  5823  5823 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-28 12:59:43.046  5802  5822 I bt_userial_vendor: device fd = 54 open
,11-28 12:59:43.063  5802  5822 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 12:59:43.066  5802  5822 D bt_hwcfg: Chipset BCM4358A3
,11-28 12:59:43.066  5802  5822 D bt_hwcfg: Target name = [BCM4358A3]
11-28 12:59:43.066  5802  5822 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-28 12:59:43.574  5802  5822 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-28 12:59:43.575  5802  5822 D bt_hwcfg: Settlement delay -- 100 ms
11-28 12:59:43.575  5802  5822 I bt_hwcfg: Setting fw settlement delay to 100 
,11-28 12:59:43.709  5802  5822 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 12:59:43.710  5802  5822 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-28 12:59:43.711  5802  5822 I bt_hwcfg: vendor lib fwcfg completed
11-28 12:59:43.711  5802  5822 I bt_vendor: firmware callback
11-28 12:59:43.711  5802  5822 I bt_hci  : firmware_config_callback
,11-28 12:59:43.721  5802  5825 I bt_btu  : btu_task pending for preload complete event
,11-28 12:59:43.721  5802  5825 I bt_btu_task: Bluetooth chip preload is complete
11-28 12:59:43.721  5802  5825 I bt_btu  : btu_task received preload complete event
,11-28 12:59:43.726  5802  5825 I         : BTE_InitTraceLevels -- TRC_HCI
,11-28 12:59:43.727  5802  5825 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-28 12:59:43.727  5802  5825 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-28 12:59:43.727  5802  5825 I         : BTE_InitTraceLevels -- TRC_AVDT
11-28 12:59:43.727  5802  5825 I         : BTE_InitTraceLevels -- TRC_AVRC
11-28 12:59:43.727  5802  5825 I         : BTE_InitTraceLevels -- TRC_A2D
,11-28 12:59:43.727  5802  5825 I         : BTE_InitTraceLevels -- TRC_BNEP
11-28 12:59:43.727  5802  5825 I         : BTE_InitTraceLevels -- TRC_BTM
11-28 12:59:43.727  5802  5825 I         : BTE_InitTraceLevels -- TRC_GAP
11-28 12:59:43.728  5802  5825 I         : BTE_InitTraceLevels -- TRC_PAN
11-28 12:59:43.728  5802  5825 I         : BTE_InitTraceLevels -- TRC_SDP
,11-28 12:59:43.728  5802  5825 I         : BTE_InitTraceLevels -- TRC_GATT
11-28 12:59:43.728  5802  5825 I         : BTE_InitTraceLevels -- TRC_SMP
11-28 12:59:43.728  5802  5825 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-28 12:59:43.728  5802  5825 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-28 12:59:43.814   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:43.826  5802  5825 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c24549
,11-28 12:59:43.826  5802  5825 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c24549 
,11-28 12:59:43.851  5802  5818 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-28 12:59:43.854  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-28 12:59:43.854  5802  5818 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-28 12:59:43.857  5802  5818 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 12:59:43.859  5802  5818 D BluetoothAdapterProperties: Scan Mode:20
,11-28 12:59:43.860  5802  5818 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 12:59:43.860  5802  5818 D bt_hci  : do_postload posting postload work item
11-28 12:59:43.860  5802  5822 I bt_hci  : event_postload
11-28 12:59:43.860  5802  5822 I bt_vendor: sco_config_cb
11-28 12:59:43.860  5802  5822 I bt_hci  : sco_config_callback postload finished.
,11-28 12:59:43.863  5802  5818 D bt_bte_conf: Device ID record 1 : primary
,11-28 12:59:43.864  5802  5818 D bt_bte_conf:   vendorId            = 000f
11-28 12:59:43.864  5802  5818 D bt_bte_conf:   vendorIdSource      = 0001
11-28 12:59:43.864  5802  5818 D bt_bte_conf:   product             = 1200
11-28 12:59:43.864  5802  5818 D bt_bte_conf:   version             = 1436
11-28 12:59:43.864  5802  5818 D bt_bte_conf:   clientExecutableURL = 
11-28 12:59:43.864  5802  5818 D bt_bte_conf:   serviceDescription  = 
11-28 12:59:43.864  5802  5818 D bt_bte_conf:   documentationURL    = 
11-28 12:59:43.864  5802  5818 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-28 12:59:43.864  5802  5815 D bt_stack_manager: event_start_up_stack finished
,11-28 12:59:43.865  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-28 12:59:43.865  5802  5814 D BluetoothAdapterProperties: Setting state to 15
11-28 12:59:43.865  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-28 12:59:43.866  5802  5814 I BluetoothAdapterState: Entering BleOnState
,11-28 12:59:43.868  5802  5822 I bt_vendor: low_power_mode_cb
11-28 12:59:43.869  5802  5814 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-28 12:59:43.870  5802  5814 D BluetoothAdapterProperties: Setting state to 11
11-28 12:59:43.870  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-28 12:59:43.875  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:43.876  5802  5802 D HeadsetService: Received start request. Starting profile...
,11-28 12:59:43.880  5802  5802 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-28 12:59:43.880  5802  5802 D HeadsetStateMachine: make
,11-28 12:59:43.891  5802  5814 I BluetoothAdapterState: Entering PendingCommandState
,11-28 12:59:43.896  5802  5802 D HeadsetStateMachine: max_hf_connections = 1
,11-28 12:59:43.896  5802  5802 I bt_bluedroid: get_profile_interface handsfree
11-28 12:59:43.896  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-28 12:59:43.897  5802  5818 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-28 12:59:43.900  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:43.901  5802  5802 D A2dpService: Received start request. Starting profile...
11-28 12:59:43.903  5802  5802 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-28 12:59:43.903  5802  5802 I bt_bluedroid: get_profile_interface avrcp
,11-28 12:59:43.913  5802  5802 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-28 12:59:43.913  5802  5802 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-28 12:59:43.913  5802  5802 D A2dpStateMachine: make
,11-28 12:59:43.914  5802  5802 I bt_bluedroid: get_profile_interface a2dp
,11-28 12:59:43.916  5802  5833 D A2dpStateMachine: Enter Disconnected: -2
,11-28 12:59:43.917  5802  5802 I BluetoothHidServiceJni: classInitNative: succeeds
,11-28 12:59:43.917  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-28 12:59:43.918  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
11-28 12:59:43.919  5802  5802 D HidService: Received start request. Starting profile...
11-28 12:59:43.919  5802  5802 I bt_bluedroid: get_profile_interface hidhost
11-28 12:59:43.919  5802  5802 D HidService: setHidService(): set to: null
11-28 12:59:43.921  5802  5802 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-28 12:59:43.922  5802  5818 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c0556d
11-28 12:59:43.922  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-28 12:59:43.922  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
11-28 12:59:43.922  3501  3501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 12:59:43.924  5802  5802 D HealthService: Received start request. Starting profile...
,11-28 12:59:43.926  5802  5802 I bt_bluedroid: get_profile_interface health
11-28 12:59:43.926  5802  5802 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-28 12:59:43.927  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:43.928  5802  5802 D PanService: Received start request. Starting profile...
,11-28 12:59:43.928  5802  5802 D BluetoothPanServiceJni: initializeNative(L110): pan
11-28 12:59:43.928  5802  5802 I bt_bluedroid: get_profile_interface pan
11-28 12:59:43.928  5802  5818 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-28 12:59:43.931  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:43.931  5802  5802 D BluetoothMapService: Received start request. Starting profile...
,11-28 12:59:43.931  5802  5802 D BluetoothMapService: start()
,11-28 12:59:43.934  5802  5802 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-28 12:59:43.935  5802  5802 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-28 12:59:43.935  5802  5802 D BluetoothMapAppObserver: createReceiver()
,11-28 12:59:43.937  5802  5802 D BluetoothMapAppObserver: initObservers()
11-28 12:59:43.937  5802  5802 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-28 12:59:43.943  5802  5802 V SapService: SapBinder()
,11-28 12:59:43.943  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:43.943  5802  5802 D SapService: Received start request. Starting profile...
11-28 12:59:43.943  5802  5802 V SapService: start()
,11-28 12:59:43.946  5802  5802 V BluetoothAdapterState: isTurningOff()=false
,11-28 12:59:43.946  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
,11-28 12:59:43.947  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:43.947  5802  5831 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:43.948  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-28 12:59:43.949  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-28 12:59:43.949  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-28 12:59:43.949  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-28 12:59:43.949  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 12:59:43.949  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-28 12:59:43.950  5802  5814 D BluetoothAdapterProperties: ScanMode =  20
11-28 12:59:43.950  5802  5814 D BluetoothAdapterProperties: State =  11
,11-28 12:59:43.951  5802  5818 D BluetoothAdapterProperties: Scan Mode:21
,11-28 12:59:43.951  5802  5818 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 12:59:43.951  5802  5814 D BluetoothAdapterProperties: Setting state to 12
11-28 12:59:43.951  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-28 12:59:43.952  5603  5615 D BluetoothMap: onBluetoothStateChange: up=true
11-28 12:59:43.953  5802  5814 I BluetoothAdapterState: Entering OnState
11-28 12:59:43.955  5603  5614 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 12:59:43.955  3035  3840 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 12:59:43.957   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 12:59:43.958  5603  5614 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 12:59:43.958  3035  3035 D BluetoothA2dp: Proxy object connected
,11-28 12:59:43.959  5603  5615 D BluetoothPbap: onBluetoothStateChange: up=true
,11-28 12:59:43.961  3707  3727 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 12:59:43.961  5603  5614 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 12:59:43.962  5802  5802 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-28 12:59:43.962  5802  5802 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-28 12:59:43.963  3035  3048 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-28 12:59:43.963  5802  5802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 12:59:43.964  3035  3035 D BluetoothInputDevice: Proxy object connected
11-28 12:59:43.964  3035  3035 D HidProfile: Bluetooth service connected
11-28 12:59:43.965  3035  3840 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 12:59:43.965  5802  5802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 12:59:43.966  3035  3900 D BluetoothPan: onBluetoothStateChange on: true
11-28 12:59:43.966  5802  5802 D ObexServerSockets: Succeed to create listening sockets 
11-28 12:59:43.967  5802  5802 D ObexServerSockets0: startAccept()
11-28 12:59:43.967  5802  5802 D ObexServerSockets0: prepareForNewConnect()
11-28 12:59:43.967   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-28 12:59:43.967   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 12:59:43.968   931   931 D BluetoothA2dp: Proxy object connected
11-28 12:59:43.968  3035  3048 D BluetoothMap: onBluetoothStateChange: up=true
11-28 12:59:43.968  5603  5603 D BluetoothMap: Proxy object connected
11-28 12:59:43.968  5603  5603 D MapProfile: Bluetooth service connected
11-28 12:59:43.968  5603  5603 D BluetoothMap: getConnectedDevices()
11-28 12:59:43.968  5802  5802 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-28 12:59:43.968  5802  5802 D BluetoothSdpJni: SDP Create record success - handle: 0
11-28 12:59:43.969  5802  5839 D ObexServerSockets0: Accepting socket connection...
,11-28 12:59:43.969  5802  5840 D ObexServerSockets0: Accepting socket connection...
,11-28 12:59:43.969  3035  3035 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 12:59:43.970  3035  3035 D PanProfile: Bluetooth service connected
11-28 12:59:43.970  3035  3900 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 12:59:43.970  3035  3035 D BluetoothMap: Proxy object connected
,11-28 12:59:43.970  3035  3035 D MapProfile: Bluetooth service connected
11-28 12:59:43.970  3035  3035 D BluetoothMap: getConnectedDevices()
11-28 12:59:43.971  5603  5603 D BluetoothInputDevice: Proxy object connected
11-28 12:59:43.971  5603  5603 D HidProfile: Bluetooth service connected
11-28 12:59:43.971  5603  5615 D BluetoothPan: onBluetoothStateChange on: true
11-28 12:59:43.973   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 12:59:43.974  5603  5603 D BluetoothA2dp: Proxy object connected
11-28 12:59:43.975  5802  5802 D BluetoothMapService: onReceive
11-28 12:59:43.975  5802  5802 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 12:59:43.975  5802  5802 D BluetoothMapService: STATE_ON
11-28 12:59:43.975   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-28 12:59:43.976  5603  5603 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 12:59:43.976  5603  5603 D PanProfile: Bluetooth service connected
11-28 12:59:43.978  5802  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 12:59:43.980  5802  5842 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-28 12:59:43.980  5802  5842 D BluetoothSdpJni: SDP Create record success - handle: 1
11-28 12:59:43.981  5603  5603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 12:59:43.987  3501  3501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 12:59:43.988  5603  5603 D DockEventReceiver: finishStartingService: stopping service
,11-28 12:59:43.993  5603  5603 D BluetoothPbap: Proxy object connected
11-28 12:59:43.994  5603  5603 D PbapServerProfile: Bluetooth service connected
,11-28 12:59:43.999  5802  5802 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-28 12:59:44.000  5802  5802 D ObexServerSockets0: prepareForNewConnect()
,11-28 12:59:44.000  5802  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 12:59:44.004  3035  3035 D BluetoothPbap: Proxy object connected
11-28 12:59:44.004  3035  3035 D PbapServerProfile: Bluetooth service connected
,11-28 12:59:44.017  5802  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 12:59:44.019  5802  5850 I BtOppRfcommListener: Accept thread started.
,11-28 12:59:44.056  3035  3048 D BluetoothHeadset: Proxy object connected
11-28 12:59:44.057   931   931 D BluetoothHeadset: Proxy object connected
11-28 12:59:44.057  3035  3035 D HeadsetProfile: Bluetooth service connected
,11-28 12:59:44.057  5603  5838 D BluetoothHeadset: Proxy object connected
,11-28 12:59:44.057  3707  3733 D BluetoothHeadset: Proxy object connected
11-28 12:59:44.057   931   948 D BluetoothHeadset: Proxy object connected
11-28 12:59:44.058   931   931 D BluetoothHeadset: Proxy object connected
11-28 12:59:44.058   931   931 D BluetoothHeadset: Proxy object connected
11-28 12:59:44.059  5603  5603 D HeadsetProfile: Bluetooth service connected
,11-28 12:59:44.062  3707  3932 D BluetoothHeadset: Proxy object connected
,11-28 12:59:44.066  3035  3054 D BluetoothHeadset: Proxy object connected
11-28 12:59:44.066  3035  3035 D HeadsetProfile: Bluetooth service connected
,11-28 12:59:44.067   931   948 D BluetoothHeadset: Proxy object connected
,11-28 12:59:44.074   931   948 D BluetoothHeadset: Proxy object connected
,11-28 12:59:44.815   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-28 12:59:47.762  5549  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:47.762  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:47.762  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:47.762  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 12:59:47.762  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 12:59:47.762  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 12:59:47.762  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 12:59:47.762  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 12:59:47.762  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 12:59:47.768  5549  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 12:59:47.769  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 12:59:47.769  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c70c57d removed from the list
11-28 12:59:47.769  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 12:59:47.771  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 12:59:47.771  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3de5c72 added. We now have 4 listener(s)
11-28 12:59:47.772  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:47.776   931  3071 D WifiService: setWifiEnabled: false pid=5549, uid=10077
,11-28 12:59:47.776   931  3071 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 12:59:49.816   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:50.817   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:51.820   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:52.787  5549  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 12:59:52.788   931  3332 D WifiService: setWifiEnabled: true pid=5549, uid=10077
11-28 12:59:52.788   931  3332 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 12:59:52.795   511   928 D SoftapController: Softap fwReload - Ok
,11-28 12:59:52.801   511   928 D CommandListener: Setting iface cfg
,11-28 12:59:52.801   511   928 D CommandListener: Trying to bring down wlan0
,11-28 12:59:52.803   511   928 D CommandListener: Clearing all IP addresses on wlan0
,11-28 12:59:52.809   931  2890 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 12:59:52.821   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:53.496   931  2890 D wifi    : set interface wlan0 flags (UP)
,11-28 12:59:53.498   931  2890 I WifiHAL : Initializing wifi
,11-28 12:59:53.499   931  2890 I WifiHAL : Creating socket
,11-28 12:59:53.507   931  2890 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-28 12:59:53.508   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-28 12:59:53.508   931  2890 D wifi    : Did set static halHandle = 0x7f5e58dcc0
11-28 12:59:53.508   931  2890 D wifi    : halHandle = 0x7f5e58dcc0, mVM = 0x7f7abcd140, mCls = 0x1016a2
11-28 12:59:53.508   931  2890 D wifi    : array field set
11-28 12:59:53.509   931  2890 I WifiNative-HAL: interface[0] = wlan0
,11-28 12:59:53.513   931  5855 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547043728576
11-28 12:59:53.513   931  5855 D wifi    : waitForHalEvents called, vm = 0x7f7abcd140, obj = 0x1016a2, env = 0x7f5f673d80
,11-28 12:59:53.578  5856  5856 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-28 12:59:53.601  5856  5856 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 12:59:53.613  5856  5856 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 12:59:53.613  5856  5856 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
11-28 12:59:53.614   931  2890 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-28 12:59:53.635   931  2890 D WifiConfigStore: Loading config and enabling all networks 
,11-28 12:59:53.649   931  2890 D WifiConfigStore: loaded 0 passpoint configs
11-28 12:59:53.649   931  2890 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-28 12:59:53.650   931  2890 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-28 12:59:53.651   931  2890 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-28 12:59:53.652   931  2890 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-28 12:59:53.653   931  2890 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-28 12:59:53.653   931  2890 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-28 12:59:53.653   931  2890 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-28 12:59:53.657   931  2890 D WifiNative-HAL: Setting external_sim to 1
,11-28 12:59:53.657  4935  4935 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 12:59:53.657   931  2890 D wifi    : setting dfs flag to true, 0x7f602f90a0
11-28 12:59:53.658   931  2890 D WifiStateMachine: Setting OUI to DA-A1-19
11-28 12:59:53.658   931  2890 D wifi    : setting scan oui 0x7f602f90a0
11-28 12:59:53.658   931  2890 D WifiHAL : Sending mac address OUI
,11-28 12:59:53.662   931  2890 E native  : do suspend false
,11-28 12:59:53.672   931  2890 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-28 12:59:53.673   931   931 D RttService: SCAN_AVAILABLE : 3
11-28 12:59:53.673   931  3000 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 12:59:53.677   511   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-28 12:59:53.679   511   928 D CommandListener: Setting iface cfg
,11-28 12:59:53.681   931  2869 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
,11-28 12:59:53.681   931  2869 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-28 12:59:53.687   931  2869 D WifiNative-HAL: p2pGetDeviceAddress
11-28 12:59:53.687   931  2869 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-28 12:59:53.709   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=244067 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=32 mControllerEnergyUsed=121 }
,11-28 12:59:53.822   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 12:59:54.823   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-28 12:59:56.832  5856  5856 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 12:59:56.836  5856  5856 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 12:59:56.841  5856  5856 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 12:59:56.926   931  2890 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-28 12:59:56.927   931  2890 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-28 12:59:56.927   931  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 12:59:56.940   931  2890 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-28 12:59:56.975   931  2890 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-28 12:59:56.978  5856  5856 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-28 12:59:57.404  5856  5856 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-28 12:59:57.434  5856  5856 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-28 12:59:57.434  5856  5856 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-28 12:59:57.445   931  2890 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 12:59:57.445   931  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 12:59:57.445   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-28 12:59:57.458   931  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 12:59:57.468   511   928 D CommandListener: Setting iface cfg
,11-28 12:59:57.474   931  2890 D WifiStateMachine: Start Dhcp Watchdog 3
,11-28 12:59:57.481   931  5861 D DhcpClient: Receive thread started
,11-28 12:59:57.484   931  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-28 12:59:57.484   931  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-28 12:59:57.485   931  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-28 12:59:57.566   931  2890 E native  : do suspend false
,11-28 12:59:57.580   931  5860 D DhcpClient: Broadcasting DHCPDISCOVER
,11-28 12:59:57.594   931  5861 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-28 12:59:57.595   931  5860 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
11-28 12:59:57.597   931  5860 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-28 12:59:57.619   931  5861 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-28 12:59:57.620   931  5860 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-28 12:59:57.623   511   928 D CommandListener: Setting iface cfg
,11-28 12:59:57.629   931  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-28 12:59:57.635   931  5860 D DhcpClient: Scheduling renewal in 86399s
,11-28 12:59:57.647   931  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-28 12:59:57.649   931  2890 D WifiConfigStore: No blacklist allowed without epno enabled
,11-28 12:59:57.650   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-28 12:59:57.652   931  2892 D ConnectivityService: Adding iface wlan0 to network 102
11-28 12:59:57.654   931  2890 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-28 12:59:57.697   931  2892 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-28 12:59:57.698   931  2892 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-28 12:59:57.701   931  2892 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-28 12:59:57.704   931  2892 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-28 12:59:57.706   931  2892 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-28 12:59:57.714   931  2892 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-28 12:59:57.719   931  2892 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-28 12:59:57.719   931  2892 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-28 12:59:57.719   931  2892 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-28 12:59:57.719   931  2890 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-28 12:59:57.719   931  2892 D ConnectivityService:    accepting network in place of null
11-28 12:59:57.720   931  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 12:59:57.720   931  2892 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 12:59:57.739   931  5859 D NetlinkSocketObserver: NeighborEvent{elapsedMs=248097, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 12:59:57.744   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 12:59:57.766   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 12:59:57.770   931  2892 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-28 12:59:57.770  3670  3832 W QCNEJ   : |CORE| network available: 102
11-28 12:59:57.770   931  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-28 12:59:57.771   931  2892 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-28 12:59:57.772   931   948 D Tethering: MasterInitialState.processMessage what=3
11-28 12:59:57.773  3670  3832 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-28 12:59:57.774  3670  3832 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-28 12:59:57.775  3670  3832 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-28 12:59:57.780  4960  4984 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-28 12:59:57.780  4960  4984 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-28 12:59:57.780  4960  4984 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,11-28 12:59:57.784  4960  4984 E SarControlService: no key has been found,reset the power
,11-28 12:59:57.784  4960  4997 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 12:59:57.784  4960  4997 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 12:59:57.784  4960  4997 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 12:59:57.785  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 12:59:57.785  4985  4985 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 12:59:57.786  3767  3767 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 12:59:57.788  4960  4997 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 12:59:57.788  4960  4997 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 12:59:57.788  4960  4997 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-28 12:59:57.789  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-28 12:59:57.789  4985  4985 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 12:59:57.793  3767  3767 D SystemUpdateService: onCreate
11-28 12:59:57.794  4985  4999 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4247c2 HexData = [00000000f003000000000000ffffffff]
,11-28 12:59:57.794  4985  4999 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 12:59:57.794  4985  4999 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-28 12:59:57.794  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 12:59:57.795  4960  4971 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-28 12:59:57.798  4985  4999 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b4247c2 HexData = [00000000f103000000000000ffffffff]
11-28 12:59:57.798  4985  4999 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 12:59:57.798  4985  4999 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-28 12:59:57.798  4985  4985 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 12:59:57.799  4960  4970 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-28 12:59:57.799  3767  3767 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-28 12:59:57.803  5549  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 12:59:57.803  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 12:59:57.803  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 12:59:57.803  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 12:59:57.803  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 12:59:57.803  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 12:59:57.803  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 12:59:57.803  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 12:59:57.803  5549  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 12:59:57.806  5549  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 12:59:57.806   931  5858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-28 12:59:57.806  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.806  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3de5c72 removed from the list
11-28 12:59:57.806  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:57.809  5549  5596 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-28 12:59:57.809  5549  5596 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-28 12:59:57.811  5549  5596 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5080627 Bundle[{}]
,11-28 12:59:57.812  5549  5596 I io.jxcore.node.LifeCycleMonitor: start: OK
11-28 12:59:57.812  5549  5596 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-28 12:59:57.812  5549  5596 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-28 12:59:57.813  5549  5596 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-28 12:59:57.813  5549  5596 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-28 12:59:57.813  5549  5596 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-28 12:59:57.819  5549  5596 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-28 12:59:57.819  5549  5596 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-28 12:59:57.820  5549  5596 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-28 12:59:57.820  3767  3767 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-28 12:59:57.821  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 12:59:57.821  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80448c3 added. We now have 3 listener(s)
,11-28 12:59:57.823  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:59:57.823  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.823  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.823  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:57.824  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d09540 added. We now have 4 listener(s)
11-28 12:59:57.824  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:57.824  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 12:59:57.824  3767  5322 I iu.UploadsManager: num queued entries: 0
11-28 12:59:57.825  3767  5322 I iu.UploadsManager: num updated entries: 0
,11-28 12:59:57.825  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:59:57.826  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c93c79 added. We now have 4 listener(s)
,11-28 12:59:57.827  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:59:57.827  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.827  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.827  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:57.828  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb1cdbe added. We now have 5 listener(s)
11-28 12:59:57.828  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 12:59:57.828  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 12:59:57.828  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:57.828  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:57.828  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.828  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.828  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:59:57.828  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80448c3 removed from the list
11-28 12:59:57.829  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.829  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d09540 removed from the list
11-28 12:59:57.829  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:57.829  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.829  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.830  3767  3767 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-28 12:59:57.831  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.831  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.831  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.831  3767  3767 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-28 12:59:57.831  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:57.831  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.831  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.831  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d09540 not in the list
11-28 12:59:57.831  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.831  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.832  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.832  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.832  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.832  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.832  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:57.832  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.832  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb1cdbe removed from the list
11-28 12:59:57.832  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.832  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.832  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:59:57.833  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c93c79 removed from the list
11-28 12:59:57.833  5669  5669 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-28 12:59:57.833  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:59:57.833  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d58ae1f added. We now have 3 listener(s)
11-28 12:59:57.834  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:59:57.834  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.834  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.834  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:57.834  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec9c56c added. We now have 4 listener(s)
11-28 12:59:57.834  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 12:59:57.835  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 12:59:57.836  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:59:57.836  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3982735 added. We now have 4 listener(s)
11-28 12:59:57.837  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-28 12:59:57.837  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.837  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.837  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:57.837  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb907ca added. We now have 5 listener(s)
11-28 12:59:57.837  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 12:59:57.837  5669  5669 D SprintDMHelper: simOperator: 
11-28 12:59:57.837  5669  5669 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-28 12:59:57.837  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 12:59:57.837  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 12:59:57.837  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 12:59:57.837  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:59:57.837  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-28 12:59:57.841  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 12:59:57.842  3767  5871 I SystemUpdateService: active receiver: enabled
,11-28 12:59:57.845  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 12:59:57.845  5549  5596 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 12:59:57.845  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 12:59:57.848  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.848  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 12:59:57.850  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 12:59:57.850  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-28 12:59:57.850  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-28 12:59:57.850  3767  5322 I iu.SyncManager: NEXT; no task
,11-28 12:59:57.853  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.853  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 12:59:57.853  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 12:59:57.853  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 12:59:57.853  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 12:59:57.853  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.854  5549  5596 D BluetoothAdapter: STATE_ON
,11-28 12:59:57.856  5802  5830 D BtGatt.GattService: registerClient() - UUID=8bdbf774-4309-4b60-965b-464de664960b
,11-28 12:59:57.857  5802  5818 D BtGatt.GattService: onClientRegistered() - UUID=8bdbf774-4309-4b60-965b-464de664960b, clientIf=5
11-28 12:59:57.857  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 12:59:57.857   931  5858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 28 Nov 2016 17:59:57 GMT], X-Android-Received-Millis=[1480355997857], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480355997830]}
11-28 12:59:57.858   931  2892 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-28 12:59:57.858   931  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-28 12:59:57.858  5802  5841 D BtGatt.GattService: start scan with filters
11-28 12:59:57.858   931  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-28 12:59:57.859   931  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-28 12:59:57.861  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 12:59:57.861  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.861  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 12:59:57.862  5802  5821 D BtGatt.ScanManager: handling starting scan
,11-28 12:59:57.862  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.862  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 12:59:57.862  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 12:59:57.862  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.862  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 12:59:57.862  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 12:59:57.862  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.862  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.863  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.863  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.863  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 12:59:57.863  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.864  5802  5821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560b04b
,11-28 12:59:57.866  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.866  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:59:57.866  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.866  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.866  5549  5596 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 12:59:57.866  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:57.866  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 12:59:57.866  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:59:57.866  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:59:57.866  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.866  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 12:59:57.866  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 12:59:57.866  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.866  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 12:59:57.866  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 12:59:57.867  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.867  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.867  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.867  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 12:59:57.867  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.868  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:59:57.868  5802  5830 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 12:59:57.870  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-28 12:59:57.871  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:59:57.871  5802  5812 D BtGatt.GattService: stopScan() - queue size =1
11-28 12:59:57.872  5802  5818 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 12:59:57.872  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.872  5802  5830 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 12:59:57.872  5802  5821 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 12:59:57.872  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.873  3767  5871 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.873  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 12:59:57.873  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 12:59:57.878  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 12:59:57.878  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.879  5802  5818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 12:59:57.879  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.879  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.879  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:59:57.879  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.879  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.879  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.880  5802  5821 D BtGatt.ScanManager: Starting BLE batch scan
11-28 12:59:57.880  5802  5821 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 12:59:57.880  3767  5871 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-28 12:59:57.880  3767  5871 I SystemUpdateService: now status is 0 (complete)
11-28 12:59:57.880  3767  5871 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 12:59:57.880  3767  5871 I SystemUpdateService: file has been verified
,11-28 12:59:57.881  3767  5871 I SystemUpdateService: OTA package size = 21989297
,11-28 12:59:57.883  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.883  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:57.887  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-28 12:59:57.887  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.887  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:57.887  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:57.887  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:59:57.887  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.887  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:59:57.887  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.887  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:59:57.887  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:59:57.887  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 12:59:57.887  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.887  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d58ae1f removed from the list
11-28 12:59:57.888  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-28 12:59:57.888  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.888  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 12:59:57.888  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.888  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec9c56c removed from the list
11-28 12:59:57.888  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:57.888  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.888  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.888  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.888  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:59:57.888  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.888  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.888  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.890  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.890  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.890  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.890  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.890  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.891  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.891  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:57.891  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.891  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.891  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec9c56c not in the list
11-28 12:59:57.891  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.891  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.893  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.893  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.893  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.893  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.893  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:57.893  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.893  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb907ca removed from the list
11-28 12:59:57.893  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.893  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.893  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:59:57.893  5802  5818 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 12:59:57.894  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.893  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3982735 removed from the list
11-28 12:59:57.895  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:59:57.895  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc4217 added. We now have 3 listener(s)
,11-28 12:59:57.896  3767  5871 I SystemUpdateService: showing system update notification
11-28 12:59:57.896  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:59:57.896  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.897  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.897  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:57.897  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a555604 added. We now have 4 listener(s)
11-28 12:59:57.897  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:57.897  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 12:59:57.899  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:59:57.899  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a307ed added. We now have 4 listener(s)
11-28 12:59:57.899  5802  5818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 12:59:57.900  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:59:57.900  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:59:57.901  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.901  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.901  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:57.901  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d22c622 added. We now have 5 listener(s)
11-28 12:59:57.901  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 12:59:57.901  5802  5821 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 12:59:57.901  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-28 12:59:57.902  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 12:59:57.902  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 12:59:57.902  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 12:59:57.902  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:59:57.902  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-28 12:59:57.903  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 12:59:57.906  5802  5818 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 12:59:57.906  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 12:59:57.906  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.907  5549  5596 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 12:59:57.907  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 12:59:57.907  5802  5818 E BtGatt.ContextMap: Context not found for ID 5
,11-28 12:59:57.909  3767  3767 D SystemUpdateService: onDestroy
,11-28 12:59:57.912  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.913  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 12:59:57.913  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-28 12:59:57.913  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 12:59:57.913  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-28 12:59:57.913  5802  5818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 12:59:57.913  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.914  5802  5821 D BtGatt.ScanManager: stopping BLe Batch
,11-28 12:59:57.918  5802  5818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 12:59:57.918  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.919  5802  5821 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 12:59:57.920  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.920  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 12:59:57.920  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 12:59:57.920  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 12:59:57.920  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 12:59:57.920  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.920  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:59:57.922  5802  5818 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 12:59:57.923  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.923  5802  5830 D BtGatt.GattService: registerClient() - UUID=f6e305a6-c0e5-41b1-bf95-9c16c7afc3c6
11-28 12:59:57.924  5802  5818 D BtGatt.GattService: onClientRegistered() - UUID=f6e305a6-c0e5-41b1-bf95-9c16c7afc3c6, clientIf=5
,11-28 12:59:57.924  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 12:59:57.924  5802  5812 D BtGatt.GattService: start scan with filters
,11-28 12:59:57.927  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 12:59:57.927  5802  5821 D BtGatt.ScanManager: handling starting scan
11-28 12:59:57.927  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.927  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 12:59:57.927  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.927  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 12:59:57.928  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 12:59:57.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-28 12:59:57.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 12:59:57.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 12:59:57.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.928  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.928  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.929  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 12:59:57.929  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.932  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.932  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:59:57.932  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.932  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.932  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.932  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 12:59:57.932  5549  5596 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 12:59:57.932  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:57.932  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:57.932  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:57.933  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.933  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:59:57.933  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:59:57.933  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.933  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:59:57.933  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc4217 removed from the list
11-28 12:59:57.933  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.933  5802  5818 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 12:59:57.933  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.933  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a555604 removed from the list
11-28 12:59:57.933  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:57.933  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:59:57.933  5802  5821 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 12:59:57.933  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:59:57.933  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.934  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-28 12:59:57.934  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-28 12:59:57.934  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:59:57.934  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:59:57.934  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.934  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.935  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.935  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.935  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:59:57.935  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.935  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.935  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.935  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
11-28 12:59:57.935  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.936  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.936  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a555604 not in the list
11-28 12:59:57.936  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 12:59:57.936  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.936  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 12:59:57.936  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 12:59:57.936  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.936  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.936  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.936  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 12:59:57.936  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.937  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:59:57.938  5802  5813 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 12:59:57.938  5802  5818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 12:59:57.938  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.938  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 12:59:57.938  5802  5821 D BtGatt.ScanManager: Starting BLE batch scan
11-28 12:59:57.938  5802  5821 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 12:59:57.939  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:59:57.939  5802  5830 D BtGatt.GattService: stopScan() - queue size =1
11-28 12:59:57.940  5802  5812 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 12:59:57.940  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.941  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.942  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 12:59:57.942  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 12:59:57.942  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 12:59:57.943  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.944  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.944  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:59:57.944  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.944  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.945  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.945  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:57.945  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.945  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d22c622 removed from the list
11-28 12:59:57.945  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:59:57.945  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.945  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.945  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-28 12:59:57.945  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:59:57.945  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 12:59:57.945  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.945  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a307ed removed from the list
11-28 12:59:57.945  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 12:59:57.945  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 12:59:57.946  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.946  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.946  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.946  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:59:57.946  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.946  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.946  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:59:57.946  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80f5d0f added. We now have 3 listener(s)
11-28 12:59:57.947  4935  5876 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-28 12:59:57.947  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.947  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.947  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.947  5802  5818 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 12:59:57.947  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.948  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:59:57.948  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.948  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.948  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:57.948  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f619c added. We now have 4 listener(s)
,11-28 12:59:57.948  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 12:59:57.949  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 12:59:57.952  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:59:57.952  5802  5818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 12:59:57.952  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.952  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a247a5 added. We now have 4 listener(s)
11-28 12:59:57.953  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:59:57.953  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.953  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.953  5802  5821 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 12:59:57.954  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 12:59:57.954  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28af77a added. We now have 5 listener(s)
11-28 12:59:57.954  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 12:59:57.954  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 12:59:57.954  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 12:59:57.954  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 12:59:57.954  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 12:59:57.954  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-28 12:59:57.955  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 12:59:57.957  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 12:59:57.957  5549  5596 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 12:59:57.957  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 12:59:57.958  5802  5818 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 12:59:57.959  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.959  5802  5818 E BtGatt.ContextMap: Context not found for ID 5
11-28 12:59:57.960  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.960  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 12:59:57.961  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 12:59:57.961  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 12:59:57.961  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-28 12:59:57.964  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.964  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-28 12:59:57.964  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 12:59:57.964  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 12:59:57.964  5802  5818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 12:59:57.964  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 12:59:57.964  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.964  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.964  5802  5821 D BtGatt.ScanManager: stopping BLe Batch
,11-28 12:59:57.965  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:59:57.966  5802  5812 D BtGatt.GattService: registerClient() - UUID=107976e8-675e-481a-ad7b-2aa414b1aac5
11-28 12:59:57.967  5802  5818 D BtGatt.GattService: onClientRegistered() - UUID=107976e8-675e-481a-ad7b-2aa414b1aac5, clientIf=5
,11-28 12:59:57.967  5549  5559 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 12:59:57.967  5802  5841 D BtGatt.GattService: start scan with filters
,11-28 12:59:57.969  5802  5818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-28 12:59:57.969  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.969  5802  5821 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 12:59:57.969  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-28 12:59:57.969  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.969  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 12:59:57.970  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.970  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 12:59:57.970  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-28 12:59:57.970  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.970  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 12:59:57.970  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 12:59:57.970  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.970  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.971  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.971  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.971  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 12:59:57.971  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.973  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 12:59:57.974  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:59:57.974  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.974  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.974  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.974  5802  5818 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 12:59:57.974  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.975  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:57.975  5802  5821 D BtGatt.ScanManager: handling starting scan
11-28 12:59:57.976  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:57.976  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:57.976  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.976  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:59:57.976  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:59:57.976  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.976  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-28 12:59:57.976  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80f5d0f removed from the list
11-28 12:59:57.976  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.976  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f619c removed from the list
11-28 12:59:57.976  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:57.976  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:59:57.976  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:59:57.976  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.976  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-28 12:59:57.976  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-28 12:59:57.976  5549  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 12:59:57.976  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 12:59:57.976  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.977  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.977  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.977  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.977  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.978  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:57.978  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.978  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.978  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f619c not in the list
11-28 12:59:57.978  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDisc,overer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.978  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 12:59:57.978  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.979  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:59:57.979  5802  5830 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 12:59:57.979  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 12:59:57.980  5549  5596 D BluetoothAdapter: STATE_ON
11-28 12:59:57.980  5802  5812 D BtGatt.GattService: stopScan() - queue size =1
11-28 12:59:57.981  5802  5830 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.981  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-28 12:59:57.981  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 12:59:57.982  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 12:59:57.982  5802  5818 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 12:59:57.982  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:57.982  5802  5821 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 12:59:57.982  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.984  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.984  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:59:57.984  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.984  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.984  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.984  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:57.984  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.984  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28af77a removed from the list
11-28 12:59:57.984  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.984  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:59:57.984  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 12:59:57.984  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:59:57.984  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 12:59:57.984  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a247a5 removed from the list
11-28 12:59:57.984  5549  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 12:59:57.984  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.984  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 12:59:57.984  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 12:59:57.985  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.985  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.985  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.985  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:59:57.985  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 12:59:57.985  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdf07 added. We now have 3 listener(s)
11-28 12:59:57.985  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.985  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.986  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.986  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 12:59:57.986  5549  5549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 12:59:57.986  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:59:57.986  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.986  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.987  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:57.987  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c4834 added. We now have 4 listener(s)
11-28 12:59:57.987  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 12:59:57.987  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 12:59:57.988  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 12:59:57.988  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2c65d added. We now have 4 listener(s)
11-28 12:59:57.989  5802  5818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 12:59:57.989  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:59:57.989  5802  5821 D BtGatt.ScanManager: Starting BLE batch scan
11-28 12:59:57.989  5802  5821 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 12:59:57.989  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 12:59:57.989  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 12:59:57.989  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 12:59:57.989  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 12:59:57.989  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ecfbd2 added. We now have 5 listener(s)
11-28 12:59:57.989  5549  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 12:59:57.990  5549  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 12:59:57.990  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:57.990  5549  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 12:59:57.990  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.990  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.990  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:59:57.990  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdf07 removed from the list
11-28 12:59:57.990  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.990  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c4834 removed from the list
11-28 12:59:57.990  5549  5596 D io.jxcore.node.ConnectivityMonitor: stop
11-28 12:59:57.990  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.990  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.991  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.991  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.991  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.991  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:57.991  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.991  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.991  5549  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c4834 not in the list
11-28 12:59:57.991  5549  5596 D org.thaliproject.p2,p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.991  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.992  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.992  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.992  5549  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 12:59:57.993  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 12:59:57.993  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 12:59:57.993  5549  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 12:59:57.993  5549  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ecfbd2 removed from the list
11-28 12:59:57.993  5549  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 12:59:57.993  5549  5596 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 12:59:57.993  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 12:59:57.993  5549  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2c65d removed from the list
11-28 12:59:57.994  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-28 12:59:57.994  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 12:59:57.994  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 12:59:57.994  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 12:59:57.994  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-28 12:59:57.995  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 12:59:57.997  5802  5818 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 12:59:57.997  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:59:58.001  5802  5818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-28 12:59:58.002  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:58.003  5802  5821 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 12:59:58.007  5802  5818 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 12:59:58.007  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:58.007  5802  5818 E BtGatt.ContextMap: Context not found for ID 5
,11-28 12:59:58.012  5802  5818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 12:59:58.012  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:58.013  5802  5821 D BtGatt.ScanManager: stopping BLe Batch
,11-28 12:59:58.017  5802  5818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 12:59:58.017  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 12:59:58.017  5802  5821 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 12:59:58.021  5802  5818 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 12:59:58.021  5802  5818 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 12:59:58.389  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 12:59:58.447  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 12:59:58.485  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 13:00:00.166  5549  5883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 13:00:00.166  5549  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 13:00:00.505   931  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-28 13:00:01.026  5549  5883 W !!      : call onHalfStreamCopied
,11-28 13:00:01.026  5549  5883 I testCopyDataAndClose: closing input stream
,11-28 13:00:01.798  5549  5883 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 13:00:01.798  5549  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 13:00:01.798  5549  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 13:00:01.798  5549  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 13:00:01.798  5549  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 13:00:01.798  5549  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 13:00:01.798  5549  5883 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 13:00:01.799  5549  5883 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 13:00:01.799  5549  5883 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 13:00:01.799  5549  5883 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 13:00:01.799  5549  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 13:00:04.824   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:05.724   931  2892 D ConnectivityService: handlePromptUnvalidated 102
,11-28 13:00:05.825   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:05.904  5549  5885 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-28 13:00:05.904  5549  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 13:00:06.827   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:07.828   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:07.904  5549  5596 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-28 13:00:07.904  5549  5596 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 13:00:07.905  5549  5596 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-28 13:00:07.970  5549  5885 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-28 13:00:07.970  5549  5885 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-28 13:00:07.970  5549  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-28 13:00:08.043  5549  5886 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 13:00:08.043  5549  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 13:00:08.712   931  2890 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-28 13:00:08.829   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:09.670  5549  5886 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 13:00:09.670  5549  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 13:00:09.671  5549  5886 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 13:00:09.671  5549  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 13:00:09.671  5549  5886 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-28 13:00:09.671  5549  5886 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 13:00:09.671  5549  5886 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 13:00:09.671  5549  5886 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 13:00:09.671  5549  5886 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 13:00:09.671  5549  5886 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 13:00:09.671  5549  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 13:00:09.830   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-28 13:00:13.753  5549  5887 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-28 13:00:13.753  5549  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 13:00:13.753  5549  5887 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-28 13:00:13.753  5549  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 13:00:13.754  5549  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 13:00:13.754  5549  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 13:00:13.754  5549  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 13:00:13.754  5549  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-28 13:00:13.754  5549  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 13:00:13.754  5549  5887 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 13:00:13.754  5549  5887 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 13:00:13.755  5549  5887 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-28 13:00:13.755  5549  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-28 13:00:13.756  5549  5596 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-28 13:00:13.759  5549  5888 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-28 13:00:13.759  5549  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 13:00:13.760  5549  5888 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-28 13:00:13.760  5549  5888 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-28 13:00:13.760  5549  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-28 13:00:13.760  5549  5888 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-28 13:00:13.761  5549  5888 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-28 13:00:13.761  5549  5888 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-28 13:00:13.766  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-28 13:00:13.766  5549  5596 I jxcore-log: 
,11-28 13:00:13.766  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-28 13:00:13.766  5549  5596 I jxcore-log: 
11-28 13:00:13.766  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-28 13:00:13.766  5549  5596 I jxcore-log: 
11-28 13:00:13.767  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-28 13:00:13.767  5549  5596 I jxcore-log: 
11-28 13:00:13.767  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG UnitTest_app: 'Total duration:  91542'
11-28 13:00:13.767  5549  5596 I jxcore-log: 
,11-28 13:00:13.770  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-28 13:00:13.770  5549  5596 I jxcore-log: 
,11-28 13:00:13.775  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 13:00:13.775  5549  5596 I jxcore-log: 
,11-28 13:00:13.776  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 13:00:13.776  5549  5596 I jxcore-log: 
11-28 13:00:13.777  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-28 13:00:13.777  5549  5596 I jxcore-log: 
11-28 13:00:13.777  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 13:00:13.777  5549  5596 I jxcore-log: 
11-28 13:00:13.777  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 13:00:13.777  5549  5596 I jxcore-log: 
11-28 13:00:13.778  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 13:00:13.778  5549  5596 I jxcore-log: 
,11-28 13:00:13.778  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 13:00:13.778  5549  5596 I jxcore-log: 
11-28 13:00:13.778  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 13:00:13.778  5549  5596 I jxcore-log: 
11-28 13:00:13.779  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 13:00:13.779  5549  5596 I jxcore-log: 
11-28 13:00:13.779  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-28 13:00:13.779  5549  5596 I jxcore-log: 
11-28 13:00:13.779  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 13:00:13.779  5549  5596 I jxcore-log: 
,11-28 13:00:13.779  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 13:00:13.779  5549  5596 I jxcore-log: 
11-28 13:00:13.779  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 13:00:13.779  5549  5596 I jxcore-log: 
11-28 13:00:13.780  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 13:00:13.780  5549  5596 I jxcore-log: 
11-28 13:00:13.780  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 13:00:13.780  5549  5596 I jxcore-log: 
,11-28 13:00:13.780  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 13:00:13.780  5549  5596 I jxcore-log: 
11-28 13:00:13.780  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-28 13:00:13.780  5549  5596 I jxcore-log: 
11-28 13:00:13.780  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-28 13:00:13.780  5549  5596 I jxcore-log: 
11-28 13:00:13.781  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-28 13:00:13.781  5549  5596 I jxcore-log: 
11-28 13:00:13.781  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-28 13:00:13.781  5549  5596 I jxcore-log: 
11-28 13:00:13.781  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 13:00:13.781  5549  5596 I jxcore-log: 
,11-28 13:00:13.781  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-28 13:00:13.781  5549  5596 I jxcore-log: 
11-28 13:00:13.782  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-28 13:00:13.782  5549  5596 I jxcore-log: 
11-28 13:00:13.782  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-28 13:00:13.782  5549  5596 I jxcore-log: 
11-28 13:00:13.784  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-28 13:00:13.784  5549  5596 I jxcore-log: 
11-28 13:00:13.784  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-28 13:00:13.784  5549  5596 I jxcore-log: 
11-28 13:00:13.784  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 13:00:13.784  5549  5596 I jxcore-log: 
11-28 13:00:13.784  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-28 13:00:13.784  5549  5596 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-28 13:00:13.785  5549  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 13:00:13.785  5549  5596 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-28 13:00:13.785  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 13:00:13.785  5549  5596 I jxcore-log: 
11-28 13:00:13.785  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 13:00:13.785  5549  5596 I jxcore-log: 
11-28 13:00:13.785  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 13:00:13.785  5549  5596 I jxcore-log: 
11-28 13:00:13.786  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 13:00:13.786  5549  5596 I jxcore-log: 
11-28 13:00:13.786  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 13:00:13.786  5549  5596 I jxcore-log: 
,11-28 13:00:13.786  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 13:00:13.786  5549  5596 I jxcore-log: 
11-28 13:00:13.788  5549  5549 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-28 13:00:13.788  5549  5549 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-28 13:00:13.791  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-28 13:00:13.791  5549  5596 I jxcore-log: 
11-28 13:00:13.791  5549  5596 I jxcore-log: 2016-11-28 18:00:13 - WARN testUtils: 'myNameCallback not set!'
11-28 13:00:13.791  5549  5596 I jxcore-log: 
,11-28 13:00:15.843  5549  5596 I jxcore-log: 2016-11-28 18:00:15 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-28 13:00:15.843  5549  5596 I jxcore-log: 
,11-28 13:00:15.844  5549  5596 I jxcore-log: 2016-11-28 18:00:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-28 13:00:15.844  5549  5596 I jxcore-log: 
,11-28 13:00:16.193  5549  5596 I jxcore-log: 2016-11-28 18:00:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-28 13:00:16.193  5549  5596 I jxcore-log: 
,11-28 13:00:16.205  5549  5596 I jxcore-log: 2016-11-28 18:00:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-28 13:00:16.205  5549  5596 I jxcore-log: 
,11-28 13:00:17.319  5549  5596 I jxcore-log: 2016-11-28 18:00:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-28 13:00:17.319  5549  5596 I jxcore-log: 
,11-28 13:00:17.511  5549  5596 I jxcore-log: 2016-11-28 18:00:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-28 13:00:17.511  5549  5596 I jxcore-log: 
,11-28 13:00:17.516  5549  5596 I jxcore-log: 2016-11-28 18:00:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-28 13:00:17.516  5549  5596 I jxcore-log: 
,11-28 13:00:17.521  5549  5596 I jxcore-log: 2016-11-28 18:00:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-28 13:00:17.521  5549  5596 I jxcore-log: 
,11-28 13:00:18.007  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-28 13:00:18.007  5549  5596 I jxcore-log: 
,11-28 13:00:18.052  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-28 13:00:18.052  5549  5596 I jxcore-log: 
,11-28 13:00:18.066  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-28 13:00:18.066  5549  5596 I jxcore-log: 
,11-28 13:00:18.070  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-28 13:00:18.070  5549  5596 I jxcore-log: 
,11-28 13:00:18.342  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-28 13:00:18.342  5549  5596 I jxcore-log: 
,11-28 13:00:18.471  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-28 13:00:18.471  5549  5596 I jxcore-log: 
,11-28 13:00:18.850  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-28 13:00:18.850  5549  5596 I jxcore-log: 
,11-28 13:00:18.858  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-28 13:00:18.858  5549  5596 I jxcore-log: 
,11-28 13:00:18.862  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-28 13:00:18.862  5549  5596 I jxcore-log: 
,11-28 13:00:18.867  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-28 13:00:18.867  5549  5596 I jxcore-log: 
,11-28 13:00:18.873  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-28 13:00:18.873  5549  5596 I jxcore-log: 
,11-28 13:00:18.901  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-28 13:00:18.901  5549  5596 I jxcore-log: 
,11-28 13:00:18.936  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-28 13:00:18.936  5549  5596 I jxcore-log: 
,11-28 13:00:18.943  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-28 13:00:18.943  5549  5596 I jxcore-log: 
,11-28 13:00:18.950  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-28 13:00:18.950  5549  5596 I jxcore-log: 
,11-28 13:00:18.965  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-28 13:00:18.965  5549  5596 I jxcore-log: 
,11-28 13:00:18.981  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-28 13:00:18.981  5549  5596 I jxcore-log: 
,11-28 13:00:18.987  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-28 13:00:18.987  5549  5596 I jxcore-log: 
,11-28 13:00:18.992  5549  5596 I jxcore-log: 2016-11-28 18:00:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-28 13:00:18.992  5549  5596 I jxcore-log: 
,11-28 13:00:19.005  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-28 13:00:19.005  5549  5596 I jxcore-log: 
,11-28 13:00:19.022  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-28 13:00:19.022  5549  5596 I jxcore-log: 
,11-28 13:00:19.037  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-28 13:00:19.037  5549  5596 I jxcore-log: 
,11-28 13:00:19.047  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-28 13:00:19.047  5549  5596 I jxcore-log: 
,11-28 13:00:19.060  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-28 13:00:19.060  5549  5596 I jxcore-log: 
,11-28 13:00:19.070  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-28 13:00:19.070  5549  5596 I jxcore-log: 
,11-28 13:00:19.083  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-28 13:00:19.083  5549  5596 I jxcore-log: 
,11-28 13:00:19.093  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-28 13:00:19.093  5549  5596 I jxcore-log: 
,11-28 13:00:19.100  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-28 13:00:19.100  5549  5596 I jxcore-log: 
,11-28 13:00:19.122  5549  5596 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-28 13:00:19.123  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO testUtils: 'BLE multiple advertisement supported'
11-28 13:00:19.123  5549  5596 I jxcore-log: 
,11-28 13:00:19.155  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-28 13:00:19.155  5549  5596 I jxcore-log: 
,11-28 13:00:19.398  5549  5596 I jxcore-log: 2016-11-28 18:00:19 - DEBUG CoordinatedClient: 'connected to the test server'
11-28 13:00:19.398  5549  5596 I jxcore-log: 
,11-28 13:00:24.831   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:25.832   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:26.833   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:27.835   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:28.836   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:29.837   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-28 13:00:37.701   931  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 13:00:49.839   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:50.840   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:51.841   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:52.842   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:53.843   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:00:54.844   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 13:01:17.707   931  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 13:01:19.845   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-28 13:01:19.845   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 13:01:34.846   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:35.848   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:36.849   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:37.709   931  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 13:01:37.850   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:38.851   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:39.852   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-28 13:01:44.854   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:45.856   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:46.858   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:47.859   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:48.860   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:01:49.861   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-28 13:01:59.863   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:00.865   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:01.866   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:02.867   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:03.868   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:04.868   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-28 13:02:17.713   931  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 13:02:19.870   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:20.871   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:21.872   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:22.873   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:23.874   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:24.875   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-28 13:02:37.717   931  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 13:02:44.877   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:45.878   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:46.879   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:47.880   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:48.881   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:02:49.882   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 13:02:57.721   931  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 13:03:14.883   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-28 13:03:14.883   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 13:03:21.454  5856  5856 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 13:03:34.884   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:03:35.886   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:03:36.888   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:03:37.726   931  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 13:03:37.889   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:03:38.006  5549  5596 I jxcore-log: 2016-11-28 18:03:38 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-28 13:03:38.006  5549  5596 I jxcore-log: 
,11-28 13:03:38.233  5549  5596 I jxcore-log: 2016-11-28 18:03:38 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 13:03:38.233  5549  5596 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 13:03:38.233  5549  5596 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 13:03:38.233  5549  5596 I jxcore-log: emit@events.js:82:1
11-28 13:03:38.233  5549  5596 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 13:03:38.233  5549  5596 I jxcore-log: emit@events.js:82:1''
11-28 13:03:38.233  5549  5596 I jxcore-log: 
,11-28 13:03:38.235  5549  5596 I jxcore-log: 2016-11-28 18:03:38 - DEBUG CoordinatedClient: 'test client failed'
11-28 13:03:38.235  5549  5596 I jxcore-log: 
,11-28 13:03:38.248  5549  5596 I jxcore-log: 2016-11-28 18:03:38 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 13:03:38.248  5549  5596 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 13:03:38.248  5549  5596 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 13:03:38.248  5549  5596 I jxcore-log: emit@events.js:82:1
11-28 13:03:38.248  5549  5596 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 13:03:38.248  5549  5596 I jxcore-log: emit@events.js:82:1''
11-28 13:03:38.248  5549  5596 I jxcore-log: 
,11-28 13:03:38.250  5549  5596 I jxcore-log: 2016-11-28 18:03:38 - DEBUG CoordinatedClient: 'test client failed'
11-28 13:03:38.250  5549  5596 I jxcore-log: 
,11-28 13:03:38.255  5549  5596 I jxcore-log: 2016-11-28 18:03:38 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 13:03:38.255  5549  5596 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 13:03:38.255  5549  5596 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 13:03:38.255  5549  5596 I jxcore-log: emit@events.js:82:1
11-28 13:03:38.255  5549  5596 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 13:03:38.255  5549  5596 I jxcore-log: emit@events.js:82:1''
11-28 13:03:38.255  5549  5596 I jxcore-log: 
,11-28 13:03:38.256  5549  5596 I jxcore-log: 2016-11-28 18:03:38 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-28 13:03:38.256  5549  5596 I jxcore-log: 
,11-28 13:03:38.805  5900  5900 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-28 13:03:38.829  5900  5900 D AndroidRuntime: CheckJNI is OFF
,11-28 13:03:38.859  5900  5900 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-28 13:03:38.890   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 13:03:38.907  5900  5900 I Radio-JNI: register_android_hardware_Radio DONE
,11-28 13:03:38.926  5900  5900 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-28 13:03:38.943   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-28 13:03:38.943   931   944 I ActivityManager: Killing 5549:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-28 13:03:39.046   931   941 D GraphicsStats: Buffer count: 2
11-28 13:03:39.046   931  3766 I WindowState: WIN DEATH: Window{2da1a84 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-28 13:03:39.047   931  2891 D WifiService: Client connection lost with reason: 4
,11-28 13:03:39.081   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-28 13:03:39.082   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-28 13:03:39.083   931   944 E ActivityManager: Failure starting process com.test.thalitest
11-28 13:03:39.083   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-28 13:03:39.083   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 13:03:39.083   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-28 13:03:39.083   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 13:03:39.083   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-28 13:03:39.083   931   944 I ActivityManager:   Force finishing activity ActivityRecord{b918951 u0 com.test.thalitest/.MainActivity t10}
11-28 13:03:39.084   931   954 I art     : Starting a blocking GC Explicit
,11-28 13:03:39.097   931  3123 W ActivityManager: Spurious death for ProcessRecord{734c937 0:com.test.thalitest/u0a77}, curProc for 5549: null
,11-28 13:03:39.100   931   949 W WindowManager: Attempted to add application window with unknown token Token{a7455b6 ActivityRecord{b918951 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-28 13:03:39.101   931   949 W WindowManager: Token{a7455b6 ActivityRecord{b918951 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{a7455b6 ActivityRecord{b918951 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-28 13:03:39.101   931   949 W WindowManager: view not successfully added to wm, removing view
11-28 13:03:39.101   931   949 W WindowManager: Exception when adding starting window
11-28 13:03:39.101   931   949 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{555260e V.E...... R.....ID 0,0-0,0} not attached to window manager
11-28 13:03:39.101   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-28 13:03:39.101   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-28 13:03:39.101   931   949 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-28 13:03:39.101   931   949 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-28 13:03:39.101   931   949 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-28 13:03:39.101   931   949 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 13:03:39.101   931   949 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-28 13:03:39.101   931   949 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 13:03:39.101   931   949 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-28 13:03:39.181   931   954 I art     : Explicit concurrent mark sweep GC freed 116295(8MB) AllocSpace objects, 74(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.699ms total 96.147ms
,11-28 13:03:39.201   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-28 13:03:39.205  5900  5900 I art     : System.exit called, status: 0
11-28 13:03:39.205  5900  5900 I AndroidRuntime: VM exiting with result code 0.
,11-28 13:03:39.210   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-28 13:03:39.225   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-28 13:03:39.228  3584  3584 I Keyboard.Facilitator: resetDictionaries() : en_US
11-28 13:03:39.230  5802  5802 D BluetoothMapAppObserver: onReceive
,11-28 13:03:39.230  5802  5802 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-28 13:03:39.232   931  2824 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-28 13:03:39.234  3999  4110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-28 13:03:39.243  3584  5911 I Keyboard.Facilitator.DecoderInitializer: run()
,11-28 13:03:39.255  3584  5911 I Decoder : createOrResetDecoder
,11-28 13:03:39.263  3317  5913 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-28 13:03:39.300  3707  3707 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-28 13:03:39.315   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-28 13:03:39.316  3501  3501 I ConfigService: onCreate
,11-28 13:03:39.336  3584  5911 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-28 13:03:39.338  3501  3501 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-28 13:03:39.339  3501  3501 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-28 13:03:39.343    17    17 W kworker/2:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 13:03:39.350    17    17 W kworker/2:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 13:03:39.360  3767  5919 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-28 13:03:39.360  3767  5919 D AccountUtils: Clearing selected account for com.test.thalitest
,11-28 13:03:39.377    17    17 W kworker/2:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 13:03:39.404  3317  5913 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
11-28 13:03:39.405  3317  5913 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-28 13:03:39.405  3317  5913 E AndroidRuntime: Process: android.process.acore, PID: 3317
11-28 13:03:39.405  3317  5913 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 13:03:39.405  3317  5913 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-28 13:03:39.424  3767  5919 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-28 13:03:39.450  3317  5913 I Process : Sending signal. PID: 3317 SIG: 9
,11-28 13:03:39.452   931  5924 E DropBoxManagerService: Can't write: system_app_crash
11-28 13:03:39.452   931  5924 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 13:03:39.452   931  5924 E DropBoxManagerService: 	... 5 more
,11-28 13:03:39.452  3767  5919 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-28 13:03:39.452  3767  5919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 13:03:39.453  3767  5919 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-28 13:03:39.453  3767  5919 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-28 13:03:39.454  3767  5919 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-28 13:03:39.534  3767  5926 I GMPM-SVC: App measurement is starting up
,11-28 13:03:39.540  3767  5926 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-28 13:03:39.541  3767  5926 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-28 13:03:39.562   931  3766 I ActivityManager: Process android.process.acore (pid 3317) has died
,11-28 13:03:39.563   931  3766 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms

```
