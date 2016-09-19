#### Test 8560660433ca4f7_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-19 11:06:10.296  3588  5614 I VacuumService: Vacuum at: now=1474297570296 tag=VacuumService
,09-19 11:06:10.328  3588  5617 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
09-19 11:06:10.366  3588  5615 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
09-19 11:06:10.369  3588  5615 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
09-19 11:06:10.406  3588  5615 W Uploader:  no longer exists, so no auth token.
09-19 11:06:10.412  3588  5617 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
09-19 11:06:10.693  5620  5620 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-19 11:06:10.698  3588  5619 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
09-19 11:06:10.699  5620  5620 D AndroidRuntime: CheckJNI is OFF
09-19 11:06:10.722  5620  5620 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-19 11:06:10.751  5620  5620 I Radio-JNI: register_android_hardware_Radio DONE
09-19 11:06:10.766  5620  5620 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-19 11:06:10.772   924   934 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-19 11:06:10.775  3588  5617 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
09-19 11:06:10.822   924   934 I ActivityManager: Start proc 5632:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-19 11:06:10.831  5620  5620 D AndroidRuntime: Shutting down VM
,09-19 11:06:11.158   924   935 I WindowManager: Screenshot max retries 4 of Token{204518 ActivityRecord{6f7f0fb u0 com.test.thalitest/.MainActivity t4}} appWin=Window{bad8473 u0 Starting com.test.thalitest} drawState=2
,09-19 11:06:11.232  5632  5632 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-19 11:06:11.241  3588  5619 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 11:06:11.262  5632  5632 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-19 11:06:11.299  3588  5615 W Uploader:  no longer exists, so no auth token.
,09-19 11:06:11.306  3588  5617 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 11:06:11.321  5632  5632 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 619-674)
,09-19 11:06:11.322  5632  5632 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-19 11:06:11.354  5632  5632 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c5a7eac}
,09-19 11:06:11.354  5632  5632 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-19 11:06:11.354  5632  5632 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-19 11:06:11.360  5632  5632 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-19 11:06:11.361  5632  5632 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-19 11:06:11.371  3588  5619 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 11:06:11.411  5632  5632 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-19 11:06:11.429  5632  5632 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-19 11:06:11.429  5632  5632 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-19 11:06:11.429  5632  5632 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-19 11:06:11.429  5632  5632 I Adreno  : Build Date                       : 12/06/15
09-19 11:06:11.429  5632  5632 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
,09-19 11:06:11.429  5632  5632 I Adreno  : Local Branch                     : mybranch17112971
09-19 11:06:11.429  5632  5632 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-19 11:06:11.429  5632  5632 I Adreno  : Remote Branch                    : NONE
09-19 11:06:11.429  5632  5632 I Adreno  : Reconstruct Branch               : NOTHING
,09-19 11:06:11.472   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4814806:true
,09-19 11:06:11.501   405   405 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33924]" dev="sockfs" ino=33924 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-19 11:06:11.501   405   405 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33924]" dev="sockfs" ino=33924 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-19 11:06:11.517  5632  5632 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-19 11:06:11.526  5632  5632 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-19 11:06:11.544   405   405 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32308]" dev="sockfs" ino=32308 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-19 11:06:11.544   405   405 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32308]" dev="sockfs" ino=32308 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 11:06:11.548  5632  5669 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-19 11:06:11.547  3203  3203 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33935]" dev="sockfs" ino=33935 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 11:06:11.547  3203  3203 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33935]" dev="sockfs" ino=33935 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 11:06:11.554  5632  5656 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-19 11:06:11.579  5632  5669 I OpenGLRenderer: Initialized EGL, version 1.4
,09-19 11:06:11.647   924   942 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +485ms (total +845ms)
,09-19 11:06:11.689  5632  5632 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5632
,09-19 11:06:11.821  5632  5632 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-19 11:06:11.916  5632  5671 D jxcore_app_log: JniHelper::setJavaVM(0xf54bc000), pthread_self() = -580388560
,09-19 11:06:11.920  5632  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-19 11:06:11.920  5632  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-19 11:06:11.920  5632  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-19 11:06:11.920  5632  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-19 11:06:11.920  5632  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-19 11:06:11.921  5632  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0a4822 added. We now have 1 listener(s)
09-19 11:06:11.923  5632  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-19 11:06:11.923  5632  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-19 11:06:11.924  5632  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-19 11:06:11.924  5632  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-19 11:06:11.926  5632  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dc1fe9 added. We now have 1 listener(s)
,09-19 11:06:11.926  5632  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 11:06:11.930   924  2978 D WifiService: New client listening to asynchronous messages
,09-19 11:06:11.931  5632  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 11:06:11.931  5632  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-19 11:06:11.931  5632  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-19 11:06:11.931  5632  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-19 11:06:11.931  5632  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-19 11:06:11.933  5632  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:11.933  5632  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-19 11:06:11.938  5632  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-19 11:06:11.938  5632  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:11.938  5632  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:11.938  5632  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:11.938  5632  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:11.938  5632  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:11.938  5632  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:11.938  5632  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 11:06:11.938  5632  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 11:06:11.938  5632  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-19 11:06:11.938  5632  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 11:06:11.938  5632  5671 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-19 11:06:12.006  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:12.009  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:12.012  5632  5632 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-19 11:06:12.228  5632  5641 I art     : Background sticky concurrent mark sweep GC freed 86825(8MB) AllocSpace objects, 18(1676KB) LOS objects, 21% free, 25MB/32MB, paused 1.900ms total 100.558ms
,09-19 11:06:12.305  5632  5678 W jxcore-log: Initializing JXcore engine
09-19 11:06:12.305  5632  5678 W jxcore-log: JXcore engine is ready
,09-19 11:06:12.324  5678  5678 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12464 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-19 11:06:12.324  5678  5678 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15413]" dev="sockfs" ino=15413 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-19 11:06:12.324  5678  5678 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-19 11:06:12.324  5678  5678 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33089]" dev="sockfs" ino=33089 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-19 11:06:12.336  5632  5678 W jxcore-log: Starting JXcore engine
,09-19 11:06:12.387  5632  5678 W jxcore-log: Platform android
09-19 11:06:12.387  5632  5678 W jxcore-log: 
,09-19 11:06:12.387  5632  5678 W jxcore-log: Process ARCH arm
09-19 11:06:12.387  5632  5678 W jxcore-log: 
,09-19 11:06:12.511  5632  5678 I jxcore-log: JXcore Cordova bridge is ready!
09-19 11:06:12.511  5632  5678 I jxcore-log: 
,09-19 11:06:12.511  5632  5678 W jxcore-log: JXcore engine is started
,09-19 11:06:12.526  5632  5671 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-19 11:06:12.532  5632  5632 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-19 11:06:14.945   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:15.431   924  5383 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-19 11:06:15.945   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:16.946   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:17.947   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:18.948   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:19.949   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 11:06:22.546  5632  5678 I jxcore-log: 2016-09-19 15:06:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-19 11:06:22.546  5632  5678 I jxcore-log: 
,09-19 11:06:22.548  5632  5678 I jxcore-log: 2016-09-19 15:06:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-19 11:06:22.548  5632  5678 I jxcore-log: 
,09-19 11:06:22.552  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:22.552  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:22.552  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:22.552  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:22.552  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:22.552  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:22.552  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 11:06:22.552  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 11:06:22.553  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 11:06:22.555  5632  5678 I jxcore-log: 2016-09-19 15:06:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-19 11:06:22.555  5632  5678 I jxcore-log: 
,09-19 11:06:22.557  5632  5678 I jxcore-log: 2016-09-19 15:06:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-19 11:06:22.557  5632  5678 I jxcore-log: 
,09-19 11:06:22.816  5632  5678 D ExecuteNativeTests: Running unit tests
,09-19 11:06:22.854  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-19 11:06:22.854  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc added. We now have 2 listener(s)
,09-19 11:06:22.855  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-19 11:06:22.855  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:22.855  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:22.855  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 11:06:22.855  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 added. We now have 2 listener(s)
09-19 11:06:22.855  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:22.855  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 11:06:22.857  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:22.859  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:22.859  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:22.859  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:22.859  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:22.859  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:22.859  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:22.859  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 11:06:22.859  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 11:06:22.860  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:22.860  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 11:06:22.861  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-19 11:06:22.861  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 11:06:22.861  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 11:06:22.862  5632  5678 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-19 11:06:22.862  5632  5678 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-19 11:06:22.862  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-19 11:06:22.862  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 11:06:22.862  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 11:06:22.862  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:22.863  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:22.863  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-19 11:06:22.863  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:22.863  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.863  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:22.863  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:22.863  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc removed from the list
09-19 11:06:22.863  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 11:06:22.863  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 removed from the list
09-19 11:06:22.865  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:22.872  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:22.873  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:22.873  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:22.874  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.874  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:22.874  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:22.874  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:22.874  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 11:06:22.874  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:22.875  5632  5678 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-19 11:06:22.875  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 11:06:22.875  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:22.875  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:22.875  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:22.876  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.876  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:22.876  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:22.876  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:22.876  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:22.876  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:22.876  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.876  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:22.876  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.876  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:22.876  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:22.876  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:22.876  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:22.876  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-19 11:06:22.879  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-19 11:06:22.880  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-19 11:06:22.880  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:22.880  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:22.880  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:22.880  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:22.880  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 11:06:22.880  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:22.880  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:22.880  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:22.880  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:22.880  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 11:06:22.880  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.880  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:22.880  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.880  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:22.881  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:22.881  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:22.881  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 11:06:22.881  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:22.881  5632  5678 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-19 11:06:22.882  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:22.884  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:22.884  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:22.884  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:22.884  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:22.884  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:22.884  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:22.884  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 11:06:22.884  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 11:06:22.885  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:22.885  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 11:06:22.885  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 11:06:22.885  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 11:06:22.885  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 11:06:22.885  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:22.885  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:22.887  5632  5678 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:22.887  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-19 11:06:22.889  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:22.892  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-19 11:06:22.893  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:22.894  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 11:06:22.894  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 11:06:22.895  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-19 11:06:22.896  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-19 11:06:22.896  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-19 11:06:22.897  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 11:06:22.897  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-19 11:06:22.897  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:22.900  4594  4608 D BtGatt.GattService: registerClient() - UUID=1095bbfb-3252-49b2-9c9d-46bb62b990d6
,09-19 11:06:22.902  4594  4667 D BtGatt.GattService: onClientRegistered() - UUID=1095bbfb-3252-49b2-9c9d-46bb62b990d6, clientIf=5
,09-19 11:06:22.903  5632  5643 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-19 11:06:22.905  4594  4805 D BtGatt.GattService: start scan with filters
,09-19 11:06:22.911  4594  4672 D BtGatt.ScanManager: handling starting scan
,09-19 11:06:22.911  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-19 11:06:22.911  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-19 11:06:22.911  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-19 11:06:22.912  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-19 11:06:22.912  4594  4672 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:22.913  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-19 11:06:22.914  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 11:06:22.914  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-19 11:06:22.914  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-19 11:06:22.915  5632  5678 I io.jxcore.node.ConnectionHelper: start: OK
,09-19 11:06:22.916  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:22.916  5632  5678 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-19 11:06:22.916  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:22.917  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 11:06:22.917  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.917  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 11:06:22.917  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 11:06:22.917  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 11:06:22.917  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 11:06:22.917  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 11:06:22.917  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 11:06:22.917  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-19 11:06:22.917  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:22.918  4594  4837 D BtGatt.GattService: stopScan() - queue size =1
09-19 11:06:22.918  4594  4607 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-19 11:06:22.918  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:22.918  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-19 11:06:22.918  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-19 11:06:22.918  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-19 11:06:22.918  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 11:06:22.919  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:22.919  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:22.919  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 11:06:22.919  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:22.919  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:22.920  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:22.920  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.920  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 11:06:22.920  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:22.920  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:22.920  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:22.920  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:22.920  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:22.920  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:22.920  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:22.920  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:22.920  5632  5678 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-19 11:06:22.920  4594  4667 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-19 11:06:22.920  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:22.921  4594  4672 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-19 11:06:22.922  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:22.925  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:22.925  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:22.925  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:22.925  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:22.925  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:22.925  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:22.925  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 11:06:22.925  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 11:06:22.925  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:22.926  5632  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-19 11:06:22.927  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:22.927  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 11:06:22.927  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-19 11:06:22.927  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 11:06:22.928  4594  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-19 11:06:22.928  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:22.928  4594  4672 D BtGatt.ScanManager: Starting BLE batch scan
09-19 11:06:22.928  4594  4672 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-19 11:06:22.931  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 11:06:22.932  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 11:06:22.932  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 11:06:22.932  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:22.933  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:22.935  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:22.935  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:22.935  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 11:06:22.938  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:22.938  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-19 11:06:22.938  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:22.939  4594  4667 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-19 11:06:22.939  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:22.940  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-19 11:06:22.941  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 11:06:22.941  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:22.941  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:22.943  5632  5678 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-19 11:06:22.944  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:22.945  4594  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-19 11:06:22.945  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:22.946  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:22.946  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-19 11:06:22.946  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 11:06:22.946  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-19 11:06:22.947  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:22.948  4594  4608 D BtGatt.GattService: registerClient() - UUID=6b308e71-d4f3-42af-b409-67905658f321
,09-19 11:06:22.948  4594  4667 D BtGatt.GattService: onClientRegistered() - UUID=6b308e71-d4f3-42af-b409-67905658f321, clientIf=5
09-19 11:06:22.948  5632  5642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-19 11:06:22.949  4594  4837 D BtGatt.GattService: start scan with filters
09-19 11:06:22.951  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-19 11:06:22.951  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-19 11:06:22.951  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-19 11:06:22.951  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-19 11:06:22.952  4594  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-19 11:06:22.952  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:22.952  4594  4672 D BtGatt.ScanManager: stopping BLe Batch
,09-19 11:06:22.952  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 11:06:22.952  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 11:06:22.952  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 11:06:22.953  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-19 11:06:22.956  5632  5678 I io.jxcore.node.ConnectionHelper: start: OK
,09-19 11:06:22.956  4594  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-19 11:06:22.956  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 11:06:22.956  4594  4672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-19 11:06:22.956  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:22.957  5632  5678 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-19 11:06:22.957  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:22.957  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 11:06:22.957  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.957  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 11:06:22.957  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 11:06:22.957  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 11:06:22.957  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-19 11:06:22.957  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 11:06:22.957  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 11:06:22.957  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-19 11:06:22.957  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:22.957  4594  4607 D BtGatt.GattService: stopScan() - queue size =0
09-19 11:06:22.958  4594  4805 D BtGatt.GattService: unregisterClient() - clientIf=5
09-19 11:06:22.958  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:22.958  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-19 11:06:22.958  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-19 11:06:22.958  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-19 11:06:22.958  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 11:06:22.958  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:22.958  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:22.958  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 11:06:22.958  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:22.959  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:22.959  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-19 11:06:22.959  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.959  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:22.959  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:22.959  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:22.959  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:22.959  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:22.959  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:22.959  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:22.959  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:22.959  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 11:06:22.962  4594  4667 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-19 11:06:22.962  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 11:06:22.963  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-19 11:06:22.963  5632  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-19 11:06:22.963  4594  4672 D BtGatt.ScanManager: handling starting scan
,09-19 11:06:22.966  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 11:06:22.967  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 11:06:22.967  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 11:06:22.967  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:22.967  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:22.969  4594  4667 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-19 11:06:22.969  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:22.969  4594  4672 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-19 11:06:22.969  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:22.970  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:22.970  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 11:06:22.973  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:22.973  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-19 11:06:22.973  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:22.975  4594  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-19 11:06:22.975  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:22.975  4594  4672 D BtGatt.ScanManager: Starting BLE batch scan
09-19 11:06:22.975  4594  4672 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-19 11:06:22.976  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:22.976  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:22.976  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:22.977  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:22.977  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:22.977  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 11:06:22.978  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:22.978  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:22.978  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:22.978  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 11:06:22.978  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:22.978  5632  5678 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-19 11:06:22.980  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:22.983  4594  4667 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-19 11:06:22.983  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:22.983  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:22.983  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:22.983  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:22.983  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:22.983  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:22.983  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 11:06:22.983  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 11:06:22.983  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 11:06:22.986  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 11:06:22.986  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 11:06:22.986  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-19 11:06:22.986  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 11:06:22.986  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 11:06:22.986  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:22.986  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 11:06:22.988  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:22.990  4594  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-19 11:06:22.990  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:22.990  5632  5678 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-19 11:06:22.991  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:22.995  4594  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-19 11:06:22.995  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:22.995  4594  4672 D BtGatt.ScanManager: stopping BLe Batch
09-19 11:06:22.995  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-19 11:06:22.996  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 11:06:22.996  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-19 11:06:22.996  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:22.998  4594  4837 D BtGatt.GattService: registerClient() - UUID=08ec1815-f588-4b34-9c50-ff1c6a92249e
09-19 11:06:22.999  4594  4667 D BtGatt.GattService: onClientRegistered() - UUID=08ec1815-f588-4b34-9c50-ff1c6a92249e, clientIf=5
09-19 11:06:22.999  5632  5642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-19 11:06:23.000  4594  4608 D BtGatt.GattService: start scan with filters
09-19 11:06:23.000  4594  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-19 11:06:23.000  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 11:06:23.000  4594  4672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-19 11:06:23.002  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-19 11:06:23.002  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-19 11:06:23.002  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-19 11:06:23.002  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-19 11:06:23.004  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 11:06:23.004  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 11:06:23.004  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 11:06:23.005  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-19 11:06:23.005  4594  4667 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-19 11:06:23.005  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 11:06:23.006  4594  4672 D BtGatt.ScanManager: handling starting scan
09-19 11:06:23.007  5632  5678 I io.jxcore.node.ConnectionHelper: start: OK
09-19 11:06:23.007  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.007  5632  5678 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-19 11:06:23.007  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.007  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 11:06:23.007  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.007  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 11:06:23.007  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 11:06:23.007  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 11:06:23.007  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 11:06:23.007  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 11:06:23.007  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 11:06:23.007  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-19 11:06:23.008  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.008  4594  4608 D BtGatt.GattService: stopScan() - queue size =1
,09-19 11:06:23.009  4594  4835 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-19 11:06:23.009  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.009  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-19 11:06:23.009  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-19 11:06:23.009  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-19 11:06:23.009  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 11:06:23.010  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:23.010  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.010  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 11:06:23.010  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-19 11:06:23.011  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:23.011  4594  4667 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-19 11:06:23.011  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:23.012  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:23.012  4594  4672 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-19 11:06:23.012  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:23.012  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:23.012  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.012  5632  5678 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-19 11:06:23.012  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 11:06:23.012  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.012  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.012  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.012  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 11:06:23.012  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.012  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.012  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.012  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.012  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 11:06:23.015  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:23.015  5632  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-19 11:06:23.016  4594  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-19 11:06:23.016  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:23.016  4594  4672 D BtGatt.ScanManager: Starting BLE batch scan
09-19 11:06:23.016  4594  4672 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-19 11:06:23.018  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 11:06:23.019  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 11:06:23.019  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 11:06:23.019  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:23.020  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:23.023  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.023  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:23.024  4594  4667 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-19 11:06:23.024  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.024  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:23.024  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.024  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 11:06:23.025  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:23.025  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.025  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.025  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.025  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:23.025  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.025  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:23.025  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:23.025  5632  5678 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-19 11:06:23.026  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.026  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.026  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.026  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.026  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.026  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:23.026  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
,09-19 11:06:23.026  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.026  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.026  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.026  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.026  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:23.027  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:23.027  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:23.028  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.029  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.029  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:23.029  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:23.030  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-19 11:06:23.030  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.030  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:23.031  4594  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-19 11:06:23.031  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:23.031  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.031  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.031  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.031  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.031  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.032  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-19 11:06:23.032  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.032  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.033  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-19 11:06:23.033  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.033  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.033  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.033  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.033  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.033  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.033  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.033  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.033  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.033  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 11:06:23.033  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.034  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.034  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.034  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:23.034  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.034  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.034  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.034  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.035  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.035  5632  5678 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-19 11:06:23.035  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.035  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.035  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.035  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.035  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.035  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.035  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.036  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.036  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
,09-19 11:06:23.036  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.036  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.036  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.036  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.036  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.036  4594  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-19 11:06:23.036  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:23.036  4594  4672 D BtGatt.ScanManager: stopping BLe Batch
09-19 11:06:23.037  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.037  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.037  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 11:06:23.038  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.038  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.038  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.038  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.038  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.039  5632  5678 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-19 11:06:23.039  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.039  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.039  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-19 11:06:23.039  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.039  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.039  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.039  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.039  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.039  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.039  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.039  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.039  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.039  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.039  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.041  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.041  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.041  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:23.041  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.042  5632  5678 D BluetoothLeScanner: could not find callback wrapper
,09-19 11:06:23.042  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.042  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.042  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.042  4594  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-19 11:06:23.042  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:23.042  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-19 11:06:23.043  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 11:06:23.043  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-19 11:06:23.043  4594  4672 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-19 11:06:23.043  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 11:06:23.043  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-19 11:06:23.043  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-19 11:06:23.044  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 11:06:23.044  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.044  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.044  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.044  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.044  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.044  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.045  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.045  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.045  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.045  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 11:06:23.045  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.045  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.045  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.045  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.046  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.046  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:23.046  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.046  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.046  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.046  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 11:06:23.046  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.047  5632  5678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-19 11:06:23.047  5632  5678 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-19 11:06:23.047  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-19 11:06:23.048  4594  4667 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-19 11:06:23.048  4594  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:23.049  5632  5678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-19 11:06:23.049  5632  5678 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-19 11:06:23.049  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-19 11:06:23.049  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-19 11:06:23.049  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-19 11:06:23.049  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-19 11:06:23.049  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-19 11:06:23.049  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-19 11:06:23.049  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-19 11:06:23.050  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-19 11:06:23.051  5632  5678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-19 11:06:23.051  5632  5678 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-19 11:06:23.051  5632  5678 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-19 11:06:23.051  5632  5678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-19 11:06:23.051  5632  5678 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-19 11:06:23.051  5632  5678 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-19 11:06:23.051  5632  5678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-19 11:06:23.051  5632  5678 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-19 11:06:23.051  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-19 11:06:23.054  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-19 11:06:23.055  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-19 11:06:23.055  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-19 11:06:23.056  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-19 11:06:23.056  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-19 11:06:23.056  5632  5678 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-19 11:06:23.056  5632  5678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-19 11:06:23.056  5632  5678 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-19 11:06:23.056  5632  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-19 11:06:23.057  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.057  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.057  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.057  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-19 11:06:23.057  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.057  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.057  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-19 11:06:23.059  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.059  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.059  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.059  5632  5680 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 11:06:23.059  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 11:06:23.059  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.059  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.059  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.059  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.060  5632  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-19 11:06:23.060  5632  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-19 11:06:23.060  5632  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
,09-19 11:06:23.060  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-19 11:06:23.060  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.057  4835  4835 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31219]" dev="sockfs" ino=31219 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-19 11:06:23.060  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:23.061  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:23.061  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.061  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.061  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.061  5632  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-19 11:06:23.061  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.062  5632  5678 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-19 11:06:23.057  4835  4835 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31219]" dev="sockfs" ino=31219 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-19 11:06:23.062  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.062  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.062  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-19 11:06:23.062  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.062  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 11:06:23.063  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:23.063  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.063  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.063  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.063  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.063  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 11:06:23.063  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.063  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.063  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.064  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.064  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.064  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:23.064  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:23.065  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.065  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.065  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.065  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.065  5632  5678 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-19 11:06:23.065  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.066  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 11:06:23.066  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.066  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.066  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.066  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.066  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.066  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.066  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.066  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.066  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.066  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.066  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.066  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.067  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-19 11:06:23.067  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.067  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:23.068  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.068  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.068  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.068  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.068  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.068  5632  5678 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-19 11:06:23.068  5632  5678 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-19 11:06:23.069  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-19 11:06:23.069  5632  5678 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-19 11:06:23.069  5632  5678 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-19 11:06:23.069  5632  5678 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-19 11:06:23.069  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-19 11:06:23.069  5632  5678 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-19 11:06:23.069  5632  5678 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-19 11:06:23.069  5632  5678 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-19 11:06:23.069  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-19 11:06:23.069  5632  5678 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-19 11:06:23.069  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.069  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.069  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.069  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-19 11:06:23.069  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.069  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.069  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.069  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.069  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.069  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.069  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.070  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.070  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.070  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.071  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.071  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.071  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:23.072  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:23.072  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.072  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.072  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.072  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.072  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.072  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.072  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.073  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.073  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.073  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.073  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.073  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 11:06:23.073  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.073  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.073  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.073  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.073  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.073  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.073  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.073  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.073  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.073  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.073  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.073  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 11:06:23.073  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.073  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.074  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.074  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.074  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.074  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.074  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.074  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.074  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.075  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.075  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.075  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:23.075  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:23.075  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.075  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.075  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.075  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.077  5632  5678 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-19 11:06:23.077  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:23.078  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-19 11:06:23.079  5632  5678 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-19 11:06:23.079  5632  5678 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-19 11:06:23.079  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-19 11:06:23.079  5632  5632 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-19 11:06:23.079  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 11:06:23.080  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.080  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-19 11:06:23.080  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-19 11:06:23.080  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-19 11:06:23.080  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.080  5632  5682 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 11:06:23.080  5632  5678 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-19 11:06:23.080  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.080  5632  5632 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-19 11:06:23.080  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.080  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 11:06:23.080  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 11:06:23.080  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 11:06:23.080  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 11:06:23.081  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.081  5632  5678 D BluetoothLeScanner: could not find callback wrapper
,09-19 11:06:23.081  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.081  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.081  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 11:06:23.077  4607  4607 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32332]" dev="sockfs" ino=32332 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-19 11:06:23.082  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.082  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.082  5632  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-19 11:06:23.077  4607  4607 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32332]" dev="sockfs" ino=32332 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-19 11:06:23.082  5632  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-19 11:06:23.082  5632  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-19 11:06:23.082  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:23.083  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.083  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:23.083  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:23.083  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.083  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:23.083  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.083  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.083  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.083  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.083  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:23.083  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.083  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.083  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
,09-19 11:06:23.084  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.084  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.084  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:23.085  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:23.085  5632  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-19 11:06:23.088  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 11:06:23.088  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 11:06:23.089  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 11:06:23.089  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:23.089  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:23.090  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:23.090  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:23.090  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 11:06:23.092  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:23.092  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:23.093  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.094  5632  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-19 11:06:23.095  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:23.095  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.095  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:23.096  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.096  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.096  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 11:06:23.097  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:23.097  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.097  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.097  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.097  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
,09-19 11:06:23.098  5632  5678 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-19 11:06:23.098  5632  5678 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-19 11:06:23.099  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-19 11:06:23.099  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 11:06:23.099  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.099  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 11:06:23.099  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.099  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.099  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.099  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.100  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.100  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.100  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.100  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.100  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.100  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.100  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.100  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:23.101  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.101  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.102  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 11:06:23.102  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.102  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.102  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.102  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 11:06:23.103  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
,09-19 11:06:23.106  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.106  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.106  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-19 11:06:23.107  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.107  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.107  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.107  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.107  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.107  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.107  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.107  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.107  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.107  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.107  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:23.108  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.109  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:23.109  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 11:06:23.109  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:23.109  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.110  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.110  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.110  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
,09-19 11:06:23.111  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:23.111  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:23.111  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:23.111  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:23.111  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.111  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.111  5632  5678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b40dcc not in the list
09-19 11:06:23.111  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.111  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
09-19 11:06:23.111  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:23.111  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:23.112  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.112  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 11:06:23.112  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:23.113  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:23.113  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-19 11:06:23.113  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 11:06:23.114  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:23.114  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:23.114  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:23.114  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:23.114  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a63815 not in the list
,09-19 11:06:23.115  5632  5678 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-19 11:06:23.115  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-19 11:06:23.115  5632  5678 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-19 11:06:23.115  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-19 11:06:23.115  5632  5678 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-19 11:06:23.116  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-19 11:06:23.117  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-19 11:06:23.117  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-19 11:06:23.118  5632  5678 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-19 11:06:23.118  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-19 11:06:23.118  5632  5678 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-19 11:06:23.118  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-19 11:06:23.118  5632  5678 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-19 11:06:23.118  5632  5678 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-19 11:06:23.118  5632  5678 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-19 11:06:23.118  5632  5678 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-19 11:06:23.119  5632  5678 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-19 11:06:23.119  5632  5678 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-19 11:06:23.119  5632  5678 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-19 11:06:23.119  5632  5678 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-19 11:06:23.119  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:23.119  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5986483 added. We now have 2 listener(s)
,09-19 11:06:23.119  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:23.121  5632  5678 D BluetoothAdapter: enable(): BT is already enabled..!
,09-19 11:06:23.121   924  3152 D WifiService: setWifiEnabled: true pid=5632, uid=10077
09-19 11:06:23.121   924  3152 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-19 11:06:23.121  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:23.121  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4e600 added. We now have 3 listener(s)
09-19 11:06:23.121  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 11:06:23.126  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 11:06:23.126  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cba1e39 added. We now have 4 listener(s)
09-19 11:06:23.126  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 11:06:23.127  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:23.127  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@98a6c7e added. We now have 5 listener(s)
09-19 11:06:23.127  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 11:06:23.129   924  3420 D WifiService: setWifiEnabled: false pid=5632, uid=10077
09-19 11:06:23.129   924  3420 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-19 11:06:23.133   924  2977 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-19 11:06:23.133   924  2977 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-19 11:06:23.133   924  2977 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-19 11:06:23.133   924  2977 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-19 11:06:23.136  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:23.136  4594  4661 D BluetoothAdapterState: Current state: ON, message: 23
09-19 11:06:23.136  4594  4661 D BluetoothAdapterProperties: Setting state to 13
09-19 11:06:23.138  4594  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-19 11:06:23.138  4594  4661 D BluetoothAdapterProperties: onBluetoothDisable()
,09-19 11:06:23.139  4594  4661 I BluetoothAdapterState: Entering PendingCommandState
09-19 11:06:23.139  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 11:06:23.139  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:23.139  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:23.139  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:23.139  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:23.139  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:23.139  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:23.139  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 11:06:23.139  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 11:06:23.140  4594  4667 D BluetoothAdapterProperties: Scan Mode:20
09-19 11:06:23.140  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.140  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:23.140  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-19 11:06:23.141  4594  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-19 11:06:23.143  4594  4594 D HeadsetService: Received stop request...Stopping profile...
09-19 11:06:23.145  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.146  3786  3818 D BluetoothHeadset: Proxy object disconnected
09-19 11:06:23.147   924   924 D BluetoothHeadset: Proxy object disconnected
09-19 11:06:23.147   924   924 D BluetoothHeadset: Proxy object disconnected
09-19 11:06:23.147  3118  3130 D BluetoothHeadset: Proxy object disconnected
09-19 11:06:23.147  3118  3118 D HeadsetProfile: Bluetooth service disconnected
09-19 11:06:23.147   924   924 D BluetoothHeadset: Proxy object disconnected
,09-19 11:06:23.148  4594  4594 D A2dpService: Received stop request...Stopping profile...
09-19 11:06:23.148  4594  4809 D A2dpStateMachine: Exit Disconnected: -1
,09-19 11:06:23.149  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.150   924  5384 D DhcpClient: Clearing IP address
09-19 11:06:23.150  3118  3118 D BluetoothA2dp: Proxy object disconnected
09-19 11:06:23.150   924   924 D BluetoothA2dp: Proxy object disconnected
09-19 11:06:23.150   507   917 D CommandListener: Clearing all IP addresses on wlan0
09-19 11:06:23.151  4594  4594 D HidService: Received stop request...Stopping profile...
09-19 11:06:23.151  4594  4594 D HidService: Stopping Bluetooth HidService
09-19 11:06:23.152  3118  3118 D BluetoothInputDevice: Proxy object disconnected
09-19 11:06:23.152  3118  3118 D HidProfile: Bluetooth service disconnected
,09-19 11:06:23.155  4594  4594 D HealthService: Received stop request...Stopping profile...
,09-19 11:06:23.156  4594  4594 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:23.156  4594  4594 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:23.156  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:23.156  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:23.157  4594  4594 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-19 11:06:23.157  4594  4594 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-19 11:06:23.158  4594  4667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-19 11:06:23.158  4594  4594 D PanService: Received stop request...Stopping profile...
,09-19 11:06:23.158   507   917 D CommandListener: Setting iface cfg
,09-19 11:06:23.158  4594  4798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-19 11:06:23.158  4594  4798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:23.158  4594  4798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:23.158  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.158  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:23.158  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:23.158  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:23.158  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:23.158  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:23.158  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:23.158  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 11:06:23.158  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 11:06:23.158  4594  4667 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-19 11:06:23.158  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-19 11:06:23.159  3118  3118 D PanProfile: Bluetooth service disconnected
09-19 11:06:23.159  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.159  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 11:06:23.160  4594  4594 D BluetoothMapService: Received stop request...Stopping profile...
09-19 11:06:23.160  4594  4594 D BluetoothMapService: stop()
09-19 11:06:23.161  3588  5437 V NativeCrypto: Read error: ssl=0x7fa1cb2000: I/O error during system call, Connection timed out
09-19 11:06:23.161  4594  4594 D BluetoothMapAppObserver: deinitObservers()
09-19 11:06:23.161  4594  4594 D BluetoothMapAppObserver: removeReceiver()
09-19 11:06:23.162  3118  3118 D BluetoothMap: Proxy object disconnected
09-19 11:06:23.162  3588  5437 V NativeCrypto: SSL shutdown failed: ssl=0x7fa1cb2000: I/O error during system call, Broken pipe
09-19 11:06:23.162  3118  3118 D MapProfile: Bluetooth service disconnected
09-19 11:06:23.162  4594  4594 D SapService: Received stop request...Stopping profile...
09-19 11:06:23.162  4594  4594 V SapService: stop()
09-19 11:06:23.163  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.164  4594  4594 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:23.164  4594  4594 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:23.164  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:23.164  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:23.164   924   935 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-19 11:06:23.165   924  5382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-19 11:06:23.166  4594  4594 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:23.166  4594  4594 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:23.166  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:23.166  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:23.166  4594  4594 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-19 11:06:23.166  4594  4594 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-19 11:06:23.167  4594  4594 V BluetoothAdapte,rState: isTurningOff()=true
09-19 11:06:23.167  4594  4594 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:23.167  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:23.167  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:23.167   924  5385 D DhcpClient: Receive thread stopped
09-19 11:06:23.167  4594  4594 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-19 11:06:23.167  4594  4667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-19 11:06:23.167  4594  4798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:23.167  4594  4667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-19 11:06:23.167  4594  4594 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-19 11:06:23.167  4594  4667 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-19 11:06:23.167  4594  4798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:23.167  4594  4798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-19 11:06:23.167  4594  4594 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:23.168  4594  4798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-19 11:06:23.168  4594  4594 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:23.168  4594  4798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-19 11:06:23.168  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:23.168   924  5382 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-19 11:06:23.168  4594  4798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-19 11:06:23.168  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:23.168  4594  4594 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-19 11:06:23.168  4594  4594 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-19 11:06:23.169  4594  4594 D BluetoothMapService: MAP Service closeService in
09-19 11:06:23.169  4594  4594 D BluetoothMapMasInstance0: MAP Service shutdown
09-19 11:06:23.169  4594  4594 D ObexServerSockets0: shutdown(block = true)
09-19 11:06:23.169  4594  4841 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-19 11:06:23.170  4594  4594 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-19 11:06:23.170  4594  4594 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-19 11:06:23.170  4594  4842 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-19 11:06:23.170   924  2979 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-19 11:06:23.170   924  2979 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-19 11:06:23.170   924  2979 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-19 11:06:23.171   537   537 E Parcel  : Reading a NULL string not supported here.
09-19 11:06:23.171   924  2979 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-19 11:06:23.172  4594  4803 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-19 11:06:23.172  4594  4594 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:23.172  4594  4594 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:23.172  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:23.173  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:23.174  4594  4594 D BluetoothMapService: cleanup()
09-19 11:06:23.174  4594  4594 D BluetoothMapService: MAP Service closeService in
09-19 11:06:23.174  4594  4594 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:23.174  4594  4594 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:23.174  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:23.175  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:23.175  4594  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-19 11:06:23.175  4594  4661 D BluetoothAdapterProperties: Setting state to 15
09-19 11:06:23.175  4594  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-19 11:06:23.176  4594  4661 I BluetoothAdapterState: Entering BleOnState
09-19 11:06:23.176   924  2979 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-19 11:06:23.178   924   924 D RttService: SCAN_AVAILABLE : 1
09-19 11:06:23.178   924  3081 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-19 11:06:23.181   924  2979 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-19 11:06:23.183  3739  3894 W QCNEJ   : |CORE| network lost: 100
09-19 11:06:23.183  3739  3894 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-19 11:06:23.184   924  2977 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-19 11:06:23.193  3118  3130 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 11:06:23.194  4594  4594 I BtOppRfcommListener: stopping Accept Thread
09-19 11:06:23.194  4594  5325 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-19 11:06:23.194  4594  5325 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-19 11:06:23.194   924  2977 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-19 11:06:23.197  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.197  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:23.197  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:23.197  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:23.197  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:23.197  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:23.197  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:23.197  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:23.197  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:23.198  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.198  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:23.200  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.200  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:23.200  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:23.200  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:23.200  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:23.200  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:23.200  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:23.200  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:23.200  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:23.200  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.201  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:23.206   924   937 I ActivityManager: Start proc 5691:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-19 11:06:23.210  3118  3962 D BluetoothPbap: onBluetoothStateChange: up=false
09-19 11:06:23.210   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:23.211  3118  3967 D BluetoothPan: onBluetoothStateChange on: false
09-19 11:06:23.211  3118  3131 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-19 11:06:23.212  3118  3130 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:23.212  3118  3962 D BluetoothMap: onBluetoothStateChange: up=false
09-19 11:06:23.213   924   941 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 11:06:23.213   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:23.213   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:23.213  3786  3818 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:23.214  4594  4661 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-19 11:06:23.214  4594  4661 D BluetoothAdapterProperties: Setting state to 16
09-19 11:06:23.214  4594  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-19 11:06:23.214  4594  4661 D BluetoothAdapterProperties: onBleDisable
09-19 11:06:23.215  4594  4661 I BluetoothAdapterState: Entering PendingCommandState
09-19 11:06:23.215  4594  4662 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-19 11:06:23.216  4594  4667 D BluetoothAdapterProperties: Scan Mode:20
09-19 11:06:23.216  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.218  4594  4798 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-19 11:06:23.218  4594  4798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:23.218  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.218   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-19 11:06:23.221  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.222  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.249   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-19 11:06:23.249   507   917 D CommandListener: Clearing all IP addresses on wlan0
09-19 11:06:23.250   507   917 D TetherController: Setting IP forward enable = 0
09-19 11:06:23.251   924  2979 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-19 11:06:23.251   924  2979 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-19 11:06:23.252   924   941 D Tethering: MasterInitialState.processMessage what=3
09-19 11:06:23.254   924  2977 D DhcpClient: doQuit
09-19 11:06:23.254   924  2977 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-19 11:06:23.255  3445  3445 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-19 11:06:23.255   924  5384 D DhcpClient: onQuitting
09-19 11:06:23.255  5282  5282 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5bbde58 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-19 11:06:23.255  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.258  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.258  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:23.258  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:23.258  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:23.258  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:23.258  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:23.258  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:23.258  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:23.258  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:23.259  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.259  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:23.262  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 11:06:23.262  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:23.262  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:23.262  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:23.262  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:23.262  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:23.262  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:23.262  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:23.262  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:23.263  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:23.263  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:23.264  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.265  5053  5077 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-19 11:06:23.265  5053  5077 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-19 11:06:23.265  5053  5077 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-19 11:06:23.265  5053  5077 E SarControlService: no key has been found,reset the power
09-19 11:06:23.266  5053  5090 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-19 11:06:23.266  5053  5090 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-19 11:06:23.266  5053  5090 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-19 11:06:23.266  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-19 11:06:23.266  5078  5078 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-19 11:06:23.268  5053  5090 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-19 11:06:23.268  5053  5090 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-19 11:06:23.268  5053  5090 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-19 11:06:23.269  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-19 11:06:23.269  5078  5078 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-19 11:06:23.272  5078  5092 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@13114fe HexData = [00000000ea03000000000000ffffffff]
09-19 11:06:23.272  5078  5092 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-19 11:06:23.272  5078  5092 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-19 11:06:23.272  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-19 11:06:23.272  5053  5064 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-19 11:06:23.275  5078  5092 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@13114fe HexData = [00000000eb03000000000000ffffffff]
,09-19 11:06:23.275  5078  5092 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-19 11:06:23.275  5078  5092 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-19 11:06:23.276  5078  5078 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-19 11:06:23.276  5053  5063 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-19 11:06:23.277  3445  3445 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-19 11:06:23.280  3445  3445 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-19 11:06:23.283  5691  5691 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-19 11:06:23.294  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-19 11:06:23.302  3588  3588 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 11:06:23.303   507   917 E Netd    : netlink response contains error (No such file or directory)
09-19 11:06:23.303   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a01176:true
,09-19 11:06:23.303   507   917 D TetherController: Setting IP forward enable = 0
09-19 11:06:23.304   924  2979 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-19 11:06:23.315  3445  3445 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-19 11:06:23.316   924  3420 I ActivityManager: Start proc 5716:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-19 11:06:23.323  5691  5691 D LocalBluetoothProfileManager: Adding local MAP profile
,09-19 11:06:23.327  3445  3445 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-19 11:06:23.327  5691  5691 D BluetoothMap: Create BluetoothMap proxy object
,09-19 11:06:23.348  5691  5691 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-19 11:06:23.355  5716  5716 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-19 11:06:23.366  5691  5691 D DockEventReceiver: finishStartingService: stopping service
,09-19 11:06:23.370   924  3152 I ActivityManager: Killing 4993:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-19 11:06:23.422  4594  4667 I bt_hci  : shut_down
,09-19 11:06:23.424  4594  4674 D bt_hwcfg: hw_epilog_process
,09-19 11:06:23.424  4594  4674 I bt_vendor: low_power_mode_cb
,09-19 11:06:23.427  4594  4674 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-19 11:06:23.427  4594  4674 I bt_vendor: epilog_cb
09-19 11:06:23.427  4594  4674 I bt_hci  : epilog_finished_callback
,09-19 11:06:23.430  4594  4667 I bt_hci_h4: hal_close
,09-19 11:06:23.430  4594  4667 I bt_userial_vendor: device fd = 54 close
,09-19 11:06:23.432  5028  5028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-19 11:06:23.432   924  2977 D wifi    : In wifi stop Hal
09-19 11:06:23.432   924  2977 D wifi    : halHandle = 0x7f8b748b80, mVM = 0x7fa7dcd140, mCls = 0x100a02
,09-19 11:06:23.433   924  3444 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-19 11:06:23.433   924  3444 D WifiHAL : Got a signal to exit!!!
09-19 11:06:23.433   924  3444 I WifiHAL : Exit wifi_event_loop
09-19 11:06:23.433   924  2977 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-19 11:06:23.433   924  2977 E WifiHAL : Event processing terminated
09-19 11:06:23.433   924  2977 D wifi    : In wifi cleaned up handler
09-19 11:06:23.433   924  2977 I WifiHAL : Internal cleanup completed
09-19 11:06:23.435  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:23.437  4110  4231 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-19 11:06:23.437  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:23.456   924  3444 D wifi    : set interface wlan0 flags (DOWN)
,09-19 11:06:23.457   924  2977 D WifiNative-HAL: HAL event thread stopped successfully
,09-19 11:06:23.546  4594  4662 D bt_stack_manager: event_shut_down_stack finished.
,09-19 11:06:23.546  4594  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-19 11:06:23.548  4594  4661 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-19 11:06:23.548  4594  4594 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-19 11:06:23.549  4594  4594 D BtGatt.GattService: Received stop request...Stopping profile...
,09-19 11:06:23.549  4594  4594 D BtGatt.GattService: stop()
09-19 11:06:23.549  4594  4594 D BtGatt.AdvertiseManager: advertise clients cleared
09-19 11:06:23.551  4594  4594 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:23.551  4594  4594 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:23.551  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:23.551  4594  4594 V BluetoothAdapterState: isBleTurningOff()=true
09-19 11:06:23.551  4594  4661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-19 11:06:23.551  4594  4661 D BluetoothAdapterProperties: Setting state to 10
09-19 11:06:23.551  4594  4661 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-19 11:06:23.552  4594  4661 I BluetoothAdapterState: Entering OffState
,09-19 11:06:23.553   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-19 11:06:23.554  5716  5716 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.File.exists(File.java:361)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-19 11:06:23.554  5716  5716 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:23.554  5716  5716 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:23.554  5716  5716 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.e.b(PG:170)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:23.554  5716  5716 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.k.d(PG:583)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.e.b(PG:170)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:23.554  5716  5716 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.File.exists(File.java:361)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:23.554  5716  5716 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.io.File.exists(File.java:361)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:23.554  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:23.562  4594  4594 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-19 11:06:23.562  4594  4594 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-19 11:06:23.562  4594  4594 I BluetoothServiceJni: cleanupNative: return from cleanup
09-19 11:06:23.564  4594  4662 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-19 11:06:23.565  5716  5716 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 11:06:23.565  5716  5716 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:23.565  5716  5716 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:23.569  4594  4594 I art     : System.exit called, status: 0
09-19 11:06:23.569  4594  4594 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-19 11:06:23.595  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-19 11:06:23.595  5632  5632 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-19 11:06:23.598   924  3419 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-19 11:06:23.598   924  3419 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-19 11:06:23.599   924  3419 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-19 11:06:23.599   924  3419 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-19 11:06:23.599   924  3419 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-19 11:06:23.599   924  3419 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-19 11:06:23.599   924  3419 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-19 11:06:23.599   924  3419 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-19 11:06:23.599   924  3419 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-19 11:06:23.599   924  3419 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-19 11:06:23.599   924  3419 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-19 11:06:23.599   924  3419 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-19 11:06:23.599   924  3419 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-19 11:06:23.619   924  3419 I ActivityManager: Start proc 5748:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-19 11:06:23.621   924  3829 W ActivityManager: Spurious death for ProcessRecord{bc1414b 5748:com.android.bluetooth/1002}, curProc for 4594: null
,09-19 11:06:23.637  5691  5691 D DockEventReceiver: finishStartingService: stopping service
,09-19 11:06:23.641   924   935 I ActivityManager: Killing 5411:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-19 11:06:23.660   924   941 D Tethering: InitialState.processMessage what=4
,09-19 11:06:23.668   924   941 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-19 11:06:23.699  5748  5748 D AdapterServiceConfig: Adding HeadsetService
,09-19 11:06:23.699  5748  5748 D AdapterServiceConfig: Adding A2dpService
09-19 11:06:23.699  5748  5748 D AdapterServiceConfig: Adding HidService
09-19 11:06:23.699  5748  5748 D AdapterServiceConfig: Adding HealthService
09-19 11:06:23.699  5748  5748 D AdapterServiceConfig: Adding PanService
09-19 11:06:23.700  5748  5748 D AdapterServiceConfig: Adding GattService
09-19 11:06:23.700  5748  5748 D AdapterServiceConfig: Adding BluetoothMapService
,09-19 11:06:23.700  5748  5748 D AdapterServiceConfig: Adding SapService
09-19 11:06:23.702   924   934 I ActivityManager: Killing 5423:com.android.chrome/u0a39 (adj 15): empty #17
,09-19 11:06:23.730  3588  3588 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 11:06:23.749  3909  3909 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-19 11:06:23.755  3909  5408 I iu.UploadsManager: num queued entries: 0
,09-19 11:06:23.755  3909  5408 I iu.UploadsManager: num updated entries: 0
09-19 11:06:23.756  3909  5408 I iu.SyncManager: NEXT; no task
,09-19 11:06:23.757  3909  3909 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-19 11:06:23.760  3909  3909 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-19 11:06:23.772   924  3420 I ActivityManager: Start proc 5762:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-19 11:06:23.815  5762  5762 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-19 11:06:23.818  5762  5762 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-19 11:06:23.827  5762  5762 D SprintDMHelper: simOperator: 
09-19 11:06:23.827  5762  5762 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-19 11:06:23.840   924  3420 I ActivityManager: Start proc 5774:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-19 11:06:23.841   924  3420 I ActivityManager: Killing 5441:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-19 11:06:23.935  5028  5788 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-19 11:06:23.945   924  3419 I ActivityManager: Start proc 5789:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-19 11:06:23.947   924  3419 I ActivityManager: Killing 5282:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-19 11:06:23.997  5789  5789 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-19 11:06:24.149   924  3418 I ActivityManager: Killing 4686:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-19 11:06:24.191  5716  5743 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-19 11:06:24.200   924  3420 I ActivityManager: Start proc 5801:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-19 11:06:24.202   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@68f31fe:true
,09-19 11:06:24.228  5801  5801 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-19 11:06:24.242   924  3418 I ActivityManager: Killing 5496:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-19 11:06:26.142   924  3203 D WifiService: setWifiEnabled: true pid=5632, uid=10077
09-19 11:06:26.143   924  3203 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-19 11:06:26.150   507   917 D SoftapController: Softap fwReload - Ok
,09-19 11:06:26.155   507   917 D CommandListener: Setting iface cfg
,09-19 11:06:26.155   507   917 D CommandListener: Trying to bring down wlan0
,09-19 11:06:26.157   507   917 D CommandListener: Clearing all IP addresses on wlan0
,09-19 11:06:26.162   924  2977 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-19 11:06:26.767   924  2977 D wifi    : set interface wlan0 flags (UP)
09-19 11:06:26.770   924  2977 I WifiHAL : Initializing wifi
09-19 11:06:26.771   924  2977 I WifiHAL : Creating socket
,09-19 11:06:26.776   924   941 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-19 11:06:26.778   924  2977 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-19 11:06:26.779   924  2977 D wifi    : Did set static halHandle = 0x7f8b748b80
09-19 11:06:26.779   924  2977 D wifi    : halHandle = 0x7f8b748b80, mVM = 0x7fa7dcd140, mCls = 0x20175e
,09-19 11:06:26.780   924  2977 D wifi    : array field set
09-19 11:06:26.780   924  2977 I WifiNative-HAL: interface[0] = wlan0
09-19 11:06:26.782   924  5823 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547800517504
09-19 11:06:26.782   924  5823 D wifi    : waitForHalEvents called, vm = 0x7fa7dcd140, obj = 0x20175e, env = 0x7f8bd3a140
,09-19 11:06:26.859  5824  5824 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-19 11:06:26.879  5824  5824 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-19 11:06:26.884   924  2977 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-19 11:06:26.892  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:26.893  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:26.902  5824  5824 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-19 11:06:26.902  5824  5824 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-19 11:06:26.918  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 11:06:26.918  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:26.918  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:26.918  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:26.918  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:26.918  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:26.918  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:26.918  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:26.918  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:26.918  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:26.918  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:26.919  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 11:06:26.919  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:26.919  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:26.919  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:26.919  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:26.919  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:26.919  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:26.919  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:26.919  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:26.919  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:26.919   924  2977 D WifiConfigStore: Loading config and enabling all networks 
09-19 11:06:26.919  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:26.928   924  2977 D WifiConfigStore: loaded 0 passpoint configs
09-19 11:06:26.928   924  2977 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-19 11:06:26.929   924  2977 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-19 11:06:26.930   924  2977 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-19 11:06:26.931   924  2977 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-19 11:06:26.931   924  2977 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-19 11:06:26.931   924  2977 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-19 11:06:26.931   924  2977 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-19 11:06:26.934   924  2977 D WifiNative-HAL: Setting external_sim to 1
,09-19 11:06:26.935  5028  5028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-19 11:06:26.935   924  2977 D wifi    : setting dfs flag to true, 0x7f90cbf840
09-19 11:06:26.936   924  2977 D WifiStateMachine: Setting OUI to DA-A1-19
,09-19 11:06:26.936   924  2977 D wifi    : setting scan oui 0x7f90cbf840
09-19 11:06:26.936   924  2977 D WifiHAL : Sending mac address OUI
,09-19 11:06:26.939   924  2977 E native  : do suspend false
,09-19 11:06:26.946   924   924 D RttService: SCAN_AVAILABLE : 3
09-19 11:06:26.946   924  2977 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-19 11:06:26.947   507   917 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-19 11:06:26.947   924  3081 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-19 11:06:26.948   507   917 D CommandListener: Setting iface cfg
,09-19 11:06:26.952   924  2958 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,09-19 11:06:26.952   924  2958 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-19 11:06:26.961   924  2958 D WifiNative-HAL: p2pGetDeviceAddress
09-19 11:06:26.961   924  2958 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-19 11:06:26.967   924   939 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=176320 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-19 11:06:29.149   924   934 D WifiService: setWifiEnabled: false pid=5632, uid=10077
09-19 11:06:29.149   924   934 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-19 11:06:29.158   924   924 D RttService: SCAN_AVAILABLE : 1
09-19 11:06:29.159   924  3081 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-19 11:06:29.171   924  2977 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-19 11:06:29.172   507   917 D CommandListener: Clearing all IP addresses on wlan0
,09-19 11:06:29.180   924  2977 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-19 11:06:29.182  5824  5824 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-19 11:06:29.190  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 11:06:29.190  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:29.190  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:29.190  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:29.190  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:29.190  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:29.190  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:29.190  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:29.190  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:29.190  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:29.191  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:29.193  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:29.193  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:29.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:29.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:29.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:29.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:29.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:29.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:29.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:29.193  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 11:06:29.193  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:29.198  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-19 11:06:29.204  5824  5824 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-19 11:06:29.207  5824  5824 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-19 11:06:29.312   924  2977 D wifi    : In wifi stop Hal
,09-19 11:06:29.312   924  2977 D wifi    : halHandle = 0x7f8b748b80, mVM = 0x7fa7dcd140, mCls = 0x20175e
,09-19 11:06:29.312   924  5823 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-19 11:06:29.312   924  5823 D WifiHAL : Got a signal to exit!!!
09-19 11:06:29.312   924  5823 I WifiHAL : Exit wifi_event_loop
09-19 11:06:29.314   924  2977 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-19 11:06:29.315   924  2977 E WifiHAL : Event processing terminated
09-19 11:06:29.311  5028  5028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-19 11:06:29.316   924  2977 D wifi    : In wifi cleaned up handler
09-19 11:06:29.316   924  2977 I WifiHAL : Internal cleanup completed
,09-19 11:06:29.318  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:29.320  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:29.322  4110  4231 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-19 11:06:29.338   924  5823 D wifi    : set interface wlan0 flags (DOWN)
,09-19 11:06:29.338   924  2977 D WifiNative-HAL: HAL event thread stopped successfully
,09-19 11:06:29.545   924   941 D Tethering: InitialState.processMessage what=4
,09-19 11:06:29.550   924   941 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-19 11:06:32.192   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a00fdc:true
,09-19 11:06:32.193  5748  5748 D BluetoothAdapterState: make() - Creating AdapterState
,09-19 11:06:32.199  5748  5748 I bt_bluedroid: init
,09-19 11:06:32.199  5748  5828 I BluetoothAdapterState: Entering OffState
,09-19 11:06:32.203  5748  5829 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-19 11:06:32.204  5748  5829 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-19 11:06:32.204  5748  5829 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-19 11:06:32.204  5748  5829 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-19 11:06:32.205  5748  5748 I bt_bluedroid: get_profile_interface socket
,09-19 11:06:32.207  5748  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-19 11:06:32.208  5748  5748 I bt_bluedroid: get_profile_interface sdp
09-19 11:06:32.209  5748  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-19 11:06:32.214  5748  5758 I bt_bluedroid: config_hci_snoop_log
09-19 11:06:32.216   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-19 11:06:32.222  5748  5828 D BluetoothAdapterState: Current state: OFF, message: 0
,09-19 11:06:32.222  5748  5828 D BluetoothAdapterProperties: Setting state to 14
09-19 11:06:32.222  5748  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-19 11:06:32.224  5748  5828 D BluetoothBondStateMachine: make
09-19 11:06:32.226  5748  5833 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-19 11:06:32.229  5748  5828 I BluetoothAdapterState: Entering PendingCommandState
,09-19 11:06:32.230  5748  5748 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-19 11:06:32.234  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:32.234  5748  5748 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-19 11:06:32.235  5748  5748 D BtGatt.GattService: Received start request. Starting profile...
,09-19 11:06:32.235  5748  5748 D BtGatt.GattService: start()
09-19 11:06:32.235  5748  5748 I bt_bluedroid: get_profile_interface gatt
09-19 11:06:32.236  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
09-19 11:06:32.236  5748  5748 D BtGatt.AdvertiseManager: advertise manager created
09-19 11:06:32.241  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:32.241  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:32.241  5748  5748 V BluetoothAdapterState: isBleTurningOn()=true
09-19 11:06:32.241  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:32.242  5748  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-19 11:06:32.243  5748  5828 I bt_bluedroid: bt_bluedroid
09-19 11:06:32.243  5748  5829 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-19 11:06:32.243  5748  5829 I bt_hci  : start_up
,09-19 11:06:32.249  5748  5829 I bt_vendor: alloc value 0xf40f8871
,09-19 11:06:32.249  5748  5829 I bt_vendor: init
09-19 11:06:32.249  5748  5829 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-19 11:06:32.249  5748  5829 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-19 11:06:32.358  5748  5829 D bt_hci  : start_up starting async portion
,09-19 11:06:32.358  5748  5836 I bt_hci  : event_finish_startup
,09-19 11:06:32.359  5748  5836 I bt_hci_h4: hal_open
09-19 11:06:32.359  5748  5836 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-19 11:06:32.354  5837  5837 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-19 11:06:32.360  5748  5836 I bt_userial_vendor: device fd = 54 open
,09-19 11:06:32.372  5748  5836 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-19 11:06:32.374  5748  5836 D bt_hwcfg: Chipset BCM4358A3
,09-19 11:06:32.374  5748  5836 D bt_hwcfg: Target name = [BCM4358A3]
09-19 11:06:32.374  5748  5836 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-19 11:06:32.714  5748  5836 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-19 11:06:32.714  5748  5836 D bt_hwcfg: Settlement delay -- 100 ms
,09-19 11:06:32.714  5748  5836 I bt_hwcfg: Setting fw settlement delay to 100 
,09-19 11:06:32.849  5748  5836 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-19 11:06:32.849  5748  5836 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-19 11:06:32.851  5748  5836 I bt_hwcfg: vendor lib fwcfg completed
,09-19 11:06:32.851  5748  5836 I bt_vendor: firmware callback
09-19 11:06:32.851  5748  5836 I bt_hci  : firmware_config_callback
,09-19 11:06:32.859  5748  5839 I bt_btu  : btu_task pending for preload complete event
,09-19 11:06:32.859  5748  5839 I bt_btu_task: Bluetooth chip preload is complete
,09-19 11:06:32.859  5748  5839 I bt_btu  : btu_task received preload complete event
,09-19 11:06:32.866  5748  5839 I         : BTE_InitTraceLevels -- TRC_HCI
,09-19 11:06:32.866  5748  5839 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-19 11:06:32.866  5748  5839 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-19 11:06:32.866  5748  5839 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-19 11:06:32.866  5748  5839 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-19 11:06:32.866  5748  5839 I         : BTE_InitTraceLevels -- TRC_A2D
09-19 11:06:32.867  5748  5839 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-19 11:06:32.867  5748  5839 I         : BTE_InitTraceLevels -- TRC_BTM
09-19 11:06:32.867  5748  5839 I         : BTE_InitTraceLevels -- TRC_GAP
,09-19 11:06:32.867  5748  5839 I         : BTE_InitTraceLevels -- TRC_PAN
09-19 11:06:32.867  5748  5839 I         : BTE_InitTraceLevels -- TRC_SDP
09-19 11:06:32.867  5748  5839 I         : BTE_InitTraceLevels -- TRC_GATT
09-19 11:06:32.867  5748  5839 I         : BTE_InitTraceLevels -- TRC_SMP
,09-19 11:06:32.867  5748  5839 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-19 11:06:32.867  5748  5839 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-19 11:06:32.949  5748  5839 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4076549
,09-19 11:06:32.949  5748  5839 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4076549 
,09-19 11:06:32.964  5748  5832 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-19 11:06:32.966  5748  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-19 11:06:32.967  5748  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-19 11:06:32.969  5748  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
09-19 11:06:32.972  5748  5832 D BluetoothAdapterProperties: Scan Mode:20
,09-19 11:06:32.973  5748  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
09-19 11:06:32.973  5748  5832 D bt_hci  : do_postload posting postload work item
09-19 11:06:32.973  5748  5836 I bt_hci  : event_postload
09-19 11:06:32.974  5748  5836 I bt_vendor: sco_config_cb
09-19 11:06:32.974  5748  5836 I bt_hci  : sco_config_callback postload finished.
,09-19 11:06:32.977  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:32.981  5748  5836 I bt_vendor: low_power_mode_cb
09-19 11:06:32.982  5748  5832 D bt_bte_conf: Device ID record 1 : primary
09-19 11:06:32.982  5748  5832 D bt_bte_conf:   vendorId            = 000f
09-19 11:06:32.982  5748  5832 D bt_bte_conf:   vendorIdSource      = 0001
09-19 11:06:32.982  5748  5832 D bt_bte_conf:   product             = 1200
,09-19 11:06:32.982  5748  5832 D bt_bte_conf:   version             = 1436
09-19 11:06:32.982  5748  5832 D bt_bte_conf:   clientExecutableURL = 
09-19 11:06:32.982  5748  5832 D bt_bte_conf:   serviceDescription  = 
09-19 11:06:32.982  5748  5832 D bt_bte_conf:   documentationURL    = 
09-19 11:06:32.982  5748  5832 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-19 11:06:32.983  5748  5829 D bt_stack_manager: event_start_up_stack finished
09-19 11:06:32.983  5748  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-19 11:06:32.983  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:32.984  5748  5828 D BluetoothAdapterProperties: Setting state to 15
09-19 11:06:32.984  5748  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-19 11:06:32.985  5748  5828 I BluetoothAdapterState: Entering BleOnState
09-19 11:06:32.989  5748  5828 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-19 11:06:32.989  5748  5828 D BluetoothAdapterProperties: Setting state to 11
09-19 11:06:32.989  5748  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-19 11:06:32.994  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:32.996  5748  5748 D HeadsetService: Received start request. Starting profile...
,09-19 11:06:32.999  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:33.001  5748  5748 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-19 11:06:33.001  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:33.001  5748  5748 D HeadsetStateMachine: make
,09-19 11:06:33.009  5748  5828 I BluetoothAdapterState: Entering PendingCommandState
,09-19 11:06:33.013  5748  5748 D HeadsetStateMachine: max_hf_connections = 1
,09-19 11:06:33.013  5748  5748 I bt_bluedroid: get_profile_interface handsfree
09-19 11:06:33.013  5748  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-19 11:06:33.013  5748  5832 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-19 11:06:33.016  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:33.017  5748  5748 D A2dpService: Received start request. Starting profile...
,09-19 11:06:33.018  5748  5748 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-19 11:06:33.018  5748  5748 I bt_bluedroid: get_profile_interface avrcp
,09-19 11:06:33.024  5748  5748 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-19 11:06:33.024  5748  5748 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-19 11:06:33.024  5748  5748 D A2dpStateMachine: make
,09-19 11:06:33.027  5748  5748 I bt_bluedroid: get_profile_interface a2dp
,09-19 11:06:33.031  5748  5847 D A2dpStateMachine: Enter Disconnected: -2
,09-19 11:06:33.032  5748  5748 I BluetoothHidServiceJni: classInitNative: succeeds
09-19 11:06:33.032  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:33.033  5748  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-19 11:06:33.034  5748  5748 D HidService: Received start request. Starting profile...
,09-19 11:06:33.034  5691  5691 D BluetoothInputDevice: Proxy object connected
,09-19 11:06:33.034  5748  5748 I bt_bluedroid: get_profile_interface hidhost
09-19 11:06:33.034  5748  5748 D HidService: setHidService(): set to: null
09-19 11:06:33.034  5748  5832 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf405756d
09-19 11:06:33.035  5748  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-19 11:06:33.035  5748  5748 I BluetoothHealthServiceJni: classInitNative: succeeds
09-19 11:06:33.035  5691  5691 D HidProfile: Bluetooth service connected
09-19 11:06:33.036  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
09-19 11:06:33.036  5748  5748 D HealthService: Received start request. Starting profile...
,09-19 11:06:33.038  5748  5748 I bt_bluedroid: get_profile_interface health
09-19 11:06:33.038  5748  5748 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-19 11:06:33.039  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:33.040  3588  3588 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 11:06:33.040  5748  5748 D PanService: Received start request. Starting profile...
,09-19 11:06:33.041  5691  5691 D BluetoothPan: BluetoothPAN Proxy object connected
,09-19 11:06:33.041  5748  5748 D BluetoothPanServiceJni: initializeNative(L110): pan
09-19 11:06:33.041  5748  5748 I bt_bluedroid: get_profile_interface pan
09-19 11:06:33.041  5691  5691 D PanProfile: Bluetooth service connected
09-19 11:06:33.041  5748  5832 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-19 11:06:33.044  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:33.045  5748  5748 D BluetoothMapService: Received start request. Starting profile...
,09-19 11:06:33.045  5748  5748 D BluetoothMapService: start()
09-19 11:06:33.045  5691  5691 D BluetoothMap: Proxy object connected
09-19 11:06:33.045  5691  5691 D MapProfile: Bluetooth service connected
09-19 11:06:33.046  5691  5691 D BluetoothMap: getConnectedDevices()
09-19 11:06:33.046  5691  5691 D BluetoothMap: Bluetooth is Not enabled
09-19 11:06:33.047  5748  5748 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-19 11:06:33.048  5748  5748 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-19 11:06:33.048  5748  5748 D BluetoothMapAppObserver: createReceiver()
09-19 11:06:33.050  5748  5748 D BluetoothMapAppObserver: initObservers()
09-19 11:06:33.050  5748  5748 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-19 11:06:33.057  5748  5748 V SapService: SapBinder()
,09-19 11:06:33.057  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:33.057  5748  5748 D SapService: Received start request. Starting profile...
,09-19 11:06:33.057  5748  5748 V SapService: start()
,09-19 11:06:33.060  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:33.060  5748  5748 V BluetoothAdapterState: isTurningOn()=true
,09-19 11:06:33.060  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:33.060  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isTurningOff()=false
,09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isTurningOn()=true
,09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:33.061  5748  5845 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
,09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
,09-19 11:06:33.061  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:33.062  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:33.062  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:33.062  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:33.062  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:33.063  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:33.063  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:33.063  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:33.063  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:33.063  5748  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-19 11:06:33.063  5748  5828 D BluetoothAdapterProperties: ScanMode =  20
09-19 11:06:33.063  5748  5828 D BluetoothAdapterProperties: State =  11
09-19 11:06:33.064  5748  5828 D BluetoothAdapterProperties: Setting state to 12
09-19 11:06:33.064  5748  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-19 11:06:33.064  5748  5828 I BluetoothAdapterState: Entering OnState
09-19 11:06:33.064  3118  3130 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 11:06:33.066  5748  5832 D BluetoothAdapterProperties: Scan Mode:21
09-19 11:06:33.066  5748  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
09-19 11:06:33.066  3118  3962 D BluetoothPbap: onBluetoothStateChange: up=true
09-19 11:06:33.068  5691  5704 D BluetoothPbap: onBluetoothStateChange: up=true
09-19 11:06:33.070  3118  3118 D BluetoothA2dp: Proxy object connected
09-19 11:06:33.070  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:33.070  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:33.070  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:33.070  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:33.070  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:33.070  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:33.070  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:33.070  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 11:06:33.071  5691  5703 D BluetoothPan: onBluetoothStateChange on: true
09-19 11:06:33.071   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 11:06:33.071  3118  3130 D BluetoothPan: onBluetoothStateChange on: true
,09-19 11:06:33.073  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:33.074  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
,09-19 11:06:33.074  3118  3118 D PanProfile: Bluetooth service connected
09-19 11:06:33.074  3118  3962 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-19 11:06:33.075  5748  5748 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-19 11:06:33.076  5748  5748 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-19 11:06:33.076  3118  3118 D BluetoothInputDevice: Proxy object connected
09-19 11:06:33.076  3118  3118 D HidProfile: Bluetooth service connected
,09-19 11:06:33.076  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:33.076  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:33.076  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:33.076  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:33.076  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:33.076  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:33.076  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:33.076  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:33.076  3118  3130 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 11:06:33.077  3118  3131 D BluetoothMap: onBluetoothStateChange: up=true
09-19 11:06:33.077  5748  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 11:06:33.078  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:33.079   924   941 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 11:06:33.079   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 11:06:33.079   924   924 D BluetoothA2dp: Proxy object connected
09-19 11:06:33.079  5691  5704 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-19 11:06:33.079  3118  3118 D BluetoothMap: Proxy object connected
09-19 11:06:33.080  3118  3118 D MapProfile: Bluetooth service connected
09-19 11:06:33.080  3118  3118 D BluetoothMap: getConnectedDevices()
09-19 11:06:33.080  5691  5703 D BluetoothMap: onBluetoothStateChange: up=true
09-19 11:06:33.080  5748  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 11:06:33.080   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 11:06:33.080  3786  3818 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-19 11:06:33.082   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
,09-19 11:06:33.083  5748  5748 D ObexServerSockets: Succeed to create listening sockets 
09-19 11:06:33.083  5748  5748 D ObexServerSockets0: startAccept()
,09-19 11:06:33.083  5748  5748 D ObexServerSockets0: prepareForNewConnect()
,09-19 11:06:33.085  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:33.085  5748  5748 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-19 11:06:33.085  5748  5748 D BluetoothSdpJni: SDP Create record success - handle: 0
09-19 11:06:33.086  5748  5748 D BluetoothMapService: onReceive
09-19 11:06:33.086  5748  5748 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-19 11:06:33.086  5748  5854 D ObexServerSockets0: Accepting socket connection...
09-19 11:06:33.086  5748  5748 D BluetoothMapService: STATE_ON
09-19 11:06:33.086  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:33.086  5748  5855 D ObexServerSockets0: Accepting socket connection...
,09-19 11:06:33.087  5691  5691 D LocalBluetoothProfileManager: Adding local A2DP profile
09-19 11:06:33.088  5748  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 11:06:33.089  5748  5856 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-19 11:06:33.089  5748  5856 D BluetoothSdpJni: SDP Create record success - handle: 1
09-19 11:06:33.091  5691  5691 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-19 11:06:33.099  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-19 11:06:33.101  5691  5691 D BluetoothA2dp: Proxy object connected
,09-19 11:06:33.105  3588  3588 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 11:06:33.110  5691  5691 D DockEventReceiver: finishStartingService: stopping service
,09-19 11:06:33.112  5748  5748 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-19 11:06:33.112  5691  5691 D BluetoothPbap: Proxy object connected
,09-19 11:06:33.112  5748  5748 D ObexServerSockets0: prepareForNewConnect()
09-19 11:06:33.112  5691  5691 D PbapServerProfile: Bluetooth service connected
09-19 11:06:33.114  3118  3118 D BluetoothPbap: Proxy object connected
09-19 11:06:33.114  3118  3118 D PbapServerProfile: Bluetooth service connected
,09-19 11:06:33.121  5748  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 11:06:33.134  5748  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 11:06:33.135  5748  5864 I BtOppRfcommListener: Accept thread started.
,09-19 11:06:33.173  3786  3820 D BluetoothHeadset: Proxy object connected
09-19 11:06:33.173   924   924 D BluetoothHeadset: Proxy object connected
,09-19 11:06:33.173   924   924 D BluetoothHeadset: Proxy object connected
09-19 11:06:33.173  3118  3967 D BluetoothHeadset: Proxy object connected
09-19 11:06:33.173  3118  3118 D HeadsetProfile: Bluetooth service connected
09-19 11:06:33.173   924   924 D BluetoothHeadset: Proxy object connected
,09-19 11:06:33.177  3118  3130 D BluetoothHeadset: Proxy object connected
,09-19 11:06:33.177  3118  3118 D HeadsetProfile: Bluetooth service connected
,09-19 11:06:33.179   924   941 D BluetoothHeadset: Proxy object connected
,09-19 11:06:33.181   924   941 D BluetoothHeadset: Proxy object connected
,09-19 11:06:33.181  3786  3995 D BluetoothHeadset: Proxy object connected
,09-19 11:06:33.195  5691  5704 D BluetoothHeadset: Proxy object connected
,09-19 11:06:33.197  5691  5691 D HeadsetProfile: Bluetooth service connected
,09-19 11:06:35.170  5748  5828 D BluetoothAdapterState: Current state: ON, message: 23
,09-19 11:06:35.171  5748  5828 D BluetoothAdapterProperties: Setting state to 13
09-19 11:06:35.171  5748  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-19 11:06:35.172  5748  5828 D BluetoothAdapterProperties: onBluetoothDisable()
09-19 11:06:35.174  5748  5828 I BluetoothAdapterState: Entering PendingCommandState
,09-19 11:06:35.178  5748  5748 D BluetoothMapService: onReceive
,09-19 11:06:35.178  5748  5748 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-19 11:06:35.178  5748  5748 D BluetoothMapService: STATE_TURNING_OFF
09-19 11:06:35.179  5748  5748 D BluetoothMapService: MAP Service closeService in
09-19 11:06:35.179  5748  5748 D BluetoothMapMasInstance0: MAP Service shutdown
09-19 11:06:35.179  5748  5748 D ObexServerSockets0: shutdown(block = true)
09-19 11:06:35.180  5748  5748 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-19 11:06:35.180  5748  5748 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-19 11:06:35.180  5748  5854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-19 11:06:35.180  5748  5855 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-19 11:06:35.180  5748  5832 D BluetoothAdapterProperties: Scan Mode:20
09-19 11:06:35.181  5748  5841 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-19 11:06:35.181  5748  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-19 11:06:35.184  5748  5748 I BtOppRfcommListener: stopping Accept Thread
09-19 11:06:35.185  5748  5864 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-19 11:06:35.185  5748  5864 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-19 11:06:35.186  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:35.186  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:35.186  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:35.186  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:35.186  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:35.186  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:35.186  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:35.186  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:35.186  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:35.187  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:35.187  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:35.189  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-19 11:06:35.190  5748  5748 D HeadsetService: Received stop request...Stopping profile...
,09-19 11:06:35.193  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:35.193  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:35.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:35.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:35.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:35.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 11:06:35.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:35.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:35.193  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:35.194  5632  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 11:06:35.194  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:35.196  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:35.198  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:35.200  5691  5704 D BluetoothHeadset: Proxy object disconnected
,09-19 11:06:35.200  5748  5748 D A2dpService: Received stop request...Stopping profile...
09-19 11:06:35.200  3786  3818 D BluetoothHeadset: Proxy object disconnected
09-19 11:06:35.201   924   924 D BluetoothHeadset: Proxy object disconnected
09-19 11:06:35.201   924   924 D BluetoothHeadset: Proxy object disconnected
09-19 11:06:35.201  3118  3130 D BluetoothHeadset: Proxy object disconnected
09-19 11:06:35.201  3118  3118 D HeadsetProfile: Bluetooth service disconnected
,09-19 11:06:35.201  5748  5847 D A2dpStateMachine: Exit Disconnected: -1
09-19 11:06:35.201  3118  3118 D BluetoothA2dp: Proxy object disconnected
09-19 11:06:35.201   924   924 D BluetoothHeadset: Proxy object disconnected
09-19 11:06:35.202   924   924 D BluetoothA2dp: Proxy object disconnected
09-19 11:06:35.202  5691  5691 D DockEventReceiver: finishStartingService: stopping service
09-19 11:06:35.202  5748  5748 D HidService: Received stop request...Stopping profile...
09-19 11:06:35.202  5748  5748 D HidService: Stopping Bluetooth HidService
09-19 11:06:35.203  5691  5691 D HeadsetProfile: Bluetooth service disconnected
,09-19 11:06:35.203  5691  5691 D BluetoothA2dp: Proxy object disconnected
09-19 11:06:35.203  5691  5691 D BluetoothInputDevice: Proxy object disconnected
09-19 11:06:35.204  5691  5691 D HidProfile: Bluetooth service disconnected
09-19 11:06:35.205  3118  3118 D BluetoothInputDevice: Proxy object disconnected
09-19 11:06:35.205  3118  3118 D HidProfile: Bluetooth service disconnected
09-19 11:06:35.205  5748  5748 D HealthService: Received stop request...Stopping profile...
09-19 11:06:35.206  5748  5748 D PanService: Received stop request...Stopping profile...
09-19 11:06:35.206  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-19 11:06:35.206  3118  3118 D PanProfile: Bluetooth service disconnected
09-19 11:06:35.207  5748  5748 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:35.207  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:35.207  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:35.207  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:35.207  5691  5691 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-19 11:06:35.207  5691  5691 D PanProfile: Bluetooth service disconnected
,09-19 11:06:35.208  5748  5748 D BluetoothMapService: Received stop request...Stopping profile...
09-19 11:06:35.208  5748  5748 D BluetoothMapService: stop()
09-19 11:06:35.211  3588  3588 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-19 11:06:35.211  5748  5748 D BluetoothMapAppObserver: deinitObservers()
09-19 11:06:35.212  5748  5748 D BluetoothMapAppObserver: removeReceiver()
,09-19 11:06:35.214  3118  3118 D BluetoothMap: Proxy object disconnected
,09-19 11:06:35.214  3118  3118 D MapProfile: Bluetooth service disconnected
09-19 11:06:35.214  5691  5691 D BluetoothMap: Proxy object disconnected
09-19 11:06:35.214  5691  5691 D MapProfile: Bluetooth service disconnected
,09-19 11:06:35.214  5748  5748 D SapService: Received stop request...Stopping profile...
,09-19 11:06:35.214  5748  5748 V SapService: stop()
09-19 11:06:35.216  5748  5748 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-19 11:06:35.216  5748  5748 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-19 11:06:35.217  5748  5748 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:35.217  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:35.217  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:35.217  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:35.217  5748  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:35.217  5748  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:35.217  5748  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:35.217  5748  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-19 11:06:35.218  5748  5832 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-19 11:06:35.218  5748  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-19 11:06:35.218  5748  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:35.218  5748  5748 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:35.218  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:35.218  5748  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:35.218  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:35.218  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:35.218  5748  5839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-19 11:06:35.218  5748  5839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-19 11:06:35.218  5748  5839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-19 11:06:35.218  5748  5839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-19 11:06:35.218  5748  5748 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-19 11:06:35.218  5748  5748 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-19 11:06:35.219  5748  5748 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:35.219  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:35.219  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:35.219  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:35.219  5748  5748 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-19 11:06:35.219  5748  5748 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-19 11:06:35.219  5748  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-19 11:06:35.219  5748  5832 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-19 11:06:35.219  5748  5748 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:35.219  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:35.219  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:35.219  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:35.220  5748  5748 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-19 11:06:35.223  5748  5748 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-19 11:06:35.226  3118  3118 D BluetoothPbap: Proxy object disconnected
09-19 11:06:35.226  3118  3118 D PbapServerProfile: Bluetooth service disconnected
,09-19 11:06:35.226  5748  5748 D BluetoothMapService: MAP Service closeService in
09-19 11:06:35.226  5748  5748 V BluetoothAdapterState: isTurningOff()=true
,09-19 11:06:35.226  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:35.226  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:35.226  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:35.226  5748  5748 D BluetoothMapService: cleanup()
09-19 11:06:35.226  5748  5748 D BluetoothMapService: MAP Service closeService in
09-19 11:06:35.227  5748  5748 V BluetoothAdapterState: isTurningOff()=true
09-19 11:06:35.227  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:35.227  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:35.227  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:35.227  5748  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-19 11:06:35.227  5748  5828 D BluetoothAdapterProperties: Setting state to 15
09-19 11:06:35.227  5748  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-19 11:06:35.227  5748  5828 I BluetoothAdapterState: Entering BleOnState
09-19 11:06:35.228  3118  3967 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 11:06:35.228  3118  3130 D BluetoothPbap: onBluetoothStateChange: up=false
,09-19 11:06:35.230  5691  5704 D BluetoothPbap: onBluetoothStateChange: up=false
,09-19 11:06:35.231  5691  5703 D BluetoothPan: onBluetoothStateChange on: false
09-19 11:06:35.231   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:35.231  3118  3962 D BluetoothPan: onBluetoothStateChange on: false
09-19 11:06:35.232  3118  3131 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-19 11:06:35.232  5691  5704 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:35.232  3118  3967 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:35.233  3118  3130 D BluetoothMap: onBluetoothStateChange: up=false
09-19 11:06:35.233  5691  5703 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 11:06:35.233   924   941 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 11:06:35.227  5691  5691 D BluetoothPbap: Proxy object disconnected
,09-19 11:06:35.234  5691  5691 D PbapServerProfile: Bluetooth service disconnected
09-19 11:06:35.234   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:35.234  5691  5704 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-19 11:06:35.234  5691  5703 D BluetoothMap: onBluetoothStateChange: up=false
09-19 11:06:35.235   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:35.235  3786  3820 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 11:06:35.235  5748  5828 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-19 11:06:35.235  5748  5828 D BluetoothAdapterProperties: Setting state to 16
09-19 11:06:35.235  5748  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-19 11:06:35.236  5748  5828 D BluetoothAdapterProperties: onBleDisable
09-19 11:06:35.236  5748  5828 I BluetoothAdapterState: Entering PendingCommandState
09-19 11:06:35.237  5748  5829 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-19 11:06:35.238  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:35.239  5748  5839 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-19 11:06:35.239  5748  5832 D BluetoothAdapterProperties: Scan Mode:20
09-19 11:06:35.239  5748  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 11:06:35.239  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-19 11:06:35.239  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:35.245  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:35.246  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:35.249  3588  3588 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 11:06:35.254  5691  5691 D DockEventReceiver: finishStartingService: stopping service
,09-19 11:06:35.449  5748  5832 I bt_hci  : shut_down
,09-19 11:06:35.459  5748  5836 D bt_hwcfg: hw_epilog_process
,09-19 11:06:35.459  5748  5836 I bt_vendor: low_power_mode_cb
,09-19 11:06:35.462  5748  5836 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-19 11:06:35.462  5748  5836 I bt_vendor: epilog_cb
09-19 11:06:35.462  5748  5836 I bt_hci  : epilog_finished_callback
,09-19 11:06:35.466  5748  5832 I bt_hci_h4: hal_close
,09-19 11:06:35.466  5748  5832 I bt_userial_vendor: device fd = 54 close
,09-19 11:06:35.582  5748  5829 D bt_stack_manager: event_shut_down_stack finished.
,09-19 11:06:35.583  5748  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-19 11:06:35.587  5748  5828 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-19 11:06:35.588  5748  5748 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-19 11:06:35.589  5748  5748 D BtGatt.GattService: Received stop request...Stopping profile...
,09-19 11:06:35.589  5748  5748 D BtGatt.GattService: stop()
,09-19 11:06:35.589  5748  5748 D BtGatt.AdvertiseManager: advertise clients cleared
09-19 11:06:35.592  5748  5748 V BluetoothAdapterState: isTurningOff()=false
,09-19 11:06:35.592  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:35.592  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
,09-19 11:06:35.592  5748  5748 V BluetoothAdapterState: isBleTurningOff()=true
,09-19 11:06:35.593  5748  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-19 11:06:35.594  5748  5828 D BluetoothAdapterProperties: Setting state to 10
09-19 11:06:35.594  5748  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-19 11:06:35.595  5748  5828 I BluetoothAdapterState: Entering OffState
09-19 11:06:35.596   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-19 11:06:35.614  5748  5748 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-19 11:06:35.614  5748  5748 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-19 11:06:35.614  5748  5829 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-19 11:06:35.616  5748  5748 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-19 11:06:35.622  5748  5748 I art     : System.exit called, status: 0
,09-19 11:06:35.622  5748  5748 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-19 11:06:35.647   924  3420 I ActivityManager: Process com.android.bluetooth (pid 5748) has died
,09-19 11:06:38.171  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:38.171  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:39.950   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:40.951   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:41.179  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 11:06:41.179  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a2622c added. We now have 6 listener(s)
,09-19 11:06:41.179  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:41.182  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:41.183  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@71564f5 added. We now have 7 listener(s)
09-19 11:06:41.183  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 11:06:41.186  5632  5678 I System.out: IsBluetoothEnabled
,09-19 11:06:41.194  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:41.220   924   941 I ActivityManager: Start proc 5872:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-19 11:06:41.294  5872  5872 D AdapterServiceConfig: Adding HeadsetService
,09-19 11:06:41.294  5872  5872 D AdapterServiceConfig: Adding A2dpService
09-19 11:06:41.294  5872  5872 D AdapterServiceConfig: Adding HidService
09-19 11:06:41.294  5872  5872 D AdapterServiceConfig: Adding HealthService
,09-19 11:06:41.294  5872  5872 D AdapterServiceConfig: Adding PanService
09-19 11:06:41.295  5872  5872 D AdapterServiceConfig: Adding GattService
09-19 11:06:41.295  5872  5872 D AdapterServiceConfig: Adding BluetoothMapService
09-19 11:06:41.295  5872  5872 D AdapterServiceConfig: Adding SapService
,09-19 11:06:41.305   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a56f89c:true
,09-19 11:06:41.305  5872  5872 D BluetoothAdapterState: make() - Creating AdapterState
,09-19 11:06:41.308  5872  5872 I bt_bluedroid: init
,09-19 11:06:41.308  5872  5884 I BluetoothAdapterState: Entering OffState
,09-19 11:06:41.311  5872  5885 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-19 11:06:41.311  5872  5885 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-19 11:06:41.311  5872  5885 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-19 11:06:41.311  5872  5885 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-19 11:06:41.311  5872  5872 I bt_bluedroid: get_profile_interface socket
,09-19 11:06:41.313  5872  5888 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-19 11:06:41.313  5872  5872 I bt_bluedroid: get_profile_interface sdp
,09-19 11:06:41.314  5872  5888 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-19 11:06:41.317  5872  5883 I bt_bluedroid: config_hci_snoop_log
,09-19 11:06:41.318   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-19 11:06:41.322  5872  5884 D BluetoothAdapterState: Current state: OFF, message: 0
,09-19 11:06:41.322  5872  5884 D BluetoothAdapterProperties: Setting state to 14
09-19 11:06:41.323  5872  5884 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-19 11:06:41.324  5872  5884 D BluetoothBondStateMachine: make
,09-19 11:06:41.326  5872  5889 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-19 11:06:41.328  5872  5884 I BluetoothAdapterState: Entering PendingCommandState
,09-19 11:06:41.329  5872  5872 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-19 11:06:41.331  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
09-19 11:06:41.331  5872  5872 D BtGatt.DebugUtils: handleDebugAction() action=null
09-19 11:06:41.332  5872  5872 D BtGatt.GattService: Received start request. Starting profile...
09-19 11:06:41.332  5872  5872 D BtGatt.GattService: start()
09-19 11:06:41.332  5872  5872 I bt_bluedroid: get_profile_interface gatt
09-19 11:06:41.333  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
09-19 11:06:41.333  5872  5872 D BtGatt.AdvertiseManager: advertise manager created
,09-19 11:06:41.337  5872  5872 V BluetoothAdapterState: isTurningOff()=false
,09-19 11:06:41.337  5872  5872 V BluetoothAdapterState: isTurningOn()=false
09-19 11:06:41.337  5872  5872 V BluetoothAdapterState: isBleTurningOn()=true
09-19 11:06:41.337  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
,09-19 11:06:41.338  5872  5884 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-19 11:06:41.339  5872  5884 I bt_bluedroid: bt_bluedroid
09-19 11:06:41.339  5872  5885 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-19 11:06:41.339  5872  5885 I bt_hci  : start_up
,09-19 11:06:41.344  5872  5885 I bt_vendor: alloc value 0xf416d871
,09-19 11:06:41.344  5872  5885 I bt_vendor: init
09-19 11:06:41.344  5872  5885 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-19 11:06:41.344  5872  5885 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-19 11:06:41.457  5872  5885 D bt_hci  : start_up starting async portion
,09-19 11:06:41.457  5872  5892 I bt_hci  : event_finish_startup
09-19 11:06:41.457  5872  5892 I bt_hci_h4: hal_open
09-19 11:06:41.458  5872  5892 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-19 11:06:41.454  5893  5893 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-19 11:06:41.461  5872  5892 I bt_userial_vendor: device fd = 54 open
,09-19 11:06:41.475  5872  5892 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-19 11:06:41.478  5872  5892 D bt_hwcfg: Chipset BCM4358A3
,09-19 11:06:41.478  5872  5892 D bt_hwcfg: Target name = [BCM4358A3]
09-19 11:06:41.479  5872  5892 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-19 11:06:41.884  5872  5892 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-19 11:06:41.884  5872  5892 D bt_hwcfg: Settlement delay -- 100 ms
09-19 11:06:41.885  5872  5892 I bt_hwcfg: Setting fw settlement delay to 100 
,09-19 11:06:41.952   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:42.018  5872  5892 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-19 11:06:42.018  5872  5892 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-19 11:06:42.020  5872  5892 I bt_hwcfg: vendor lib fwcfg completed
,09-19 11:06:42.020  5872  5892 I bt_vendor: firmware callback
09-19 11:06:42.020  5872  5892 I bt_hci  : firmware_config_callback
,09-19 11:06:42.028  5872  5895 I bt_btu  : btu_task pending for preload complete event
09-19 11:06:42.028  5872  5895 I bt_btu_task: Bluetooth chip preload is complete
,09-19 11:06:42.028  5872  5895 I bt_btu  : btu_task received preload complete event
,09-19 11:06:42.033  5872  5895 I         : BTE_InitTraceLevels -- TRC_HCI
,09-19 11:06:42.034  5872  5895 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-19 11:06:42.034  5872  5895 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-19 11:06:42.034  5872  5895 I         : BTE_InitTraceLevels -- TRC_AVDT
09-19 11:06:42.034  5872  5895 I         : BTE_InitTraceLevels -- TRC_AVRC
09-19 11:06:42.034  5872  5895 I         : BTE_InitTraceLevels -- TRC_A2D
09-19 11:06:42.034  5872  5895 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-19 11:06:42.034  5872  5895 I         : BTE_InitTraceLevels -- TRC_BTM
09-19 11:06:42.034  5872  5895 I         : BTE_InitTraceLevels -- TRC_GAP
09-19 11:06:42.035  5872  5895 I         : BTE_InitTraceLevels -- TRC_PAN
09-19 11:06:42.035  5872  5895 I         : BTE_InitTraceLevels -- TRC_SDP
09-19 11:06:42.035  5872  5895 I         : BTE_InitTraceLevels -- TRC_GATT
09-19 11:06:42.035  5872  5895 I         : BTE_InitTraceLevels -- TRC_SMP
,09-19 11:06:42.035  5872  5895 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-19 11:06:42.035  5872  5895 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-19 11:06:42.114  5872  5895 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40eb549
09-19 11:06:42.114  5872  5895 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40eb549 
,09-19 11:06:42.136  5872  5888 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-19 11:06:42.137  5872  5888 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-19 11:06:42.138  5872  5888 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-19 11:06:42.141  5872  5888 D BluetoothAdapterProperties: Name is: Nexus 6P,
09-19 11:06:42.143  5872  5888 D BluetoothAdapterProperties: Scan Mode:20
09-19 11:06:42.144  5872  5888 D BluetoothAdapterProperties: Discoverable Timeout:120
09-19 11:06:42.144  5872  5888 D bt_hci  : do_postload posting postload work item
09-19 11:06:42.144  5872  5892 I bt_hci  : event_postload
,09-19 11:06:42.144  5872  5892 I bt_vendor: sco_config_cb
09-19 11:06:42.144  5872  5892 I bt_hci  : sco_config_callback postload finished.
09-19 11:06:42.147  5872  5888 D bt_bte_conf: Device ID record 1 : primary
,09-19 11:06:42.148  5872  5888 D bt_bte_conf:   vendorId            = 000f
09-19 11:06:42.148  5872  5888 D bt_bte_conf:   vendorIdSource      = 0001
09-19 11:06:42.148  5872  5888 D bt_bte_conf:   product             = 1200
09-19 11:06:42.148  5872  5888 D bt_bte_conf:   version             = 1436
09-19 11:06:42.148  5872  5888 D bt_bte_conf:   clientExecutableURL = 
09-19 11:06:42.148  5872  5888 D bt_bte_conf:   serviceDescription  = 
09-19 11:06:42.148  5872  5888 D bt_bte_conf:   documentationURL    = 
09-19 11:06:42.148  5872  5888 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-19 11:06:42.149  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:42.149  5872  5885 D bt_stack_manager: event_start_up_stack finished
09-19 11:06:42.150  5872  5884 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-19 11:06:42.150  5872  5884 D BluetoothAdapterProperties: Setting state to 15
09-19 11:06:42.150  5872  5884 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-19 11:06:42.151  5872  5884 I BluetoothAdapterState: Entering BleOnState
,09-19 11:06:42.156  5872  5892 I bt_vendor: low_power_mode_cb
09-19 11:06:42.157  5872  5884 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-19 11:06:42.157  5872  5884 D BluetoothAdapterProperties: Setting state to 11
09-19 11:06:42.157  5872  5884 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-19 11:06:42.164  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:42.165  5872  5872 D HeadsetService: Received start request. Starting profile...
,09-19 11:06:42.166  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:42.170  5872  5872 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-19 11:06:42.170  5872  5872 D HeadsetStateMachine: make
,09-19 11:06:42.181  5872  5872 D HeadsetStateMachine: max_hf_connections = 1
,09-19 11:06:42.181  5872  5872 I bt_bluedroid: get_profile_interface handsfree
09-19 11:06:42.181  5872  5888 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-19 11:06:42.182  5872  5884 I BluetoothAdapterState: Entering PendingCommandState
09-19 11:06:42.184  5872  5888 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-19 11:06:42.186  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
09-19 11:06:42.186  5872  5872 D A2dpService: Received start request. Starting profile...
,09-19 11:06:42.187  5872  5872 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-19 11:06:42.187  5872  5872 I bt_bluedroid: get_profile_interface avrcp
,09-19 11:06:42.194  5872  5872 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-19 11:06:42.194  5872  5872 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-19 11:06:42.194  5872  5872 D A2dpStateMachine: make
09-19 11:06:42.195  5872  5872 I bt_bluedroid: get_profile_interface a2dp
,09-19 11:06:42.196  5872  5888 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-19 11:06:42.199  5872  5872 I BluetoothHidServiceJni: classInitNative: succeeds
,09-19 11:06:42.200  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:42.200  5872  5872 D HidService: Received start request. Starting profile...
09-19 11:06:42.201  5872  5872 I bt_bluedroid: get_profile_interface hidhost
09-19 11:06:42.201  3588  3588 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-19 11:06:42.201  5872  5872 D HidService: setHidService(): set to: null
09-19 11:06:42.201  5872  5888 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40cc56d
09-19 11:06:42.201  5872  5888 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-19 11:06:42.201  5872  5872 I BluetoothHealthServiceJni: classInitNative: succeeds
09-19 11:06:42.201  5872  5903 D A2dpStateMachine: Enter Disconnected: -2
09-19 11:06:42.202  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:42.203  5872  5872 D HealthService: Received start request. Starting profile...
,09-19 11:06:42.204  5872  5872 I bt_bluedroid: get_profile_interface health
,09-19 11:06:42.205  5872  5872 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-19 11:06:42.206  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:42.208  5872  5872 D PanService: Received start request. Starting profile...
09-19 11:06:42.208  5872  5872 D BluetoothPanServiceJni: initializeNative(L110): pan
09-19 11:06:42.208  5872  5872 I bt_bluedroid: get_profile_interface pan
09-19 11:06:42.208  5872  5888 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-19 11:06:42.210  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:42.211  5872  5872 D BluetoothMapService: Received start request. Starting profile...
,09-19 11:06:42.211  5872  5872 D BluetoothMapService: start()
09-19 11:06:42.214  5872  5872 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-19 11:06:42.214  5872  5872 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-19 11:06:42.215  5872  5872 D BluetoothMapAppObserver: createReceiver()
,09-19 11:06:42.216  5872  5872 D BluetoothMapAppObserver: initObservers()
,09-19 11:06:42.216  5872  5872 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-19 11:06:42.222  5872  5872 V SapService: SapBinder()
,09-19 11:06:42.222  5872  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:42.223  5872  5872 D SapService: Received start request. Starting profile...
09-19 11:06:42.223  5872  5872 V SapService: start()
,09-19 11:06:42.224  5872  5872 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:42.224  5872  5872 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:42.224  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
,09-19 11:06:42.224  5872  5901 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-19 11:06:42.224  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
,09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:42.225  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
,09-19 11:06:42.226  5872  5872 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:42.226  5872  5872 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:42.226  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
,09-19 11:06:42.226  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:42.226  5872  5872 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:42.226  5872  5872 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:42.226  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:42.226  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
,09-19 11:06:42.227  5872  5872 V BluetoothAdapterState: isTurningOff()=false
09-19 11:06:42.227  5872  5872 V BluetoothAdapterState: isTurningOn()=true
09-19 11:06:42.227  5872  5872 V BluetoothAdapterState: isBleTurningOn()=false
09-19 11:06:42.227  5872  5872 V BluetoothAdapterState: isBleTurningOff()=false
09-19 11:06:42.227  5872  5884 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-19 11:06:42.228  5872  5884 D BluetoothAdapterProperties: ScanMode =  20
09-19 11:06:42.228  5872  5884 D BluetoothAdapterProperties: State =  11
09-19 11:06:42.228  5872  5884 D BluetoothAdapterProperties: Setting state to 12
09-19 11:06:42.228  5872  5884 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-19 11:06:42.228  5872  5884 I BluetoothAdapterState: Entering OnState
09-19 11:06:42.228  3118  3967 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 11:06:42.230  3118  3130 D BluetoothPbap: onBluetoothStateChange: up=true
09-19 11:06:42.230  5872  5888 D BluetoothAdapterProperties: Scan Mode:21
09-19 11:06:42.232  3118  3118 D BluetoothA2dp: Proxy object connected
09-19 11:06:42.232  5872  5888 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-19 11:06:42.232  5691  5704 D BluetoothPbap: onBluetoothStateChange: up=true
,09-19 11:06:42.234  5691  5703 D BluetoothPan: onBluetoothStateChange on: true
09-19 11:06:42.235   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 11:06:42.236  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:42.236  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:42.236  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:42.236  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:42.236  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:42.236  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:42.236  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:42.236  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:42.236  3118  3967 D BluetoothPan: onBluetoothStateChange on: true
09-19 11:06:42.237  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:42.238  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
09-19 11:06:42.238  3118  3962 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-19 11:06:42.238  3118  3118 D PanProfile: Bluetooth service connected
09-19 11:06:42.239  5691  5703 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 11:06:42.239  3118  3967 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-19 11:06:42.240  3118  3118 D BluetoothInputDevice: Proxy object connected
09-19 11:06:42.240  3118  3118 D HidProfile: Bluetooth service connected
09-19 11:06:42.240  3118  3131 D BluetoothMap: onBluetoothStateChange: up=true
,09-19 11:06:42.241  5872  5872 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-19 11:06:42.242  5691  5704 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 11:06:42.242  5872  5872 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-19 11:06:42.243  5872  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 11:06:42.244  5691  5691 D BluetoothPan: BluetoothPAN Proxy object connected
09-19 11:06:42.244  5691  5691 D PanProfile: Bluetooth service connected
09-19 11:06:42.245   924   941 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 11:06:42.246   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 11:06:42.246   924   924 D BluetoothA2dp: Proxy object connected
,09-19 11:06:42.246  5691  5703 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-19 11:06:42.247  5872  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 11:06:42.248  5691  5691 D BluetoothA2dp: Proxy object connected
09-19 11:06:42.248  5872  5872 D ObexServerSockets: Succeed to create listening sockets 
09-19 11:06:42.248  5872  5872 D ObexServerSockets0: startAccept()
09-19 11:06:42.248  5872  5872 D ObexServerSockets0: prepareForNewConnect()
09-19 11:06:42.250  5872  5872 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-19 11:06:42.250  5872  5872 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-19 11:06:42.252  5872  5910 D ObexServerSockets0: Accepting socket connection...
09-19 11:06:42.252  5691  5909 D BluetoothMap: onBluetoothStateChange: up=true
09-19 11:06:42.252  5872  5911 D ObexServerSockets0: Accepting socket connection...
,09-19 11:06:42.253  3118  3118 D BluetoothMap: Proxy object connected
,09-19 11:06:42.253  3118  3118 D MapProfile: Bluetooth service connected
09-19 11:06:42.253  3118  3118 D BluetoothMap: getConnectedDevices()
09-19 11:06:42.254   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 11:06:42.254  3786  3820 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-19 11:06:42.256  5691  5691 D BluetoothInputDevice: Proxy object connected
09-19 11:06:42.256  5691  5691 D HidProfile: Bluetooth service connected
09-19 11:06:42.256   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
09-19 11:06:42.256  5872  5872 D BluetoothMapService: onReceive
09-19 11:06:42.256  5872  5872 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-19 11:06:42.257  5872  5872 D BluetoothMapService: STATE_ON
,09-19 11:06:42.258  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:42.259  5872  5913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 11:06:42.259  5691  5691 D BluetoothMap: Proxy object connected
09-19 11:06:42.259  5691  5691 D MapProfile: Bluetooth service connected
09-19 11:06:42.260  5691  5691 D BluetoothMap: getConnectedDevices()
09-19 11:06:42.261  5872  5913 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-19 11:06:42.261  5872  5913 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-19 11:06:42.267  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-19 11:06:42.273  3588  3588 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 11:06:42.277  5691  5691 D DockEventReceiver: finishStartingService: stopping service
,09-19 11:06:42.281  5691  5691 D BluetoothPbap: Proxy object connected
09-19 11:06:42.281  5691  5691 D PbapServerProfile: Bluetooth service connected
,09-19 11:06:42.281  5872  5872 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-19 11:06:42.282  5872  5872 D ObexServerSockets0: prepareForNewConnect()
09-19 11:06:42.284  3118  3118 D BluetoothPbap: Proxy object connected
09-19 11:06:42.284  3118  3118 D PbapServerProfile: Bluetooth service connected
,09-19 11:06:42.290  5872  5917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 11:06:42.305  5872  5921 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 11:06:42.306  5872  5921 I BtOppRfcommListener: Accept thread started.
,09-19 11:06:42.338  5691  5909 D BluetoothHeadset: Proxy object connected
,09-19 11:06:42.338  3786  3995 D BluetoothHeadset: Proxy object connected
09-19 11:06:42.339   924   924 D BluetoothHeadset: Proxy object connected
09-19 11:06:42.339   924   924 D BluetoothHeadset: Proxy object connected
09-19 11:06:42.339  3118  3130 D BluetoothHeadset: Proxy object connected
09-19 11:06:42.339  3118  3118 D HeadsetProfile: Bluetooth service connected
09-19 11:06:42.339   924   924 D BluetoothHeadset: Proxy object connected
09-19 11:06:42.339  5691  5703 D BluetoothHeadset: Proxy object connected
,09-19 11:06:42.340  5691  5691 D HeadsetProfile: Bluetooth service connected
,09-19 11:06:42.341  3118  3967 D BluetoothHeadset: Proxy object connected
09-19 11:06:42.341  3118  3118 D HeadsetProfile: Bluetooth service connected
,09-19 11:06:42.342  5691  5691 D HeadsetProfile: Bluetooth service connected
,09-19 11:06:42.346   924   941 D BluetoothHeadset: Proxy object connected
,09-19 11:06:42.354   924   941 D BluetoothHeadset: Proxy object connected
,09-19 11:06:42.355  3786  3818 D BluetoothHeadset: Proxy object connected
,09-19 11:06:42.953   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:43.211  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:43.211  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:43.211  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:43.211  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 11:06:43.211  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:43.211  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:43.211  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:43.211  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 11:06:43.218  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:43.221  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 11:06:43.221  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35cd28a added. We now have 8 listener(s)
09-19 11:06:43.222  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 11:06:43.229   924  3418 D WifiService: setWifiEnabled: false pid=5632, uid=10077
,09-19 11:06:43.229   924  3418 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-19 11:06:43.239  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:43.240   924  3829 D WifiService: setWifiEnabled: true pid=5632, uid=10077
,09-19 11:06:43.240   924  3829 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-19 11:06:43.246   507   917 D SoftapController: Softap fwReload - Ok
,09-19 11:06:43.252   507   917 D CommandListener: Setting iface cfg
09-19 11:06:43.253   507   917 D CommandListener: Trying to bring down wlan0
,09-19 11:06:43.256   507   917 D CommandListener: Clearing all IP addresses on wlan0
,09-19 11:06:43.261   924  2977 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-19 11:06:43.864   924  2977 D wifi    : set interface wlan0 flags (UP)
,09-19 11:06:43.868   924  2977 I WifiHAL : Initializing wifi
,09-19 11:06:43.869   924  2977 I WifiHAL : Creating socket
,09-19 11:06:43.871   924   941 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-19 11:06:43.874   924  2977 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-19 11:06:43.875   924  2977 D wifi    : Did set static halHandle = 0x7f8b748b80
,09-19 11:06:43.875   924  2977 D wifi    : halHandle = 0x7f8b748b80, mVM = 0x7fa7dcd140, mCls = 0x1856
09-19 11:06:43.875   924  2977 D wifi    : array field set
09-19 11:06:43.875   924  2977 I WifiNative-HAL: interface[0] = wlan0
09-19 11:06:43.877   924  5926 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547800517504
,09-19 11:06:43.878   924  5926 D wifi    : waitForHalEvents called, vm = 0x7fa7dcd140, obj = 0x1856, env = 0x7f8bd3a680
,09-19 11:06:43.937  5927  5927 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-19 11:06:43.954   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 11:06:43.958  5927  5927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-19 11:06:43.970  5927  5927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-19 11:06:43.971  5927  5927 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-19 11:06:43.979   924  2977 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-19 11:06:43.985  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:43.992   924  2977 D WifiConfigStore: Loading config and enabling all networks 
,09-19 11:06:43.995  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:43.995  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:43.995  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:43.995  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:43.995  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:43.995  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:43.995  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:43.995  5632  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 11:06:43.997  5632  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:44.001   924  2977 D WifiConfigStore: loaded 0 passpoint configs
,09-19 11:06:44.002   924  2977 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-19 11:06:44.002   924  2977 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-19 11:06:44.003   924  2977 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-19 11:06:44.004   924  2977 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-19 11:06:44.005   924  2977 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-19 11:06:44.005   924  2977 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-19 11:06:44.005   924  2977 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-19 11:06:44.008  5028  5028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-19 11:06:44.008   924  2977 D WifiNative-HAL: Setting external_sim to 1
09-19 11:06:44.009   924  2977 D wifi    : setting dfs flag to true, 0x7f8fd3e600
09-19 11:06:44.009   924  2977 D WifiStateMachine: Setting OUI to DA-A1-19
09-19 11:06:44.009   924  2977 D wifi    : setting scan oui 0x7f8fd3e600
09-19 11:06:44.009   924  2977 D WifiHAL : Sending mac address OUI
,09-19 11:06:44.013   924  2977 E native  : do suspend false
,09-19 11:06:44.020   924   924 D RttService: SCAN_AVAILABLE : 3
09-19 11:06:44.020   924  2977 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-19 11:06:44.020   507   917 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-19 11:06:44.020   924  3081 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-19 11:06:44.021   507   917 D CommandListener: Setting iface cfg
,09-19 11:06:44.025   924  2958 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '140 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 140 Failed to set address (No such device)'
,09-19 11:06:44.025   924  2958 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-19 11:06:44.036   924  2958 D WifiNative-HAL: p2pGetDeviceAddress
,09-19 11:06:44.040   924   939 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=193393 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
09-19 11:06:44.040   924  2958 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-19 11:06:44.261  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 11:06:44.261  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:44.261  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:44.261  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:44.261  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:44.261  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:44.261  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:44.261  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 11:06:44.266  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:44.275  5632  5678 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-19 11:06:44.277  5632  5678 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-19 11:06:44.281  5632  5678 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@69b6962 Bundle[{}]
,09-19 11:06:44.282  5632  5678 I io.jxcore.node.LifeCycleMonitor: start: OK
09-19 11:06:44.282  5632  5678 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-19 11:06:44.283  5632  5678 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-19 11:06:44.284  5632  5678 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-19 11:06:44.285  5632  5678 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-19 11:06:44.287  5632  5678 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-19 11:06:44.295  5632  5678 I System.out: Running OutgoingSocketThread
,09-19 11:06:44.297  5632  5929 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 155)
,09-19 11:06:44.299  5632  5929 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45174
,09-19 11:06:44.299  5632  5929 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-19 11:06:44.954   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 11:06:45.298  5632  5678 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 156)
,09-19 11:06:45.299  5632  5678 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 156)
,09-19 11:06:45.307  5632  5678 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 161)
,09-19 11:06:45.308  5632  5678 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-19 11:06:45.308  5632  5678 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 162)
,09-19 11:06:45.313  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-19 11:06:45.314  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@767e0fb added. We now have 2 listener(s)
,09-19 11:06:45.316  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 11:06:45.316  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.316  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:45.316  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 11:06:45.317  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae97518 added. We now have 9 listener(s)
09-19 11:06:45.317  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:45.317  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 11:06:45.321  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:45.325  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:45.325  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:45.325  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:45.325  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:45.325  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:45.325  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:45.325  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:45.325  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 11:06:45.327  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:45.327  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 11:06:45.328  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 11:06:45.328  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73d8d56 added. We now have 3 listener(s)
09-19 11:06:45.329  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:45.330  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 11:06:45.330  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.330  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-19 11:06:45.332  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:45.331  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 11:06:45.345  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc991d7 added. We now have 10 listener(s)
09-19 11:06:45.345  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:45.346  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:45.346  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:45.346  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:45.346  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.346  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.346  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 11:06:45.346  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:45.346  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@767e0fb removed from the list
09-19 11:06:45.346  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.346  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae97518 removed from the list
09-19 11:06:45.346  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:45.346  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:45.348  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.348  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:45.349  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-19 11:06:45.349  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:45.349  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.349  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae97518 not in the list
,09-19 11:06:45.349  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.349  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:45.350  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:45.350  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:45.350  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.350  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc991d7 removed from the list
09-19 11:06:45.350  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.350  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.350  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:45.350  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:45.351  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73d8d56 removed from the list
09-19 11:06:45.351  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 11:06:45.351  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8ccac4 added. We now have 2 listener(s)
09-19 11:06:45.353  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 11:06:45.353  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.353  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:45.353  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:45.353  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c523dad added. We now have 9 listener(s)
09-19 11:06:45.353  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 11:06:45.354  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 11:06:45.356  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:45.359  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:45.359  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:45.359  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:45.359  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:45.359  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:45.359  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:45.359  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:45.359  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 11:06:45.361  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:45.361  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-19 11:06:45.361  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 11:06:45.361  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2b7473 added. We now have 3 listener(s)
09-19 11:06:45.363  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:45.364  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 11:06:45.364  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.364  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:45.365  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:45.365  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 11:06:45.365  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fedcf30 added. We now have 10 listener(s)
09-19 11:06:45.365  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:45.365  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 11:06:45.365  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 11:06:45.365  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 11:06:45.365  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.365  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 11:06:45.368  5632  5678 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-19 11:06:45.368  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-19 11:06:45.372  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 11:06:45.372  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 11:06:45.373  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-19 11:06:45.376  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-19 11:06:45.376  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 11:06:45.376  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-19 11:06:45.376  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:45.379  5872  5883 D BtGatt.GattService: registerClient() - UUID=fb8a8f1c-8ae0-44e0-8e08-81677da70985
09-19 11:06:45.380  5872  5888 D BtGatt.GattService: onClientRegistered() - UUID=fb8a8f1c-8ae0-44e0-8e08-81677da70985, clientIf=5
09-19 11:06:45.380  5632  5642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-19 11:06:45.381  5872  5912 D BtGatt.GattService: start scan with filters
,09-19 11:06:45.384  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-19 11:06:45.384  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-19 11:06:45.384  5872  5891 D BtGatt.ScanManager: handling starting scan
09-19 11:06:45.385  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-19 11:06:45.385  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-19 11:06:45.386  5872  5891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11fa057
,09-19 11:06:45.387  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-19 11:06:45.387  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 11:06:45.387  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 11:06:45.389  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-19 11:06:45.391  5632  5678 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-19 11:06:45.391  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:45.391  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 11:06:45.391  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.391  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 11:06:45.391  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-19 11:06:45.391  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 11:06:45.391  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 11:06:45.391  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 11:06:45.391  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 11:06:45.391  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-19 11:06:45.392  5872  5888 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-19 11:06:45.392  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.392  5872  5891 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-19 11:06:45.392  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:45.393  5872  5883 D BtGatt.GattService: stopScan() - queue size =1
,09-19 11:06:45.394  5872  5912 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-19 11:06:45.395  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:45.395  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-19 11:06:45.395  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-19 11:06:45.395  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-19 11:06:45.395  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 11:06:45.396  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-19 11:06:45.396  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:45.396  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 11:06:45.396  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:45.397  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:45.398  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:45.398  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.398  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-19 11:06:45.398  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:45.398  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.398  5872  5891 D BtGatt.ScanManager: Starting BLE batch scan
09-19 11:06:45.399  5872  5891 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-19 11:06:45.400  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:45.400  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 11:06:45.400  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:45.400  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.400  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.400  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 11:06:45.400  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:45.400  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:45.400  5632  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-19 11:06:45.400  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8ccac4 removed from the list
09-19 11:06:45.400  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.400  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c523dad removed from the list
09-19 11:06:45.400  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:45.400  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:45.401  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.401  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-19 11:06:45.401  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.401  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:45.402  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:45.402  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:45.402  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.402  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c523dad not in the list
,09-19 11:06:45.405  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-19 11:06:45.406  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 11:06:45.406  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 11:06:45.406  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:45.406  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:45.408  5872  5888 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-19 11:06:45.408  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.408  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:45.408  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.408  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 11:06:45.412  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-19 11:06:45.412  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:45.412  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:45.414  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-19 11:06:45.414  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.414  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-19 11:06:45.414  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.414  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:45.417  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 11:06:45.417  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:45.417  5632  5678 D BluetoothLeScanner: could not find callback wrapper
09-19 11:06:45.417  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-19 11:06:45.417  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:45.418  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:45.418  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.418  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fedcf30 removed from the list
09-19 11:06:45.418  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.418  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.418  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:45.418  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:45.418  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2b7473 removed from the list
09-19 11:06:45.419  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 11:06:45.419  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb05448 added. We now have 2 listener(s)
,09-19 11:06:45.420  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 11:06:45.420  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-19 11:06:45.420  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.420  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.420  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:45.420  5872  5891 D BtGatt.ScanManager: stopping BLe Batch
09-19 11:06:45.420  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:45.420  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27202e1 added. We now have 9 listener(s)
09-19 11:06:45.420  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 11:06:45.421  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 11:06:45.423  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.424  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-19 11:06:45.425  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.425  5872  5891 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-19 11:06:45.425  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:45.425  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:45.425  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:45.425  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:45.425  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:45.425  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:45.425  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:45.425  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:45.427  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:45.427  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 11:06:45.427  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 11:06:45.428  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebc9ec7 added. We now have 3 listener(s)
,09-19 11:06:45.428  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:45.429  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 11:06:45.429  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.429  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:45.429  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:45.429  5872  5888 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-19 11:06:45.429  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a6cf4 added. We now have 10 listener(s)
09-19 11:06:45.429  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.429  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:45.429  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-19 11:06:45.430  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 11:06:45.430  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 11:06:45.430  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 11:06:45.430  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 11:06:45.430  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.430  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 11:06:45.434  5632  5678 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:45.434  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-19 11:06:45.438  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 11:06:45.438  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-19 11:06:45.438  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-19 11:06:45.442  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-19 11:06:45.442  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 11:06:45.442  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-19 11:06:45.443  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:45.445  5872  5882 D BtGatt.GattService: registerClient() - UUID=852fe852-0ba7-488b-a672-cf961b9be2fe
,09-19 11:06:45.445  5872  5888 D BtGatt.GattService: onClientRegistered() - UUID=852fe852-0ba7-488b-a672-cf961b9be2fe, clientIf=5
09-19 11:06:45.445  5632  5642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-19 11:06:45.446  5872  5908 D BtGatt.GattService: start scan with filters
,09-19 11:06:45.447  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-19 11:06:45.448  5872  5891 D BtGatt.ScanManager: handling starting scan
09-19 11:06:45.448  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-19 11:06:45.448  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-19 11:06:45.448  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-19 11:06:45.449  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 11:06:45.450  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 11:06:45.450  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-19 11:06:45.452  5872  5888 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-19 11:06:45.453  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.453  5872  5891 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-19 11:06:45.453  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-19 11:06:45.456  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 11:06:45.456  5632  5678 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-19 11:06:45.456  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:45.456  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:45.456  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:45.456  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.456  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.456  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 11:06:45.456  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:45.456  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb05448 removed from the list
,09-19 11:06:45.456  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.456  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27202e1 removed from the list
09-19 11:06:45.456  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:45.456  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:45.457  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.457  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-19 11:06:45.457  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.457  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:45.459  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-19 11:06:45.459  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.459  5872  5891 D BtGatt.ScanManager: Starting BLE batch scan
09-19 11:06:45.459  5872  5891 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-19 11:06:45.459  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:45.459  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:45.459  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.459  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27202e1 not in the list
09-19 11:06:45.459  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 11:06:45.459  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 11:06:45.459  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 11:06:45.459  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 11:06:45.459  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-19 11:06:45.460  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:45.460  5872  5912 D BtGatt.GattService: stopScan() - queue size =1
,09-19 11:06:45.461  5872  5883 D BtGatt.GattService: unregisterClient() - clientIf=5
09-19 11:06:45.461  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-19 11:06:45.461  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-19 11:06:45.462  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-19 11:06:45.462  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-19 11:06:45.462  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 11:06:45.462  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:45.462  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:45.462  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 11:06:45.462  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:45.463  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:45.464  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:45.464  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:45.464  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.464  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:45.464  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a6cf4 removed from the list
09-19 11:06:45.464  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.464  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.464  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:45.464  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.464  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:45.464  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-19 11:06:45.464  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebc9ec7 removed from the list
09-19 11:06:45.464  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 11:06:45.465  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98f2d19 added. We now have 2 listener(s)
09-19 11:06:45.466  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 11:06:45.466  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.466  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:45.466  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:45.466  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0a01de added. We now have 9 listener(s)
09-19 11:06:45.466  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:45.466  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:45.466  5632  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-19 11:06:45.467  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 11:06:45.468  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.469  5872  5888 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-19 11:06:45.469  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 11:06:45.470  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 11:06:45.472  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-19 11:06:45.472  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 11:06:45.472  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:45.472  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:45.472  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:45.472  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:45.472  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:45.472  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:45.472  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:45.472  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:45.472  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 11:06:45.473  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 11:06:45.474  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-19 11:06:45.474  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.475  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 11:06:45.475  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 11:06:45.475  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 11:06:45.475  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392668c added. We now have 3 listener(s)
09-19 11:06:45.475  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:45.475  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.475  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:45.476  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-19 11:06:45.476  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.476  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:45.476  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:45.476  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9305dea added. We now have 10 listener(s)
09-19 11:06:45.476  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:45.476  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 11:06:45.477  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 11:06:45.477  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 11:06:45.477  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:45.477  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:45.477  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:45.477  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-19 11:06:45.477  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-19 11:06:45.478  5632  5678 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:45.478  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-19 11:06:45.479  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-19 11:06:45.479  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.479  5872  5891 D BtGatt.ScanManager: stopping BLe Batch
09-19 11:06:45.481  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-19 11:06:45.481  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:45.481  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 11:06:45.482  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-19 11:06:45.482  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:45.484  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-19 11:06:45.485  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 11:06:45.485  5872  5891 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-19 11:06:45.485  5632  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 11:06:45.486  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-19 11:06:45.486  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 11:06:45.486  5632  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-19 11:06:45.487  5632  5678 D BluetoothAdapter: STATE_ON
,09-19 11:06:45.488  5872  5882 D BtGatt.GattService: registerClient() - UUID=fffdcb20-98c3-46af-bb8b-15b0a2dbb076
,09-19 11:06:45.489  5872  5888 D BtGatt.GattService: onClientRegistered() - UUID=fffdcb20-98c3-46af-bb8b-15b0a2dbb076, clientIf=5
,09-19 11:06:45.489  5632  5642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-19 11:06:45.489  5872  5888 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-19 11:06:45.489  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.490  5872  5908 D BtGatt.GattService: start scan with filters
09-19 11:06:45.493  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-19 11:06:45.493  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-19 11:06:45.493  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-19 11:06:45.493  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-19 11:06:45.493  5872  5891 D BtGatt.ScanManager: handling starting scan
09-19 11:06:45.495  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 11:06:45.496  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 11:06:45.497  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-19 11:06:45.498  5872  5888 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-19 11:06:45.498  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 11:06:45.498  5872  5891 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-19 11:06:45.499  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 11:06:45.501  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 11:06:45.501  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:45.501  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:45.501  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.501  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.501  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 11:06:45.501  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:45.501  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98f2d19 removed from the list
,09-19 11:06:45.501  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.501  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0a01de removed from the list
09-19 11:06:45.501  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:45.501  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:45.502  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.502  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-19 11:06:45.502  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.502  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:45.503  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:45.503  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:45.503  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.503  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-19 11:06:45.503  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0a01de not in the list
09-19 11:06:45.503  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 11:06:45.503  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.503  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 11:06:45.503  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 11:06:45.503  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 11:06:45.503  5872  5891 D BtGatt.ScanManager: Starting BLE batch scan
09-19 11:06:45.503  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-19 11:06:45.503  5872  5891 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-19 11:06:45.504  5632  5678 D BluetoothAdapter: STATE_ON
09-19 11:06:45.504  5872  5883 D BtGatt.GattService: stopScan() - queue size =1
,09-19 11:06:45.507  5872  5908 D BtGatt.GattService: unregisterClient() - clientIf=5
09-19 11:06:45.507  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 11:06:45.507  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-19 11:06:45.507  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-19 11:06:45.507  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-19 11:06:45.507  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 11:06:45.508  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:45.508  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 11:06:45.508  5632  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 11:06:45.508  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:45.508  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:45.510  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:45.510  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-19 11:06:45.510  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.510  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9305dea removed from the list
09-19 11:06:45.510  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.510  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.510  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:45.510  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:45.510  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:45.510  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.511  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392668c removed from the list
09-19 11:06:45.511  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 11:06:45.511  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 11:06:45.511  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae6eb6 added. We now have 2 listener(s)
09-19 11:06:45.512  5872  5888 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-19 11:06:45.512  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.512  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-19 11:06:45.512  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.512  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:45.512  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:45.513  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c4c7b7 added. We now have 9 listener(s)
09-19 11:06:45.513  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:45.513  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 11:06:45.514  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:45.514  5632  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-19 11:06:45.517  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 11:06:45.517  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-19 11:06:45.517  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.517  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 11:06:45.517  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 11:06:45.518  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 11:06:45.518  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 11:06:45.518  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 11:06:45.520  5632  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 11:06:45.520  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 11:06:45.520  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-19 11:06:45.523  5872  5888 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-19 11:06:45.523  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.523  5872  5891 D BtGatt.ScanManager: stopping BLe Batch
09-19 11:06:45.524  5632  5678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 11:06:45.524  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 11:06:45.524  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 11:06:45.524  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 11:06:45.524  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 11:06:45.524  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 11:06:45.524  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 11:06:45.524  5632  5678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 11:06:45.526  5632  5678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 11:06:45.526  5632  5678 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 11:06:45.526  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 11:06:45.526  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72ac042 added. We now have 3 listener(s)
09-19 11:06:45.528  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 11:06:45.528  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 11:06:45.528  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 11:06:45.528  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 11:06:45.528  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d42853 added. We now have 10 listener(s)
09-19 11:06:45.528  5632  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 11:06:45.528  5872  5888 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-19 11:06:45.528  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.528  5872  5891 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-19 11:06:45.533  5632  5678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 11:06:45.533  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:45.533  5632  5678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 11:06:45.533  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.533  5872  5888 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-19 11:06:45.533  5872  5888 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 11:06:45.533  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.533  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 11:06:45.533  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:45.533  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae6eb6 removed from the list
09-19 11:06:45.533  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 11:06:45.533  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c4c7b7 removed from the list
09-19 11:06:45.533  5632  5678 D io.jxcore.node.ConnectivityMonitor: stop
09-19 11:06:45.533  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 11:06:45.534  5632  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 11:06:45.534  5632  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-19 11:06:45.534  5632  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:45.535  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.535  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-19 11:06:45.536  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-19 11:06:45.536  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:45.536  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.536  5632  5678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c4c7b7 not in the list
09-19 11:06:45.536  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.536  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:45.537  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 11:06:45.537  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 11:06:45.537  5632  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 11:06:45.536  5632  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 11:06:45.537  5632  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d42853 removed from the list
,09-19 11:06:45.537  5632  5678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 11:06:45.537  5632  5678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 11:06:45.537  5632  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-19 11:06:45.537  5632  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 11:06:45.537  5632  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72ac042 removed from the list
09-19 11:06:45.538  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-19 11:06:45.538  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-19 11:06:45.538  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-19 11:06:45.538  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 11:06:45.538  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-19 11:06:45.538  5632  5678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-19 11:06:45.542  5632  5930 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: My test thread name)
09-19 11:06:45.542  5632  5930 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: My test thread name)
09-19 11:06:45.543  5632  5930 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-19 11:06:45.544  5632  5931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: My test thread name)
09-19 11:06:45.544  5632  5931 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: My test thread name)
,09-19 11:06:45.544  5632  5931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-19 11:06:45.546  5632  5678 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-19 11:06:45.546  5632  5678 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-19 11:06:45.546  5632  5678 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-19 11:06:45.546  5632  5678 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-19 11:06:45.546  5632  5678 D com.test.thalitest.ThaliTestRunner: Total duration: 22693 ms
09-19 11:06:45.548  5632  5678 I jxcore-log: Total number of executed tests:  80
09-19 11:06:45.548  5632  5678 I jxcore-log: 
09-19 11:06:45.548  5632  5678 I jxcore-log: Number of passed tests:  80
09-19 11:06:45.548  5632  5678 I jxcore-log: 
09-19 11:06:45.548  5632  5678 I jxcore-log: Number of failed tests:  0
09-19 11:06:45.548  5632  5678 I jxcore-log: 
09-19 11:06:45.548  5632  5678 I jxcore-log: Number of ignored tests:  0
09-19 11:06:45.548  5632  5678 I jxcore-log: 
09-19 11:06:45.548  5632  5678 I jxcore-log: Total duration:  22693
09-19 11:06:45.548  5632  5678 I jxcore-log: 
,09-19 11:06:45.550  5632  5678 I jxcore-log: Unit Test app is loaded
09-19 11:06:45.550  5632  5678 I jxcore-log: 
,09-19 11:06:45.557  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-19 11:06:45.557  5632  5678 I jxcore-log: 
,09-19 11:06:45.559  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-19 11:06:45.559  5632  5678 I jxcore-log: 
,09-19 11:06:45.560  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-19 11:06:45.560  5632  5678 I jxcore-log: 
,09-19 11:06:45.560  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-19 11:06:45.560  5632  5678 I jxcore-log: 
09-19 11:06:45.561  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-19 11:06:45.561  5632  5678 I jxcore-log: 
,09-19 11:06:45.561  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-19 11:06:45.561  5632  5678 I jxcore-log: 
,09-19 11:06:45.562  5632  5632 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,09-19 11:06:45.563  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-19 11:06:45.563  5632  5678 I jxcore-log: 
,09-19 11:06:45.564  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.564  5632  5678 I jxcore-log: 
,09-19 11:06:45.564  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.564  5632  5678 I jxcore-log: 
09-19 11:06:45.564  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.564  5632  5678 I jxcore-log: 
,09-19 11:06:45.565  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.565  5632  5678 I jxcore-log: 
,09-19 11:06:45.565  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-19 11:06:45.565  5632  5678 I jxcore-log: 
,09-19 11:06:45.566  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.566  5632  5678 I jxcore-log: 
,09-19 11:06:45.566  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.566  5632  5678 I jxcore-log: 
09-19 11:06:45.567  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.567  5632  5678 I jxcore-log: 
,09-19 11:06:45.567  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.567  5632  5678 I jxcore-log: 
09-19 11:06:45.567  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.567  5632  5678 I jxcore-log: 
,09-19 11:06:45.568  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.568  5632  5678 I jxcore-log: 
09-19 11:06:45.568  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.568  5632  5678 I jxcore-log: 
,09-19 11:06:45.568  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.568  5632  5678 I jxcore-log: 
09-19 11:06:45.568  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.568  5632  5678 I jxcore-log: 
,09-19 11:06:45.569  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-19 11:06:45.569  5632  5678 I jxcore-log: 
09-19 11:06:45.569  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.569  5632  5678 I jxcore-log: 
,09-19 11:06:45.569  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.569  5632  5678 I jxcore-log: 
09-19 11:06:45.570  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.570  5632  5678 I jxcore-log: 
,09-19 11:06:45.570  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.570  5632  5678 I jxcore-log: 
09-19 11:06:45.570  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.570  5632  5678 I jxcore-log: 
,09-19 11:06:45.571  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.571  5632  5678 I jxcore-log: 
09-19 11:06:45.571  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-19 11:06:45.571  5632  5678 I jxcore-log: 
,09-19 11:06:45.573  5632  5678 I jxcore-log: My device name is: Huawei-Nexus 6P
09-19 11:06:45.573  5632  5678 I jxcore-log: 
,09-19 11:06:45.574  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - WARN testUtils: 'myNameCallback not set!'
09-19 11:06:45.574  5632  5678 I jxcore-log: 
,09-19 11:06:45.915  5632  5632 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-19 11:06:45.925  5632  5678 E jxcore  : Error!: Cannot find module './CoordinatedClient'
09-19 11:06:45.925  5632  5678 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedTape.js","_functionName":"","_lineNumber":"13","_columnNumber":"25","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedTape.js:13:25"}]
,09-19 11:06:45.926  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - ERROR TestsProcess: 'uncaught exception, error: 'Error: Cannot find module './CoordinatedClient'', stack: 'Error: Cannot find module './CoordinatedClient'
09-19 11:06:45.926  5632  5678 I jxcore-log:     at $w._oldRes@module.js:802:9
09-19 11:06:45.926  5632  5678 I jxcore-log:     at $w._resolveFilename@module.js:1771:1
09-19 11:06:45.926  5632  5678 I jxcore-log:     at $w._load@module.js:362:4
09-19 11:06:45.926  5632  5678 I jxcore-log:     at $w.prototype.require@module.js:477:8
09-19 11:06:45.926  5632  5678 I jxcore-log:     at require@module.js:495:8
09-19 11:06:45.926  5632  5678 I jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedTape.js:13:25''
09-19 11:06:45.926  5632  5678 I jxcore-log: 
09-19 11:06:45.927  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-19 11:06:45.927  5632  5678 I jxcore-log: 
09-19 11:06:45.927  5632  5678 E jxcore-log: Error: 
,09-19 11:06:45.927  5632  5678 E jxcore-log: Cannot find module './CoordinatedClient'
09-19 11:06:45.927  5632  5678 E jxcore-log:  (module.js 802:9)
09-19 11:06:45.928  5632  5678 E jxcore-log: 
09-19 11:06:45.930  5632  5678 E jxcore  : Error!: JXcore: Method Doesn't Exist [
09-19 11:06:45.930  5632  5678 E jxcore  : Stack: [{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"309","_columnNumber":"11","_msg":"    at JXMobile.executeJSON@main.js:309:11"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"main.js","_functionName":"unknown","_lineNumber":"309","_columnNumber":"11","_msg":""}]
09-19 11:06:45.930  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-19 11:06:45.930  5632  5678 I jxcore-log: 
,09-19 11:06:45.981  5632  5632 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-19 11:06:45.983  5632  5678 I jxcore-log: 2016-09-19 15:06:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-19 11:06:45.983  5632  5678 I jxcore-log: 
,09-19 11:06:46.037  5632  5632 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-19 11:06:46.038  5632  5678 I jxcore-log: 2016-09-19 15:06:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-19 11:06:46.038  5632  5678 I jxcore-log: 
,09-19 11:06:46.356  5932  5932 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-19 11:06:46.362  5932  5932 D AndroidRuntime: CheckJNI is OFF
,09-19 11:06:46.393  5932  5932 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-19 11:06:46.428  5932  5932 I Radio-JNI: register_android_hardware_Radio DONE
,09-19 11:06:46.446  5932  5932 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-19 11:06:46.456   924   937 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-19 11:06:46.457   924   937 I ActivityManager: Killing 5632:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-19 11:06:46.545   924  2978 D WifiService: Client connection lost with reason: 4
09-19 11:06:46.545   924  3152 I WindowState: WIN DEATH: Window{d31beb6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-19 11:06:46.545   924   934 D GraphicsStats: Buffer count: 2
,09-19 11:06:46.605   924   937 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-19 11:06:46.606   924   937 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-19 11:06:46.606   924   947 I art     : Starting a blocking GC Explicit
,09-19 11:06:46.607   924   937 E ActivityManager: Failure starting process com.test.thalitest
09-19 11:06:46.607   924   937 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-19 11:06:46.607   924   937 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:46.607   924   937 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:46.607   924   937 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 11:06:46.607   924   937 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-19 11:06:46.608   924   937 I ActivityManager:   Force finishing activity ActivityRecord{6f7f0fb u0 com.test.thalitest/.MainActivity t4}
,09-19 11:06:46.615   924   934 W ActivityManager: Spurious death for ProcessRecord{99795c0 0:com.test.thalitest/u0a77}, curProc for 5632: null
,09-19 11:06:46.619   924   942 W WindowManager: Attempted to add application window with unknown token Token{204518 ActivityRecord{6f7f0fb u0 com.test.thalitest/.MainActivity t4 f}}.  Aborting.
,09-19 11:06:46.620   924   942 W WindowManager: Token{204518 ActivityRecord{6f7f0fb u0 com.test.thalitest/.MainActivity t4 f}} already running, starting window not displayed. Unable to add window -- token Token{204518 ActivityRecord{6f7f0fb u0 com.test.thalitest/.MainActivity t4 f}} is not valid; is your activity running?
09-19 11:06:46.620   924   942 W WindowManager: view not successfully added to wm, removing view
09-19 11:06:46.620   924   942 W WindowManager: Exception when adding starting window
09-19 11:06:46.620   924   942 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{4f08fbb V.E...... R.....ID 0,0-0,0} not attached to window manager
09-19 11:06:46.620   924   942 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-19 11:06:46.620   924   942 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-19 11:06:46.620   924   942 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-19 11:06:46.620   924   942 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-19 11:06:46.620   924   942 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-19 11:06:46.620   924   942 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:46.620   924   942 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:46.620   924   942 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 11:06:46.620   924   942 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-19 11:06:46.686   924   947 I art     : Explicit concurrent mark sweep GC freed 24774(1569KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.532ms total 80.109ms
,09-19 11:06:46.705   924   947 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-19 11:06:46.707  5932  5932 I art     : System.exit called, status: 0
,09-19 11:06:46.707  5932  5932 I AndroidRuntime: VM exiting with result code 0.
,09-19 11:06:46.722   924   947 I ActivityManager: Start proc 5942:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-19 11:06:46.722   924   947 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-19 11:06:46.729   924   937 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-19 11:06:46.735  3672  3672 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-19 11:06:46.736  5872  5872 D BluetoothMapAppObserver: onReceive
,09-19 11:06:46.736  5872  5872 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-19 11:06:46.739  4110  4189 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-19 11:06:46.739   924  2942 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-19 11:06:46.772  3403  5955 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-19 11:06:46.774  3672  5954 I Keyboard.Facilitator.DecoderInitializer: run(),
,09-19 11:06:46.783  3786  3786 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-19 11:06:46.784   656   656 W kworker/3:2: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-19 11:06:46.791   656   656 W kworker/3:2: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-19 11:06:46.799  3588  3588 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-19 11:06:46.799  3588  3588 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-19 11:06:46.804   656   656 W kworker/3:2: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-19 11:06:46.808  3672  5954 I Decoder : createOrResetDecoder
09-19 11:06:46.815   924   924 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-19 11:06:46.818  3909  5961 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-19 11:06:46.818  3909  5961 D AccountUtils: Clearing selected account for com.test.thalitest
,09-19 11:06:46.828   924   936 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-19 11:06:46.829  3909  5961 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
09-19 11:06:46.829   924   936 E PackageManager: Failed to write settings, restoring backup
09-19 11:06:46.829   924   936 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-19 11:06:46.829   924   936 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-19 11:06:46.829   924   936 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-19 11:06:46.829   924   936 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-19 11:06:46.829   924   936 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-19 11:06:46.829   924   936 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:46.829   924   936 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:46.829   924   936 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-19 11:06:46.834   924   937 E DropBoxManagerService: Can't write: system_server_wtf
09-19 11:06:46.834   924   937 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-19 11:06:46.834   924   937 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-19 11:06:46.834   924   937 E DropBoxManagerService: 	... 13 more
,09-19 11:06:46.836  3822  3920 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-19 11:06:46.837  3909  5961 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:46.837  3909  5961 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:46.838  3909  5961 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 11:06:46.839  3909  5961 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-19 11:06:46.849   924  3203 I ActivityManager: Start proc 5965:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-19 11:06:46.849  3822  3920 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-19 11:06:46.849  3822  3920 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3822
09-19 11:06:46.849  3822  3920 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:46.849  3822  3920 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-19 11:06:46.853   924  5971 E DropBoxManagerService: Can't write: system_app_crash
09-19 11:06:46.853   924  5971 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-19 11:06:46.853   924  5971 E DropBoxManagerService: 	... 5 more
,09-19 11:06:46.853  3403  3431 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj7B75429A2) - 
,09-19 11:06:46.855   924   934 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-19 11:06:46.860  3822  3920 I Process : Sending signal. PID: 3822 SIG: 9
,09-19 11:06:46.880  3909  5980 I GMPM-SVC: App measurement is starting up
,09-19 11:06:46.882  3588  3588 I ConfigService: onCreate
,09-19 11:06:46.883  3909  5980 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-19 11:06:46.884  3909  5980 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-19 11:06:46.884  3588  5982 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-19 11:06:46.884  3588  5982 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-19 11:06:46.885  3588  5982 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-19 11:06:46.887  3588  5982 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-19 11:06:46.888  3909  5980 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-19 11:06:46.888  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
09-19 11:06:46.888  3909  5980 E GMPM-SVC: Opening the database failed, dropping and recreating it
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:46,.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-19 11:06:46.889  3909  5980 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
09-19 11:06:46.889  3909  5980 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
09-19 11:06:46.889  3909  5980 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
09-19 11:06:46.890  3909  5980 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,09-19 11:06:46.892  3909  4888 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,09-19 11:06:46.894  3909  4888 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
09-19 11:06:46.895  3909  4888 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
09-19 11:06:46.895  3909  4888 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
09-19 11:06:46.896  3909  4888 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
09-19 11:06:46.896  3909  4888 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,09-19 11:06:46.903  3672  5954 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-19 11:06:46.921  3403  3431 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-19 11:06:46.921  3403  3431 E AndroidRuntime: Process: android.process.acore, PID: 3403
09-19 11:06:46.921  3403  3431 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:46.921  3403  3431 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-19 11:06:46.924   924  5986 E DropBoxManagerService: Can't write: system_app_crash
09-19 11:06:46.924   924  5986 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-19 11:06:46.924   924  5986 E DropBoxManagerService: 	... 5 more
,09-19 11:06:46.947  3403  3431 I Process : Sending signal. PID: 3403 SIG: 9
,09-19 11:06:46.963   924  3420 D GraphicsStats: Buffer count: 1
,09-19 11:06:46.964   924  2941 W InputDispatcher: channel '3618a8d com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-19 11:06:46.964   924  2941 E InputDispatcher: channel '3618a8d com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-19 11:06:46.963   924   934 I WindowState: WIN DEATH: Window{3618a8d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-19 11:06:46.964   924   934 W InputDispatcher: Attempted to unregister already unregistered input channel '3618a8d com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-19 11:06:46.968   924  3829 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3822) has died
09-19 11:06:46.969   924  3829 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-19 11:06:46.970   924  3829 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-19 11:06:46.986   924   937 I ActivityManager: Start proc 5987:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-19 11:06:47.034  5987  5987 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:47.034  5987  5987 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-19 11:06:47.035  5987  5987 D AndroidRuntime: Shutting down VM
,09-19 11:06:47.042  5987  5987 E AndroidRuntime: FATAL EXCEPTION: main
09-19 11:06:47.042  5987  5987 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5987
09-19 11:06:47.042  5987  5987 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-19 11:06:47.042  5987  5987 E AndroidRuntime: 	... 10 more
09-19 11:06:47.044   924  3829 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-19 11:06:47.044   924  6000 E DropBoxManagerService: Can't write: system_app_crash
09-19 11:06:47.044   924  6000 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-19 11:06:47.044   924  6000 E DropBoxManagerService: 	... 5 more
09-19 11:06:47.045  5987  5987 I Process : Sending signal. PID: 5987 SIG: 9
,09-19 11:06:47.066   924  3420 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5987) has died
,09-19 11:06:47.067   924  3420 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-19 11:06:47.082   924   937 I ActivityManager: Start proc 6001:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-19 11:06:47.136  6001  6001 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:47.136  6001  6001 E SQLiteDatabase: ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:47.137  6001  6001 D AndroidRuntime: Shutting down VM
,09-19 11:06:47.145  6001  6001 E AndroidRuntime: FATAL EXCEPTION: main
09-19 11:06:47.145  6001  6001 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6001
09-19 11:06:47.145  6001  6001 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-19 11:06:47.145  6001  6001 E AndroidRuntime: 	... 10 more
,09-19 11:06:47.148   924  3418 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-19 11:06:47.148   924  6013 E DropBoxManagerService: Can't write: system_app_crash
09-19 11:06:47.148   924  6013 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-19 11:06:47.148   924  6013 E DropBoxManagerService: 	... 5 more
,09-19 11:06:47.149  6001  6001 I Process : Sending signal. PID: 6001 SIG: 9
,09-19 11:06:47.160   924  3203 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6001) has died
,09-19 11:06:47.161   924  3203 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-19 11:06:47.181   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
